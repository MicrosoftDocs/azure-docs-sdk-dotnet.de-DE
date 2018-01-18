<Type Name="DownloadDirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions">
  <TypeSignature Language="C#" Value="public sealed class DownloadDirectoryOptions : Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DownloadDirectoryOptions extends Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DownloadDirectoryOptions&#xA;Inherits DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DownloadDirectoryOptions = class&#xA;    inherit DirectoryOptions" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2220e-101">Stellt eine Reihe von Optionen, die für Download Verzeichnisoperation angegeben werden können</span><span class="sxs-lookup"><span data-stu-id="2220e-101">Represents a set of options that may be specified for download directory operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DownloadDirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delimiter">
      <MemberSignature Language="C#" Value="public char Delimiter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance char Delimiter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
      <MemberSignature Language="VB.NET" Value="Public Property Delimiter As Char" />
      <MemberSignature Language="F#" Value="member this.Delimiter : char with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.Delimiter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Char</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2220e-102">Ermittelt oder definiert einen Char, der das Trennzeichen zum Trennen der virtuellen Verzeichnisse in einem blobnamen angibt.</span><span class="sxs-lookup"><span data-stu-id="2220e-102">Gets or sets a char that indicates the delimiter character used to delimit virtual directories in a blob name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableContentMD5Validation">
      <MemberSignature Language="C#" Value="public bool DisableContentMD5Validation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableContentMD5Validation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableContentMD5Validation As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableContentMD5Validation : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.DisableContentMD5Validation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2220e-103">Ruft ab oder legt ein Flag, das angibt, ob die Content-MD5 oder beim Lesen nicht von Daten aus dem Quellobjekt zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="2220e-103">Gets or sets a flag that indicates whether to validate content MD5 or not when reading data from the source object.</span></span>
            <span data-ttu-id="2220e-104">Wenn es sich bei festlegen auf "true", "Quellobjekt Content MD5 überprüft wird; Andernfalls wird Quellinhalt MD5-Objekt nicht überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="2220e-104">If set to true, source object content MD5 will be validated; otherwise, source object content MD5 will not be validated.</span></span>
            <span data-ttu-id="2220e-105">Wenn nicht angegeben ist, wird standardmäßig auf "false".</span><span class="sxs-lookup"><span data-stu-id="2220e-105">If not specified, it defaults to false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IncludeSnapshots">
      <MemberSignature Language="C#" Value="public bool IncludeSnapshots { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IncludeSnapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
      <MemberSignature Language="VB.NET" Value="Public Property IncludeSnapshots As Boolean" />
      <MemberSignature Language="F#" Value="member this.IncludeSnapshots : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DownloadDirectoryOptions.IncludeSnapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2220e-106">Ruft ab oder legt ein Flag, der angibt, ob Momentaufnahmen eingeschlossen werden sollen, beim Herunterladen von Azure Blob-Speicher.</span><span class="sxs-lookup"><span data-stu-id="2220e-106">Gets or sets a flag indicating whether to include snapshots when downloading from Azure blob storage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="2220e-107">Wenn dieses Flag, auf "true" Momentaufnahmen des Quell-Blob festgelegt ist wird als separate Dateien an Ziel kopiert werden.</span><span class="sxs-lookup"><span data-stu-id="2220e-107">If this flag is set to true, snapshots of the source blob will be copied to destination as separate files.</span></span> <span data-ttu-id="2220e-108">Ein Quell-Blob-Name im Format "x.y" wird angegeben, ist, auf dem "X" ist der Dateiname ohne Erweiterung und den Buchstaben "j" wird die Dateinamenerweiterung der Zieldateiname des Blob-Momentaufnahme als "x (% snapshot_time_stamp%).y" formatiert.</span><span class="sxs-lookup"><span data-stu-id="2220e-108">Given a source blob name in the form of "x.y", where 'x' is the file name without extension and 'y' is the file name extension, the destination file name of blob snapshot is formatted as "x (%snapshot_time_stamp%).y".</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>