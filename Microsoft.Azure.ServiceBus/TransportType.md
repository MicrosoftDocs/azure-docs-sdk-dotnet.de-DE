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
            <span data-ttu-id="787b1-101">AMQP-Transporttyp</span><span class="sxs-lookup"><span data-stu-id="787b1-101">AMQP Transport Type</span></span>
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
            <span data-ttu-id="787b1-102">Mithilfe von AMQP über TCP.</span><span class="sxs-lookup"><span data-stu-id="787b1-102">Uses AMQP over TCP.</span></span>
            <span data-ttu-id="787b1-103"><remarks>Dies ist der Standardwert. Es wird auf Port 5671 ausgeführt.</remarks></span><span class="sxs-lookup"><span data-stu-id="787b1-103"><remarks>This is the default value. It runs on port 5671. </remarks></span></span></summary>
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
            <span data-ttu-id="787b1-104">AMQP verwendet über WebSockets</span><span class="sxs-lookup"><span data-stu-id="787b1-104">Uses AMQP over WebSockets</span></span>
            </summary>
        <remarks><span data-ttu-id="787b1-105">Dies wird über Port 443 mit Wss-URI-Schema ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="787b1-105">This runs on port 443 with wss URI scheme.</span></span> <span data-ttu-id="787b1-106">Dies kann in Szenarien verwendet werden, in dem Datenverkehr an Port 5671 blockiert ist.</span><span class="sxs-lookup"><span data-stu-id="787b1-106">This could be used in scenarios where traffic to port 5671 is blocked.</span></span> <span data-ttu-id="787b1-107">Um eine Proxy-Verbindung einrichten, konfigurieren Sie System Standardproxy.</span><span class="sxs-lookup"><span data-stu-id="787b1-107">To setup a proxy connection, please configure system default proxy.</span></span> <span data-ttu-id="787b1-108">Proxy wird derzeit nur in net451 + Framework unterstützt.</span><span class="sxs-lookup"><span data-stu-id="787b1-108">Proxy currently is supported only in net451+ framework.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>