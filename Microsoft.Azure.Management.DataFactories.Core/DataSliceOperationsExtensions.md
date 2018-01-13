<Type Name="DataSliceOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSliceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSliceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSliceOperationsExtensions = class" />
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
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceListParameters) As DataSliceListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96787-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-102">Required.</span></span> <span data-ttu-id="96787-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="96787-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="96787-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-104">Required.</span></span> <span data-ttu-id="96787-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="96787-105">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="96787-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-106">Required.</span></span> <span data-ttu-id="96787-107">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="96787-107">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96787-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-108">Required.</span></span> <span data-ttu-id="96787-109">Parameter, die angibt, wie der Datenslices des Datasets aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="96787-109">Parameters specifying how to list data slices of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-110">Ruft die erste Seite des Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="96787-110">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-111">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="96787-111">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceListParameters) As Task(Of DataSliceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-112">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-112">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96787-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-113">Required.</span></span> <span data-ttu-id="96787-114">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="96787-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="96787-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-115">Required.</span></span> <span data-ttu-id="96787-116">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="96787-116">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="96787-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-117">Required.</span></span> <span data-ttu-id="96787-118">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="96787-118">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96787-119">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-119">Required.</span></span> <span data-ttu-id="96787-120">Parameter, die angibt, wie der Datenslices des Datasets aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="96787-120">Parameters specifying how to list data slices of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-121">Ruft die erste Seite des Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="96787-121">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-122">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="96787-122">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataSliceOperations, nextLink As String) As DataSliceListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-123">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-123">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="96787-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-124">Required.</span></span> <span data-ttu-id="96787-125">Die Url der nächsten Datenseite Slices.</span><span class="sxs-lookup"><span data-stu-id="96787-125">The url to the next data slices page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-126">Ruft die nächste Seite der Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="96787-126">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-127">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="96787-127">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataSliceOperations, nextLink As String) As Task(Of DataSliceListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-128">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="96787-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-129">Required.</span></span> <span data-ttu-id="96787-130">Die Url der nächsten Datenseite Slices.</span><span class="sxs-lookup"><span data-stu-id="96787-130">The url to the next data slices page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-131">Ruft die nächste Seite der Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="96787-131">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-132">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="96787-132">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse SetStatus (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse SetStatus(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatus(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetStatus (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceSetStatusParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member SetStatus : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatus (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-133">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-133">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96787-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-134">Required.</span></span> <span data-ttu-id="96787-135">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="96787-135">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="96787-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-136">Required.</span></span> <span data-ttu-id="96787-137">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="96787-137">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="96787-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-138">Required.</span></span> <span data-ttu-id="96787-139">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="96787-139">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96787-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-140">Required.</span></span> <span data-ttu-id="96787-141">Die Parameter erforderlich, um den Status der Datenslices festgelegt.</span><span class="sxs-lookup"><span data-stu-id="96787-141">The parameters required to set status of data slices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-142">Legt den Status der Datenslices über einen Zeitraum für ein bestimmtes Dataset fest.</span><span class="sxs-lookup"><span data-stu-id="96787-142">Sets status of data slices over a time range for a specific dataset.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-143">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="96787-143">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatusAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SetStatusAsync (operations As IDataSliceOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceSetStatusParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SetStatusAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceOperationsExtensions.SetStatusAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="96787-144">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span><span class="sxs-lookup"><span data-stu-id="96787-144">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="96787-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-145">Required.</span></span> <span data-ttu-id="96787-146">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="96787-146">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="96787-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-147">Required.</span></span> <span data-ttu-id="96787-148">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="96787-148">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="96787-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-149">Required.</span></span> <span data-ttu-id="96787-150">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="96787-150">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="96787-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="96787-151">Required.</span></span> <span data-ttu-id="96787-152">Die Parameter erforderlich, um den Status der Datenslices festgelegt.</span><span class="sxs-lookup"><span data-stu-id="96787-152">The parameters required to set status of data slices.</span></span>
            </param>
        <summary>
            <span data-ttu-id="96787-153">Legt den Status der Datenslices über einen Zeitraum für ein bestimmtes Dataset fest.</span><span class="sxs-lookup"><span data-stu-id="96787-153">Sets status of data slices over a time range for a specific dataset.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="96787-154">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="96787-154">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>