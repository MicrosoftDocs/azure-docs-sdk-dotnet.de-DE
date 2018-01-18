<Type Name="OutputFileBlobContainerDestination" FullName="Microsoft.Azure.Batch.OutputFileBlobContainerDestination">
  <TypeSignature Language="C#" Value="public class OutputFileBlobContainerDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileBlobContainerDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileBlobContainerDestination" />
  <TypeSignature Language="F#" Value="type OutputFileBlobContainerDestination = class&#xA;    interface ITransportObjectProvider&lt;OutputFileBlobContainerDestination&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a3628-101">Gibt eine Datei hochladen Ziel innerhalb einer Azure-Blob-Speichercontainer.</span><span class="sxs-lookup"><span data-stu-id="a3628-101">Specifies a file upload destination within an Azure blob storage container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination (string containerUrl, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerUrl, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerUrl As String, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination : string * string -&gt; Microsoft.Azure.Batch.OutputFileBlobContainerDestination" Usage="new Microsoft.Azure.Batch.OutputFileBlobContainerDestination (containerUrl, path)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="containerUrl" Type="System.String" />
        <Parameter Name="path" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="containerUrl"><span data-ttu-id="a3628-102">Die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-102">The URL of the container within Azure Blob Storage to which to upload the file(s).</span></span></param>
        <param name="path"><span data-ttu-id="a3628-103">Der Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container, in dem die Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-103">The destination blob or virtual directory within the Azure Storage container to which to upload the file(s).</span></span></param>
        <summary>
            <span data-ttu-id="a3628-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a3628-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.OutputFileBlobContainerDestination" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerUrl">
      <MemberSignature Language="C#" Value="public string ContainerUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ContainerUrl : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.ContainerUrl" />
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
            <span data-ttu-id="a3628-105">Ruft die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-105">Gets the URL of the container within Azure Blob Storage to which to upload the file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="a3628-106">Die URL muss eine Shared Access Signature (SAS) ein, erteilen Schreibberechtigungen für den Container enthalten.</span><span class="sxs-lookup"><span data-stu-id="a3628-106">The URL must include a Shared Access Signature (SAS) granting write permissions to the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Batch.OutputFileBlobContainerDestination.Path" />
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
            <span data-ttu-id="a3628-107">Ruft ab, die Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container, in dem die Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-107">Gets the destination blob or virtual directory within the Azure Storage container to which to upload the file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="a3628-108">Wenn <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> bezieht sich auf eine bestimmte (d. h. er enthält keine Platzhalter), ist dies der Name des Blob, an dem diese Datei hochladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-108">If <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> refers to a specific file (i.e. it contains no wildcards), then this is the name of the blob to which to upload that file.</span></span></para>
          <para><span data-ttu-id="a3628-109">Wenn <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> Platzhalterzeichen enthält (und möglicherweise mehrere Dateien aus diesem Grund überein), und klicken Sie dann diese dann dies der Name des virtuellen Blob-Verzeichnisses ist (die einzelnen blobnamen vorangestellt ist), in dem die Dateien hochladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-109">If <see cref="P:Microsoft.Azure.Batch.OutputFile.FilePattern" /> contains wildcards (and may therefore match multiple files), then this then this is the name of the blob virtual directory (which is prepended to each blob name) to which to upload the file(s).</span></span></para>
          <para><span data-ttu-id="a3628-110">Wenn nicht angegeben, werden die Dateien in das Stammverzeichnis des Containers mit einem übereinstimmenden Dateinamen blobnamen hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="a3628-110">If omitted, file(s) are uploaded to the root of the container with a blob name matching their file name.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>