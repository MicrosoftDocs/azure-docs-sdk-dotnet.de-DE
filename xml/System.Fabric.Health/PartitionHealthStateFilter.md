<Type Name="PartitionHealthStateFilter" FullName="System.Fabric.Health.PartitionHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class PartitionHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit PartitionHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.PartitionHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class PartitionHealthStateFilter" />
  <TypeSignature Language="F#" Value="type PartitionHealthStateFilter = class" />
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
            <span data-ttu-id="afb17-101">Filter für <see cref="T:System.Fabric.Health.PartitionHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="afb17-101">Filter for <see cref="T:System.Fabric.Health.PartitionHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="afb17-102">Der Status-Segment integritätsabfragen können angeben, eine Liste der Filter feine Partition wählen Sie die Partitionen, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="afb17-102">The health state chunk queries can specify a list of partition filters to fine-grain select the partitions that should be included in the query result.</span></span>
            <span data-ttu-id="afb17-103">Beachten Sie, dass alle Partitionen zur Bewertung des Eltern Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</span><span class="sxs-lookup"><span data-stu-id="afb17-103">Note that all the partitions are used to evaluate parents' aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="afb17-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="afb17-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.PartitionHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="afb17-105">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="afb17-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="afb17-106">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.PartitionHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="afb17-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.PartitionHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="afb17-107">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="afb17-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="afb17-108">Für eine Partition, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="afb17-108">For a partition to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionIdFilter">
      <MemberSignature Language="C#" Value="public Guid PartitionIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionIdFilter As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionIdFilter : Guid with get, set" Usage="System.Fabric.Health.PartitionHealthStateFilter.PartitionIdFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afb17-109">Abrufen oder Festlegen des Partitions-Id-Filters.</span><span class="sxs-lookup"><span data-stu-id="afb17-109">Gets or sets the partition id filter.</span></span>
            </summary>
        <value><span data-ttu-id="afb17-110">Der Partitions-Id-Filter.</span><span class="sxs-lookup"><span data-stu-id="afb17-110">The partition id filter.</span></span></value>
        <remarks><span data-ttu-id="afb17-111">Wenn nicht angegeben wird, werden alle Partitionen, die das übergeordnete Element entsprechen gefiltert (sofern vorhanden), und der angegebenen Integrität Statusfilter stimmen Sie dem Filter überein.</span><span class="sxs-lookup"><span data-stu-id="afb17-111">If not specified, all partitions that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="afb17-112">Andernfalls gilt der Filter nur für die Partition, die durch die Partitions-Id identifiziert. Alle anderen Filter Member, wie Statusfilter Integrität und Replikate-Filter werden auf dieser Partition angewendet.</span><span class="sxs-lookup"><span data-stu-id="afb17-112">Otherwise, the filter only applies to the partition identified by the partition id. All the other filter members, like health state filter and replicas filter, are applied to this partition.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Health.ReplicaHealthStateFilter&gt; ReplicaFilters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaFilters As IList(Of ReplicaHealthStateFilter)" />
      <MemberSignature Language="F#" Value="member this.ReplicaFilters : System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;" Usage="System.Fabric.Health.PartitionHealthStateFilter.ReplicaFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Health.ReplicaHealthStateFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="afb17-113">Ruft die Liste der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> auf die untergeordneten Elemente replikatintegritätszustände angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="afb17-113">Gets the list of <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> to be applied to the replica children health states.</span></span>
            </summary>
        <value><span data-ttu-id="afb17-114">Die Liste der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> auf die untergeordneten Elemente replikatintegritätszustände angewendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="afb17-114">The list of <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> to be applied to the replica children health states.</span></span></value>
        <remarks><span data-ttu-id="afb17-115">Alle Replikat untergeordneten Elemente, die dem Filter entsprechen, werden als untergeordnete Elemente der Partition zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="afb17-115">All replica children that match the filter will be returned as children of the partition.</span></span>
            <span data-ttu-id="afb17-116">Ohne Angabe werden die untergeordneten Elemente standardmäßig nicht zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="afb17-116">If empty, the children are not returned by default.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.PartitionHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="partitionHealthStateFilter.ToString " />
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
            <span data-ttu-id="afb17-117">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="afb17-117">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="afb17-118">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="afb17-118">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>