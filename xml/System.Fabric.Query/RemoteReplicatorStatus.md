<Type Name="RemoteReplicatorStatus" FullName="System.Fabric.Query.RemoteReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class RemoteReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit RemoteReplicatorStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.RemoteReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class RemoteReplicatorStatus" />
  <TypeSignature Language="F#" Value="type RemoteReplicatorStatus = class" />
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
      <para><span data-ttu-id="17ec6-101">Stellt den Status der sekundären Replikator aus Sicht der primären Replikator dar.</span><span class="sxs-lookup"><span data-stu-id="17ec6-101">Represents the state of the secondary replicator from the primary replicator’s point of view.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RemoteReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.RemoteReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="17ec6-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.RemoteReplicatorStatus" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17ec6-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.RemoteReplicatorStatus" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInBuild">
      <MemberSignature Language="C#" Value="public bool IsInBuild { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInBuild" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInBuild : bool" Usage="System.Fabric.Query.RemoteReplicatorStatus.IsInBuild" />
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
          <para><span data-ttu-id="17ec6-103">Ruft einen Wert, der angibt, ob das sekundäre Replikat wird gerade erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="17ec6-103">Gets a value that indicates whether the secondary replica is in the process of being built.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="17ec6-104"><languageKeyword>"true"</languageKeyword> Wenn das sekundäre Replikat gerade erstellt wurde, andernfalls wird <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="17ec6-104"><languageKeyword>true</languageKeyword> if the secondary replica is in the process of being built; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAcknowledgementProcessedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastAcknowledgementProcessedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAcknowledgementProcessedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastAcknowledgementProcessedTimeUtc : DateTime" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAcknowledgementProcessedTimeUtc" />
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
          <para><span data-ttu-id="17ec6-105">Ruft den Zeitstempel der letzten (in UTC) Wenn eine Bestätigung vom sekundären Replikator in der primären verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="17ec6-105">Gets the last timestamp (in UTC) when an acknowledgement from the secondary replicator was processed in the primary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-106">Der letzte Zeitstempel in der primären eine Bestätigung vom sekundären Replikator verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="17ec6-106">The last timestamp when an acknowledgement from the secondary replicator was processed in the primary.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="17ec6-107">UTC-0 stellt einen ungültigen Wert dar, der angibt, dass keine Bestätigungsnachrichten jemals verarbeitet wurden.</span><span class="sxs-lookup"><span data-stu-id="17ec6-107">UTC 0 represents an invalid value, indicating that no acknowledgement messages were ever processed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedCopySequenceNumber" />
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
          <para><span data-ttu-id="17ec6-108">Höchste Kopie Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank den Zustand angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-108">Gets the highest copy operation sequence number that the secondary has applied to its state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-109">Die höchste Kopie Vorgang Sequenznummer, die die sekundäre Datenbank den Zustand angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-109">The highest copy operation sequence number that the secondary has applied to its state.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="17ec6-110">Der Wert "1", kann ignoriert werden, da er gibt an, dass der Kopiervorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="17ec6-110">A value of ‘-1’ can be ignored since it indicates that the copy process is complete.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAppliedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastAppliedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAppliedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastAppliedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastAppliedReplicationSequenceNumber" />
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
          <para><span data-ttu-id="17ec6-111">Höchste Replikation Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank den Zustand angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-111">Gets the highest replication operation sequence number that the secondary has applied to its state.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-112">Die höchste Replikation Vorgang Sequenznummer, die die sekundäre Datenbank den Zustand angewendet hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-112">The highest replication operation sequence number that the secondary has applied to its state.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedCopySequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedCopySequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedCopySequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedCopySequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedCopySequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedCopySequenceNumber" />
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
          <para><span data-ttu-id="17ec6-113">Höchste Kopie Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank vom primären Server empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-113">Gets the highest copy operation sequence number that the secondary has received from the primary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-114">Die höchste Kopie Vorgang Sequenznummer, die die sekundäre Datenbank vom primären Server empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-114">The highest copy operation sequence number that the secondary has received from the primary.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="17ec6-115">Der Wert "1", kann ignoriert werden, da er gibt an, dass der Kopiervorgang abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="17ec6-115">A value of ‘-1’ can be ignored since it indicates that the copy process is complete.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReceivedReplicationSequenceNumber">
      <MemberSignature Language="C#" Value="public long LastReceivedReplicationSequenceNumber { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReceivedReplicationSequenceNumber As Long" />
      <MemberSignature Language="F#" Value="member this.LastReceivedReplicationSequenceNumber : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.LastReceivedReplicationSequenceNumber" />
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
          <para><span data-ttu-id="17ec6-116">Höchste Replikation Vorgang ruft die Sequenznummer ab, der die sekundäre Datenbank vom primären Server empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-116">Gets the highest replication operation sequence number that the secondary has received from the primary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-117">Die höchste Replikation Vorgang Sequenznummer, die die sekundäre Datenbank vom primären Server empfangen hat.</span><span class="sxs-lookup"><span data-stu-id="17ec6-117">The highest replication operation sequence number that the secondary has received from the primary.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteReplicatorAcknowledgementStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.RemoteReplicatorAcknowledgementStatus RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteReplicatorAcknowledgementStatus As RemoteReplicatorAcknowledgementStatus" />
      <MemberSignature Language="F#" Value="member this.RemoteReplicatorAcknowledgementStatus : System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" Usage="System.Fabric.Query.RemoteReplicatorStatus.RemoteReplicatorAcknowledgementStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.RemoteReplicatorAcknowledgementStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="17ec6-118">Bestätigung Zahlen enthält, für jeden remote Replikatoren</span><span class="sxs-lookup"><span data-stu-id="17ec6-118">Contains acknowledgement numbers for each of the remote replicators</span></span></para>
          <para><span data-ttu-id="17ec6-119">Die Werte sind abhängig von den Status der Replikate.</span><span class="sxs-lookup"><span data-stu-id="17ec6-119">The values are dependent on the status of the replicas.</span></span> <span data-ttu-id="17ec6-120">InBuild-Replikaten enthält Werte, die über kopieren können, während aktive Replias nicht wird.</span><span class="sxs-lookup"><span data-stu-id="17ec6-120">Inbuild replicas will contain values pertaining to copy while active replias will not.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-121">RemoteReplicatorAcknowledgementStatus-Objekt, die Details in Bezug auf die Replikation und kopieren Sie Stream-Bestätigung enthält.</span><span class="sxs-lookup"><span data-stu-id="17ec6-121">RemoteReplicatorAcknowledgementStatus object containing details regarding replication and copy stream acknowledgement.</span></span> <span data-ttu-id="17ec6-122">Weitere Informationen finden Sie unter <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" /> .</span><span class="sxs-lookup"><span data-stu-id="17ec6-122">See <see cref="T:System.Fabric.Query.RemoteReplicatorAcknowledgementStatus" /> for more information.</span></span> </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicaId">
      <MemberSignature Language="C#" Value="public long ReplicaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReplicaId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicaId As Long" />
      <MemberSignature Language="F#" Value="member this.ReplicaId : int64" Usage="System.Fabric.Query.RemoteReplicatorStatus.ReplicaId" />
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
          <para><span data-ttu-id="17ec6-123">Ruft die Replikat-ID der sekundären Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="17ec6-123">Gets the replica ID of the secondary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="17ec6-124">Die Replikat-ID</span><span class="sxs-lookup"><span data-stu-id="17ec6-124">The replica ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>