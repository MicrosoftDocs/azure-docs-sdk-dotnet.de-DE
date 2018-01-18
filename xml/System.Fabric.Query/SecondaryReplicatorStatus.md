<Type Name="SecondaryReplicatorStatus" FullName="System.Fabric.Query.SecondaryReplicatorStatus">
  <TypeSignature Language="C#" Value="public sealed class SecondaryReplicatorStatus : System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SecondaryReplicatorStatus extends System.Fabric.Query.ReplicatorStatus" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.SecondaryReplicatorStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SecondaryReplicatorStatus&#xA;Inherits ReplicatorStatus" />
  <TypeSignature Language="F#" Value="type SecondaryReplicatorStatus = class&#xA;    inherit ReplicatorStatus" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.ReplicatorStatus</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="1be46-101">Stellt Statistiken zum Service Fabric Replikator, bereit, wenn es in funktioniert einer <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> Rolle.</span><span class="sxs-lookup"><span data-stu-id="1be46-101">Provides statistics about the Service Fabric Replicator, when it is functioning in a <see cref="F:System.Fabric.ReplicaRole.ActiveSecondary" /> role.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecondaryReplicatorStatus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.SecondaryReplicatorStatus.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="1be46-102">Initialisiert eine neue Instanz der <see cref="T:System.Fabric.Query.SecondaryReplicatorStatus" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1be46-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.SecondaryReplicatorStatus" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CopyQueueStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorQueueStatus CopyQueueStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorQueueStatus CopyQueueStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.CopyQueueStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CopyQueueStatus As ReplicatorQueueStatus" />
      <MemberSignature Language="F#" Value="member this.CopyQueueStatus : System.Fabric.Query.ReplicatorQueueStatus" Usage="System.Fabric.Query.SecondaryReplicatorStatus.CopyQueueStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorQueueStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1be46-103">Ruft den Status der Warteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="1be46-103">Gets the status of the Copy queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be46-104">Der Status der Warteschlange kopieren.</span><span class="sxs-lookup"><span data-stu-id="1be46-104">The status of the copy queue.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInBuild">
      <MemberSignature Language="C#" Value="public bool IsInBuild { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInBuild" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.IsInBuild" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInBuild As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInBuild : bool" Usage="System.Fabric.Query.SecondaryReplicatorStatus.IsInBuild" />
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
          <para><span data-ttu-id="1be46-105">Ruft einen Wert, der angibt, ob das Replikat gerade erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="1be46-105">Gets a value that indicates whether the replica is currently being built.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="1be46-106"><languageKeyword>"true"</languageKeyword> , wenn das Replikat erstellt wurde, andernfalls zurzeit ist <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="1be46-106"><languageKeyword>true</languageKeyword> if the replica is currently being built; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastAcknowledgementSentTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastAcknowledgementSentTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastAcknowledgementSentTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastAcknowledgementSentTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastAcknowledgementSentTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastAcknowledgementSentTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastAcknowledgementSentTimeUtc" />
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
          <para><span data-ttu-id="1be46-107">Ruft den letzten-Zeitstempel (UTC) mit dem eine Bestätigung an den primären Replikator gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-107">Gets the last time-stamp (UTC) at which an acknowledgment was sent to the primary replicator.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be46-108">Zeitstempel der letzten-mit der eine Bestätigung an den primären Replikator gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-108">The last time-stamp at which an acknowledgment was sent to the primary replicator.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1be46-109">UTC-0 stellt einen ungültigen Wert dar, der angibt, dass nie eine Bestätigungsnachricht gesendet wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-109">UTC 0 represents an invalid value, indicating that an acknowledgment message was never sent.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastCopyOperationReceivedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastCopyOperationReceivedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastCopyOperationReceivedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastCopyOperationReceivedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastCopyOperationReceivedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastCopyOperationReceivedTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastCopyOperationReceivedTimeUtc" />
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
          <para><span data-ttu-id="1be46-110">Ruft den letzten-Zeitstempel (UTC) an dem ein Vorgang zum Kopieren als Teil eines Builds von der primären empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-110">Gets the last time-stamp (UTC) at which a copy operation was received as part of a build from the primary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be46-111">Zeitstempel der letzten-an dem ein Vorgang zum Kopieren als Teil eines Builds von der primären empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-111">The last time-stamp at which a copy operation was received as part of a build from the primary.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1be46-112">UTC-0 stellt einen ungültigen Wert dar, der angibt, dass eine Kopie Vorgang Nachricht nie empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-112">UTC 0 represents an invalid value, indicating that a copy operation message was never received.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastReplicationOperationReceivedTimeUtc">
      <MemberSignature Language="C#" Value="public DateTime LastReplicationOperationReceivedTimeUtc { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastReplicationOperationReceivedTimeUtc" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.LastReplicationOperationReceivedTimeUtc" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastReplicationOperationReceivedTimeUtc As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastReplicationOperationReceivedTimeUtc : DateTime" Usage="System.Fabric.Query.SecondaryReplicatorStatus.LastReplicationOperationReceivedTimeUtc" />
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
          <para><span data-ttu-id="1be46-113">Ruft den letzten-Zeitstempel (UTC) an dem ein Replikationsvorgang vom primären Server empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-113">Gets the last time-stamp (UTC) at which a replication operation was received from the primary.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be46-114">Zeitstempel der letzten-mit der ein Replikationsvorgang vom primären Server empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-114">The last time-stamp at which a replication operation was received from the primary.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="1be46-115">UTC-0 stellt einen ungültigen Wert dar, der angibt, dass eine Vorgang Replikationsnachricht nie empfangen wurde.</span><span class="sxs-lookup"><span data-stu-id="1be46-115">UTC 0 represents an invalid value, indicating that a replication operation message was never received.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicationQueueStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.ReplicatorQueueStatus ReplicationQueueStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.SecondaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicationQueueStatus As ReplicatorQueueStatus" />
      <MemberSignature Language="F#" Value="member this.ReplicationQueueStatus : System.Fabric.Query.ReplicatorQueueStatus" Usage="System.Fabric.Query.SecondaryReplicatorStatus.ReplicationQueueStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ReplicatorQueueStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="1be46-116">Ruft den Status der Replikationswarteschlange ab.</span><span class="sxs-lookup"><span data-stu-id="1be46-116">Gets the status of the Replication queue.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="1be46-117">Der Status der Replikationswarteschlange.</span><span class="sxs-lookup"><span data-stu-id="1be46-117">The status of the replication queue.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>