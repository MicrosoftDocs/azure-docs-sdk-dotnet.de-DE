<Type Name="OutputFile" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFile">
  <TypeSignature Language="C#" Value="public class OutputFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFile" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFile" />
  <TypeSignature Language="F#" Value="type OutputFile = class" />
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
            <span data-ttu-id="6e932-101">Eine Spezifikation für das Hochladen von Dateien aus einem Azure Batch-Knoten an einen anderen Speicherort aus, nachdem der Batch-Dienst beendet wurde, den Task Prozess ausführen.</span><span class="sxs-lookup"><span data-stu-id="6e932-101">A specification for uploading files from an Azure Batch node to another location after the Batch service has finished executing the task process.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.#ctor" />
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
            <span data-ttu-id="6e932-102">Initialisiert eine neue Instanz der OutputFile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e932-102">Initializes a new instance of the OutputFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile (string filePattern, Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination destination, Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions uploadOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filePattern, class Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination destination, class Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions uploadOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.#ctor(System.String,Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination,Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filePattern As String, destination As OutputFileDestination, uploadOptions As OutputFileUploadOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OutputFile : string * Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination * Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.OutputFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.OutputFile (filePattern, destination, uploadOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination" />
        <Parameter Name="uploadOptions" Type="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions" />
      </Parameters>
      <Docs>
        <param name="filePattern"><span data-ttu-id="6e932-103">Ein Muster, der angibt, die Ordner hochladen.</span><span class="sxs-lookup"><span data-stu-id="6e932-103">A pattern indicating which file(s) to upload.</span></span></param>
        <param name="destination"><span data-ttu-id="6e932-104">Das Ziel für die Ausgabedateien.</span><span class="sxs-lookup"><span data-stu-id="6e932-104">The destination for the output file(s).</span></span></param>
        <param name="uploadOptions"><span data-ttu-id="6e932-105">Zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.</span><span class="sxs-lookup"><span data-stu-id="6e932-105">Additional options for the upload operation, including under what conditions to perform the upload.</span></span></param>
        <summary>
            <span data-ttu-id="6e932-106">Initialisiert eine neue Instanz der OutputFile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6e932-106">Initializes a new instance of the OutputFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As OutputFileDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e932-107">Ruft ab oder legt das Ziel für die Ausgabedateien.</span><span class="sxs-lookup"><span data-stu-id="6e932-107">Gets or sets the destination for the output file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e932-108">Ermittelt oder definiert ein Muster, der angibt, die Ordner hochladen.</span><span class="sxs-lookup"><span data-stu-id="6e932-108">Gets or sets a pattern indicating which file(s) to upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="6e932-109">Relative und absolute Pfade werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="6e932-109">Both relative and absolute paths are supported.</span></span> <span data-ttu-id="6e932-110">Relative Pfade sind relativ zum Arbeitsverzeichnis Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="6e932-110">Relative paths are relative to the task working directory.</span></span> <span data-ttu-id="6e932-111">Die folgenden Platzhalter werden unterstützt: * entspricht 0 oder mehr Zeichen (Beispiel Muster Abc * entsprechen Abc oder Abcdef), ** entspricht einem beliebigen Verzeichnis?</span><span class="sxs-lookup"><span data-stu-id="6e932-111">The following wildcards are supported: * matches 0 or more characters (for example pattern abc* would match abc or abcdef), ** matches any directory, ?</span></span> <span data-ttu-id="6e932-112">entspricht jedem beliebigen einzelnen Zeichen, mit einem Zeichen in eckigen Klammern [Abc] und [a-c] entspricht einem Zeichen im Bereich.</span><span class="sxs-lookup"><span data-stu-id="6e932-112">matches any single character, [abc] matches one character in the brackets, and [a-c] matches one character in the range.</span></span> <span data-ttu-id="6e932-113">Klammern eine Negation entsprechend einem beliebigen Zeichen, die nicht angegeben (z. B. [! Abc] entspricht jedem außer a, b Zeichen oder c).</span><span class="sxs-lookup"><span data-stu-id="6e932-113">Brackets can include a negation to match any character not specified (for example [!abc] matches any character but a, b, or c).</span></span> <span data-ttu-id="6e932-114">Wenn ein Dateiname mit beginnt "." wird standardmäßig ignoriert, aber es kann abgeglichen werden, indem Sie es explizit angeben (z. B. *GIF stimmen nicht überein. a.gif, aber.*. GIF wird).</span><span class="sxs-lookup"><span data-stu-id="6e932-114">If a file name starts with "." it is ignored by default but may be matched by specifying it explicitly (for example *.gif will not match .a.gif, but .*.gif will).</span></span> <span data-ttu-id="6e932-115">Ein einfaches Beispiel: \* \* \\*".txt" entspricht jede Datei, die nicht, in gestartet wird "." und ".txt" in das Arbeitsverzeichnis für den Task oder einem Unterverzeichnis endet. Wenn der Dateiname ein Platzhalterzeichen enthält. es kann mit Escapezeichen versehen werden mithilfe von Klammern (z. B. Abc [*] würde eine Datei namens Abc entsprechen*).</span><span class="sxs-lookup"><span data-stu-id="6e932-115">A simple example: \**\\*.txt matches any file that does not start in '.' and ends with .txt in the task working directory or any subdirectory. If the filename contains a wildcard character it can be escaped using brackets (for example abc[*] would match a file named abc\*).</span></span> <span data-ttu-id="6e932-116">Beachten Sie, dass beide \ und / als Verzeichnistrennzeichen unter Windows ist jedoch nur behandelt werden / wird unter Linux.</span><span class="sxs-lookup"><span data-stu-id="6e932-116">Note that both \ and / are treated as directory separators on Windows, but only / is on Linux.</span></span> <span data-ttu-id="6e932-117">Umgebungsvariablen ("% Var-" unter Windows) oder $var unter Linux werden erweitert, vor dem das Muster angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="6e932-117">Environment variables (%var% on Windows or $var on Linux) are expanded prior to the pattern being applied.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions UploadOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions UploadOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OutputFile.UploadOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property UploadOptions As OutputFileUploadOptions" />
      <MemberSignature Language="F#" Value="member this.UploadOptions : Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFile.UploadOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uploadOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6e932-118">Ermittelt oder definiert zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.</span><span class="sxs-lookup"><span data-stu-id="6e932-118">Gets or sets additional options for the upload operation, including under what conditions to perform the upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OutputFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="outputFile.Validate " />
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
            <span data-ttu-id="6e932-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6e932-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6e932-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6e932-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>