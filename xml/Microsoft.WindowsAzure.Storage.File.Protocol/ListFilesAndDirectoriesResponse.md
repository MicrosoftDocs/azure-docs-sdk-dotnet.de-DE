<Type Name="ListFilesAndDirectoriesResponse" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListFilesAndDirectoriesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListFilesAndDirectoriesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListFilesAndDirectoriesResponse&#xA;Inherits ResponseParsingBase(Of IListFileEntry)" />
  <TypeSignature Language="F#" Value="type ListFilesAndDirectoriesResponse = class&#xA;    inherit ResponseParsingBase&lt;IListFileEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="26cc1-101">Stellt Methoden zum Analysieren der Antwort einen dateiauflistungsvorgang bereit.</span><span class="sxs-lookup"><span data-stu-id="26cc1-101">Provides methods for parsing the response from a file listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListFilesAndDirectoriesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" Usage="new Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse stream" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="stream" Type="System.IO.Stream" />
      </Parameters>
      <Docs>
        <param name="stream"><span data-ttu-id="26cc1-102">Der Stream, der analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="26cc1-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="26cc1-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="26cc1-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Files">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; Files { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; Files" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Files" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Files As IEnumerable(Of IListFileEntry)" />
      <MemberSignature Language="F#" Value="member this.Files : seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Files" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-104">Ruft eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" /> aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="26cc1-104">Gets an enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" /> from the response.</span></span>
            </summary>
        <value><span data-ttu-id="26cc1-105">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span><span class="sxs-lookup"><span data-stu-id="26cc1-105">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As FileListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-106">Ruft den Kontext für die Auflistung aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="26cc1-106">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="26cc1-107">Ein Satz von Parametern für die Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="26cc1-107">A set of parameters for the listing operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.Marker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-108">Ruft den Marker-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="26cc1-108">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="26cc1-109">Der markerwert.</span><span class="sxs-lookup"><span data-stu-id="26cc1-109">The Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.MaxResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-110">Ruft den "maxresults"-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="26cc1-110">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="26cc1-111">Der Wert "maxresults".</span><span class="sxs-lookup"><span data-stu-id="26cc1-111">The MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.NextMarker" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-112">Ruft den NextMarker-Wert aus der XML-Antwort ab, wenn die Auflistung nicht abgeschlossen war.</span><span class="sxs-lookup"><span data-stu-id="26cc1-112">Gets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="26cc1-113">Das NextMarker-Wert.</span><span class="sxs-lookup"><span data-stu-id="26cc1-113">The NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListFilesAndDirectoriesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of IListFileEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;" Usage="listFilesAndDirectoriesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="26cc1-114">Analysiert das Antwort-XML für einen dateiauflistungsvorgang an.</span><span class="sxs-lookup"><span data-stu-id="26cc1-114">Parses the response XML for a file listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="26cc1-115">Eine aufzählbare Auflistung von Objekten, implementieren <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span><span class="sxs-lookup"><span data-stu-id="26cc1-115">An enumerable collection of objects that implement <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.IListFileEntry" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>