<Type Name="ResourceFile" FullName="Microsoft.Azure.Batch.ResourceFile">
  <TypeSignature Language="C#" Value="public class ResourceFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ResourceFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ResourceFile" />
  <TypeSignature Language="VB.NET" Value="Public Class ResourceFile" />
  <TypeSignature Language="F#" Value="type ResourceFile = class&#xA;    interface ITransportObjectProvider&lt;ResourceFile&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="77e60-101">Eine Datei aus dem Azure-Blob-Speicher auf einem Serverknoten z. B. Task ausführbare Dateien heruntergeladen und aufgabenbezogene Eingabedateien Daten.</span><span class="sxs-lookup"><span data-stu-id="77e60-101">A file to be downloaded to a compute node from Azure Blob Storage, such as task executables and task input data files.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ResourceFile (string blobSource, string filePath, string fileMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blobSource, string filePath, string fileMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ResourceFile.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (blobSource As String, filePath As String, Optional fileMode As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ResourceFile : string * string * string -&gt; Microsoft.Azure.Batch.ResourceFile" Usage="new Microsoft.Azure.Batch.ResourceFile (blobSource, filePath, fileMode)" />
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
        <param name="blobSource"><span data-ttu-id="77e60-102">Die URL der Datei innerhalb des Azure-Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="77e60-102">The URL of the file within Azure Blob Storage.</span></span></param>
        <param name="filePath"><span data-ttu-id="77e60-103">Der Speicherort, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task.</span><span class="sxs-lookup"><span data-stu-id="77e60-103">The location to which to download the file, relative to the task's working directory.</span></span></param>
        <param name="fileMode"><span data-ttu-id="77e60-104">Die Datei Berechtigung Mode-Attribut im Oktalformat.</span><span class="sxs-lookup"><span data-stu-id="77e60-104">The file permission mode attribute in octal format.</span></span></param>
        <summary>
            <span data-ttu-id="77e60-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ResourceFile" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="77e60-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ResourceFile" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobSource">
      <MemberSignature Language="C#" Value="public string BlobSource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobSource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.BlobSource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobSource As String" />
      <MemberSignature Language="F#" Value="member this.BlobSource : string" Usage="Microsoft.Azure.Batch.ResourceFile.BlobSource" />
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
            <span data-ttu-id="77e60-106">Ruft die URL der Datei innerhalb des Azure-Blob-Speicher ab.</span><span class="sxs-lookup"><span data-stu-id="77e60-106">Gets the URL of the file within Azure Blob Storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="77e60-107">Diese URL sollte eine shared Access Signature enthalten, wenn das Blob nicht öffentlich gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="77e60-107">This URL should include a shared access signature if the blob is not publicly readable.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="FileMode">
      <MemberSignature Language="C#" Value="public string FileMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FileMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileMode As String" />
      <MemberSignature Language="F#" Value="member this.FileMode : string" Usage="Microsoft.Azure.Batch.ResourceFile.FileMode" />
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
            <span data-ttu-id="77e60-108">Ruft die Datei Berechtigung Mode-Attribut im Oktalformat ab.</span><span class="sxs-lookup"><span data-stu-id="77e60-108">Gets the file permission mode attribute in octal format.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="77e60-109">Diese Eigenschaft ist nur anwendbar, wenn die Ressourcendatei auf einem Linux-Knoten heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="77e60-109">This property is applicable only if the resource file is downloaded to a Linux node.</span></span> <span data-ttu-id="77e60-110">Diese Eigenschaft wird ignoriert, wenn er für angegeben ist eine <see cref="T:Microsoft.Azure.Batch.ResourceFile" /> die wird zu einem Windows-Knoten heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="77e60-110">This property will be ignored if it is specified for a <see cref="T:Microsoft.Azure.Batch.ResourceFile" /> which will be downloaded to a Windows node.</span></span> <span data-ttu-id="77e60-111">Wenn diese Eigenschaft nicht für einen Linux-Knoten angegeben wird, ist der Standardwert 0770.</span><span class="sxs-lookup"><span data-stu-id="77e60-111">If this property is not specified for a Linux node, then the default value is 0770.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePath">
      <MemberSignature Language="C#" Value="public string FilePath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ResourceFile.FilePath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePath As String" />
      <MemberSignature Language="F#" Value="member this.FilePath : string" Usage="Microsoft.Azure.Batch.ResourceFile.FilePath" />
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
            <span data-ttu-id="77e60-112">Ruft den Speicherort, der zum Herunterladen der Datei, relativ zum Arbeitsverzeichnis für den Task ab.</span><span class="sxs-lookup"><span data-stu-id="77e60-112">Gets the location to which to download the file, relative to the task's working directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>