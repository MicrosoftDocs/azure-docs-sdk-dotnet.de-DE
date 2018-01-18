<Type Name="NodeHealthStateFilter" FullName="System.Fabric.Health.NodeHealthStateFilter">
  <TypeSignature Language="C#" Value="public sealed class NodeHealthStateFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeHealthStateFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.NodeHealthStateFilter" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeHealthStateFilter" />
  <TypeSignature Language="F#" Value="type NodeHealthStateFilter = class" />
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
            <span data-ttu-id="2652d-101">Filter für <see cref="T:System.Fabric.Health.NodeHealthState" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2652d-101">Filter for <see cref="T:System.Fabric.Health.NodeHealthState" /> objects.</span></span>
            </summary>
    <remarks><span data-ttu-id="2652d-102">Der Cluster Status-Segment integritätsabfragen können angeben, eine Liste der Knoten feine Filter wählen Sie die Knoten, die in das Abfrageergebnis aufgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="2652d-102">The cluster health state chunk queries can specify a list of node filters to fine-grain select the nodes that should be included in the query result.</span></span>
            <span data-ttu-id="2652d-103">Beachten Sie, dass alle Knoten dienen zum Auswerten der Integritätsstatus des Clusters aggregiert, unabhängig von den Filter übergeben.</span><span class="sxs-lookup"><span data-stu-id="2652d-103">Note that all the nodes are used to evaluate cluster aggregated health state, regardless of the filter passed in.</span></span></remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeHealthStateFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2652d-104">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Health.NodeHealthStateFilter" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2652d-104">Initializes a new instance of the <see cref="T:System.Fabric.Health.NodeHealthStateFilter" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthStateFilter">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthStateFilter HealthStateFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthStateFilter HealthStateFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateFilter.HealthStateFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property HealthStateFilter As HealthStateFilter" />
      <MemberSignature Language="F#" Value="member this.HealthStateFilter : System.Fabric.Health.HealthStateFilter with get, set" Usage="System.Fabric.Health.NodeHealthStateFilter.HealthStateFilter" />
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
            <span data-ttu-id="2652d-105">Ruft ab oder legt Sie Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="2652d-105">Gets or sets filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span> 
            </summary>
        <value><span data-ttu-id="2652d-106">Der Filter für den aggregierten Zustand der <see cref="T:System.Fabric.Health.NodeHealthState" /> Einträge in der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="2652d-106">The filter for the aggregated health state of the <see cref="T:System.Fabric.Health.NodeHealthState" /> entries in the collection.</span></span></value>
        <remarks><span data-ttu-id="2652d-107">Die Integrität statusfilterwert stammen von Membern oder bitweisen Kombination von Membern der <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span><span class="sxs-lookup"><span data-stu-id="2652d-107">The health state filter value comes from members or bitwise combination of members of <see cref="T:System.Fabric.Health.HealthStateFilter" />.</span></span> <span data-ttu-id="2652d-108">Für einen Knoten, die dem Filter entsprechen muss der aggregierte Integritätszustand der angegebenen Integrität Statusfilter übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="2652d-108">For a node to match the filter, its aggregated health state must match the specified health state filter.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeNameFilter">
      <MemberSignature Language="C#" Value="public string NodeNameFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeNameFilter" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.NodeHealthStateFilter.NodeNameFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeNameFilter As String" />
      <MemberSignature Language="F#" Value="member this.NodeNameFilter : string with get, set" Usage="System.Fabric.Health.NodeHealthStateFilter.NodeNameFilter" />
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
            <span data-ttu-id="2652d-109">Abrufen oder Festlegen der Knoten Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="2652d-109">Gets or sets the node name filter.</span></span>
            </summary>
        <value><span data-ttu-id="2652d-110">Der Knoten Namensfilter.</span><span class="sxs-lookup"><span data-stu-id="2652d-110">The node name filter.</span></span></value>
        <remarks><span data-ttu-id="2652d-111">Wenn nicht angegeben, werden alle Knoten, die die übergeordnete Filter (sofern vorhanden) entsprechen berücksichtigt und mit den anderen Elementen in einem Filter, wie die Integrität Statusfilter abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="2652d-111">If not specified, all nodes that match the parent filters (if any) are taken into consideration and matched against the other filter members, like health state filter.</span></span>
            <span data-ttu-id="2652d-112">Andernfalls gilt der Filter nur auf den angegebenen Knoten.</span><span class="sxs-lookup"><span data-stu-id="2652d-112">Otherwise, the filter only applies to the specfied node.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.NodeHealthStateFilter.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeHealthStateFilter.ToString " />
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
            <span data-ttu-id="2652d-113">Gibt eine Zeichenfolgendarstellung des Filters zurück.</span><span class="sxs-lookup"><span data-stu-id="2652d-113">Returns a string representation of the filter.</span></span>
            </summary>
        <returns><span data-ttu-id="2652d-114">Eine Zeichenfolgendarstellung des Filters.</span><span class="sxs-lookup"><span data-stu-id="2652d-114">A string representation of the filter.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>