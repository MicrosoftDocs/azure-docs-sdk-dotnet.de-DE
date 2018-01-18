<Type Name="ListSharesResponse" FullName="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse">
  <TypeSignature Language="C#" Value="public sealed class ListSharesResponse : Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ListSharesResponse extends Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ListSharesResponse&#xA;Inherits ResponseParsingBase(Of FileShareEntry)" />
  <TypeSignature Language="F#" Value="type ListSharesResponse = class&#xA;    inherit ResponseParsingBase&lt;FileShareEntry&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.WindowsAzure.Storage.Shared.Protocol.ResponseParsingBase&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="T">Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2cd51-101">Stellt Methoden zum Analysieren der Antwort aus einer Freigabe Auflistungsvorgang bereit.</span><span class="sxs-lookup"><span data-stu-id="2cd51-101">Provides methods for parsing the response from a share listing operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ListSharesResponse (System.IO.Stream stream);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.IO.Stream stream) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.#ctor(System.IO.Stream)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse : System.IO.Stream -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse" Usage="new Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse stream" />
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
        <param name="stream"><span data-ttu-id="2cd51-102">Der Stream, der analysiert werden.</span><span class="sxs-lookup"><span data-stu-id="2cd51-102">The stream to be parsed.</span></span></param>
        <summary>
            <span data-ttu-id="2cd51-103">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2cd51-103">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListingContext">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext ListingContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.ListingContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ListingContext As ListingContext" />
      <MemberSignature Language="F#" Value="member this.ListingContext : Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.ListingContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ListingContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cd51-104">Ruft den Kontext für die Auflistung aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="2cd51-104">Gets the listing context from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-105">Ein Satz von Parametern für die Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="2cd51-105">A set of parameters for the listing operation.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Marker">
      <MemberSignature Language="C#" Value="public string Marker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Marker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Marker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Marker As String" />
      <MemberSignature Language="F#" Value="member this.Marker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Marker" />
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
            <span data-ttu-id="2cd51-106">Ruft den Marker-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2cd51-106">Gets the Marker value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-107">Der markerwert.</span><span class="sxs-lookup"><span data-stu-id="2cd51-107">The Marker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxResults">
      <MemberSignature Language="C#" Value="public int MaxResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.MaxResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxResults As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxResults : int" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.MaxResults" />
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
            <span data-ttu-id="2cd51-108">Ruft den "maxresults"-Wert, der für die Auflistungsvorgang aus der XML-Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="2cd51-108">Gets the MaxResults value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-109">Der Wert "maxresults".</span><span class="sxs-lookup"><span data-stu-id="2cd51-109">The MaxResults value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextMarker">
      <MemberSignature Language="C#" Value="public string NextMarker { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextMarker" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.NextMarker" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextMarker As String" />
      <MemberSignature Language="F#" Value="member this.NextMarker : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.NextMarker" />
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
            <span data-ttu-id="2cd51-110">Ruft den NextMarker-Wert aus der XML-Antwort ab, wenn die Auflistung nicht abgeschlossen war.</span><span class="sxs-lookup"><span data-stu-id="2cd51-110">Gets the NextMarker value from the XML response, if the listing was not complete.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-111">Das NextMarker-Wert.</span><span class="sxs-lookup"><span data-stu-id="2cd51-111">The NextMarker value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ParseXml">
      <MemberSignature Language="C#" Value="protected override System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt; ParseXml ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt; ParseXml() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.ParseXml" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function ParseXml () As IEnumerable(Of FileShareEntry)" />
      <MemberSignature Language="F#" Value="override this.ParseXml : unit -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;" Usage="listSharesResponse.ParseXml " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2cd51-112">Analysiert das Antwort-XML für eine Freigabe Auflistungsvorgang an.</span><span class="sxs-lookup"><span data-stu-id="2cd51-112">Parses the response XML for a share listing operation.</span></span>
            </summary>
        <returns><span data-ttu-id="2cd51-113">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2cd51-113">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> objects.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Prefix">
      <MemberSignature Language="C#" Value="public string Prefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Prefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Prefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Prefix As String" />
      <MemberSignature Language="F#" Value="member this.Prefix : string" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Prefix" />
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
            <span data-ttu-id="2cd51-114">Ruft das Präfix Wertanbieter für die Auflistungsvorgang aus der XML-Antwort ab.</span><span class="sxs-lookup"><span data-stu-id="2cd51-114">Gets the Prefix value provided for the listing operation from the XML response.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-115">Der Präfix-Wert.</span><span class="sxs-lookup"><span data-stu-id="2cd51-115">The Prefix value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Shares">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt; Shares { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt; Shares" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Shares" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Shares As IEnumerable(Of FileShareEntry)" />
      <MemberSignature Language="F#" Value="member this.Shares : seq&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;" Usage="Microsoft.WindowsAzure.Storage.File.Protocol.ListSharesResponse.Shares" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2cd51-116">Ruft eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> Objekte aus der Antwort.</span><span class="sxs-lookup"><span data-stu-id="2cd51-116">Gets an enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> objects from the response.</span></span>
            </summary>
        <value><span data-ttu-id="2cd51-117">Eine aufzählbare Auflistung von <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> Objekte.</span><span class="sxs-lookup"><span data-stu-id="2cd51-117">An enumerable collection of <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileShareEntry" /> objects.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>