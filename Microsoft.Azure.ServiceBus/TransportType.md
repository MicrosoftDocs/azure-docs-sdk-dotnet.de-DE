<Type Name="TransportType" FullName="Microsoft.Azure.ServiceBus.TransportType">
  <TypeSignature Language="C#" Value="public enum TransportType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.TransportType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportType" />
  <TypeSignature Language="F#" Value="type TransportType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            AMQP-Transporttyp
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Amqp">
      <MemberSignature Language="C#" Value="Amqp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.ServiceBus.TransportType Amqp = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.TransportType.Amqp" />
      <MemberSignature Language="VB.NET" Value="Amqp" />
      <MemberSignature Language="F#" Value="Amqp = 0" Usage="Microsoft.Azure.ServiceBus.TransportType.Amqp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Mithilfe von AMQP über TCP.
            <remarks>Dies ist der Standardwert. Es wird auf Port 5671 ausgeführt.</remarks></summary>
      </Docs>
    </Member>
    <Member MemberName="AmqpWebSockets">
      <MemberSignature Language="C#" Value="AmqpWebSockets" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.ServiceBus.TransportType AmqpWebSockets = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.ServiceBus.TransportType.AmqpWebSockets" />
      <MemberSignature Language="VB.NET" Value="AmqpWebSockets" />
      <MemberSignature Language="F#" Value="AmqpWebSockets = 1" Usage="Microsoft.Azure.ServiceBus.TransportType.AmqpWebSockets" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            AMQP verwendet über WebSockets
            </summary>
        <remarks>Dies wird über Port 443 mit Wss-URI-Schema ausgeführt. Dies kann in Szenarien verwendet werden, in dem Datenverkehr an Port 5671 blockiert ist. Um eine Proxy-Verbindung einrichten, konfigurieren Sie System Standardproxy. Proxy wird derzeit nur in net451 + Framework unterstützt.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>