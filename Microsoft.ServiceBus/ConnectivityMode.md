<Type Name="ConnectivityMode" FullName="Microsoft.ServiceBus.ConnectivityMode">
  <TypeSignature Language="C#" Value="public enum ConnectivityMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ConnectivityMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.ConnectivityMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum ConnectivityMode" />
  <TypeSignature Language="F#" Value="type ConnectivityMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="49d19-101">Legt das zugrunde liegende auf Übertragungsebene-Protokoll zur Kommunikation mit Service Bus verwendet.</span><span class="sxs-lookup"><span data-stu-id="49d19-101">Sets the underlying wire-level protocol used to communicate with Service Bus.</span></span> </summary>
    <remarks><span data-ttu-id="49d19-102">Der Verbindungsmodus unterscheidet sich von der <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> Protokoll, das der Dienst für die Clientkommunikation angibt.</span><span class="sxs-lookup"><span data-stu-id="49d19-102">The connectivity mode differs from the <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> protocol that the service specifies for client communication.</span></span> <span data-ttu-id="49d19-103">Der Transporttyp wird durch die verwendete Bindung bestimmt.</span><span class="sxs-lookup"><span data-stu-id="49d19-103">The transport type is determined by the binding used.</span></span> <span data-ttu-id="49d19-104">Unabhängig davon, welche <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> Auswahl (NetMessaging oder AMQP), die Kommunikation über den ausgewählten Verbindungsmodus verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="49d19-104">No matter which <see cref="T:Microsoft.ServiceBus.Messaging.TransportType" /> you select (NetMessaging or AMQP), the communication occurs over the selected connectivity mode.</span></span> <span data-ttu-id="49d19-105">Beispielsweise haben Sie AMQP TCP-oder HTTP (S) auftreten.</span><span class="sxs-lookup"><span data-stu-id="49d19-105">For example, you can have AMQP occur over TCP or HTTP(S).</span></span> </remarks>
  </Docs>
  <Members>
    <Member MemberName="AutoDetect">
      <MemberSignature Language="C#" Value="AutoDetect" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode AutoDetect = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberSignature Language="VB.NET" Value="AutoDetect" />
      <MemberSignature Language="F#" Value="AutoDetect = 2" Usage="Microsoft.ServiceBus.ConnectivityMode.AutoDetect" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary><span data-ttu-id="49d19-106">Modus "automatisch erkennen".</span><span class="sxs-lookup"><span data-stu-id="49d19-106">Auto-detect mode.</span></span> <span data-ttu-id="49d19-107">Wählt automatisch zwischen den TCP-, HTTP- und HTTPS-Modi, die basierend auf einem automatischen Erkennungsmechanismus, der prüft, ob beide Verbindungsoptionen für die aktuell Netzwerkumgebung verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="49d19-107">Automatically selects between the TCP, HTTP and HTTPS modes based on an auto-detection mechanism that probes whether either connectivity option is available for the current network environment.</span></span> <span data-ttu-id="49d19-108">Wenn beide verfügbar sind, wird das System TCP wird standardmäßig ausgewählt.</span><span class="sxs-lookup"><span data-stu-id="49d19-108">If both are available, the system will choose TCP by default.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Http">
      <MemberSignature Language="C#" Value="Http" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Http = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberSignature Language="VB.NET" Value="Http" />
      <MemberSignature Language="F#" Value="Http = 0" Usage="Microsoft.ServiceBus.ConnectivityMode.Http" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="49d19-109">HTTP-Modus.</span><span class="sxs-lookup"><span data-stu-id="49d19-109">HTTP mode.</span></span> <span data-ttu-id="49d19-110">Listener versucht, eine HTTP-Verbindung, gefolgt von einer HTTPS-Verbindung mit der Service Bus-Dienst, und Warten auf Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="49d19-110">Listeners attempt an HTTP connection followed by an HTTPS connection with the Service Bus service, then wait for messages.</span></span> <span data-ttu-id="49d19-111">Dadurch möglicherweise, dass Sie problemlos TCP-Port Einschränkungen umgehen.</span><span class="sxs-lookup"><span data-stu-id="49d19-111">This might allow you to more easily work around TCP port constraints.</span></span></summary>
      </Docs>
    </Member>
    <Member MemberName="Https">
      <MemberSignature Language="C#" Value="Https" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Https = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberSignature Language="VB.NET" Value="Https" />
      <MemberSignature Language="F#" Value="Https = 3" Usage="Microsoft.ServiceBus.ConnectivityMode.Https" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary><span data-ttu-id="49d19-112">HTTPS-Modus.</span><span class="sxs-lookup"><span data-stu-id="49d19-112">HTTPS mode.</span></span> <span data-ttu-id="49d19-113">Listener eine HTTPS-Verbindung mit dem Service Bus-Dienst versucht dann Nachrichten warten.</span><span class="sxs-lookup"><span data-stu-id="49d19-113">Listeners attempt an HTTPS connection with the Service Bus service, then wait  for messages.</span></span> </summary>
      </Docs>
    </Member>
    <Member MemberName="Tcp">
      <MemberSignature Language="C#" Value="Tcp" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.ConnectivityMode Tcp = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberSignature Language="VB.NET" Value="Tcp" />
      <MemberSignature Language="F#" Value="Tcp = 1" Usage="Microsoft.ServiceBus.ConnectivityMode.Tcp" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.ConnectivityMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="49d19-114">TCP-Modus (Standard).</span><span class="sxs-lookup"><span data-stu-id="49d19-114">TCP mode (default).</span></span> <span data-ttu-id="49d19-115">Erstellen Sie Listener TCP-Verbindungen mit dem Service Bus-Dienst an einen Zielport im Bereich 9350 bis 9354.</span><span class="sxs-lookup"><span data-stu-id="49d19-115">Listeners create TCP connections to the Service Bus service to a destination port in the range 9350 to 9354.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>