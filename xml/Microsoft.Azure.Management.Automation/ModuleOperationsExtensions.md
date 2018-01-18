<Type Name="ModuleOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ModuleOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ModuleOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ModuleOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ModuleOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, parameters As ModuleCreateOrUpdateParameters) As ModuleCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-101">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-101">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-102">Required.</span></span> <span data-ttu-id="5edc6-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-104">Required.</span></span> <span data-ttu-id="5edc6-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5edc6-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-106">Required.</span></span> <span data-ttu-id="5edc6-107">Die CREATE- oder Update-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="5edc6-107">The create or update parameters for module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-108">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="5edc6-108">Create the module identified by module name.</span></span>  <span data-ttu-id="5edc6-109">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-109">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-110">Das Antwort-Modell für den Vorgang der-Modul erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5edc6-110">The response model for the create or update module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, parameters As ModuleCreateOrUpdateParameters) As Task(Of ModuleCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModuleCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-111">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-111">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-112">Required.</span></span> <span data-ttu-id="5edc6-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-114">Required.</span></span> <span data-ttu-id="5edc6-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5edc6-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-116">Required.</span></span> <span data-ttu-id="5edc6-117">Die CREATE- oder Update-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="5edc6-117">The create or update parameters for module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-118">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="5edc6-118">Create the module identified by module name.</span></span>  <span data-ttu-id="5edc6-119">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-119">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-120">Das Antwort-Modell für den Vorgang der-Modul erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="5edc6-120">The response model for the create or update module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-121">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-121">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-122">Required.</span></span> <span data-ttu-id="5edc6-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-124">Required.</span></span> <span data-ttu-id="5edc6-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-125">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="5edc6-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-126">Required.</span></span> <span data-ttu-id="5edc6-127">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="5edc6-127">The module name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-128">Löschen Sie das Modul nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="5edc6-128">Delete the module by name.</span></span>  <span data-ttu-id="5edc6-129">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-129">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="5edc6-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-131">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-131">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-132">Required.</span></span> <span data-ttu-id="5edc6-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-134">Required.</span></span> <span data-ttu-id="5edc6-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-135">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="5edc6-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-136">Required.</span></span> <span data-ttu-id="5edc6-137">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="5edc6-137">The module name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-138">Löschen Sie das Modul nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="5edc6-138">Delete the module by name.</span></span>  <span data-ttu-id="5edc6-139">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-139">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="5edc6-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ModuleGetResponse Get (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse Get(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As ModuleGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ModuleGetResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Get (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ModuleGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-141">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-141">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-142">Required.</span></span> <span data-ttu-id="5edc6-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-144">Required.</span></span> <span data-ttu-id="5edc6-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-145">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="5edc6-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-146">Required.</span></span> <span data-ttu-id="5edc6-147">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="5edc6-147">The module name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-148">Abgerufen Sie das Modul identifiziert anhand des Namens des Moduls werden.</span><span class="sxs-lookup"><span data-stu-id="5edc6-148">Retrieve the module identified by module name.</span></span>  <span data-ttu-id="5edc6-149">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-149">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-150">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-150">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, string moduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, moduleName As String) As Task(Of ModuleGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, moduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-151">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-151">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-152">Required.</span></span> <span data-ttu-id="5edc6-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-154">Required.</span></span> <span data-ttu-id="5edc6-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-155">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="5edc6-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-156">Required.</span></span> <span data-ttu-id="5edc6-157">Der Modulname.</span><span class="sxs-lookup"><span data-stu-id="5edc6-157">The module name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-158">Abgerufen Sie das Modul identifiziert anhand des Namens des Moduls werden.</span><span class="sxs-lookup"><span data-stu-id="5edc6-158">Retrieve the module identified by module name.</span></span>  <span data-ttu-id="5edc6-159">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-159">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-160">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-160">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ModuleListResponse List (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ModuleListResponse List(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.List(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IModuleOperations, resourceGroupName As String, automationAccount As String) As ModuleListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IModuleOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.ModuleListResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ModuleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-161">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-161">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-162">Required.</span></span> <span data-ttu-id="5edc6-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-164">Required.</span></span> <span data-ttu-id="5edc6-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-166">Rufen Sie eine Liste der Module.</span><span class="sxs-lookup"><span data-stu-id="5edc6-166">Retrieve a list of modules.</span></span>  <span data-ttu-id="5edc6-167">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-167">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-168">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-168">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IModuleOperations, resourceGroupName As String, automationAccount As String) As Task(Of ModuleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-169">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-169">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-170">Required.</span></span> <span data-ttu-id="5edc6-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-172">Required.</span></span> <span data-ttu-id="5edc6-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-174">Rufen Sie eine Liste der Module.</span><span class="sxs-lookup"><span data-stu-id="5edc6-174">Retrieve a list of modules.</span></span>  <span data-ttu-id="5edc6-175">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-175">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-176">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-176">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ModuleListResponse ListNext (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ModuleListResponse ListNext(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IModuleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IModuleOperations, nextLink As String) As ModuleListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IModuleOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.ModuleListResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ModuleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-177">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-177">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5edc6-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-178">Required.</span></span> <span data-ttu-id="5edc6-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="5edc6-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-180">Nächste Liste der Module abrufen.</span><span class="sxs-lookup"><span data-stu-id="5edc6-180">Retrieve next list of modules.</span></span>  <span data-ttu-id="5edc6-181">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-181">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-182">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-182">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IModuleOperations, nextLink As String) As Task(Of ModuleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-183">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-183">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="5edc6-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-184">Required.</span></span> <span data-ttu-id="5edc6-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="5edc6-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-186">Nächste Liste der Module abrufen.</span><span class="sxs-lookup"><span data-stu-id="5edc6-186">Retrieve next list of modules.</span></span>  <span data-ttu-id="5edc6-187">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-187">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-188">Das Antwort-Modell für den List-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-188">The response model for the list module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.ModuleGetResponse Patch (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse Patch(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModulePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, parameters As ModulePatchParameters) As ModuleGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ModulePatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.ModuleGetResponse" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.ModuleGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModulePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-189">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-189">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-190">Required.</span></span> <span data-ttu-id="5edc6-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-192">Required.</span></span> <span data-ttu-id="5edc6-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5edc6-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-194">Required.</span></span> <span data-ttu-id="5edc6-195">Die Patch-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="5edc6-195">The patch parameters for module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-196">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="5edc6-196">Create the module identified by module name.</span></span>  <span data-ttu-id="5edc6-197">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-197">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-198">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-198">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IModuleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.ModulePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IModuleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.ModulePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IModuleOperations, resourceGroupName As String, automationAccount As String, parameters As ModulePatchParameters) As Task(Of ModuleGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IModuleOperations * string * string * Microsoft.Azure.Management.Automation.Models.ModulePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.ModuleOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.ModuleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IModuleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.ModulePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5edc6-199">Verweis auf die Microsoft.Azure.Management.Automation.IModuleOperations.</span><span class="sxs-lookup"><span data-stu-id="5edc6-199">Reference to the Microsoft.Azure.Management.Automation.IModuleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5edc6-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-200">Required.</span></span> <span data-ttu-id="5edc6-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5edc6-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5edc6-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-202">Required.</span></span> <span data-ttu-id="5edc6-203">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5edc6-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5edc6-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5edc6-204">Required.</span></span> <span data-ttu-id="5edc6-205">Die Patch-Parameter für das Modul.</span><span class="sxs-lookup"><span data-stu-id="5edc6-205">The patch parameters for module.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5edc6-206">Erstellen Sie das Modul identifiziert anhand des Namens des Moduls.</span><span class="sxs-lookup"><span data-stu-id="5edc6-206">Create the module identified by module name.</span></span>  <span data-ttu-id="5edc6-207">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5edc6-207">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5edc6-208">Das Antwort-Modell für die Get-Modul-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5edc6-208">The response model for the get module operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>