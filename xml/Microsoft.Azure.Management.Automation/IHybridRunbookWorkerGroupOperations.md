<Type Name="IHybridRunbookWorkerGroupOperations" FullName="Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations">
  <TypeSignature Language="C#" Value="public interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IHybridRunbookWorkerGroupOperations" />
  <TypeSignature Language="F#" Value="type IHybridRunbookWorkerGroupOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3233d-101">Der Dienstvorgang für Automation Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="3233d-101">Service operation for automation hybrid runbook worker group.</span></span>  <span data-ttu-id="3233d-102">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-102">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.DeleteAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
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
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3233d-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3233d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3233d-104">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="3233d-104">Automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="3233d-105">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="3233d-105">The hybrid runbook worker group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3233d-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3233d-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3233d-107">Löschen Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="3233d-107">Delete a hybrid runbook worker group.</span></span>  <span data-ttu-id="3233d-108">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-108">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3233d-109">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="3233d-109">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.GetAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3233d-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3233d-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3233d-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="3233d-111">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="3233d-112">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="3233d-112">The hybrid runbook worker group name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3233d-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3233d-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3233d-114">Abrufen einer Hybrid Runbook Worker-gruppendiagramms.</span><span class="sxs-lookup"><span data-stu-id="3233d-114">Retrieve a hybrid runbook worker group.</span></span>  <span data-ttu-id="3233d-115">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-115">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3233d-116">Das Antwort-Modell für den Hybrid Runbook Worker-Gruppe Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="3233d-116">The response model for the get hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3233d-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3233d-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3233d-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="3233d-118">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3233d-119">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3233d-119">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3233d-120">Rufen Sie eine Liste von Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="3233d-120">Retrieve a list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="3233d-121">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-121">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3233d-122">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="3233d-122">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupsListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="3233d-123">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="3233d-123">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3233d-124">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3233d-124">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3233d-125">Rufen Sie weitere Liste der Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="3233d-125">Retrieve next list of hybrid runbook worker groups.</span></span>  <span data-ttu-id="3233d-126">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-126">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3233d-127">Das Antwort-Modell für die Liste Hybrid Runbook Worker-Gruppen.</span><span class="sxs-lookup"><span data-stu-id="3233d-127">The response model for the list hybrid runbook worker groups.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, string hybridRunbookWorkerGroupName, class Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations.PatchAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * string * Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;" Usage="iHybridRunbookWorkerGroupOperations.PatchAsync (resourceGroupName, automationAccount, hybridRunbookWorkerGroupName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="hybridRunbookWorkerGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.HybridRunbookWorkerGroupPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="3233d-128">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3233d-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="3233d-129">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="3233d-129">The automation account name.</span></span>
            </param>
        <param name="hybridRunbookWorkerGroupName">
            <span data-ttu-id="3233d-130">Der Gruppenname von Hybrid Runbook worker</span><span class="sxs-lookup"><span data-stu-id="3233d-130">The hybrid runbook worker group name</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3233d-131">Hybrid Runbook Worker-Gruppe</span><span class="sxs-lookup"><span data-stu-id="3233d-131">The hybrid runbook worker group</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3233d-132">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3233d-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3233d-133">Aktualisieren Sie eine Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="3233d-133">Update a hybrid runbook worker group.</span></span>  <span data-ttu-id="3233d-134">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="3233d-134">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3233d-135">Das Antwort-Modell für den Patch Hybrid Runbook Worker-Gruppe-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="3233d-135">The response model for the patch hybrid runbook worker group operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>