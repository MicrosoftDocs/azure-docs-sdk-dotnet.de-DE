<Type Name="ReceiveMode" FullName="Microsoft.Azure.ServiceBus.ReceiveMode">
  <TypeSignature Language="C#" Value="public enum ReceiveMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ReceiveMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.ReceiveMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ReceiveMode" />
  <TypeSignature Language="F#" Value="type ReceiveMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>0.0.6.0</AssemblyVersion>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="ae00f-101">Gibt das Verhalten des Empfängers.</span><span class="sxs-lookup"><span data-stu-id="ae00f-101">Specifies the behavior of the receiver.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="PeekLock">
      <MemberSignature Language="C#" Value="PeekLock" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.ServiceBus.ReceiveMode PeekLock = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />
      <MemberSignature Language="VB.NET" Value="PeekLock" />
      <MemberSignature Language="F#" Value="PeekLock = 0" Usage="Microsoft.Azure.ServiceBus.ReceiveMode.PeekLock" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ae00f-102">Ermöglicht eine Nachricht empfangen, und nur von Service Bus gelöscht. wenn <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" /> aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="ae00f-102">Allows a message to be received, and only deleted from Service Bus when <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" /> is called.</span></span></summary>
        <remarks><span data-ttu-id="ae00f-103">Dies ist der Standardwert für <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />, und die für garantierte Zustellung verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ae00f-103">This is the default value for <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />, and should be used for guaranteed delivery.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReceiveAndDelete">
      <MemberSignature Language="C#" Value="ReceiveAndDelete" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.ServiceBus.ReceiveMode ReceiveAndDelete = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.ReceiveMode.ReceiveAndDelete" />
      <MemberSignature Language="VB.NET" Value="ReceiveAndDelete" />
      <MemberSignature Language="F#" Value="ReceiveAndDelete = 1" Usage="Microsoft.Azure.ServiceBus.ReceiveMode.ReceiveAndDelete" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>0.0.6.0</AssemblyVersion>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.ReceiveMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="ae00f-104">ReceiveAndDelete Löschen der Nachricht vom Service Bus an, sobald die Nachricht zugestellt wird.</span><span class="sxs-lookup"><span data-stu-id="ae00f-104">ReceiveAndDelete will delete the message from Service Bus as soon as the message is delivered.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>