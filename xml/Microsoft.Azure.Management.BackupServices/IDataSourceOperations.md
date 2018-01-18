<Type Name="IDataSourceOperations" FullName="Microsoft.Azure.Management.BackupServices.IDataSourceOperations">
  <TypeSignature Language="C#" Value="public interface IDataSourceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDataSourceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.IDataSourceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDataSourceOperations" />
  <TypeSignature Language="F#" Value="type IDataSourceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c9c19-101">Die Definition der DataSource-Vorgänge für die Azure Backup-Erweiterung.</span><span class="sxs-lookup"><span data-stu-id="c9c19-101">Definition of DataSource operations for the Azure Backup extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; DisableProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.DisableProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.DisableProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c9c19-102">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="c9c19-102">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="c9c19-103">ContainerName.</span><span class="sxs-lookup"><span data-stu-id="c9c19-103">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="c9c19-104">Elementname.</span><span class="sxs-lookup"><span data-stu-id="c9c19-104">itemName.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9c19-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c9c19-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9c19-106">Deaktivieren Sie den Schutz für die angegebene Element</span><span class="sxs-lookup"><span data-stu-id="c9c19-106">Disable protection for given item</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9c19-107">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="c9c19-107">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; EnableProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest csmparameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.EnableProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.EnableProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMSetProtectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c9c19-108">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="c9c19-108">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="c9c19-109">ContainerName.</span><span class="sxs-lookup"><span data-stu-id="c9c19-109">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="c9c19-110">Elementname.</span><span class="sxs-lookup"><span data-stu-id="c9c19-110">itemName.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="c9c19-111">Set-Schutz-Anforderung Eingabe.</span><span class="sxs-lookup"><span data-stu-id="c9c19-111">Set protection request input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9c19-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c9c19-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9c19-113">Aktivieren des Schutzes für Element angegeben.</span><span class="sxs-lookup"><span data-stu-id="c9c19-113">Enable protection for given item.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9c19-114">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="c9c19-114">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt; ListCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject csmparameters, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.ListCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;" Usage="iDataSourceOperations.ListCSMAsync (resourceGroupName, resourceName, csmparameters, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemListOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMProtectedItemQueryObject" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="csmparameters">
            <span data-ttu-id="c9c19-115">DataSource-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="c9c19-115">DataSource query parameter.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c9c19-116">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="c9c19-116">Request header parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9c19-117">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c9c19-117">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9c19-118">Ruft die Liste aller Datenquellen.</span><span class="sxs-lookup"><span data-stu-id="c9c19-118">Get the list of all Datasources.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9c19-119">Die Definition einer CSMProtectedItemListOperationResponse.</span><span class="sxs-lookup"><span data-stu-id="c9c19-119">The definition of a CSMProtectedItemListOperationResponse.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateProtectionCSMAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync (string resourceGroupName, string resourceName, Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BackupServices.OperationResponse&gt; UpdateProtectionCSMAsync(string resourceGroupName, string resourceName, class Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders customRequestHeaders, string containerName, string itemName, class Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest csmparameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.IDataSourceOperations.UpdateProtectionCSMAsync(System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders,System.String,System.String,Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateProtectionCSMAsync : string * string * Microsoft.Azure.Management.BackupServices.Models.CustomRequestHeaders * string * string * Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BackupServices.OperationResponse&gt;" Usage="iDataSourceOperations.UpdateProtectionCSMAsync (resourceGroupName, resourceName, customRequestHeaders, containerName, itemName, csmparameters, cancellationToken)" />
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
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="itemName" Type="System.String" />
        <Parameter Name="csmparameters" Type="Microsoft.Azure.Management.BackupServices.Models.CSMUpdateProtectionRequest" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">To be added.</param>
        <param name="resourceName">To be added.</param>
        <param name="customRequestHeaders">
            <span data-ttu-id="c9c19-120">Header Anforderungsparameter.</span><span class="sxs-lookup"><span data-stu-id="c9c19-120">Request header parameters.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="c9c19-121">ContainerName.</span><span class="sxs-lookup"><span data-stu-id="c9c19-121">containerName.</span></span>
            </param>
        <param name="itemName">
            <span data-ttu-id="c9c19-122">Elementname.</span><span class="sxs-lookup"><span data-stu-id="c9c19-122">itemName.</span></span>
            </param>
        <param name="csmparameters">
            <span data-ttu-id="c9c19-123">Set-Schutz-Anforderung Eingabe.</span><span class="sxs-lookup"><span data-stu-id="c9c19-123">Set protection request input.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c9c19-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c9c19-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c9c19-125">Aktivieren des Schutzes für Element angegeben.</span><span class="sxs-lookup"><span data-stu-id="c9c19-125">Enable protection for given item.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c9c19-126">Die Definition einer Operation-Antwort.</span><span class="sxs-lookup"><span data-stu-id="c9c19-126">The definition of a Operation Response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>