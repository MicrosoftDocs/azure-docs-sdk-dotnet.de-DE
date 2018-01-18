<Type Name="Node" FullName="System.Fabric.Query.Node">
  <TypeSignature Language="C#" Value="public sealed class Node" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit Node extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Node" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class Node" />
  <TypeSignature Language="F#" Value="type Node = class" />
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
      <para><span data-ttu-id="16b19-101">Stellt einen Service Fabric-Cluster-Knoten dar.</span><span class="sxs-lookup"><span data-stu-id="16b19-101">Represents a Service Fabric cluster node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodeVersion">
      <MemberSignature Language="C#" Value="public string CodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.CodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodeVersion : string" Usage="System.Fabric.Query.Node.CodeVersion" />
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
          <para><span data-ttu-id="16b19-102">Ruft die Service Fabric-Runtime-Version, die auf den Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-102">Gets the Service Fabric runtime version running on the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-103">Die Service Fabric-Runtime-Version auf den Knoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="16b19-103">The Service Fabric runtime version running on the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfigVersion">
      <MemberSignature Language="C#" Value="public string ConfigVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConfigVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.ConfigVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConfigVersion As String" />
      <MemberSignature Language="F#" Value="member this.ConfigVersion : string" Usage="System.Fabric.Query.Node.ConfigVersion" />
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
          <para><span data-ttu-id="16b19-104">Ruft die Cluster-Konfigurationsversion auf den Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-104">Gets the cluster configuration version on the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-105">Die Cluster-Konfigurationsversion auf dem Knoten.</span><span class="sxs-lookup"><span data-stu-id="16b19-105">The cluster configuration version on the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FaultDomain">
      <MemberSignature Language="C#" Value="public Uri FaultDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri FaultDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.FaultDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FaultDomain As Uri" />
      <MemberSignature Language="F#" Value="member this.FaultDomain : Uri" Usage="System.Fabric.Query.Node.FaultDomain" />
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
          <para><span data-ttu-id="16b19-106">Ruft die Fehlerdomäne für diesen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-106">Gets the fault domain for this node.</span></span></para>
          <remarks>
            <para><span data-ttu-id="16b19-107">Fehlerdomänen definieren Sätze von Knoten, die wahrscheinlich gleichzeitig aufgrund von freigegebenen physischen Abhängigkeiten wie Strom oder Netzwerkressourcen Fehler auftreten.</span><span class="sxs-lookup"><span data-stu-id="16b19-107">Fault domains define sets of nodes which are likely to experience failure at the same time due to shared physical dependencies such as power and networking resources.</span></span> <span data-ttu-id="16b19-108">Fehlerdomänen stellen in der Regel die Hierarchie und daher werden mit dargestellt <see cref="T:System.Uri" />.</span><span class="sxs-lookup"><span data-stu-id="16b19-108">Fault domains typically represent hierarchy and hence are represented using <see cref="T:System.Uri" />.</span></span></para>
          </remarks>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-109">Die Fehlerdomäne für diesen Knoten.</span><span class="sxs-lookup"><span data-stu-id="16b19-109">The fault domain for this node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Node.HealthState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Health.HealthState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-110">Ruft den Integritätsstatus des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-110">Gets the health state of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-111">Der Integritätsstatus des Knotens.</span><span class="sxs-lookup"><span data-stu-id="16b19-111">The health state of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddressOrFQDN">
      <MemberSignature Language="C#" Value="public string IpAddressOrFQDN { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddressOrFQDN" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IpAddressOrFQDN" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpAddressOrFQDN As String" />
      <MemberSignature Language="F#" Value="member this.IpAddressOrFQDN : string" Usage="System.Fabric.Query.Node.IpAddressOrFQDN" />
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
          <para><span data-ttu-id="16b19-112">Ruft die IP-Adresse oder den vollständig qualifizierten Domänennamen (FQDN) des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-112">Gets the IP address or the fully qualified domain name (FQDN) of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-113">Die IP-Adresse oder den vollständig qualifizierten Domänennamen (FQDN) des Knotens.</span><span class="sxs-lookup"><span data-stu-id="16b19-113">The IP address or the fully qualified domain name (FQDN) of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSeedNode">
      <MemberSignature Language="C#" Value="public bool IsSeedNode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsSeedNode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsSeedNode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsSeedNode As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsSeedNode : bool" Usage="System.Fabric.Query.Node.IsSeedNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-114">Ruft einen Wert, der angibt, ob dies eine Seed-Knoten ist.</span><span class="sxs-lookup"><span data-stu-id="16b19-114">Gets a value indicating whether this is a seed node.</span></span> <span data-ttu-id="16b19-115">SEED-Knoten sind besondere Art von Knoten automatisch konfiguriert und wird intern vom System verwendet.</span><span class="sxs-lookup"><span data-stu-id="16b19-115">Seed nodes are special type of node configured automatically and used internally by the system.</span></span> </para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="16b19-116"><languageKeyword>"true"</languageKeyword> Wenn diese Instanz einen Seed-Knoten handelt, andernfalls <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="16b19-116"><languageKeyword>true</languageKeyword> if this instance is a seed node; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStopped">
      <MemberSignature Language="C#" Value="public bool IsStopped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsStopped" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.IsStopped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsStopped As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsStopped : bool" Usage="System.Fabric.Query.Node.IsStopped" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="16b19-117">"True", wenn ein Knoten beendet wird.</span><span class="sxs-lookup"><span data-stu-id="16b19-117">True if a node is stopped.</span></span>  <span data-ttu-id="16b19-118">Ein Knoten ist im Status "beendet", wenn sie das Ziel einen erfolgreichen Aufruf von StartNodeTransitionAsync mit NodeTransitionType beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="16b19-118">A node is in a stopped state if it was the target of a successful call to StartNodeTransitionAsync with a NodeTransitionType of Stop.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-119">Und zwar unabhängig davon, ob ein Knoten wurde beendet</span><span class="sxs-lookup"><span data-stu-id="16b19-119">Whether or not a node is stopped</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDeactivationInfo">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.NodeDeactivationResult NodeDeactivationInfo" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDeactivationInfo As NodeDeactivationResult" />
      <MemberSignature Language="F#" Value="member this.NodeDeactivationInfo : System.Fabric.Query.NodeDeactivationResult" Usage="System.Fabric.Query.Node.NodeDeactivationInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeDeactivationResult</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>
            <span data-ttu-id="16b19-120">Ruft die Deaktivierungsinformationen für den Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-120">Gets the deactivation information for the node.</span></span>
            </para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-121">Die Deaktivierung Knoteninformationen.</span><span class="sxs-lookup"><span data-stu-id="16b19-121">The node deactivation information.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownAt">
      <MemberSignature Language="C#" Value="public DateTime NodeDownAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeDownAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeDownAt : DateTime" Usage="System.Fabric.Query.Node.NodeDownAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-122">Ruft die Datum-Zeit Knotenstatus Änderungszeitpunkt zu nach unten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-122">Gets the date time when node status changed to down.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-123">Datum Uhrzeit Knotenstatus Änderungszeitpunkt zu nach unten.</span><span class="sxs-lookup"><span data-stu-id="16b19-123">The date time when node status changed to down.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeDownTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeDownTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeDownTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeDownTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeDownTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeDownTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeDownTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeDownAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-124">Ruft den Knoten außer Betrieb genommen.</span><span class="sxs-lookup"><span data-stu-id="16b19-124">Gets the node down time.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-125">Der Knoten, außer Betrieb genommen werden soll.</span><span class="sxs-lookup"><span data-stu-id="16b19-125">The node down time.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeId NodeId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.NodeId NodeId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeId As NodeId" />
      <MemberSignature Language="F#" Value="member this.NodeId : System.Fabric.NodeId" Usage="System.Fabric.Query.Node.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-126">Ruft die interne ID, die von Service Fabric verwendet, um einen Knoten eindeutig zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="16b19-126">Gets the internal ID used by Service Fabric to uniquely identify a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-127">Die interne ID, die von Service Fabric verwendet, um einen Knoten eindeutig zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="16b19-127">The internal ID used by Service Fabric to uniquely identify a node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.Query.Node.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-128">Ruft die interne ID, die von Service Fabric verwendet, um eine Knoteninstanz eindeutig zu identifizieren.</span><span class="sxs-lookup"><span data-stu-id="16b19-128">Gets the internal ID used by Service Fabric to uniquely identify a node instance.</span></span> <span data-ttu-id="16b19-129">Die Knoten-ID wird aus der "nodename" deterministisch zugeordnet und ändert sich nicht über den Knoten neu gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="16b19-129">The NodeId is deterministically mapped from NodeName and does not change across node restarts.</span></span> <span data-ttu-id="16b19-130">Allerdings wird die NodeInstanceId bei jedem Neustart des Knotens ändern.</span><span class="sxs-lookup"><span data-stu-id="16b19-130">However, the NodeInstanceId will change with every restart of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-131">Gibt <see cref="T:System.Numerics.BigInteger" />zurück.</span><span class="sxs-lookup"><span data-stu-id="16b19-131">Returns <see cref="T:System.Numerics.BigInteger" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Node.NodeName" />
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
          <para><span data-ttu-id="16b19-132">Ruft den Namen des Knotens ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-132">Gets the name of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-133">Der Name des Knotens.</span><span class="sxs-lookup"><span data-stu-id="16b19-133">The name of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.NodeStatus NodeStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.NodeStatus NodeStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeStatus As NodeStatus" />
      <MemberSignature Language="F#" Value="member this.NodeStatus : System.Fabric.Query.NodeStatus" Usage="System.Fabric.Query.Node.NodeStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.NodeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-134">Ruft den Knotenstatus ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-134">Gets the node status.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-135">Der Knotenstatus.</span><span class="sxs-lookup"><span data-stu-id="16b19-135">The node status.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeType">
      <MemberSignature Language="C#" Value="public string NodeType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeType As String" />
      <MemberSignature Language="F#" Value="member this.NodeType : string" Usage="System.Fabric.Query.Node.NodeType" />
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
          <para><span data-ttu-id="16b19-136">Ruft den Knotentyp ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-136">Gets the node type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-137">Der Knotentyp.</span><span class="sxs-lookup"><span data-stu-id="16b19-137">The node type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpAt">
      <MemberSignature Language="C#" Value="public DateTime NodeUpAt { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime NodeUpAt" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpAt" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpAt As DateTime" />
      <MemberSignature Language="F#" Value="member this.NodeUpAt : DateTime" Usage="System.Fabric.Query.Node.NodeUpAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-138">Ruft das Datum-Uhrzeit Knotenstatus Änderungszeitpunkt zu nach oben.</span><span class="sxs-lookup"><span data-stu-id="16b19-138">Gets the date time when node status changed to up.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-139">Datum Uhrzeit Knotenstatus Änderungszeitpunkt zu nach oben.</span><span class="sxs-lookup"><span data-stu-id="16b19-139">The date time when node status changed to up.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUpTime">
      <MemberSignature Language="C#" Value="public TimeSpan NodeUpTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan NodeUpTime" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.NodeUpTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeUpTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.NodeUpTime : TimeSpan" Usage="System.Fabric.Query.Node.NodeUpTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is deprecated, use NodeUpAt instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="16b19-140">Ruft die knotenbetriebszeit ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-140">Gets the node up time.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-141">Die knotenbetriebszeit.</span><span class="sxs-lookup"><span data-stu-id="16b19-141">The node up time.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomain">
      <MemberSignature Language="C#" Value="public string UpgradeDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomain" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Node.UpgradeDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomain As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomain : string" Usage="System.Fabric.Query.Node.UpgradeDomain" />
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
          <para><span data-ttu-id="16b19-142">Ruft den upgradedomäne-Wert für diesen Knoten ab.</span><span class="sxs-lookup"><span data-stu-id="16b19-142">Gets the upgrade domain value for this node.</span></span> </para>
          <remarks><span data-ttu-id="16b19-143">Upgradedomänen definieren Sätze von Knoten, die ungefähr zur gleichen Zeit für Upgrades heruntergefahren werden.</span><span class="sxs-lookup"><span data-stu-id="16b19-143">Upgrade domains define sets of nodes which are shut down for upgrades at approximately the same time.</span></span></remarks>
        </summary>
        <value>
          <para><span data-ttu-id="16b19-144">Die upgradedomäne für diesen Knoten.</span><span class="sxs-lookup"><span data-stu-id="16b19-144">The upgrade domain for this node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>