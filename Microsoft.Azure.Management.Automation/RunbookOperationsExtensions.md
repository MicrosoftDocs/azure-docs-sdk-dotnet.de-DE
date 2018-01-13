<Type Name="RunbookOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RunbookOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RunbookOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RunbookOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RunbookOperationsExtensions = class" />
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
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Content(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Content (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member Content : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Content (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-101">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-101">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-102">Required.</span></span> <span data-ttu-id="b609b-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-104">Required.</span></span> <span data-ttu-id="b609b-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-105">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-106">Required.</span></span> <span data-ttu-id="b609b-107">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-107">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-108">Rufen Sie den Inhalt des Runbooks im Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-108">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-109">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-109">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-110">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="b609b-110">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ContentAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ContentAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member ContentAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ContentAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-111">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-111">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-112">Required.</span></span> <span data-ttu-id="b609b-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-114">Required.</span></span> <span data-ttu-id="b609b-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-115">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-116">Required.</span></span> <span data-ttu-id="b609b-117">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-117">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-118">Rufen Sie den Inhalt des Runbooks im Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-118">Retrieve the content of runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-119">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-119">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-120">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="b609b-120">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdate (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdate(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateParameters) As RunbookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-121">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-121">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-122">Required.</span></span> <span data-ttu-id="b609b-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-124">Required.</span></span> <span data-ttu-id="b609b-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-125">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-126">Required.</span></span> <span data-ttu-id="b609b-127">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-127">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-128">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-128">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-129">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-129">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-130">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="b609b-130">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateParameters) As Task(Of RunbookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-131">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-131">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-132">Required.</span></span> <span data-ttu-id="b609b-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-134">Required.</span></span> <span data-ttu-id="b609b-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-135">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-136">Required.</span></span> <span data-ttu-id="b609b-137">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-137">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-138">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-138">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-139">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-139">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-140">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="b609b-140">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraft">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdateWithDraft (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse CreateOrUpdateWithDraft(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraft(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithDraft (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateDraftParameters) As RunbookCreateOrUpdateResponse" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithDraft : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraft (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-141">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-141">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-142">Required.</span></span> <span data-ttu-id="b609b-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-144">Required.</span></span> <span data-ttu-id="b609b-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-145">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-146">Required.</span></span> <span data-ttu-id="b609b-147">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-147">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-148">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-148">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-149">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-149">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-150">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="b609b-150">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateWithDraftAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt; CreateOrUpdateWithDraftAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraftAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdateWithDraftAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookCreateOrUpdateDraftParameters) As Task(Of RunbookCreateOrUpdateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateWithDraftAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.CreateOrUpdateWithDraftAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookCreateOrUpdateDraftParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-151">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-151">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-152">Required.</span></span> <span data-ttu-id="b609b-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-154">Required.</span></span> <span data-ttu-id="b609b-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-155">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-156">Required.</span></span> <span data-ttu-id="b609b-157">Die erstellen oder Aktualisieren der Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-157">The create or update parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-158">Erstellen Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-158">Create the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-159">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-159">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-160">Das Antwort-Modell für das Runbook Antwort erstellen.</span><span class="sxs-lookup"><span data-stu-id="b609b-160">The response model for the runbook create response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-161">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-161">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-162">Required.</span></span> <span data-ttu-id="b609b-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-164">Required.</span></span> <span data-ttu-id="b609b-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-166">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-166">Required.</span></span> <span data-ttu-id="b609b-167">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-168">Löschen Sie das Runbook nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="b609b-168">Delete the runbook by name.</span></span>  <span data-ttu-id="b609b-169">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-169">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-170">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b609b-170">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-171">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-171">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-172">Required.</span></span> <span data-ttu-id="b609b-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-174">Required.</span></span> <span data-ttu-id="b609b-175">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-176">Required.</span></span> <span data-ttu-id="b609b-177">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-178">Löschen Sie das Runbook nach Namen an.</span><span class="sxs-lookup"><span data-stu-id="b609b-178">Delete the runbook by name.</span></span>  <span data-ttu-id="b609b-179">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-179">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-180">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b609b-180">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Get (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Get(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-181">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-181">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-182">Required.</span></span> <span data-ttu-id="b609b-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-184">Required.</span></span> <span data-ttu-id="b609b-185">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-186">Required.</span></span> <span data-ttu-id="b609b-187">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-188">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="b609b-188">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-189">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-189">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-190">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="b609b-190">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-191">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-191">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-192">Required.</span></span> <span data-ttu-id="b609b-193">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-194">Required.</span></span> <span data-ttu-id="b609b-195">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="b609b-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-196">Required.</span></span> <span data-ttu-id="b609b-197">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="b609b-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-198">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="b609b-198">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-199">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-199">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-200">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="b609b-200">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookListResponse List (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookListResponse List(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.List(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String) As RunbookListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookListResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-201">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-201">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-202">Required.</span></span> <span data-ttu-id="b609b-203">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-203">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-204">Required.</span></span> <span data-ttu-id="b609b-205">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-205">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-206">Rufen Sie eine Liste von Runbooks.</span><span class="sxs-lookup"><span data-stu-id="b609b-206">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="b609b-207">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-207">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-208">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="b609b-208">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String) As Task(Of RunbookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-209">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-209">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-210">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-210">Required.</span></span> <span data-ttu-id="b609b-211">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-211">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-212">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-212">Required.</span></span> <span data-ttu-id="b609b-213">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-213">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-214">Rufen Sie eine Liste von Runbooks.</span><span class="sxs-lookup"><span data-stu-id="b609b-214">Retrieve a list of runbooks.</span></span>  <span data-ttu-id="b609b-215">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-215">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-216">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="b609b-216">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookListResponse ListNext (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookListResponse ListNext(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IRunbookOperations, nextLink As String) As RunbookListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IRunbookOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookListResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-217">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-217">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b609b-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-218">Required.</span></span> <span data-ttu-id="b609b-219">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b609b-219">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-220">Nächste Liste der Runbooks abrufen.</span><span class="sxs-lookup"><span data-stu-id="b609b-220">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="b609b-221">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-221">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-222">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="b609b-222">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IRunbookOperations, nextLink As String) As Task(Of RunbookListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-223">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-223">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b609b-224">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-224">Required.</span></span> <span data-ttu-id="b609b-225">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b609b-225">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-226">Nächste Liste der Runbooks abrufen.</span><span class="sxs-lookup"><span data-stu-id="b609b-226">Retrieve next list of runbooks.</span></span>  <span data-ttu-id="b609b-227">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-227">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-228">Das Antwort-Modell für den runbookvorgang Liste.</span><span class="sxs-lookup"><span data-stu-id="b609b-228">The response model for the list runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Patch (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse Patch(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Patch(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Patch (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookPatchParameters) As RunbookGetResponse" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters -&gt; Microsoft.Azure.Management.Automation.Models.RunbookGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.Patch (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-229">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-229">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-230">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-230">Required.</span></span> <span data-ttu-id="b609b-231">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-231">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-232">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-232">Required.</span></span> <span data-ttu-id="b609b-233">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-233">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-234">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-234">Required.</span></span> <span data-ttu-id="b609b-235">Die Patch-Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-235">The patch parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-236">Aktualisieren Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-236">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-237">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-237">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-238">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="b609b-238">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync (this Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt; PatchAsync(class Microsoft.Azure.Management.Automation.IRunbookOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.PatchAsync(Microsoft.Azure.Management.Automation.IRunbookOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PatchAsync (operations As IRunbookOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookPatchParameters) As Task(Of RunbookGetResponse)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Management.Automation.IRunbookOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookOperationsExtensions.PatchAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookPatchParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b609b-239">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookOperations.</span><span class="sxs-lookup"><span data-stu-id="b609b-239">Reference to the Microsoft.Azure.Management.Automation.IRunbookOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b609b-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-240">Required.</span></span> <span data-ttu-id="b609b-241">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b609b-241">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b609b-242">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-242">Required.</span></span> <span data-ttu-id="b609b-243">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b609b-243">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b609b-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b609b-244">Required.</span></span> <span data-ttu-id="b609b-245">Die Patch-Parameter für das Runbook.</span><span class="sxs-lookup"><span data-stu-id="b609b-245">The patch parameters for runbook.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b609b-246">Aktualisieren Sie das Runbook Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b609b-246">Update the runbook identified by runbook name.</span></span>  <span data-ttu-id="b609b-247">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b609b-247">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b609b-248">Das Antwort-Modell für die Get-Runbook-Operation.</span><span class="sxs-lookup"><span data-stu-id="b609b-248">The response model for the get runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>