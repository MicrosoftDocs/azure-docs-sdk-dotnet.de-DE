<Type Name="ITestJobOperations" FullName="Microsoft.Azure.Management.Automation.ITestJobOperations">
  <TypeSignature Language="C#" Value="public interface ITestJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITestJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ITestJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITestJobOperations" />
  <TypeSignature Language="F#" Value="type ITestJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="eb14d-101">Der Dienstvorgang für Automation Testaufträge.</span><span class="sxs-lookup"><span data-stu-id="eb14d-101">Service operation for automation test jobs.</span></span>  <span data-ttu-id="eb14d-102">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-102">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;" Usage="iTestJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.TestJobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb14d-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eb14d-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="eb14d-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb14d-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="eb14d-105">Für den Create Test Job-Vorgang angegebene Parameter.</span><span class="sxs-lookup"><span data-stu-id="eb14d-105">The parameters supplied to the create test job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb14d-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb14d-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb14d-107">Erstellen eines Testauftrags des Runbooks.</span><span class="sxs-lookup"><span data-stu-id="eb14d-107">Create a test job of the runbook.</span></span>  <span data-ttu-id="eb14d-108">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-108">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb14d-109">Das Antwort-Modell für das Erstellen, Testen Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="eb14d-109">The response model for the create test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;" Usage="iTestJobOperations.GetAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TestJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb14d-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eb14d-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="eb14d-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb14d-111">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="eb14d-112">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="eb14d-112">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb14d-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb14d-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb14d-114">Abrufen des Testauftrags für das angegebene Runbook an.</span><span class="sxs-lookup"><span data-stu-id="eb14d-114">Retrieve the test job for the specified runbook.</span></span>  <span data-ttu-id="eb14d-115">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-115">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb14d-116">Das Antwort-Modell für die Get Job-Vorgang zu testen.</span><span class="sxs-lookup"><span data-stu-id="eb14d-116">The response model for the get test job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.ResumeAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResumeAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.ResumeAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb14d-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eb14d-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="eb14d-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb14d-118">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="eb14d-119">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="eb14d-119">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb14d-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb14d-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb14d-121">Fortsetzen des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="eb14d-121">Resume the test job.</span></span>  <span data-ttu-id="eb14d-122">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-122">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb14d-123">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="eb14d-123">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.StopAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.StopAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb14d-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eb14d-124">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="eb14d-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb14d-125">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="eb14d-126">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="eb14d-126">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb14d-127">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb14d-127">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb14d-128">Beenden des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="eb14d-128">Stop the test job.</span></span>  <span data-ttu-id="eb14d-129">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-129">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb14d-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="eb14d-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (string resourceGroupName, string automationAccount, string runbookName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(string resourceGroupName, string automationAccount, string runbookName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITestJobOperations.SuspendAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SuspendAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iTestJobOperations.SuspendAsync (resourceGroupName, automationAccount, runbookName, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="eb14d-131">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="eb14d-131">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="eb14d-132">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="eb14d-132">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="eb14d-133">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="eb14d-133">The runbook name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="eb14d-134">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="eb14d-134">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="eb14d-135">Anhalten des Testauftrags an.</span><span class="sxs-lookup"><span data-stu-id="eb14d-135">Suspend the test job.</span></span>  <span data-ttu-id="eb14d-136">(siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="eb14d-136">(see http://aka.ms/azureautomationsdk/testjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="eb14d-137">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="eb14d-137">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>