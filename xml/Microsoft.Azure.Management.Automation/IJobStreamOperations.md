<Type Name="IJobStreamOperations" FullName="Microsoft.Azure.Management.Automation.IJobStreamOperations">
  <TypeSignature Language="C#" Value="public interface IJobStreamOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IJobStreamOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.IJobStreamOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IJobStreamOperations" />
  <TypeSignature Language="F#" Value="type IJobStreamOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79101-101">Der Dienstvorgang für Automation-Auftrag-Streams.</span><span class="sxs-lookup"><span data-stu-id="79101-101">Service operation for automation job streams.</span></span>  <span data-ttu-id="79101-102">(siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="79101-102">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync (string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.GetAsync(System.String,System.String,System.Guid,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * Guid * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iJobStreamOperations.GetAsync (resourceGroupName, automationAccount, jobId, jobStreamId, cancellationToken)" />
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
            <span data-ttu-id="79101-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="79101-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="79101-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="79101-104">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="79101-105">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="79101-105">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="79101-106">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="79101-106">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="79101-107">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="79101-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="79101-108">Abgerufen Sie die Auftrags-Stream-Id identifizierten auftragsdatenstrom werden.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="79101-108">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="79101-109">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="79101-109">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStreamAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync (string resourceGroupName, string automationAccount, string runbookName, string jobStreamId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync(string resourceGroupName, string automationAccount, string runbookName, string jobStreamId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.GetTestJobStreamAsync(System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTestJobStreamAsync : string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="iJobStreamOperations.GetTestJobStreamAsync (resourceGroupName, automationAccount, runbookName, jobStreamId, cancellationToken)" />
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
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="79101-110">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="79101-110">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="79101-111">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="79101-111">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="79101-112">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="79101-112">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="79101-113">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="79101-113">The job stream id.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="79101-114">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="79101-114">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="79101-115">Abrufen ein Tests Auftrag, Runbook-Name und Stream-Id identifizierten Streams.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="79101-115">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="79101-116">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="79101-116">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListAsync(System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListAsync (resourceGroupName, automationAccount, jobId, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="79101-117">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="79101-117">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="79101-118">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="79101-118">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="79101-119">Die Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="79101-119">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="79101-120">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="79101-120">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="79101-121">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="79101-121">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="79101-122">Rufen Sie eine Liste der Aufträge Datenströme durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="79101-122">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="79101-123">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="79101-123">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync (string nextLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync(string nextLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListNextAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListNextAsync (nextLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextLink">
            <span data-ttu-id="79101-124">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="79101-124">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="79101-125">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="79101-125">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="79101-126">Ruft die nächste Seite der Auftrag Streams mit dem nächsten Link ab.</span><span class="sxs-lookup"><span data-stu-id="79101-126">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="79101-127">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="79101-127">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreamsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync (string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync(string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.IJobStreamOperations.ListTestJobStreamsAsync(System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTestJobStreamsAsync : string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="iJobStreamOperations.ListTestJobStreamsAsync (resourceGroupName, automationAccount, runbookName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="79101-128">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="79101-128">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="79101-129">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="79101-129">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="79101-130">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="79101-130">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="79101-131">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="79101-131">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="79101-132">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="79101-132">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="79101-133">Rufen Sie eine Liste der Test Auftrag Datenströme Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="79101-133">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="79101-134">(siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="79101-134">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="79101-135">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="79101-135">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>