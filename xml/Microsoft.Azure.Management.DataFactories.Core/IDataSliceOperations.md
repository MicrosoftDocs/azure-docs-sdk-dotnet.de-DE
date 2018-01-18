<Type Name="IDataSliceOperations" FullName="Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d3c2e-101">Vorgänge zum Verwalten von Datenslices.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-101">Operations for managing data slices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3c2e-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d3c2e-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-103">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d3c2e-104">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-104">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d3c2e-105">Parameter, die angibt, wie der Datenslices des Datasets aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-105">Parameters specifying how to list data slices of the dataset.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3c2e-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3c2e-107">Ruft die erste Seite des Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-107">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d3c2e-108">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-108">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="d3c2e-109">Die Url der nächsten Datenseite Slices.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-109">The url to the next data slices page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3c2e-110">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3c2e-111">Ruft die nächste Seite der Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-111">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d3c2e-112">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-112">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (string resourceGroupName, string dataFactoryName, string datasetName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(string resourceGroupName, string dataFactoryName, string datasetName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Core.IDataSliceOperations.SetStatusAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStatusAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataSliceOperations.SetStatusAsync (resourceGroupName, dataFactoryName, datasetName, parameters, cancellationToken)" />
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
        <Parameter Name="datasetName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="d3c2e-113">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-113">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="d3c2e-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-114">A unique data factory instance name.</span></span>
            </param>
        <param name="datasetName">
            <span data-ttu-id="d3c2e-115">Eine eindeutige Instanz DatasetName.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-115">A unique dataset instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="d3c2e-116">Die Parameter erforderlich, um den Status der Datenslices festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-116">The parameters required to set status of data slices.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d3c2e-117">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d3c2e-118">Legt den Status der Datenslices über einen Zeitraum für ein bestimmtes Dataset fest.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-118">Sets status of data slices over a time range for a specific dataset.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d3c2e-119">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="d3c2e-119">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>