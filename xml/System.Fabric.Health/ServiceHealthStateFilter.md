<Type Name="ServiceHealthStateFilter" FullName="System.Fabric.Health.ServiceHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ServiceHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServiceHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServiceHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ServiceHealthStateFilter = class" />
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
            <span data-ttu-id="1d6ae-101">Filter für <see cref="T:System.Fabric.Health.ServiceHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-101">Filter for <see cref="T:System.Fabric.Health.ServiceHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="1d6ae-102">Die Entität Health Status Block Abfragen können angeben, eine Liste der Filter feine Service wählen Sie die Dienste, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-102">The entity health state chunk queries can specify a list of service filters to fine-grain select the services that should be included in the query result.</span></span>
            <span data-ttu-id="1d6ae-103">Beachten Sie, dass alles, was die Dienste zur Bewertung des übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-103">Note that all the services are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1d6ae-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.ServiceHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="1d6ae-105">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="1d6ae-106">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ServiceHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ServiceHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="1d6ae-107">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="1d6ae-108">Für einen Dienst auf dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-108">For a service to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.PartitionHealthStateFilter&gt; PartitionFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionFilters As IList(Of PartitionHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.PartitionFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;" Usage="System.Fabric.Health.ServiceHealthStateFilter.PartitionFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.PartitionHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1d6ae-109">Ruft die Liste der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> auf untergeordnete Elemente Zustände Partition angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-109">Gets the list of <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> to be applied to the partition children health states.</span></span>
            </summary>
        <value><span data-ttu-id="1d6ae-110">Die Liste der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> auf untergeordnete Elemente Zustände Partition angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-110">The list of <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> to be applied to the partition children health states.</span></span></value>
        <remarks><span data-ttu-id="1d6ae-111">Die Liste kann es sich um einen Standardfilter Partition und/oder Partition Filter für bestimmte Partitionen feine-Entitäten, die von der Abfrage zurückgegebenen enthalten.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-111">The list can contain one default partition filter and/or partition filters for specific partitions to fine-grain entities returned by the query.</span></span>
            <span data-ttu-id="1d6ae-112">Alle Partitionen untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente des Diensts zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-112">All partition children that match the filter will be returned as children of the service.</span></span>
            <span data-ttu-id="1d6ae-113">Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-113">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceNameFilter">
      <MemberSignature Language="C#" Value="public Uri ServiceNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceNameFilter As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceNameFilter : Uri with get, set" Usage="System.Fabric.Health.ServiceHealthStateFilter.ServiceNameFilter" />
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
            <span data-ttu-id="1d6ae-114">Abrufen / definieren den Dienst Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-114">Gets or sets the service name filter.</span></span>
            </summary>
        <value><span data-ttu-id="1d6ae-115">Der Filter für den Service-Name.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-115">The service name filter.</span></span></value>
        <remarks><span data-ttu-id="1d6ae-116">Wenn nicht angegeben, werden alle Dienste, die die übergeordnete Filter (sofern vorhanden) und der angegebenen Integrität Statusfilter übereinstimmen Filter entsprechen.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-116">If not specified, all services that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="1d6ae-117">Andernfalls gilt der Filter nur für den angegebenen Dienst.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-117">Otherwise, the filter only applies to the specified service.</span></span> <span data-ttu-id="1d6ae-118">Alle anderen Filter Member, wie die Integrität der Statusfilter, werden auf diesen Dienst angewendet.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-118">All the other filter members, like health state filter, are applied to this service.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="serviceHealthStateFilter.ToString " />
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
            <span data-ttu-id="1d6ae-119">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-119">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="1d6ae-120">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="1d6ae-120">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>