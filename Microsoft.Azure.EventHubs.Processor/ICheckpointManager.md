<Type Name="ICheckpointManager" FullName="Microsoft.Azure.EventHubs.Processor.ICheckpointManager">
  <TypeSignature Language="C#" Value="public interface ICheckpointManager" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICheckpointManager" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.EventHubs.Processor.ICheckpointManager" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICheckpointManager" />
  <TypeSignature Language="F#" Value="type ICheckpointManager = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
    <AssemblyVersion>1.0.1.0</AssemblyVersion>
    <AssemblyVersion>1.0.3.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d4ce4-101">Wenn Sie EventProcessorHost Prüfpunkte an einer anderen Stelle als Azure-Speicher gespeichert haben möchten, können Sie eigene Verwendung dieser Schnittstelle Checkpoint-Manager schreiben.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-101">If you wish to have EventProcessorHost store checkpoints somewhere other than Azure Storage, you can write your own checkpoint manager using this interface.</span></span>  
            
            <span data-ttu-id="d4ce4-102"><para>Die Azure-Speicher-Manager verwenden den gleichen Speicher wie für Lease und Prüfpunkte, sodass beide Schnittstellen von derselben Klasse implementiert werden. Sie können dasselbe nicht tun, wenn Sie einheitlichen Speicher für beide Arten von Daten. </para> <para>Diese Schnittstelle nicht Initialisierungsmethoden angeben, da es keine Möglichkeit, zu wissen, welche Informationen, die Ihre Implementierung haben.</para></span><span class="sxs-lookup"><span data-stu-id="d4ce4-102"><para>The Azure Storage managers use the same storage for both lease and checkpoints, so both interfaces are implemented by the same class. You are free to do the same thing if you have a unified store for both types of data.</para><para>This interface does not specify initialization methods because we have no way of knowing what information your implementation will require.</para></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CheckpointStoreExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CheckpointStoreExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CheckpointStoreExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CheckpointStoreExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CheckpointStoreExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CheckpointStoreExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CheckpointStoreExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4ce4-103">Ist der Prüfpunkts Store vorhanden?</span><span class="sxs-lookup"><span data-stu-id="d4ce4-103">Does the checkpoint store exist?</span></span>
            </summary>
        <returns><span data-ttu-id="d4ce4-104">"true", wenn es "false" Falls nicht vorhanden ist,</span><span class="sxs-lookup"><span data-stu-id="d4ce4-104">true if it exists, false if not</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; CreateCheckpointIfNotExistsAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointIfNotExistsAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointIfNotExistsAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointIfNotExistsAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.CreateCheckpointIfNotExistsAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="d4ce4-105">Die ID der Partition zum Erstellen des Prüfpunkts für.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-105">Id of partition to create the checkpoint for.</span></span></param>
        <summary>
            <span data-ttu-id="d4ce4-106">Erstellen Sie den Prüfpunkt für die angegebene Partition aus, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-106">Create the checkpoint for the given partition if it doesn't exist.</span></span> <span data-ttu-id="d4ce4-107">Tun Sie nichts, wenn sie vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-107">Do nothing if it does exist.</span></span>
            <span data-ttu-id="d4ce4-108">Der Offset/SequenceNumber für einen neu erstellten Prüfpunkt sollte auf StartOfStream/0 festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-108">The offset/sequenceNumber for a freshly-created checkpoint should be set to StartOfStream/0.</span></span>
            </summary>
        <returns><span data-ttu-id="d4ce4-109">Der Prüfpunkt für die angegebene Partition, ob bereits vorhandene oder neu erstellt.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-109">The checkpoint for the given partition, whether newly created or already existing.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCheckpointStoreIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateCheckpointStoreIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.CreateCheckpointStoreIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateCheckpointStoreIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateCheckpointStoreIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iCheckpointManager.CreateCheckpointStoreIfNotExistsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d4ce4-110">Erstellen Sie die Prüfpunkt-Speicher, wenn er nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-110">Create the checkpoint store if it doesn't exist.</span></span> <span data-ttu-id="d4ce4-111">Tun Sie nichts, wenn sie vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-111">Do nothing if it does exist.</span></span>
            </summary>
        <returns><span data-ttu-id="d4ce4-112">"true", wenn der Prüfpunkt-Speicher ist bereits vorhanden oder "OK". "false" erstellt wurde, wenn ein Fehler aufgetreten</span><span class="sxs-lookup"><span data-stu-id="d4ce4-112">true if the checkpoint store already exists or was created OK, false if there was a failure</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.DeleteCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteCheckpointAsync (partitionId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteCheckpointAsync : string -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.DeleteCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="d4ce4-113">ID der Partition So löschen Sie den Prüfpunkt aus Speicher</span><span class="sxs-lookup"><span data-stu-id="d4ce4-113">id of partition to delete checkpoint from store</span></span></param>
        <summary>
            <span data-ttu-id="d4ce4-114">Löschen Sie die gespeicherten Prüfpunkt für die angegebene Partition.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-114">Delete the stored checkpoint for the given partition.</span></span> <span data-ttu-id="d4ce4-115">Wenn keine gespeicherten Prüfpunkt für die angegebene Partition, die als erfolgreich eingestuft ist.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-115">If there is no stored checkpoint for the given partition, that is treated as success.</span></span>
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync (string partitionId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.EventHubs.Processor.Checkpoint&gt; GetCheckpointAsync(string partitionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.GetCheckpointAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCheckpointAsync (partitionId As String) As Task(Of Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member GetCheckpointAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;" Usage="iCheckpointManager.GetCheckpointAsync partitionId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.EventHubs.Processor.Checkpoint&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="partitionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="partitionId"><span data-ttu-id="d4ce4-116">Die ID der Partition zum Abrufen von Prüfpunktdatei-Informationen für.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-116">Id of partition to get checkpoint info for.</span></span></param>
        <summary>
            <span data-ttu-id="d4ce4-117">Abrufen der Prüfpunktdaten auf der angegebenen Partition zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-117">Get the checkpoint data associated with the given partition.</span></span> <span data-ttu-id="d4ce4-118">Kann null zurück, wenn kein Prüfpunkt für die Partition erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-118">Could return null if no checkpoint has been created for that partition.</span></span>
            </summary>
        <returns><span data-ttu-id="d4ce4-119">Prüfpunkt-Informationen für die angegebene Partition oder Null, wenn keine zuvor gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-119">Checkpoint info for the given partition, or null if none has been previously stored.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync checkpoint" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateCheckpointAsync(Lease lease, Checkpoint checkpoint) instead", true)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="checkpoint"><span data-ttu-id="d4ce4-120">Offset/SequeceNumber zum Aktualisieren des Speichers mit.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-120">offset/sequeceNumber to update the store with.</span></span></param>
        <summary>
            <span data-ttu-id="d4ce4-121">Aktualisieren Sie den Prüfpunkt im Speicher mit den Offset/SequenceNumber im bereitgestellten Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-121">Update the checkpoint in the store with the offset/sequenceNumber in the provided checkpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCheckpointAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateCheckpointAsync (Microsoft.Azure.EventHubs.Processor.Lease lease, Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateCheckpointAsync(class Microsoft.Azure.EventHubs.Processor.Lease lease, class Microsoft.Azure.EventHubs.Processor.Checkpoint checkpoint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.EventHubs.Processor.ICheckpointManager.UpdateCheckpointAsync(Microsoft.Azure.EventHubs.Processor.Lease,Microsoft.Azure.EventHubs.Processor.Checkpoint)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCheckpointAsync : Microsoft.Azure.EventHubs.Processor.Lease * Microsoft.Azure.EventHubs.Processor.Checkpoint -&gt; System.Threading.Tasks.Task" Usage="iCheckpointManager.UpdateCheckpointAsync (lease, checkpoint)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.EventHubs.Processor</AssemblyName>
        <AssemblyVersion>1.0.1.0</AssemblyVersion>
        <AssemblyVersion>1.0.3.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="lease" Type="Microsoft.Azure.EventHubs.Processor.Lease" />
        <Parameter Name="checkpoint" Type="Microsoft.Azure.EventHubs.Processor.Checkpoint" />
      </Parameters>
      <Docs>
        <param name="lease"><span data-ttu-id="d4ce4-122">Die Partitionsinformationen für die Durchführung ein Prüfpunkts.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-122">Partition information against which to perform a checkpoint.</span></span></param>
        <param name="checkpoint"><span data-ttu-id="d4ce4-123">Offset/SequeceNumber zum Aktualisieren des Speichers mit.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-123">offset/sequeceNumber to update the store with.</span></span></param>
        <summary>
            <span data-ttu-id="d4ce4-124">Aktualisieren Sie den Prüfpunkt im Speicher mit den Offset/SequenceNumber im bereitgestellten Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="d4ce4-124">Update the checkpoint in the store with the offset/sequenceNumber in the provided checkpoint.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>