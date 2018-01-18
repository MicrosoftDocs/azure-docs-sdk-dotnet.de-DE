<Type Name="ApplicationHealthStateFilter" FullName="System.Fabric.Health.ApplicationHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ApplicationHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ApplicationHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ApplicationHealthStateFilter = class" />
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
            <span data-ttu-id="ea00e-101">Filter für <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="ea00e-101">Filter for <see cref="T:System.Fabric.Health.ApplicationHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="ea00e-102">Die Entität Health Status Block Abfragen können angeben, eine Liste der feine Anwendungsfilter wählen Sie die Anwendungen, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="ea00e-102">The entity health state chunk queries can specify a list of application filters to fine-grain select the applications that should be included in the query result.</span></span>
            <span data-ttu-id="ea00e-103">Beachten Sie, dass alle Anwendungen zur Bewertung des Integritätsstatus des Clusters aggregiert, unabhängig von den Filter übergeben.</span><span class="sxs-lookup"><span data-stu-id="ea00e-103">Note that all the applications are used to evaluate cluster aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ea00e-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ea00e-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.ApplicationHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationNameFilter">
      <MemberSignature Language="C#" Value="public Uri ApplicationNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationNameFilter : Uri with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationNameFilter" />
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
            <span data-ttu-id="ea00e-105">Abrufen oder Festlegen der Anwendung Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="ea00e-105">Gets or sets the application name filter.</span></span>
            </summary>
        <value><span data-ttu-id="ea00e-106">Die Anwendung Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="ea00e-106">The application name filter.</span></span></value>
        <remarks><span data-ttu-id="ea00e-107">Wenn angegeben, gilt der Filter nur auf die gewünschte Anwendung.</span><span class="sxs-lookup"><span data-stu-id="ea00e-107">If specified, the filter applies only to the desired application.</span></span> <span data-ttu-id="ea00e-108">Für die Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ea00e-108">For the application to match the filter, its aggregated health state must match the specified health state filter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationTypeNameFilter">
      <MemberSignature Language="C#" Value="public string ApplicationTypeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApplicationTypeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationTypeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ApplicationTypeNameFilter : string with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ApplicationTypeNameFilter" />
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
            <span data-ttu-id="ea00e-109">Abrufen oder Festlegen der Anwendung Namen Typfilter.</span><span class="sxs-lookup"><span data-stu-id="ea00e-109">Gets or sets the application type name filter.</span></span>
            </summary>
        <value><span data-ttu-id="ea00e-110">Die Anwendung Typ Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="ea00e-110">The application type name filter.</span></span></value>
        <remarks><span data-ttu-id="ea00e-111">Wenn angegeben, gilt der Filter für alle Anwendungen vom angegebenen Typ, die einen spezifischeren Filter (für einen bestimmten Anwendungsnamen) besitzen.</span><span class="sxs-lookup"><span data-stu-id="ea00e-111">If specified, the filter applies to all applications of specified application type that don't have a more specific filter (for a specific application name).</span></span>
            <span data-ttu-id="ea00e-112">Für eine Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ea00e-112">For an application to match the filter, its aggregated health state must match the specified health state filter.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedApplicationFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.DeployedApplicationHealthStateFilter&gt; DeployedApplicationFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedApplicationFilters As IList(Of DeployedApplicationHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.DeployedApplicationFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.DeployedApplicationFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.DeployedApplicationHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea00e-113">Ruft die Liste der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> auf des Integritätsstatus der bereitgestellten Anwendung untergeordnete Elemente angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ea00e-113">Gets the list of <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> to be applied to the deployed application children health states.</span></span>
            </summary>
        <value><span data-ttu-id="ea00e-114">Die Liste der <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> auf des Integritätsstatus der bereitgestellten Anwendung untergeordnete Elemente angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ea00e-114">The list of <see cref="T:System.Fabric.Health.DeployedApplicationHealthStateFilter" /> to be applied to the deployed application children health states.</span></span></value>
        <remarks><span data-ttu-id="ea00e-115">Die Liste kann es sich um ein Standard-bereitgestellten Anwendung oder die bereitgestellte Anwendungsfilter für bestimmte bereitgestellte Anwendungen auf feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.</span><span class="sxs-lookup"><span data-stu-id="ea00e-115">The list can contain one default deployed application filter or deployed application filters for specific deployed applications to fine-grain entities returned by the query.</span></span>
            <span data-ttu-id="ea00e-116">Alle bereitgestellten Anwendung, die untergeordnete Elemente, die dem Filter entsprechen, als untergeordnete Elemente der Anwendung zurückgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ea00e-116">All deployed application children that match the filter will be returned as children of the application.</span></span>
            <span data-ttu-id="ea00e-117">Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ea00e-117">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ApplicationHealthStateFilter.HealthStateFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthStateFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea00e-118">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ea00e-118">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ApplicationHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="ea00e-119">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ApplicationHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="ea00e-119">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ApplicationHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="ea00e-120">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="ea00e-120">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="ea00e-121">Für eine Anwendung, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="ea00e-121">For an application to match the filter, its aggregated health state must match the specified health state filter.</span></span>
            <span data-ttu-id="ea00e-122">Wenn die Integrität Statusfilter Standard, standardmäßig der Statusfilter Integrität auf None, wenn es keine spezifischen Filter (Anwendungsname oder Name des Anwendungstyps sind).</span><span class="sxs-lookup"><span data-stu-id="ea00e-122">If the health state filter is Default, the health state filter defaults to None if there are no specific filters (application name or application type name).</span></span>
            <span data-ttu-id="ea00e-123">Andernfalls gilt der Standardfilter für alle gelten.</span><span class="sxs-lookup"><span data-stu-id="ea00e-123">Otherwise, the Default filter is considered to apply to All.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ServiceHealthStateFilter&gt; ServiceFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceFilters As IList(Of ServiceHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ServiceFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;" Usage="System.Fabric.Health.ApplicationHealthStateFilter.ServiceFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ServiceHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ea00e-124">Ruft die Liste der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> auf die untergeordneten Elemente dienstintegritätszustände angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ea00e-124">Gets the list of <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> to be applied to the service children health states.</span></span>
            </summary>
        <value><span data-ttu-id="ea00e-125">Die Liste der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> auf die untergeordneten Elemente dienstintegritätszustände angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="ea00e-125">The list of <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> to be applied to the service children health states.</span></span></value>
        <remarks><span data-ttu-id="ea00e-126">Die Liste kann es sich um eine Standard-Dienst oder die Service Filter für bestimmte Dienste feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.</span><span class="sxs-lookup"><span data-stu-id="ea00e-126">The list can contain one default service filter or service filters for specific services to fine-grain entities returned by the query.</span></span>
            <span data-ttu-id="ea00e-127">Alle Service untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente der Anwendung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ea00e-127">All service children that match the filter will be returned as children of the application.</span></span>
            <span data-ttu-id="ea00e-128">Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="ea00e-128">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ApplicationHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="applicationHealthStateFilter.ToString " />
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
            <span data-ttu-id="ea00e-129">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="ea00e-129">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="ea00e-130">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="ea00e-130">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>