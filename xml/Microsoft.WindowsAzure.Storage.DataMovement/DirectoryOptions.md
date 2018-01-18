<Type Name="DirectoryOptions" FullName="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions">
  <TypeSignature Language="C#" Value="public class DirectoryOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DirectoryOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class DirectoryOptions" />
  <TypeSignature Language="F#" Value="type DirectoryOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
    <AssemblyVersion>0.5.3.0</AssemblyVersion>
    <AssemblyVersion>0.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="627c8-101">Stellt eine Reihe von Optionen, die für den Übertragungsvorgang Verzeichnis angegeben werden können</span><span class="sxs-lookup"><span data-stu-id="627c8-101">Represents a set of options that may be specified for directory transfer operation</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DirectoryOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.#ctor" />
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
    <Member MemberName="Recursive">
      <MemberSignature Language="C#" Value="public bool Recursive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Recursive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
      <MemberSignature Language="VB.NET" Value="Public Property Recursive As Boolean" />
      <MemberSignature Language="F#" Value="member this.Recursive : bool with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.Recursive" />
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
            <span data-ttu-id="627c8-102">Ruft ab, oder einen booleschen Wert ab, der angibt, ob Unterverzeichnisse enthalten, bei einem Übertragungsvorgang Verzeichnis.</span><span class="sxs-lookup"><span data-stu-id="627c8-102">Gets or sets a boolean that indicates whether to include subdirectories when doing a directory transfer operation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchPattern">
      <MemberSignature Language="C#" Value="public string SearchPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SearchPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property SearchPattern As String" />
      <MemberSignature Language="F#" Value="member this.SearchPattern : string with get, set" Usage="Microsoft.WindowsAzure.Storage.DataMovement.DirectoryOptions.SearchPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage.DataMovement</AssemblyName>
        <AssemblyVersion>0.5.3.0</AssemblyVersion>
        <AssemblyVersion>0.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="627c8-103">Ruft ab oder legt eine Zeichenfolge, die verwendet wird, um die Überprüfung der Namen von Dateien auf Übereinstimmungen.</span><span class="sxs-lookup"><span data-stu-id="627c8-103">Gets or sets a string that will be used to match against the names of files.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="627c8-104">SearchPattern Übereinstimmung unterscheidet sich für verschiedene Datenquellentypen zu Verzeichnis und die Einstellung der rekursiven: bei der Quelle lokalen Verzeichnispfad ist, wird mit Quelldateinamen als Standardplatzhalter SearchPattern abgeglichen.</span><span class="sxs-lookup"><span data-stu-id="627c8-104">Behavior of SearchPattern match varies for different source directory types and setting of Recursive: When source is local directory path, SearchPattern is matched against source file name as standard wildcards.</span></span> <span data-ttu-id="627c8-105">Wenn Recuresive auf "false" festgelegt ist, werden nur die Dateien direkt unterhalb des Quellverzeichnisses zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="627c8-105">If recuresive is set to false, only files directly under the source directory will be matched.</span></span> <span data-ttu-id="627c8-106">Andernfalls werden alle Dateien in das Unterverzeichnis ebenfalls zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="627c8-106">Otherwise, all files in the sub-directory will be matched as well.</span></span>
            
            <span data-ttu-id="627c8-107">Wenn Quelle Azure Blob-Verzeichnis ist, wenn Recuresive auf "true", "SearchPattern festgelegt ist wird als Präfix für Quell-Blob verglichen.</span><span class="sxs-lookup"><span data-stu-id="627c8-107">When source is Azure blob directory, if recuresive is set to true, SearchPattern is matched against source blob as name prefix.</span></span>
            <span data-ttu-id="627c8-108">Andernfalls, nur Azure-Blob mit dem genauen Namen SearchPattern gemäß wird abgeglichen werden.</span><span class="sxs-lookup"><span data-stu-id="627c8-108">Otherwise, only Azure blob with the exact name specified by SearchPattern will be matched.</span></span>
            
            <span data-ttu-id="627c8-109">Wenn Quelle Azure Dateiverzeichnis, ist, wenn rekursive auf "true", "SearchPattern festgelegt ist, wird nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="627c8-109">When source is Azure file directory, if recursive is set to true, SearchPattern is not supported.</span></span> <span data-ttu-id="627c8-110">Andernfalls werden nur Azure-Datei mit dem genauen Namen gemäß SearchPattern zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="627c8-110">Otherwise, only Azure file with the exact name specified by SearchPattern will be matched.</span></span>
            
            <span data-ttu-id="627c8-111">Wenn SearchPattern nicht angegeben ist, "*.*" für lokales Verzeichnis Quelle beim leere Zeichenfolge für Azure Blob-Datei-Verzeichnis verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="627c8-111">If SearchPattern is not specified, "*.*" will be used for local directory source while empty string for Azure blob/file directory.</span></span> <span data-ttu-id="627c8-112">So geben Sie das Suchmuster entweder oder rekursiv auf bei "true" festgelegt Quelle Directory Azure Blob-Datei ist, andernfalls keine Blob-Datei abgeglichen werden.</span><span class="sxs-lookup"><span data-stu-id="627c8-112">So please either specify the Search Pattern or set Recursive to true when source is Azure blob/file directory, otherwise, no blob/file will be matched.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>