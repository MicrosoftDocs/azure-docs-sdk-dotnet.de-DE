<Type Name="IDscNodeOperations" FullName="Microsoft.Azure.Management.Automation.IDscNodeOperations">
  <TypeSignature Language="C#" Value="public interface IDscNodeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscNodeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscNodeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscNodeOperations" />
  <TypeSignature Language="F#" Value="type IDscNodeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f8150-101">Der Dienstvorgang für dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="f8150-101">Service operation for dsc nodes.</span></span>  <span data-ttu-id="f8150-102">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-102">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, Guid nodeId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeOperations.DeleteAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iDscNodeOperations.DeleteAsync (resourceGroupName, automationAccount, nodeId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f8150-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f8150-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f8150-104">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="f8150-104">Automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f8150-105">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="f8150-105">The node id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8150-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8150-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8150-107">Löschen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-107">Delete the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8150-108">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="f8150-108">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid nodeId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid nodeId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeOperations.GetAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;" Usage="iDscNodeOperations.GetAsync (resourceGroupName, automationAccount, nodeId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="nodeId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f8150-109">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f8150-109">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f8150-110">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f8150-110">The automation account name.</span></span>
            </param>
        <param name="nodeId">
            <span data-ttu-id="f8150-111">Die Knoten-ID.</span><span class="sxs-lookup"><span data-stu-id="f8150-111">The node id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8150-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8150-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8150-113">Abrufen der dsc-Knoten, die durch die Knoten-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-113">Retrieve the dsc node identified by node id.  (see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8150-114">Das Antwort-Modell für die Get dsc-Knotens.</span><span class="sxs-lookup"><span data-stu-id="f8150-114">The response model for the get dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodeListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodeListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodeListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="iDscNodeOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodeListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f8150-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f8150-115">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f8150-116">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f8150-116">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8150-117">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="f8150-117">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8150-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8150-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8150-119">Eine Liste der dsc-Knoten abzurufen.</span><span class="sxs-lookup"><span data-stu-id="f8150-119">Retrieve a list of dsc nodes.</span></span>  <span data-ttu-id="f8150-120">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-120">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8150-121">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f8150-121">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;" Usage="iDscNodeOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodeListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="f8150-122">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="f8150-122">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8150-123">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8150-123">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8150-124">Rufen Sie weitere Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="f8150-124">Retrieve next list of configurations.</span></span>  <span data-ttu-id="f8150-125">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-125">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8150-126">Das Antwort-Modell für die Liste dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f8150-126">The response model for the list dsc nodes operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscNodeOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;" Usage="iDscNodeOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscNodePatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscNodePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="f8150-127">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="f8150-127">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="f8150-128">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="f8150-128">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="f8150-129">Parameter, die auf den Patch für dsc-Knoten angegeben.</span><span class="sxs-lookup"><span data-stu-id="f8150-129">Parameters supplied to the patch dsc node.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="f8150-130">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="f8150-130">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f8150-131">Aktualisieren Sie den dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="f8150-131">Update the dsc node.</span></span>  <span data-ttu-id="f8150-132">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="f8150-132">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f8150-133">Das Antwort-Modell für die Patch-dsc-Knoten-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="f8150-133">The response model for the patch dsc node operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>