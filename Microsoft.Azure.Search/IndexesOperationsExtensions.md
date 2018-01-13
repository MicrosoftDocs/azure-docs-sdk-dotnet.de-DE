<Type Name="IndexesOperationsExtensions" FullName="Microsoft.Azure.Search.IndexesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IndexesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IndexesOperationsExtensions = class" />
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
            <span data-ttu-id="a5ec3-101">Vorgänge zum Verwalten von Indizes.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-101">Operations for managing indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Index-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Analyze">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.AnalyzeResult Analyze (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.AnalyzeResult Analyze(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Analyze : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.AnalyzeResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Analyze (operations, indexName, request, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.AnalyzeResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-102">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-103">Der Name des Indexes, für den test eines Analyzers.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-103">The name of the index for which to test an analyzer.</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="a5ec3-104">Die Text- und Analyzer oder Analysis-Komponenten zu testen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-104">The text and analyzer or analysis components to test.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-105">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-105">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-106">Zeigt, wie ein Analyzer Text in Token unterteilt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-106">Shows how an analyzer breaks text into tokens.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AnalyzeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.AnalyzeRequest request, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.AnalyzeResult&gt; AnalyzeAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.AnalyzeRequest request, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.AnalyzeRequest,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AnalyzeAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.AnalyzeRequest * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.AnalyzeAsync (operations, indexName, request, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;AnalyzeAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.AnalyzeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.Azure.Search.Models.AnalyzeRequest" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-107">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-107">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-108">Der Name des Indexes, für den test eines Analyzers.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-108">The name of the index for which to test an analyzer.</span></span>
            </param>
        <param name="request">
            <span data-ttu-id="a5ec3-109">Die Text- und Analyzer oder Analysis-Komponenten zu testen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-109">The text and analyzer or analysis components to test.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-110">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-110">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-111">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-111">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-112">Zeigt, wie ein Analyzer Text in Token unterteilt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-112">Shows how an analyzer breaks text into tokens.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/test-analyzer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Create (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Create(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Create(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Create (operations, index, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-113">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-114">Die Definition des Indexes zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-114">The definition of the index to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-115">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-115">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-116">Erstellt einen neuen Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-116">Creates a new Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateAsync (operations, index, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-117">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-118">Die Definition des Indexes zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-118">The definition of the index to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-119">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-119">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-120">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-120">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-121">Erstellt einen neuen Azure Search-Index.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-121">Creates a new Azure Search index.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-122">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-123">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-123">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="a5ec3-124">Können neue Analysen, Tokenizer, token Filter oder Char-Filter auf einen Index hinzugefügt werden, indem der Index offline mindestens ein paar Sekunden dauert.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-124">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="a5ec3-125">Dadurch wird vorübergehend indizierungs- und Abfragefunktionen Anforderungen fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-125">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="a5ec3-126">Leistung und Schreibverfügbarkeit des Indexes können nach der Indexaktualisierung mehrere Minuten lang eingeschränkt sein, bei sehr großen Indizes auch länger.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-126">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-127">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-127">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-128">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-128">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-129">Erstellt einen neuen Azure Search-Index oder einen Index aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-129">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index CreateOrUpdate (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index CreateOrUpdate(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdate (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-130">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-131">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-131">The definition of the index to create or update.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-132">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-132">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="a5ec3-133">Können neue Analysen, Tokenizer, token Filter oder Char-Filter auf einen Index hinzugefügt werden, indem der Index offline mindestens ein paar Sekunden dauert.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-133">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span>
            <span data-ttu-id="a5ec3-134">Dadurch wird vorübergehend indizierungs- und Abfragefunktionen Anforderungen fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-134">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="a5ec3-135">Leistung und Schreibverfügbarkeit des Indexes können nach der Indexaktualisierung mehrere Minuten lang eingeschränkt sein, bei sehr großen Indizes auch länger.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-135">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-136">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-136">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-137">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-137">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-138">Erstellt einen neuen Azure Search-Index oder einen Index aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-138">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-139">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-139">The operations group for this extension method.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-140">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-140">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="a5ec3-141">Können neue Analysen, Tokenizer, token Filter oder Char-Filter auf einen Index hinzugefügt werden, indem der Index offline mindestens ein paar Sekunden dauert.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-141">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span> <span data-ttu-id="a5ec3-142">Dadurch wird vorübergehend indizierungs- und Abfragefunktionen Anforderungen fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-142">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="a5ec3-143">Leistung und Schreibverfügbarkeit des Indexes können nach der Indexaktualisierung mehrere Minuten lang eingeschränkt sein, bei sehr großen Indizes auch länger.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-143">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-144">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-144">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-145">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-145">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-146">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-146">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-147">Erstellt einen neuen Azure Search-Index oder einen Index aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-147">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.Index index, Nullable&lt;bool&gt; allowIndexDowntime = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.Index index, valuetype System.Nullable`1&lt;bool&gt; allowIndexDowntime, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.Index,System.Nullable{System.Boolean},Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.Index * Nullable&lt;bool&gt; * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.CreateOrUpdateAsync (operations, indexName, index, allowIndexDowntime, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="index" Type="Microsoft.Azure.Search.Models.Index" />
        <Parameter Name="allowIndexDowntime" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-148">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-148">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-149">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-149">The definition of the index to create or update.</span></span>
            </param>
        <param name="index">
            <span data-ttu-id="a5ec3-150">Die Definition des Indexes erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-150">The definition of the index to create or update.</span></span>
            </param>
        <param name="allowIndexDowntime">
            <span data-ttu-id="a5ec3-151">Können neue Analysen, Tokenizer, token Filter oder Char-Filter auf einen Index hinzugefügt werden, indem der Index offline mindestens ein paar Sekunden dauert.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-151">Allows new analyzers, tokenizers, token filters, or char filters to be added to an index by taking the index offline for at least a few seconds.</span></span>
            <span data-ttu-id="a5ec3-152">Dadurch wird vorübergehend indizierungs- und Abfragefunktionen Anforderungen fehlschlägt.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-152">This temporarily causes indexing and query requests to fail.</span></span> <span data-ttu-id="a5ec3-153">Leistung und Schreibverfügbarkeit des Indexes können nach der Indexaktualisierung mehrere Minuten lang eingeschränkt sein, bei sehr großen Indizes auch länger.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-153">Performance and write availability of the index can be impaired for several minutes after the index is updated, or longer for very large indexes.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-154">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-154">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-155">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-155">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-157">Erstellt einen neuen Azure Search-Index oder einen Index aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-157">Creates a new Azure Search index or updates an index if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Delete(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Delete (operations, indexName, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-158">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-159">Der Name des zu löschenden Index.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-159">The name of the index to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-160">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-160">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-161">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-161">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-162">Löscht einen Azure Search-Index und die darin enthaltenen Dokumente.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-162">Deletes an Azure Search index and all the documents it contains.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.DeleteAsync (operations, indexName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;DeleteAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-163">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-163">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-164">Der Name des zu löschenden Index.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-164">The name of the index to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-165">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-165">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="a5ec3-166">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-166">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-167">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-167">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-168">Löscht einen Azure Search-Index und die darin enthaltenen Dokumente.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-168">Deletes an Azure Search index and all the documents it contains.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Exists(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Exists (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-169">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-170">Der Name des Indexes.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-170">The name of the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-171">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-171">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-172">Legt fest, ob der angegebene Index in der Azure Search-Dienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-172">Determines whether or not the given index exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="a5ec3-173"><c>"true"</c> Wenn der Index vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-173"><c>true</c> if the index exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ExistsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-174">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-175">Der Name des Indexes.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-175">The name of the index.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-176">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-176">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-178">Legt fest, ob der angegebene Index in der Azure Search-Dienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-178">Determines whether or not the given index exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="a5ec3-179"><c>"true"</c> Wenn der Index vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-179"><c>true</c> if the index exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Index Get (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Index Get(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.Get(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Index" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.Get (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Index</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-180">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-181">Der Name des Indexes abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-181">The name of the index to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-182">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-182">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-183">Ruft eine Indexdefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-183">Retrieves an index definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt; GetAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Index&gt; GetAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Index&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-184">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-185">Der Name des Indexes abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-185">The name of the index to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-186">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-186">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-187">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-187">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-188">Ruft eine Indexdefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-188">Retrieves an index definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatistics">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexGetStatisticsResult GetStatistics(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member GetStatistics : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexGetStatisticsResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatistics (operations, indexName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexGetStatisticsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-189">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-189">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-190">Der Name des Indexes, für den Statistiken abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-190">The name of the index for which to retrieve statistics.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-191">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-191">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-192">Gibt Statistiken für den angegebenen Index, einschließlich der Anzahl und den Speicher einer dokumentnutzung zurück.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-192">Returns statistics for the given index, including a document count and storage usage.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatisticsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string indexName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt; GetStatisticsAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string indexName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatisticsAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.GetStatisticsAsync (operations, indexName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;GetStatisticsAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexGetStatisticsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="indexName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-193">The operations group for this extension method.</span></span>
            </param>
        <param name="indexName">
            <span data-ttu-id="a5ec3-194">Der Name des Indexes, für den Statistiken abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-194">The name of the index for which to retrieve statistics.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-195">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-195">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-197">Gibt Statistiken für den angegebenen Index, einschließlich der Anzahl und den Speicher einer dokumentnutzung zurück.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-197">Returns statistics for the given index, including a document count and storage usage.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Index-Statistics" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexListResult List (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexListResult List(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.List(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexListResult" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.List (operations, select, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-198">The operations group for this extension method.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="a5ec3-199">Wählt die Eigenschaften der Indexdefinitionen abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-199">Selects which properties of the index definitions to retrieve.</span></span> <span data-ttu-id="a5ec3-200">Als eine durch Trennzeichen getrennte Liste von JSON-Eigenschaftennamen, oder "\*" für alle Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-200">Specified as a comma-separated list of JSON property names, or '\*' for all properties.</span></span>
            <span data-ttu-id="a5ec3-201">Der Standardwert ist alle Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-201">The default is all properties.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-202">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-202">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-203">Listet alle Indizes für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-203">Lists all indexes available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync (this Microsoft.Azure.Search.IIndexesOperations operations, string select = null, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexListResult&gt; ListAsync(class Microsoft.Azure.Search.IIndexesOperations operations, string select, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync(Microsoft.Azure.Search.IIndexesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IIndexesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListAsync (operations, select, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="select" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-204">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-204">The operations group for this extension method.</span></span>
            </param>
        <param name="select">
            <span data-ttu-id="a5ec3-205">Wählt die Eigenschaften der Indexdefinitionen abgerufen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-205">Selects which properties of the index definitions to retrieve.</span></span> <span data-ttu-id="a5ec3-206">Als eine durch Trennzeichen getrennte Liste von JSON-Eigenschaftennamen, oder "\*" für alle Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-206">Specified as a comma-separated list of JSON property names, or '\*' for all properties.</span></span>
            <span data-ttu-id="a5ec3-207">Der Standardwert ist alle Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-207">The default is all properties.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-208">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-208">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-210">Listet alle Indizes für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-210">Lists all indexes available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNames">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IList&lt;string&gt; ListNames (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IList`1&lt;string&gt; ListNames(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member ListNames : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNames (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-211">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-211">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-212">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-212">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-213">Listet die Namen aller verfügbaren Indizes für einen Azure Search-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-213">Lists the names of all indexes available for an Azure Search service.</span></span> <span data-ttu-id="a5ec3-214">Verwenden Sie diese anstatt List(), wenn Sie nur Namen indizieren müssen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-214">Use this instead of List() when you only need index names.</span></span> <span data-ttu-id="a5ec3-215">Es wird die Bandbreite und der ressourcennutzung, speichern, insbesondere, wenn Ihre Suchdienst viele Indizes aufweist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-215">It will save bandwidth and resource utilization, especially if your Search Service has many indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            <span data-ttu-id="a5ec3-216">Die Liste der alle Indexnamen für den Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-216">The list of all index names for the search service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNamesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt; ListNamesAsync (this Microsoft.Azure.Search.IIndexesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;string&gt;&gt; ListNamesAsync(class Microsoft.Azure.Search.IIndexesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync(Microsoft.Azure.Search.IIndexesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNamesAsync : Microsoft.Azure.Search.IIndexesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;string&gt;&gt;" Usage="Microsoft.Azure.Search.IndexesOperationsExtensions.ListNamesAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexesOperationsExtensions/&lt;ListNamesAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="a5ec3-217">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-217">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="a5ec3-218">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="a5ec3-218">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a5ec3-219">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-219">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a5ec3-220">Listet die Namen aller verfügbaren Indizes für einen Azure Search-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-220">Lists the names of all indexes available for an Azure Search service.</span></span> <span data-ttu-id="a5ec3-221">Verwenden Sie diese anstatt List(), wenn Sie nur Namen indizieren müssen.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-221">Use this instead of List() when you only need index names.</span></span> <span data-ttu-id="a5ec3-222">Es wird die Bandbreite und der ressourcennutzung, speichern, insbesondere, wenn Ihre Suchdienst viele Indizes aufweist.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-222">It will save bandwidth and resource utilization, especially if your Search Service has many indexes.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexes" /></summary>
        <returns>
            <span data-ttu-id="a5ec3-223">Die Liste der alle Indexnamen für den Suchdienst.</span><span class="sxs-lookup"><span data-stu-id="a5ec3-223">The list of all index names for the search service.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>