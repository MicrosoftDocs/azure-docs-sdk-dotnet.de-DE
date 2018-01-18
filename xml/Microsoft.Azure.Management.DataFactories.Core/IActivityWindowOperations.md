<Type Name="IActivityWindowOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations">
  <TypeSignature Language="C#" Value="public interface IActivityWindowOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityWindowOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityWindowOperations" />
  <TypeSignature Language="F#" Value="type IActivityWindowOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8cc16-101">Vorgänge für das Aktivitätsfenster.</span><span class="sxs-lookup"><span data-stu-id="8cc16-101">Operations for activity windows.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByDataFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDataFactoryAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDataFactoryAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListByDataFactoryAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDataFactoryAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListByDataFactoryAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="8cc16-102">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-102">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-103">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-104">Ruft die erste Seite der Aktivität Fensterinstanzen für eine Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-104">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-105">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-105">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDatasetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDatasetAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByDatasetAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListByDatasetAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByDatasetAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListByDatasetAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="8cc16-106">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-106">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-107">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-108">Ruft die erste Seite der Aktivität Fensterinstanzen für ein Dataset mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-108">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-109">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-109">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineActivityAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineActivityAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineActivityAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListByPipelineActivityAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByPipelineActivityAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListByPipelineActivityAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="8cc16-110">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-110">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-112">Ruft die erste Seite der Aktivität Fensterinstanzen für eine pipelineaktivität mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-112">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-113">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-113">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByPipelineAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListByPipelineAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListByPipelineAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByPipelineAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListByPipelineAsync (parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parameters">
            <span data-ttu-id="8cc16-114">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-114">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-115">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-115">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-116">Ruft die erste Seite der Aktivität Fensterinstanzen für eine Pipeline mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-116">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-117">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-117">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDataFactoryAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDataFactoryAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDataFactoryAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListNextByDataFactoryAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextByDataFactoryAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextByDataFactoryAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="8cc16-118">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc16-118">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cc16-119">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-119">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-121">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-121">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-122">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-122">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByDatasetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDatasetAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByDatasetAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListNextByDatasetAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextByDatasetAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextByDatasetAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="8cc16-123">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc16-123">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cc16-124">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-124">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-125">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-126">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-126">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-127">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-127">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipelineActivityAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineActivityAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineActivityAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListNextByPipelineActivityAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextByPipelineActivityAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextByPipelineActivityAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="8cc16-128">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc16-128">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cc16-129">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-129">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-130">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-131">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-131">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-132">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-132">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextByPipelineAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextByPipelineAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IActivityWindowOperations.ListNextByPipelineAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextByPipelineAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextByPipelineAsync (nextLink, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="8cc16-133">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="8cc16-133">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8cc16-134">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="8cc16-134">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="8cc16-135">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="8cc16-135">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8cc16-136">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="8cc16-136">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8cc16-137">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="8cc16-137">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>