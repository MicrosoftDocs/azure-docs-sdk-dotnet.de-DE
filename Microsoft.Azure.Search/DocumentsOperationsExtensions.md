<Type Name="DocumentsOperationsExtensions" FullName="Microsoft.Azure.Search.DocumentsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DocumentsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DocumentsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.DocumentsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DocumentsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DocumentsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="137da-101">Vorgänge zum Abfragen von Index und hochladen, Zusammenführen und Löschen von Dokumenten.</span><span class="sxs-lookup"><span data-stu-id="137da-101">Operations for querying an index and uploading, merging, and deleting documents.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Document-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContinueSearch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult ContinueSearch(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-102">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="137da-103">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="137da-103">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-105">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-105">Retrieves the next page of search results from the Azure Search index.</span></span> 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-106">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-106">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-107">Nicht generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-107">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-108">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-108">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-109">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-109">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-110">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-110">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-111">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="137da-111">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="137da-112">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="137da-112">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearch&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; ContinueSearch&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; ContinueSearch&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ContinueSearch : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearch (operations, continuationToken, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-113">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-113">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-114">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-114">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-115">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-115">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="137da-116">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="137da-116">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-117">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-117">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-118">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-118">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-119">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-119">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-120">Generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-120">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-121">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-121">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-122">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-122">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-123">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="137da-123">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="137da-124">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="137da-124">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; ContinueSearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-125">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="137da-126">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="137da-126">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-127">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-127">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-129">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-129">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-130">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-130">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-131">Nicht generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-131">The non-generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-132">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-132">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-133">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-133">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-134">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-134">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-135">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="137da-135">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="137da-136">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="137da-136">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueSearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; ContinueSearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; ContinueSearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchContinuationToken continuationToken, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchContinuationToken,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ContinueSearchAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchContinuationToken * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.ContinueSearchAsync (operations, continuationToken, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;ContinueSearchAsync&gt;d__5`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="continuationToken" Type="Microsoft.Azure.Search.Models.SearchContinuationToken" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-137">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-137">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-138">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-138">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-139">The operations group for this extension method.</span></span>
            </param>
        <param name="continuationToken">
            <span data-ttu-id="137da-140">Kapselt den Zustand erforderlich, um die nächste Seite der Suchergebnisse aus dem Index abrufen.</span><span class="sxs-lookup"><span data-stu-id="137da-140">Encapsulates the state required to fetch the next page of search results from the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-141">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-141">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-142">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-142">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-143">Ruft die nächste Seite der Suchergebnisse aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-143">Retrieves the next page of search results from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-144">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-144">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-145">Generische Überladungen der Methoden ContinueSearch ContinueSearchAsync und ContinueSearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-145">The generic overloads of the ContinueSearch, ContinueSearchAsync, and ContinueSearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-146">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-146">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-147">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-147">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-148">Beachten Sie, dass diese Methode nicht vorgesehen ist, können Sie die Auslagerung von Suchergebnissen zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="137da-148">Note that this method is not meant to help you implement paging of search results.</span></span> <span data-ttu-id="137da-149">Implementieren Sie mithilfe von Paging der <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">oben</c> und <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">überspringen</c> Parameter für die <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Suche</c> Methode.</span><span class="sxs-lookup"><span data-stu-id="137da-149">You can implement paging using the <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Top">Top</c> and <c cref="P:Microsoft.Azure.Search.Models.SearchParameters.Skip">Skip</c> parameters to the <c cref="M:Microsoft.Azure.Search.IDocumentsOperations.SearchWithHttpMessagesAsync``1(System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)">Search</c> method.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public static long Count (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig int64 Count(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Count(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Count : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; int64" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Count (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-150">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-151">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-151">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-152">Fragt die Anzahl der Dokumente in der Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-152">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;long&gt; CountAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;int64&gt; CountAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CountAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.CountAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;CountAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-153">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-154">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-154">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-155">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-155">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-156">Fragt die Anzahl der Dokumente in der Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-156">Queries the number of documents in the Azure Search index.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Document Get (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Document Get(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Document" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Document</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-157">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="137da-158">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="137da-158">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="137da-159">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt.</span><span class="sxs-lookup"><span data-stu-id="137da-159">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span> <span data-ttu-id="137da-160">Alle abrufbar Felder sind standardmäßig im Resultset enthalten.</span><span class="sxs-lookup"><span data-stu-id="137da-160">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-161">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-161">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-162">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-162">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="137da-163">Das angeforderte Dokument.</span><span class="sxs-lookup"><span data-stu-id="137da-163">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-164">Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-164">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-165">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-165">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static T Get&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig !!T Get&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Get``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; 'T (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Get (operations, key, selectedFields, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-166">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-166">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-167">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-167">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-168">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="137da-169">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="137da-169">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="137da-170">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt.</span><span class="sxs-lookup"><span data-stu-id="137da-170">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span> <span data-ttu-id="137da-171">Alle abrufbar Felder sind standardmäßig im Resultset enthalten.</span><span class="sxs-lookup"><span data-stu-id="137da-171">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-172">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-172">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-173">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-173">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="137da-174">Das angeforderte Dokument.</span><span class="sxs-lookup"><span data-stu-id="137da-174">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-175">Generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-175">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt; GetAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Document&gt; GetAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Document&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-176">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="137da-177">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="137da-177">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="137da-178">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen werden aus dem zurückgegebenen Dokument fehlt.</span><span class="sxs-lookup"><span data-stu-id="137da-178">List of field names to retrieve for the document; Any field not retrieved will be missing from the returned document.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-179">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-179">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-181">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-181">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="137da-182">Das angeforderte Dokument.</span><span class="sxs-lookup"><span data-stu-id="137da-182">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-183">Die nicht generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-183">The non-generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-184">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-184">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;T&gt; GetAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string key, System.Collections.Generic.IEnumerable&lt;string&gt; selectedFields = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;!!T&gt; GetAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string key, class System.Collections.Generic.IEnumerable`1&lt;string&gt; selectedFields, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDocumentsOperations * string * seq&lt;string&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.GetAsync (operations, key, selectedFields, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;GetAsync&gt;d__9`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="selectedFields" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-185">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-185">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-186">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-186">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-187">The operations group for this extension method.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="137da-188">Der Schlüssel des abzurufenden Dokuments; Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> für die Regeln zum Erstellen von gültigen Dokumentschlüssel.</span><span class="sxs-lookup"><span data-stu-id="137da-188">The key of the document to retrieve; See <see href="https://docs.microsoft.com/rest/api/searchservice/Naming-rules" /> for the rules for constructing valid document keys.</span></span>
            </param>
        <param name="selectedFields">
            <span data-ttu-id="137da-189">Liste von Feldnamen für das Dokument abgerufen; Jedes Feld nicht abgerufen müssen Null oder Default als die entsprechenden Eigenschaftswert im zurückgegebenen Objekt.</span><span class="sxs-lookup"><span data-stu-id="137da-189">List of field names to retrieve for the document; Any field not retrieved will have null or default as its corresponding property value in the returned object.</span></span> <span data-ttu-id="137da-190">Alle abrufbar Felder sind standardmäßig im Resultset enthalten.</span><span class="sxs-lookup"><span data-stu-id="137da-190">All retrievable fields are included in the result by default.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-191">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-191">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-193">Ruft ein Dokument aus dem Azure-Suchindex ab.</span><span class="sxs-lookup"><span data-stu-id="137da-193">Retrieves a document from the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Lookup-Document" /></summary>
        <returns>
            <span data-ttu-id="137da-194">Das angeforderte Dokument.</span><span class="sxs-lookup"><span data-stu-id="137da-194">The requested document.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-195">Generische Überladungen der Methoden Get, GetAsync und GetWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-195">The generic overloads of the Get, GetAsync, and GetWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Index">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-196">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-196">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="137da-197">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="137da-197">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-198">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-198">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-199">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-199">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="137da-200">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="137da-200">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-201">Die nicht generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-201">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-202">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-202">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="137da-203">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="137da-203">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="137da-204">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="137da-204">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="137da-205">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="137da-205">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="137da-206">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-206">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Index&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentIndexResult Index&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Index``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Index : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentIndexResult (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Index (operations, batch, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentIndexResult</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-207">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-207">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-208">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="137da-208">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-209">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-209">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="137da-210">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="137da-210">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-211">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-211">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-212">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-212">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="137da-213">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="137da-213">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-214">Generische Überladung von Index und IndexAsync Methoden unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-214">The generic overloads of the Index and IndexAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="137da-215">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="137da-215">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="137da-216">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="137da-216">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="137da-217">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="137da-217">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="137da-218">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-218">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-219">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="137da-220">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="137da-220">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-221">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-221">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-222">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-222">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-223">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-223">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="137da-224">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="137da-224">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-225">Die nicht generische Überladungen der Index, IndexAsync und IndexWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-225">The non-generic overloads of the Index, IndexAsync, and IndexWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-226">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-226">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="137da-227">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="137da-227">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="137da-228">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="137da-228">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="137da-229">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="137da-229">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="137da-230">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-230">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="IndexAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt; batch, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentIndexResult&gt; IndexAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, class Microsoft.Azure.Search.Models.IndexBatch`1&lt;!!T&gt; batch, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync``1(Microsoft.Azure.Search.IDocumentsOperations,Microsoft.Azure.Search.Models.IndexBatch{``0},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member IndexAsync : Microsoft.Azure.Search.IDocumentsOperations * Microsoft.Azure.Search.Models.IndexBatch&lt;'T (requires 'T : null)&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.IndexAsync (operations, batch, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;IndexAsync&gt;d__13`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentIndexResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="batch" Type="Microsoft.Azure.Search.Models.IndexBatch&lt;T&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-231">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-231">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-232">Instanzen dieses Typs können als Dokumente im Index gespeichert werden.</span><span class="sxs-lookup"><span data-stu-id="137da-232">Instances of this type can be stored as documents in the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-233">The operations group for this extension method.</span></span>
            </param>
        <param name="batch">
            <span data-ttu-id="137da-234">Der Batch, der indexaktionen.</span><span class="sxs-lookup"><span data-stu-id="137da-234">The batch of index actions.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-235">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-235">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-236">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-236">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-237">Sendet einen Batch von hochladen, Zusammenführen und/oder löschen-Aktionen auf den Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-237">Sends a batch of upload, merge, and/or delete actions to the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/addupdate-or-delete-documents" /></summary>
        <returns>
            <span data-ttu-id="137da-238">Die Antwort enthält den Status von Vorgängen für alle Aktionen im Batch.</span><span class="sxs-lookup"><span data-stu-id="137da-238">Response containing the status of operations for all actions in the batch.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-239">Generische Überladung von Index und IndexAsync Methoden unterstützen die Zuordnung von Feldtypen für Azure Search .NET Typen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-239">The generic overloads of the Index and IndexAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Azure.Search.IndexBatchException">
            <span data-ttu-id="137da-240">Wird ausgelöst, wenn einige der Volltextindizierung Aktionen Fehler, aber andere Aktionen erfolgreich ausgeführt wurde und der Status des Indexes geändert.</span><span class="sxs-lookup"><span data-stu-id="137da-240">Thrown when some of the indexing actions failed, but other actions succeeded and modified the state of the index.</span></span> <span data-ttu-id="137da-241">Dies kann geschehen, wenn der Suchdienst Indizierung ausgelastet ist.</span><span class="sxs-lookup"><span data-stu-id="137da-241">This can happen when the Search Service is under heavy indexing load.</span></span> <span data-ttu-id="137da-242">Es ist wichtig, explizit diese Ausnahme abfangen und überprüfen Sie ihre <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="137da-242">It is important to explicitly catch this exception and check its <c cref="P:Microsoft.Azure.Search.IndexBatchException.IndexingResults">IndexResult</c> property.</span></span> <span data-ttu-id="137da-243">Diese Eigenschaft gibt den Status der einzelnen Indizierung Aktionen im Batch, wodurch den Status des Indexes nach einem Fehler, teilweise zu bestimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-243">This property reports the status of each indexing action in the batch, making it possible to determine the state of the index after a partial failure.</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Search">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult Search (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult Search(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-244">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-245">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-245">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="137da-246">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="137da-246">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="137da-247">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-247">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-248">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-248">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-249">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-249">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-250">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-250">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-251">Nicht generische Überladungen der Suche, SearchAsync und SearchWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-251">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-252">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-252">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-253">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-253">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-254">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-254">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Search&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt; Search&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt; Search&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Search``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Search : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Search (operations, searchText, searchParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-255">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-255">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-256">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-256">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-257">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-257">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-258">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-258">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="137da-259">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="137da-259">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="137da-260">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-260">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-261">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-261">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-262">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-262">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-263">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-263">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-264">Generische Überladungen der Methoden suchen, SearchAsync und SearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter t Azure Search Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-264">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-265">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-265">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-266">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-266">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult&gt; SearchAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-267">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-267">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-268">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-268">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="137da-269">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="137da-269">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="137da-270">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-270">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-271">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-271">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-272">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-272">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-273">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-273">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-274">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-274">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-275">Nicht generische Überladungen der Suche, SearchAsync und SearchWithHttpMessagesAsync Methoden stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-275">The non-generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-276">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-276">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-277">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-277">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-278">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-278">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="SearchAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt; SearchAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, Microsoft.Azure.Search.Models.SearchParameters searchParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSearchResult`1&lt;!!T&gt;&gt; SearchAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, class Microsoft.Azure.Search.Models.SearchParameters searchParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,Microsoft.Azure.Search.Models.SearchParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SearchAsync : Microsoft.Azure.Search.IDocumentsOperations * string * Microsoft.Azure.Search.Models.SearchParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SearchAsync (operations, searchText, searchParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SearchAsync&gt;d__17`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSearchResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="searchParameters" Type="Microsoft.Azure.Search.Models.SearchParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-279">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-279">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-280">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-280">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-281">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-281">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-282">Ein Abfrageausdruck für die Volltextsuche; Verwenden Sie Null oder "\*" alle Dokumente übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-282">A full-text search query expression; Use null or "\*" to match all documents.</span></span> <span data-ttu-id="137da-283">Finden Sie unter <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> Weitere Informationen zur Abfragesyntax für die Suche.</span><span class="sxs-lookup"><span data-stu-id="137da-283">See <see href="https://docs.microsoft.com/rest/api/searchservice/Simple-query-syntax-in-Azure-Search" /> for more information about search query syntax.</span></span>
            </param>
        <param name="searchParameters">
            <span data-ttu-id="137da-284">Parameter für die Suchabfrage verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-284">Parameters to further refine the search query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-285">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-285">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-286">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-286">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-287">Sucht nach Dokumenten in Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="137da-287">Searches for documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Search-Documents" /></summary>
        <returns>
            <span data-ttu-id="137da-288">Die Antwort mit den Dokumenten, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-288">Response containing the documents matching the query.</span></span>
            </returns>
        <remarks>
          <para>
            <span data-ttu-id="137da-289">Generische Überladungen der Methoden suchen, SearchAsync und SearchWithHttpMessagesAsync unterstützen die Zuordnung von Feldtypen, .NET-oder Schematypen über der Typparameter t Azure Search Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-289">The generic overloads of the Search, SearchAsync, and SearchWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </para>
          <para>
            <span data-ttu-id="137da-290">Wenn Azure Search alle Ergebnisse in einer einzelnen Antwort enthalten kann, umfasst die Antwort zurückgegeben wird ein Fortsetzungstoken ContinueSearch zum Abrufen von mehr Ergebnissen übergeben werden kann.</span><span class="sxs-lookup"><span data-stu-id="137da-290">If Azure Search can't include all results in a single response, the response returned will include a continuation token that can be passed to ContinueSearch to retrieve more results.</span></span>
            <span data-ttu-id="137da-291">Finden Sie unter <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> für Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="137da-291">See <c cref="P:Microsoft.Azure.Search.Models.DocumentSearchResultBase`2.ContinuationToken">DocumentSearchResultBase.ContinuationToken</c> for more information.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Suggest">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult Suggest(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-292">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-292">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-293">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="137da-293">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="137da-294">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="137da-294">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="137da-295">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-295">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-296">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-296">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-297">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="137da-297">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="137da-298">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-298">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-299">Die nichtgenerischen Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-299">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-300">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-300">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Suggest&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt; Suggest&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt; Suggest&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Suggest : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T (requires 'T : null)&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.Suggest (operations, searchText, suggesterName, suggestParameters, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-301">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-301">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-302">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-302">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-303">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-303">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-304">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="137da-304">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="137da-305">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="137da-305">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="137da-306">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-306">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-307">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-307">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-308">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="137da-308">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="137da-309">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-309">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-310">Generische Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-310">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult&gt; SuggestAsync(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="137da-311">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-311">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-312">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="137da-312">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="137da-313">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="137da-313">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="137da-314">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-314">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-315">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-315">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-316">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-316">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-317">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="137da-317">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="137da-318">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-318">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-319">Die nichtgenerischen Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync stellen einen Best-Effort-Versuch zum .NET-oder Schematypen JSON-Typen in die antwortnutzlast zuweisen.</span><span class="sxs-lookup"><span data-stu-id="137da-319">The non-generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods make a best-effort attempt to map JSON types in the response payload to .NET types.</span></span> <span data-ttu-id="137da-320">Weitere Informationen finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> .</span><span class="sxs-lookup"><span data-stu-id="137da-320">See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more information.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SuggestAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt; SuggestAsync&lt;T&gt; (this Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, Microsoft.Azure.Search.Models.SuggestParameters suggestParameters = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null) where T : class;" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DocumentSuggestResult`1&lt;!!T&gt;&gt; SuggestAsync&lt;class T&gt;(class Microsoft.Azure.Search.IDocumentsOperations operations, string searchText, string suggesterName, class Microsoft.Azure.Search.Models.SuggestParameters suggestParameters, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync``1(Microsoft.Azure.Search.IDocumentsOperations,System.String,System.String,Microsoft.Azure.Search.Models.SuggestParameters,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SuggestAsync : Microsoft.Azure.Search.IDocumentsOperations * string * string * Microsoft.Azure.Search.Models.SuggestParameters * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;'T&gt;&gt; (requires 'T : null)" Usage="Microsoft.Azure.Search.DocumentsOperationsExtensions.SuggestAsync (operations, searchText, suggesterName, suggestParameters, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DocumentsOperationsExtensions/&lt;SuggestAsync&gt;d__21`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DocumentSuggestResult&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T">
          <Constraints>
            <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDocumentsOperations" RefType="this" />
        <Parameter Name="searchText" Type="System.String" />
        <Parameter Name="suggesterName" Type="System.String" />
        <Parameter Name="suggestParameters" Type="Microsoft.Azure.Search.Models.SuggestParameters" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">
            <span data-ttu-id="137da-321">Die CLR-Typ, der dem IndexSchema zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="137da-321">The CLR type that maps to the index schema.</span></span> <span data-ttu-id="137da-322">Instanzen dieses Typs können als Dokumente aus dem Index abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="137da-322">Instances of this type can be retrieved as documents from the index.</span></span>
            </typeparam>
        <param name="operations">
            <span data-ttu-id="137da-323">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="137da-323">The operations group for this extension method.</span></span>
            </param>
        <param name="searchText">
            <span data-ttu-id="137da-324">Das Suchen von Text auf der Vorschläge basieren.</span><span class="sxs-lookup"><span data-stu-id="137da-324">The search text on which to base suggestions.</span></span>
            </param>
        <param name="suggesterName">
            <span data-ttu-id="137da-325">Der Name des suggesters gemäß Angabe in der suggester-Auflistung, die Teil der Indexdefinition ist.</span><span class="sxs-lookup"><span data-stu-id="137da-325">The name of the suggester as specified in the suggesters collection that's part of the index definition.</span></span>
            </param>
        <param name="suggestParameters">
            <span data-ttu-id="137da-326">Parameter, die die vorschlagsabfrage weiter zu verfeinern.</span><span class="sxs-lookup"><span data-stu-id="137da-326">Parameters to further refine the suggestion query.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="137da-327">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="137da-327">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="137da-328">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="137da-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="137da-329">Wird basierend auf dem Eingabetext und Vergleich von Dokumenten in der Azure-Suchindex Abfrageausdrücke vorgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="137da-329">Suggests query terms based on input text and matching documents in the Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Suggestions" /></summary>
        <returns>
            <span data-ttu-id="137da-330">Die Antwort mit der vorgeschlagene Text und Dokumente, die mit der Abfrage übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="137da-330">Response containing the suggested text and documents matching the query.</span></span>
            </returns>
        <remarks>
            <span data-ttu-id="137da-331">Generische Überladungen der Methoden vorschlagen, SuggestAsync und SuggestWithHttpMessagesAsync unterstützen die Zuordnung von Azure Search-Feld-Typen, die .NET-oder Schematypen über der Typparameter T. Finden Sie unter <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> detaillierte Informationen für die Typzuordnung.</span><span class="sxs-lookup"><span data-stu-id="137da-331">The generic overloads of the Suggest, SuggestAsync, and SuggestWithHttpMessagesAsync methods support mapping of Azure Search field types to .NET types via the type parameter T. See <see cref="M:Microsoft.Azure.Search.IDocumentsOperations.GetWithHttpMessagesAsync``1(System.String,System.Collections.Generic.IEnumerable{System.String},Microsoft.Azure.Search.Models.SearchRequestOptions,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" /> for more details on the type mapping.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>