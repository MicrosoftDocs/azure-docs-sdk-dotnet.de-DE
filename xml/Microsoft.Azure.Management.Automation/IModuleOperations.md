<Type Name="IModuleOperations" FullName="Microsoft.Azure.Management.Automation.IModuleOperations">
  <TypeSignature Language="C#" Value="public interface IModuleOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IModuleOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IModuleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IModuleOperations" />
  <TypeSignature Language="F#" Value="type IModuleOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="47764-101">Der Dienstvorgang für Automation-Module.</span><span class="sxs-lookup"><span data-stu-id="47764-101">Service operation for automation modules.</span></span>  <span data-ttu-id="47764-102">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-102">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt; CreateOrUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt; CreateOrUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.CreateOrUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateOrUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt;" Usage="iModuleOperations.CreateOrUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47764-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="47764-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="47764-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="47764-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="47764-105">Die CREATE- oder Update-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="47764-105">The create or update parameters for module.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-107">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="47764-107">Create the module identified by module name.</span></span>  <span data-ttu-id="47764-108">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-108">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-109">Das Antwort-Modell für den Vorgang der-Modul erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="47764-109">The response model for the create or update module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (string resourceGroupName, string automationAccount, string moduleName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(string resourceGroupName, string automationAccount, string moduleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.DeleteAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iModuleOperations.DeleteAsync (resourceGroupName, automationAccount, moduleName, cancellationToken)" />
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
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47764-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="47764-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="47764-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="47764-111">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="47764-112">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="47764-112">The module name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-114">Löschen Sie das Modul nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="47764-114">Delete the module by name.</span></span>  <span data-ttu-id="47764-115">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-115">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-116">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="47764-116">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string moduleName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string moduleName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;" Usage="iModuleOperations.GetAsync (resourceGroupName, automationAccount, moduleName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47764-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="47764-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="47764-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="47764-118">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="47764-119">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="47764-119">The module name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-121">Abgerufen Sie das Modul identifiziert anhand des Namens des Moduls werden.</span><span class="sxs-lookup"><span data-stu-id="47764-121">Retrieve the module identified by module name.</span></span>  <span data-ttu-id="47764-122">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-122">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-123">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="47764-123">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.ListAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;" Usage="iModuleOperations.ListAsync (resourceGroupName, automationAccount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47764-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="47764-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="47764-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="47764-125">The automation account name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-127">Rufen Sie eine Liste der Module.</span><span class="sxs-lookup"><span data-stu-id="47764-127">Retrieve a list of modules.</span></span>  <span data-ttu-id="47764-128">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-128">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-129">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="47764-129">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;" Usage="iModuleOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="47764-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="47764-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-132">Nächste Liste der Module abrufen.</span><span class="sxs-lookup"><span data-stu-id="47764-132">Retrieve next list of modules.</span></span>  <span data-ttu-id="47764-133">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-133">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-134">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="47764-134">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; PatchAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; PatchAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IModuleOperations.PatchAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModulePatchParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PatchAsync : string * string * Microsoft.Azure.Management.Automation.Models.ModulePatchParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;" Usage="iModuleOperations.PatchAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModulePatchParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="47764-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="47764-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="47764-136">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="47764-136">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="47764-137">Die Patch-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="47764-137">The patch parameters for module.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="47764-138">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="47764-138">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="47764-139">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="47764-139">Create the module identified by module name.</span></span>  <span data-ttu-id="47764-140">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="47764-140">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="47764-141">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="47764-141">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>