<Type Name="RunbookDraftOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RunbookDraftOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RunbookDraftOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RunbookDraftOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RunbookDraftOperationsExtensions = class" />
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
    <Member MemberName="BeginPublish">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginPublish (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginPublish(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublish(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPublish (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginPublish : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublish (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-101">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-101">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-102">Required.</span></span> <span data-ttu-id="5ba67-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-104">Required.</span></span> <span data-ttu-id="5ba67-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-106">Required.</span></span> <span data-ttu-id="5ba67-107">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="5ba67-107">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-108">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-108">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-109">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-109">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-110">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-110">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPublishAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublishAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPublishAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginPublishAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginPublishAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-111">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-111">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-112">Required.</span></span> <span data-ttu-id="5ba67-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-114">Required.</span></span> <span data-ttu-id="5ba67-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-116">Required.</span></span> <span data-ttu-id="5ba67-117">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="5ba67-117">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-118">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-118">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-119">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-119">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-120">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-120">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdate (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdate(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdate (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdate (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-121">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-121">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-122">Required.</span></span> <span data-ttu-id="5ba67-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-124">Required.</span></span> <span data-ttu-id="5ba67-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-125">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-126">Required.</span></span> <span data-ttu-id="5ba67-127">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-127">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-128">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-128">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-129">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-129">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-130">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-130">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-131">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-131">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-132">Required.</span></span> <span data-ttu-id="5ba67-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-134">Required.</span></span> <span data-ttu-id="5ba67-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-135">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-136">Required.</span></span> <span data-ttu-id="5ba67-137">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-137">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-138">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-138">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-139">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-139">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-140">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-140">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraph">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdateGraph (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse BeginUpdateGraph(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraph(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateGraph (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member BeginUpdateGraph : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraph (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-141">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-141">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-142">Required.</span></span> <span data-ttu-id="5ba67-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-144">Required.</span></span> <span data-ttu-id="5ba67-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-145">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-146">Required.</span></span> <span data-ttu-id="5ba67-147">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-147">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-148">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-148">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-149">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-149">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-150">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-150">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraphAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraphAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginUpdateGraphAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateGraphAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.BeginUpdateGraphAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-151">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-151">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-152">Required.</span></span> <span data-ttu-id="5ba67-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-154">Required.</span></span> <span data-ttu-id="5ba67-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-155">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-156">Required.</span></span> <span data-ttu-id="5ba67-157">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-157">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-158">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-158">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-159">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-159">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-160">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-160">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Content">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse Content(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Content(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Content (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member Content : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Content (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-161">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-161">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-162">Required.</span></span> <span data-ttu-id="5ba67-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-164">Required.</span></span> <span data-ttu-id="5ba67-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-165">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-166">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-166">Required.</span></span> <span data-ttu-id="5ba67-167">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-167">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-168">Abrufen des Inhalts des Runbook-Entwurf Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5ba67-168">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="5ba67-169">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-169">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-170">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-170">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.ContentAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ContentAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member ContentAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.ContentAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-171">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-171">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-172">Required.</span></span> <span data-ttu-id="5ba67-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-173">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-174">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-174">Required.</span></span> <span data-ttu-id="5ba67-175">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-175">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-176">Required.</span></span> <span data-ttu-id="5ba67-177">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-177">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-178">Abrufen des Inhalts des Runbook-Entwurf Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5ba67-178">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="5ba67-179">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-179">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-180">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-180">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse Get (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse Get(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookDraftGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Get (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-181">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-181">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-182">Required.</span></span> <span data-ttu-id="5ba67-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-183">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-184">Required.</span></span> <span data-ttu-id="5ba67-185">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-185">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-186">Required.</span></span> <span data-ttu-id="5ba67-187">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-187">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-188">Abrufen des Runbook-Entwurfs Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5ba67-188">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="5ba67-189">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-189">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-190">Das Antwort-Modell für den Runbook-Entwurf Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-190">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookDraftGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-191">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-191">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-192">Required.</span></span> <span data-ttu-id="5ba67-193">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-193">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-194">Required.</span></span> <span data-ttu-id="5ba67-195">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-195">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-196">Required.</span></span> <span data-ttu-id="5ba67-197">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-197">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-198">Abrufen des Runbook-Entwurfs Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5ba67-198">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="5ba67-199">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-199">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-200">Das Antwort-Modell für den Runbook-Entwurf Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-200">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Publish">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Publish (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Publish(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Publish(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Publish (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member Publish : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Publish (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-201">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-201">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-202">Required.</span></span> <span data-ttu-id="5ba67-203">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-203">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-204">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-204">Required.</span></span> <span data-ttu-id="5ba67-205">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-205">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-206">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-206">Required.</span></span> <span data-ttu-id="5ba67-207">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="5ba67-207">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-208">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-208">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-209">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-209">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-210">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-210">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.PublishAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PublishAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftPublishParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member PublishAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.PublishAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-211">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-211">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-212">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-212">Required.</span></span> <span data-ttu-id="5ba67-213">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-213">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-214">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-214">Required.</span></span> <span data-ttu-id="5ba67-215">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-215">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-216">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-216">Required.</span></span> <span data-ttu-id="5ba67-217">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="5ba67-217">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-218">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-218">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-219">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-219">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-220">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-220">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEdit">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse UndoEdit (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse UndoEdit(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEdit(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UndoEdit (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As RunbookDraftUndoEditResponse" />
      <MemberSignature Language="F#" Value="static member UndoEdit : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEdit (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-221">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-221">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-222">Required.</span></span> <span data-ttu-id="5ba67-223">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-223">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-224">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-224">Required.</span></span> <span data-ttu-id="5ba67-225">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-225">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-226">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-226">Required.</span></span> <span data-ttu-id="5ba67-227">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-227">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-228">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-228">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-229">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-229">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-230">Das Antwort-Modell für den Undoedit runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-230">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEditAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, string runbookName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEditAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UndoEditAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, runbookName As String) As Task(Of RunbookDraftUndoEditResponse)" />
      <MemberSignature Language="F#" Value="static member UndoEditAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UndoEditAsync (operations, resourceGroupName, automationAccount, runbookName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-231">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-231">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-232">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-232">Required.</span></span> <span data-ttu-id="5ba67-233">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-233">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-234">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-234">Required.</span></span> <span data-ttu-id="5ba67-235">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-235">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="5ba67-236">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-236">Required.</span></span> <span data-ttu-id="5ba67-237">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="5ba67-237">The runbook name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-238">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="5ba67-238">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="5ba67-239">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-239">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-240">Das Antwort-Modell für den Undoedit runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="5ba67-240">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Update (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse Update(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Update(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Update (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.Update (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-241">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-241">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-242">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-242">Required.</span></span> <span data-ttu-id="5ba67-243">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-243">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-244">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-244">Required.</span></span> <span data-ttu-id="5ba67-245">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-245">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-246">Required.</span></span> <span data-ttu-id="5ba67-247">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-247">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-248">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-248">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-249">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-249">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-250">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-250">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-251">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-251">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-252">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-252">Required.</span></span> <span data-ttu-id="5ba67-253">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-253">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-254">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-254">Required.</span></span> <span data-ttu-id="5ba67-255">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-255">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-256">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-256">Required.</span></span> <span data-ttu-id="5ba67-257">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-257">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-258">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-258">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-259">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-259">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-260">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-260">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraph">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse UpdateGraph (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse UpdateGraph(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraph(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateGraph (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As LongRunningOperationResultResponse" />
      <MemberSignature Language="F#" Value="static member UpdateGraph : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraph (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-261">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-261">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-262">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-262">Required.</span></span> <span data-ttu-id="5ba67-263">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-263">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-264">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-264">Required.</span></span> <span data-ttu-id="5ba67-265">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-265">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-266">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-266">Required.</span></span> <span data-ttu-id="5ba67-267">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-267">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-268">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-268">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-269">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-269">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-270">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-270">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraphAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync (this Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync(class Microsoft.Azure.Management.Automation.IRunbookDraftOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraphAsync(Microsoft.Azure.Management.Automation.IRunbookDraftOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpdateGraphAsync (operations As IRunbookDraftOperations, resourceGroupName As String, automationAccount As String, parameters As RunbookDraftUpdateParameters) As Task(Of LongRunningOperationResultResponse)" />
      <MemberSignature Language="F#" Value="static member UpdateGraphAsync : Microsoft.Azure.Management.Automation.IRunbookDraftOperations * string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="Microsoft.Azure.Management.Automation.RunbookDraftOperationsExtensions.UpdateGraphAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IRunbookDraftOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5ba67-271">Verweis auf die Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span><span class="sxs-lookup"><span data-stu-id="5ba67-271">Reference to the Microsoft.Azure.Management.Automation.IRunbookDraftOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="5ba67-272">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-272">Required.</span></span> <span data-ttu-id="5ba67-273">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5ba67-273">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5ba67-274">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-274">Required.</span></span> <span data-ttu-id="5ba67-275">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5ba67-275">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="5ba67-276">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5ba67-276">Required.</span></span> <span data-ttu-id="5ba67-277">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="5ba67-277">The runbook draft update parameters.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5ba67-278">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="5ba67-278">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="5ba67-279">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5ba67-279">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5ba67-280">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="5ba67-280">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>