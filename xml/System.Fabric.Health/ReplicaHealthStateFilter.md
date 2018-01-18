<Type Name="ReplicaHealthStateFilter" FullName="System.Fabric.Health.ReplicaHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class ReplicaHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ReplicaHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ReplicaHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ReplicaHealthStateFilter" />
  <TypeSignature Language="F#" Value="type ReplicaHealthStateFilter = class" />
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
            <span data-ttu-id="7928a-101">Filter für <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="7928a-101">Filter for <see cref="T:System.Fabric.Health.ReplicaHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="7928a-102">Die Entität Health Status Block Abfragen können angeben, eine Liste der Replikatfilter feine auswählen, die Replikate, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="7928a-102">The entity health state chunk queries can specify a list of replica filters to fine-grain select the replicas that should be included in the query result.</span></span>
            <span data-ttu-id="7928a-103">Beachten Sie, dass alle Replikate dienen zum Auswerten von übergeordneten Elementen Integritätsstatus, unabhängig von der übergebene Filter aggregiert.</span><span class="sxs-lookup"><span data-stu-id="7928a-103">Note that all the replicas are used to evaluate parents aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ReplicaHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7928a-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7928a-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.ReplicaHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="7928a-105">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="7928a-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="7928a-106">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.ReplicaHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="7928a-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.ReplicaHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="7928a-107">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="7928a-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="7928a-108">Für ein Replikat auf dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="7928a-108">For a replica to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaOrInstanceIdFilter">
      <MemberSignature Language="C#" Value="public long ReplicaOrInstanceIdFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplicaOrInstanceIdFilter As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaOrInstanceIdFilter : int64 with get, set" Usage="System.Fabric.Health.ReplicaHealthStateFilter.ReplicaOrInstanceIdFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7928a-109">Ruft ab oder legt fest, der einem zustandsbehafteten Dienst-Id oder des zustandslose Instanz-Id-Filters.</span><span class="sxs-lookup"><span data-stu-id="7928a-109">Gets or sets the stateful service replica id or the stateless instance id filter.</span></span>
            </summary>
        <value><span data-ttu-id="7928a-110">Der zustandsbehaftete Dienst-Id oder des zustandslose Instanz-Id-Filters.</span><span class="sxs-lookup"><span data-stu-id="7928a-110">The stateful service replica id or the stateless instance id filter.</span></span></value>
        <remarks><span data-ttu-id="7928a-111">Wenn nicht angegeben wird, werden alle Replikate, die das übergeordnete Element entsprechen gefiltert (sofern vorhanden), und der angegebenen Integrität Statusfilter stimmen Sie dem Filter überein.</span><span class="sxs-lookup"><span data-stu-id="7928a-111">If not specified, all replicas that match the parent filters (if any) and the specified health state filter match the filter.</span></span>
            <span data-ttu-id="7928a-112">Andernfalls gilt der Filter nur für das Replikat durch die angegebene Id identifizierte.</span><span class="sxs-lookup"><span data-stu-id="7928a-112">Otherwise, the filter only applies to the replica identified by the given id.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ReplicaHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="replicaHealthStateFilter.ToString " />
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
            <span data-ttu-id="7928a-113">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="7928a-113">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="7928a-114">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="7928a-114">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>