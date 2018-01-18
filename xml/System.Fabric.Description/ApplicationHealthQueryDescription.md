<Type Name="ApplicationHealthQueryDescription" FullName="System.Fabric.Description.ApplicationHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type ApplicationHealthQueryDescription = class" />
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
      <para><span data-ttu-id="98498-101">Stellt die abfrageeingabe zum Abrufen der Anwendungsintegrität dar.</span><span class="sxs-lookup"><span data-stu-id="98498-101">Represents the query input for getting application health.</span></span> <span data-ttu-id="98498-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="98498-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetApplicationHealthAsync(System.Fabric.Description.ApplicationHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthQueryDescription (Uri applicationName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.ApplicationHealthQueryDescription : Uri -&gt; System.Fabric.Description.ApplicationHealthQueryDescription" Usage="new System.Fabric.Description.ApplicationHealthQueryDescription applicationName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="98498-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="98498-103">The application name.</span></span> <span data-ttu-id="98498-104">Nicht mit <languageKeyword>null</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="98498-104">Cannot be <languageKeyword>null</languageKeyword>.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="98498-105">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="98498-105">Initializes a new instance of the <see cref="T:System.Fabric.Description.ApplicationHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="98498-106">Ein null-Wert wurde für einen erforderlichen Parameter übergeben.</span><span class="sxs-lookup"><span data-stu-id="98498-106">A null value was passed in for a required parameter.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="98498-107">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="98498-107">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="98498-108">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="98498-108">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.DeployedApplicationHealthStatesFilter DeployedApplicationsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property DeployedApplicationsFilter As DeployedApplicationHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationsFilter : System.Fabric.Health.DeployedApplicationHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.DeployedApplicationsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.DeployedApplicationHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="98498-109">Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="98498-109">Gets or sets the filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthState" /> children.</span></span> <span data-ttu-id="98498-110">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-110">Only children that match the filter will be returned.</span></span> <span data-ttu-id="98498-111">Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-111">All children will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="98498-112">Der Filter für <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="98498-112">The filter for <see cref="T:System.Fabric.Health.DeployedApplicationHealthStatesFilter" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="98498-113">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-113">Only children that match the filter will be returned.</span></span> <span data-ttu-id="98498-114">Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-114">All children will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="98498-115">Wenn der Filter nicht angegeben ist, werden alle bereitgestellten Anwendung untergeordneten Elemente der Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-115">If the filter is not specified, all deployed application children of the application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="98498-116">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die Anwendung gemeldet.</span><span class="sxs-lookup"><span data-stu-id="98498-116">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the application.</span></span> <span data-ttu-id="98498-117">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-117">Only events that match the filter will be returned.</span></span> <span data-ttu-id="98498-118">Alle Ereignisse dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-118">All events will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="98498-119">Der Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für die Anwendung gemeldet.</span><span class="sxs-lookup"><span data-stu-id="98498-119">The filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the application.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="98498-120">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-120">Only events that match the filter will be returned.</span></span> <span data-ttu-id="98498-121">Alle Ereignisse dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-121">All events will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="98498-122">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-122">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="98498-123">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Anwendungszustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="98498-123">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the application health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="98498-124">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zum Auswerten der Anwendungsintegrität verwendet.</span><span class="sxs-lookup"><span data-stu-id="98498-124">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate application health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="98498-125">Wenn nicht angegeben, verwendet den Health-Speicher die Anwendung Integritätsrichtlinie, die im Anwendungsmanifest angegebene zum Auswerten der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="98498-125">If not specified, the health store uses the application health policy specified in the application manifest to evaluate the application.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStatisticsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthStatisticsFilter HealthStatisticsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStatisticsFilter As ApplicationHealthStatisticsFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStatisticsFilter : System.Fabric.Health.ApplicationHealthStatisticsFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.HealthStatisticsFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ApplicationHealthStatisticsFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="98498-126">Abrufen oder festlegen den Integrität Statistiken Filter.</span><span class="sxs-lookup"><span data-stu-id="98498-126">Gets or sets the health statistics filter.</span></span>
            </summary>
        <value><span data-ttu-id="98498-127">Der Filter für den Integritäts-Statistiken.</span><span class="sxs-lookup"><span data-stu-id="98498-127">The health statistics filter.</span></span></value>
        <remarks>
          <para>
            <span data-ttu-id="98498-128">Filtersteuerelementen gibt an, ob die Statistiken für die Integrität der <see cref="T:System.Fabric.Health.ApplicationHealth" /> zurückgegeben werden, indem Sie die Abfrage enthält, die Integrität Anwendungsstatistiken.</span><span class="sxs-lookup"><span data-stu-id="98498-128">The health statistics filter controls whether the <see cref="T:System.Fabric.Health.ApplicationHealth" /> returned by the query contains the application health statistics.</span></span> <span data-ttu-id="98498-129">Wenn nicht angegeben, werden die Statistiken enthalten.</span><span class="sxs-lookup"><span data-stu-id="98498-129">If not specified, the statistics are included.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicesFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ServiceHealthStatesFilter ServicesFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicesFilter As ServiceHealthStatesFilter" />
      <MemberSignature Language="F#" Value="member this.ServicesFilter : System.Fabric.Health.ServiceHealthStatesFilter with get, set" Usage="System.Fabric.Description.ApplicationHealthQueryDescription.ServicesFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.ServiceHealthStatesFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="98498-130">Ruft ab oder legt den Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="98498-130">Gets or sets the filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> children.</span></span> <span data-ttu-id="98498-131">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-131">Only children that match the filter will be returned.</span></span> <span data-ttu-id="98498-132">Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-132">All children will be used to evaluate the application aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="98498-133">Der Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> untergeordneten Elemente.</span><span class="sxs-lookup"><span data-stu-id="98498-133">The filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> children.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="98498-134">Nur untergeordnete Elemente, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-134">Only children that match the filter will be returned.</span></span> <span data-ttu-id="98498-135">Alle untergeordneten Elemente dienen zum Auswerten des integritätszustands der Anwendung aggregiert.</span><span class="sxs-lookup"><span data-stu-id="98498-135">All children will be used to evaluate the application aggregated health state.</span></span>
            <span data-ttu-id="98498-136">Wenn der Filter nicht angegeben ist, werden alle untergeordneten Objekte Dienst die Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="98498-136">If the filter is not specified, all service children of the application are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthQueryDescription.ToString " />
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
            <span data-ttu-id="98498-137">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="98498-137">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="98498-138">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="98498-138">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>