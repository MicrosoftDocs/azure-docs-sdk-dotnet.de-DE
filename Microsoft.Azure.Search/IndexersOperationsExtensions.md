<Type Name="IndexersOperationsExtensions" FullName="Microsoft.Azure.Search.IndexersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class IndexersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit IndexersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.IndexersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module IndexersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type IndexersOperationsExtensions = class" />
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
            <span data-ttu-id="581ec-101">Vorgänge zum Verwalten von Indexern.</span><span class="sxs-lookup"><span data-stu-id="581ec-101">Operations for managing indexers.</span></span> 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Indexer-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer Create (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer Create(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Create(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Create (operations, indexer, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-102">The operations group for this extension method.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-103">Die Definition der zu erstellenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-103">The definition of the indexer to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-105">Erstellt einen neuen Azure Search-Indexer.</span><span class="sxs-lookup"><span data-stu-id="581ec-105">Creates a new Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateAsync (operations, indexer, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-106">The operations group for this extension method.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-107">Die Definition der zu erstellenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-107">The definition of the indexer to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-108">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-110">Erstellt einen neuen Azure Search-Indexer.</span><span class="sxs-lookup"><span data-stu-id="581ec-110">Creates a new Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer CreateOrUpdate (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer CreateOrUpdate(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate (operations, indexer, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-111">The operations group for this extension method.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-112">Die Definition des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-112">The definition of the indexer to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-113">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-113">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-114">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-114">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-115">Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-115">Creates a new Azure Search indexer or updates an indexer if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer CreateOrUpdate (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer CreateOrUpdate(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdate (operations, indexerName, indexer, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-116">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-117">Der Name des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-117">The name of the indexer to create or update.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-118">Die Definition des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-118">The definition of the indexer to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-119">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-119">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-120">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-120">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-121">Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-121">Creates a new Azure Search indexer or updates an indexer if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync (operations, indexer, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-122">The operations group for this extension method.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-123">Die Definition des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-123">The definition of the indexer to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-124">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-124">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-125">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-127">Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-127">Creates a new Azure Search indexer or updates an indexer if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.Indexer indexer, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.Indexer indexer, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.Indexer,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.Indexer * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.CreateOrUpdateAsync (operations, indexerName, indexer, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="indexer" Type="Microsoft.Azure.Search.Models.Indexer" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-128">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-129">Der Name des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-129">The name of the indexer to create or update.</span></span>
            </param>
        <param name="indexer">
            <span data-ttu-id="581ec-130">Die Definition des Indexers erstellt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="581ec-130">The definition of the indexer to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-131">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-131">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-132">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-132">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-134">Erstellt einen neuen Azure Search-Indexer oder aktualisiert einen Indexer, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-134">Creates a new Azure Search indexer or updates an indexer if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Delete(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Delete (operations, indexerName, searchRequestOptions, accessCondition)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-135">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-136">Der Name des zu löschenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-136">The name of the indexer to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-137">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-137">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-138">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-138">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-139">Löscht einen Azure Search-Indexer.</span><span class="sxs-lookup"><span data-stu-id="581ec-139">Deletes an Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.DeleteAsync (operations, indexerName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;DeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-140">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-141">Der Name des zu löschenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-141">The name of the indexer to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-142">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-142">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="581ec-143">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-143">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-145">Löscht einen Azure Search-Indexer.</span><span class="sxs-lookup"><span data-stu-id="581ec-145">Deletes an Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Exists(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Exists (operations, indexerName, searchRequestOptions)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-146">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-147">Der Name des Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-147">The name of the indexer.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-148">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-148">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-149">Legt fest, ob der angegebene Indexer im Azure-Suchdienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-149">Determines whether or not the given indexer exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="581ec-150"><c>"true"</c> Wenn der Indexer vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="581ec-150"><c>true</c> if the indexer exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ExistsAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-151">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-152">Der Name des Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-152">The name of the indexer.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-153">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-153">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-155">Legt fest, ob der angegebene Indexer im Azure-Suchdienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="581ec-155">Determines whether or not the given indexer exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="581ec-156"><c>"true"</c> Wenn der Indexer vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="581ec-156"><c>true</c> if the indexer exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.Indexer Get (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.Indexer Get(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Get(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.Indexer" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Get (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.Indexer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-157">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-158">Der Name des abzurufenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-158">The name of the indexer to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-159">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-160">Ruft eine indexerdefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="581ec-160">Retrieves an indexer definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt; GetAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.Indexer&gt; GetAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;GetAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.Indexer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-161">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-162">Der Name des abzurufenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-162">The name of the indexer to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-163">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-163">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-165">Ruft eine indexerdefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="581ec-165">Retrieves an indexer definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexerExecutionInfo GetStatus (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexerExecutionInfo GetStatus(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatus(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member GetStatus : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexerExecutionInfo" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatus (operations, indexerName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerExecutionInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-166">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-167">Der Name des Indexers, für das Status abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="581ec-167">The name of the indexer for which to retrieve status.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-168">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-168">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-169">Gibt den aktuellen Status und Ausführungsverlauf eines Indexers zurück.</span><span class="sxs-lookup"><span data-stu-id="581ec-169">Returns the current status and execution history of an indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer-Status" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt; GetStatusAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt; GetStatusAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatusAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStatusAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.GetStatusAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;GetStatusAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerExecutionInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-170">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-170">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-171">Der Name des Indexers, für das Status abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="581ec-171">The name of the indexer for which to retrieve status.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-172">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-172">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-174">Gibt den aktuellen Status und Ausführungsverlauf eines Indexers zurück.</span><span class="sxs-lookup"><span data-stu-id="581ec-174">Returns the current status and execution history of an indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Indexer-Status" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.IndexerListResult List (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.IndexerListResult List(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.List(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.IndexerListResult" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.IndexerListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-175">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-176">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-176">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-177">Listet alle Indexer für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="581ec-177">Lists all indexers available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexers" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt; ListAsync (this Microsoft.Azure.Search.IIndexersOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.IndexerListResult&gt; ListAsync(class Microsoft.Azure.Search.IIndexersOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ListAsync(Microsoft.Azure.Search.IIndexersOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IIndexersOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt;" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ListAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.IndexerListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-178">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-178">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-179">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-179">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-181">Listet alle Indexer für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="581ec-181">Lists all indexers available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Indexers" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reset">
      <MemberSignature Language="C#" Value="public static void Reset (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Reset(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Reset(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Reset : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Reset (operations, indexerName, searchRequestOptions)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-182">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-183">Der Name des zurückzusetzenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-183">The name of the indexer to reset.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-184">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-184">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-185">Setzt einen Azure Search-Indexer zugeordneten änderungsnachverfolgungsstatus zurück.</span><span class="sxs-lookup"><span data-stu-id="581ec-185">Resets the change tracking state associated with an Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Reset-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.ResetAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.ResetAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;ResetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-186">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-187">Der Name des zurückzusetzenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-187">The name of the indexer to reset.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-188">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-188">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-190">Setzt einen Azure Search-Indexer zugeordneten änderungsnachverfolgungsstatus zurück.</span><span class="sxs-lookup"><span data-stu-id="581ec-190">Resets the change tracking state associated with an Azure Search indexer.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Reset-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Run">
      <MemberSignature Language="C#" Value="public static void Run (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Run(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.Run(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Run : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; unit" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.Run (operations, indexerName, searchRequestOptions)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-191">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-192">Der Name des auszuführenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-192">The name of the indexer to run.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-193">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-193">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-194">Führt einen Azure Search-Indexer bei Bedarf an.</span><span class="sxs-lookup"><span data-stu-id="581ec-194">Runs an Azure Search indexer on-demand.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Run-Indexer" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RunAsync (this Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RunAsync(class Microsoft.Azure.Search.IIndexersOperations operations, string indexerName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.IndexersOperationsExtensions.RunAsync(Microsoft.Azure.Search.IIndexersOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RunAsync : Microsoft.Azure.Search.IIndexersOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.IndexersOperationsExtensions.RunAsync (operations, indexerName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.IndexersOperationsExtensions/&lt;RunAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IIndexersOperations" RefType="this" />
        <Parameter Name="indexerName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="581ec-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="581ec-195">The operations group for this extension method.</span></span>
            </param>
        <param name="indexerName">
            <span data-ttu-id="581ec-196">Der Name des auszuführenden Indexers.</span><span class="sxs-lookup"><span data-stu-id="581ec-196">The name of the indexer to run.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="581ec-197">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="581ec-197">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="581ec-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="581ec-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="581ec-199">Führt einen Azure Search-Indexer bei Bedarf an.</span><span class="sxs-lookup"><span data-stu-id="581ec-199">Runs an Azure Search indexer on-demand.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Run-Indexer" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>