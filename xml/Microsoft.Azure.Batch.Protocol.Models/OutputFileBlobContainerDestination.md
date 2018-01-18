<Type Name="OutputFileBlobContainerDestination" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination">
  <TypeSignature Language="C#" Value="public class OutputFileBlobContainerDestination" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFileBlobContainerDestination extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFileBlobContainerDestination" />
  <TypeSignature Language="F#" Value="type OutputFileBlobContainerDestination = class" />
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
            <span data-ttu-id="2ea62-101">Gibt eine Datei hochladen Ziel innerhalb einer Azure-Blob-Speichercontainer.</span><span class="sxs-lookup"><span data-stu-id="2ea62-101">Specifies a file upload destination within an Azure blob storage container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ea62-102">Initialisiert eine neue Instanz der OutputFileBlobContainerDestination-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ea62-102">Initializes a new instance of the OutputFileBlobContainerDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFileBlobContainerDestination (string containerUrl, string path = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string containerUrl, string path) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (containerUrl As String, Optional path As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination : string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination (containerUrl, path)" />
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
        <param name="containerUrl"><span data-ttu-id="2ea62-103">Die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="2ea62-103">The URL of the container within Azure Blob Storage to which to upload the file(s).</span></span></param>
        <param name="path"><span data-ttu-id="2ea62-104">Der Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container.</span><span class="sxs-lookup"><span data-stu-id="2ea62-104">The destination blob or virtual directory within the Azure Storage container.</span></span></param>
        <summary>
            <span data-ttu-id="2ea62-105">Initialisiert eine neue Instanz der OutputFileBlobContainerDestination-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2ea62-105">Initializes a new instance of the OutputFileBlobContainerDestination class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerUrl">
      <MemberSignature Language="C#" Value="public string ContainerUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerUrl As String" />
      <MemberSignature Language="F#" Value="member this.ContainerUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.ContainerUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ea62-106">Ruft ab oder legt die URL des Containers im Azure-Blob-Speicher, um Dateien hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="2ea62-106">Gets or sets the URL of the container within Azure Blob Storage to which to upload the file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ea62-107">Die URL muss eine Shared Access Signature (SAS) ein, erteilen Schreibberechtigungen für den Container enthalten.</span><span class="sxs-lookup"><span data-stu-id="2ea62-107">The URL must include a Shared Access Signature (SAS) granting write permissions to the container.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="path")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2ea62-108">Ruft ab, oder legt sie fest, die Ziel-Blob oder das virtuelle Verzeichnis in Azure Storage-Container.</span><span class="sxs-lookup"><span data-stu-id="2ea62-108">Gets or sets the destination blob or virtual directory within the Azure Storage container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2ea62-109">Wenn FilePattern auf eine bestimmte Datei verweist (d. h. keine Platzhalter enthält), dann lautet der Name des Blob, an dem diese Datei hochladen.</span><span class="sxs-lookup"><span data-stu-id="2ea62-109">If filePattern refers to a specific file (i.e. contains no wildcards), then path is the name of the blob to which to upload that file.</span></span> <span data-ttu-id="2ea62-110">Wenn FilePattern mindestens ein Platzhalterzeichen enthält (und daher möglicherweise mehrere Dateien übereinstimmen), ist Pfad den Namen des virtuellen Blob-Verzeichnisses (die einzelnen blobnamen vorangestellt ist), um Dateien hochzuladen.</span><span class="sxs-lookup"><span data-stu-id="2ea62-110">If filePattern contains one or more wildcards (and therefore may match multiple files), then path is the name of the blob virtual directory (which is prepended to each blob name) to which to upload the file(s).</span></span> <span data-ttu-id="2ea62-111">Wenn nicht angegeben, werden die Dateien in das Stammverzeichnis des Containers mit einem übereinstimmenden Dateinamen blobnamen hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="2ea62-111">If omitted, file(s) are uploaded to the root of the container with a blob name matching their file name.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFileBlobContainerDestination.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFileBlobContainerDestination.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2ea62-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2ea62-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2ea62-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2ea62-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>