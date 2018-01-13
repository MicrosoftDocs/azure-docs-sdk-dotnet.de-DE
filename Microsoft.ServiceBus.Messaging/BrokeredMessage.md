<Type Name="BrokeredMessage" FullName="Microsoft.ServiceBus.Messaging.BrokeredMessage">
  <TypeSignature Language="C#" Value="public sealed class BrokeredMessage : IDisposable, System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BrokeredMessage extends System.Object implements class System.IDisposable, class System.Xml.Serialization.IXmlSerializable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BrokeredMessage&#xA;Implements IDisposable, IXmlSerializable" />
  <TypeSignature Language="F#" Value="type BrokeredMessage = class&#xA;    interface IXmlSerializable&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Xml.Serialization.IXmlSerializable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Xml.Serialization.XmlRoot("BrokeredMessage", Namespace="http://schemas.microsoft.com/netservices/2011/06/servicebus")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>Stellt die kommunikationseinheit zwischen Service Bus-Clients dar.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage messageBodyStream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream">Der Nachrichtentext-Streams.</param>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage serializableObject" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="serializableObject">Das Objekt, das in den Nachrichtentext serialisiert werden.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> Klasse aus einem Objekt mit einem binären XmlDictionaryWriter mithilfe von "DataContractSerializer".</summary>
        <remarks>Eine standardmäßige <see cref="T:Microsoft.ServiceBus.Messaging.DataContractBinarySerializer" /> für die Serialisierung des Objekts verwendet wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (System.IO.Stream messageBodyStream, bool ownsStream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream messageBodyStream, bool ownsStream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.IO.Stream,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (messageBodyStream As Stream, ownsStream As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : System.IO.Stream * bool -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (messageBodyStream, ownsStream)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="messageBodyStream" Type="System.IO.Stream" />
        <Parameter Name="ownsStream" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="messageBodyStream">Der Nachrichtentext-Streams.</param>
        <param name="ownsStream">"true", um anzugeben, dass der Stream geschlossen wird, wenn die Nachricht geschlossen wird; "false", um anzugeben, dass der Datenstrom nicht geschlossen wird, wenn die Nachricht geschlossen wird.</param>
        <summary>Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> -Klasse mithilfe des angegebenen Streams als Text.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BrokeredMessage (object serializableObject, System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(object serializableObject, class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.#ctor(System.Object,System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (serializableObject As Object, serializer As XmlObjectSerializer)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.BrokeredMessage : obj * System.Runtime.Serialization.XmlObjectSerializer -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="new Microsoft.ServiceBus.Messaging.BrokeredMessage (serializableObject, serializer)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serializableObject" Type="System.Object" />
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <param name="serializableObject"> Die serializable-Objekt. </param>
        <param name="serializer">         Das Serialisierungsprogrammobjekt. </param>
        <summary> Konstruktor, der von einem Objekt mithilfe der bereitgestellten XmlObjectSerializer eine "brokeredmessage" wird erstellt </summary>
        <remarks> Sie sollten beachten von Ausnahmen sein, dass ihre bereitgestellten Serialisierer auslösen kann, und ergreifen Sie entsprechende Maßnahmen. Finden Sie unter <see href="http://msdn.microsoft.com/en-us/library/ms574055.aspx" /> eine mögliche Liste der Ausnahmen und deren Ursachen. </remarks>
        <exception cref="T:System.ArgumentNullException">Wird ausgelöst, wenn null-Serialisierungsprogramm an die Methode mit einem SerializableObject ungleich Null übergeben wird</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon ()" />
      <MemberSignature Language="F#" Value="member this.Abandon : unit -&gt; unit" Usage="brokeredMessage.Abandon " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Bricht die Sperre für eine Nachricht einsehen gesperrt ab.</summary>
        <remarks> Dieser Vorgang sollte nur für eine Nachricht empfangen, die im Peek / Lock-Modus ausgeführt werden soll.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht im Status "freigegeben wird" oder des Empfängers mit dem die Nachricht empfangen wurde verworfen Zustand.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn ein Timeout eintritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wenn Sie die Sperre zugeordnet diese Nachricht wurde unterbrochen, oder das Sperrtoken nicht gefunden wurde.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wenn diese Nachricht empfangen wurde, aus einer Sitzung und die Sperre der Sitzung zugeordnet ist verloren gegangen.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</exception>
      </Docs>
    </Member>
    <Member MemberName="Abandon">
      <MemberSignature Language="C#" Value="public void Abandon (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Abandon(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Abandon(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abandon (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Abandon : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Abandon propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Bricht die Sperre für eine Nachricht einsehen gesperrt ab.</summary>
        <remarks> Dieser Vorgang sollte nur für eine Nachricht empfangen, die im Peek / Lock-Modus ausgeführt werden soll.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn <list type="bullet"> <item>Meldung wird verworfen Zustand.</item> <item>der Empfänger mit dem die Nachricht wurde empfangen befindet sich in freigegebenem Zustand</item></list></exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn <list type="bullet"> <item>eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen.</item> <item>für eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen</item></list></exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.
                                            <seealso cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /></exception>
        <exception cref="T:System.ServiceModel.CommunicationException">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfangen wurde, nicht mehr in der Message-Server vorhanden ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Abbricht, asynchron die Sperre für eine Nachricht einsehen gesperrt.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AbandonAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task AbandonAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task AbandonAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.AbandonAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function AbandonAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.AbandonAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.AbandonAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Abbricht, asynchron die Sperre für eine Nachricht einsehen gesperrt.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.BrokeredMessage Clone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.ServiceBus.Messaging.BrokeredMessage Clone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Clone" />
      <MemberSignature Language="VB.NET" Value="Public Function Clone () As BrokeredMessage" />
      <MemberSignature Language="F#" Value="member this.Clone : unit -&gt; Microsoft.ServiceBus.Messaging.BrokeredMessage" Usage="brokeredMessage.Clone " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.BrokeredMessage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Klont eine Nachricht an, damit, dass es möglich ist, einen Klon einer Nachricht als eine neue Nachricht zu senden.</summary>
        <returns>Die <see cref="T:Microsoft.ServiceBus.Messaging.BrokeredMessage" /> , das die geklonte Meldung enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="public void Complete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Complete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Complete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Complete ()" />
      <MemberSignature Language="F#" Value="member this.Complete : unit -&gt; unit" Usage="brokeredMessage.Complete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Schließt den Empfangsvorgang einer Nachricht ab und gibt an, dass die Nachricht als verarbeitet gekennzeichnet werden soll und gelöscht.</summary>
        <remarks> Diese Methode wird als ein Handshake zwischen dem Empfänger und die Service Bus für eine Zustellung der Nachricht verwendet. Wenn der Empfänger, die vor dem Aufrufen dieser Methode fehlgeschlagen ist, wird die Nachricht in der Warteschlange beibehalten.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist. LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist. Die Dauer der Sperre ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung. Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</exception>
      </Docs>
    </Member>
    <Member MemberName="CompleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CompleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CompleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.CompleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CompleteAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CompleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.CompleteAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron abgeschlossen wird den Empfangsvorgang einer Nachricht und gibt an, dass die Nachricht als verarbeitet gekennzeichnet werden soll und gelöscht.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Typ des Inhalts fest.</summary>
        <value>Der Typ des Inhalts des Nachrichtentexts. Dies ist ein Content-Type-Bezeichner von Sender und Empfänger für anwendungsspezifische Logik verwendet wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Korrelation.</summary>
        <value>Der Bezeichner der Korrelation.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter ()" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : unit -&gt; unit" Usage="brokeredMessage.DeadLetter " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.DeadLetter propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetter">
      <MemberSignature Language="C#" Value="public void DeadLetter (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeadLetter(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetter(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeadLetter (deadLetterReason As String, deadLetterErrorDescription As String)" />
      <MemberSignature Language="F#" Value="member this.DeadLetter : string * string -&gt; unit" Usage="brokeredMessage.DeadLetter (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason">Der Grund für unzustellbare Nachrichten die Nachricht.</param>
        <param name="deadLetterErrorDescription">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</param>
        <summary>Verschiebt die Nachricht an die Dead Letter-Warteschlange an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status besitzt oder der Empfänger mit dem die Nachricht empfangen wurde befindet sich in freigegebenem Zustand.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</exception>
        <exception cref="T:System.ServiceModel.CommunicationException">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn ein Timeout eintritt. Timeouts wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist. LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist. Sperrdauer Sitzung ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung. Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeadLetterAsync (string deadLetterReason, string deadLetterErrorDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeadLetterAsync(string deadLetterReason, string deadLetterErrorDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeadLetterAsync (deadLetterReason As String, deadLetterErrorDescription As String) As Task" />
      <MemberSignature Language="F#" Value="member this.DeadLetterAsync : string * string -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeadLetterAsync (deadLetterReason, deadLetterErrorDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deadLetterReason" Type="System.String" />
        <Parameter Name="deadLetterErrorDescription" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deadLetterReason">Der Grund für unzustellbare Nachrichten die Nachricht.</param>
        <param name="deadLetterErrorDescription">Die Beschreibungsinformationen für unzustellbare Nachrichten die Nachricht.</param>
        <summary>Asynchron verschiebt die Nachricht an die Dead Letter-Warteschlange.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeadLetterSource">
      <MemberSignature Language="C#" Value="public string DeadLetterSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeadLetterSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeadLetterSource As String" />
      <MemberSignature Language="F#" Value="member this.DeadLetterSource : string" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeadLetterSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer ()" />
      <MemberSignature Language="F#" Value="member this.Defer : unit -&gt; unit" Usage="brokeredMessage.Defer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</summary>
        <remarks>Vor dem Verschieben der Nachrichteninhalts, muss der Benutzer den Empfang der Nachricht für den späteren Abruf reserviert. </remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht im Status "freigegeben" oder der Empfänger mit dem die Nachricht empfangen wurde im Status "freigegeben" wird.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn eine Nachricht, die nicht aus dem e-Mail-Server empfangen wurde aufgerufen oder auf eine Nachricht, die nicht im Peek / Lock-Modus empfangen wurde aufgerufen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Wird ausgelöst, wenn die Warteschlange oder das Abonnement, das die Nachricht empfängt, nicht mehr in der Message-Server vorhanden ist.</exception>
        <exception cref="T:System.TimeoutException">Wird ausgelöst, wenn der Vorgang ein Timeout auftritt. Das Zeitlimit wird initialisiert, durch die <see cref="T:Microsoft.ServiceBus.Messaging.MessagingFactorySettings" />. Sie müssen möglicherweise den Wert erhöhen <see cref="P:Microsoft.ServiceBus.Messaging.MessagingFactorySettings.OperationTimeout" /> um diese Ausnahme zu vermeiden, wenn der Timeoutwert relativ gering ist.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn die Sperre für die Nachricht abgelaufen ist. LockDuration ist eine Entität serverweite Einstellung, und können durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wird ausgelöst, wenn die Sperre für die Sitzung abgelaufen ist. Die Dauer der Sperre ist identisch mit der Nachricht LockDuration und ist eine Entität serverweite Einstellung. Es kann durch initialisiert werden <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.LockDuration" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.LockDuration" /> für Warteschlangen und Abonnements bzw.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.ServerBusyException">Beim Servicebus-Dienst ist ausgelastet und wird nicht verarbeitet die Anforderung.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingEntityNotFoundException">Wenn messaging-Entität die Nachricht von empfangen wurde, wurde gelöscht.</exception>
        <exception cref="T:System.UnauthorizedAccessException">Wenn das Sicherheitstoken, die von der TokenProvider bereitgestellten keine Ansprüche zum Ausführen dieses Vorgangs enthält.</exception>
        <exception cref="T:System.ServiceModel.QuotaExceededException">Bei der die Anzahl gleichzeitiger Verbindungen mit einer Entität nicht überschreiten der maximal zulässige Wert.</exception>
      </Docs>
    </Member>
    <Member MemberName="Defer">
      <MemberSignature Language="C#" Value="public void Defer (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Defer(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Defer(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub Defer (propertiesToModify As IDictionary(Of String, Object))" />
      <MemberSignature Language="F#" Value="member this.Defer : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; unit" Usage="brokeredMessage.Defer propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Gibt an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</summary>
        <remarks>Vor dem Verschieben der Nachrichteninhalts, muss der Benutzer den Empfang der Nachricht für den späteren Abruf reserviert. </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt asynchron an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeferAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeferAsync (System.Collections.Generic.IDictionary&lt;string,object&gt; propertiesToModify);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeferAsync(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; propertiesToModify) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeferAsync(System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Function DeferAsync (propertiesToModify As IDictionary(Of String, Object)) As Task" />
      <MemberSignature Language="F#" Value="member this.DeferAsync : System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.DeferAsync propertiesToModify" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="propertiesToModify" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="propertiesToModify">Die Schlüssel / Wert-Paar-Auflistung von Eigenschaften zu ändern.</param>
        <summary>Gibt asynchron an, dass der Empfänger die Verarbeitung für diese Meldung verzögern möchte.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeliveryCount">
      <MemberSignature Language="C#" Value="public int DeliveryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DeliveryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeliveryCount As Integer" />
      <MemberSignature Language="F#" Value="member this.DeliveryCount : int" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.DeliveryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Anzahl der Übermittlungen ab.</summary>
        <value>Die Anzahl der Übermittlungen.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die Nachricht vom Service Bus nicht zugestellt wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="brokeredMessage.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Führt anwendungsspezifische Aufgaben durch, die mit der Freigabe, der Zurückgabe oder dem Zurücksetzen von nicht verwalteten Ressourcen zusammenhängen.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedSequenceNumber">
      <MemberSignature Language="C#" Value="public long EnqueuedSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 EnqueuedSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.EnqueuedSequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedSequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die in die Warteschlange eingereihten Sequenznummer der Nachricht fest.</summary>
        <value>Die in die Warteschlange eingereihten Sequenznummer der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnqueuedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime EnqueuedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime EnqueuedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnqueuedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.EnqueuedTimeUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt Datum und Uhrzeit der gesendeten Zeit in UTC.</summary>
        <value>Die in die Warteschlange einzureihen Zeit in UTC. Dieser Wert stellt die tatsächliche Zeit des einreihen der Nachricht.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ExpiresAtUtc">
      <MemberSignature Language="C#" Value="public DateTime ExpiresAtUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpiresAtUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpiresAtUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpiresAtUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ExpiresAtUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit in UTC, an dem die Nachricht abläuft festgelegt ist.</summary>
        <value>Die Nachricht Ablaufzeit in UTC.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht nicht von ServerBus übermittelt wurden.</exception>
      </Docs>
    </Member>
    <Member MemberName="ForcePersistence">
      <MemberSignature Language="C#" Value="public bool ForcePersistence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ForcePersistence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberSignature Language="VB.NET" Value="Public Property ForcePersistence As Boolean" />
      <MemberSignature Language="F#" Value="member this.ForcePersistence : bool with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ForcePersistence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert, der angibt, ob die Nachricht in die Datenbank sofort beibehalten werden, statt im Speicher für eine kurze Zeit aufrechterhalten wird. Diese Eigenschaft wird ignoriert, wenn die Nachricht an eine nicht-Express-Warteschlange oder ein Thema gesendet wird.</summary>
        <value>"true", wenn die Nachricht an die Datenbank sofort beibehalten werden, statt für kurze Zeit im Arbeitsspeicher gespeichert werden; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) () As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : unit -&gt; 'T" Usage="brokeredMessage.GetBody " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="T">Der Typ, den der Nachrichtentext deserialisiert werden.</typeparam>
        <summary>Deserialisiert die vermittelte Nachrichtentext in ein Objekt des angegebenen Typs mithilfe der <see cref="T:System.Runtime.Serialization.DataContractSerializer" /> mit einer Binärdatei <see cref="T:System.Xml.XmlDictionaryReader" />.</summary>
        <returns>Das deserialisierte Objekt oder ein Diagramm.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wenn die Nachricht, in verworfen wird wurde bereits Bundesland oder der Textdatenstrom Nachricht verworfen.</exception>
        <exception cref="T:System.InvalidOperationException">Wenn die Nachricht einen null-Textdatenstrom enthält oder den Antworttext-Datenstrom keine Daten oder den Nachrichtentext enthält wurde bereits verwendet.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetBody&lt;T&gt;">
      <MemberSignature Language="C#" Value="public T GetBody&lt;T&gt; (System.Runtime.Serialization.XmlObjectSerializer serializer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance !!T GetBody&lt;T&gt;(class System.Runtime.Serialization.XmlObjectSerializer serializer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.GetBody``1(System.Runtime.Serialization.XmlObjectSerializer)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetBody(Of T) (serializer As XmlObjectSerializer) As T" />
      <MemberSignature Language="F#" Value="member this.GetBody : System.Runtime.Serialization.XmlObjectSerializer -&gt; 'T" Usage="brokeredMessage.GetBody serializer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="serializer" Type="System.Runtime.Serialization.XmlObjectSerializer" />
      </Parameters>
      <Docs>
        <typeparam name="T"> Generische Typparameter. </typeparam>
        <param name="serializer"> Das Serialisierungsprogrammobjekt. </param>
        <summary>Deserialisiert den Text "brokeredmessage" in ein Objekt des angegebenen Typs eine binäre XmlObjectSerializer mit "DataContractSerializer". </summary>
        <returns> Des deserialisierten Objektdiagramms</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException"> Wird ausgelöst, wenn die Nachricht verworfen Status aufweist. </exception>
        <exception cref="T:System.ArgumentNullException"> Wird ausgelöst, wenn mit einem Null-Serialisierungsprogramm-Objekt aufgerufen. </exception>
        <exception cref="T:System.InvalidOperationException"> Wird ausgelöst, wenn die Nachricht eine Null-Textdatenstrom enthält keine Daten enthält oder wenn der Stream einmal (über alle Aufrufe GetBody()) gelesen wurde. </exception>
      </Docs>
    </Member>
    <Member MemberName="IsBodyConsumed">
      <MemberSignature Language="C#" Value="public bool IsBodyConsumed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsBodyConsumed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsBodyConsumed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsBodyConsumed : bool" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.IsBodyConsumed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Gibt an, ob die Nachricht verbraucht wurde.</summary>
        <value>"true", wenn die Meldung verarbeitet wurde; andernfalls "false".</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Label">
      <MemberSignature Language="C#" Value="public string Label { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Label" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberSignature Language="VB.NET" Value="Public Property Label As String" />
      <MemberSignature Language="F#" Value="member this.Label : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Label" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die anwendungsspezifische Bezeichnung.</summary>
        <value>Die anwendungsspezifische Bezeichnung.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="LockedUntilUtc">
      <MemberSignature Language="C#" Value="public DateTime LockedUntilUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LockedUntilUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockedUntilUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LockedUntilUtc : DateTime" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockedUntilUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Datum und die Uhrzeit in UTC bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</summary>
        <value>Das Datum und die Uhrzeit, die bis zu dem die Nachricht in die Warteschlange/Abonnement gesperrt wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die Nachricht aus der Service Bus nicht empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="LockToken">
      <MemberSignature Language="C#" Value="public Guid LockToken { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid LockToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LockToken As Guid" />
      <MemberSignature Language="F#" Value="member this.LockToken : Guid" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.LockToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft das Sperrtoken von Service Bus zugeordnet wird, diese Nachricht ab.</summary>
        <value>Das Sperrtoken von Service Bus zugeordnet wird, diese Nachricht.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die Nachricht aus der Service Bus nicht empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="MessageId">
      <MemberSignature Language="C#" Value="public string MessageId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MessageId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberSignature Language="VB.NET" Value="Public Property MessageId As String" />
      <MemberSignature Language="F#" Value="member this.MessageId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.MessageId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Nachricht fest. Dies ist ein benutzerdefiniertes-Wert, den zum Identifizieren doppelter Meldungen verwendet Service Bus verwenden können, wenn aktiviert.</summary>
        <value>Der Bezeichner der Nachricht.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht in einem freigegebenen Zustand befindet.</exception>
        <exception cref="T:System.ArgumentException">Wird ausgelöst, wenn die Nachrichten-ID null ist oder mehr 128 Zeichen lang sein als.</exception>
      </Docs>
    </Member>
    <Member MemberName="PartitionKey">
      <MemberSignature Language="C#" Value="public string PartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.PartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.PartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert einen Partitionsschlüssel für das Senden einer transaktionalen Nachricht an eine Warteschlange oder ein Thema, das nicht für Sitzungen aktivierte ist.</summary>
        <value>Der Partitionsschlüssel für eine transaktionale Nachricht senden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, obj&gt;" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den anwendungsspezifischen Meldungseigenschaften ab.</summary>
        <value>Die anwendungsspezifischen Meldungseigenschaften.</value>
        <remarks>Die Größe der einzelnen Property-Objekt in der Eigenschaftensammlung darf 32 KB nicht überschreiten.
            Der gemeinsame Größe die Eigenschaftensammlung darf 64 KB nicht überschreiten.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLock">
      <MemberSignature Language="C#" Value="public void RenewLock ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RenewLock() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" />
      <MemberSignature Language="VB.NET" Value="Public Sub RenewLock ()" />
      <MemberSignature Language="F#" Value="member this.RenewLock : unit -&gt; unit" Usage="brokeredMessage.RenewLock " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erneuert die Sperre für eine Nachricht an.</summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingException">Wenn <see cref="P:Microsoft.ServiceBus.Messaging.MessagingException.IsTransient" /> ist "true", können Sie den Vorgang sofort wiederholen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessagingCommunicationException">Sie können sofort den Vorgang wiederholen.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException">Wird ausgelöst, wenn Sie aufgerufen haben <see cref="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLock" /> zu spät. In einer Sitzung wird dies niemals ausgelöst.</exception>
        <exception cref="T:Microsoft.ServiceBus.Messaging.SessionLockLostException">Wird ausgelöst, anstelle von <see cref="T:Microsoft.ServiceBus.Messaging.MessageLockLostException" /> ist die Nachricht aus einer <see cref="T:Microsoft.ServiceBus.Messaging.MessageSession" />.</exception>
      </Docs>
    </Member>
    <Member MemberName="RenewLockAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RenewLockAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RenewLockAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.RenewLockAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function RenewLockAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.RenewLockAsync : unit -&gt; System.Threading.Tasks.Task" Usage="brokeredMessage.RenewLockAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Die Sperre für eine Nachricht erneuert asynchron.</summary>
        <returns>Das asynchrone Ergebnis des Vorgangs.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplyTo">
      <MemberSignature Language="C#" Value="public string ReplyTo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyTo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyTo As String" />
      <MemberSignature Language="F#" Value="member this.ReplyTo : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyTo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Adresse der Warteschlange, an die geantwortet.</summary>
        <value>Die Antwort auf die Adresse.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ReplyToSessionId">
      <MemberSignature Language="C#" Value="public string ReplyToSessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplyToSessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplyToSessionId As String" />
      <MemberSignature Language="F#" Value="member this.ReplyToSessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ReplyToSessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ermittelt oder definiert die Sitzungs-ID, um zu antworten.</summary>
        <value>Die Sitzungs-ID, an die geantwortet werden soll.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ScheduledEnqueueTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime ScheduledEnqueueTimeUtc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduledEnqueueTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.ScheduledEnqueueTimeUtc : DateTime with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ScheduledEnqueueTimeUtc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt das Datum und die Uhrzeit in UTC, an dem die Nachricht in die Warteschlange eingereiht werden. Diese Eigenschaft gibt die Zeit in UTC; Wenn die Eigenschaft festlegen, muss der angegebene DateTime-Wert auch in UTC.</summary>
        <value>Die geplante Enqueue-Zeit in UTC. Dieser Wert ist für das verzögerte zu nachrichtensenden. Es wird verwendet, um Nachrichten senden zu einem bestimmten Zeitpunkt in der Zukunft zu verzögern.</value>
        <remarks> Zeitpunkt der Enquing bedeutet nicht, dass die Nachricht zur gleichen Zeit gesendet wird. Erhalten sie in die Warteschlange eingereiht, aber tatsächliche sendende erforderliche Zeit hängt von der Warteschlange arbeitsauslastung und den Zustand. <seealso cref="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.EnqueuedTimeUtc" /></remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der übergebene Wert DateTime.MaxValue ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SequenceNumber">
      <MemberSignature Language="C#" Value="public long SequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SequenceNumber" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.SequenceNumber : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SequenceNumber" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen.</summary>
        <value>Die eindeutige Nummer, die eine Nachricht vom Servicebus zugewiesen wird.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die Nachricht nicht aus dem e-Mail-Server empfangen wurde.</exception>
      </Docs>
    </Member>
    <Member MemberName="SessionId">
      <MemberSignature Language="C#" Value="public string SessionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SessionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SessionId As String" />
      <MemberSignature Language="F#" Value="member this.SessionId : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.SessionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Bezeichner der Sitzung fest.</summary>
        <value>Der Bezeichner der Sitzung.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public long Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As Long" />
      <MemberSignature Language="F#" Value="member this.Size : int64" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Größe der Nachricht in Bytes ab.</summary>
        <value>Die Nachrichtengröße in Byte.</value>
        <remarks>Der Wert der Größe ist nur genau, nachdem die Instanz "brokeredmessage" gesendet oder empfangen wird.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessageState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessageState State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As MessageState" />
      <MemberSignature Language="F#" Value="member this.State : Microsoft.ServiceBus.Messaging.MessageState" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Status der Nachricht fest.</summary>
        <value>Der Status der Nachricht.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.GetSchema">
      <MemberSignature Language="C#" Value="System.Xml.Schema.XmlSchema IXmlSerializable.GetSchema ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Xml.Schema.XmlSchema System.Xml.Serialization.IXmlSerializable.GetSchema() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#GetSchema" />
      <MemberSignature Language="VB.NET" Value="Function GetSchema () As XmlSchema Implements IXmlSerializable.GetSchema" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.GetSchema</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Xml.Schema.XmlSchema</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Diese Methode ist reserviert und sollte nicht verwendet werden. Wenn Sie die IXmlSerializable-Schnittstelle implementieren, sollten Sie null (Nothing in Visual Basic) von dieser Methode zurückgeben und stattdessen angeben eines benutzerdefinierten Schemas erforderlich ist, gelten die XmlSchemaProviderAttribute für die Klasse.</summary>
        <returns>Ein XmlSchema, das die XML-Darstellung des Objekts beschreibt, die von der Methode WriteXml und von der ReadXml-Methode genutzt wird.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.ReadXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.ReadXml (System.Xml.XmlReader reader);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.ReadXml(class System.Xml.XmlReader reader) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#ReadXml(System.Xml.XmlReader)" />
      <MemberSignature Language="VB.NET" Value="Sub ReadXml (reader As XmlReader) Implements IXmlSerializable.ReadXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.ReadXml(System.Xml.XmlReader)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="reader" Type="System.Xml.XmlReader" />
      </Parameters>
      <Docs>
        <param name="reader">Der XmlReader-Datenstrom, aus dem das Objekt deserialisiert wird.</param>
        <summary>Generiert ein Objekt aus seiner XML-Darstellung. Diese Methode ist für die interne Verwendung reserviert und sollte nicht verwendet werden direkt oder indirekt (z. B. über ein Serialisierungsprogramm oder ein Formatierungsprogramm).</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Xml.Serialization.IXmlSerializable.WriteXml">
      <MemberSignature Language="C#" Value="void IXmlSerializable.WriteXml (System.Xml.XmlWriter writer);" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void System.Xml.Serialization.IXmlSerializable.WriteXml(class System.Xml.XmlWriter writer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.System#Xml#Serialization#IXmlSerializable#WriteXml(System.Xml.XmlWriter)" />
      <MemberSignature Language="VB.NET" Value="Sub WriteXml (writer As XmlWriter) Implements IXmlSerializable.WriteXml" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Xml.Serialization.IXmlSerializable.WriteXml(System.Xml.XmlWriter)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="writer" Type="System.Xml.XmlWriter" />
      </Parameters>
      <Docs>
        <param name="writer">Der XmlWriter-Datenstrom, der das Objekt serialisiert wird.</param>
        <summary>Konvertiert ein Objekt in seine XML-Darstellung. Diese Methode ist für die interne Verwendung reserviert und sollte nicht verwendet werden, direkt oder indirekt (z. B. ein Serialisierungsprogramm oder ein Formatierungsprogramm verwenden).</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public TimeSpan TimeToLive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeToLive As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : TimeSpan with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt die Nachricht TTL-Wert. Hierbei handelt es sich um den Zeitraum, nach dem Ablauf die Nachricht beginnend ab dem Zeitpunkt der Nachricht an den Servicebus gesendet wird. Nachrichten, die älter als ihr TimeToLive-Wert abläuft und nicht länger im Nachrichtenspeicher beibehalten. Abonnenten werden können abgelaufene Nachrichten empfangen. TimeToLive ist die maximale Lebensdauer, die eine Nachricht empfangen kann, aber der Wert darf nicht die angegebene Entität überschreiten die <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" /> Wert an die Zielwarteschlange oder das Abonnement. Wenn Sie ein niedriger TimeToLive-Wert angegeben wird, wird er auf die einzelne Nachricht angewendet werden. Ein höheren Wert für die Nachricht angegebenen wird jedoch durch die Entität DefaultMessageTimeToLive Wert überschrieben werden.</summary>
        <value>Die Nachricht Gültigkeitsdauerwert.</value>
        <remarks>Wenn die Gültigkeitsdauer (TTL) für eine Nachricht festlegen, indem der Absender das Ziel Gültigkeitsdauer (TTL) überschreitet, werden Gültigkeitsdauer der Nachricht durch die neuere Version überschrieben.
            Finden Sie unter <see cref="P:Microsoft.ServiceBus.Messaging.QueueDescription.DefaultMessageTimeToLive" />, <see cref="P:Microsoft.ServiceBus.Messaging.TopicDescription.DefaultMessageTimeToLive" /> und <see cref="P:Microsoft.ServiceBus.Messaging.SubscriptionDescription.DefaultMessageTimeToLive" /> erfahren Sie mehr über das Nachrichten-TTL auf eine Entitätsebene steuern.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
        <exception cref="T:System.ArgumentOutOfRangeException">Wird ausgelöst, wenn der übergebene Wert kleiner als oder gleich TimeSpan.Zero ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="To">
      <MemberSignature Language="C#" Value="public string To { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string To" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberSignature Language="VB.NET" Value="Public Property To As String" />
      <MemberSignature Language="F#" Value="member this.To : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.To" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt senden zu Adresse.</summary>
        <value>Die Adresse des Empfängers.</value>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ObjectDisposedException">Wird ausgelöst, wenn die Nachricht verworfen Status aufweist.</exception>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.BrokeredMessage.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="brokeredMessage.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Gibt eine Zeichenfolge, die die aktuelle Nachricht darstellt.</summary>
        <returns>Die Zeichenfolgendarstellung der aktuellen Nachricht.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ViaPartitionKey">
      <MemberSignature Language="C#" Value="public string ViaPartitionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ViaPartitionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property ViaPartitionKey As String" />
      <MemberSignature Language="F#" Value="member this.ViaPartitionKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.BrokeredMessage.ViaPartitionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt einen Wert für den Partitionsschlüssel wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</summary>
        <value>Der partitionsschlüsselwert wird eine Transaktion zum Senden von Nachrichten über eine Übertragungswarteschlange verwendet werden.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>