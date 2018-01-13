<Type Name="IDataSliceRunOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceRunOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceRunOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceRunOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceRunOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d202f-101">Vorgänge zum Verwalten von Daten Slice ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="d202f-101">Operations for managing data slice runs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string runId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string runId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;" Usage="iDataSliceRunOperations.GetAsync (resourceGroupName, dataFactoryName, runId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d202f-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d202f-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d202f-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d202f-103">A unique data factory instance name.</span></span>
            </param>
        <param name="runId">
            <span data-ttu-id="d202f-104">Eine eindeutige Ausführung Slice-Id.</span><span class="sxs-lookup"><span data-stu-id="d202f-104">A unique Data Slice Run Id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d202f-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d202f-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d202f-106">Ruft eine Instanz Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="d202f-106">Gets a Data Slice Run instance.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d202f-107">Die Get-Vorgangsantwort Daten Slice ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="d202f-107">The get Data Slice Run operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetLogsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync (string resourceGroupName, string dataFactoryName, string dataSliceRunId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt; GetLogsAsync(string resourceGroupName, string dataFactoryName, string dataSliceRunId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.GetLogsAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetLogsAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;" Usage="iDataSliceRunOperations.GetLogsAsync (resourceGroupName, dataFactoryName, dataSliceRunId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunGetLogsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="dataSliceRunId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d202f-108">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d202f-108">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d202f-109">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d202f-109">A unique data factory instance name.</span></span>
            </param>
        <param name="dataSliceRunId">
            <span data-ttu-id="d202f-110">Führen Sie ein eindeutigen Datenslice Instanz-Id aus.</span><span class="sxs-lookup"><span data-stu-id="d202f-110">A unique data slice run instance id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d202f-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d202f-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d202f-112">Ruft die Protokolle für einen Datenslice ausführen ab</span><span class="sxs-lookup"><span data-stu-id="d202f-112">Gets logs for a data slice run</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d202f-113">Der Datenslice Protokolle-Get-Antwort-Vorgang ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="d202f-113">The data slice run get logs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d202f-114">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d202f-114">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d202f-115">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d202f-115">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d202f-116">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d202f-116">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d202f-117">Parameter zum Angeben der Filter, um die Liste der Datenslice führt des Datasets.</span><span class="sxs-lookup"><span data-stu-id="d202f-117">Parameters for specifying the filters to list data slice runs of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d202f-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d202f-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d202f-119">Ruft die erste Seite des Datenslice Ausführen von Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d202f-119">Gets the first page of data slice run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d202f-120">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="d202f-120">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceRunOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;" Usage="iDataSliceRunOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceRunListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="d202f-121">Die Url zu den nächsten Datenslice wird die Seite ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="d202f-121">The url to the next data slice runs page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d202f-122">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d202f-122">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d202f-123">Ruft die nächste Seite der ausgeführten Instanzen mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d202f-123">Gets the next page of run instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d202f-124">Der Datenslice Liste führt Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="d202f-124">The List data slice runs operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>