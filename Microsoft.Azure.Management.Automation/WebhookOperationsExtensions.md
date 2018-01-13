<Type Name="WebhookOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class WebhookOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit WebhookOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module WebhookOperationsExtensions" />
  <TypeSignature Language="F#" Value="type WebhookOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As WebhookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-101">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-101">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-102">Required.</span></span> <span data-ttu-id="424de-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-104">Required.</span></span> <span data-ttu-id="424de-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="424de-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-106">Required.</span></span> <span data-ttu-id="424de-107">Das Erstellen oder Aktualisieren der Parameter für Webhook.</span><span class="sxs-lookup"><span data-stu-id="424de-107">The create or update parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-108">Erstellen des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-108">Create the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-109">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-109">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-110">Das Antwort-Modell für den Webhook erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="424de-110">The response model for the create or update webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookCreateOrUpdateParameters) As Task(Of WebhookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-111">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-111">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-112">Required.</span></span> <span data-ttu-id="424de-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-114">Required.</span></span> <span data-ttu-id="424de-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="424de-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-116">Required.</span></span> <span data-ttu-id="424de-117">Das Erstellen oder Aktualisieren der Parameter für Webhook.</span><span class="sxs-lookup"><span data-stu-id="424de-117">The create or update parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-118">Erstellen des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-118">Create the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-119">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-119">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-120">Das Antwort-Modell für den Webhook erstellen oder aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="424de-120">The response model for the create or update webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-121">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-121">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-122">Required.</span></span> <span data-ttu-id="424de-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-124">Required.</span></span> <span data-ttu-id="424de-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-125">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="424de-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-126">Required.</span></span> <span data-ttu-id="424de-127">Den webhooknamen.</span><span class="sxs-lookup"><span data-stu-id="424de-127">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-128">Löschen des webhooks anhand des Namens an.</span><span class="sxs-lookup"><span data-stu-id="424de-128">Delete the webhook by name.</span></span>  <span data-ttu-id="424de-129">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-129">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="424de-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-131">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-131">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-132">Required.</span></span> <span data-ttu-id="424de-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-134">Required.</span></span> <span data-ttu-id="424de-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-135">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="424de-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-136">Required.</span></span> <span data-ttu-id="424de-137">Den webhooknamen.</span><span class="sxs-lookup"><span data-stu-id="424de-137">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-138">Löschen des webhooks anhand des Namens an.</span><span class="sxs-lookup"><span data-stu-id="424de-138">Delete the webhook by name.</span></span>  <span data-ttu-id="424de-139">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-139">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="424de-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUri">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse GenerateUri(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUri (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As WebhookGenerateUriResponse" />
      <MemberSignature Language="F#" Value="static member GenerateUri : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUri (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-141">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-141">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-142">Required.</span></span> <span data-ttu-id="424de-143">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="424de-143">The name of the resource group.</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-144">Required.</span></span> <span data-ttu-id="424de-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-145">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-146">Generiert einen Uri für die Verwendung in einen Webhook zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="424de-146">Generates a Uri for use in creating a webhook.</span></span>  <span data-ttu-id="424de-147">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-147">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-148">Das Antwort-Modell für die Webhook-Get-Uri-Antwort.</span><span class="sxs-lookup"><span data-stu-id="424de-148">The response model for the webhook get uri response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateUriAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt; GenerateUriAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GenerateUriAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String) As Task(Of WebhookGenerateUriResponse)" />
      <MemberSignature Language="F#" Value="static member GenerateUriAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GenerateUriAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGenerateUriResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-149">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-149">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-150">Required.</span></span> <span data-ttu-id="424de-151">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="424de-151">The name of the resource group.</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-152">Required.</span></span> <span data-ttu-id="424de-153">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-153">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-154">Generiert einen Uri für die Verwendung in einen Webhook zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="424de-154">Generates a Uri for use in creating a webhook.</span></span>  <span data-ttu-id="424de-155">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-155">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-156">Das Antwort-Modell für die Webhook-Get-Uri-Antwort.</span><span class="sxs-lookup"><span data-stu-id="424de-156">The response model for the webhook get uri response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Get(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Get (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-157">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-157">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-158">Required.</span></span> <span data-ttu-id="424de-159">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-160">Required.</span></span> <span data-ttu-id="424de-161">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-161">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="424de-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-162">Required.</span></span> <span data-ttu-id="424de-163">Den webhooknamen.</span><span class="sxs-lookup"><span data-stu-id="424de-163">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-164">Abrufen des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-164">Retrieve the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-165">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-165">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-166">Das Antwort-Modell für den Webhook Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-166">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string webhookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, webhookName As String) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, webhookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="webhookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-167">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-167">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-168">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-168">Required.</span></span> <span data-ttu-id="424de-169">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-169">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-170">Required.</span></span> <span data-ttu-id="424de-171">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-171">The automation account name.</span></span>
            </param>
        <param name="webhookName">
            <span data-ttu-id="424de-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-172">Required.</span></span> <span data-ttu-id="424de-173">Den webhooknamen.</span><span class="sxs-lookup"><span data-stu-id="424de-173">The webhook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-174">Abrufen des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-174">Retrieve the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-175">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-175">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-176">Das Antwort-Modell für den Webhook Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-176">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse List (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse List(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.List (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-177">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-177">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-178">Required.</span></span> <span data-ttu-id="424de-179">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-179">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-180">Required.</span></span> <span data-ttu-id="424de-181">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-181">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="424de-182">Optional.</span><span class="sxs-lookup"><span data-stu-id="424de-182">Optional.</span></span> <span data-ttu-id="424de-183">Der Automation-Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="424de-183">The automation runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-184">Rufen Sie eine Liste von Webhooks.</span><span class="sxs-lookup"><span data-stu-id="424de-184">Retrieve a list of webhooks.</span></span>  <span data-ttu-id="424de-185">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-185">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-186">Das Antwort-Modell für die Liste Webhook-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-186">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-187">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-187">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-188">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-188">Required.</span></span> <span data-ttu-id="424de-189">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-189">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-190">Required.</span></span> <span data-ttu-id="424de-191">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-191">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="424de-192">Optional.</span><span class="sxs-lookup"><span data-stu-id="424de-192">Optional.</span></span> <span data-ttu-id="424de-193">Der Automation-Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="424de-193">The automation runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-194">Rufen Sie eine Liste von Webhooks.</span><span class="sxs-lookup"><span data-stu-id="424de-194">Retrieve a list of webhooks.</span></span>  <span data-ttu-id="424de-195">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-195">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-196">Das Antwort-Modell für die Liste Webhook-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-196">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookListResponse ListNext(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IWebhookOperations, nextLink As String) As WebhookListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.WebhookListResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-197">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-197">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="424de-198">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-198">Required.</span></span> <span data-ttu-id="424de-199">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="424de-199">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-200">Abgerufen Sie weitere Liste der Webhooks werden.</span><span class="sxs-lookup"><span data-stu-id="424de-200">Retrieve next list of webhooks.</span></span>  <span data-ttu-id="424de-201">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-201">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-202">Das Antwort-Modell für die Liste Webhook-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-202">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IWebhookOperations, nextLink As String) As Task(Of WebhookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-203">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-203">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="424de-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-204">Required.</span></span> <span data-ttu-id="424de-205">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="424de-205">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-206">Abgerufen Sie weitere Liste der Webhooks werden.</span><span class="sxs-lookup"><span data-stu-id="424de-206">Retrieve next list of webhooks.</span></span>  <span data-ttu-id="424de-207">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-207">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-208">Das Antwort-Modell für die Liste Webhook-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-208">The response model for the list webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse Patch(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As WebhookGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.WebhookGetResponse" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.WebhookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-209">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-209">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-210">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-210">Required.</span></span> <span data-ttu-id="424de-211">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-211">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-212">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-212">Required.</span></span> <span data-ttu-id="424de-213">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-213">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="424de-214">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-214">Required.</span></span> <span data-ttu-id="424de-215">Die Patch-Parameter für Webhook.</span><span class="sxs-lookup"><span data-stu-id="424de-215">The patch parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-216">Patch des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-216">Patch the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-217">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-217">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-218">Das Antwort-Modell für den Webhook Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-218">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IWebhookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IWebhookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IWebhookOperations, resourceGroupName As String, automationAccount As String, parameters As WebhookPatchParameters) As Task(Of WebhookGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IWebhookOperations * string * string * Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.WebhookOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.WebhookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IWebhookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.WebhookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="424de-219">Verweis auf die Microsoft.Azure.Management.Automation.IWebhookOperations.</span><span class="sxs-lookup"><span data-stu-id="424de-219">Reference to the Microsoft.Azure.Management.Automation.IWebhookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="424de-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-220">Required.</span></span> <span data-ttu-id="424de-221">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="424de-221">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="424de-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-222">Required.</span></span> <span data-ttu-id="424de-223">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="424de-223">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="424de-224">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="424de-224">Required.</span></span> <span data-ttu-id="424de-225">Die Patch-Parameter für Webhook.</span><span class="sxs-lookup"><span data-stu-id="424de-225">The patch parameters for webhook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="424de-226">Patch des webhooks Webhook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="424de-226">Patch the webhook identified by webhook name.</span></span>  <span data-ttu-id="424de-227">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="424de-227">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="424de-228">Das Antwort-Modell für den Webhook Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="424de-228">The response model for the get webhook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>