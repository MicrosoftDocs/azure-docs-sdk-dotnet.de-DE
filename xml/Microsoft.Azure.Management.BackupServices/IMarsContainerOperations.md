<Type Name="IMarsContainerOperations" FullName="Microsoft.Azure.Management.BackupServices.IMarsContainerOperations">
  <TypeSignature Language="C#" Value="public interface IMarsContainerOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMarsContainerOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMarsContainerOperations" />
  <TypeSignature Language="F#" Value="type IMarsContainerOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1ee37-101">Definition der containervorgänge für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="1ee37-101">Definition of Container operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="EnableMarsContainerReregistrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync (string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableMarsContainerReregistrationAsync(string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest enableReregistrationRequest, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.EnableMarsContainerReregistrationAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableMarsContainerReregistrationAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iMarsContainerOperations.EnableMarsContainerReregistrationAsync (resourceGroupName, resourceName, containerId, enableReregistrationRequest, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="enableReregistrationRequest" Type="Microsoft.Azure.Management.BackupServices.Models.EnableReregistrationRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerId">
            <span data-ttu-id="1ee37-102">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="1ee37-102">MARS container ID.</span></span>
            </param>
        <param name="enableReregistrationRequest">
            <span data-ttu-id="1ee37-103">Aktivieren Sie die Anforderung für eine erneute Registrierung.</span><span class="sxs-lookup"><span data-stu-id="1ee37-103">Enable Reregistration Request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1ee37-104">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-104">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ee37-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ee37-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ee37-106">Der Container eine erneute Registrierung zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="1ee37-106">Enable the container reregistration.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1ee37-107">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="1ee37-107">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAndFriendlyNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAndFriendlyNameAsync(string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, string friendlyName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.ListMarsContainersByTypeAndFriendlyNameAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMarsContainersByTypeAndFriendlyNameAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="iMarsContainerOperations.ListMarsContainersByTypeAndFriendlyNameAsync (resourceGroupName, resourceName, containerType, friendlyName, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerType">
            <span data-ttu-id="1ee37-108">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="1ee37-108">Type of container.</span></span>
            </param>
        <param name="friendlyName">
            <span data-ttu-id="1ee37-109">Anzeigename des Containers.</span><span class="sxs-lookup"><span data-stu-id="1ee37-109">Friendly name of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1ee37-110">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-110">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ee37-111">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ee37-111">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ee37-112">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-112">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1ee37-113">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="1ee37-113">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMarsContainersByTypeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt; ListMarsContainersByTypeAsync(string resourceGroupName, string resourceName, valuetype Microsoft.Azure.Management.BackupServices.Models.MarsContainerType containerType, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.ListMarsContainersByTypeAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.MarsContainerType,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListMarsContainersByTypeAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.MarsContainerType * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;" Usage="iMarsContainerOperations.ListMarsContainersByTypeAsync (resourceGroupName, resourceName, containerType, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.ListMarsContainerOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="containerType" Type="Microsoft.Azure.Management.BackupServices.Models.MarsContainerType" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerType">
            <span data-ttu-id="1ee37-114">Der Typ des Containers.</span><span class="sxs-lookup"><span data-stu-id="1ee37-114">Type of container.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1ee37-115">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-115">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ee37-116">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ee37-116">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ee37-117">Ruft die Liste der alle Container, die anhand der angegebenen Abfragezeichenfolge für den Filter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-117">Get the list of all container based on the given query filter string.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1ee37-118">Die Liste der Microsoft Azure Recovery Services (MARS)-Container.</span><span class="sxs-lookup"><span data-stu-id="1ee37-118">List of Microsoft Azure Recovery Services (MARS) containers.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterMarsContainerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync (string resourceGroupName, string resourceName, string containerId, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UnregisterMarsContainerAsync(string resourceGroupName, string resourceName, string containerId, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IMarsContainerOperations.UnregisterMarsContainerAsync(System.String,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnregisterMarsContainerAsync : string * string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iMarsContainerOperations.UnregisterMarsContainerAsync (resourceGroupName, resourceName, containerId, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="containerId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="containerId">
            <span data-ttu-id="1ee37-119">MARS-Container-ID.</span><span class="sxs-lookup"><span data-stu-id="1ee37-119">MARS container ID.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1ee37-120">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="1ee37-120">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1ee37-121">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1ee37-121">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1ee37-122">Aufheben der Registrierung des Containers.</span><span class="sxs-lookup"><span data-stu-id="1ee37-122">Unregister the container.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1ee37-123">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="1ee37-123">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>