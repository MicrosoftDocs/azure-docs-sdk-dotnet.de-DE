<Type Name="DeployedServicePackageHealthStateFilter" FullName="System.Fabric.Health.DeployedServicePackageHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServicePackageHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServicePackageHealthStateFilter" />
  <TypeSignature Language="F#" Value="type DeployedServicePackageHealthStateFilter = class" />
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
            <span data-ttu-id="e3379-101">Filter für <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="e3379-101">Filter for <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="e3379-102">Der Status-Segment integritätsabfragen können angeben, eine Liste der bereitgestellten Dienst Paket Filter feine wählen Sie die bereitgestellten dienstpakete, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="e3379-102">The health state chunk queries can specify a list of deployed service package filters to fine-grain select the deployed service packages that should be included in the query result.</span></span>
            <span data-ttu-id="e3379-103">Beachten Sie, dass alles, was die bereitgestellten dienstpakete zur Bewertung des übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</span><span class="sxs-lookup"><span data-stu-id="e3379-103">Note that all the deployed service packages are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedServicePackageHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e3379-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e3379-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="e3379-105">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="e3379-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="e3379-106">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="e3379-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.DeployedServicePackageHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="e3379-107">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="e3379-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="e3379-108">Für ein bereitgestelltes Dienstpaket, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="e3379-108">For a deployed service package to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestNameFilter">
      <MemberSignature Language="C#" Value="public string ServiceManifestNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceManifestNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestNameFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServiceManifestNameFilter" />
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
            <span data-ttu-id="e3379-109">Abrufen oder Festlegen der Dienstfilter Manifestnamen.</span><span class="sxs-lookup"><span data-stu-id="e3379-109">Gets or sets the service manifest name filter.</span></span>
            </summary>
        <value><span data-ttu-id="e3379-110">Der Dienstfilter Manifestnamen.</span><span class="sxs-lookup"><span data-stu-id="e3379-110">The service manifest name filter.</span></span></value>
        <remarks><span data-ttu-id="e3379-111">Wenn nicht angegeben, alle bereitgestellten Dienstpaketen, die die übergeordnete Filter (sofern vorhanden) entsprechen und die angegebenen Health Status filtern, die Filterkriterien erfüllen.</span><span class="sxs-lookup"><span data-stu-id="e3379-111">If not specified, all deployed service packages that match the parent filters (if any) and the specified health state filters match the filter.</span></span>
            <span data-ttu-id="e3379-112">Andernfalls der Filter gilt nur für das Paket bereitgestellten Dienst für den angegebenen Dienst Manifestnamen und anhand der Integrität Statusfilter abgeglichen werden.</span><span class="sxs-lookup"><span data-stu-id="e3379-112">Otherwise, the filter only applies to the deployed service package for the specified service manifest name and the health state filter will be matched against it.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationIdFilter">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServicePackageActivationIdFilter As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationIdFilter : string with get, set" Usage="System.Fabric.Health.DeployedServicePackageHealthStateFilter.ServicePackageActivationIdFilter" />
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
            <span data-ttu-id="e3379-113">Abrufen oder festlegen den Dienst Paket ActivationId-Filter.</span><span class="sxs-lookup"><span data-stu-id="e3379-113">Gets or sets the service package ActivationId filter.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="e3379-114">Die <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> bereitgestellten Diensts Paket abgerufen werden kann, mithilfe von <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> Abfrage.</span><span class="sxs-lookup"><span data-stu-id="e3379-114">The <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> of deployed service package can be obtained by using <see cref="M:System.Fabric.FabricClient.QueryClient.GetDeployedServicePackageListAsync(System.String,System.Uri)" /> query.</span></span> 
             </para>
          <para>
            <span data-ttu-id="e3379-115">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung des Diensts wurde <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wurde, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="e3379-115">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service was <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it was not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="e3379-116">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="e3379-116">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.DeployedServicePackageHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="deployedServicePackageHealthStateFilter.ToString " />
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
            <span data-ttu-id="e3379-117">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="e3379-117">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="e3379-118">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="e3379-118">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>