<Type Name="IContainerOperations" FullName="Microsoft.Azure.Management.BackupServices.IContainerOperations">
  <TypeSignature Language="C#" Value="public interface IContainerOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IContainerOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerOperations" />
  <TypeSignature Language="F#" Value="type IContainerOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4ab77-101">Definition der containervorgänge für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="4ab77-101">Definition of Container operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt; ListAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters parameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;" Usage="iContainerOperations.ListAsync (resourceGroupName, resourceName, parameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMContainerListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BackupServices.Models.ContainerQueryParameters" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="parameters">
            <span data-ttu-id="4ab77-102">Container-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-102">Container query parameters.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4ab77-103">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-103">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ab77-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4ab77-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ab77-105">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-105">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ab77-106">Die Definition einer CSMContainerListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="4ab77-106">The definition of a CSMContainerListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RefreshAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RefreshAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RefreshAsync (resourceGroupName, resourceName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4ab77-107">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-107">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ab77-108">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4ab77-108">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ab77-109">Lösen Sie die Ermittlung an.</span><span class="sxs-lookup"><span data-stu-id="4ab77-109">Trigger the Discovery.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ab77-110">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="4ab77-110">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; RegisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.RegisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.RegisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            <span data-ttu-id="4ab77-111">Container werden registriert.</span><span class="sxs-lookup"><span data-stu-id="4ab77-111">Container to be register.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4ab77-112">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-112">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ab77-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4ab77-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ab77-114">Registrieren Sie den Container.</span><span class="sxs-lookup"><span data-stu-id="4ab77-114">Register the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ab77-115">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="4ab77-115">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync (string resourceGroupName, string resourceName, string containerName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterAsync(string resourceGroupName, string resourceName, string containerName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IContainerOperations.UnregisterAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iContainerOperations.UnregisterAsync (resourceGroupName, resourceName, containerName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerName">
            <span data-ttu-id="4ab77-116">Container, der Registrierung aufgehoben werden soll.</span><span class="sxs-lookup"><span data-stu-id="4ab77-116">Container which we want to unregister.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="4ab77-117">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="4ab77-117">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="4ab77-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="4ab77-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="4ab77-119">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="4ab77-119">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="4ab77-120">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="4ab77-120">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>