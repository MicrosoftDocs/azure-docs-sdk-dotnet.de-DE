<Type Name="DataSliceRunOperationsExtensions" FullName="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DataSliceRunOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DataSliceRunOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DataSliceRunOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DataSliceRunOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse Get (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse Get(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.Get(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, runId As String) As DataSliceRunGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.Get (operations, resourceGroupName, dataFactoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-101">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-101">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-102">Required.</span></span> <span data-ttu-id="5e50e-103">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-103">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-104">Required.</span></span> <span data-ttu-id="5e50e-105">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-105">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="5e50e-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-106">Required.</span></span> <span data-ttu-id="5e50e-107">Eine eindeutige Ausführung Slice-Id.</span><span class="sxs-lookup"><span data-stu-id="5e50e-107">A unique Data Slice Run Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-108">Ruft eine Instanz Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5e50e-108">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-109">Die Get-Vorgangsantwort Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5e50e-109">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string runId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, runId As String) As Task(Of DataSliceRunGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetAsync (operations, resourceGroupName, dataFactoryName, runId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-110">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-110">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-111">Required.</span></span> <span data-ttu-id="5e50e-112">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-112">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-113">Required.</span></span> <span data-ttu-id="5e50e-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-114">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="5e50e-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-115">Required.</span></span> <span data-ttu-id="5e50e-116">Eine eindeutige Ausführung Slice-Id.</span><span class="sxs-lookup"><span data-stu-id="5e50e-116">A unique Data Slice Run Id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-117">Ruft eine Instanz Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5e50e-117">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-118">Die Get-Vorgangsantwort Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="5e50e-118">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogs">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse GetLogs (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse GetLogs(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogs(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLogs (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, dataSliceRunId As String) As DataSliceRunGetLogsResponse" />
      <MemberSignature Language="F#" Value="static member GetLogs : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogs (operations, resourceGroupName, dataFactoryName, dataSliceRunId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-119">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-119">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-120">Required.</span></span> <span data-ttu-id="5e50e-121">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-121">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-122">Required.</span></span> <span data-ttu-id="5e50e-123">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-123">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="5e50e-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-124">Required.</span></span> <span data-ttu-id="5e50e-125">Führen Sie ein eindeutigen Datenslice Instanz-Id aus.</span><span class="sxs-lookup"><span data-stu-id="5e50e-125">A unique data slice run instance id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-126">Ruft die Protokolle für einen Datenslice ausführen ab</span><span class="sxs-lookup"><span data-stu-id="5e50e-126">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-127">Der Datenslice Protokolle-Get-Antwort-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5e50e-127">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string dataSliceRunId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogsAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetLogsAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, dataSliceRunId As String) As Task(Of DataSliceRunGetLogsResponse)" />
      <MemberSignature Language="F#" Value="static member GetLogsAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.GetLogsAsync (operations, resourceGroupName, dataFactoryName, dataSliceRunId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-128">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-128">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-129">Required.</span></span> <span data-ttu-id="5e50e-130">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-130">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-131">Required.</span></span> <span data-ttu-id="5e50e-132">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-132">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="5e50e-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-133">Required.</span></span> <span data-ttu-id="5e50e-134">Führen Sie ein eindeutigen Datenslice Instanz-Id aus.</span><span class="sxs-lookup"><span data-stu-id="5e50e-134">A unique data slice run instance id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-135">Ruft die Protokolle für einen Datenslice ausführen ab</span><span class="sxs-lookup"><span data-stu-id="5e50e-135">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-136">Der Datenslice Protokolle-Get-Antwort-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="5e50e-136">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse List (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse List(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.List(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceRunListParameters) As DataSliceRunListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.List (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-137">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-137">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-138">Required.</span></span> <span data-ttu-id="5e50e-139">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-139">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-140">Required.</span></span> <span data-ttu-id="5e50e-141">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-141">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="5e50e-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-142">Required.</span></span> <span data-ttu-id="5e50e-143">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="5e50e-143">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5e50e-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-144">Required.</span></span> <span data-ttu-id="5e50e-145">Parameter zum Angeben der Filter, um die Liste der Datenslice führt des Datasets.</span><span class="sxs-lookup"><span data-stu-id="5e50e-145">Parameters for specifying the filters to list data slice runs of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-146">Ruft die erste Seite des Datenslice Ausführen von Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="5e50e-146">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-147">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="5e50e-147">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDataSliceRunOperations, resourceGroupName As String, dataFactoryName As String, datasetName As String, parameters As DataSliceRunListParameters) As Task(Of DataSliceRunListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListAsync (operations, resourceGroupName, dataFactoryName, datasetName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-148">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-148">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5e50e-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-149">Required.</span></span> <span data-ttu-id="5e50e-150">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="5e50e-150">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="5e50e-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-151">Required.</span></span> <span data-ttu-id="5e50e-152">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="5e50e-152">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="5e50e-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-153">Required.</span></span> <span data-ttu-id="5e50e-154">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="5e50e-154">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5e50e-155">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-155">Required.</span></span> <span data-ttu-id="5e50e-156">Parameter zum Angeben der Filter, um die Liste der Datenslice führt des Datasets.</span><span class="sxs-lookup"><span data-stu-id="5e50e-156">Parameters for specifying the filters to list data slice runs of the dataset.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-157">Ruft die erste Seite des Datenslice Ausführen von Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="5e50e-157">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-158">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="5e50e-158">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse ListNext (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse ListNext(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNext(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDataSliceRunOperations, nextLink As String) As DataSliceRunListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string -&gt; Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-159">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-159">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5e50e-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-160">Required.</span></span> <span data-ttu-id="5e50e-161">Die Url zu den nächsten Datenslice wird die Seite ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5e50e-161">The url to the next data slice runs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-162">Ruft die nächste Seite der ausgeführten Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="5e50e-162">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-163">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="5e50e-163">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDataSliceRunOperations, nextLink As String) As Task(Of DataSliceRunListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="Microsoft.Azure.Management.DataFactories.Core.DataSliceRunOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5e50e-164">Verweis auf die Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span><span class="sxs-lookup"><span data-stu-id="5e50e-164">Reference to the Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5e50e-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5e50e-165">Required.</span></span> <span data-ttu-id="5e50e-166">Die Url zu den nächsten Datenslice wird die Seite ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="5e50e-166">The url to the next data slice runs page.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5e50e-167">Ruft die nächste Seite der ausgeführten Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="5e50e-167">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5e50e-168">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="5e50e-168">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>