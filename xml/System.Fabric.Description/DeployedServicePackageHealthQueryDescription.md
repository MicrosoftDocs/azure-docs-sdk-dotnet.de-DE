<Type Name="DeployedServicePackageHealthQueryDescription" FullName="System.Fabric.Description.DeployedServicePackageHealthQueryDescription">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthQueryDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthQueryDescription" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthQueryDescription = class" />
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
      <para><span data-ttu-id="870d2-101">Beschreibt die als abfrageeingabe für die erste <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</span><span class="sxs-lookup"><span data-stu-id="870d2-101">Describes the query input for getting <see cref="T:System.Fabric.Health.DeployedServicePackageHealth" />.</span></span> <span data-ttu-id="870d2-102">Wird von <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" /> verwendet.</span><span class="sxs-lookup"><span data-stu-id="870d2-102">Used by <see cref="M:System.Fabric.FabricClient.HealthClient.GetDeployedServicePackageHealthAsync(System.Fabric.Description.DeployedServicePackageHealthQueryDescription)" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="870d2-103">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="870d2-103">The application name.</span></span> <span data-ttu-id="870d2-104">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-104">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="870d2-105">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="870d2-105">The node name.</span></span> <span data-ttu-id="870d2-106">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-106">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="870d2-107">Der dienstmanifestname.</span><span class="sxs-lookup"><span data-stu-id="870d2-107">The service manifest name.</span></span> <span data-ttu-id="870d2-108">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-108">Cannot be null or empty.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="870d2-109">Instanziiert eine <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="870d2-109">Instantiates a <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="870d2-110">Ein erforderlicher Parameter darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-110">A required parameter can't be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="870d2-111">Ein erforderlicher Parameter darf nicht leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-111">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthQueryDescription (Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri applicationName, string nodeName, string serviceManifestName, string servicePackageActivationId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.#ctor(System.Uri,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (applicationName As Uri, nodeName As String, serviceManifestName As String, servicePackageActivationId As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription : Uri * string * string * string -&gt; System.Fabric.Description.DeployedServicePackageHealthQueryDescription" Usage="new System.Fabric.Description.DeployedServicePackageHealthQueryDescription (applicationName, nodeName, serviceManifestName, servicePackageActivationId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="servicePackageActivationId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para><span data-ttu-id="870d2-112">Der Anwendungsname.</span><span class="sxs-lookup"><span data-stu-id="870d2-112">The application name.</span></span> <span data-ttu-id="870d2-113">Darf nicht NULL sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-113">Cannot be null.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="870d2-114">Der Knotenname.</span><span class="sxs-lookup"><span data-stu-id="870d2-114">The node name.</span></span> <span data-ttu-id="870d2-115">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-115">Cannot be null or empty.</span></span></para>
        </param>
        <param name="serviceManifestName">
          <para><span data-ttu-id="870d2-116">Der dienstmanifestname.</span><span class="sxs-lookup"><span data-stu-id="870d2-116">The service manifest name.</span></span> <span data-ttu-id="870d2-117">Darf weder NULL noch leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-117">Cannot be null or empty.</span></span></para>
        </param>
        <param name="servicePackageActivationId">
          <para>
            <span data-ttu-id="870d2-118">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets.</span><span class="sxs-lookup"><span data-stu-id="870d2-118">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span>
            <span data-ttu-id="870d2-119">ServicePackageActivationId für ein bereitgestelltes Dienstpaket kann abgerufen, indem <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="870d2-119">ServicePackageActivationId of a deployed service package can obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="870d2-120">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="870d2-120">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="870d2-121">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="870d2-121">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </param>
        <summary>
          <para><span data-ttu-id="870d2-122">Instanziiert eine <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> Klasse.</span><span class="sxs-lookup"><span data-stu-id="870d2-122">Instantiates a <see cref="T:System.Fabric.Description.DeployedServicePackageHealthQueryDescription" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para><span data-ttu-id="870d2-123">Ein erforderlicher Parameter darf nicht null sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-123">A required parameter can't be null.</span></span></para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para><span data-ttu-id="870d2-124">Ein erforderlicher Parameter darf nicht leer sein.</span><span class="sxs-lookup"><span data-stu-id="870d2-124">A required parameter can't be empty.</span></span></para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ApplicationName" />
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
          <para><span data-ttu-id="870d2-125">Ruft den Namen der Anwendung ab.</span><span class="sxs-lookup"><span data-stu-id="870d2-125">Gets the name of the application.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="870d2-126">Der Namen der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="870d2-126">The name of the application.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthEventsFilter EventsFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.HealthEventsFilter EventsFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsFilter As HealthEventsFilter" />
      <MemberSignature Language="F#" Value="member this.EventsFilter : System.Fabric.Health.HealthEventsFilter with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.EventsFilter" />
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
          <para><span data-ttu-id="870d2-127">Ruft ab oder legt Sie den Filter für die Auflistung von <see cref="T:System.Fabric.Health.HealthEvent" /> für das Paket bereitgestellten Dienst gemeldet.</span><span class="sxs-lookup"><span data-stu-id="870d2-127">Gets or sets the filter for the collection of <see cref="T:System.Fabric.Health.HealthEvent" /> reported on the deployed service package.</span></span> <span data-ttu-id="870d2-128">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="870d2-128">Only events that match the filter will be returned.</span></span> <span data-ttu-id="870d2-129">Alle Ereignisse werden zum Auswerten der aggregierten integritätszustands verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="870d2-129">All events will be used to evaluate the aggregated health state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="870d2-130">Die <see cref="T:System.Fabric.Health.HealthEventsFilter" /> verwendet, um die zurückgegebenen Ereignisse gefiltert.</span><span class="sxs-lookup"><span data-stu-id="870d2-130">The <see cref="T:System.Fabric.Health.HealthEventsFilter" /> used to filter returned events.</span></span></para>
        </value>
        <remarks>
          <para> <span data-ttu-id="870d2-131">Nur Ereignisse, die dem Filter entsprechen, werden zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="870d2-131">Only events that match the filter will be returned.</span></span> <span data-ttu-id="870d2-132">Alle Ereignisse dienen zum Auswerten des integritätszustands der Entität, die aggregiert.</span><span class="sxs-lookup"><span data-stu-id="870d2-132">All events will be used to evaluate the entity aggregated health state.</span></span>
            <span data-ttu-id="870d2-133">Wenn der Filter nicht angegeben wird, werden alle Ereignisse zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="870d2-133">If the filter is not specified, all events are returned.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthPolicy">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.ApplicationHealthPolicy HealthPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Health.ApplicationHealthPolicy HealthPolicy" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthPolicy As ApplicationHealthPolicy" />
      <MemberSignature Language="F#" Value="member this.HealthPolicy : System.Fabric.Health.ApplicationHealthPolicy with get, set" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.HealthPolicy" />
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
          <para><span data-ttu-id="870d2-134">Ruft ab oder legt die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> verwendet, um den Zustand auszuwerten.</span><span class="sxs-lookup"><span data-stu-id="870d2-134">Gets or sets the <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate the health.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="870d2-135">Die <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> zur Bewertung der Integrität.</span><span class="sxs-lookup"><span data-stu-id="870d2-135">The <see cref="T:System.Fabric.Health.ApplicationHealthPolicy" /> used to evaluate health.</span></span></para>
        </value>
        <remarks><span data-ttu-id="870d2-136">Wenn nicht angegeben, verwendet der Health Store einer anwendungsintegritäts-Richtlinie für die übergeordnete Anwendung zur bereitgestellten dienstpaketintegrität Auswertung an.</span><span class="sxs-lookup"><span data-stu-id="870d2-136">If not specified, the health store uses the application health policy of the parent application to evaluate the deployed service package health.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.NodeName" />
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
          <para><span data-ttu-id="870d2-137">Ruft den Knotennamen ab.</span><span class="sxs-lookup"><span data-stu-id="870d2-137">Gets the node name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="870d2-138">Die <see cref="T:System.String" /> , der Name des Knotens darstellt.</span><span class="sxs-lookup"><span data-stu-id="870d2-138">The <see cref="T:System.String" /> representing the node name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServiceManifestName" />
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
          <para><span data-ttu-id="870d2-139">Ruft den Namen des Dienst-Manifests ab.</span><span class="sxs-lookup"><span data-stu-id="870d2-139">Gets the service manifest name.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="870d2-140">Die <see cref="T:System.String" /> der dienstmanifestname darstellt.</span><span class="sxs-lookup"><span data-stu-id="870d2-140">The <see cref="T:System.String" /> representing the service manifest name.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ServicePackageActivationId" />
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
            <span data-ttu-id="870d2-141">Ruft die ActivationId des Dienstpakets ab.</span><span class="sxs-lookup"><span data-stu-id="870d2-141">Gets the ActivationId of the service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="870d2-142">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> des bereitgestellten Dienstpakets.</span><span class="sxs-lookup"><span data-stu-id="870d2-142">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package.</span></span> <span data-ttu-id="870d2-143">ServicePackageActivationId für ein bereitgestelltes Dienstpaket kann abgerufen, indem <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="870d2-143">ServicePackageActivationId of a deployed service package can obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
            </para>
          <para>
            <span data-ttu-id="870d2-144">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="870d2-144">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="870d2-145">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="870d2-145">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span> 
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.DeployedServicePackageHealthQueryDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthQueryDescription.ToString " />
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
            <span data-ttu-id="870d2-146">Ruft eine Zeichenfolgendarstellung der Integrität abfragebeschreibung ab.</span><span class="sxs-lookup"><span data-stu-id="870d2-146">Gets a string representation of the health query description.</span></span>
            </summary>
        <returns><span data-ttu-id="870d2-147">Eine Zeichenfolgendarstellung der abfragebeschreibung Integrität.</span><span class="sxs-lookup"><span data-stu-id="870d2-147">A string representation of the health query description.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>