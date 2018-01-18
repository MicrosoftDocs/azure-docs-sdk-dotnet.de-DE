<Type Name="DataSourcesOperationsExtensions" FullName="Microsoft.Azure.Search.DataSourcesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSourcesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSourcesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.DataSourcesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSourcesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSourcesOperationsExtensions = class" />
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
            <span data-ttu-id="2d30b-101">Vorgänge zum Verwalten von Datenquellen.</span><span class="sxs-lookup"><span data-stu-id="2d30b-101">Operations for managing datasources.</span></span> 
            <see href="https://docs.microsoft.com/rest/api/searchservice/Indexer-operations" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource Create (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource Create(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Create(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Create (operations, dataSource, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-102">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-103">Die Definition der zu erstellenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-103">The definition of the datasource to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-104">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-104">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-105">Erstellt eine neue Azure Search-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-105">Creates a new Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateAsync (operations, dataSource, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-106">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-106">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-107">Die Definition der zu erstellenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-107">The definition of the datasource to create.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-108">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-108">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-109">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-109">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-110">Erstellt eine neue Azure Search-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-110">Creates a new Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Create-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate (operations, dataSource, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-111">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-111">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-112">Die Definition der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-112">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-113">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-113">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-114">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-114">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-115">Erstellt eine neue Azure Search-Datenquelle oder eine Datenquelle aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-115">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource CreateOrUpdate (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource CreateOrUpdate(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdate (operations, dataSourceName, dataSource, searchRequestOptions, accessCondition)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-116">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-116">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-117">Der Name der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-117">The name of the datasource to create or update.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-118">Die Definition der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-118">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-119">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-119">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-120">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-120">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-121">Erstellt eine neue Azure Search-Datenquelle oder eine Datenquelle aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-121">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, dataSource, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-122">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-122">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-123">Die Definition der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-123">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-124">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-124">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-125">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-125">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-127">Erstellt eine neue Azure Search-Datenquelle oder eine Datenquelle aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-127">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.DataSource dataSource, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; CreateOrUpdateAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.DataSource dataSource, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.DataSource,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.DataSource * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.CreateOrUpdateAsync (operations, dataSourceName, dataSource, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="dataSource" Type="Microsoft.Azure.Search.Models.DataSource" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-128">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-128">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-129">Der Name der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-129">The name of the datasource to create or update.</span></span>
            </param>
        <param name="dataSource">
            <span data-ttu-id="2d30b-130">Die Definition der Datenquelle zu erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="2d30b-130">The definition of the datasource to create or update.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-131">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-131">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-132">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-132">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-133">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-133">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-134">Erstellt eine neue Azure Search-Datenquelle oder eine Datenquelle aktualisiert, wenn sie bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-134">Creates a new Azure Search datasource or updates a datasource if it already exists.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Update-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Delete(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition -&gt; unit" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Delete (operations, dataSourceName, searchRequestOptions, accessCondition)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-135">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-135">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-136">Der Name des zu löschenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-136">The name of the datasource to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-137">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-137">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-138">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-138">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-139">Löscht eine Azure Search-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-139">Deletes an Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Data-Source" /></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, Microsoft.Azure.Search.Models.AccessCondition accessCondition = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, class Microsoft.Azure.Search.Models.AccessCondition accessCondition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.DeleteAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,Microsoft.Azure.Search.Models.AccessCondition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * Microsoft.Azure.Search.Models.AccessCondition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.DeleteAsync (operations, dataSourceName, searchRequestOptions, accessCondition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="accessCondition" Type="Microsoft.Azure.Search.Models.AccessCondition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-140">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-140">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-141">Der Name des zu löschenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-141">The name of the datasource to delete.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-142">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-142">Additional parameters for the operation</span></span>
            </param>
        <param name="accessCondition">
            <span data-ttu-id="2d30b-143">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-143">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-144">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-144">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-145">Löscht eine Azure Search-Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-145">Deletes an Azure Search datasource.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Delete-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Exists(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; bool" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Exists (operations, dataSourceName, searchRequestOptions)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-146">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-146">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-147">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-147">The name of the data source.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-148">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-148">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-149">Legt fest, ob die angegebene Datenquelle im Azure-Suchdienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-149">Determines whether or not the given data source exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2d30b-150"><c>"true"</c> Wenn die Datenquelle vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="2d30b-150"><c>true</c> if the data source exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.ExistsAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.ExistsAsync (operations, dataSourceName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;ExistsAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-151">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-152">Der Name der Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-152">The name of the data source.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-153">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-153">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-154">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-154">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-155">Legt fest, ob die angegebene Datenquelle im Azure-Suchdienst vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="2d30b-155">Determines whether or not the given data source exists in the Azure Search service.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="2d30b-156"><c>"true"</c> Wenn die Datenquelle vorhanden ist. <c>"false"</c> andernfalls.</span><span class="sxs-lookup"><span data-stu-id="2d30b-156"><c>true</c> if the data source exists; <c>false</c> otherwise.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSource Get (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSource Get(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.Get(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSource" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.Get (operations, dataSourceName, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSource</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-157">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-158">Der Name der abzurufenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-158">The name of the datasource to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-159">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-159">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-160">Ruft ein Datenquellendefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="2d30b-160">Retrieves a datasource definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt; GetAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSource&gt; GetAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, string dataSourceName, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.GetAsync(Microsoft.Azure.Search.IDataSourcesOperations,System.String,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Search.IDataSourcesOperations * string * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.GetAsync (operations, dataSourceName, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;GetAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSource&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="dataSourceName" Type="System.String" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-161">The operations group for this extension method.</span></span>
            </param>
        <param name="dataSourceName">
            <span data-ttu-id="2d30b-162">Der Name der abzurufenden Datenquelle.</span><span class="sxs-lookup"><span data-stu-id="2d30b-162">The name of the datasource to retrieve.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-163">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-163">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-165">Ruft ein Datenquellendefinition aus Azure Search ab.</span><span class="sxs-lookup"><span data-stu-id="2d30b-165">Retrieves a datasource definition from Azure Search.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Get-Data-Source" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.DataSourceListResult List (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.DataSourceListResult List(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.List(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions -&gt; Microsoft.Azure.Search.Models.DataSourceListResult" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.List (operations, searchRequestOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DataSourceListResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-166">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-167">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-167">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-168">Listet alle Datenquellen, die für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="2d30b-168">Lists all datasources available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Data-Sources" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt; ListAsync (this Microsoft.Azure.Search.IDataSourcesOperations operations, Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Search.Models.DataSourceListResult&gt; ListAsync(class Microsoft.Azure.Search.IDataSourcesOperations operations, class Microsoft.Azure.Search.Models.SearchRequestOptions searchRequestOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.DataSourcesOperationsExtensions.ListAsync(Microsoft.Azure.Search.IDataSourcesOperations,Microsoft.Azure.Search.Models.SearchRequestOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Search.IDataSourcesOperations * Microsoft.Azure.Search.Models.SearchRequestOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt;" Usage="Microsoft.Azure.Search.DataSourcesOperationsExtensions.ListAsync (operations, searchRequestOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Search.DataSourcesOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Search.Models.DataSourceListResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Search.IDataSourcesOperations" RefType="this" />
        <Parameter Name="searchRequestOptions" Type="Microsoft.Azure.Search.Models.SearchRequestOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="2d30b-169">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="2d30b-169">The operations group for this extension method.</span></span>
            </param>
        <param name="searchRequestOptions">
            <span data-ttu-id="2d30b-170">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="2d30b-170">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="2d30b-171">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="2d30b-171">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="2d30b-172">Listet alle Datenquellen, die für einen Azure Search-Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="2d30b-172">Lists all datasources available for an Azure Search service.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/List-Data-Sources" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>