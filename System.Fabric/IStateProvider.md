<Type Name="IStateProvider" FullName="System.Fabric.IStateProvider">
  <TypeSignature Language="C#" Value="public interface IStateProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStateProvider" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.IStateProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStateProvider" />
  <TypeSignature Language="F#" Value="type IStateProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
      <para>Definiert das Verhalten, das ein Dienst implementieren muss, um die Interaktion mit der <see cref="T:System.Fabric.FabricReplicator" />.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetCopyContext">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyContext ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyContext() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyContext" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyContext () As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyContext : unit -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyContext " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Kontext auf einem sekundären Replikat erhält, nachdem es erstellt und geöffnet, um den Kontext mit dem primären Replikat zu senden.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</para>
        </returns>
        <remarks>
          <para>Das primäre Replikat analysiert den Kontext und zurücksendet Status über <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />.</para>
          <para>
            <see cref="M:System.Fabric.IStateProvider.GetCopyContext" />wird aufgerufen, auf neu erstellt werden, inaktive sekundäre Replikate und bietet einen Mechanismus zum asynchron eine bidirektionale Konversation mit dem primären Replikat hergestellt. Das sekundäre Replikat sendet <see cref="T:System.Fabric.OperationData" /> Objekte, die mit dem das primäre Replikat den Status des Sammelns von Kontext auf dem sekundären Replikat bestimmen kann. Das primäre Replikat sendet seinerseits den erforderlichen Zustand zurück.
                Finden Sie unter <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> an das primäre Replikat für die andere Hälfte des Austausches. </para>
          <para>Für InMemory-Dienste die <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode wird nicht aufgerufen, da der Status der sekundären Replikate bekannt ist (sie sind leer und benötigen alle Status).</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCopyState">
      <MemberSignature Language="C#" Value="public System.Fabric.IOperationDataStream GetCopyState (long upToSequenceNumber, System.Fabric.IOperationDataStream copyContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Fabric.IOperationDataStream GetCopyState(int64 upToSequenceNumber, class System.Fabric.IOperationDataStream copyContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCopyState (upToSequenceNumber As Long, copyContext As IOperationDataStream) As IOperationDataStream" />
      <MemberSignature Language="F#" Value="abstract member GetCopyState : int64 * System.Fabric.IOperationDataStream -&gt; System.Fabric.IOperationDataStream" Usage="iStateProvider.GetCopyState (upToSequenceNumber, copyContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("StyleCop.CSharp.NamingRules", "SA1305:FieldNamesMustNotUseHungarianNotation", Justification="Not Hungarian notation.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.IOperationDataStream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upToSequenceNumber" Type="System.Int64" />
        <Parameter Name="copyContext" Type="System.Fabric.IOperationDataStream" />
      </Parameters>
      <Docs>
        <param name="upToSequenceNumber">
          <para>Die maximale letzte Sequenznummer, die in den Stream kopieren über eingefügt werden soll die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode.
            LSNs, die größer als diese Zahl werden an das sekundäre Replikat als Teil der replikationsdatenstrom über übermittelt die <see cref="M:System.Fabric.IStateReplicator.GetReplicationStream" /> Methode.</para>
        </param>
        <param name="copyContext">
          <para>Ein <see cref="T:System.Fabric.IOperationDataStream" /> , enthält die <see cref="T:System.Fabric.OperationData" /> Objekte, die vom sekundären Replikat erstellt werden. </para>
        </param>
        <summary>
          <para>Ruft die Status für ein primäres Replikat, das erforderlich sind, um ein sekundäres Replikat zu erstellen.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Fabric.IOperationDataStream" />zurück.</para>
        </returns>
        <remarks>
          <para>Ebenso wie <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> ermöglicht das sekundäre Replikat das primäre Replikat über Kontext an ein <see cref="T:System.Fabric.IOperationDataStream" />, <see cref="M:System.Fabric.IStateProvider.GetCopyState(System.Int64,System.Fabric.IOperationDataStream)" /> ermöglicht das primäre Replikat antwortet ein <see cref="T:System.Fabric.IOperationDataStream" />. Der Datenstrom enthält Objekte, die an das sekundäre Replikat über übermittelt werden die <see cref="M:System.Fabric.IStateReplicator.GetCopyStream" /> Methode der <see cref="T:System.Fabric.FabricReplicator" /> Klasse. Implementieren Sie die Objekte <see cref="T:System.Fabric.IOperation" /> und die angegebenen Daten enthalten. </para>
          <para> Wenn das primäre Replikat dieser Aufruf empfängt, sollte er erstellen und Zurückgeben einer anderen <see cref="T:System.Fabric.IOperationDataStream" /> enthält <see cref="T:System.Fabric.OperationData" />. <see cref="T:System.Fabric.OperationData" />Stellt dar, die das sekundäre Replikat benötigt wird, um den aktuellen Stand zu bereitgestellten Daten/Status <paramref name="upToSequenceNumber" /> maximale LSN. Wie viel und welchen Status hat, Versand kann bestimmt werden, über die Kontextinformationen, die das sekundäre Replikat über bereitstellt <see cref="M:System.Fabric.IStateProvider.GetCopyContext" /> Methode.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLastCommittedSequenceNumber">
      <MemberSignature Language="C#" Value="public long GetLastCommittedSequenceNumber ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance int64 GetLastCommittedSequenceNumber() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.GetLastCommittedSequenceNumber" />
      <MemberSignature Language="VB.NET" Value="Public Function GetLastCommittedSequenceNumber () As Long" />
      <MemberSignature Language="F#" Value="abstract member GetLastCommittedSequenceNumber : unit -&gt; int64" Usage="iStateProvider.GetLastCommittedSequenceNumber " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die letzte Sequenznummer, die der Dienst ein Commit ausgeführt wurde, auch bekannt als logische-Sequenz-Anzahl (LSN). </para>
        </summary>
        <returns>
          <para>Gibt die letzte Sequenznummer für ein Commit ausgeführt wurde.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iStateProvider.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.MSInternal", "CA908:UseApprovedGenericsForPrecompiledAssemblies", Justification="Not precompiled assembly.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Gibt an, dass ein schreibquorums Replikate in dieser Replikatsatz verloren gegangen ist und daher Datenverlust aufgetreten sind. Die Replikatgruppe besteht aus der Mehrheit der Replikate, die das primäre Replikat enthält. </para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:System.Boolean" />, Wert, der angibt, ob die State-Anbieter als Teil der Verarbeitung dieser benachrichtigungs seinen Status geändert wurde</para>
        </returns>
        <remarks>
          <para>Wenn die Service Fabric-Laufzeit einen Fehler des ein Quorum der Replikate, der das primäre Replikat enthält berücksichtigt, wählt ein neues primäres Replikat und sofort ruft diese Methode auf dem neuen primären Replikat. Ein primäres Replikat, das eines möglichen Datenverlusts informiert ist die Möglichkeit, den Zustand aus einer externen Datenquelle wiederherstellen oder kann weiterhin mit dem Status ausgeführt wird, die derzeit. Wenn der Dienst mit seinem aktuellen Zustand ausgeführt werden weiterhin, sollte es "false" von dieser Methode zurückgeben, der gibt an, dass keine Änderung vorgenommen wurde. Wenn es wiederhergestellt oder geändert Datenbankzustands, z. B. unvollständige Arbeit ein Rollback sollte "true" zurückgeben. Wenn "true" zurückgegeben wird, muss der Status in den anderen Replikaten angenommen werden, falsch zu sein.
            Aus diesem Grund die Service Fabric-Laufzeit die anderen Replikaten in der Replikatgruppe entfernt und erneut erstellt werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateEpochAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateEpochAsync (System.Fabric.Epoch epoch, long previousEpochLastSequenceNumber, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task UpdateEpochAsync(valuetype System.Fabric.Epoch epoch, int64 previousEpochLastSequenceNumber, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateEpochAsync : System.Fabric.Epoch * int64 * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iStateProvider.UpdateEpochAsync (epoch, previousEpochLastSequenceNumber, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="epoch" Type="System.Fabric.Epoch" />
        <Parameter Name="previousEpochLastSequenceNumber" Type="System.Int64" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="epoch">
          <para>Die neue <see cref="T:System.Fabric.Epoch" />.</para>
        </param>
        <param name="previousEpochLastSequenceNumber">
          <para> Die maximale Sequenznummer (LSN) in der vorherigen Epoche.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass der Abbruch advisory ist und weiterhin der Vorgang abgeschlossen werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ein Replikat zeigt an, dass die Konfiguration einer Replikatgruppe aufgrund einer Änderung der geändert oder ändern, mit dem primären Replikat versucht. Die Änderung tritt aufgrund eines Fehlers oder Lastenausgleich des vorherigen primären Replikats. Epoche Änderungen fungieren als einer Barrier-Klasse, indem Sie segmentieren Vorgänge in die genaue Konfiguration Zeiträume, in denen sie von einem bestimmten primären Replikat gesendet wurden.</para>
        </summary>
        <returns>
          <para>Gibt <see cref="T:System.Threading.Tasks.Task" />zurück.</para>
        </returns>
        <remarks>
          <para>Die Informationen in der <see cref="M:System.Fabric.IStateProvider.UpdateEpochAsync(System.Fabric.Epoch,System.Int64,System.Threading.CancellationToken)" /> -Methode ermöglicht dem Dienst um einen Vektor Status aufrecht ist eine Liste der einzelnen Epoche, die das Replikat empfangen hat und die maximale LSN, die sie enthalten. </para>
          <para>
                Die Bearbeitung Vektordaten werden zusammen mit den aktuellen angewendeten maximale LSN eignet sich für ein sekundäres Replikat während des Kopiervorgangs zu senden, um den Status des Replikats zu beschreiben.</para>
          <para>
                Vergleichen von Fortschritt Vektoren, die während des Kopiervorgangs von sekundären Replikaten empfangen werden primäre Replikate, um zu bestimmen, ob das sekundäre Replikat auf dem neuesten Stand ist, muss welchen Status an das sekundäre Replikat gesendet werden kann und ob das sekundäre Replikat ist "false" Fortschritt erzielt. </para>
          <para>"False" Status bedeutet, dass ein sekundäres Replikat meldet wurde eine LSN in einer vorherigen Epoche größer als die LSN, die das primäre Replikat in seinen Fortschritt Vektor verfügt. </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>