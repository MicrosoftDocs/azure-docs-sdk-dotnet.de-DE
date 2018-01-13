<Type Name="OutputFile" FullName="Microsoft.Azure.Batch.OutputFile">
  <TypeSignature Language="C#" Value="public class OutputFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OutputFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.OutputFile" />
  <TypeSignature Language="VB.NET" Value="Public Class OutputFile" />
  <TypeSignature Language="F#" Value="type OutputFile = class&#xA;    interface ITransportObjectProvider&lt;OutputFile&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="1850b-101">Eine Spezifikation für das Hochladen von Dateien aus einem Azure Batch-Knoten an einen anderen Speicherort aus, nachdem der Batch-Dienst beendet wurde, den Task Prozess ausführen.</span><span class="sxs-lookup"><span data-stu-id="1850b-101">A specification for uploading files from an Azure Batch node to another location after the Batch service has finished executing the task process.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OutputFile (string filePattern, Microsoft.Azure.Batch.OutputFileDestination destination, Microsoft.Azure.Batch.OutputFileUploadOptions uploadOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string filePattern, class Microsoft.Azure.Batch.OutputFileDestination destination, class Microsoft.Azure.Batch.OutputFileUploadOptions uploadOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.OutputFile.#ctor(System.String,Microsoft.Azure.Batch.OutputFileDestination,Microsoft.Azure.Batch.OutputFileUploadOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (filePattern As String, destination As OutputFileDestination, uploadOptions As OutputFileUploadOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.OutputFile : string * Microsoft.Azure.Batch.OutputFileDestination * Microsoft.Azure.Batch.OutputFileUploadOptions -&gt; Microsoft.Azure.Batch.OutputFile" Usage="new Microsoft.Azure.Batch.OutputFile (filePattern, destination, uploadOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="destination" Type="Microsoft.Azure.Batch.OutputFileDestination" />
        <Parameter Name="uploadOptions" Type="Microsoft.Azure.Batch.OutputFileUploadOptions" />
      </Parameters>
      <Docs>
        <param name="filePattern"><span data-ttu-id="1850b-102">Ein Muster, der angibt, die Ordner hochladen.</span><span class="sxs-lookup"><span data-stu-id="1850b-102">A pattern indicating which file(s) to upload.</span></span></param>
        <param name="destination"><span data-ttu-id="1850b-103">Das Ziel für die Ausgabedateien.</span><span class="sxs-lookup"><span data-stu-id="1850b-103">The destination for the output file(s).</span></span></param>
        <param name="uploadOptions"><span data-ttu-id="1850b-104">Zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.</span><span class="sxs-lookup"><span data-stu-id="1850b-104">Additional options for the upload operation, including under what conditions to perform the upload.</span></span></param>
        <summary>
            <span data-ttu-id="1850b-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.OutputFile" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1850b-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.OutputFile" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OutputFileDestination Destination { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OutputFileDestination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.Destination" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Destination As OutputFileDestination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Batch.OutputFileDestination" Usage="Microsoft.Azure.Batch.OutputFile.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OutputFileDestination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1850b-106">Ruft das Ziel für die Ausgabedateien ab.</span><span class="sxs-lookup"><span data-stu-id="1850b-106">Gets the destination for the output file(s).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string" Usage="Microsoft.Azure.Batch.OutputFile.FilePattern" />
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
            <span data-ttu-id="1850b-107">Ruft ein Muster, der angibt, die Ordner hochladen.</span><span class="sxs-lookup"><span data-stu-id="1850b-107">Gets a pattern indicating which file(s) to upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1850b-108">Relative und absolute Pfade werden unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1850b-108">Both relative and absolute paths are supported.</span></span> <span data-ttu-id="1850b-109">Relative Pfade sind relativ zum Arbeitsverzeichnis Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="1850b-109">Relative paths are relative to the task working directory.</span></span> <span data-ttu-id="1850b-110">Verwenden Sie Platzhalterzeichen, \* auf einem beliebigen Zeichen entspricht und \*\* mit einem beliebigen Verzeichnis übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="1850b-110">For wildcards, use \* to match any character and \*\* to match any directory.</span></span> <span data-ttu-id="1850b-111">Z. B. \*\*\\*".txt" entspricht jede Datei in ".txt" in das Arbeitsverzeichnis für den Task oder einem Unterverzeichnis beenden.</span><span class="sxs-lookup"><span data-stu-id="1850b-111">For example, \*\*\\*.txt matches any file ending in .txt in the task working directory or any subdirectory.</span></span> <span data-ttu-id="1850b-112">Beachten Sie, dass \ und / Synonym behandelt und das richtige Verzeichnistrennzeichen unter dem Betriebssystem des Compute-Knoten zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="1850b-112">Note that \ and / are treated interchangeably and mapped to the correct directory separator on the compute node operating system.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UploadOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.OutputFileUploadOptions UploadOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.OutputFileUploadOptions UploadOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.OutputFile.UploadOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UploadOptions As OutputFileUploadOptions" />
      <MemberSignature Language="F#" Value="member this.UploadOptions : Microsoft.Azure.Batch.OutputFileUploadOptions" Usage="Microsoft.Azure.Batch.OutputFile.UploadOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.OutputFileUploadOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1850b-113">Ruft zusätzliche Optionen für den Uploadvorgang, einschließlich unter welche Bedingungen, um der Upload auszuführen.</span><span class="sxs-lookup"><span data-stu-id="1850b-113">Gets additional options for the upload operation, including under what conditions to perform the upload.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>