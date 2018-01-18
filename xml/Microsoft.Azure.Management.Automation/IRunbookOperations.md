<Type Name="IRunbookOperations" FullName="Microsoft.Azure.Management.Automation.IRunbookOperations">
  <TypeSignature Language="C#" Value="public interface IRunbookOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRunbookOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IRunbookOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRunbookOperations" />
  <TypeSignature Language="F#" Value="type IRunbookOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a9831-101">Der Dienstvorgang für Automation-Runbooks.</span><span class="sxs-lookup"><span data-stu-id="a9831-101">Service operation for automation runbooks.</span></span>  <span data-ttu-id="a9831-102">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-102">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="iRunbookOperations.ContentAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-104">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="a9831-105">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="a9831-105">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-107">Rufen Sie den Inhalt des Runbooks im Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a9831-107">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="a9831-108">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-108">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-109">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="a9831-109">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="iRunbookOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-111">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a9831-112">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="a9831-112">The create or update parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-114">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a9831-114">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="a9831-115">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-115">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-116">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="a9831-116">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraftAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.CreateOrUpdateWithDraftAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateWithDraftAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="iRunbookOperations.CreateOrUpdateWithDraftAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-118">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a9831-119">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="a9831-119">The create or update parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-121">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a9831-121">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="a9831-122">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-122">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-123">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="a9831-123">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iRunbookOperations.DeleteAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="a9831-126">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="a9831-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-127">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-128">Löschen Sie das Runbook nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="a9831-128">Delete the runbook by name.</span></span>  <span data-ttu-id="a9831-129">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-129">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="a9831-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="iRunbookOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-131">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-132">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="a9831-133">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="a9831-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-134">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-135">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="a9831-135">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="a9831-136">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-136">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-137">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="a9831-137">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="iRunbookOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-138">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-138">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-139">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-139">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-140">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-140">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-141">Rufen Sie eine Liste von Runbooks.</span><span class="sxs-lookup"><span data-stu-id="a9831-141">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="a9831-142">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-142">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-143">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="a9831-143">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="iRunbookOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="a9831-144">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="a9831-144">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-145">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-145">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-146">Nächste Liste der Runbooks abrufen.</span><span class="sxs-lookup"><span data-stu-id="a9831-146">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="a9831-147">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-147">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-148">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="a9831-148">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="iRunbookOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="a9831-149">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="a9831-149">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="a9831-150">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="a9831-150">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="a9831-151">Die Patch-Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="a9831-151">The patch parameters for runbook.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="a9831-152">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="a9831-152">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="a9831-153">Aktualisieren Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="a9831-153">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="a9831-154">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="a9831-154">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="a9831-155">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="a9831-155">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>