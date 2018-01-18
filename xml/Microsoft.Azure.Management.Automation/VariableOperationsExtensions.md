<Type Name="VariableOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.VariableOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VariableOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VariableOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.VariableOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VariableOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VariableOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariableCreateOrUpdateParameters) As VariableCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-101">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-101">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-102">Required.</span></span> <span data-ttu-id="163ac-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-104">Required.</span></span> <span data-ttu-id="163ac-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="163ac-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-106">Required.</span></span> <span data-ttu-id="163ac-107">Die Parameter für die Variable CREATE- oder Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="163ac-107">The parameters supplied to the create or update variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-108">Erstellen Sie eine Variable.</span><span class="sxs-lookup"><span data-stu-id="163ac-108">Create a variable.</span></span>  <span data-ttu-id="163ac-109">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-109">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-110">Das Antwort-Modell für die Variable CREATE- oder Update-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="163ac-110">The response model for the create or update variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariableCreateOrUpdateParameters) As Task(Of VariableCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariableCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-111">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-111">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-112">Required.</span></span> <span data-ttu-id="163ac-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-114">Required.</span></span> <span data-ttu-id="163ac-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="163ac-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-116">Required.</span></span> <span data-ttu-id="163ac-117">Die Parameter für die Variable CREATE- oder Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="163ac-117">The parameters supplied to the create or update variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-118">Erstellen Sie eine Variable.</span><span class="sxs-lookup"><span data-stu-id="163ac-118">Create a variable.</span></span>  <span data-ttu-id="163ac-119">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-119">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-120">Das Antwort-Modell für die Variable CREATE- oder Update-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="163ac-120">The response model for the create or update variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-121">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-121">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-122">Required.</span></span> <span data-ttu-id="163ac-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-124">Required.</span></span> <span data-ttu-id="163ac-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-125">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="163ac-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-126">Required.</span></span> <span data-ttu-id="163ac-127">Der Name der Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-127">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-128">Löschen Sie die Variable an.</span><span class="sxs-lookup"><span data-stu-id="163ac-128">Delete the variable.</span></span>  <span data-ttu-id="163ac-129">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-129">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="163ac-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-131">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-131">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-132">Required.</span></span> <span data-ttu-id="163ac-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-134">Required.</span></span> <span data-ttu-id="163ac-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-135">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="163ac-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-136">Required.</span></span> <span data-ttu-id="163ac-137">Der Name der Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-137">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-138">Löschen Sie die Variable an.</span><span class="sxs-lookup"><span data-stu-id="163ac-138">Delete the variable.</span></span>  <span data-ttu-id="163ac-139">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-139">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="163ac-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableGetResponse Get (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableGetResponse Get(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As VariableGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableGetResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Get (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-141">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-141">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-142">Required.</span></span> <span data-ttu-id="163ac-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-144">Required.</span></span> <span data-ttu-id="163ac-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-145">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="163ac-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-146">Required.</span></span> <span data-ttu-id="163ac-147">Der Name der Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-147">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-148">Rufen Sie die Variable, die anhand des Variablennamens identifiziert.</span><span class="sxs-lookup"><span data-stu-id="163ac-148">Retrieve the variable identified by variable name.</span></span>  <span data-ttu-id="163ac-149">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-149">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-150">Das Antwort-Modell für die Variable Get-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="163ac-150">The response model for the get variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, string variableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, variableName As String) As Task(Of VariableGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, variableName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="variableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-151">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-151">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-152">Required.</span></span> <span data-ttu-id="163ac-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-154">Required.</span></span> <span data-ttu-id="163ac-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-155">The automation account name.</span></span>
            </param>
        <param name="variableName">
            <span data-ttu-id="163ac-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-156">Required.</span></span> <span data-ttu-id="163ac-157">Der Name der Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-157">The name of variable.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-158">Rufen Sie die Variable, die anhand des Variablennamens identifiziert.</span><span class="sxs-lookup"><span data-stu-id="163ac-158">Retrieve the variable identified by variable name.</span></span>  <span data-ttu-id="163ac-159">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-159">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-160">Das Antwort-Modell für die Variable Get-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="163ac-160">The response model for the get variable operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableListResponse List (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableListResponse List(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.List(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVariableOperations, resourceGroupName As String, automationAccount As String) As VariableListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IVariableOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableListResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-161">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-161">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-162">Required.</span></span> <span data-ttu-id="163ac-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-164">Required.</span></span> <span data-ttu-id="163ac-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-166">Rufen Sie eine Liste von Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-166">Retrieve a list of variables.</span></span>  <span data-ttu-id="163ac-167">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-167">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-168">Das Antwort-Modell für den Vorgang der Liste Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-168">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String) As Task(Of VariableListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-169">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-169">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-170">Required.</span></span> <span data-ttu-id="163ac-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-172">Required.</span></span> <span data-ttu-id="163ac-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-174">Rufen Sie eine Liste von Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-174">Retrieve a list of variables.</span></span>  <span data-ttu-id="163ac-175">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-175">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-176">Das Antwort-Modell für den Vorgang der Liste Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-176">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.VariableListResponse ListNext (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.VariableListResponse ListNext(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IVariableOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVariableOperations, nextLink As String) As VariableListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IVariableOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.VariableListResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.VariableListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-177">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-177">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="163ac-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-178">Required.</span></span> <span data-ttu-id="163ac-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="163ac-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-180">Abgerufen Sie weitere Liste der Variablen werden.</span><span class="sxs-lookup"><span data-stu-id="163ac-180">Retrieve next list of variables.</span></span>  <span data-ttu-id="163ac-181">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-181">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-182">Das Antwort-Modell für den Vorgang der Liste Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-182">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IVariableOperations, nextLink As String) As Task(Of VariableListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.VariableListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-183">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-183">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="163ac-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-184">Required.</span></span> <span data-ttu-id="163ac-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="163ac-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-186">Abgerufen Sie weitere Liste der Variablen werden.</span><span class="sxs-lookup"><span data-stu-id="163ac-186">Retrieve next list of variables.</span></span>  <span data-ttu-id="163ac-187">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-187">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-188">Das Antwort-Modell für den Vorgang der Liste Variablen.</span><span class="sxs-lookup"><span data-stu-id="163ac-188">The response model for the list variables operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Patch (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Patch(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariablePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariablePatchParameters) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariablePatchParameters -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariablePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-189">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-189">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-190">Required.</span></span> <span data-ttu-id="163ac-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-192">Required.</span></span> <span data-ttu-id="163ac-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-193">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="163ac-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-194">Required.</span></span> <span data-ttu-id="163ac-195">Für die Variable Patch-Vorgang angegebene Parameter.</span><span class="sxs-lookup"><span data-stu-id="163ac-195">The parameters supplied to the patch variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-196">Aktualisieren Sie eine Variable.</span><span class="sxs-lookup"><span data-stu-id="163ac-196">Update a variable.</span></span>  <span data-ttu-id="163ac-197">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-197">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-198">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="163ac-198">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IVariableOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.VariablePatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.VariableOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IVariableOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.VariablePatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IVariableOperations, resourceGroupName As String, automationAccount As String, parameters As VariablePatchParameters) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IVariableOperations * string * string * Microsoft.Azure.Management.Automation.Models.VariablePatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.VariableOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IVariableOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.VariablePatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="163ac-199">Verweis auf die Microsoft.Azure.Management.Automation.IVariableOperations.</span><span class="sxs-lookup"><span data-stu-id="163ac-199">Reference to the Microsoft.Azure.Management.Automation.IVariableOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="163ac-200">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-200">Required.</span></span> <span data-ttu-id="163ac-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="163ac-201">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="163ac-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-202">Required.</span></span> <span data-ttu-id="163ac-203">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="163ac-203">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="163ac-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="163ac-204">Required.</span></span> <span data-ttu-id="163ac-205">Für die Variable Patch-Vorgang angegebene Parameter.</span><span class="sxs-lookup"><span data-stu-id="163ac-205">The parameters supplied to the patch variable operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="163ac-206">Aktualisieren Sie eine Variable.</span><span class="sxs-lookup"><span data-stu-id="163ac-206">Update a variable.</span></span>  <span data-ttu-id="163ac-207">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="163ac-207">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="163ac-208">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="163ac-208">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>