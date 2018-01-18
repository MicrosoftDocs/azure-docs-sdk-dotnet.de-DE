<Type Name="IDscCompilationJobOperations" FullName="Microsoft.Azure.Management.Automation.IDscCompilationJobOperations">
  <TypeSignature Language="C#" Value="public interface IDscCompilationJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDscCompilationJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDscCompilationJobOperations" />
  <TypeSignature Language="F#" Value="type IDscCompilationJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="924d6-101">Dienstvorgang Automation dsc-Konfiguration kompilieren Aufträge.</span><span class="sxs-lookup"><span data-stu-id="924d6-101">Service operation for automation dsc configuration compile jobs.</span></span>  <span data-ttu-id="924d6-102">(siehe http://aka.ms/azureautomationsdk/dscccompilationjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-102">(see http://aka.ms/azureautomationsdk/dscccompilationjoboperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt; CreateAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.CreateAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;" Usage="iDscCompilationJobOperations.CreateAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="924d6-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="924d6-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="924d6-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="924d6-104">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="924d6-105">Die Parameter für den Auftragsvorgang der erstellen-Kompilierung angegeben.</span><span class="sxs-lookup"><span data-stu-id="924d6-105">The parameters supplied to the create compilation job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="924d6-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="924d6-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="924d6-107">Erstellt die Dsc-Kompilierungsauftrag der Konfiguration an.</span><span class="sxs-lookup"><span data-stu-id="924d6-107">Creates the Dsc compilation job of the configuration.</span></span>  <span data-ttu-id="924d6-108">(siehe http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-108">(see http://aka.ms/azureautomationsdk/dscconfigurationcompilejoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="924d6-109">Das Antwort-Modell für das Erstellen von Dsc-Kompilierung Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="924d6-109">The response model for the create Dsc Compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.GetAsync(System.String,System.String,System.Guid,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;" Usage="iDscCompilationJobOperations.GetAsync (resourceGroupName, automationAccount, jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="924d6-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="924d6-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="924d6-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="924d6-111">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="924d6-112">Die Dsc-Konfiguration Kompilierung Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="924d6-112">The Dsc configuration compilation job id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="924d6-113">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="924d6-113">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="924d6-114">Abrufen der Dsc-Konfiguration-Kompilierungsauftrag durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/dsccompilationjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-114">Retrieve the Dsc configuration compilation job identified by job id.  (see http://aka.ms/azureautomationsdk/dsccompilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="924d6-115">Das Antwort-Modell für den Get Job-Vorgang für Dsc-Kompilierung.</span><span class="sxs-lookup"><span data-stu-id="924d6-115">The response model for the get Dsc compilation job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync (string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetOutputAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.GetOutputAsync(System.String,System.String,System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOutputAsync : string * string * Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iDscCompilationJobOperations.GetOutputAsync (resourceGroupName, automationAccount, jobId, jobStreamId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="924d6-116">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="924d6-116">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="924d6-117">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="924d6-117">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="924d6-118">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="924d6-118">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="924d6-119">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="924d6-119">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="924d6-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="924d6-120">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="924d6-121">Abgerufen Sie die Auftrags-Stream-Id identifizierten auftragsdatenstrom werden.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-121">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="924d6-122">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="924d6-122">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.ListAsync(System.String,System.String,Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="iDscCompilationJobOperations.ListAsync (resourceGroupName, automationAccount, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.DscCompilationJobListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="924d6-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="924d6-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="924d6-124">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="924d6-124">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="924d6-125">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="924d6-125">The parameters supplied to the list operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="924d6-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="924d6-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="924d6-127">Eine Liste der dsc-Kompilierungsaufträge abzurufen.</span><span class="sxs-lookup"><span data-stu-id="924d6-127">Retrieve a list of dsc compilation jobs.</span></span>  <span data-ttu-id="924d6-128">(siehe http://aka.ms/azureautomationsdk/compilationjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-128">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="924d6-129">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="924d6-129">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IDscCompilationJobOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;" Usage="iDscCompilationJobOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.DscCompilationJobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="924d6-130">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="924d6-130">The link to retrieve next set of items.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="924d6-131">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="924d6-131">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="924d6-132">Abgerufen Sie weitere Liste der dsc-Kompilierungsaufträge werden.</span><span class="sxs-lookup"><span data-stu-id="924d6-132">Retrieve next list of dsc compilation jobs.</span></span>  <span data-ttu-id="924d6-133">(siehe http://aka.ms/azureautomationsdk/compilationjoboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="924d6-133">(see http://aka.ms/azureautomationsdk/compilationjoboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="924d6-134">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="924d6-134">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>