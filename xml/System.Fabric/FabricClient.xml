<Type Name="FabricClient" FullName="System.Fabric.FabricClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit FabricClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type FabricClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1201:ElementsMustAppearInTheCorrectOrder", Justification="Preserve order of public members from V1.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1204:StaticElementsMustAppearBeforeInstanceElements", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.OrderingRules", "SA1202:ElementsMustBeOrderedByAccess", Justification="Current grouping improves readability.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="280ef-101">Erstellt und verwaltet Service Fabric-Dienste oder andere Einrichtungen weitergeben.</span><span class="sxs-lookup"><span data-stu-id="280ef-101">Creates and manages Service Fabric services and other entities.</span></span></para>
    </summary>
    <remarks>
      <para><span data-ttu-id="280ef-102">Es wird dringend empfohlen, dass Sie so weit wie möglich FabricClients freigeben.</span><span class="sxs-lookup"><span data-stu-id="280ef-102">It is highly recommended that you share FabricClients as much as possible.</span></span>
                <span data-ttu-id="280ef-103">Dies ist, da die FabricClient mehrere Optimierungen verwendet, wie z. B. caching und Batchverarbeitung, dass Sie nicht vollständig nutzen Sie andernfalls wäre.</span><span class="sxs-lookup"><span data-stu-id="280ef-103">This is because the FabricClient has multiple optimizations such as caching and batching that you would not be able to fully utilize otherwise.</span></span>
                </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.FabricClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="280ef-104">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class.</span></span> <span data-ttu-id="280ef-105">Dieser Konstruktor sollte von Code verwendet werden, die innerhalb des Clusters ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="280ef-105">This constructor should be used by code that is running inside the cluster.</span></span> <span data-ttu-id="280ef-106">Sie können die <see cref="T:System.Fabric.FabricClient" /> Instanz für die Verbindung mit dem Cluster über den lokalen Gateway-Dienst auf demselben Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="280ef-106">It allows the <see cref="T:System.Fabric.FabricClient" /> instance to connect to the cluster via the local Gateway service running on the same node.</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="280ef-107">Da dieser Konstruktor den lokalen Gateway-Dienst auf demselben Knoten ausgeführt für th-Cluster die Verbindung verwendet wird, kann der Client einen zusätzlicher Netzwerkhop umgangen werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-107">Since this constructor uses the local Gateway service running on the same node to connect to th cluster, your client can bypass an extra network hop.</span></span> <span data-ttu-id="280ef-108">Zur Verbindung mit eines Clusters aus Code außerhalb eines Clusters ausgeführt wird, verwenden Sie einen anderen Konstruktor explizit die Verbindungsparameter angeben können.</span><span class="sxs-lookup"><span data-stu-id="280ef-108">To connect to a cluster from code running outside the cluster, use a different constructor which allows you to explicitly specify the connection parameters.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientRole clientRole);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.FabricClientRole clientRole) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientRole)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientRole As FabricClientRole)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientRole -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient clientRole" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientRole" Type="System.Fabric.FabricClientRole" />
      </Parameters>
      <Docs>
        <param name="clientRole">
          <para><span data-ttu-id="280ef-109">Die Fabric-Client-Rolle.</span><span class="sxs-lookup"><span data-stu-id="280ef-109">The fabric client role.</span></span></para>
        </param>
        <summary>
          <para>
            <span data-ttu-id="280ef-110">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit den angegebenen Client fabricrolle - <see cref="T:System.Fabric.FabricClientRole" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-110">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with the specified fabric client role - <see cref="T:System.Fabric.FabricClientRole" />.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient settings" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="280ef-111">Die Fabric-Clienteinstellungen, die von den Fabric-Client verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="280ef-111">The fabric client settings used by the fabric client.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-112">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit den gewünschten <see cref="T:System.Fabric.FabricClientSettings" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-112">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with the desired <see cref="T:System.Fabric.FabricClientSettings" />.</span></span> <span data-ttu-id="280ef-113">Wenn die <see cref="T:System.Fabric.FabricClient" /> auf demselben Cluster wie der Dienst ist, dann verwenden Sie eine lokale <see cref="T:System.Fabric.FabricClient" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-113">If the <see cref="T:System.Fabric.FabricClient" /> is on the same cluster as the service, then use a Local <see cref="T:System.Fabric.FabricClient" />.</span></span> <span data-ttu-id="280ef-114">Lokale <see cref="T:System.Fabric.FabricClient" /> ist ein Feature von Service Fabric, das ermöglicht die <see cref="T:System.Fabric.FabricClient" /> für die Verbindung mit dem lokalen Gateway-Dienst anstelle von aus einer Liste auswählen.</span><span class="sxs-lookup"><span data-stu-id="280ef-114">Local <see cref="T:System.Fabric.FabricClient" /> is a feature of Service Fabric that allows the <see cref="T:System.Fabric.FabricClient" /> to connect to the local Gateway Service instead of choosing from a list.</span></span> <span data-ttu-id="280ef-115">Auf diese Weise kann der Client einen zusätzlicher Netzwerkhop umgangen werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-115">This way, your client can bypass an extra network hop.</span></span> <span data-ttu-id="280ef-116">Im Fall Auflösen eines Diensts einen anderen Dienstpartition im selben Cluster, und es wird empfohlen, die Verwendung von lokalen <see cref="T:System.Fabric.FabricClient" />, wie es, den automatischen Lastenausgleich ermöglicht und die Leistung verbessert.</span><span class="sxs-lookup"><span data-stu-id="280ef-116">In case a service is resolving another service partition in the same cluster, then it is recommended that you use Local <see cref="T:System.Fabric.FabricClient" />, as it enables automatic load balancing and improves performance.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient hostEndpoints" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="hostEndpoints">
          <para><span data-ttu-id="280ef-117">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-117">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-118">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Gateway-Adressen.</span><span class="sxs-lookup"><span data-stu-id="280ef-118">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses.</span></span> <span data-ttu-id="280ef-119">Diese Host-Endpunkte sind die Liste der ":" als Trennzeichen für Zeichenfolgen, wobei der erste Teil ist die IP-Adresse des Clusters und der zweite Teil ist die Clientverbindungs-Endpunkt-Port.</span><span class="sxs-lookup"><span data-stu-id="280ef-119">These host-endpoints are list of ':' delimited strings where the first part is the ip of the cluster and the second part is the client-connection endpoint-port.</span></span> </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="280ef-120">Die Fabric-Clienteinstellungen.</span><span class="sxs-lookup"><span data-stu-id="280ef-120">The fabric client settings.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="280ef-121">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-121">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-122">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Standardgatewayadressen und die gewünschte <see cref="T:System.Fabric.FabricClientSettings" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-122">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses and the desired <see cref="T:System.Fabric.FabricClientSettings" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <span data-ttu-id="280ef-123"><see cref="T:System.Fabric.SecurityCredentials" />definiert die Sicherheitseinstellungen für die<see cref="T:System.Fabric.FabricClient" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-123"><see cref="T:System.Fabric.SecurityCredentials" /> defines the security settings for the<see cref="T:System.Fabric.FabricClient" />.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="280ef-124">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-124">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-125">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> Klasse, mit Service Fabric-Standardgatewayadressen und <see cref="T:System.Fabric.SecurityCredentials" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-125">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses and <see cref="T:System.Fabric.SecurityCredentials" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="keepAliveInterval">
          <para><span data-ttu-id="280ef-126">Definiert das Intervall der periodischen Keep alive-Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="280ef-126">Defines the periodic keep alive message interval.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para> <span data-ttu-id="280ef-127">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-127">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-128">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="280ef-128">DEPRECATED.</span></span> <span data-ttu-id="280ef-129">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen KeepAliveInterval und Service Fabric-Standardgatewayadressen (HostEndpoints).</span><span class="sxs-lookup"><span data-stu-id="280ef-129">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given keepAliveInterval and Service Fabric Gateway addresses (hostEndpoints).</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="280ef-130">Wenn externe Geräte zwischen die Verbindung vom Client zum Cluster, die regelmäßige Nachrichten an die Verbindung aufrechtzuerhalten erfordern vorhanden sind, stellen Sie sicher, dass die Funktion "Keepalive" FabricClient verwenden.</span><span class="sxs-lookup"><span data-stu-id="280ef-130">If there are external devices in between the connection from the client to the cluster that require periodic messages to keep the connection alive, then make sure to use the KeepAlive feature of FabricClient.</span></span> <span data-ttu-id="280ef-131">Während der Initialisierung der FabricClient können Benutzer einen TimeSpan-KeepAliveInterval angeben.</span><span class="sxs-lookup"><span data-stu-id="280ef-131">During the initialization of the FabricClient, users can specify a TimeSpan keepAliveInterval.</span></span> <span data-ttu-id="280ef-132">Wenn dieses Argument angegeben wird, führt dann die FabricClient in regelmäßigen Abständen ping derzeit kommuniziert mit diesem Service Fabric-Gatewaydienst als ein ausstehender Vorgang vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="280ef-132">If this argument is specified, then the FabricClient will periodically ping the Service Fabric Gateway Service it is currently communicating with, as long as there is a pending operation.</span></span> <span data-ttu-id="280ef-133">Ein Beispiel für ein Szenario, in dem diese Funktion hilfreich ist, ist Windows Azure.</span><span class="sxs-lookup"><span data-stu-id="280ef-133">An example of a scenario where this feature is useful is Windows Azure.</span></span> <span data-ttu-id="280ef-134">Wenn die <see cref="T:System.Fabric.FabricClient" /> außerhalb von Windows Azure wird der Cluster ist in Windows Azure, und alle Verbindungen über Azure Load Balancer (ALB) wechseln.</span><span class="sxs-lookup"><span data-stu-id="280ef-134">If the <see cref="T:System.Fabric.FabricClient" /> is outside of Windows Azure and the cluster is inside of Windows Azure, then all connections will go through the Azure Load Balancer (ALB).</span></span> <span data-ttu-id="280ef-135">ALB beendet-Verbindungen, die mehr als 60 Sekunden lang im Leerlauf befinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-135">ALB terminates connections that are idle for more than 60 seconds.</span></span> <span data-ttu-id="280ef-136">Daher wird in diesen Situationen <see cref="T:System.Fabric.FabricClient" /> erstellt werden soll, mit KeepAliveInterval festgelegt &lt;59 Sekunden (20 -30 wird empfohlen).</span><span class="sxs-lookup"><span data-stu-id="280ef-136">Hence, in these situations, <see cref="T:System.Fabric.FabricClient" /> should be created with KeepAliveInterval set to &lt;59 seconds (20 -30 is recommended).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, System.Fabric.FabricClientSettings settings, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, class System.Fabric.FabricClientSettings settings, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.Fabric.FabricClientSettings,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, settings As FabricClientSettings, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * System.Fabric.FabricClientSettings * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, settings, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential">
          <para>
            <span data-ttu-id="280ef-137"><see cref="T:System.Fabric.SecurityCredentials" />definiert die Sicherheitseinstellungen für die<see cref="T:System.Fabric.FabricClient" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-137"><see cref="T:System.Fabric.SecurityCredentials" /> defines the security settings for the<see cref="T:System.Fabric.FabricClient" />.</span></span></para>
        </param>
        <param name="settings">
          <para><span data-ttu-id="280ef-138">Die Fabric-Clienteinstellungen.</span><span class="sxs-lookup"><span data-stu-id="280ef-138">The fabric client settings.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para><span data-ttu-id="280ef-139">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-139">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-140">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Service Fabric-Gateway-Adressen <see cref="T:System.Fabric.SecurityCredentials" /> und <see cref="T:System.Fabric.FabricClientSettings" />.</span><span class="sxs-lookup"><span data-stu-id="280ef-140">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given Service Fabric Gateway addresses, <see cref="T:System.Fabric.SecurityCredentials" /> and <see cref="T:System.Fabric.FabricClientSettings" />.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FabricClient (System.Fabric.SecurityCredentials credential, TimeSpan keepAliveInterval, params string[] hostEndpoints);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.SecurityCredentials credential, valuetype System.TimeSpan keepAliveInterval, string[] hostEndpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.#ctor(System.Fabric.SecurityCredentials,System.TimeSpan,System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credential As SecurityCredentials, keepAliveInterval As TimeSpan, ParamArray hostEndpoints As String())" />
      <MemberSignature Language="F#" Value="new System.Fabric.FabricClient : System.Fabric.SecurityCredentials * TimeSpan * string[] -&gt; System.Fabric.FabricClient" Usage="new System.Fabric.FabricClient (credential, keepAliveInterval, hostEndpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Deprecated", true)</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="credential" Type="System.Fabric.SecurityCredentials" />
        <Parameter Name="keepAliveInterval" Type="System.TimeSpan" />
        <Parameter Name="hostEndpoints" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credential"><span data-ttu-id="280ef-141">Definieren der Sicherheitsanmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="280ef-141">Defines the security credentials.</span></span></param>
        <param name="keepAliveInterval">
          <para><span data-ttu-id="280ef-142">Definiert das Intervall der periodischen Keep alive-Nachrichten.</span><span class="sxs-lookup"><span data-stu-id="280ef-142">Defines the periodic keep alive message interval.</span></span></para>
        </param>
        <param name="hostEndpoints">
          <para> <span data-ttu-id="280ef-143">Definiert den Satz von Gatewayadressen der <see cref="T:System.Fabric.FabricClient" /> können Sie mit dem Cluster verbinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-143">Defines the set of Gateway addresses the <see cref="T:System.Fabric.FabricClient" /> can use to connect to the cluster.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-144">ALS VERALTET MARKIERT.</span><span class="sxs-lookup"><span data-stu-id="280ef-144">DEPRECATED.</span></span> <span data-ttu-id="280ef-145">Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.FabricClient" /> -Klasse mit angegebenen Anmeldeinformationen, KeepAliveInterval und Service Fabric-Standardgatewayadressen (HostEndpoints).</span><span class="sxs-lookup"><span data-stu-id="280ef-145">Initializes a new instance of the <see cref="T:System.Fabric.FabricClient" /> class with given credentials, keepAliveInterval and Service Fabric Gateway addresses (hostEndpoints).</span></span></para>
        </summary>
        <remarks>
          <para><span data-ttu-id="280ef-146">Wenn externe Geräte zwischen die Verbindung vom Client zum Cluster, die regelmäßige Nachrichten an die Verbindung aufrechtzuerhalten erfordern vorhanden sind, stellen Sie sicher, dass die Funktion "Keepalive" FabricClient verwenden.</span><span class="sxs-lookup"><span data-stu-id="280ef-146">If there are external devices in between the connection from the client to the cluster that require periodic messages to keep the connection alive, then make sure to use the KeepAlive feature of FabricClient.</span></span> <span data-ttu-id="280ef-147">Während der Initialisierung der FabricClient können Benutzer einen TimeSpan-KeepAliveInterval angeben.</span><span class="sxs-lookup"><span data-stu-id="280ef-147">During the initialization of the FabricClient, users can specify a TimeSpan keepAliveInterval.</span></span> <span data-ttu-id="280ef-148">Wenn dieses Argument angegeben wird, führt dann die FabricClient in regelmäßigen Abständen ping derzeit kommuniziert mit diesem Service Fabric-Gatewaydienst als ein ausstehender Vorgang vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="280ef-148">If this argument is specified, then the FabricClient will periodically ping the Service Fabric Gateway Service it is currently communicating with, as long as there is a pending operation.</span></span> <span data-ttu-id="280ef-149">Ein Beispiel für ein Szenario, in dem diese Funktion hilfreich ist, ist Windows Azure.</span><span class="sxs-lookup"><span data-stu-id="280ef-149">An example of a scenario where this feature is useful is Windows Azure.</span></span> <span data-ttu-id="280ef-150">Wenn die <see cref="T:System.Fabric.FabricClient" /> außerhalb von Windows Azure wird der Cluster ist in Windows Azure, und alle Verbindungen über Azure Load Balancer (ALB) wechseln.</span><span class="sxs-lookup"><span data-stu-id="280ef-150">If the <see cref="T:System.Fabric.FabricClient" /> is outside of Windows Azure and the cluster is inside of Windows Azure, then all connections will go through the Azure Load Balancer (ALB).</span></span> <span data-ttu-id="280ef-151">ALB beendet-Verbindungen, die mehr als 60 Sekunden lang im Leerlauf befinden.</span><span class="sxs-lookup"><span data-stu-id="280ef-151">ALB terminates connections that are idle for more than 60 seconds.</span></span> <span data-ttu-id="280ef-152">Daher wird in diesen Situationen <see cref="T:System.Fabric.FabricClient" /> erstellt werden soll, mit KeepAliveInterval festgelegt &lt;59 Sekunden (20 -30 wird empfohlen).</span><span class="sxs-lookup"><span data-stu-id="280ef-152">Hence, in these situations, <see cref="T:System.Fabric.FabricClient" /> should be created with KeepAliveInterval set to &lt;59 seconds (20 -30 is recommended).</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ApplicationManagementClient ApplicationManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ApplicationManagementClient ApplicationManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ApplicationManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationManager As FabricClient.ApplicationManagementClient" />
      <MemberSignature Language="F#" Value="member this.ApplicationManager : System.Fabric.FabricClient.ApplicationManagementClient" Usage="System.Fabric.FabricClient.ApplicationManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ApplicationManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-153">Ruft die <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Anwendungen und Anwendungstypen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-153">Gets the <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> that can be used to perform operations related to applications and application types.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-154">Die <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Anwendungen und Anwendungstypen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-154">The <see cref="P:System.Fabric.FabricClient.ApplicationManager" /> that can be used to perform operations related to applications and application types.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClaimsRetrieval">
      <MemberSignature Language="C#" Value="public event System.Fabric.FabricClient.ClaimsRetrievalEventHandler ClaimsRetrieval;" />
      <MemberSignature Language="ILAsm" Value=".event class System.Fabric.FabricClient/ClaimsRetrievalEventHandler ClaimsRetrieval" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClaimsRetrieval" />
      <MemberSignature Language="VB.NET" Value="Public Event ClaimsRetrieval As FabricClient.ClaimsRetrievalEventHandler " />
      <MemberSignature Language="F#" Value="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " Usage="member this.ClaimsRetrieval : System.Fabric.FabricClient.ClaimsRetrievalEventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClaimsRetrievalEventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="280ef-155">Tritt auf, wenn der Client einem Claims-Token für die Autorisierung mit dem Gateway bereitstellen muss</span><span class="sxs-lookup"><span data-stu-id="280ef-155">Occurs when the client needs to provide a claims token for authorization with the gateway</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="280ef-156">Finden Sie unter <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" /> zum Herstellen einer Verbindung zum sicheren Cluster mithilfe der Azure Active Directory-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="280ef-156">See <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-connect-to-secure-cluster#connect-to-a-secure-cluster-using-the-fabricclient-apis" /> for connecting to secure cluster using Azure Active Directory authentication.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientConnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientConnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientConnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientConnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientConnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientConnected : EventHandler " Usage="member this.ClientConnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="280ef-157">Tritt auf, wenn der Client zum Gateway verbunden ist.</span><span class="sxs-lookup"><span data-stu-id="280ef-157">Occurs when the client is connected to gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientDisconnected">
      <MemberSignature Language="C#" Value="public event EventHandler ClientDisconnected;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ClientDisconnected" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ClientDisconnected" />
      <MemberSignature Language="VB.NET" Value="Public Event ClientDisconnected As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ClientDisconnected : EventHandler " Usage="member this.ClientDisconnected : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="280ef-158">Tritt auf, wenn der Client über das Gateway getrennt ist.</span><span class="sxs-lookup"><span data-stu-id="280ef-158">Occurs when the client is disconnected from the gateway.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClusterManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ClusterManagementClient ClusterManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ClusterManagementClient ClusterManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ClusterManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClusterManager As FabricClient.ClusterManagementClient" />
      <MemberSignature Language="F#" Value="member this.ClusterManager : System.Fabric.FabricClient.ClusterManagementClient" Usage="System.Fabric.FabricClient.ClusterManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ClusterManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-159">Ruft die <see cref="P:System.Fabric.FabricClient.ClusterManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Service Fabric-Cluster verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-159">Gets the <see cref="P:System.Fabric.FabricClient.ClusterManager" /> that can be used to perform operations related to the Service Fabric cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-160">Die <see cref="P:System.Fabric.FabricClient.ClusterManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Service Fabric-Cluster verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-160">The <see cref="P:System.Fabric.FabricClient.ClusterManager" /> that can be used to perform operations related to the Service Fabric cluster.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComposeDeploymentManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ComposeDeploymentClient ComposeDeploymentManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ComposeDeploymentClient ComposeDeploymentManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComposeDeploymentManager As FabricClient.ComposeDeploymentClient" />
      <MemberSignature Language="F#" Value="member this.ComposeDeploymentManager : System.Fabric.FabricClient.ComposeDeploymentClient" Usage="System.Fabric.FabricClient.ComposeDeploymentManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ComposeDeploymentClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-161">Ruft die <see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Bereitstellung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-161">Gets the <see cref="T:System.Fabric.FabricClient.ComposeDeploymentClient" /> that can be used to perform operations related to compose deployment.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-162">Die <see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit der Bereitstellung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-162">The <see cref="P:System.Fabric.FabricClient.ComposeDeploymentManager" /> that can be used to perform operations related to compose deployment.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="fabricClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="280ef-163">Verwirft den Fabric-Client.</span><span class="sxs-lookup"><span data-stu-id="280ef-163">Disposes of the fabric client.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FabricSystemApplication">
      <MemberSignature Language="C#" Value="public readonly Uri FabricSystemApplication;" />
      <MemberSignature Language="ILAsm" Value=".field public initonly class System.Uri FabricSystemApplication" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly FabricSystemApplication As Uri " />
      <MemberSignature Language="F#" Value="val mutable FabricSystemApplication : Uri" Usage="System.Fabric.FabricClient.FabricSystemApplication" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-164">Die Service Fabric-System-Anwendung.</span><span class="sxs-lookup"><span data-stu-id="280ef-164">The Service Fabric System application.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.FaultManagementClient FaultManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/FaultManagementClient FaultManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.FaultManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultManager As FabricClient.FaultManagementClient" />
      <MemberSignature Language="F#" Value="member this.FaultManager : System.Fabric.FabricClient.FaultManagementClient" Usage="System.Fabric.FabricClient.FaultManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+FaultManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="280ef-165">Ruft die <see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> zum Auslösen von Fehlern.</span><span class="sxs-lookup"><span data-stu-id="280ef-165">Gets the <see cref="T:System.Fabric.FabricClient.FaultManagementClient" /> to induce faults.</span></span> <span data-ttu-id="280ef-166">Beispielsweise RestartNodeAsync.</span><span class="sxs-lookup"><span data-stu-id="280ef-166">For example, RestartNodeAsync.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="280ef-167">Gibt <see cref="T:System.Fabric.FabricClient.FaultManagementClient" />zurück.</span><span class="sxs-lookup"><span data-stu-id="280ef-167">Returns <see cref="T:System.Fabric.FabricClient.FaultManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Finalize">
      <MemberSignature Language="C#" Value="~FabricClient ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Finalize() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.Finalize" />
      <MemberSignature Language="VB.NET" Value="Finalize ()" />
      <MemberSignature Language="F#" Value="override this.Finalize : unit -&gt; unit" Usage="fabricClient.Finalize " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="280ef-168">Der Destruktor der Fabric-Client.</span><span class="sxs-lookup"><span data-stu-id="280ef-168">Destructor of fabric client.</span></span>
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.HealthClient HealthManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/HealthClient HealthManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.HealthManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthManager As FabricClient.HealthClient" />
      <MemberSignature Language="F#" Value="member this.HealthManager : System.Fabric.FabricClient.HealthClient" Usage="System.Fabric.FabricClient.HealthManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+HealthClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-169">Ruft den Integritäts-Client, der verwendet werden kann, zum Ausführen von Integrität, die im Zusammenhang Vorgänge, wie z. B. Melden der Integrität oder Entitätsintegrität abrufen.</span><span class="sxs-lookup"><span data-stu-id="280ef-169">Gets the health client that can be used to perform health related operations, like report health or get entity health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-170">Die Integrität-Client, der verwendet werden kann, um integritätsprüfungen auszuführen im Zusammenhang mit Vorgängen, z. B. Melden der Integrität oder Get Entitätsintegrität.</span><span class="sxs-lookup"><span data-stu-id="280ef-170">The health client that can be used to perform health related operations, like report health or get entity health.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InfrastructureManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.InfrastructureServiceClient InfrastructureManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/InfrastructureServiceClient InfrastructureManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.InfrastructureManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InfrastructureManager As FabricClient.InfrastructureServiceClient" />
      <MemberSignature Language="F#" Value="member this.InfrastructureManager : System.Fabric.FabricClient.InfrastructureServiceClient" Usage="System.Fabric.FabricClient.InfrastructureManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+InfrastructureServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-171">Ruft die <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> , die verwendet werden kann, zum Ausführen von Vorgängen im Zusammenhang mit der Infrastruktur, die auf dem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="280ef-171">Gets the <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> that can be used to perform operations related to the infrastructure on which the cluster is running.</span></span></para>
          <para><span data-ttu-id="280ef-172">Diese Eigenschaft unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-172">This property supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-173">Die <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> , die verwendet werden kann, zum Ausführen von Vorgängen im Zusammenhang mit der Infrastruktur, die auf dem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="280ef-173">The <see cref="T:System.Fabric.FabricClient.InfrastructureServiceClient" /> that can be used to perform operations related to the infrastructure on which the cluster is running.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PropertyManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.PropertyManagementClient PropertyManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/PropertyManagementClient PropertyManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.PropertyManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PropertyManager As FabricClient.PropertyManagementClient" />
      <MemberSignature Language="F#" Value="member this.PropertyManager : System.Fabric.FabricClient.PropertyManagementClient" Usage="System.Fabric.FabricClient.PropertyManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+PropertyManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-174">Ruft die <see cref="P:System.Fabric.FabricClient.PropertyManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Namen und Eigenschaften verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-174">Gets the <see cref="P:System.Fabric.FabricClient.PropertyManager" /> that can be used to perform operations related to names and properties.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-175">Die <see cref="P:System.Fabric.FabricClient.PropertyManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Namen und Eigenschaften verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-175">The <see cref="P:System.Fabric.FabricClient.PropertyManager" /> that can be used to perform operations related to names and properties.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.QueryClient QueryManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/QueryClient QueryManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.QueryManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryManager As FabricClient.QueryClient" />
      <MemberSignature Language="F#" Value="member this.QueryManager : System.Fabric.FabricClient.QueryClient" Usage="System.Fabric.FabricClient.QueryManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+QueryClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-176">Ruft den Abfrage-Manager, der zum Ausführen von Abfragen für die Service Fabric-Cluster verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-176">Gets the query manager that can be used to execute queries against the Service Fabric cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-177">Der Abfrage-Manager, der zum Ausführen von Abfragen für die Service Fabric-Cluster verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-177">The query manager that can be used to execute queries against the Service Fabric cluster.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="280ef-178">Der Abfrage-Manager kann zum Ausführen von Abfragen für den Cluster verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-178">The query manager can be used to execute queries against the cluster.</span></span>
            <span data-ttu-id="280ef-179">Die meisten Abfragen verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-179">Most of the queries are distributed.</span></span> <span data-ttu-id="280ef-180">Sie rufen Sie mehrere Systemkomponenten, um verschiedene Informationen zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="280ef-180">They call multiple system components to get different information.</span></span>
            <span data-ttu-id="280ef-181">Die Aufrufe an die Systemkomponenten werden parallel ausgeführt, und die zurückgegebenen Ergebnisse werden basierend auf einem gemeinsamen Schlüssel aggregiert.</span><span class="sxs-lookup"><span data-stu-id="280ef-181">The calls to the system components are executed in parallel and the returned results are aggregated based on a common key.</span></span>
            <span data-ttu-id="280ef-182">Beispielsweise, um die Liste der Knoten im Cluster ist, erhalten die <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> Abfrage wechselt zum Failovercluster-Manager, Cluster-Manager und Health Manager Systemdienste.</span><span class="sxs-lookup"><span data-stu-id="280ef-182">For example, to get the list of nodes in the cluster, the <see cref="M:System.Fabric.FabricClient.QueryClient.GetNodeListAsync" /> query goes to Failover Manager, Cluster Manager, and Health Manager system services.</span></span>
            <span data-ttu-id="280ef-183">Aus diesem Grund sind einige Abfragen teuer.</span><span class="sxs-lookup"><span data-stu-id="280ef-183">For this reason, some queries are expensive.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RepairManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.RepairManagementClient RepairManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/RepairManagementClient RepairManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.RepairManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepairManager As FabricClient.RepairManagementClient" />
      <MemberSignature Language="F#" Value="member this.RepairManager : System.Fabric.FabricClient.RepairManagementClient" Usage="System.Fabric.FabricClient.RepairManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+RepairManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-184">Ruft die <see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> , die zur Verwaltung reparieren Aufgaben verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-184">Gets the <see cref="T:System.Fabric.FabricClient.RepairManagementClient" /> that can be used to manage repair tasks.</span></span></para>
          <para><span data-ttu-id="280ef-185">Diese Eigenschaft unterstützt die Service Fabric-Plattform. Es ist nicht vorgesehen, direkt aus Ihrem Code aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-185">This property supports the Service Fabric platform; it is not meant to be called directly from your code.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-186">Gibt <see cref="T:System.Fabric.FabricClient.RepairManagementClient" />zurück.</span><span class="sxs-lookup"><span data-stu-id="280ef-186">Returns <see cref="T:System.Fabric.FabricClient.RepairManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceGroupManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceGroupManagementClient ServiceGroupManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceGroupManagementClient ServiceGroupManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceGroupManager As FabricClient.ServiceGroupManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceGroupManager : System.Fabric.FabricClient.ServiceGroupManagementClient" Usage="System.Fabric.FabricClient.ServiceGroupManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceGroupManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-187">Ruft die <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Dienstgruppen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-187">Gets the <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> that can be used to perform operations related to service groups.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-188">Die <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Dienstgruppen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-188">The <see cref="P:System.Fabric.FabricClient.ServiceGroupManager" /> that can be used to perform operations related to service groups.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.ServiceManagementClient ServiceManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/ServiceManagementClient ServiceManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.ServiceManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManager As FabricClient.ServiceManagementClient" />
      <MemberSignature Language="F#" Value="member this.ServiceManager : System.Fabric.FabricClient.ServiceManagementClient" Usage="System.Fabric.FabricClient.ServiceManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+ServiceManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-189">Ruft die <see cref="P:System.Fabric.FabricClient.ServiceManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Diensten und Diensttypen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-189">Gets the <see cref="P:System.Fabric.FabricClient.ServiceManager" /> that can be used to perform operations related to services and service types.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-190">Die <see cref="P:System.Fabric.FabricClient.ServiceManager" /> , die zum Ausführen von Vorgängen im Zusammenhang mit Diensten und Diensttypen verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="280ef-190">The <see cref="P:System.Fabric.FabricClient.ServiceManager" /> that can be used to perform operations related to services and service types.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClientSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClientSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As FabricClientSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.FabricClientSettings" Usage="System.Fabric.FabricClient.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClientSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="280ef-191">Ruft die Fabric-Clienteinstellungen.</span><span class="sxs-lookup"><span data-stu-id="280ef-191">Gets the fabric client settings.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="280ef-192">Die Fabric-Clienteinstellungen.</span><span class="sxs-lookup"><span data-stu-id="280ef-192">The fabric client settings.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestManager">
      <MemberSignature Language="C#" Value="public System.Fabric.FabricClient.TestManagementClient TestManager { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.FabricClient/TestManagementClient TestManager" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.FabricClient.TestManager" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestManager As FabricClient.TestManagementClient" />
      <MemberSignature Language="F#" Value="member this.TestManager : System.Fabric.FabricClient.TestManagementClient" Usage="System.Fabric.FabricClient.TestManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.FabricClient+TestManagementClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="280ef-193">Ruft die <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> für komplexe Aktionen, die FaultAnalysisService durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="280ef-193">Gets the <see cref="T:System.Fabric.FabricClient.TestManagementClient" /> to perform complex actions that go through FaultAnalysisService.</span></span> <span data-ttu-id="280ef-194">Beispielsweise StartPartitionDataLossAsync.</span><span class="sxs-lookup"><span data-stu-id="280ef-194">For example, StartPartitionDataLossAsync.</span></span>
            <span data-ttu-id="280ef-195">Dies unterstützt auch die APIs für die Überprüfung (die nicht über FaultAnalysisService geleitet werden).</span><span class="sxs-lookup"><span data-stu-id="280ef-195">This also supports APIs for validation (that do not go through FaultAnalysisService).</span></span> <span data-ttu-id="280ef-196">Beispielsweise ValidateServiceAsync.</span><span class="sxs-lookup"><span data-stu-id="280ef-196">For example, ValidateServiceAsync.</span></span>
            </summary>
        <value>
          <para><span data-ttu-id="280ef-197">Gibt <see cref="T:System.Fabric.FabricClient.TestManagementClient" />zurück.</span><span class="sxs-lookup"><span data-stu-id="280ef-197">Returns <see cref="T:System.Fabric.FabricClient.TestManagementClient" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecurityCredentials">
      <MemberSignature Language="C#" Value="public void UpdateSecurityCredentials (System.Fabric.SecurityCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSecurityCredentials(class System.Fabric.SecurityCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSecurityCredentials(System.Fabric.SecurityCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSecurityCredentials (credentials As SecurityCredentials)" />
      <MemberSignature Language="F#" Value="member this.UpdateSecurityCredentials : System.Fabric.SecurityCredentials -&gt; unit" Usage="fabricClient.UpdateSecurityCredentials credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="System.Fabric.SecurityCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="280ef-198">Die neuen Anmeldeinformationen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-198">The new security credentials to be used.</span></span></param>
        <summary>
            <span data-ttu-id="280ef-199">Aktualisiert die Fabric-Client-Sicherheitsanmeldeinformationen an.</span><span class="sxs-lookup"><span data-stu-id="280ef-199">Updates the fabric client security credentials.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSettings">
      <MemberSignature Language="C#" Value="public void UpdateSettings (System.Fabric.FabricClientSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateSettings(class System.Fabric.FabricClientSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.UpdateSettings(System.Fabric.FabricClientSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateSettings (settings As FabricClientSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateSettings : System.Fabric.FabricClientSettings -&gt; unit" Usage="fabricClient.UpdateSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.FabricClientSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para><span data-ttu-id="280ef-200">Die neuen Fabric-Clienteinstellungen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="280ef-200">The new fabric client settings to be used.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="280ef-201">Aktualisiert die Fabric-Clienteinstellungen.</span><span class="sxs-lookup"><span data-stu-id="280ef-201">Updates the fabric client settings.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="280ef-202">Die angegebene Fabric-Clienteinstellungen darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="280ef-202">The specified fabric client settings can’t be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
            <span data-ttu-id="280ef-203"><see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" />muss größer oder gleich 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="280ef-203"><see cref="P:System.Fabric.FabricClientSettings.AuthTokenBufferSize" /> must be greater or equal to zero.</span></span></para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>