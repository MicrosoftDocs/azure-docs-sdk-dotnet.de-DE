<Type Name="IDatasetOperations" FullName="Microsoft.Azure.Management.DataFactories.IDatasetOperations">
  <TypeSignature Language="C#" Value="public interface IDatasetOperations : Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDatasetOperations implements class Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Dataset&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDatasetOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDatasetOperations&#xA;Implements ITypeRegistrationOperations(Of Dataset)" />
  <TypeSignature Language="F#" Value="type IDatasetOperations = interface&#xA;    interface ITypeRegistrationOperations&lt;Dataset&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataFactories.Conversion.ITypeRegistrationOperations&lt;Microsoft.Azure.Management.DataFactories.Models.Dataset&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="15937-101">Vorgänge zum Verwalten von Datasets.</span><span class="sxs-lookup"><span data-stu-id="15937-101">Operations for managing Datasets.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.BeginCreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-103">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15937-104">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="15937-104">The parameters required to create or update a Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-106">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="15937-106">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-107">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="15937-107">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.BeginCreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-109">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-109">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="15937-110">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="15937-110">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15937-111">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="15937-111">The parameters required to create or update a Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-113">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="15937-113">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-114">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="15937-114">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.BeginDeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="15937-115">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-115">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-116">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-116">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="15937-117">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="15937-117">Name of the Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-119">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="15937-119">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-120">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="15937-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateAsync (resourceGroupName, dataFactoryName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-122">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-122">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15937-123">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="15937-123">The parameters required to create or update a Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-125">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="15937-125">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-126">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="15937-126">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.CreateOrUpdateWithRawJsonContentAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithRawJsonContentAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.CreateOrUpdateWithRawJsonContentAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-127">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-127">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-128">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-128">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="15937-129">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="15937-129">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="15937-130">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="15937-130">The parameters required to create or update a Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-132">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="15937-132">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-133">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="15937-133">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="15937-134">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-134">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-135">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-135">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="15937-136">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="15937-136">Name of the Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-137">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-137">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-138">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="15937-138">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-139">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="15937-139">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string datasetName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string datasetName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;" Usage="iDatasetOperations.GetAsync (resourceGroupName, dataFactoryName, datasetName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-140">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-140">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-141">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-141">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="15937-142">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="15937-142">Name of the Dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-143">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-143">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-144">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="15937-144">Gets a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-145">Vorgangsantwort Dataset abrufen.</span><span class="sxs-lookup"><span data-stu-id="15937-145">The Get Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.GetCreateOrUpdateStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCreateOrUpdateStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="iDatasetOperations.GetCreateOrUpdateStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="15937-146">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="15937-146">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-147">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-147">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="15937-148">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="15937-148">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListAsync (resourceGroupName, dataFactoryName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="15937-149">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="15937-149">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="15937-150">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="15937-150">A unique data factory instance name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-151">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-151">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-152">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="15937-152">Gets all the Dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-153">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="15937-153">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDatasetOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="iDatasetOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="15937-154">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="15937-154">The url to the next Datasets page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="15937-155">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="15937-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="15937-156">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="15937-156">Gets the next page of Dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="15937-157">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="15937-157">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>