<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.Protocol.Models.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class" />
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
            <span data-ttu-id="48ac7-101">Eine Datei, die auf einem Serverknoten aus dem Azure-Blob-Speicher heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="48ac7-101">A file to be downloaded from Azure blob storage to a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor" />
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
            <span data-ttu-id="48ac7-102">Initialisiert eine neue Instanz der Klasse ResourceFile an.</span><span class="sxs-lookup"><span data-stu-id="48ac7-102">Initializes a new instance of the ResourceFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ResourceFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.ResourceFile (blobSource, filePath, fileMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blobSource" Type="System.String" />
        <Parameter Name="filePath" Type="System.String" />
        <Parameter Name="fileMode" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blobSource"><span data-ttu-id="48ac7-103">Die URL der Datei innerhalb des Azure-Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="48ac7-103">The URL of the file within Azure Blob Storage.</span></span></param>
        <param name="filePath"><span data-ttu-id="48ac7-104">Der Speicherort auf den Serverknoten, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task.</span><span class="sxs-lookup"><span data-stu-id="48ac7-104">The location on the compute node to which to download the file, relative to the task's working directory.</span></span></param>
        <param name="fileMode"><span data-ttu-id="48ac7-105">Die Datei Berechtigung Mode-Attribut im Oktalformat.</span><span class="sxs-lookup"><span data-stu-id="48ac7-105">The file permission mode attribute in octal format.</span></span></param>
        <summary>
            <span data-ttu-id="48ac7-106">Initialisiert eine neue Instanz der Klasse ResourceFile an.</span><span class="sxs-lookup"><span data-stu-id="48ac7-106">Initializes a new instance of the ResourceFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.BlobSource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blobSource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="48ac7-107">Ruft ab oder legt die URL der Datei innerhalb des Azure-Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="48ac7-107">Gets or sets the URL of the file within Azure Blob Storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="48ac7-108">Diese URL muss anonyme Zugriff verwendet werden können; der Batch-Dienst darstellen, also keine Anmeldeinformationen, beim Herunterladen von BLOBs.</span><span class="sxs-lookup"><span data-stu-id="48ac7-108">This URL must be readable using anonymous access; that is, the Batch service does not present any credentials when downloading the blob.</span></span> <span data-ttu-id="48ac7-109">Es gibt zwei Möglichkeiten, einen solchen URL für ein Blob im Azure-Speicher: eine Shared Access Signature (SAS) ein, Gewähren von Lese-und Schreibberechtigungen für das Blob enthalten, oder legen Sie die Zugriffssteuerungsliste für das Blob oder den Container öffentlichen Zugriff zulassen.</span><span class="sxs-lookup"><span data-stu-id="48ac7-109">There are two ways to get such a URL for a blob in Azure storage: include a Shared Access Signature (SAS) granting read permissions on the blob, or set the ACL for the blob or its container to allow public access.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FileMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="48ac7-110">Ruft ab oder legt die Datei Berechtigung Mode-Attribut im Oktalformat.</span><span class="sxs-lookup"><span data-stu-id="48ac7-110">Gets or sets the file permission mode attribute in octal format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="48ac7-111">Diese Eigenschaft gilt nur für Dateien, die für Linux-Serverknoten heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="48ac7-111">This property applies only to files being downloaded to Linux compute nodes.</span></span> <span data-ttu-id="48ac7-112">Es wird ignoriert, wenn sie für eine ResourceFile angegeben ist, die auf einem Windows-Knoten heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="48ac7-112">It will be ignored if it is specified for a resourceFile which will be downloaded to a Windows node.</span></span> <span data-ttu-id="48ac7-113">Wenn diese Eigenschaft nicht für einen Linux-Knoten angegeben wird, wird ein Standardwert von 0770 in die Datei angewendet.</span><span class="sxs-lookup"><span data-stu-id="48ac7-113">If this property is not specified for a Linux node, then a default value of 0770 is applied to the file.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ResourceFile.FilePath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="48ac7-114">Ruft ab oder legt den Speicherort auf den Serverknoten, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task fest.</span><span class="sxs-lookup"><span data-stu-id="48ac7-114">Gets or sets the location on the compute node to which to download the file, relative to the task's working directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ResourceFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="resourceFile.Validate " />
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
            <span data-ttu-id="48ac7-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="48ac7-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="48ac7-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="48ac7-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>