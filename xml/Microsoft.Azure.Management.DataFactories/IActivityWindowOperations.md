<Type Name="IActivityWindowOperations" FullName="Microsoft.Azure.Management.DataFactories.IActivityWindowOperations">
  <TypeSignature Language="C#" Value="public interface IActivityWindowOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IActivityWindowOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IActivityWindowOperations" />
  <TypeSignature Language="F#" Value="type IActivityWindowOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b00b-101">Vorgänge für das Aktivitätsfenster.</span><span class="sxs-lookup"><span data-stu-id="6b00b-101">Operations for activity windows.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-102">Windows-Liste von Pipeline-Aktivitätsparameter Aktivitäten.</span><span class="sxs-lookup"><span data-stu-id="6b00b-102">Activity windows list by pipeline activity parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-103">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-103">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-104">Ruft die erste Seite der Aktivität Fensterinstanzen für eine pipelineaktivität mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-104">Gets the first page of activity window instances for a pipeline activity with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-105">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-105">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-106">Aktivität Windows eine Liste optionaler Filterparameter aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="6b00b-106">Activity windows list optional filter parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-107">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-108">Ruft die erste Seite der Aktivität Fensterinstanzen für eine Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-108">Gets the first page of activity window instances for a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-109">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-109">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-110">Windows-Aktivitätsliste von datasetparameter.</span><span class="sxs-lookup"><span data-stu-id="6b00b-110">Activity windows list by dataset parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-112">Ruft die erste Seite der Aktivität Fensterinstanzen für ein Dataset mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-112">Gets the first page of activity window instances for a dataset with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-113">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-113">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync (Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListAsync(Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListAsync (parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-114">Windows-Aktivitätsliste von Pipeline-Parameter.</span><span class="sxs-lookup"><span data-stu-id="6b00b-114">Activity windows list by pipeline parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-115">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-115">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-116">Ruft die erste Seite der Aktivität Fensterinstanzen für eine Pipeline mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-116">Gets the first page of activity window instances for a pipeline with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-117">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-117">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByActivityListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-118">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="6b00b-118">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b00b-119">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="6b00b-119">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-121">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-121">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-122">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-122">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDataFactoryListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-123">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="6b00b-123">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b00b-124">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="6b00b-124">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-125">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-126">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-126">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-127">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-127">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByDatasetListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-128">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="6b00b-128">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b00b-129">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="6b00b-129">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-130">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-131">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-131">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-132">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-132">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync (string nextLink, Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt; ListNextAsync(string nextLink, class Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IActivityWindowOperations.ListNextAsync(System.String,Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * Microsoft.Azure.Management.DataFactories.Models.ActivityWindowsByPipelineListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.ActivityWindowListResponse&gt;" Usage="iActivityWindowOperations.ListNextAsync (nextLink, parameters, cancellationToken)" />
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
            <span data-ttu-id="6b00b-133">Die URL, die nächste Seite der Aktivität Windows.</span><span class="sxs-lookup"><span data-stu-id="6b00b-133">The URL to the next page of activity windows.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="6b00b-134">Parameter für die Windows-Liste der Aktivitäten zu filtern.</span><span class="sxs-lookup"><span data-stu-id="6b00b-134">Filter parameters for activity windows list.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="6b00b-135">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="6b00b-135">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="6b00b-136">Ruft die nächste Seite der Aktivität ab, das Fensterinstanzen mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="6b00b-136">Gets the next page of activity window instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b00b-137">Liste Aktivität Windows Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="6b00b-137">The List activity windows operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>