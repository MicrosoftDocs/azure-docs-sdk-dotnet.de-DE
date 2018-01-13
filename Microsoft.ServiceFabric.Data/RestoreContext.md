<Type Name="RestoreContext" FullName="Microsoft.ServiceFabric.Data.RestoreContext">
  <TypeSignature Language="C#" Value="public struct RestoreContext" />
  <TypeSignature Language="ILAsm" Value=".class public sequential ansi sealed beforefieldinit RestoreContext extends System.ValueType" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.RestoreContext" />
  <TypeSignature Language="VB.NET" Value="Public Structure RestoreContext" />
  <TypeSignature Language="F#" Value="type RestoreContext = struct" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.ValueType</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <cref name="RestoreContext" />enthält die <cref name="RestoreContext.RestoreAsync(RestoreDescription)" /> , die verwendet werden kann, um den Status des Replikats aus einer Sicherung wiederherzustellen. 
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RestoreContext (Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ServiceFabric.Data.IStateProviderReplica stateProviderReplica) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.#ctor(Microsoft.ServiceFabric.Data.IStateProviderReplica)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (stateProviderReplica As IStateProviderReplica)" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Data.RestoreContext : Microsoft.ServiceFabric.Data.IStateProviderReplica -&gt; Microsoft.ServiceFabric.Data.RestoreContext" Usage="new Microsoft.ServiceFabric.Data.RestoreContext stateProviderReplica" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stateProviderReplica" Type="Microsoft.ServiceFabric.Data.IStateProviderReplica" />
      </Parameters>
      <Docs>
        <param name="stateProviderReplica">
            Eine <see cref="T:Microsoft.ServiceFabric.Data.IStateProviderReplica" /> , die ein Replikat des zuverlässigen Zustand Anbieter darstellt.
            </param>
        <summary>
            Initialisiert eine neue Instanz der <cref name="RestoreContext" />-Struktur.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync restoreDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
      </Parameters>
      <Docs>
        <param name="restoreDescription">Beschreibung für die Anforderung zum Wiederherstellen.</param>
        <summary>
            Eine Sicherung von beschriebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.
            </returns>
        <remarks>
            Diese API muss von OnDataLossAsync-Methode aufgerufen werden. Nur ein RestoreAsync-API kann in-Flight pro Replikat zu einem bestimmten Zeitpunkt Zeit sein.
            
            Beachten Sie, dass diese API ausgelöste Ausnahmen abhängig von zugrunde liegenden zustandsanbieter unterscheiden. Die Ausnahmen, die für diese API nur für die Out-of-Box-Status-Anbieter von Service Fabric bereitgestellt wird, für zuverlässige Dienste und Reliable Actors gilt derzeit dokumentiert sind.
            <para>Folgende Ausnahmen werden ausgelöst, über diese API, wenn die im zuverlässigen Dienst aufgerufen: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list> </para> <para> Folgende Ausnahmen werden über diese API, wenn im Akteur-Dienst mit KvsActorStateProvider als seine State-Anbieter aufgerufen wird (also den Status Standardanbieter für Reliable Actors) ausgelöst:<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            Gibt an, dass die Eingabe Sicherungsordner keine vollständige Sicherung enthält.
            Für einen Sicherungsordner wiederherstellbar sein muss sie genau eine vollständige Sicherung und eine beliebige Anzahl von inkrementellen Sicherungen enthalten.
            </exception>
        <exception cref="T:System.ArgumentException">
            Gibt an, dass eines der Argumente nicht gültig ist. Z. B. wenn zuverlässig wiederherstellen, wenn RestorePolicy Safe, aber die Eingabe Sicherungsordner festgelegt ist eine Version des Status enthält, die älter als der Status, in das aktuelle Replikat beibehalten wird.
            
            Beim Wiederherstellen von einem Akteur-Dienst wird diese Ausnahme ausgelöst, wenn der angegebene <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> ist leer.
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            Gibt an, dass die Wiederherstellung angegebene Verzeichnis nicht vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            Gibt an, dass das Replikat geschlossen werden.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Gibt an, dass die aktuellen Restore-Vorgang ungültig ist. Z. B. die <see cref="T:System.Fabric.ServicePartitionKind" /> der Partition aus, in dem Sicherung erstellt wurde unterscheidet sich von der aktuellen Partition, die wiederhergestellt wird.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Gibt an, die erwartete Sicherungsdateien unter dem angegebenen Restore-Verzeichnis wurde nicht gefunden.
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            Gibt an, der Restore-Vorgang ist einen unerwarteter Fehler aufgetreten, oder die Sicherungsdateien im Restore-Verzeichnis sind nicht gültig.
            Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft gibt den Typ des aufgetretenen Fehlers.
            <list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>Gibt an, dass die Sicherungsdateien in das Verzeichnis für die Wiederherstellung angegebene entweder fehlen Dateien oder über zusätzliche unerwartete Dateien. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>Gibt an, dass die Metadatendateien (restore.dat) im Verzeichnis der Wiederherstellung ist entweder beschädigt oder enthält ungültige Daten. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) angegebene Verzeichnis bei der Wiederherstellung ist unterbrochen. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) bereitgestellten bei der Wiederherstellung Verzeichnis doppelte Sicherungen enthält. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>Wenn <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> wird im Rahmen des angegebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, bedeutet dies, dass die Sicherung, Wiederherstellung vorgesehenen ältere Daten als die zurzeit im Dienst vorhanden ist.</description></item></list></exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(valuetype Microsoft.ServiceFabric.Data.RestoreDescription restoreDescription, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.RestoreContext.RestoreAsync(Microsoft.ServiceFabric.Data.RestoreDescription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : Microsoft.ServiceFabric.Data.RestoreDescription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="restoreContext.RestoreAsync (restoreDescription, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restoreDescription" Type="Microsoft.ServiceFabric.Data.RestoreDescription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restoreDescription">Beschreibung für die Anforderung zum Wiederherstellen.</param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Wiederherstellen einer Sicherung von beschriebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />.
            </summary>
        <returns>
            Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.
            </returns>
        <remarks>
            Diese API muss von OnDataLossAsync-Methode aufgerufen werden. Nur ein RestoreAsync-API kann in-Flight pro Replikat zu einem bestimmten Zeitpunkt Zeit sein.
            
            Beachten Sie, dass diese API ausgelöste Ausnahmen abhängig von zugrunde liegenden zustandsanbieter unterscheiden. Die Ausnahmen, die für diese API nur für die Out-of-Box-Status-Anbieter von Service Fabric bereitgestellt wird, für zuverlässige Dienste und Reliable Actors gilt derzeit dokumentiert sind.
            <para>Folgende Ausnahmen werden ausgelöst, über diese API, wenn die im zuverlässigen Dienst aufgerufen: <list type="bullet"> <item> <description> <see cref="T:System.Fabric.FabricMissingFullBackupException" /> </description> </item> <item> <description> <see cref="T:System.ArgumentException" /> </description> </item> </list> </para> <para> Folgende Ausnahmen werden über diese API, wenn im Akteur-Dienst mit KvsActorStateProvider als seine State-Anbieter aufgerufen wird (also den Status Standardanbieter für Reliable Actors) ausgelöst:<list type="bullet"><item><description><see cref="T:System.ArgumentException" /></description></item><item><description><see cref="T:System.IO.DirectoryNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricObjectClosedException" /></description></item><item><description><see cref="T:System.InvalidOperationException" /></description></item><item><description><see cref="T:System.IO.FileNotFoundException" /></description></item><item><description><see cref="T:System.Fabric.FabricException" /></description></item></list></para></remarks>
        <exception cref="T:System.Fabric.FabricMissingFullBackupException">
            Gibt an, dass die Eingabe Sicherungsordner keine vollständige Sicherung enthält.
            Für einen Sicherungsordner wiederherstellbar sein muss sie genau eine vollständige Sicherung und eine beliebige Anzahl von inkrementellen Sicherungen enthalten.
            </exception>
        <exception cref="T:System.ArgumentException">
            Gibt an, dass eines der Argumente nicht gültig ist. Z. B. wenn zuverlässig wiederherstellen, wenn RestorePolicy Safe, aber die Eingabe Sicherungsordner festgelegt ist eine Version des Status enthält, die älter als der Status, in das aktuelle Replikat beibehalten wird.
            
            Beim Wiederherstellen von einem Akteur-Dienst wird diese Ausnahme ausgelöst, wenn der angegebene <see cref="P:Microsoft.ServiceFabric.Data.RestoreDescription.BackupFolderPath" /> ist leer.
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
            Gibt an, dass die Wiederherstellung angegebene Verzeichnis nicht vorhanden ist.
            </exception>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
            Gibt an, dass das Replikat geschlossen werden.
            </exception>
        <exception cref="T:System.InvalidOperationException">
            Gibt an, dass die aktuellen Restore-Vorgang ungültig ist. Z. B. die <see cref="T:System.Fabric.ServicePartitionKind" /> der Partition aus, in dem Sicherung erstellt wurde unterscheidet sich von der aktuellen Partition, die wiederhergestellt wird.
            </exception>
        <exception cref="T:System.IO.FileNotFoundException">
            Gibt an, die erwartete Sicherungsdateien unter dem angegebenen Restore-Verzeichnis wurde nicht gefunden.
            </exception>
        <exception cref="T:System.Fabric.FabricException">
            Gibt an, der Restore-Vorgang ist einen unerwarteter Fehler aufgetreten, oder die Sicherungsdateien im Restore-Verzeichnis sind nicht gültig.
            Die <see cref="P:System.Fabric.FabricException.ErrorCode" /> Eigenschaft gibt den Typ des aufgetretenen Fehlers.
            <list type="bullet"><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackup" /></term><description>Gibt an, dass die Sicherungsdateien in das Verzeichnis für die Wiederherstellung angegebene entweder fehlen Dateien oder über zusätzliche unerwartete Dateien. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidRestoreData" /></term><description>Gibt an, dass die Metadatendateien (restore.dat) im Verzeichnis der Wiederherstellung ist entweder beschädigt oder enthält ungültige Daten. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.InvalidBackupChain" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) angegebene Verzeichnis bei der Wiederherstellung ist unterbrochen. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.DuplicateBackups" /></term><description>Gibt an, dass die sicherungskette (d. h. eine vollständige Sicherung und NULL oder mehr fortlaufenden inkrementelle Sicherungen, die danach ausgeführt wurden) bereitgestellten bei der Wiederherstellung Verzeichnis doppelte Sicherungen enthält. </description></item><item><term><see cref="F:System.Fabric.FabricErrorCode.RestoreSafeCheckFailed" /></term><description>Wenn <see cref="F:Microsoft.ServiceFabric.Data.RestorePolicy.Safe" /> wird im Rahmen des angegebenen <see cref="T:Microsoft.ServiceFabric.Data.RestoreDescription" />, bedeutet dies, dass die Sicherung, Wiederherstellung vorgesehenen ältere Daten als die zurzeit im Dienst vorhanden ist.</description></item></list></exception>
      </Docs>
    </Member>
  </Members>
</Type>