<Type Name="IFileStagingArtifact" FullName="Microsoft.Azure.Batch.IFileStagingArtifact">
  <TypeSignature Language="C#" Value="public interface IFileStagingArtifact" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IFileStagingArtifact" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IFileStagingArtifact" />
  <TypeSignature Language="VB.NET" Value="Public Interface IFileStagingArtifact" />
  <TypeSignature Language="F#" Value="type IFileStagingArtifact = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Informationen zu einer Datei mit dem Stagingprozess.  Datei Staging erfolgt in der Regel für eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> (siehe <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />).
            </summary>
    <remarks>
      <para>
            IFileStagingArtifact ermöglicht einer Anwendung, um anzupassen und Abrufen von Informationen zum Hochladen von Dateien in die Cloud, z. B. im Rahmen eines Vorgangs aufgabenbezogenen wie z. B. <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see> oder <see cref="M:Microsoft.Azure.Batch.CloudJob.AddTaskAsync(Microsoft.Azure.Batch.CloudTask,System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)">CloudJob.AddTaskAsync</see>.  Anwendungen können diese Informationen verwenden, um, z. B. Informationen zu Containern herauszufinden, die im Azure-Speicher als Teil des Uploadvorgangs erstellt wurden.
            </para>
      <para>
            Wenn <see cref="M:Microsoft.Azure.Batch.JobOperations.AddTaskAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.BatchClientParallelOptions,System.Collections.Concurrent.ConcurrentBag{System.Collections.Concurrent.ConcurrentDictionary{System.Type,Microsoft.Azure.Batch.IFileStagingArtifact}},System.Nullable{System.TimeSpan},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})">JobOperations.AddTaskAsync</see> aufgerufen wird, wird der Batch-Client sendet die Aufgaben, die dem Batch-Dienst in Auflistungen.  Wie jede Sammlung verarbeitet wird, führt der Batch-Client Datei Staging für diese Sammlung: untersucht die Aufgaben aus, um festzustellen, ob diese angeben <see cref="P:Microsoft.Azure.Batch.CloudTask.FilesToStage" />, und wenn dies der Fall ist, erstellt einen Wörterbucheintrag für jeden Typ von <see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" /> in der FilesToStage-Auflistung. Der Schlüssel des Wörterbucheintrags ist die <see cref="T:System.Type" /> der IFileStagingProvider und der Wert ist eine Instanz der entsprechenden Implementierung des IFileStagingArtifact.  Z. B. wenn FilesToStage ein oder mehrere FileToStage-Objekte (aus der Bibliothek Microsoft.Azure.Batch.FileStaging) enthält, enthält das Wörterbuch einen Eintrag, dessen Schlüssel ist typeof(FileToStage) und dessen Wert ist eine Instanz von SequentialFileStagingArtifact.
            </para>
      <para>
            Bei Abschluss des Vorgangs Aufgabe hinzufügen, oder während des Vorgangs Aufgabe hinzufügen, wenn die Anwendung mit mehreren Threads ist, können Sie untersuchen das Wörterbuch und konvertieren jedes IFileStagingArtifact in den entsprechenden Typ zum Abrufen der-spezifische Informationen.  Z. B. wenn der Vorgang zum Hinzufügen von Tasks ein oder mehrere FileToStage Objekte angegeben wird, können Sie suchen nach Argumentnamen geordnet typeof(FileToStage) Wörterbucheintrags, wandelt den Wert auf SequentialFileStagingArtifact, und Überprüfen der SequentialFileStagingArtifact.BlobContainerCreated-Eigenschaft, um festzustellen, ob während des Uploads einen Blob-Container im Azure-Speicher erstellt und der Name des Containers.
            In diesem Beispiel kann zum Bereinigen von automatisch erstellten Container nützlich sein.
            </para>
      <para>
            (Einzelnen Aufgabe hinzufügen aufgabenvorgänge funktionieren auf ähnliche Weise, außer dass bei einer Aufgabe Hinzufügen mehrerer Aufgaben, es gibt ein Wörterbuch für jede Sammlung von Aufgaben und die Wörterbücher werden gesammelt, einem <see cref="T:System.Collections.Concurrent.ConcurrentBag`1" />, während in einer einzelnen Aufgabe hinzufügen Taskvorgang nur besteht ein einzelne Wörterbuch.)
            </para>
      <para>
            In einer einzelnen Aufgabe Aufgabe hinzufügen-Vorgang auch können Wörterbuch Sie die Datei mit dem Stagingprozess von vorab Befüllen mit entsprechenden Einträge anzupassen.  Nehmen wir beispielsweise an, Sie möchten die Steuerung der <see cref="P:Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" /> für eine Gruppe von FileToStage-Objekten.  Dann Sie das Wörterbuch mit initialisieren konnte <c>{typeof(FileToStage), neue SequentialFileStagingArtifact {NamingFragment = "" MyName ""}}</c> vor der Übergabe an AddTaskAsync.  Die Implementierung FileToStage IFileStagingProvider würde dann Ihre SequentialFileStagingArtifact verwenden, statt einen eigenen.  (Diese Funktion ist nicht verfügbar in mehreren Aufgaben hinzufügen aufgabenvorgänge.)
            </para>
      <para>
            IFileStagingArtifact kann auch auftreten, wenn Sie eine benutzerdefinierte entwickeln <see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" />.
            In diesem Fall erstellen Sie in der Regel eine benutzerdefinierte Implementierung von IFileStagingArtifact implementierungsspezifische um Informationen zu melden Ihre Datei Stagingprozess.
            </para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="NamingFragment">
      <MemberSignature Language="C#" Value="public string NamingFragment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NamingFragment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" />
      <MemberSignature Language="VB.NET" Value="Public Property NamingFragment As String" />
      <MemberSignature Language="F#" Value="member this.NamingFragment : string with get, set" Usage="Microsoft.Azure.Batch.IFileStagingArtifact.NamingFragment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ein Name-Fragment, das beim Erstellen von Namen für Standardwerte verwendet werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>Obwohl ein Aufrufer diese Eigenschaft festlegen, kann die <see cref="T:Microsoft.Azure.Batch.FileStaging.IFileStagingProvider" /> Implementierung ist nicht erforderlich, um es zu berücksichtigen.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>