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
            Gibt das Verhalten des Empfängers.
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
        <summary>Ermöglicht eine Nachricht empfangen, und nur von Service Bus gelöscht. wenn <see cref="M:Microsoft.Azure.ServiceBus.Core.IReceiverClient.CompleteAsync(System.String)" /> aufgerufen wird.</summary>
        <remarks>Dies ist der Standardwert für <see cref="T:Microsoft.Azure.ServiceBus.ReceiveMode" />, und die für garantierte Zustellung verwendet werden soll.</remarks>
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
        <summary>ReceiveAndDelete Löschen der Nachricht vom Service Bus an, sobald die Nachricht zugestellt wird.</summary>
      </Docs>
    </Member>
  </Members>
</Type>