<Type Name="TaskOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage">
  <TypeSignature Language="C#" Value="public class TaskOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskOutputStorage" />
  <TypeSignature Language="F#" Value="type TaskOutputStorage = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Stellt permanenten Speicher für die Ausgaben eines Azure Batch-Vorgangs dar.
            </summary>
    <remarks>
            Aufgabenausgaben finden Sie in Ausgabedaten logisch eine bestimmte Aufgabe, anstatt den Auftrag als Ganzes zugeordnet. Z. B. in einem Film-Rendering-Auftrag wäre wenn eine Aufgabe mit einen einzelnen Frame gerendert dieser Rahmen einer Aufgabenausgabe.  Protokolle und andere Diagnoseinformationen wie z. B. Zwischendateien möglicherweise auch beibehalten, wie taskausgaben (siehe <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für eine Möglichkeit, diese zu kategorisieren, sodass Clients die Hauptausgabe weitere Daten unterscheiden, können).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">Die URL im Azure-Speicher des Blob-Containers für diesen Auftrag zugeordneten Ausgaben verwendet werden soll. Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</param>
        <param name="taskId">Die Id der Azure Batch-Aufgabe.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einem Task-Id und eine URL, die der Auftrag Ausgabecontainer darstellt.
            </summary>
        <remarks>Der Container muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="jobId">Die Id des Azure Batch-Auftrags, der den Task enthält.</param>
        <param name="taskId">Die Id der Azure Batch-Aufgabe.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse aus einem Speicherkonto, die Auftrags-Id und die Task-Id.
            </summary>
        <remarks>Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Uri jobOutputContainerUri, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Uri * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (jobOutputContainerUri, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">Die URL im Azure-Speicher des Blob-Containers für diesen Auftrag zugeordneten Ausgaben verwendet werden soll. Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</param>
        <param name="taskId">Die Id der Azure Batch-Aufgabe.</param>
        <param name="storageRetryPolicy">Die wiederholungsrichtlinie für speicheranforderungen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einem Task-Id und eine URL, die der Auftrag Ausgabecontainer darstellt.
            </summary>
        <remarks>Der Container muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, string taskId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, taskId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage (storageAccount, jobId, taskId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="jobId">Die Id des Azure Batch-Auftrags, der den Task enthält.</param>
        <param name="taskId">Die Id der Azure Batch-Aufgabe.</param>
        <param name="storageRetryPolicy">Die wiederholungsrichtlinie für speicheranforderungen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse aus einem Speicherkonto, die Auftrags-Id und die Task-Id.
            </summary>
        <remarks>Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse TaskOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;GetOutputAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie der Ausgabe abrufen, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <param name="filePath">Der Pfad, unter dem die Ausgabe im Blob-Speicher beibehalten wurde.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft eine Aufgabenausgabe aus dem Azure-Blob-Speicher von der Art und den Pfad ab.
            </summary>
        <returns>Ein Verweis auf die angeforderte Datei im Azure-Blob-Speicher.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As TaskOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="taskOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie der Ausgaben auflisten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <summary>
            Listet die Aufgabenausgaben der angegebenen Art an.
            </summary>
        <returns>Eine Liste der persistent gespeicherten Aufgabenausgaben der angegebenen Art.</returns>
        <remarks>Die Liste wird aus dem Azure-Blob-Speicher verzögert abgerufen, wenn diese aufgelistet wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <param name="relativePath">Der Pfad der Datei relativ zum aktuellen Verzeichnis zu speichern.
            Wenn die Datei in einem Unterverzeichnis des aktuellen Verzeichnisses ist, wird der relative Pfad im Blob-Speicher beibehalten.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Speichert die angegebene Datei in den persistenten Speicher.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>Wenn die Datei außerhalb des aktuellen Verzeichnisses ist, werden von links aus der Verzeichnisstruktur entfernt.
            Z. B. eine <paramref name="relativePath" /> der ".. \ProcessEnv.cmd"würde als"ProcessEnv.cmd"im Rahmen der Erstellen eines Blob-namens behandelt werden.</remarks>
        <exception cref="T:System.ArgumentNullException">Die <paramref name="kind" /> oder <paramref name="relativePath" /> Argument ist null.</exception>
        <exception cref="T:System.ArgumentException">Die <paramref name="relativePath" /> Argument ist ein absoluter Pfad oder ist leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <param name="sourcePath">Der Pfad der zu speichernden Datei.</param>
        <param name="destinationRelativePath">Der Blob-Name, unter dem die Datei gespeichert werden soll. Dies kann eine relative Komponente, wie z. B. "pointclouds/pointcloud_0001.txt" umfassen.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Speichert die angegebene Datei in den persistenten Speicher.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die <paramref name="kind" />, <paramref name="sourcePath" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</exception>
        <exception cref="T:System.ArgumentException">Die <paramref name="sourcePath" /> oder <paramref name="destinationRelativePath" /> -Argument leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveTextAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveTextAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string text, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTextAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveTextAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="taskOutputStorage.SaveTextAsync (kind, text, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="text" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem Speichern der Daten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <param name="text">Der Text gespeichert.</param>
        <param name="destinationRelativePath">Der Blob-Name, unter dem den Text gespeichert werden soll. Dies kann eine relative Komponente, wie z. B. "records/widget42.json" umfassen.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Speichert den angegebenen Text in den permanenten Speicher, ohne dass Ihnen die Erstellung eine lokale Datei.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Die <paramref name="kind" />, <paramref name="text" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</exception>
        <exception cref="T:System.ArgumentException">Die <paramref name="destinationRelativePath" /> -Argument leer ist.</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (string relativePath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(string relativePath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (relativePath As String) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync relativePath" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="relativePath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="relativePath">Der Pfad der Datei relativ zum aktuellen Verzeichnis zu speichern.
            Wenn die Datei in einem Unterverzeichnis des aktuellen Verzeichnisses ist, wird der relative Pfad im Blob-Speicher beibehalten.</param>
        <summary>
            Speichert die angegebene Datei in den persistenten Speicher als eine <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />, und nachfolgende verfolgt fügt an die Datei und fügt sie an die persistente Kopie zu.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> die speichert einer Datei in Blob-Speicher und die Datei wird in regelmäßigen Abständen entleert fügt Sie in das Blob erst verworfen.  Wenn freigegeben, fügt allen übrigen werden geleert, um blob-Speicher und weitere Track Datei fügt wird beendet.</returns>
        <remarks>
          <para>Nachverfolgen von unterstützt nur angefügt. Während eine Datei nachverfolgt wird, werden am Ende hinzugefügten Daten im permanenten Speicher angefügt. Änderungen an Daten, die bereits hochgeladen wurden, werden nicht im permanenten Speicher berücksichtigt. Diese Methode ist daher nur für Dateien, wie z. B. Protokolldateien (nicht drehen) für die Verwendung vorgesehen, in dem Daten nur am Ende der Datei hinzugefügt wird.
            Wenn Sie den gesamten Inhalt einer Datei ändern können, verwenden <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.Threading.CancellationToken)" /> und nennen Sie es in regelmäßigen Abständen oder nach jeder Änderung.</para>
          <para>Wenn die Datei außerhalb des aktuellen Verzeichnisses ist, werden von links aus der Verzeichnisstruktur entfernt.
            Z. B. eine <paramref name="relativePath" /> der ".. \ProcessEnv.cmd"würde als"ProcessEnv.cmd"im Rahmen der Erstellen eines Blob-namens behandelt werden.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">Das <paramref name="relativePath" />-Argument ist null.</exception>
        <exception cref="T:System.ArgumentException">Die <paramref name="relativePath" /> Argument ist ein absoluter Pfad oder ist leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="SaveTrackedAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync (Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, TimeSpan flushInterval);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt; SaveTrackedAsync(class Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.TimeSpan flushInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveTrackedAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveTrackedAsync (kind As TaskOutputKind, sourcePath As String, destinationRelativePath As String, flushInterval As TimeSpan) As Task(Of ITrackedSaveOperation)" />
      <MemberSignature Language="F#" Value="member this.SaveTrackedAsync : Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind * string * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;" Usage="taskOutputStorage.SaveTrackedAsync (kind, sourcePath, destinationRelativePath, flushInterval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage/&lt;SaveTrackedAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="flushInterval" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind.TaskLog" />.</param>
        <param name="sourcePath">Der Pfad der zu speichernden Datei.</param>
        <param name="destinationRelativePath">Der Blob-Name, unter dem die Datei gespeichert werden soll. Dies kann eine relative Komponente, wie z. B. "pointclouds/pointcloud_0001.txt" umfassen.</param>
        <param name="flushInterval">Das Intervall, in dem leeren fügt in den persistenten Speicher.</param>
        <summary>
            Speichert die angegebene Datei permanenten Speicher und verfolgt nachfolgende fügt an die Datei und fügt sie die persistente Kopie zu.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.ITrackedSaveOperation" /> die speichert einer Datei in Blob-Speicher und die Datei wird in regelmäßigen Abständen entleert fügt Sie in das Blob erst verworfen.  Wenn freigegeben, fügt allen übrigen werden geleert, um blob-Speicher und weitere Track Datei fügt wird beendet.</returns>
        <remarks>
          <para>Nachverfolgen von unterstützt nur angefügt. Während eine Datei nachverfolgt wird, werden am Ende hinzugefügten Daten im permanenten Speicher angefügt. Änderungen an Daten, die bereits hochgeladen wurden, werden nicht im permanenten Speicher berücksichtigt. Diese Methode ist daher nur für Dateien, wie z. B. Protokolldateien (nicht drehen) für die Verwendung vorgesehen, in dem Daten nur am Ende der Datei hinzugefügt wird.
            Wenn Sie den gesamten Inhalt einer Datei ändern können, verwenden <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.TaskOutputKind,System.String,System.String,System.Threading.CancellationToken)" /> und nennen Sie es in regelmäßigen Abständen oder nach jeder Änderung.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">Die <paramref name="kind" />, <paramref name="sourcePath" />, oder <paramref name="destinationRelativePath" /> Argument ist null.</exception>
        <exception cref="T:System.ArgumentException">Die <paramref name="sourcePath" /> oder <paramref name="destinationRelativePath" /> -Argument leer ist.</exception>
      </Docs>
    </Member>
  </Members>
</Type>