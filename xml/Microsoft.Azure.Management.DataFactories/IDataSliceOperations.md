<Type Name="IDataSliceOperations" FullName="Microsoft.Azure.Management.DataFactories.IDataSliceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSliceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSliceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IDataSliceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSliceOperations" />
  <TypeSignature Language="F#" Value="type IDataSliceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80ee0-101">Vorgänge zum Verwalten von Datenslices.</span><span class="sxs-lookup"><span data-stu-id="80ee0-101">Operations for managing data slices.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt;" Usage="iDataSliceOperations.ListAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="80ee0-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="80ee0-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="80ee0-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="80ee0-103">A unique data factory instance name.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="80ee0-104">Eine eindeutige Instanz Tabellenname.</span><span class="sxs-lookup"><span data-stu-id="80ee0-104">A unique table instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80ee0-105">Parameter, die angibt, wie der Datenslices der Tabelle aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="80ee0-105">Parameters specifying how to list data slices of the table.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80ee0-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="80ee0-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80ee0-107">Ruft die erste Seite des Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="80ee0-107">Gets the first page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="80ee0-108">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="80ee0-108">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.DataSliceListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
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
            <span data-ttu-id="80ee0-109">Die Url der nächsten Datenseite Slices.</span><span class="sxs-lookup"><span data-stu-id="80ee0-109">The url to the next data slices page.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80ee0-110">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="80ee0-110">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80ee0-111">Ruft die nächste Seite der Slice-Dateninstanzen, mit dem Link zur nächsten Seite ab.</span><span class="sxs-lookup"><span data-stu-id="80ee0-111">Gets the next page of data slice instances with the link to the next page.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="80ee0-112">Die Liste Datenslices Vorgangsantwort.</span><span class="sxs-lookup"><span data-stu-id="80ee0-112">The List data slices operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync (string resourceGroupName, string dataFactoryName, string tableName, Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SetStatusAsync(string resourceGroupName, string dataFactoryName, string tableName, class Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IDataSliceOperations.SetStatusAsync(System.String,System.String,System.String,Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStatusAsync : string * string * string * Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDataSliceOperations.SetStatusAsync (resourceGroupName, dataFactoryName, tableName, parameters, cancellationToken)" />
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
        <Parameter Name="tableName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.DataFactories.Models.DataSliceSetStatusParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="80ee0-113">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="80ee0-113">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="80ee0-114">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="80ee0-114">A unique data factory instance name.</span></span>
            </param>
        <param name="tableName">
            <span data-ttu-id="80ee0-115">Eine eindeutige Instanz Tabellenname.</span><span class="sxs-lookup"><span data-stu-id="80ee0-115">A unique table instance name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="80ee0-116">Die Parameter erforderlich, um den Status der Datenslices festgelegt.</span><span class="sxs-lookup"><span data-stu-id="80ee0-116">The parameters required to set status of data slices.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="80ee0-117">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="80ee0-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="80ee0-118">Status des Datenslices festgelegt über einen Zeitraum für eine bestimmte Tabelle.</span><span class="sxs-lookup"><span data-stu-id="80ee0-118">Sets status of data slices over a time range for a specific table.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="80ee0-119">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="80ee0-119">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>