<Type Name="Replica" FullName="System.Fabric.Query.Replica">
  <TypeSignature Language="C#" Value="public abstract class Replica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit Replica extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.Replica" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class Replica" />
  <TypeSignature Language="F#" Value="type Replica = class" />
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
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatelessServiceInstance))</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.KnownType(typeof(System.Fabric.Query.StatefulServiceReplica))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
      <para><span data-ttu-id="51647-101">Stellt ein Replikat für die Abfrage an.</span><span class="sxs-lookup"><span data-stu-id="51647-101">Represents a query replica.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected Replica (System.Fabric.Query.ServiceKind serviceKind, long id, System.Fabric.Query.ServiceReplicaStatus replicaStatus, System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, TimeSpan lastInBuildDuration);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.Query.ServiceKind serviceKind, int64 id, valuetype System.Fabric.Query.ServiceReplicaStatus replicaStatus, valuetype System.Fabric.Health.HealthState healthState, string replicaAddress, string nodeName, valuetype System.TimeSpan lastInBuildDuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.Replica.#ctor(System.Fabric.Query.ServiceKind,System.Int64,System.Fabric.Query.ServiceReplicaStatus,System.Fabric.Health.HealthState,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Query.Replica : System.Fabric.Query.ServiceKind * int64 * System.Fabric.Query.ServiceReplicaStatus * System.Fabric.Health.HealthState * string * string * TimeSpan -&gt; System.Fabric.Query.Replica" Usage="new System.Fabric.Query.Replica (serviceKind, id, replicaStatus, healthState, replicaAddress, nodeName, lastInBuildDuration)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceKind" Type="System.Fabric.Query.ServiceKind" />
        <Parameter Name="id" Type="System.Int64" />
        <Parameter Name="replicaStatus" Type="System.Fabric.Query.ServiceReplicaStatus" />
        <Parameter Name="healthState" Type="System.Fabric.Health.HealthState" />
        <Parameter Name="replicaAddress" Type="System.String" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="lastInBuildDuration" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceKind">
          <para><span data-ttu-id="51647-102">Der Typ des Replikats</span><span class="sxs-lookup"><span data-stu-id="51647-102">The type of the replica</span></span></para>
        </param>
        <param name="id">
          <para><span data-ttu-id="51647-103">Die Replikat-ID</span><span class="sxs-lookup"><span data-stu-id="51647-103">The replica ID</span></span></para>
        </param>
        <param name="replicaStatus">
          <para><span data-ttu-id="51647-104">Mit wird der Status-Replikat initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="51647-104">The status replica will be initialized with.</span></span></para>
        </param>
        <param name="healthState">
          <para><span data-ttu-id="51647-105">Mit wird die Integrität-Status-Replikat initialisiert werden</span><span class="sxs-lookup"><span data-stu-id="51647-105">The health state replica will be initialized with</span></span></para>
        </param>
        <param name="replicaAddress">
          <para><span data-ttu-id="51647-106">Mit wird die Adresse-Replikat initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="51647-106">The address replica will be initialized with.</span></span></para>
        </param>
        <param name="nodeName">
          <para><span data-ttu-id="51647-107">Das Replikat der Knoten-Name wird mit initialisiert werden</span><span class="sxs-lookup"><span data-stu-id="51647-107">The node name replica will be initialized with</span></span></para>
        </param>
        <param name="lastInBuildDuration">
          <para><span data-ttu-id="51647-108">Das letzte in Build Dauer Replikat wird mit initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="51647-108">The last in build duration replica will be initialized with.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="51647-109">Initialisiert ein Replikat</span><span class="sxs-lookup"><span data-stu-id="51647-109">Initializes a replica</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HealthState">
      <MemberSignature Language="C#" Value="public System.Fabric.Health.HealthState HealthState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Health.HealthState HealthState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.HealthState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HealthState As HealthState" />
      <MemberSignature Language="F#" Value="member this.HealthState : System.Fabric.Health.HealthState" Usage="System.Fabric.Query.Replica.HealthState" />
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
          <para><span data-ttu-id="51647-110">Ruft den Integritätsstatus des Replikats ab.</span><span class="sxs-lookup"><span data-stu-id="51647-110">Gets the health state of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-111">Der Integritätsstatus des Replikats.</span><span class="sxs-lookup"><span data-stu-id="51647-111">The health state of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public long Id { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Id" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As Long" />
      <MemberSignature Language="F#" Value="member this.Id : int64 with get, set" Usage="System.Fabric.Query.Replica.Id" />
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
          <para><span data-ttu-id="51647-112">Ruft die Replikat-ID ab.</span><span class="sxs-lookup"><span data-stu-id="51647-112">Gets the replica identifier.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-113">Der Bezeichner des Replikats.</span><span class="sxs-lookup"><span data-stu-id="51647-113">The replica identifier.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDuration">
      <MemberSignature Language="C#" Value="public TimeSpan LastInBuildDuration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LastInBuildDuration" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastInBuildDuration As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDuration : TimeSpan" Usage="System.Fabric.Query.Replica.LastInBuildDuration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="51647-114">Ruft erstellen im letzten Dauer.</span><span class="sxs-lookup"><span data-stu-id="51647-114">Gets last in build duration.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-115">Die letzte Builddauer.</span><span class="sxs-lookup"><span data-stu-id="51647-115">The last in build duration.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastInBuildDurationInSeconds">
      <MemberSignature Language="C#" Value="protected internal long LastInBuildDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastInBuildDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Protected Friend ReadOnly Property LastInBuildDurationInSeconds As Long" />
      <MemberSignature Language="F#" Value="member this.LastInBuildDurationInSeconds : int64" Usage="System.Fabric.Query.Replica.LastInBuildDurationInSeconds" />
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
            <span data-ttu-id="51647-116">Ruft letzte Builddauer in Sekunden ab.</span><span class="sxs-lookup"><span data-stu-id="51647-116">Gets last in build duration in seconds.</span></span>
            </summary>
        <value><span data-ttu-id="51647-117">Erstellen Sie zuletzt in die Dauer in Sekunden.</span><span class="sxs-lookup"><span data-stu-id="51647-117">Last in build duration in seconds.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Query.Replica.NodeName" />
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
          <para><span data-ttu-id="51647-118">Ruft den Knotennamen, auf den das Replikat ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="51647-118">Gets the node name the replica is running on.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-119">Der Name des Knotens des Replikats ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="51647-119">The node name the replica is running on.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaAddress">
      <MemberSignature Language="C#" Value="public string ReplicaAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ReplicaAddress" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaAddress As String" />
      <MemberSignature Language="F#" Value="member this.ReplicaAddress : string" Usage="System.Fabric.Query.Replica.ReplicaAddress" />
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
          <para><span data-ttu-id="51647-120">Ruft die Adresse, an der das Replikat empfangsbereit ist.</span><span class="sxs-lookup"><span data-stu-id="51647-120">Gets the address the replica is listening on.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-121">Die Adresse des Replikats überwacht wird.</span><span class="sxs-lookup"><span data-stu-id="51647-121">The address the replica is listening on.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ServiceReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ServiceReplicaStatus" Usage="System.Fabric.Query.Replica.ReplicaStatus" />
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
          <para><span data-ttu-id="51647-122">Ruft den Status des Replikats ab.</span><span class="sxs-lookup"><span data-stu-id="51647-122">Gets the status of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="51647-123">Der Status des Replikats.</span><span class="sxs-lookup"><span data-stu-id="51647-123">The status of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceKind">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceKind ServiceKind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceKind ServiceKind" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.Replica.ServiceKind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceKind As ServiceKind" />
      <MemberSignature Language="F#" Value="member this.ServiceKind : System.Fabric.Query.ServiceKind" Usage="System.Fabric.Query.Replica.ServiceKind" />
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
            <span data-ttu-id="51647-124">Ruft die Art des Diensts ab.</span><span class="sxs-lookup"><span data-stu-id="51647-124">Gets the service kind.</span></span>
            </summary>
        <value><span data-ttu-id="51647-125">Die Art des Diensts.</span><span class="sxs-lookup"><span data-stu-id="51647-125">The service kind.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>