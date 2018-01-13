<Type Name="IPipelineOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations">
  <TypeSignature Language="C#" Value="public interface IPipelineOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPipelineOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPipelineOperations" />
  <TypeSignature Language="F#" Value="type IPipelineOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="df813-101">Vorgänge zum Verwalten von Pipelines.</span><span class="sxs-lookup"><span data-stu-id="df813-101">Operations for managing pipelines.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df813-104">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="df813-104">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-106">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="df813-106">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-107">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-107">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-109">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-109">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-110">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-110">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df813-111">Die Parameter zum Erstellen einer Pipeline erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="df813-111">The parameters required to create a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-113">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="df813-113">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-114">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-114">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-115">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-116">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-116">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-117">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-117">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-119">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="df813-119">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-120">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="df813-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-122">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-122">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df813-123">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="df813-123">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-125">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="df813-125">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-126">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-126">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-127">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-128">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-128">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-129">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-129">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df813-130">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="df813-130">The parameters required to create or update a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-132">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="df813-132">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-133">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-133">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iPipelineOperations.DeleteAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-134">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-135">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-135">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-136">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-136">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-137">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-138">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="df813-138">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-139">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="df813-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;" Usage="iPipelineOperations.GetAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-140">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-141">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-141">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-142">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-142">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-143">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-144">Ruft eine Pipelineinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="df813-144">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-145">Get Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-145">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="iPipelineOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="df813-146">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="df813-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-147">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="df813-148">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-148">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-149">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-150">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-151">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-152">Ruft die erste Seite des Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="df813-152">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-153">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-153">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="iPipelineOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="df813-154">Die Url zur nächsten Seite Pipelines.</span><span class="sxs-lookup"><span data-stu-id="df813-154">The url to the next pipelines page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-155">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-156">Ruft die nächste Seite der Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="df813-156">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-157">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="df813-157">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.ResumeAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-158">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-158">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-159">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-159">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-160">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-160">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-161">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-161">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-162">Fortsetzen einer angehaltenen Pipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-162">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-163">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="df813-163">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriodAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SetActivePeriodAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetActivePeriodAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SetActivePeriodAsync (resourceGroupName, dataFactoryName, dataPipelineName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-164">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-164">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-165">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-165">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-166">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-166">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="df813-167">Der Parameter erforderlich, um den aktiven Zeitraum einer Pipeline festgelegt.</span><span class="sxs-lookup"><span data-stu-id="df813-167">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-168">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-168">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-169">Legt den aktiven Zeitraum einer Pipeline fest.</span><span class="sxs-lookup"><span data-stu-id="df813-169">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-170">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="df813-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string dataFactoryName, string dataPipelineName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string dataFactoryName, string dataPipelineName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iPipelineOperations.SuspendAsync (resourceGroupName, dataFactoryName, dataPipelineName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="df813-171">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="df813-171">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="df813-172">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="df813-172">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="df813-173">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="df813-173">Name of the data pipeline.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="df813-174">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="df813-174">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="df813-175">Anhalten einer Pipeline ausgeführten.</span><span class="sxs-lookup"><span data-stu-id="df813-175">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="df813-176">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="df813-176">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>