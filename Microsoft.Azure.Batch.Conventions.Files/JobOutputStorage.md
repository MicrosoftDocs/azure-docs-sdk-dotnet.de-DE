<Type Name="JobOutputStorage" FullName="Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage">
  <TypeSignature Language="C#" Value="public class JobOutputStorage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobOutputStorage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" />
  <TypeSignature Language="VB.NET" Value="Public Class JobOutputStorage" />
  <TypeSignature Language="F#" Value="type JobOutputStorage = class" />
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
            Stellt permanenten Speicher für die Ausgaben von einem Azure Batch-Auftrag dar.
            </summary>
    <remarks>
            Auftragsausgaben finden Sie in Ausgabedaten, die logisch mit einer bestimmten Aufgabe, anstatt das gesamte Projekt verknüpft ist. Z. B. in einem Film-Rendering-Auftrag, wenn eine Aufgabe in einen Film alle Frames kombiniert, die logisch eine Auftragsausgabe wäre. Der Zweck der categorising einer Ausgabe wie "Auftragsausgabe" ist, um den Client zu speichern, müssen Sie wissen, welche Aufgabe erzeugt es wurde.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage jobOutputContainerUri" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">Gibt die URL im Azure-Speicher des Blob-Containers für den Auftrag aus. Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einer URL, die der Auftrag Ausgabecontainer darstellt.
            </summary>
        <remarks>Der Container muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="jobId">Die Id des Azure Batch-Auftrags.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse über eine Speicher-Konto und die Auftrags-Id.
            </summary>
        <remarks>Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Uri jobOutputContainerUri, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri jobOutputContainerUri, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (jobOutputContainerUri As Uri, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Uri * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (jobOutputContainerUri, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="jobOutputContainerUri" Type="System.Uri" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="jobOutputContainerUri">Gibt die URL im Azure-Speicher des Blob-Containers für den Auftrag aus. Diese URL muss eine SAS (Shared Access Signature) mit dem Gewähren des Zugriffs auf den Container enthalten, oder der Container muss öffentlich sein.</param>
        <param name="storageRetryPolicy">Die wiederholungsrichtlinie für speicheranforderungen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse von einer URL, die der Auftrag Ausgabecontainer darstellt.
            </summary>
        <remarks>Der Container muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobOutputStorage (Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, string jobId, class Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy storageRetryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.String,Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccount As CloudStorageAccount, jobId As String, storageRetryPolicy As IRetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage : Microsoft.WindowsAzure.Storage.CloudStorageAccount * string * Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="new Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage (storageAccount, jobId, storageRetryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="storageRetryPolicy" Type="Microsoft.WindowsAzure.Storage.RetryPolicies.IRetryPolicy" />
      </Parameters>
      <Docs>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="jobId">Die Id des Azure Batch-Auftrags.</param>
        <param name="storageRetryPolicy">Die wiederholungsrichtlinie für speicheranforderungen.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> Klasse über eine Speicher-Konto und die Auftrags-Id.
            </summary>
        <remarks>Der Auftrag Ausgabecontainer muss bereits vorhanden sein; die Klasse JobOutputStorage wird nicht für Sie erstellt.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; GetOutputAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string filePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.GetOutputAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetOutputAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.GetOutputAsync (kind, filePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;GetOutputAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie der Ausgabe abrufen, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</param>
        <param name="filePath">Der Pfad, unter dem die Ausgabe im Blob-Speicher beibehalten wurde.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Ruft eine Auftragsausgabe aus dem Azure-Blob-Speicher von der Art und den Pfad ab.
            </summary>
        <returns>Ein Verweis auf die angeforderte Datei im Azure-Blob-Speicher.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt; ListOutputs(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.ListOutputs(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListOutputs (kind As JobOutputKind) As IEnumerable(Of OutputFileReference)" />
      <MemberSignature Language="F#" Value="member this.ListOutputs : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind -&gt; seq&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;" Usage="jobOutputStorage.ListOutputs kind" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.Conventions.Files.OutputFileReference&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie der Ausgaben auflisten, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</param>
        <summary>
            Listet die auftragsausgaben der angegebenen Art an.
            </summary>
        <returns>Eine Liste der persistenten auftragsausgaben der angegebenen Art.</returns>
        <remarks>Die Liste wird aus dem Azure-Blob-Speicher verzögert abgerufen, wenn diese aufgelistet wird.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string relativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, relativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="relativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</param>
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
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SaveAsync (Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task SaveAsync(class Microsoft.Azure.Batch.Conventions.Files.JobOutputKind kind, string sourcePath, string destinationRelativePath, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.SaveAsync(Microsoft.Azure.Batch.Conventions.Files.JobOutputKind,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveAsync : Microsoft.Azure.Batch.Conventions.Files.JobOutputKind * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobOutputStorage.SaveAsync (kind, sourcePath, destinationRelativePath, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage/&lt;SaveAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="kind" Type="Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" />
        <Parameter Name="sourcePath" Type="System.String" />
        <Parameter Name="destinationRelativePath" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="kind">Ein <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind" /> für die Kategorie aus, unter dem diese Datei zu speichern, z. B. <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobOutput" /> oder <see cref="F:Microsoft.Azure.Batch.Conventions.Files.JobOutputKind.JobPreview" />.</param>
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
  </Members>
</Type>