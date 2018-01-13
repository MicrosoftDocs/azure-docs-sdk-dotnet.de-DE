<Type Name="DeployedServiceReplica" FullName="System.Fabric.Query.DeployedServiceReplica">
  <TypeSignature Language="C#" Value="public abstract class DeployedServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit DeployedServiceReplica extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceReplica" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class DeployedServiceReplica" />
  <TypeSignature Language="F#" Value="type DeployedServiceReplica = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatefulServiceReplica))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.DeployedStatelessServiceInstance))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="41897-101">Stellt die Ansicht eines Replikats auf einen Knoten dar.</span><span class="sxs-lookup"><span data-stu-id="41897-101">Represents the view of a replica on a node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected internal DeployedServiceReplica (System.Fabric.Query.ServiceKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method familyorassemblyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedServiceReplica.#ctor(System.Fabric.Query.ServiceKind)" />
      <MemberSignature Language="VB.NET" Value="Protected Friend Sub New (kind As ServiceKind)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.DeployedServiceReplica : System.Fabric.Query.ServiceKind -&gt; System.Fabric.Query.DeployedServiceReplica" Usage="new System.Fabric.Query.DeployedServiceReplica kind" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="kind" Type="System.Fabric.Query.ServiceKind" />
      </Parameters>
      <Docs>
        <param name="kind">
          <para><span data-ttu-id="41897-102">Die Art des Diensts.</span><span class="sxs-lookup"><span data-stu-id="41897-102">The service kind.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="41897-103">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.DeployedServiceReplica" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="41897-103">Initializes a new instance of the <see cref="T:System.Fabric.Query.DeployedServiceReplica" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Address">
      <MemberSignature Language="C#" Value="public string Address { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Address" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.Address" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Address As String" />
      <MemberSignature Language="F#" Value="member this.Address : string" Usage="System.Fabric.Query.DeployedServiceReplica.Address" />
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
          <para><span data-ttu-id="41897-104">Die letzte Adresse, von dem Replikat im Status Open oder ChangeRole zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="41897-104">The last address returned by the replica in Open or ChangeRole.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-105">Die letzte Adresse, von dem Replikat im Status Open oder ChangeRole zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="41897-105">The last address returned by the replica in Open or ChangeRole.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedServiceReplica.CodePackageName" />
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
          <para><span data-ttu-id="41897-106">Der Name des Code-Pakets, die dieses Replikat hostet.</span><span class="sxs-lookup"><span data-stu-id="41897-106">The name of the code package that hosts this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-107">Der Name des Code-Pakets, die dieses Replikat hostet.</span><span class="sxs-lookup"><span data-stu-id="41897-107">The name of the code package that hosts this replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostProcessId">
      <MemberSignature Language="C#" Value="public long HostProcessId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 HostProcessId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.HostProcessId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostProcessId As Long" />
      <MemberSignature Language="F#" Value="member this.HostProcessId : int64" Usage="System.Fabric.Query.DeployedServiceReplica.HostProcessId" />
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
          <para><span data-ttu-id="41897-108">Die Host-Prozess-Id an.</span><span class="sxs-lookup"><span data-stu-id="41897-108">The host process id.</span></span></para>
          <value><span data-ttu-id="41897-109">Dies wird 0 (null) sein, wenn das Replikat nicht ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="41897-109">This will be zero if the replica is down.</span></span></value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Partitionid">
      <MemberSignature Language="C#" Value="public Guid Partitionid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid Partitionid" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.Partitionid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Partitionid As Guid" />
      <MemberSignature Language="F#" Value="member this.Partitionid : Guid" Usage="System.Fabric.Query.DeployedServiceReplica.Partitionid" />
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
          <para><span data-ttu-id="41897-110">Die Partitions-Id für diese Replia.</span><span class="sxs-lookup"><span data-stu-id="41897-110">The partition id for this replia.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-111">Die Partitions-Id für diese Replia.</span><span class="sxs-lookup"><span data-stu-id="41897-111">The partition id for this replia.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ServiceReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ServiceReplicaStatus" Usage="System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="41897-112">Der Status des Replikats.</span><span class="sxs-lookup"><span data-stu-id="41897-112">The status of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-113">Der Status des Replikats.</span><span class="sxs-lookup"><span data-stu-id="41897-113">The status of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceKind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceKind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="41897-114">Der Typ des Replikats (Zustandsbehaftet oder Stateless).</span><span class="sxs-lookup"><span data-stu-id="41897-114">The type of the replica (Stateful or Stateless).</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-115">Gibt <see cref="T:System.Fabric.Query.ServiceKind" />zurück.</span><span class="sxs-lookup"><span data-stu-id="41897-115">Returns <see cref="T:System.Fabric.Query.ServiceKind" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceManifestName" />
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
          <para><span data-ttu-id="41897-116">Der Name des Dienstpakets mit dem Codepaket dieses Replikat hostet.</span><span class="sxs-lookup"><span data-stu-id="41897-116">The name of the service package that contains the code package hosting this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-117">Gibt <see cref="T:System.String" />zurück.</span><span class="sxs-lookup"><span data-stu-id="41897-117">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestVersion">
      <MemberSignature Language="C#" Value="public string ServiceManifestVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceManifestVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestVersion As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestVersion : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceManifestVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This property is no longer supported", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="41897-118">Die Version des Servicemanifests.</span><span class="sxs-lookup"><span data-stu-id="41897-118">The version of the service manifest.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-119">Die Version des Servicemanifests.</span><span class="sxs-lookup"><span data-stu-id="41897-119">The version of the service manifest.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceName" />
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
          <para><span data-ttu-id="41897-120">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="41897-120">The name of the service.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-121">Der Name des Diensts.</span><span class="sxs-lookup"><span data-stu-id="41897-121">The name of the service.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" />
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
            <span data-ttu-id="41897-122">Die ActivationId des Dienstpakets.</span><span class="sxs-lookup"><span data-stu-id="41897-122">The ActivationId of service package.</span></span>
            </summary>
        <value>
          <para>
            <span data-ttu-id="41897-123">Eine Zeichenfolge von bereitgestelltes Dienstpaket ActivationId darstellt.</span><span class="sxs-lookup"><span data-stu-id="41897-123">A string representing ActivationId of deployed service package.</span></span> <span data-ttu-id="41897-124">Wenn <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> angegeben zum Zeitpunkt der Erstellung der Dienst ist <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (oder wenn sie nicht angegeben wird, in diesem Fall wird standardmäßig <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), klicken Sie dann einen Wert von <see cref="P:System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" /> ist immer eine leere Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="41897-124">If <see cref="T:System.Fabric.Description.ServicePackageActivationMode" /> specified at the time of creating the service is <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" /> (or if it is not specified, in which case it defaults to <see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />), then value of <see cref="P:System.Fabric.Query.DeployedServiceReplica.ServicePackageActivationId" /> is always an empty string.</span></span>
            <span data-ttu-id="41897-125">Einzelheiten dazu finden Sie <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span><span class="sxs-lookup"><span data-stu-id="41897-125">For more details please see <see cref="T:System.Fabric.Description.ServicePackageActivationMode" />.</span></span>
            </para>
          <remarks>
            <span data-ttu-id="41897-126">Dies kann null-Wert aufweisen, wenn <see cref="P:System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" /> ist außer <see cref="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />, <see cref="F:System.Fabric.Query.ServiceReplicaStatus.Standby" /> oder <see cref="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />.</span><span class="sxs-lookup"><span data-stu-id="41897-126">This can have null value if <see cref="P:System.Fabric.Query.DeployedServiceReplica.ReplicaStatus" /> is other than <see cref="F:System.Fabric.Query.ServiceReplicaStatus.InBuild" />, <see cref="F:System.Fabric.Query.ServiceReplicaStatus.Standby" /> or <see cref="F:System.Fabric.Query.ServiceReplicaStatus.Ready" />.</span></span>
            </remarks>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceReplica.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.DeployedServiceReplica.ServiceTypeName" />
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
          <para><span data-ttu-id="41897-127">Den Namen des Diensttyps.</span><span class="sxs-lookup"><span data-stu-id="41897-127">The name of the service type.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="41897-128">Den Namen des Diensttyps.</span><span class="sxs-lookup"><span data-stu-id="41897-128">The name of the service type.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>