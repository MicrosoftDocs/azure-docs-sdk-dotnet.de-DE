<Type Name="DscConfigurationOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DscConfigurationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DscConfigurationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DscConfigurationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DscConfigurationOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscConfigurationCreateOrUpdateParameters) As DscConfigurationCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-101">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-101">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-102">Required.</span></span> <span data-ttu-id="8b45d-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-104">Required.</span></span> <span data-ttu-id="8b45d-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b45d-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-106">Required.</span></span> <span data-ttu-id="8b45d-107">Die CREATE- oder Update-Parameter für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-107">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-108">Erstellen Sie die Konfiguration, die durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-108">Create the configuration identified by configuration name.</span></span>  <span data-ttu-id="8b45d-109">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-109">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-110">Das Antwort-Modell für die Konfiguration der Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-110">The response model for the configuration create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, parameters As DscConfigurationCreateOrUpdateParameters) As Task(Of DscConfigurationCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscConfigurationCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-111">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-111">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-112">Required.</span></span> <span data-ttu-id="8b45d-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-114">Required.</span></span> <span data-ttu-id="8b45d-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="8b45d-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-116">Required.</span></span> <span data-ttu-id="8b45d-117">Die CREATE- oder Update-Parameter für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-117">The create or update parameters for configuration.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-118">Erstellen Sie die Konfiguration, die durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-118">Create the configuration identified by configuration name.</span></span>  <span data-ttu-id="8b45d-119">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-119">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-120">Das Antwort-Modell für die Konfiguration der Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-120">The response model for the configuration create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-121">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-121">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-122">Required.</span></span> <span data-ttu-id="8b45d-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-124">Required.</span></span> <span data-ttu-id="8b45d-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-125">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-126">Required.</span></span> <span data-ttu-id="8b45d-127">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-127">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-128">Löschen der dsc-Konfigurations durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-128">Delete the dsc configuration identified by configuration name.</span></span>
            <span data-ttu-id="8b45d-129">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-129">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="8b45d-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-131">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-131">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-132">Required.</span></span> <span data-ttu-id="8b45d-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-134">Required.</span></span> <span data-ttu-id="8b45d-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-135">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-136">Required.</span></span> <span data-ttu-id="8b45d-137">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-137">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-138">Löschen der dsc-Konfigurations durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-138">Delete the dsc configuration identified by configuration name.</span></span>
            <span data-ttu-id="8b45d-139">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-139">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="8b45d-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse Get (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse Get(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As DscConfigurationGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.Get (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-141">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-141">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-142">Required.</span></span> <span data-ttu-id="8b45d-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-144">Required.</span></span> <span data-ttu-id="8b45d-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-145">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-146">Required.</span></span> <span data-ttu-id="8b45d-147">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-147">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-148">Abrufen der Konfigurations durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-148">Retrieve the configuration identified by configuration name.</span></span>  <span data-ttu-id="8b45d-149">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-149">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-150">Das Antwort-Modell für den Abrufvorgang für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-150">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of DscConfigurationGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-151">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-151">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-152">Required.</span></span> <span data-ttu-id="8b45d-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-154">Required.</span></span> <span data-ttu-id="8b45d-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-155">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-156">Required.</span></span> <span data-ttu-id="8b45d-157">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-157">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-158">Abrufen der Konfigurations durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-158">Retrieve the configuration identified by configuration name.</span></span>  <span data-ttu-id="8b45d-159">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-159">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-160">Das Antwort-Modell für den Abrufvorgang für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-160">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse GetContent (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse GetContent(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContent(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContent (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As DscConfigurationGetContentResponse" />
      <MemberSignature Language="F#" Value="static member GetContent : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContent (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-161">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-161">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-162">Required.</span></span> <span data-ttu-id="8b45d-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-164">Required.</span></span> <span data-ttu-id="8b45d-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-165">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-166">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-166">Required.</span></span> <span data-ttu-id="8b45d-167">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-167">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-168">Rufen Sie das Konfigurationsskript durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-168">Retrieve the configuration script identified by configuration name.</span></span>
            <span data-ttu-id="8b45d-169">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-169">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-170">Das Antwort-Modell für den Abrufvorgang für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-170">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt; GetContentAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount, string configurationName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContentAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetContentAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String, configurationName As String) As Task(Of DscConfigurationGetContentResponse)" />
      <MemberSignature Language="F#" Value="static member GetContentAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.GetContentAsync (operations, resourceGroupName, automationAccount, configurationName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationGetContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="configurationName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-171">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-171">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-172">Required.</span></span> <span data-ttu-id="8b45d-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-174">Required.</span></span> <span data-ttu-id="8b45d-175">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-175">The automation account name.</span></span>
            </param>
        <param name="configurationName">
            <span data-ttu-id="8b45d-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-176">Required.</span></span> <span data-ttu-id="8b45d-177">Der Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="8b45d-177">The configuration name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-178">Rufen Sie das Konfigurationsskript durch den Namen identifiziert.</span><span class="sxs-lookup"><span data-stu-id="8b45d-178">Retrieve the configuration script identified by configuration name.</span></span>
            <span data-ttu-id="8b45d-179">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-179">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-180">Das Antwort-Modell für den Abrufvorgang für die Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="8b45d-180">The response model for the get configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse List (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse List(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.List(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String) As DscConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-181">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-181">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-182">Required.</span></span> <span data-ttu-id="8b45d-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-184">Required.</span></span> <span data-ttu-id="8b45d-185">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-185">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-186">Rufen Sie eine Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-186">Retrieve a list of configurations.</span></span>  <span data-ttu-id="8b45d-187">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-187">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-188">Das Antwort-Modell für den Konfigurationsvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="8b45d-188">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IDscConfigurationOperations, resourceGroupName As String, automationAccount As String) As Task(Of DscConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-189">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-189">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="8b45d-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-190">Required.</span></span> <span data-ttu-id="8b45d-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="8b45d-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="8b45d-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-192">Required.</span></span> <span data-ttu-id="8b45d-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="8b45d-193">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-194">Rufen Sie eine Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-194">Retrieve a list of configurations.</span></span>  <span data-ttu-id="8b45d-195">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-195">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-196">Das Antwort-Modell für den Konfigurationsvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="8b45d-196">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse ListNext (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse ListNext(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IDscConfigurationOperations, nextLink As String) As DscConfigurationListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-197">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-197">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="8b45d-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-198">Required.</span></span> <span data-ttu-id="8b45d-199">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-199">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-200">Rufen Sie weitere Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-200">Retrieve next list of configurations.</span></span>  <span data-ttu-id="8b45d-201">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-201">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-202">Das Antwort-Modell für den Konfigurationsvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="8b45d-202">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IDscConfigurationOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IDscConfigurationOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IDscConfigurationOperations, nextLink As String) As Task(Of DscConfigurationListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IDscConfigurationOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.DscConfigurationOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscConfigurationListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IDscConfigurationOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="8b45d-203">Verweis auf die Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span><span class="sxs-lookup"><span data-stu-id="8b45d-203">Reference to the Microsoft.Azure.Management.Automation.IDscConfigurationOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="8b45d-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="8b45d-204">Required.</span></span> <span data-ttu-id="8b45d-205">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-205">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="8b45d-206">Rufen Sie weitere Liste der Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="8b45d-206">Retrieve next list of configurations.</span></span>  <span data-ttu-id="8b45d-207">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="8b45d-207">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="8b45d-208">Das Antwort-Modell für den Konfigurationsvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="8b45d-208">The response model for the list configuration operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>