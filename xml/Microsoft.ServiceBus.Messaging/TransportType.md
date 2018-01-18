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
    <summary><span data-ttu-id="a5b98-101">Eine Enumeration, die den messaging-Protokoll NetMessaging (ein proprietäres Protokoll mit Azure Service Bus) oder AMQP (einen Industriestandard) festlegt.</span><span class="sxs-lookup"><span data-stu-id="a5b98-101">An enumeration that sets the messaging protocol to either NetMessaging (a proprietary protocol to Azure Service Bus) or AMQP (an industry standard).</span></span></summary>
    <remarks><span data-ttu-id="a5b98-102">Obwohl NetMessaging der Standardwert ist, ist AMQP das bevorzugte Protokoll an.</span><span class="sxs-lookup"><span data-stu-id="a5b98-102">Although NetMessaging is the default value, AMQP is the preferred protocol.</span></span> <span data-ttu-id="a5b98-103">Unabhängig davon, welche Transporttyp (NetMessaging oder AMQP), wählen die Kommunikation erfolgt über den ausgewählten <see cref="T:Microsoft.ServiceBus.ConnectivityMode" />.</span><span class="sxs-lookup"><span data-stu-id="a5b98-103">No matter which transport type you select (NetMessaging or AMQP), the communication occurs over the selected <see cref="T:Microsoft.ServiceBus.ConnectivityMode" />.</span></span> <span data-ttu-id="a5b98-104">Beispielsweise haben Sie AMQP TCP-oder HTTP (S) auftreten.</span><span class="sxs-lookup"><span data-stu-id="a5b98-104">For example, you can have AMQP occur over TCP or HTTP(S).</span></span></remarks>
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
        <summary><span data-ttu-id="a5b98-105">Der Transporttyp des Advanced Message Queuing Protocol (AMQP).</span><span class="sxs-lookup"><span data-stu-id="a5b98-105">The Advanced Message Queuing Protocol (AMQP) transport type.</span></span></summary>
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
        <summary><span data-ttu-id="a5b98-106">Typ des Netzwerks messaging-Transport.</span><span class="sxs-lookup"><span data-stu-id="a5b98-106">The network messaging transport type.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>