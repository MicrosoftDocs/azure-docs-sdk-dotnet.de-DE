<Type Name="DatasetOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DatasetOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DatasetOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-102">Required.</span></span> <span data-ttu-id="d08c5-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-104">Required.</span></span> <span data-ttu-id="d08c5-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-106">Required.</span></span> <span data-ttu-id="d08c5-107">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-107">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-108">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-108">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-109">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-109">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-111">Required.</span></span> <span data-ttu-id="d08c5-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-113">Required.</span></span> <span data-ttu-id="d08c5-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-115">Required.</span></span> <span data-ttu-id="d08c5-116">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-116">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-117">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-117">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-118">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-118">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-119">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-120">Required.</span></span> <span data-ttu-id="d08c5-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-122">Required.</span></span> <span data-ttu-id="d08c5-123">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-123">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-124">Required.</span></span> <span data-ttu-id="d08c5-125">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d08c5-125">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-126">Required.</span></span> <span data-ttu-id="d08c5-127">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-127">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-128">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d08c5-128">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-129">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-129">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-130">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-130">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-131">Required.</span></span> <span data-ttu-id="d08c5-132">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-133">Required.</span></span> <span data-ttu-id="d08c5-134">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-134">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-135">Required.</span></span> <span data-ttu-id="d08c5-136">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d08c5-136">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-137">Required.</span></span> <span data-ttu-id="d08c5-138">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-138">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-139">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d08c5-139">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-140">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-140">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-141">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-142">Required.</span></span> <span data-ttu-id="d08c5-143">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-144">Required.</span></span> <span data-ttu-id="d08c5-145">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-145">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-146">Required.</span></span> <span data-ttu-id="d08c5-147">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-147">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-148">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-148">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-149">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d08c5-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-150">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-151">Required.</span></span> <span data-ttu-id="d08c5-152">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-153">Required.</span></span> <span data-ttu-id="d08c5-154">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-154">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-155">Required.</span></span> <span data-ttu-id="d08c5-156">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-156">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-157">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-157">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-158">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d08c5-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-159">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-160">Required.</span></span> <span data-ttu-id="d08c5-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-162">Required.</span></span> <span data-ttu-id="d08c5-163">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-164">Required.</span></span> <span data-ttu-id="d08c5-165">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-165">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-166">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-166">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-167">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-167">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-168">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-169">Required.</span></span> <span data-ttu-id="d08c5-170">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-171">Required.</span></span> <span data-ttu-id="d08c5-172">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-173">Required.</span></span> <span data-ttu-id="d08c5-174">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-174">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-175">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-175">Create a new dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-176">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-176">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-177">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-178">Required.</span></span> <span data-ttu-id="d08c5-179">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-180">Required.</span></span> <span data-ttu-id="d08c5-181">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-181">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-182">Required.</span></span> <span data-ttu-id="d08c5-183">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d08c5-183">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-184">Required.</span></span> <span data-ttu-id="d08c5-185">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-185">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-186">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d08c5-186">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-187">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-187">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-188">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-188">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-189">Required.</span></span> <span data-ttu-id="d08c5-190">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-191">Required.</span></span> <span data-ttu-id="d08c5-192">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-192">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-193">Required.</span></span> <span data-ttu-id="d08c5-194">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d08c5-194">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d08c5-195">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-195">Required.</span></span> <span data-ttu-id="d08c5-196">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-196">The parameters required to create or update a dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-197">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d08c5-197">Create a new dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-198">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-198">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-199">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-199">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-200">Required.</span></span> <span data-ttu-id="d08c5-201">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-202">Required.</span></span> <span data-ttu-id="d08c5-203">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-203">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-204">Required.</span></span> <span data-ttu-id="d08c5-205">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-205">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-206">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-206">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-207">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d08c5-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-208">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-208">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-209">Required.</span></span> <span data-ttu-id="d08c5-210">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-211">Required.</span></span> <span data-ttu-id="d08c5-212">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-212">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-213">Required.</span></span> <span data-ttu-id="d08c5-214">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-214">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-215">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d08c5-215">Delete a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-216">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d08c5-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As DatasetGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-217">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-218">Required.</span></span> <span data-ttu-id="d08c5-219">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-220">Required.</span></span> <span data-ttu-id="d08c5-221">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-221">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-222">Required.</span></span> <span data-ttu-id="d08c5-223">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-223">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-224">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="d08c5-224">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-225">Get Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-225">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of DatasetGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-226">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-227">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-227">Required.</span></span> <span data-ttu-id="d08c5-228">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-229">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-229">Required.</span></span> <span data-ttu-id="d08c5-230">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-230">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d08c5-231">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-231">Required.</span></span> <span data-ttu-id="d08c5-232">Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-232">Name of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-233">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="d08c5-233">Gets a dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-234">Get Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-234">The Get dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDatasetOperations, operationStatusLink As String) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-235">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="d08c5-236">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-236">Required.</span></span> <span data-ttu-id="d08c5-237">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="d08c5-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d08c5-238">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-238">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDatasetOperations, operationStatusLink As String) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-239">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-239">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="d08c5-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-240">Required.</span></span> <span data-ttu-id="d08c5-241">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="d08c5-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d08c5-242">CreateOrUpdate Dataset Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-242">The CreateOrUpdate dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-243">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-244">Required.</span></span> <span data-ttu-id="d08c5-245">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-246">Required.</span></span> <span data-ttu-id="d08c5-247">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-248">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="d08c5-248">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-249">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-249">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-250">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-250">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d08c5-251">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-251">Required.</span></span> <span data-ttu-id="d08c5-252">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d08c5-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d08c5-253">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-253">Required.</span></span> <span data-ttu-id="d08c5-254">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d08c5-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-255">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="d08c5-255">Gets all the dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-256">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-256">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDatasetOperations, nextLink As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-257">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d08c5-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-258">Required.</span></span> <span data-ttu-id="d08c5-259">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-259">The url to the next datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-260">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d08c5-260">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-261">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-261">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDatasetOperations, nextLink As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DatasetOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d08c5-262">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d08c5-262">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d08c5-263">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d08c5-263">Required.</span></span> <span data-ttu-id="d08c5-264">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d08c5-264">The url to the next datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d08c5-265">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d08c5-265">Gets the next page of dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d08c5-266">Liste Datasets Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="d08c5-266">The List datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>