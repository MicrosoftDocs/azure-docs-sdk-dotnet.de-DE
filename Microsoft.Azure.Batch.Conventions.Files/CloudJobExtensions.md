<Type Name="CloudJobExtensions" FullName="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions">
  <TypeSignature Language="C#" Value="public static class CloudJobExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit CloudJobExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module CloudJobExtensions" />
  <TypeSignature Language="F#" Value="type CloudJobExtensions = class" />
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
            Stellt Methoden zum Arbeiten mit Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job">Der Auftrag für die zum Erstellen des Containers.</param>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <summary>
            Ruft die URL, einschließlich einer Shared Access Signature (SAS), die schreiben, für den Auftrag Ausgabe Speichercontainer in Azure Blob-Speicher ermöglicht. Diese URL eignet sich für die Übergabe an Aufgaben, damit diese verwenden, können die <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> oder <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> Konstruktoren, die eine <see cref="T:System.Uri" />.
            </summary>
        <returns>Die URL, einschließlich SAS, der der Auftrag Ausgabecontainer.</returns>
        <remarks>Die SAS läuft nach 7 Tagen ab. Diese Standardeinstellung wird ausgewählt, um die maximale Zeit entsprechen, die Aufgaben aktiv bleiben können.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputStorageContainerUrl">
      <MemberSignature Language="C#" Value="public static string GetOutputStorageContainerUrl (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, TimeSpan expiryTime);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetOutputStorageContainerUrl(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.TimeSpan expiryTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputStorageContainerUrl (job As CloudJob, storageAccount As CloudStorageAccount, expiryTime As TimeSpan) As String" />
      <MemberSignature Language="F#" Value="static member GetOutputStorageContainerUrl : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * TimeSpan -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.GetOutputStorageContainerUrl (job, storageAccount, expiryTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="expiryTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="job">Der Auftrag für die zum Erstellen des Containers.</param>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="expiryTime">Die Dauer, für die die SAS gültig ist.  Dies dürfte lang genug, um alle Aufgaben des Auftrags erstellt und werden vollständig, einschließlich Spielraum für Fehler und führt die Wiederholung ausgeführt werden können.</param>
        <summary>
            Ruft die URL, einschließlich einer Shared Access Signature (SAS), die schreiben, für den Auftrag Ausgabe Speichercontainer in Azure Blob-Speicher ermöglicht. Diese URL eignet sich für die Übergabe an Aufgaben, damit diese verwenden, können die <see cref="M:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage.#ctor(System.Uri)" /> oder <see cref="M:Microsoft.Azure.Batch.Conventions.Files.TaskOutputStorage.#ctor(System.Uri,System.String)" /> Konstruktoren, die eine <see cref="T:System.Uri" />.
            </summary>
        <returns>Die URL, einschließlich SAS, der der Auftrag Ausgabecontainer.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage OutputStorage(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorage (job As CloudJob, storageAccount As CloudStorageAccount) As JobOutputStorage" />
      <MemberSignature Language="F#" Value="static member OutputStorage : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount -&gt; Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorage (job, storageAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
      </Parameters>
      <Docs>
        <param name="job">Der Auftrag für die Ausgabe-Speicher abgerufen werden soll.</param>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.Batch.Conventions.Files.JobOutputStorage" /> für einen angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJob" />.
            </summary>
        <returns>Eine JobOutputStorage für den angegebenen Auftrag.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStorageContainerName">
      <MemberSignature Language="C#" Value="public static string OutputStorageContainerName (this Microsoft.Azure.Batch.CloudJob job);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string OutputStorageContainerName(class Microsoft.Azure.Batch.CloudJob job) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName(Microsoft.Azure.Batch.CloudJob)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function OutputStorageContainerName (job As CloudJob) As String" />
      <MemberSignature Language="F#" Value="static member OutputStorageContainerName : Microsoft.Azure.Batch.CloudJob -&gt; string" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.OutputStorageContainerName job" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
      </Parameters>
      <Docs>
        <param name="job">Der Auftrag für das Abrufen des Namens des Entitätencontainers.</param>
        <summary>
            Ruft den Namen des Azure-Blob-Speichercontainer für die Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.
            </summary>
        <returns>Der Name des Containers zum Speichern der Ausgaben des Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrepareOutputStorageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PrepareOutputStorageAsync (this Microsoft.Azure.Batch.CloudJob job, Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PrepareOutputStorageAsync(class Microsoft.Azure.Batch.CloudJob job, class Microsoft.WindowsAzure.Storage.CloudStorageAccount storageAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync(Microsoft.Azure.Batch.CloudJob,Microsoft.WindowsAzure.Storage.CloudStorageAccount,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PrepareOutputStorageAsync : Microsoft.Azure.Batch.CloudJob * Microsoft.WindowsAzure.Storage.CloudStorageAccount * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions.PrepareOutputStorageAsync (job, storageAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch.Conventions.Files</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Conventions.Files.CloudJobExtensions/&lt;PrepareOutputStorageAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="job" Type="Microsoft.Azure.Batch.CloudJob" RefType="this" />
        <Parameter Name="storageAccount" Type="Microsoft.WindowsAzure.Storage.CloudStorageAccount" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="job">Der Auftrag für die zum Erstellen des Containers.</param>
        <param name="storageAccount">Das Speicherkonto mit der Azure Batch-Konto verknüpft ist.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</param>
        <summary>
            Erstellt einen Azure-Blob-Speichercontainer für die Ausgaben von einem <see cref="T:Microsoft.Azure.Batch.CloudJob" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>