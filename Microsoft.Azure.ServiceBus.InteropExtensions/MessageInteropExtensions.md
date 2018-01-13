<Type Name="MessageInteropExtensions" FullName="Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions">
  <TypeSignature Language="C#" Value="public static class MessageInteropExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MessageInteropExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MessageInteropExtensions" />
  <TypeSignature Language="F#" Value="type MessageInteropExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             Eine Erweiterung Nachrichtenklasse, die stellt Erweiterungsmethoden bereit, um den Text einer Nachricht zu deserialisieren, die serialisiert und Service Bus-Warteschlange/Thema gesendet wurde mithilfe der Clientbibliothek WindowsAzure.Messaging. Die Clientbibliothek WindowsAzure.Messaging serialisiert Objekte mithilfe der <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> (Serialisierungsprogramm Standard) oder <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> beim Senden der Nachricht. Diese Klasse stellt Erweiterungsmethoden zum Deserialisieren und Abrufen von Text solche Nachrichten bereit.
             </summary>
    <remarks>
             1. Wenn eine Nachricht nur gesendet wird und empfangen, verwenden diese Microsoft.Azure.ServiceBus-Clientbibliothek, die unten Erweiterung Methoden nicht relevant sind, und sollte nicht verwendet werden.
             
            2. Wenn diese Clientbibliothek wird verwendet, um Nachrichten zu empfangen, die mit WindowsAzure.Messaging-Clientbibliothek und diese Bibliothek (Microsoft.Azure.ServiceBus) gesendet wurden, müssen die Benutzer eine Benutzereigenschaft hinzufügen <see cref="P:Microsoft.Azure.ServiceBus.Message.UserProperties" /> beim Senden der Nachricht. Auf die Nachricht empfängt, kann diese Eigenschaft untersucht werden, um zu bestimmen, ob die Nachricht von der Clientbibliothek WindowsAzure.Messaging war und wenn dies der Fall ist, verwenden die Nachricht. GetBody()-Erweiterungsmethode, um den tatsächlichen Text der Nachricht zugeordnete abrufen.
             
             ----------------------------------------------
             <a name="scenarios-to-use-the-getbody-extension-method"></a>Szenarien für die Verwendung von GetBody Erweiterungsmethode:
             ----------------------------------------------
             Wenn die Nachricht mithilfe der Clientbibliothek WindowsAzure.Messaging wie folgt erstellt wurde:
             <code>
            var message1 = new BrokeredMessage("contoso"); // Sending a plain string
             var message2 = new BrokeredMessage(sampleObject); // Sending an actual customer object
             var message3 = new BrokeredMessage(Encoding.UTF8.GetBytes("contoso")); // Sending a UTF8 encoded byte array object
             
             await messageSender.SendAsync(message1);
             await messageSender.SendAsync(message2);
                 await messageSender.SendAsync(message3);
                 </code>
                 
            Klicken Sie dann die ursprünglichen Objekte, die mithilfe dieser Clientbibliothek wie folgt abrufen: (standardmäßig <see cref="T:Microsoft.Azure.ServiceBus.InteropExtensions.DataContractBinarySerializer" /> zum Deserialisieren und Abrufen von Text verwendet werden.
                 Wenn ein Serialisierungsprogramm, andere als die verwendet wurde, übergeben Sie das Serialisierungsprogramm explizit.)
                 <code>
                 var message1 = await messageReceiver.ReceiveAsync();
             var returnedData1 = message1.GetBody&lt;string&gt;();
            
             var message2 = await messageReceiver.ReceiveAsync();
             var returnedData2 = message1.GetBody&lt;SampleObject&gt;();
              
             var message3 = await messageReceiver.ReceiveAsync();
                 var returnedData3Bytes = message1.GetBody&lt;byte[]&gt;();
                 Console.WriteLine($"Message3 String: {Encoding.UTF8.GetString(returnedData3Bytes)}");
            </code>
                 
                 -------------------------------------------------
            <a name="scenarios-to-not-use-the-getbody-extension-method"></a>Szenarien für die Erweiterungsmethode GetBody nicht verwenden:
                 -------------------------------------------------
                 Wenn die Nachricht gesendet wurde, verwenden die Clientbibliothek WindowsAzure.Messaging wie folgt: message4 Var = neue "brokeredmessage" (neue MemoryStream(Encoding.UTF8.GetBytes("contoso"))); "await" messageSender.SendAsync(message4);
                 
             Klicken Sie dann die ursprünglichen Objekte, die mithilfe dieser Clientbibliothek wie folgt abrufen: Var message4 = "await" messageReceiver.ReceiveAsync(); zurückgegebene Zeichenfolge = Encoding.UTF8.GetString (message4. Text); Da die Nachricht als Stream, ohne Deserialisierung erforderlich, hier gesendet wurde.
            
             </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T GetBody&lt;T&gt; (this Microsoft.Azure.ServiceBus.Message message, System.Runtime.Serialization.XmlObjectSerializer serializer = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T GetBody&lt;T&gt;(class Microsoft.Azure.ServiceBus.Message message, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions.GetBody``1(Microsoft.Azure.ServiceBus.Message,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="static member GetBody : Microsoft.Azure.ServiceBus.Message * System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="Microsoft.Azure.ServiceBus.InteropExtensions.MessageInteropExtensions.GetBody (message, serializer)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="message" Type="Microsoft.Azure.ServiceBus.Message" RefType="this" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="message">To be added.</param>
        <param name="serializer">To be added.</param>
        <summary>
            Deserialisiert den Text einer Nachricht, die mit XmlObjectSerializer serialisiert wurde
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>