<Type Name="IRunbookDraftOperations" FullName="Microsoft.Azure.Management.Automation.IRunbookDraftOperations">
  <TypeSignature Language="C#" Value="public interface IRunbookDraftOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRunbookDraftOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IRunbookDraftOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRunbookDraftOperations" />
  <TypeSignature Language="F#" Value="type IRunbookDraftOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42ec4-101">Der Dienstvorgang für Automation-runbookentwurfs.</span><span class="sxs-lookup"><span data-stu-id="42ec4-101">Service operation for automation runbook draft.</span></span>  <span data-ttu-id="42ec4-102">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-102">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginPublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginPublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginPublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginPublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginPublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-105">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="42ec4-105">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-107">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="42ec4-107">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="42ec4-108">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-108">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-109">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-109">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-111">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-112">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="42ec4-112">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-114">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="42ec4-114">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="42ec4-115">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-115">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-116">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-116">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; BeginUpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.BeginUpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.BeginUpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-118">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-119">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="42ec4-119">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-121">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="42ec4-121">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="42ec4-122">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-122">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-123">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-123">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt; ContentAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.ContentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ContentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookContentResponse&gt;" Usage="iRunbookDraftOperations.ContentAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
            <span data-ttu-id="42ec4-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="42ec4-126">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="42ec4-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-127">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-128">Abrufen des Inhalts des Runbook-Entwurf Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="42ec4-128">Retrieve the content of runbook draft identified by runbook name.</span></span>
            <span data-ttu-id="42ec4-129">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-129">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-130">Das Antwort-Modell für den Inhalt runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="42ec4-130">The response model for the runbook content operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;" Usage="iRunbookDraftOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-131">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-132">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="42ec4-133">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="42ec4-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-134">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-135">Abrufen des Runbook-Entwurfs Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="42ec4-135">Retrieve the runbook draft identified by runbook name.</span></span>  <span data-ttu-id="42ec4-136">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-136">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-137">Das Antwort-Modell für den Runbook-Entwurf Abrufvorgang.</span><span class="sxs-lookup"><span data-stu-id="42ec4-137">The response model for the get runbook draft operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublishAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; PublishAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.PublishAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PublishAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.PublishAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftPublishParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-138">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-138">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-139">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-139">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-140">Parameter, die den Veröffentlichungsvorgang für das Runbook übergeben.</span><span class="sxs-lookup"><span data-stu-id="42ec4-140">The parameters supplied to the publish runbook operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-141">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-141">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-142">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="42ec4-142">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="42ec4-143">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-143">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-144">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-144">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UndoEditAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt; UndoEditAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UndoEditAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UndoEditAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;" Usage="iRunbookDraftOperations.UndoEditAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.RunbookDraftUndoEditResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-145">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-145">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-146">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-146">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="42ec4-147">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="42ec4-147">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-148">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-148">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-149">Abgerufen Sie das Runbook namentlich identifizierte Runbook werden.</span><span class="sxs-lookup"><span data-stu-id="42ec4-149">Retrieve the runbook identified by runbook name.</span></span>  <span data-ttu-id="42ec4-150">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-150">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-151">Das Antwort-Modell für den Undoedit runbookvorgang.</span><span class="sxs-lookup"><span data-stu-id="42ec4-151">The response model for the undoedit runbook operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-152">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-152">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-153">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-153">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-154">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="42ec4-154">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-155">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-155">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-156">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="42ec4-156">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="42ec4-157">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-157">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-158">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-158">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateGraphAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; UpdateGraphAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IRunbookDraftOperations.UpdateGraphAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateGraphAsync : string * string * Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iRunbookDraftOperations.UpdateGraphAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.RunbookDraftUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="42ec4-159">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="42ec4-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="42ec4-160">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="42ec4-160">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="42ec4-161">Die Runbook-Entwurf-Update-Parameter.</span><span class="sxs-lookup"><span data-stu-id="42ec4-161">The runbook draft update parameters.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="42ec4-162">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="42ec4-162">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="42ec4-163">Aktualisiert die Runbook-Entwurf mit RunbookStream als Inhalt.</span><span class="sxs-lookup"><span data-stu-id="42ec4-163">Updates the runbook draft with runbookStream as its content.</span></span>  <span data-ttu-id="42ec4-164">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="42ec4-164">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="42ec4-165">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="42ec4-165">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>