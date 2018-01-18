<Type Name="DocumentSearchResultBase&lt;TResult,TDoc&gt;" FullName="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;TResult,TDoc&gt;">
  <TypeSignature Language="C#" Value="public class DocumentSearchResultBase&lt;TResult,TDoc&gt; where TResult : SearchResultBase&lt;TDoc&gt; where TDoc : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DocumentSearchResultBase`2&lt;(class Microsoft.Azure.Search.Models.SearchResultBase`1&lt;!TDoc&gt;) TResult, class TDoc&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2" />
  <TypeSignature Language="VB.NET" Value="Public Class DocumentSearchResultBase(Of TResult, TDoc)" />
  <TypeSignature Language="F#" Value="type DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResult">
      <Constraints>
        <BaseTypeName>Microsoft.Azure.Search.Models.SearchResultBase&lt;TDoc&gt;</BaseTypeName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TDoc">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="TResult">
            <span data-ttu-id="9343b-101">Der Typ der Skriptobjektmodell-Klasse, die Dokumente in einer Suchantwort kapselt.</span><span class="sxs-lookup"><span data-stu-id="9343b-101">Type of the model class that encapsulates documents in a search response.</span></span>
            </typeparam>
    <typeparam name="TDoc">
            <span data-ttu-id="9343b-102">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="9343b-102">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="9343b-103">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="9343b-103">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
    <summary>
            <span data-ttu-id="9343b-104">Antwort mit der Suche ergibt sich aus einem Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="9343b-104">Response containing search results from an Azure Search index.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DocumentSearchResultBase ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationToken">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.SearchContinuationToken ContinuationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property ContinuationToken As SearchContinuationToken" />
      <MemberSignature Language="F#" Value="member this.ContinuationToken : Microsoft.Azure.Search.Models.SearchContinuationToken with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.ContinuationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SearchContinuationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9343b-105">Ruft ein Fortsetzungstoken an, die verwendet wird, um den Vorgang fortzusetzen, Abrufen von Suchergebnissen an.</span><span class="sxs-lookup"><span data-stu-id="9343b-105">Gets a continuation token that is used to continue fetching search results.</span></span> <span data-ttu-id="9343b-106">Dies ist erforderlich, wenn eine suchanforderung mit einer einzigen Antwort von Azure Search entsprochen werden kann.</span><span class="sxs-lookup"><span data-stu-id="9343b-106">This is necessary when Azure Search cannot fulfill a search request with a single response.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="9343b-107">Diese Eigenschaft ist null, es sei denn, die Azure Search alle angeforderten Dokumente in einer einzelnen Suche Antwort zurückgeben kann.</span><span class="sxs-lookup"><span data-stu-id="9343b-107">This property will be null unless Azure Search can't return all the requested documents in a single Search response.</span></span> <span data-ttu-id="9343b-108">Das kann verschiedene Gründe sind implementierungsspezifisch und unterliegt Änderungen auftreten.</span><span class="sxs-lookup"><span data-stu-id="9343b-108">That can happen for different reasons which are implementation-specific and subject to change.</span></span>
            <span data-ttu-id="9343b-109">Stabile Clients sollten für die Behandlung von Fällen bereit sein, in denen weniger Dokumente als erwartet zurückgegeben werden und ein Fortsetzungstoken zum Abrufen von Dokumenten enthalten ist.</span><span class="sxs-lookup"><span data-stu-id="9343b-109">Robust clients should always be ready to handle cases where fewer documents than expected are returned and a continuation token is included to continue retrieving documents.</span></span> <span data-ttu-id="9343b-110">Wenn diese Eigenschaft nicht null ist, können Sie dessen Wert übergeben der <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">ContinueSearchAsync</c> Methode, um weitere Suchergebnisse abzurufen.</span><span class="sxs-lookup"><span data-stu-id="9343b-110">If this property is not null, you can pass its value to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">ContinueSearchAsync</c> method to retrieve more search results.</span></span>
            </para>
          <para>
            <span data-ttu-id="9343b-111">Beachten Sie, dass diese Eigenschaft nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="9343b-111">Note that this property is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="9343b-112">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter zu suchen.</span><span class="sxs-lookup"><span data-stu-id="9343b-112">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> search parameters.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9343b-113">Ruft die Gesamtzahl der Ergebnisse ab, durch den Suchvorgang gefunden, oder null, wenn die Anzahl die nicht angefordert wurde.</span><span class="sxs-lookup"><span data-stu-id="9343b-113">Gets the total count of results found by the search operation, or null if the count was not requested.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="9343b-114">Falls vorhanden, möglicherweise die Anzahl größer als die Anzahl von Ergebnissen in dieser Antwort.</span><span class="sxs-lookup"><span data-stu-id="9343b-114">If present, the count may be greater than the number of results in this response.</span></span> <span data-ttu-id="9343b-115">Dies kann geschehen, wenn Sie mithilfe der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> oder <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> Parameter, oder wenn Azure Search alle angeforderten Dokumente in einer einzelnen Suche Antwort zurückgeben kann.</span><span class="sxs-lookup"><span data-stu-id="9343b-115">This can happen if you use the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> or <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters, or if Azure Search can't return all the requested documents in a single Search response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Coverage">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Coverage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Coverage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Coverage" />
      <MemberSignature Language="VB.NET" Value="Public Property Coverage As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Coverage : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Coverage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9343b-116">Ruft einen Wert, der angibt, der des Prozentsatz des Indexes, der in der Abfrage enthalten, null oder, wenn MinimumCoverage nicht festgelegt wurde, der <c cref="T:Microsoft.Azure.Search.Models.SearchParameters">SearchParameters</c>.</span><span class="sxs-lookup"><span data-stu-id="9343b-116">Gets a value indicating the percentage of the index that was included in the query, or null if MinimumCoverage was not set in the <c cref="T:Microsoft.Azure.Search.Models.SearchParameters">SearchParameters</c>.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Facets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FacetResults Facets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.FacetResults Facets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Facets" />
      <MemberSignature Language="VB.NET" Value="Public Property Facets As FacetResults" />
      <MemberSignature Language="F#" Value="member this.Facets : Microsoft.Azure.Search.Models.FacetResults with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Facets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FacetResults</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9343b-117">Ruft das Facet Abfrageergebnisse für den Suchvorgang oder Null, wenn die Abfrage keine Facets Ausdrücke enthält.</span><span class="sxs-lookup"><span data-stu-id="9343b-117">Gets the facet query results for the search operation, or null if the query did not include any facet expressions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Results">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;TResult&gt; Results { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;!TResult&gt; Results" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.Results" />
      <MemberSignature Language="VB.NET" Value="Public Property Results As IList(Of TResult)" />
      <MemberSignature Language="F#" Value="member this.Results : System.Collections.Generic.IList&lt;'Result (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt;)&gt; with get, set" Usage="Microsoft.Azure.Search.Models.DocumentSearchResultBase&lt;'Result, 'Doc (requires 'Result :&gt; Microsoft.Azure.Search.Models.SearchResultBase&lt;'Doc&gt; and 'Doc : null)&gt;.Results" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9343b-118">Ruft die Sequenz der von der Abfrage zurückgegebenen Ergebnisse ab.</span><span class="sxs-lookup"><span data-stu-id="9343b-118">Gets the sequence of results returned by the query.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>