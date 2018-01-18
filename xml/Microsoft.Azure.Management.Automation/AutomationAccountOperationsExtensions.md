<Type Name="AutomationAccountOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class AutomationAccountOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AutomationAccountOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AutomationAccountOperationsExtensions" />
  <TypeSignature Language="F#" Value="type AutomationAccountOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountCreateOrUpdateParameters) As AutomationAccountCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-101">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-101">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-102">Required.</span></span> <span data-ttu-id="dcac2-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-103">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcac2-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-104">Required.</span></span> <span data-ttu-id="dcac2-105">Parameter für das Automation-Konto erstellen oder aktualisieren bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="dcac2-105">Parameters supplied to the create or update automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-106">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-106">Create an automation account.</span></span>  <span data-ttu-id="dcac2-107">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-107">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-108">Das Antwort-Modell für den Vorgang der Konto erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="dcac2-108">The response model for the create or update account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountCreateOrUpdateParameters) As Task(Of AutomationAccountCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-109">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-109">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-110">Required.</span></span> <span data-ttu-id="dcac2-111">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-111">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcac2-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-112">Required.</span></span> <span data-ttu-id="dcac2-113">Parameter für das Automation-Konto erstellen oder aktualisieren bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="dcac2-113">Parameters supplied to the create or update automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-114">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-114">Create an automation account.</span></span>  <span data-ttu-id="dcac2-115">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-115">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-116">Das Antwort-Modell für den Vorgang der Konto erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="dcac2-116">The response model for the create or update account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccountName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Delete (operations, resourceGroupName, automationAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-117">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-117">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-118">Required.</span></span> <span data-ttu-id="dcac2-119">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-119">The name of the resource group</span></span>
            </param>
        <param name="automationAccountName">
            <span data-ttu-id="dcac2-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-120">Required.</span></span> <span data-ttu-id="dcac2-121">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="dcac2-121">Automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-122">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-122">Create an automation account.</span></span>  <span data-ttu-id="dcac2-123">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-123">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-124">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="dcac2-124">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccountName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccountName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccountName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccountName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-125">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-125">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-126">Required.</span></span> <span data-ttu-id="dcac2-127">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-127">The name of the resource group</span></span>
            </param>
        <param name="automationAccountName">
            <span data-ttu-id="dcac2-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-128">Required.</span></span> <span data-ttu-id="dcac2-129">Automation-Kontonamen.</span><span class="sxs-lookup"><span data-stu-id="dcac2-129">Automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-130">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-130">Create an automation account.</span></span>  <span data-ttu-id="dcac2-131">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-131">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-132">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="dcac2-132">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse Get (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse Get(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccount As String) As AutomationAccountGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Get (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-133">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-133">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-134">Required.</span></span> <span data-ttu-id="dcac2-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-135">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcac2-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-136">Required.</span></span> <span data-ttu-id="dcac2-137">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-137">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-138">Abgerufen Sie der Name von Konto werden.</span><span class="sxs-lookup"><span data-stu-id="dcac2-138">Retrieve the account by account name.</span></span>  <span data-ttu-id="dcac2-139">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-139">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-140">Das Antwort-Modell für den Abrufvorgang für das Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-140">The response model for the get account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IAutomationAccountOperations, resourceGroupName As String, automationAccount As String) As Task(Of AutomationAccountGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-141">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-141">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-142">Required.</span></span> <span data-ttu-id="dcac2-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="dcac2-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-144">Required.</span></span> <span data-ttu-id="dcac2-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-146">Abgerufen Sie der Name von Konto werden.</span><span class="sxs-lookup"><span data-stu-id="dcac2-146">Retrieve the account by account name.</span></span>  <span data-ttu-id="dcac2-147">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-147">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-148">Das Antwort-Modell für den Abrufvorgang für das Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-148">The response model for the get account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse List (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse List(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.List(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IAutomationAccountOperations, resourceGroupName As String) As AutomationAccountListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-149">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-149">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-150">Optional.</span><span class="sxs-lookup"><span data-stu-id="dcac2-150">Optional.</span></span> <span data-ttu-id="dcac2-151">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-151">The name of the resource group</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-152">Rufen Sie eine Liste von Konten.</span><span class="sxs-lookup"><span data-stu-id="dcac2-152">Retrieve a list of accounts.</span></span>  <span data-ttu-id="dcac2-153">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-153">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-154">Das Antwort-Modell für die Konto-Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="dcac2-154">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IAutomationAccountOperations, resourceGroupName As String) As Task(Of AutomationAccountListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListAsync (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-155">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-155">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-156">Optional.</span><span class="sxs-lookup"><span data-stu-id="dcac2-156">Optional.</span></span> <span data-ttu-id="dcac2-157">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-157">The name of the resource group</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-158">Rufen Sie eine Liste von Konten.</span><span class="sxs-lookup"><span data-stu-id="dcac2-158">Retrieve a list of accounts.</span></span>  <span data-ttu-id="dcac2-159">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-159">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-160">Das Antwort-Modell für die Konto-Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="dcac2-160">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse ListNext (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse ListNext(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IAutomationAccountOperations, nextLink As String) As AutomationAccountListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-161">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-161">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="dcac2-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-162">Required.</span></span> <span data-ttu-id="dcac2-163">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="dcac2-163">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-164">Abgerufen Sie weitere Liste der Konten werden.</span><span class="sxs-lookup"><span data-stu-id="dcac2-164">Retrieve next list of accounts.</span></span>  <span data-ttu-id="dcac2-165">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-165">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-166">Das Antwort-Modell für die Konto-Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="dcac2-166">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IAutomationAccountOperations, nextLink As String) As Task(Of AutomationAccountListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-167">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-167">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="dcac2-168">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-168">Required.</span></span> <span data-ttu-id="dcac2-169">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="dcac2-169">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-170">Abgerufen Sie weitere Liste der Konten werden.</span><span class="sxs-lookup"><span data-stu-id="dcac2-170">Retrieve next list of accounts.</span></span>  <span data-ttu-id="dcac2-171">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-171">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-172">Das Antwort-Modell für die Konto-Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="dcac2-172">The response model for the list account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse Patch (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse Patch(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountPatchParameters) As AutomationAccountPatchResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.Patch (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-173">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-173">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-174">Required.</span></span> <span data-ttu-id="dcac2-175">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-175">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcac2-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-176">Required.</span></span> <span data-ttu-id="dcac2-177">Parameter für die Patch-Automation-Konto bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="dcac2-177">Parameters supplied to the patch automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-178">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-178">Create an automation account.</span></span>  <span data-ttu-id="dcac2-179">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-179">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-180">Das Antwort-Modell für den Erstellungsvorgang für das Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-180">The response model for the create account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IAutomationAccountOperations operations, string resourceGroupName, class Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IAutomationAccountOperations,System.String,Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IAutomationAccountOperations, resourceGroupName As String, parameters As AutomationAccountPatchParameters) As Task(Of AutomationAccountPatchResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IAutomationAccountOperations * string * Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationAccountOperationsExtensions.PatchAsync (operations, resourceGroupName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IAutomationAccountOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.AutomationAccountPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcac2-181">Verweis auf die Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span><span class="sxs-lookup"><span data-stu-id="dcac2-181">Reference to the Microsoft.Azure.Management.Automation.IAutomationAccountOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcac2-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-182">Required.</span></span> <span data-ttu-id="dcac2-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcac2-183">The name of the resource group</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcac2-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="dcac2-184">Required.</span></span> <span data-ttu-id="dcac2-185">Parameter für die Patch-Automation-Konto bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="dcac2-185">Parameters supplied to the patch automation account.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcac2-186">Erstellen Sie ein Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-186">Create an automation account.</span></span>  <span data-ttu-id="dcac2-187">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="dcac2-187">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="dcac2-188">Das Antwort-Modell für den Erstellungsvorgang für das Konto.</span><span class="sxs-lookup"><span data-stu-id="dcac2-188">The response model for the create account operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>