<Type Name="DatasetOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DatasetOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DatasetOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-101">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-101">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-102">Required.</span></span> <span data-ttu-id="d768d-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-104">Required.</span></span> <span data-ttu-id="d768d-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-106">Required.</span></span> <span data-ttu-id="d768d-107">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-107">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-108">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-108">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-109">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-109">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-110">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-110">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-111">Required.</span></span> <span data-ttu-id="d768d-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-113">Required.</span></span> <span data-ttu-id="d768d-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-115">Required.</span></span> <span data-ttu-id="d768d-116">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-116">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-117">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-117">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-118">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-118">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-119">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-119">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-120">Required.</span></span> <span data-ttu-id="d768d-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-122">Required.</span></span> <span data-ttu-id="d768d-123">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-123">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-124">Required.</span></span> <span data-ttu-id="d768d-125">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-125">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-126">Required.</span></span> <span data-ttu-id="d768d-127">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-127">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-128">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten JSON-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d768d-128">Create a new Dataset instance or update an existing instance with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-129">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-129">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-130">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-130">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-131">Required.</span></span> <span data-ttu-id="d768d-132">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-133">Required.</span></span> <span data-ttu-id="d768d-134">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-134">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-135">Required.</span></span> <span data-ttu-id="d768d-136">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-136">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-137">Required.</span></span> <span data-ttu-id="d768d-138">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-138">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-139">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten JSON-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d768d-139">Create a new Dataset instance or update an existing instance with raw JSON content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-140">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-140">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-141">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-141">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-142">Required.</span></span> <span data-ttu-id="d768d-143">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-144">Required.</span></span> <span data-ttu-id="d768d-145">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-145">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-146">Required.</span></span> <span data-ttu-id="d768d-147">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-147">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-148">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-148">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-149">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d768d-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-150">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-150">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-151">Required.</span></span> <span data-ttu-id="d768d-152">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-153">Required.</span></span> <span data-ttu-id="d768d-154">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-154">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-155">Required.</span></span> <span data-ttu-id="d768d-156">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-156">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-157">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-157">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-158">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d768d-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-159">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-159">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-160">Required.</span></span> <span data-ttu-id="d768d-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-162">Required.</span></span> <span data-ttu-id="d768d-163">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-164">Required.</span></span> <span data-ttu-id="d768d-165">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-165">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-166">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-166">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-167">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-167">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, parameters As DatasetCreateOrUpdateParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-168">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-168">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-169">Required.</span></span> <span data-ttu-id="d768d-170">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-171">Required.</span></span> <span data-ttu-id="d768d-172">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-173">Required.</span></span> <span data-ttu-id="d768d-174">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-174">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-175">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-175">Create a new Dataset instance or update an existing instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-176">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-176">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-177">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-177">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-178">Required.</span></span> <span data-ttu-id="d768d-179">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-180">Required.</span></span> <span data-ttu-id="d768d-181">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-181">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-182">Required.</span></span> <span data-ttu-id="d768d-183">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-183">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-184">Required.</span></span> <span data-ttu-id="d768d-185">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-185">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-186">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d768d-186">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-187">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-187">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DatasetCreateOrUpdateWithRawJsonContentParameters) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-188">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-188">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-189">Required.</span></span> <span data-ttu-id="d768d-190">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-191">Required.</span></span> <span data-ttu-id="d768d-192">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-192">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-193">Required.</span></span> <span data-ttu-id="d768d-194">Ein eindeutiger Name der Dataset-Instanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-194">A unique Dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d768d-195">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-195">Required.</span></span> <span data-ttu-id="d768d-196">Die Parameter zum Erstellen oder Aktualisieren eines Datasets erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-196">The parameters required to create or update a Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-197">Erstellen einer neuen Datasetinstanz, oder Aktualisieren einer vorhandenen Instanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="d768d-197">Create a new Dataset instance or update an existing instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-198">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-198">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-199">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-199">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-200">Required.</span></span> <span data-ttu-id="d768d-201">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-202">Required.</span></span> <span data-ttu-id="d768d-203">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-203">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-204">Required.</span></span> <span data-ttu-id="d768d-205">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-205">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-206">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-206">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-207">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d768d-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-208">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-208">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-209">Required.</span></span> <span data-ttu-id="d768d-210">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-211">Required.</span></span> <span data-ttu-id="d768d-212">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-212">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-213">Required.</span></span> <span data-ttu-id="d768d-214">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-214">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-215">Löschen Sie eine Datasetinstanz.</span><span class="sxs-lookup"><span data-stu-id="d768d-215">Delete a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-216">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="d768d-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse Get (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse Get(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As DatasetGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-217">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-217">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-218">Required.</span></span> <span data-ttu-id="d768d-219">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-220">Required.</span></span> <span data-ttu-id="d768d-221">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-221">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-222">Required.</span></span> <span data-ttu-id="d768d-223">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-223">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-224">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="d768d-224">Gets a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-225">Vorgangsantwort Dataset abrufen.</span><span class="sxs-lookup"><span data-stu-id="d768d-225">The Get Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName, string datasetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String) As Task(Of DatasetGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, datasetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-226">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-226">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-227">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-227">Required.</span></span> <span data-ttu-id="d768d-228">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-229">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-229">Required.</span></span> <span data-ttu-id="d768d-230">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-230">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d768d-231">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-231">Required.</span></span> <span data-ttu-id="d768d-232">Der Name des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-232">Name of the Dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-233">Ruft eine Datasetinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="d768d-233">Gets a Dataset instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-234">Vorgangsantwort Dataset abrufen.</span><span class="sxs-lookup"><span data-stu-id="d768d-234">The Get Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IDatasetOperations, operationStatusLink As String) As DatasetCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-235">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-235">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="d768d-236">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-236">Required.</span></span> <span data-ttu-id="d768d-237">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="d768d-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d768d-238">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-238">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IDatasetOperations, operationStatusLink As String) As Task(Of DatasetCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-239">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-239">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="d768d-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-240">Required.</span></span> <span data-ttu-id="d768d-241">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="d768d-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d768d-242">Vorgangsantwort CreateOrUpdate Dataset.</span><span class="sxs-lookup"><span data-stu-id="d768d-242">The CreateOrUpdate Dataset operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse List (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse List(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-243">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-243">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-244">Required.</span></span> <span data-ttu-id="d768d-245">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-246">Required.</span></span> <span data-ttu-id="d768d-247">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-248">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="d768d-248">Gets all the Dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-249">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="d768d-249">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDatasetOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-250">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-250">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="d768d-251">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-251">Required.</span></span> <span data-ttu-id="d768d-252">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d768d-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d768d-253">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-253">Required.</span></span> <span data-ttu-id="d768d-254">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d768d-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-255">Ruft die Dataset-Instanzen in einer Data Factory mit dem Link zur nächsten Seite.</span><span class="sxs-lookup"><span data-stu-id="d768d-255">Gets all the Dataset instances in a data factory with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-256">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="d768d-256">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse ListNext (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse ListNext(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDatasetOperations, nextLink As String) As DatasetListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-257">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-257">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d768d-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-258">Required.</span></span> <span data-ttu-id="d768d-259">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-259">The url to the next Datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-260">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d768d-260">Gets the next page of Dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-261">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="d768d-261">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.IDatasetOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.IDatasetOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDatasetOperations, nextLink As String) As Task(Of DatasetListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.IDatasetOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.DatasetOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DatasetListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.IDatasetOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="d768d-262">Verweis auf die Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span><span class="sxs-lookup"><span data-stu-id="d768d-262">Reference to the Microsoft.Azure.Management.DataFactories.IDatasetOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="d768d-263">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="d768d-263">Required.</span></span> <span data-ttu-id="d768d-264">Die Url mit der nächsten Seite des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d768d-264">The url to the next Datasets page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d768d-265">Ruft die nächste Seite der Dataset-Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d768d-265">Gets the next page of Dataset instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d768d-266">Die Liste Datasets Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="d768d-266">The List Datasets operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>