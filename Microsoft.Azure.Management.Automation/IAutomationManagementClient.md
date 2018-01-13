<Type Name="IAutomationManagementClient" FullName="Microsoft.Azure.Management.Automation.IAutomationManagementClient">
  <TypeSignature Language="C#" Value="public interface IAutomationManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAutomationManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IAutomationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAutomationManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IAutomationManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IActivityOperations Activities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IActivityOperations Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Activities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Activities As IActivityOperations" />
      <MemberSignature Language="F#" Value="member this.Activities : Microsoft.Azure.Management.Automation.IActivityOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Activities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IActivityOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-101">Der Dienstvorgang für-automatisierungsaktivitäten auf.</span><span class="sxs-lookup"><span data-stu-id="c0896-101">Service operation for automation activities.</span></span>  <span data-ttu-id="c0896-102">(siehe http://aka.ms/azureautomationsdk/activityoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-102">(see http://aka.ms/azureautomationsdk/activityoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentRegistrationInformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AgentRegistrationInformation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AgentRegistrationInformation As IAgentRegistrationOperation" />
      <MemberSignature Language="F#" Value="member this.AgentRegistrationInformation : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.AgentRegistrationInformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAgentRegistrationOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-103">Der Dienstvorgang für Automation agentregistrierungsinformationen.</span><span class="sxs-lookup"><span data-stu-id="c0896-103">Service operation for automation agent registration information.</span></span>
            <span data-ttu-id="c0896-104">(siehe http://aka.ms/azureautomationsdk/agentregistrationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-104">(see http://aka.ms/azureautomationsdk/agentregistrationoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-105">Ruft die API-Version ab.</span><span class="sxs-lookup"><span data-stu-id="c0896-105">Gets the API version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutomationAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AutomationAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutomationAccounts As IAutomationAccountOperations" />
      <MemberSignature Language="F#" Value="member this.AutomationAccounts : Microsoft.Azure.Management.Automation.IAutomationAccountOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.AutomationAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAutomationAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-106">Der Dienstvorgang für Automation-Konten.</span><span class="sxs-lookup"><span data-stu-id="c0896-106">Service operation for automation accounts.</span></span>  <span data-ttu-id="c0896-107">(siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-107">(see http://aka.ms/azureautomationsdk/automationaccountoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-108">Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.</span><span class="sxs-lookup"><span data-stu-id="c0896-108">Gets the URI used as the base for all cloud service requests.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.ICertificateOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICertificateOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Certificates As ICertificateOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.Automation.ICertificateOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-109">Der Dienstvorgang für Automation-Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="c0896-109">Service operation for automation certificates.</span></span>  <span data-ttu-id="c0896-110">(siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-110">(see http://aka.ms/azureautomationsdk/certificateoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.CompilationJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CompilationJobs As IDscCompilationJobOperations" />
      <MemberSignature Language="F#" Value="member this.CompilationJobs : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.CompilationJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscCompilationJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-111">Dienstvorgang Automation dsc-Konfiguration kompilieren Aufträge.</span><span class="sxs-lookup"><span data-stu-id="c0896-111">Service operation for automation dsc configuration compile jobs.</span></span>
            <span data-ttu-id="c0896-112">(siehe http://aka.ms/azureautomationsdk/dscccompilationjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-112">(see http://aka.ms/azureautomationsdk/dscccompilationjoboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Configurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Configurations As IDscConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.Configurations : Microsoft.Azure.Management.Automation.IDscConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Configurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-113">Der Dienstvorgang für Konfigurationen.</span><span class="sxs-lookup"><span data-stu-id="c0896-113">Service operation for configurations.</span></span>  <span data-ttu-id="c0896-114">(siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-114">(see http://aka.ms/azureautomationsdk/configurationoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connections">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IConnectionOperations Connections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionOperations Connections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Connections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Connections As IConnectionOperations" />
      <MemberSignature Language="F#" Value="member this.Connections : Microsoft.Azure.Management.Automation.IConnectionOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Connections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-115">Der Dienstvorgang für Automation-Verbindungen.</span><span class="sxs-lookup"><span data-stu-id="c0896-115">Service operation for automation connections.</span></span>  <span data-ttu-id="c0896-116">(siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-116">(see http://aka.ms/azureautomationsdk/connectionoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ConnectionTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionTypes As IConnectionTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ConnectionTypes : Microsoft.Azure.Management.Automation.IConnectionTypeOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.ConnectionTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-117">Der Dienstvorgang für Automation Connectiontypes.</span><span class="sxs-lookup"><span data-stu-id="c0896-117">Service operation for automation connectiontypes.</span></span>  <span data-ttu-id="c0896-118">(siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-118">(see http://aka.ms/azureautomationsdk/connectiontypeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-119">Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="c0896-119">Gets subscription credentials which uniquely identify Microsoft Azure subscription.</span></span> <span data-ttu-id="c0896-120">Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.</span><span class="sxs-lookup"><span data-stu-id="c0896-120">The subscription ID forms part of the URI for every service call.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationResultStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationResultStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationResultStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="iAutomationManagementClient.GetOperationResultStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            <span data-ttu-id="c0896-121">Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.</span><span class="sxs-lookup"><span data-stu-id="c0896-121">Location value returned by the Begin operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0896-122">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0896-122">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0896-123">Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="c0896-123">The Get Operation Status operation returns the status of the specified operation.</span></span> <span data-ttu-id="c0896-124">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="c0896-124">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0896-125">Eine standarddienstantwort für lang ausgeführte Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c0896-125">A standard service response for long running operations.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync (string requestId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync(string requestId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;" Usage="iAutomationManagementClient.GetOperationStatusAsync (requestId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestId">
            <span data-ttu-id="c0896-126">Die Anforderungs-ID für die Anforderung, die Sie verfolgen möchten. Die Anforderungs-ID wird in der X-ms-Request-Id-Antwort-Header für jede Anforderung zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c0896-126">The request ID for the request you wish to track. The request ID is returned in the x-ms-request-id response header for every request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c0896-127">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c0896-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c0896-128">Der Vorgang Get Operation Status Gibt den Status des Vorgangs Thespecified zurück.</span><span class="sxs-lookup"><span data-stu-id="c0896-128">The Get Operation Status operation returns the status of thespecified operation.</span></span> <span data-ttu-id="c0896-129">Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="c0896-129">After calling an asynchronous operation, you can call Get Operation Status to determine whether the operation has succeeded, failed, or is still in progress.</span></span>  <span data-ttu-id="c0896-130">(siehe http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-130">(see http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="c0896-131">Der Antworttext enthält den Status des angegebenen asynchronen Vorgangs, der angibt, ob es erfolgreich war, in Bearbeitung, oder fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="c0896-131">The response body contains the status of the specified asynchronous operation, indicating whether it has succeeded, is inprogress, or has failed.</span></span> <span data-ttu-id="c0896-132">Beachten Sie, dass dieser Status aus der HTTP-Statuscode zurückgegeben, die für den Get Operation Status Vorgang selbst eindeutig sind.</span><span class="sxs-lookup"><span data-stu-id="c0896-132">Note that this status is distinct from the HTTP status code returned for the Get Operation Status operation itself.</span></span>  <span data-ttu-id="c0896-133">Wenn der asynchrone Vorgang erfolgreich war, enthält der Antworttext den HTTP-Statuscode für die erfolgreiche Anforderung.</span><span class="sxs-lookup"><span data-stu-id="c0896-133">If the asynchronous operation succeeded, the response body includes the HTTP status code for the successful request.</span></span>  <span data-ttu-id="c0896-134">Wenn der asynchrone Vorgang fehlgeschlagen ist, wird der Antworttext enthält den HTTP-Statuscode für die fehlerhafte Anforderung, und enthält auch Informationen zum Fehler.</span><span class="sxs-lookup"><span data-stu-id="c0896-134">If the asynchronous operation failed, the response body includes the HTTP status code for the failed request, and also includes error information regarding the failure.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridRunbookWorkerGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HybridRunbookWorkerGroups As IHybridRunbookWorkerGroupOperations" />
      <MemberSignature Language="F#" Value="member this.HybridRunbookWorkerGroups : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-135">Der Dienstvorgang für Automation Hybrid Runbook Worker-Gruppe.</span><span class="sxs-lookup"><span data-stu-id="c0896-135">Service operation for automation hybrid runbook worker group.</span></span>  <span data-ttu-id="c0896-136">(siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-136">(see http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IJobOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Jobs As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.Automation.IJobOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Jobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-137">Der Dienstvorgang für Automation-Aufträge.</span><span class="sxs-lookup"><span data-stu-id="c0896-137">Service operation for automation jobs.</span></span>  <span data-ttu-id="c0896-138">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-138">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSchedules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobSchedules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobSchedules As IJobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobSchedules : Microsoft.Azure.Management.Automation.IJobScheduleOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobSchedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-139">Der Dienstvorgang für Automation-Auftragszeitpläne.</span><span class="sxs-lookup"><span data-stu-id="c0896-139">Service operation for automation job schedules.</span></span>  <span data-ttu-id="c0896-140">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-140">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobStreams">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobStreams" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobStreams As IJobStreamOperations" />
      <MemberSignature Language="F#" Value="member this.JobStreams : Microsoft.Azure.Management.Automation.IJobStreamOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobStreams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobStreamOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-141">Der Dienstvorgang für Automation-Auftrag-Streams.</span><span class="sxs-lookup"><span data-stu-id="c0896-141">Service operation for automation job streams.</span></span>  <span data-ttu-id="c0896-142">(siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-142">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-143">Ruft ab oder legt das ursprüngliche Timeout für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c0896-143">Gets or sets the initial timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-144">Ruft ab oder legt das wiederholungstimeout für zeitintensive Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="c0896-144">Gets or sets the retry timeout for Long Running Operations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Modules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IModuleOperations Modules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IModuleOperations Modules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Modules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Modules As IModuleOperations" />
      <MemberSignature Language="F#" Value="member this.Modules : Microsoft.Azure.Management.Automation.IModuleOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Modules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IModuleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-145">Der Dienstvorgang für Automation-Module.</span><span class="sxs-lookup"><span data-stu-id="c0896-145">Service operation for automation modules.</span></span>  <span data-ttu-id="c0896-146">(siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-146">(see http://aka.ms/azureautomationsdk/moduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeConfigurations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeConfigurations As IDscNodeConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.NodeConfigurations : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-147">Der Dienstvorgang für Automation dsc-Knotenkonfigurationen.</span><span class="sxs-lookup"><span data-stu-id="c0896-147">Service operation for automation dsc node configurations.</span></span>  <span data-ttu-id="c0896-148">(siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-148">(see http://aka.ms/azureautomationsdk/dscnodeconfigurations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReports">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeReports As IDscNodeReportsOperations" />
      <MemberSignature Language="F#" Value="member this.NodeReports : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeReports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeReportsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-149">Der Dienstvorgang für Knoten Berichte.</span><span class="sxs-lookup"><span data-stu-id="c0896-149">Service operation for node reports.</span></span>  <span data-ttu-id="c0896-150">(siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-150">(see http://aka.ms/azureautomationsdk/dscnodereportoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Nodes As IDscNodeOperations" />
      <MemberSignature Language="F#" Value="member this.Nodes : Microsoft.Azure.Management.Automation.IDscNodeOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Nodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-151">Der Dienstvorgang für dsc-Knoten.</span><span class="sxs-lookup"><span data-stu-id="c0896-151">Service operation for dsc nodes.</span></span>  <span data-ttu-id="c0896-152">(siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-152">(see http://aka.ms/azureautomationsdk/dscnodeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectDataTypes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ObjectDataTypes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ObjectDataTypes As IObjectDataTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ObjectDataTypes : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.ObjectDataTypes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IObjectDataTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-153">Der Dienstvorgang für Automation Object-Datentypen.</span><span class="sxs-lookup"><span data-stu-id="c0896-153">Service operation for automation object data types.</span></span>  <span data-ttu-id="c0896-154">(siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-154">(see http://aka.ms/azureautomationsdk/objectdatatypeoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PsCredentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.PsCredentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PsCredentials As ICredentialOperations" />
      <MemberSignature Language="F#" Value="member this.PsCredentials : Microsoft.Azure.Management.Automation.ICredentialOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.PsCredentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICredentialOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-155">Der Dienstvorgang für Automation-Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="c0896-155">Service operation for automation credentials.</span></span>  <span data-ttu-id="c0896-156">(siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-156">(see http://aka.ms/azureautomationsdk/credentialoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNamespace">
      <MemberSignature Language="C#" Value="public string ResourceNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ResourceNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceNamespace : string with get, set" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.ResourceNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-157">Ruft ab oder legt die Ressourcennamespace.</span><span class="sxs-lookup"><span data-stu-id="c0896-157">Gets or sets the resource namespace.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookDraft">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.RunbookDraft" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunbookDraft As IRunbookDraftOperations" />
      <MemberSignature Language="F#" Value="member this.RunbookDraft : Microsoft.Azure.Management.Automation.IRunbookDraftOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.RunbookDraft" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookDraftOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-158">Der Dienstvorgang für Automation-runbookentwurfs.</span><span class="sxs-lookup"><span data-stu-id="c0896-158">Service operation for automation runbook draft.</span></span>  <span data-ttu-id="c0896-159">(siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-159">(see http://aka.ms/azureautomationsdk/runbookdraftoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbooks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Runbooks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Runbooks As IRunbookOperations" />
      <MemberSignature Language="F#" Value="member this.Runbooks : Microsoft.Azure.Management.Automation.IRunbookOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Runbooks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-160">Der Dienstvorgang für Automation-Runbooks.</span><span class="sxs-lookup"><span data-stu-id="c0896-160">Service operation for automation runbooks.</span></span>  <span data-ttu-id="c0896-161">(siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-161">(see http://aka.ms/azureautomationsdk/runbookoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IScheduleOperations Schedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IScheduleOperations Schedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Schedules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Schedules As IScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.Schedules : Microsoft.Azure.Management.Automation.IScheduleOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Schedules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-162">Der Dienstvorgang für Automation-Zeitpläne.</span><span class="sxs-lookup"><span data-stu-id="c0896-162">Service operation for automation schedules.</span></span>  <span data-ttu-id="c0896-163">(siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-163">(see http://aka.ms/azureautomationsdk/scheduleoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Statistics As IStatisticsOperations" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Management.Automation.IStatisticsOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Statistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IStatisticsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-164">Der Dienstvorgang für Automation-Statistiken.</span><span class="sxs-lookup"><span data-stu-id="c0896-164">Service operation for automation statistics.</span></span>  <span data-ttu-id="c0896-165">(siehe http://aka.ms/azureautomationsdk/statisticsoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-165">(see http://aka.ms/azureautomationsdk/statisticsoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TestJobs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestJobs As ITestJobOperations" />
      <MemberSignature Language="F#" Value="member this.TestJobs : Microsoft.Azure.Management.Automation.ITestJobOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.TestJobs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITestJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-166">Der Dienstvorgang für Automation Testaufträge.</span><span class="sxs-lookup"><span data-stu-id="c0896-166">Service operation for automation test jobs.</span></span>  <span data-ttu-id="c0896-167">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-167">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeFields">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TypeFields" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TypeFields As ITypeFieldOperations" />
      <MemberSignature Language="F#" Value="member this.TypeFields : Microsoft.Azure.Management.Automation.ITypeFieldOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.TypeFields" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITypeFieldOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-168">Der Dienstvorgang für Automation-Feldern.</span><span class="sxs-lookup"><span data-stu-id="c0896-168">Service operation for automation type fields.</span></span>  <span data-ttu-id="c0896-169">(siehe http://aka.ms/azureautomationsdk/typefieldoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-169">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IUsageOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IUsageOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usages As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.Automation.IUsageOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Usages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-170">Der Dienstvorgang für Automation Verwendungen.</span><span class="sxs-lookup"><span data-stu-id="c0896-170">Service operation for automation usages.</span></span>  <span data-ttu-id="c0896-171">(siehe http://aka.ms/azureautomationsdk/usageoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-171">(see http://aka.ms/azureautomationsdk/usageoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Variables">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IVariableOperations Variables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IVariableOperations Variables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Variables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Variables As IVariableOperations" />
      <MemberSignature Language="F#" Value="member this.Variables : Microsoft.Azure.Management.Automation.IVariableOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Variables" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IVariableOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-172">Der Dienstvorgang für Automation-Variablen.</span><span class="sxs-lookup"><span data-stu-id="c0896-172">Service operation for automation variables.</span></span>  <span data-ttu-id="c0896-173">(siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-173">(see http://aka.ms/azureautomationsdk/variableoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Webhooks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Webhooks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Webhooks As IWebhookOperations" />
      <MemberSignature Language="F#" Value="member this.Webhooks : Microsoft.Azure.Management.Automation.IWebhookOperations" Usage="Microsoft.Azure.Management.Automation.IAutomationManagementClient.Webhooks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IWebhookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c0896-174">Der Dienstvorgang für Automation-Webhook.</span><span class="sxs-lookup"><span data-stu-id="c0896-174">Service operation for automation webhook.</span></span>  <span data-ttu-id="c0896-175">(siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="c0896-175">(see http://aka.ms/azureautomationsdk/webhookoperations for more information)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>