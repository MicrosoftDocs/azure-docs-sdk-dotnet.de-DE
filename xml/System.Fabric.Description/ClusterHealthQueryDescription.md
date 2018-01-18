<Type Name="ClusterHealthQueryDescription" FullName="System.Fabric.Description.ClusterHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ClusterHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClusterHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ClusterHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClusterHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ClusterHealthQueryDescription = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="44db7-101">Enthält abfrageeingabe zum Herunterladen von <see cref="T:System.Fabric.Health.ClusterHealth" />.</span><span class="sxs-lookup"><span data-stu-id="44db7-101">Provides query input for getting <see cref="T:System.Fabric.Health.ClusterHealth" />.</span></span> <span data-ttu-id="44db7-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="44db7-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetClusterHealthAsync(System.Fabric.Description.ClusterHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthQueryDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="44db7-103">Initializes a new instance of the <see cref="T:System.Fabric.Description.ClusterHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationHealthPolicyMap">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicyMap ApplicationHealthPolicyMap" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationHealthPolicyMap As ApplicationHealthPolicyMap" />
      <MemberSignature Language="F#" Value="member this.ApplicationHealthPolicyMap : System.Fabric.Health.ApplicationHealthPolicyMap" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationHealthPolicyMap" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicyMap</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-104">Ruft die anwendungsintegritätsrichtlinien zum Auswerten der Integritäts der Anwendungen aus dem Cluster an.</span><span class="sxs-lookup"><span data-stu-id="44db7-104">Gets the application health policies used to evaluate the health of the applications from the cluster.</span></span> <span data-ttu-id="44db7-105">Jeder Eintrag gibt an, wie der Anwendungsname Schlüssel und als Wert ein <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="44db7-105">Each entry specifies as key the application name and as value an <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44db7-106">Die anwendungsintegritätsrichtlinien zum Auswerten der Integritäts der Anwendungen aus dem Cluster verwendet.</span><span class="sxs-lookup"><span data-stu-id="44db7-106">The application health policies used to evaluate the health of the applications from the cluster.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="44db7-107">Wenn eine Anwendung nicht in der Zuordnung angegeben wird die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> gefunden in seiner Anwendung Manifest zur Auswertung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="44db7-107">If an application is not specified in the map, the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> found in its application manifest will be used for evaluation.</span></span> <span data-ttu-id="44db7-108">Die Zuordnung ist standardmäßig leer.</span><span class="sxs-lookup"><span data-stu-id="44db7-108">The map is empty by default.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatesFilter ApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationsFilter As ApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ApplicationsFilter : System.Fabric.Health.ApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.ApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-109">Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="44db7-109">Gets or sets the filter for <see cref="T:System.Fabric.Health.ApplicationHealthState" /> children.</span></span> <span data-ttu-id="44db7-110">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-110">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44db7-111">Der Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="44db7-111">The filter for <see cref="T:System.Fabric.Health.ApplicationHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="44db7-112">Nur Anwendungen, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-112">Only applications that match the filter will be returned.</span></span> <span data-ttu-id="44db7-113">Alle Anwendungen dienen zum Auswerten des integritätszustands der Cluster aggregiert.</span><span class="sxs-lookup"><span data-stu-id="44db7-113">All applications will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="44db7-114">Wenn der Filter nicht angegeben ist, werden alle Clusteranwendungen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-114">If the filter is not specified, all cluster applications are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.EventsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthEventsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-115">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> im Cluster gemeldet.</span><span class="sxs-lookup"><span data-stu-id="44db7-115">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the cluster.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44db7-116">Der Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> im Cluster gemeldet.</span><span class="sxs-lookup"><span data-stu-id="44db7-116">The filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the cluster.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="44db7-117">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-117">Only events that match the filter will be returned.</span></span> <span data-ttu-id="44db7-118">Alle Ereignisse werden zum Auswerten der Cluster aggregiert integritätszustands verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="44db7-118">All events will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="44db7-119">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-119">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ClusterHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ClusterHealthPolicy with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-120">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="44db7-120">Gets or sets the <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the cluster health.</span></span> <span data-ttu-id="44db7-121">Die Richtlinie wird zum Auswerten der aggregierte Integritätszustand der Ereignisse gemeldet werden, auf dem Cluster als auch die aggregierten integritätszustände der Knoten verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="44db7-121">The policy will be used to evaluate the aggregated health state of the events reported on cluster as well as the aggregated health states of the nodes.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44db7-122">die <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> verwendet, um den Clusterzustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="44db7-122">The <see cref="T:System.Fabric.Health.ClusterHealthPolicy" /> used to evaluate the cluster health.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ClusterHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ClusterHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ClusterHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ClusterHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="44db7-123">Abrufen oder festlegen den Integrität Statistiken Filter.</span><span class="sxs-lookup"><span data-stu-id="44db7-123">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="44db7-124">Der Filter für den Integritäts-Statistiken.</span><span class="sxs-lookup"><span data-stu-id="44db7-124">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="44db7-125">Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.ClusterHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält die Cluster Health Statistiken.</span><span class="sxs-lookup"><span data-stu-id="44db7-125">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.ClusterHealth" /> returned by the query contains the cluster health statistics.</span></span> <span data-ttu-id="44db7-126">Wenn nicht angegeben, werden die Statistiken enthalten.</span><span class="sxs-lookup"><span data-stu-id="44db7-126">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.NodeHealthStatesFilter NodesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.NodeHealthStatesFilter NodesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodesFilter As NodeHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.NodesFilter : System.Fabric.Health.NodeHealthStatesFilter with get, set" Usage="System.Fabric.Description.ClusterHealthQueryDescription.NodesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.NodeHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="44db7-127">Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="44db7-127">Gets or sets the filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> children.</span></span> <span data-ttu-id="44db7-128">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-128">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="44db7-129">Der Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="44db7-129">The filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="44db7-130">Nur Knoten, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-130">Only nodes that match the filter will be returned.</span></span> <span data-ttu-id="44db7-131">Alle Knoten dienen zum Auswerten des integritätszustands der Cluster aggregiert.</span><span class="sxs-lookup"><span data-stu-id="44db7-131">All nodes will be used to evaluate the cluster aggregated health state.</span></span>
            <span data-ttu-id="44db7-132">Wenn der Filter nicht angegeben ist, werden alle Knoten des Clusters zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="44db7-132">If the filter is not specified, all cluster nodes are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ClusterHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="clusterHealthQueryDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="44db7-133">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="44db7-133">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="44db7-134">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="44db7-134">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>