<Type Name="TransportType" FullName="Microsoft.ServiceBus.Messaging.TransportType">
  <TypeSignature Language="C#" Value="public enum TransportType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TransportType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.TransportType" />
  <TypeSignature Language="VB.NET" Value="Public Enum TransportType" />
  <TypeSignature Language="F#" Value="type TransportType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>Eine Enumeration, die den messaging-Protokoll NetMessaging (ein proprietäres Protokoll mit Azure Service Bus) oder AMQP (einen Industriestandard) festlegt.</summary>
    <remarks>Obwohl NetMessaging der Standardwert ist, ist AMQP das bevorzugte Protokoll an. Unabhängig davon, welche Transporttyp (NetMessaging oder AMQP), wählen die Kommunikation erfolgt über den ausgewählten <see cref="T:Microsoft.ServiceBus.ConnectivityMode" />. Beispielsweise haben Sie AMQP TCP-oder HTTP (S) auftreten.</remarks>
    <altmember cref="T:Microsoft.ServiceBus.ConnectivityMode" />
  </Docs>
  <Members>
    <Member MemberName="Amqp">
      <MemberSignature Language="C#" Value="Amqp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.TransportType Amqp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TransportType.Amqp" />
      <MemberSignature Language="VB.NET" Value="Amqp" />
      <MemberSignature Language="F#" Value="Amqp = 1" Usage="Microsoft.ServiceBus.Messaging.TransportType.Amqp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>Der Transporttyp des Advanced Message Queuing Protocol (AMQP).</summary>
      </Docs>
    </Member>
    <Member MemberName="NetMessaging">
      <MemberSignature Language="C#" Value="NetMessaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.Messaging.TransportType NetMessaging = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" />
      <MemberSignature Language="VB.NET" Value="NetMessaging" />
      <MemberSignature Language="F#" Value="NetMessaging = 0" Usage="Microsoft.ServiceBus.Messaging.TransportType.NetMessaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.TransportType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>Typ des Netzwerks messaging-Transport.</summary>
      </Docs>
    </Member>
  </Members>
</Type>