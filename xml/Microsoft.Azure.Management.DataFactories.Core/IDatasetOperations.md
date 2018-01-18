<Type Name="IDatasetOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations">
  <TypeSignature Language="C#" Value="public interface IDatasetOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatasetOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatasetOperations" />
  <TypeSignature Language="F#" Value="type IDatasetOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20121-101">Vorgänge zum Verwalten von Datasets.</span><span class="sxs-lookup"><span data-stu-id="20121-101">Operations for managing datasets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="20121-104">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="20121-104">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-106">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="20121-106">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-107">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-107">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-109">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-109">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="20121-110">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="20121-110">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="20121-111">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="20121-111">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-113">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="20121-113">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-114">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-114">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iDatasetOperations.BeginDeleteAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
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
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-115">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-116">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-116">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="20121-117">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="20121-117">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-119">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="20121-119">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-120">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="20121-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-122">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-122">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="20121-123">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="20121-123">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-125">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="20121-125">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-126">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-126">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-127">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-128">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-128">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="20121-129">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="20121-129">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="20121-130">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="20121-130">The parameters required to create or update a dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-132">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="20121-132">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-133">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-133">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="iDatasetOperations.DeleteAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
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
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-134">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-135">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-135">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="20121-136">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="20121-136">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-137">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-138">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="20121-138">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-139">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="20121-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;" Usage="iDatasetOperations.GetAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-140">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-141">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-141">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="20121-142">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="20121-142">Name of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-143">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-144">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="20121-144">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-145">Get Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-145">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="20121-146">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="20121-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-147">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="20121-148">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-148">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="20121-149">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="20121-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="20121-150">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="20121-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-151">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-152">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="20121-152">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-153">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-153">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="20121-154">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="20121-154">The url to the next datasets page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="20121-155">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="20121-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="20121-156">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="20121-156">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="20121-157">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="20121-157">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>