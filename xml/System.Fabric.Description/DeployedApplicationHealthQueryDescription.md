<Type Name="DeployedApplicationHealthQueryDescription" FullName="System.Fabric.Description.DeployedApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedApplicationHealthQueryDescription = class" />
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
      <para><span data-ttu-id="f81a1-101">Beschreibt abfrageeingabe zum Abrufen von <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span><span class="sxs-lookup"><span data-stu-id="f81a1-101">Describes query input for getting <see cref="T:System.Fabric.Health.DeployedApplicationHealth" />.</span></span> <span data-ttu-id="f81a1-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="f81a1-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedApplicationHealthAsync(System.Fabric.Description.DeployedApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedApplicationHealthQueryDescription (Uri applicationName, string nodeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedApplicationHealthQueryDescription : Uri * string -&gt; System.Fabric.Description.DeployedApplicationHealthQueryDescription" Usage="new System.Fabric.Description.DeployedApplicationHealthQueryDescription (applicationName, nodeName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="f81a1-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="f81a1-103">The application name.</span></span> <span data-ttu-id="f81a1-104">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="f81a1-104">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="f81a1-105">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="f81a1-105">The node name.</span></span> <span data-ttu-id="f81a1-106">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="f81a1-106">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f81a1-107">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f81a1-107">Initializes a new instance of the <see cref="T:System.Fabric.Description.DeployedApplicationHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="f81a1-108">Ein erforderlicher Parameter darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="f81a1-108">A required parameter can’t be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="f81a1-109">Ein erforderlicher Parameter darf nicht leer sein.</span><span class="sxs-lookup"><span data-stu-id="f81a1-109">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.ApplicationName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f81a1-110">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="f81a1-110">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f81a1-111">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="f81a1-111">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServicePackagesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedServicePackageHealthStatesFilter DeployedServicePackagesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedServicePackagesFilter As DeployedServicePackageHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedServicePackagesFilter : System.Fabric.Health.DeployedServicePackageHealthStatesFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.DeployedServicePackagesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedServicePackageHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f81a1-112">Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="f81a1-112">Gets or sets the filter for <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> children.</span></span> <span data-ttu-id="f81a1-113">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-113">Only children that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f81a1-114">Die <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> zum Filtern der zurückgegebenen bereitgestellten dienstpakete verwendet.</span><span class="sxs-lookup"><span data-stu-id="f81a1-114">The <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStatesFilter" /> used to filter returned deployed service packages.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="f81a1-115">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-115">Only children that match the filter will be returned.</span></span> <span data-ttu-id="f81a1-116">Alle untergeordneten Elemente dienen zum Auswerten des Integritätsstatus der bereitgestellten Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="f81a1-116">All children will be used to evaluate the deployed application aggregated health state.</span></span>
            <span data-ttu-id="f81a1-117">Wenn der Filter nicht angegeben ist, werden alle bereitgestellten Dienst Paket untergeordneten Elemente der bereitgestellten Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-117">If the filter is not specified, all deployed service package children of the deployed application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="f81a1-118">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die bereitgestellte Anwendung gemeldet.</span><span class="sxs-lookup"><span data-stu-id="f81a1-118">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the deployed application.</span></span> <span data-ttu-id="f81a1-119">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-119">Only events that match the filter will be returned.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f81a1-120">Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die zurückgegebenen Ereignisse gefiltert.</span><span class="sxs-lookup"><span data-stu-id="f81a1-120">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="f81a1-121">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-121">Only events that match the filter will be returned.</span></span> <span data-ttu-id="f81a1-122">Alle Ereignisse dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="f81a1-122">All events will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="f81a1-123">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-123">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f81a1-124">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um die Integrität der bereitgestellten Anwendung auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="f81a1-124">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the deployed application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f81a1-125">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</span><span class="sxs-lookup"><span data-stu-id="f81a1-125">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="f81a1-126">Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie oder die übergeordnete Anwendung zum Auswerten der bereitgestellten Anwendung.</span><span class="sxs-lookup"><span data-stu-id="f81a1-126">If not specified, the health store uses the application health policy or the parent application to evaluate the deployed application.</span></span>
            <span data-ttu-id="f81a1-127">Die Integritätsrichtlinie für die Anwendung wird im Anwendungsmanifest angegeben.</span><span class="sxs-lookup"><span data-stu-id="f81a1-127">The application health policy is specified in the application manifest.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As DeployedApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.DeployedApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f81a1-128">Abrufen oder festlegen den Integrität Statistiken Filter.</span><span class="sxs-lookup"><span data-stu-id="f81a1-128">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="f81a1-129">Der Filter für den Integritäts-Statistiken.</span><span class="sxs-lookup"><span data-stu-id="f81a1-129">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="f81a1-130">Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält die bereitgestellte Anwendung Integrität Statistiken.</span><span class="sxs-lookup"><span data-stu-id="f81a1-130">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.DeployedApplicationHealth" /> returned by the query contains the deployed application health statistics.</span></span> <span data-ttu-id="f81a1-131">Wenn nicht angegeben, werden die Statistiken enthalten.</span><span class="sxs-lookup"><span data-stu-id="f81a1-131">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedApplicationHealthQueryDescription.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f81a1-132">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="f81a1-132">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f81a1-133">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="f81a1-133">The node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedApplicationHealthQueryDescription.ToString " />
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
            <span data-ttu-id="f81a1-134">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="f81a1-134">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="f81a1-135">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="f81a1-135">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>