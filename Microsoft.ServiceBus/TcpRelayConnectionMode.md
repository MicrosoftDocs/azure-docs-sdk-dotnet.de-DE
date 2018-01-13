<Type Name="TcpRelayConnectionMode" FullName="Microsoft.ServiceBus.TcpRelayConnectionMode">
  <TypeSignature Language="C#" Value="public enum TcpRelayConnectionMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TcpRelayConnectionMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.TcpRelayConnectionMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum TcpRelayConnectionMode" />
  <TypeSignature Language="F#" Value="type TcpRelayConnectionMode = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary><span data-ttu-id="f8474-101">Beschreibt den Verbindungsmodus für den <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span><span class="sxs-lookup"><span data-stu-id="f8474-101">Describes the connection mode for the <see cref="T:Microsoft.ServiceBus.NetTcpRelayBinding" />.</span></span> </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Hybrid">
      <MemberSignature Language="C#" Value="Hybrid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Hybrid = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberSignature Language="VB.NET" Value="Hybrid" />
      <MemberSignature Language="F#" Value="Hybrid = 1" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Hybrid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary><span data-ttu-id="f8474-102">Kommunikation ist über die Azure Service Bus-Infrastruktur mittels Relay weitergeleitet, während die Client- und Dienstendpunkte eine direkte Socketverbindung untereinander aushandeln.</span><span class="sxs-lookup"><span data-stu-id="f8474-102">Communication is relayed through the Azure Service Bus infrastructure while the Client and Service endpoints negotiate a direct socket connection to each other.</span></span> <span data-ttu-id="f8474-103">Die Koordination dieser direkten Verbindung wird vom Azure Service Bus-Cloud-Dienst gesteuert.</span><span class="sxs-lookup"><span data-stu-id="f8474-103">The coordination of this direct connection is governed by the Azure Service Bus cloud service.</span></span> <span data-ttu-id="f8474-104">Der Algorithmus für direkte Socketverbindungen kann direkte Verbindungen zwischen zwei Parteien, die sich hinter gegenüberliegenden Firewalls und NAT sit herstellen Geräte.</span><span class="sxs-lookup"><span data-stu-id="f8474-104">The direct socket connection algorithm is capable of establishing direct connections between two parties that sit behind opposing Firewalls and NAT devices.</span></span> <span data-ttu-id="f8474-105">Der Algorithmus verwendet nur ausgehende Verbindungen für Firewallausnahmen und stützt sich auf einen gegenseitigen Vorhersage Algorithmus für NAT-Durchlauf.</span><span class="sxs-lookup"><span data-stu-id="f8474-105">The algorithm uses only outbound connections for Firewall traversal and relies on a mutual port prediction algorithm for NAT traversal.</span></span> <span data-ttu-id="f8474-106">Da der NAT-Traversal-Algorithmus eine sehr eng festgelegten Koordination und eine geschätzte Vorhersage über NAT erwartet abhängig ist, tendenziell der Algorithmus eine sehr hohe Erfolgsrate für die Startseite "und" Small Business-Szenarien mit einer kleinen Anzahl von clients und in die Erfolgsrate mit größeren NATs beeinträchtigt wird.</span><span class="sxs-lookup"><span data-stu-id="f8474-106">Since the NAT traversal algorithm is dependent on a very narrowly timed coordination and a best-guess prediction about the expected NAT behavior, the algorithm tends to have a very high success rate for Home and Small Business scenarios with a small number of clients and degrades in its success rate with larger NATs.</span></span> <span data-ttu-id="f8474-107">Wenn eine direkte Verbindung hergestellt werden kann, wird die relayverbindung automatisch in eine direkte Verbindung ohne Nachrichten- oder Datenverluste aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="f8474-107">If a direct connection can be established, the relayed connection is automatically upgraded to the direct connection without message or data loss.</span></span> <span data-ttu-id="f8474-108">Wenn die direkte Verbindung hergestellt werden kann, weiterhin Daten der Azure Service Bus-Relay durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="f8474-108">If the direct connection cannot be established, data will continue to flow through the Azure Service Bus Relay.</span></span> 
            
            <span data-ttu-id="f8474-109">Dieser Modus erfordert zusätzlich ausgehenden Port 819 für die Vorhersage NAT-Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="f8474-109">This mode additionally requires outbound port 819 for the NAT prediction algorithm.</span></span> <span data-ttu-id="f8474-110">Die meisten persönlichen Firewall-Produkte die ausgehende Socketverbindung, die durch die direkte eingerichtet wird eine Verbindung herstellen Modus benötigen auch eine einmalige Richtlinie-Ausnahme (der persönlichen Windows-Firewall und andere Produkte in der Regel fordert vom Benutzer gewährt werden soll der Benutzer) zur hostanwendung.</span><span class="sxs-lookup"><span data-stu-id="f8474-110">With most personal firewall products, the outbound socket connection that is being established by the direct connect mode will also require a one-time policy exception to be granted by the user (the Windows Personal Firewall and other products will typically prompt the user) to the hosting application.</span></span> 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Relayed">
      <MemberSignature Language="C#" Value="Relayed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceBus.TcpRelayConnectionMode Relayed = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberSignature Language="VB.NET" Value="Relayed" />
      <MemberSignature Language="F#" Value="Relayed = 0" Usage="Microsoft.ServiceBus.TcpRelayConnectionMode.Relayed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.TcpRelayConnectionMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary><span data-ttu-id="f8474-111">Die gesamte Kommunikation wird durch die Azure Service Bus-Cloud mittels Relay weitergeleitet.</span><span class="sxs-lookup"><span data-stu-id="f8474-111">All communication is relayed through the Azure Service Bus cloud.</span></span> <span data-ttu-id="f8474-112">Die SSL-geschützte steuerungsverbindung wird verwendet, um eine weitergeleitete End-to-End-Socketverbindung auszuhandeln, der alle Client-Dienst-Kommunikation durchläuft.</span><span class="sxs-lookup"><span data-stu-id="f8474-112">The SSL-protected control connection is used to negotiate a relayed end-to-end socket connection that all Client-Service communication flows through.</span></span> <span data-ttu-id="f8474-113">Nachdem die Verbindung hergestellt wurde, fungiert die Azure Service Bus-Infrastruktur ähnlich wie eine socketweiterleitungsproxy, die einen bidirektionalen Bytedatenstrom aus.</span><span class="sxs-lookup"><span data-stu-id="f8474-113">After the connection is established, the Azure Service Bus infrastructure acts much like a socket forwarder proxy relaying a bidirectional byte stream.</span></span> <span data-ttu-id="f8474-114">Dieser Modus erfordert zusätzlich ausgehenden Port 819 für die Vorhersage NAT-Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="f8474-114">This mode additionally requires outbound port 819 for the NAT prediction algorithm.</span></span> <span data-ttu-id="f8474-115">Die meisten persönlichen Firewall-Produkte die ausgehende Socketverbindung, die durch die direkte eingerichtet wird eine Verbindung herstellen Modus benötigen auch eine einmalige Richtlinie-Ausnahme (der persönlichen Windows-Firewall und andere Produkte in der Regel fordert vom Benutzer gewährt werden soll der Benutzer) zur hostanwendung.</span><span class="sxs-lookup"><span data-stu-id="f8474-115">With most personal firewall products, the outbound socket connection that is being established by the direct connect mode will also require a one-time policy exception to be granted by the user (the Windows Personal Firewall and other products will typically prompt the user) to the hosting application.</span></span></summary>
      </Docs>
    </Member>
  </Members>
</Type>