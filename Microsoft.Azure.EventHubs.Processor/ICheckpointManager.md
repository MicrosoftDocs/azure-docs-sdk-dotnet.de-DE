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
            Wenn Sie EventProcessorHost Prüfpunkte an einer anderen Stelle als Azure-Speicher gespeichert haben möchten, können Sie eigene Verwendung dieser Schnittstelle Checkpoint-Manager schreiben.  
            
            <para>Die Azure-Speicher-Manager verwenden den gleichen Speicher wie für Lease und Prüfpunkte, sodass beide Schnittstellen von derselben Klasse implementiert werden. Sie können dasselbe nicht tun, wenn Sie einheitlichen Speicher für beide Arten von Daten. </para> <para>Diese Schnittstelle nicht Initialisierungsmethoden angeben, da es keine Möglichkeit, zu wissen, welche Informationen, die Ihre Implementierung haben.</para></summary>
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
            Ist der Prüfpunkts Store vorhanden?
            </summary>
        <returns>"true", wenn es "false" Falls nicht vorhanden ist,</returns>
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
        <param name="partitionId">Die ID der Partition zum Erstellen des Prüfpunkts für.</param>
        <summary>
            Erstellen Sie den Prüfpunkt für die angegebene Partition aus, wenn er nicht vorhanden ist. Tun Sie nichts, wenn sie vorhanden ist.
            Der Offset/SequenceNumber für einen neu erstellten Prüfpunkt sollte auf StartOfStream/0 festgelegt werden.
            </summary>
        <returns>Der Prüfpunkt für die angegebene Partition, ob bereits vorhandene oder neu erstellt.</returns>
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
            Erstellen Sie die Prüfpunkt-Speicher, wenn er nicht vorhanden ist. Tun Sie nichts, wenn sie vorhanden ist.
            </summary>
        <returns>"true", wenn der Prüfpunkt-Speicher ist bereits vorhanden oder "OK". "false" erstellt wurde, wenn ein Fehler aufgetreten</returns>
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
        <param name="partitionId">ID der Partition So löschen Sie den Prüfpunkt aus Speicher</param>
        <summary>
            Löschen Sie die gespeicherten Prüfpunkt für die angegebene Partition. Wenn keine gespeicherten Prüfpunkt für die angegebene Partition, die als erfolgreich eingestuft ist.
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
        <param name="partitionId">Die ID der Partition zum Abrufen von Prüfpunktdatei-Informationen für.</param>
        <summary>
            Abrufen der Prüfpunktdaten auf der angegebenen Partition zugeordnet. Kann null zurück, wenn kein Prüfpunkt für die Partition erstellt wurde.
            </summary>
        <returns>Prüfpunkt-Informationen für die angegebene Partition oder Null, wenn keine zuvor gespeichert wurde.</returns>
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
        <param name="checkpoint">Offset/SequeceNumber zum Aktualisieren des Speichers mit.</param>
        <summary>
            Aktualisieren Sie den Prüfpunkt im Speicher mit den Offset/SequenceNumber im bereitgestellten Prüfpunkt.
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
        <param name="lease">Die Partitionsinformationen für die Durchführung ein Prüfpunkts.</param>
        <param name="checkpoint">Offset/SequeceNumber zum Aktualisieren des Speichers mit.</param>
        <summary>
            Aktualisieren Sie den Prüfpunkt im Speicher mit den Offset/SequenceNumber im bereitgestellten Prüfpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>