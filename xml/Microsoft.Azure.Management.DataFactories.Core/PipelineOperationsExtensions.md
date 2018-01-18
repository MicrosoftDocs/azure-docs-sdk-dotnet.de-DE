<Type Name="PipelineOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class PipelineOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PipelineOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PipelineOperationsExtensions" />
  <TypeSignature Language="F#" Value="type PipelineOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-102">Required.</span></span> <span data-ttu-id="1e4b0-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-104">Required.</span></span> <span data-ttu-id="1e4b0-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-105">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-106">Required.</span></span> <span data-ttu-id="1e4b0-107">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-107">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-108">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-108">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-109">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-109">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-111">Required.</span></span> <span data-ttu-id="1e4b0-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-113">Required.</span></span> <span data-ttu-id="1e4b0-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-114">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-115">Required.</span></span> <span data-ttu-id="1e4b0-116">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-116">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-117">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-117">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-118">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-118">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse BeginCreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContent (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-119">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-120">Required.</span></span> <span data-ttu-id="1e4b0-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-122">Required.</span></span> <span data-ttu-id="1e4b0-123">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-123">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-124">Required.</span></span> <span data-ttu-id="1e4b0-125">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-125">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-126">Required.</span></span> <span data-ttu-id="1e4b0-127">Die Parameter zum Erstellen einer Pipeline erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-127">The parameters required to create a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-128">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-128">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-129">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-129">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; BeginCreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdateWithRawJsonContentAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginCreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-130">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-130">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-131">Required.</span></span> <span data-ttu-id="1e4b0-132">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-132">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-133">Required.</span></span> <span data-ttu-id="1e4b0-134">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-134">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-135">Required.</span></span> <span data-ttu-id="1e4b0-136">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-136">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-137">Required.</span></span> <span data-ttu-id="1e4b0-138">Die Parameter zum Erstellen einer Pipeline erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-138">The parameters required to create a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-139">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-139">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-140">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-140">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse BeginDelete(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDelete(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDelete (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-141">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-141">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-142">Required.</span></span> <span data-ttu-id="1e4b0-143">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-143">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-144">Required.</span></span> <span data-ttu-id="1e4b0-145">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-145">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-146">Required.</span></span> <span data-ttu-id="1e4b0-147">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-147">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-148">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-148">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-149">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-149">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeleteAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-150">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-150">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-151">Required.</span></span> <span data-ttu-id="1e4b0-152">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-152">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-153">Required.</span></span> <span data-ttu-id="1e4b0-154">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-154">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-155">Required.</span></span> <span data-ttu-id="1e4b0-156">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-156">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-157">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-157">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-158">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-159">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-160">Required.</span></span> <span data-ttu-id="1e4b0-161">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-161">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-162">Required.</span></span> <span data-ttu-id="1e4b0-163">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-163">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-164">Required.</span></span> <span data-ttu-id="1e4b0-165">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-165">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-166">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-166">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-167">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-167">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, parameters As PipelineCreateOrUpdateParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, dataFactoryName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-168">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-168">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-169">Required.</span></span> <span data-ttu-id="1e4b0-170">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-170">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-171">Required.</span></span> <span data-ttu-id="1e4b0-172">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-172">A unique data factory instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-173">Required.</span></span> <span data-ttu-id="1e4b0-174">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-174">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-175">Erstellen oder Aktualisieren einer Pipeline-Instanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-175">Create or update a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-176">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-176">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse CreateOrUpdateWithRawJsonContent(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContent(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContent (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContent : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContent (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-177">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-177">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-178">Required.</span></span> <span data-ttu-id="1e4b0-179">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-179">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-180">Required.</span></span> <span data-ttu-id="1e4b0-181">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-181">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-182">Required.</span></span> <span data-ttu-id="1e4b0-183">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-183">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-184">Required.</span></span> <span data-ttu-id="1e4b0-185">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-185">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-186">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-186">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-187">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-187">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithRawJsonContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; CreateOrUpdateWithRawJsonContentAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithRawJsonContentAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineCreateOrUpdateWithRawJsonContentParameters) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithRawJsonContentAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.CreateOrUpdateWithRawJsonContentAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateWithRawJsonContentParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-188">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-188">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-189">Required.</span></span> <span data-ttu-id="1e4b0-190">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-190">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-191">Required.</span></span> <span data-ttu-id="1e4b0-192">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-192">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-193">Required.</span></span> <span data-ttu-id="1e4b0-194">Eine eindeutige Pipeline-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-194">A unique pipeline instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-195">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-195">Required.</span></span> <span data-ttu-id="1e4b0-196">Die Parameter zum Erstellen oder Aktualisieren einer Pipeline erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-196">The parameters required to create or update a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-197">Erstellen Sie eine neue Pipelineinstanz mit unformatierten Json-Inhalt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-197">Create a new pipeline instance with raw json content.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-198">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-198">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse Delete(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Delete(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As LongRunningOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Delete (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-199">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-199">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-200">Required.</span></span> <span data-ttu-id="1e4b0-201">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-201">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-202">Required.</span></span> <span data-ttu-id="1e4b0-203">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-203">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-204">Required.</span></span> <span data-ttu-id="1e4b0-205">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-205">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-206">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-206">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-207">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-207">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of LongRunningOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.DeleteAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Common.Models.LongRunningOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-208">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-208">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-209">Required.</span></span> <span data-ttu-id="1e4b0-210">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-210">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-211">Required.</span></span> <span data-ttu-id="1e4b0-212">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-212">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-213">Required.</span></span> <span data-ttu-id="1e4b0-214">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-214">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-215">Löschen einer Pipelineinstanz.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-215">Delete a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-216">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-216">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As PipelineGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-217">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-217">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-218">Required.</span></span> <span data-ttu-id="1e4b0-219">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-219">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-220">Required.</span></span> <span data-ttu-id="1e4b0-221">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-221">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-222">Required.</span></span> <span data-ttu-id="1e4b0-223">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-223">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-224">Ruft eine Pipelineinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-224">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-225">Get Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-225">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of PipelineGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-226">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-226">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-227">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-227">Required.</span></span> <span data-ttu-id="1e4b0-228">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-228">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-229">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-229">Required.</span></span> <span data-ttu-id="1e4b0-230">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-230">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-231">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-231">Required.</span></span> <span data-ttu-id="1e4b0-232">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-232">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-233">Ruft eine Pipelineinstanz ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-233">Gets a pipeline instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-234">Get Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-234">The Get pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse GetCreateOrUpdateStatus (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse GetCreateOrUpdateStatus(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatus(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatus (operations As IPipelineOperations, operationStatusLink As String) As PipelineCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatus : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatus (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-235">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-235">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="1e4b0-236">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-236">Required.</span></span> <span data-ttu-id="1e4b0-237">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-237">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="1e4b0-238">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-238">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCreateOrUpdateStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt; GetCreateOrUpdateStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string operationStatusLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetCreateOrUpdateStatusAsync (operations As IPipelineOperations, operationStatusLink As String) As Task(Of PipelineCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member GetCreateOrUpdateStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.GetCreateOrUpdateStatusAsync (operations, operationStatusLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="operationStatusLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-239">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-239">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="operationStatusLink">
            <span data-ttu-id="1e4b0-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-240">Required.</span></span> <span data-ttu-id="1e4b0-241">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-241">Location value returned by the Begin operation.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="1e4b0-242">Erstellen oder aktualisieren Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-242">The create or update pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String) As PipelineListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.List (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-243">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-243">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-244">Required.</span></span> <span data-ttu-id="1e4b0-245">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-245">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-246">Required.</span></span> <span data-ttu-id="1e4b0-247">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-247">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-248">Ruft die erste Seite des Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-248">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-249">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-249">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String) As Task(Of PipelineListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-250">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-250">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-251">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-251">Required.</span></span> <span data-ttu-id="1e4b0-252">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-252">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-253">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-253">Required.</span></span> <span data-ttu-id="1e4b0-254">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-254">A unique data factory instance name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-255">Ruft die erste Seite des Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-255">Gets the first page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-256">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-256">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IPipelineOperations, nextLink As String) As PipelineListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-257">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-257">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1e4b0-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-258">Required.</span></span> <span data-ttu-id="1e4b0-259">Die Url zur nächsten Seite Pipelines.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-259">The url to the next pipelines page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-260">Ruft die nächste Seite der Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-260">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-261">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-261">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IPipelineOperations, nextLink As String) As Task(Of PipelineListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Core.Models.PipelineListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-262">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-262">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="1e4b0-263">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-263">Required.</span></span> <span data-ttu-id="1e4b0-264">Die Url zur nächsten Seite Pipelines.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-264">The url to the next pipelines page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-265">Ruft die nächste Seite der Pipelineinstanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-265">Gets the next page of pipeline instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-266">Liste Pipeline Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-266">The List pipeline operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Resume(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Resume (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-267">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-267">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-268">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-268">Required.</span></span> <span data-ttu-id="1e4b0-269">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-269">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-270">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-270">Required.</span></span> <span data-ttu-id="1e4b0-271">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-271">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-272">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-272">Required.</span></span> <span data-ttu-id="1e4b0-273">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-273">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-274">Fortsetzen einer angehaltenen Pipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-274">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-275">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-275">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.ResumeAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-276">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-276">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-277">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-277">Required.</span></span> <span data-ttu-id="1e4b0-278">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-278">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-279">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-279">Required.</span></span> <span data-ttu-id="1e4b0-280">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-280">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-281">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-281">Required.</span></span> <span data-ttu-id="1e4b0-282">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-282">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-283">Fortsetzen einer angehaltenen Pipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-283">Resume a suspended pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-284">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-284">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriod">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse SetActivePeriod (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse SetActivePeriod(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriod(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetActivePeriod (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineSetActivePeriodParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member SetActivePeriod : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriod (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-285">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-285">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-286">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-286">Required.</span></span> <span data-ttu-id="1e4b0-287">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-287">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-288">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-288">Required.</span></span> <span data-ttu-id="1e4b0-289">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-289">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-290">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-290">Required.</span></span> <span data-ttu-id="1e4b0-291">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-291">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-292">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-292">Required.</span></span> <span data-ttu-id="1e4b0-293">Der Parameter erforderlich, um den aktiven Zeitraum einer Pipeline festgelegt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-293">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-294">Legt den aktiven Zeitraum einer Pipeline fest.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-294">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-295">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-295">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetActivePeriodAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetActivePeriodAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName, class Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriodAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetActivePeriodAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String, parameters As PipelineSetActivePeriodParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SetActivePeriodAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SetActivePeriodAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Common.Models.PipelineSetActivePeriodParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-296">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-296">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-297">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-297">Required.</span></span> <span data-ttu-id="1e4b0-298">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-298">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-299">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-299">Required.</span></span> <span data-ttu-id="1e4b0-300">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-300">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-301">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-301">Required.</span></span> <span data-ttu-id="1e4b0-302">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-302">Name of the data pipeline.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="1e4b0-303">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-303">Required.</span></span> <span data-ttu-id="1e4b0-304">Der Parameter erforderlich, um den aktiven Zeitraum einer Pipeline festgelegt.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-304">Parameters required to set the active period of a pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-305">Legt den aktiven Zeitraum einer Pipeline fest.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-305">Sets the active period of a pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-306">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-306">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Suspend(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.Suspend (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-307">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-307">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-308">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-308">Required.</span></span> <span data-ttu-id="1e4b0-309">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-309">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-310">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-310">Required.</span></span> <span data-ttu-id="1e4b0-311">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-311">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-312">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-312">Required.</span></span> <span data-ttu-id="1e4b0-313">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-313">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-314">Anhalten einer Pipeline ausgeführten.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-314">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-315">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-315">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations operations, string resourceGroupName, string dataFactoryName, string dataPipelineName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As IPipelineOperations, resourceGroupName As String, dataFactoryName As String, dataPipelineName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.PipelineOperationsExtensions.SuspendAsync (operations, resourceGroupName, dataFactoryName, dataPipelineName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataPipelineName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="1e4b0-316">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-316">Reference to the Microsoft.Azure.Management.DataFactories.Core.IPipelineOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="1e4b0-317">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-317">Required.</span></span> <span data-ttu-id="1e4b0-318">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-318">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="1e4b0-319">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-319">Required.</span></span> <span data-ttu-id="1e4b0-320">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-320">A unique data factory instance name.</span></span>
            </param>
        <param name="dataPipelineName">
            <span data-ttu-id="1e4b0-321">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-321">Required.</span></span> <span data-ttu-id="1e4b0-322">Der Name der Datenpipeline.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-322">Name of the data pipeline.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1e4b0-323">Anhalten einer Pipeline ausgeführten.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-323">Suspend a running pipeline.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1e4b0-324">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="1e4b0-324">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>