<Type Name="IDocumentsOperations" FullName="Microsoft.Azure.Search.IDocumentsOperations">
  <TypeSignature Language="C#" Value="public interface IDocumentsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IDocumentsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentsOperations" />
  <TypeSignature Language="F#" Value="type IDocumentsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fd928-101">Definiert die Vorgänge zum Abfragen von Index und hochladen, Zusammenführen und Löschen von Dokumenten.</span><span class="sxs-lookup"><span data-stu-id="fd928-101">Defines operations for querying an index and uploading, merging, and deleting documents.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; ContinueSearchWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="continuationToken">
            <span data-ttu-id="fd928-102">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="fd928-102">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-103">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-103">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-104">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-104">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-106">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="fd928-106">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-107">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-107">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="fd928-108">Nicht generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="fd928-108">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="fd928-109">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="fd928-109">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-110">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd928-110">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="fd928-111">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="fd928-111">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-112">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="fd928-112">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="fd928-113">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="fd928-113">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; ContinueSearchWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.ContinueSearchWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContinueSearchWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.ContinueSearchWithHttpMessagesAsync (continuationToken, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="fd928-114">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fd928-114">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="fd928-115">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd928-115">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="continuationToken">
            <span data-ttu-id="fd928-116">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="fd928-116">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-117">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-117">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-118">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-118">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-119">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-119">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-120">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="fd928-120">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-121">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-121">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="fd928-122">Generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="fd928-122">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-123">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd928-123">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="fd928-124">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="fd928-124">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-125">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="fd928-125">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="fd928-126">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="fd928-126">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;long&gt;&gt; CountWithHttpMessagesAsync (Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;int64&gt;&gt; CountWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.CountWithHttpMessagesAsync(Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CountWithHttpMessagesAsync : Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;int64&gt;&gt;" Usage="iDocumentsOperations.CountWithHttpMessagesAsync (searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Int64&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-127">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-127">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-128">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-128">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-129">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-129">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-130">Fragt die Anzahl der Dokumente in der Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="fd928-130">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.Document&gt;&gt; GetWithHttpMessagesAsync(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.Document&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key">
            <span data-ttu-id="fd928-131">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd928-131">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="fd928-132">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt.</span><span class="sxs-lookup"><span data-stu-id="fd928-132">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-133">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-133">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-134">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-134">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-135">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-135">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-136">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="fd928-136">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="fd928-137">Die Antwort mit dem Dokument.</span><span class="sxs-lookup"><span data-stu-id="fd928-137">Response containing the document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-138">Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="fd928-138">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="fd928-139">Diese Zuordnung verfügt nicht über den Vorteil, dass Ausdrucksdatentyp Informationen aus dem Index, damit die Zuordnung nicht immer korrekt ist.</span><span class="sxs-lookup"><span data-stu-id="fd928-139">This mapping does not have the benefit of precise type information from the index, so the mapping is not always correct.</span></span> <span data-ttu-id="fd928-140">Insbesondere werden von den folgenden Fällen beachten: <list type="bullet"> <item> <description> einer beliebigen numerischen Wert ohne ein Dezimaltrennzeichen an. Int64 (Long in c#) deserialisiert werden. </description></item><item><description>Als Typ "System.String statt System.Double" werden besondere Gleitkommawerte mit doppelter Genauigkeit hinsichtlich Ihrer z. B. "NaN" und unendlich deserialisiert. </description></item><item><description>Jedes Zeichenfolgenfeld mit einem Wert, der formatiert wird, wie ein "DateTimeOffset" wird nicht ordnungsgemäß deserialisiert werden. Es wird empfohlen, solche Werte in Edm.DateTimeOffset Felder statt Edm.String Felder zu speichern. </description></item><item><description>Jedes Feld Edm.DateTimeOffset wird als eine System.DateTimeOffset, nicht System.DateTime deserialisiert werden.</description></item></list></span><span class="sxs-lookup"><span data-stu-id="fd928-140">In particular, be aware of the following cases: <list type="bullet"><item><description> Any numeric value without a decimal point will be deserialized to System.Int64 (long in C#). </description></item><item><description> Special double-precision floating point values such as NaN and Infinity will be deserialized as type System.String rather than System.Double. </description></item><item><description> Any string field with a value formatted like a DateTimeOffset will be deserialized incorrectly. We recommend storing such values in Edm.DateTimeOffset fields rather than Edm.String fields. </description></item><item><description> Any Edm.DateTimeOffset field will be deserialized as a System.DateTimeOffset, not System.DateTime. </description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt; GetWithHttpMessagesAsync&lt;T&gt; (string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;!!T&gt;&gt; GetWithHttpMessagesAsync&lt;class T&gt;(string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetWithHttpMessagesAsync : string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;'T&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.GetWithHttpMessagesAsync (key, selectedFields, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="fd928-141">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fd928-141">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="fd928-142">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd928-142">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="key">
            <span data-ttu-id="fd928-143">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="fd928-143">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="fd928-144">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt.</span><span class="sxs-lookup"><span data-stu-id="fd928-144">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-145">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-145">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-146">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-146">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-147">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-147">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-148">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="fd928-148">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="fd928-149">Die Antwort mit dem Dokument.</span><span class="sxs-lookup"><span data-stu-id="fd928-149">Response containing the document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-150">Die generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter T. Beachten Sie, dass alle Typen von Azure Search-Feld außer Sammlungen NULL-Werte zulässt, daher empfehlen wir mit Azure Search primitive Typen für die Eigenschaften des Typs t Die Typzuordnung lautet wie folgt: <list type="table"> <listheader> <term>Azure Search-Feldtyp</term><description>.NET Typ</description></listheader><item><term>Edm.String</term> <description> System.String (String in c#)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt; </description> </item> <item> <term>Edm.Boolean</term><description>System.Nullable&lt;System.Boolean&gt; (Bool? in c#)</description> </item> <item> <term>"Edm.Double"</term><description>System.Nullable&lt;System.Double&gt; (double? in c#)</description></item><item><term>Int32</term> <description>System.Nullable&lt;System. Int32&gt; (Int? in c#)</description></item><item><term>Int64</term><description>System.Nullable&lt; System. Int64&gt; (lange? in c#)</description></item><item><term>Edm.DateTimeOffset</term> <description> System.Nullable&lt; System.DateTimeOffset&gt; ("DateTimeOffset"? in c#) oder System.Nullable&lt;System.DateTime&gt; ("DateTime"? in c#). Beide Typen verwendet werden, obwohl es wird empfohlen, "DateTimeOffset". Wenn Sie Dokumente abrufen, wird "DateTime" Werte immer UTC. Beim Indizieren von Dokumenten werden DateTime-Werte wie folgt interpretiert: <list type="table"> <item> <term>UTC-DateTime</term><description>als gesendet – bis zum Index ist.</description> </item> <item> <term>Lokalen DateTime</term><description>vor dem senden, die dem Index in UTC konvertiert.</description> </item> <item> <term>"DateTime" mit nicht spezifizierten Zeitzone</term><description>davon ausgegangen, dass UTC und als gesendet – bis zum Index ist.</description> </item> </list> </description> </item> <item> <term>"Edm.geographypoint"</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></span><span class="sxs-lookup"><span data-stu-id="fd928-150">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. Note that all Azure Search field types except collections are nullable, so we recommend using nullable primitive types for the properties of type T. The type mapping is as follows: <list type="table"><listheader><term>Azure Search field type</term><description>.NET type</description></listheader><item><term>Edm.String</term><description>System.String (string in C#)</description></item><item><term>Collection(Edm.String)</term><description>IEnumerable&lt;System.String&gt;</description></item><item><term>Edm.Boolean</term><description>System.Nullable&lt;System.Boolean&gt; (bool? in C#)</description></item><item><term>Edm.Double</term><description>System.Nullable&lt;System.Double&gt; (double? in C#)</description></item><item><term>Edm.Int32</term><description>System.Nullable&lt;System.Int32&gt; (int? in C#)</description></item><item><term>Edm.Int64</term><description>System.Nullable&lt;System.Int64&gt; (long? in C#)</description></item><item><term>Edm.DateTimeOffset</term><description> System.Nullable&lt;System.DateTimeOffset&gt; (DateTimeOffset? in C#) or System.Nullable&lt;System.DateTime&gt; (DateTime? in C#). Both types work, although we recommend using DateTimeOffset. When retrieving documents, DateTime values will always be in UTC. When indexing documents, DateTime values are interpreted as follows: <list type="table"><item><term>UTC DateTime</term><description>Sent as-is to the index.</description></item><item><term>Local DateTime</term><description>Converted to UTC before being sent to the index.</description></item><item><term>DateTime with unspecified time zone</term><description>Assumed to be UTC and sent as-is to the index.</description></item></list></description></item><item><term>Edm.GeographyPoint</term><description><c cref="T:Microsoft.Spatial.GeographyPoint">Microsoft.Spatial.GeographyPoint</c></description></item></list></span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync (Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync(class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync(Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">
            <span data-ttu-id="fd928-151">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="fd928-151">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-152">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-152">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-153">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-153">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-155">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="fd928-155">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-156">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="fd928-156">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-157">Die nicht generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="fd928-157">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="fd928-158">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="fd928-158">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="fd928-159">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="fd928-159">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="fd928-160">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="fd928-160">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="fd928-161">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="fd928-161">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="fd928-162">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-162">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;T&gt; (Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; IndexWithHttpMessagesAsync&lt;class T&gt;(class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.IndexWithHttpMessagesAsync``1(Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member IndexWithHttpMessagesAsync : Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.IndexWithHttpMessagesAsync (batch, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="fd928-163">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fd928-163">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="fd928-164">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="fd928-164">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="batch">
            <span data-ttu-id="fd928-165">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="fd928-165">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-166">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-166">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-167">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-167">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-168">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-168">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-169">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="fd928-169">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-170">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="fd928-170">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-171">Generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter t Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="fd928-171">The generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="fd928-172">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="fd928-172">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="fd928-173">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="fd928-173">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="fd928-174">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="fd928-174">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="fd928-175">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-175">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt; SearchWithHttpMessagesAsync(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            <span data-ttu-id="fd928-176">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-176">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="fd928-177">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="fd928-177">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="fd928-178">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="fd928-178">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-179">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-179">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-180">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-180">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-181">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-181">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-182">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="fd928-182">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-183">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-183">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="fd928-184">Nicht generische Überladungen der Suche, SearchAsync und SearchWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="fd928-184">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="fd928-185">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="fd928-185">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-186">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd928-186">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="fd928-187">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="fd928-187">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;T&gt; (string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt;&gt; SearchWithHttpMessagesAsync&lt;class T&gt;(string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SearchWithHttpMessagesAsync : string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SearchWithHttpMessagesAsync (searchText, searchParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="fd928-188">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fd928-188">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="fd928-189">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd928-189">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="searchText">
            <span data-ttu-id="fd928-190">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-190">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="fd928-191">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="fd928-191">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="fd928-192">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="fd928-192">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-193">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-193">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-194">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-194">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-195">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-195">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-196">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="fd928-196">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="fd928-197">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-197">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="fd928-198">Generische Überladungen der Methoden suchen, SearchAsync und SearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter t Azure Search Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="fd928-198">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="fd928-199">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="fd928-199">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="fd928-200">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="fd928-200">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt; SuggestWithHttpMessagesAsync(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="searchText">
            <span data-ttu-id="fd928-201">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="fd928-201">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="fd928-202">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="fd928-202">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="fd928-203">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="fd928-203">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-204">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-204">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-205">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-205">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-207">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd928-207">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="fd928-208">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-208">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-209">Die nichtgenerischen Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="fd928-209">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="fd928-210">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="fd928-210">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestWithHttpMessagesAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;T&gt; (string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt;&gt; SuggestWithHttpMessagesAsync&lt;class T&gt;(string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IDocumentsOperations.SuggestWithHttpMessagesAsync``1(System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuggestWithHttpMessagesAsync : string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt;&gt; (requires 'T : null)" Usage="iDocumentsOperations.SuggestWithHttpMessagesAsync (searchText, suggesterName, suggestParameters, searchRequestOptions, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="fd928-211">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fd928-211">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="fd928-212">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="fd928-212">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="searchText">
            <span data-ttu-id="fd928-213">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="fd928-213">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="fd928-214">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="fd928-214">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="fd928-215">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="fd928-215">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="fd928-216">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="fd928-216">Additional parameters for the operation</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="fd928-217">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="fd928-217">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="fd928-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="fd928-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="fd928-219">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="fd928-219">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="fd928-220">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="fd928-220">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="fd928-221">Generische Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="fd928-221">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>