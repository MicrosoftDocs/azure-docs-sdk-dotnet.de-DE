<Type Name="DeployedStatefulServiceReplicaDetail" FullName="System.Fabric.Query.DeployedStatefulServiceReplicaDetail">
  <TypeSignature Language="C#" Value="public sealed class DeployedStatefulServiceReplicaDetail : System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedStatefulServiceReplicaDetail extends System.Fabric.Query.DeployedServiceReplicaDetail" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedStatefulServiceReplicaDetail&#xA;Inherits DeployedServiceReplicaDetail" />
  <TypeSignature Language="F#" Value="type DeployedStatefulServiceReplicaDetail = class&#xA;    inherit DeployedServiceReplicaDetail" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.DeployedServiceReplicaDetail</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="8bb44-101">Stellt die Informationen über ein zustandsbehaftetes Replikat in einem Codepaket ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8bb44-101">Represents the information about a stateful replica running in a code package.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeployedStatefulServiceReplicaDetail ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8bb44-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.DeployedStatefulServiceReplicaDetail" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentReplicatorOperation">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ReplicatorOperationName CurrentReplicatorOperation" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentReplicatorOperation As ReplicatorOperationName" />
      <MemberSignature Language="F#" Value="member this.CurrentReplicatorOperation : System.Fabric.Query.ReplicatorOperationName" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.CurrentReplicatorOperation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorOperationName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-103">Ruft die aktuellen-APIs auf Replikator ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8bb44-103">Gets the current APIs running on the replicator.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8bb44-104">Die aktuelle-APIs auf Replikator ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8bb44-104">The current APIs running on the replicator.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedServiceReplica">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.DeployedStatefulServiceReplica DeployedServiceReplica" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedServiceReplica As DeployedStatefulServiceReplica" />
      <MemberSignature Language="F#" Value="member this.DeployedServiceReplica : System.Fabric.Query.DeployedStatefulServiceReplica" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.DeployedServiceReplica" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.DeployedStatefulServiceReplica</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-105">Ruft zusätzliche Details zu den bereitgestellten dienstreplikats wie replikatrolle, Host-Prozess-ID, Informationen zur Neukonfiguration ab.</span><span class="sxs-lookup"><span data-stu-id="8bb44-105">Gets additonal details about the deployed service replica like replica role, host processId, information about reconfiguration.</span></span></para>
          <value><span data-ttu-id="8bb44-106">Replikat-Details.</span><span class="sxs-lookup"><span data-stu-id="8bb44-106">Replica Detail.</span></span></value>
        </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus ReadStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus ReadStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.ReadStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReadStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-107">Ruft den aktuellen Status für dieses Replikat zu lesen.</span><span class="sxs-lookup"><span data-stu-id="8bb44-107">Gets the current read status for this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8bb44-108">Aktuellen Status für dieses Replikat zu lesen.</span><span class="sxs-lookup"><span data-stu-id="8bb44-108">The current read status for this replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaId" />
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
          <para><span data-ttu-id="8bb44-109">Ruft die Replikat-ID für dieses Replikat.</span><span class="sxs-lookup"><span data-stu-id="8bb44-109">Gets the replica ID of this replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8bb44-110">Die Replikat-ID</span><span class="sxs-lookup"><span data-stu-id="8bb44-110">The replica ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicaStatus ReplicaStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicaStatus ReplicaStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaStatus As ReplicaStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicaStatus : System.Fabric.Query.ReplicaStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicaStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicaStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8bb44-111">Ruft einen Wert, der angibt, des Status des aktuellen Replikats.</span><span class="sxs-lookup"><span data-stu-id="8bb44-111">Gets a value indicating the status of the current replica.</span></span>
            </summary>
        <value><span data-ttu-id="8bb44-112">Der Status des Replikats.</span><span class="sxs-lookup"><span data-stu-id="8bb44-112">The replica status.</span></span></value>
        <remarks><span data-ttu-id="8bb44-113">Derzeit nur Replikate des Typs <see cref="T:System.Fabric.KeyValueStoreReplica" /> Statusdetails Abfrage erzeugt.</span><span class="sxs-lookup"><span data-stu-id="8bb44-113">Currently, only replicas of type <see cref="T:System.Fabric.KeyValueStoreReplica" /> will produce query status details.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorStatus ReplicatorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorStatus ReplicatorStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorStatus As ReplicatorStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicatorStatus : System.Fabric.Query.ReplicatorStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.ReplicatorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-114">Ruft die Informationen zur Replikator ab, wenn das Replikat Replikator Fabric-Dienst verwendet wird</span><span class="sxs-lookup"><span data-stu-id="8bb44-114">Gets the information about the replicator if the replica is using the Service Fabric Replicator</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8bb44-115">Der Replikator-Status.</span><span class="sxs-lookup"><span data-stu-id="8bb44-115">The replicator status.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.PartitionAccessStatus WriteStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PartitionAccessStatus WriteStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteStatus As PartitionAccessStatus" />
      <MemberSignature Language="F#" Value="member this.WriteStatus : System.Fabric.PartitionAccessStatus" Usage="System.Fabric.Query.DeployedStatefulServiceReplicaDetail.WriteStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PartitionAccessStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="8bb44-116">Ruft den aktuellen Schreibstatus des Replikats ab.</span><span class="sxs-lookup"><span data-stu-id="8bb44-116">Gets the current write status of the replica.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="8bb44-117">Der aktuellen Status des Replikats geschrieben werden.</span><span class="sxs-lookup"><span data-stu-id="8bb44-117">The current write status of the replica.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>