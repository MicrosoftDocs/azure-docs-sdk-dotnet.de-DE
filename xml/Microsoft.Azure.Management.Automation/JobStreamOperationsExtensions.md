<Type Name="JobStreamOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobStreamOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobStreamOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobStreamOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobStreamOperationsExtensions = class" />
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
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse Get (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse Get(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As JobStreamGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-101">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-101">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-102">Required.</span></span> <span data-ttu-id="76520-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-104">Required.</span></span> <span data-ttu-id="76520-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-105">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="76520-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-106">Required.</span></span> <span data-ttu-id="76520-107">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-107">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="76520-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-108">Required.</span></span> <span data-ttu-id="76520-109">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-109">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-110">Abgerufen Sie die Auftrags-Stream-Id identifizierten auftragsdatenstrom werden.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-110">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-111">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-111">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, jobStreamId As String) As Task(Of JobStreamGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobId, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-112">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-112">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-113">Required.</span></span> <span data-ttu-id="76520-114">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-114">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-115">Required.</span></span> <span data-ttu-id="76520-116">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-116">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="76520-117">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-117">Required.</span></span> <span data-ttu-id="76520-118">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-118">The job id.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="76520-119">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-119">Required.</span></span> <span data-ttu-id="76520-120">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-120">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-121">Abgerufen Sie die Auftrags-Stream-Id identifizierten auftragsdatenstrom werden.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-121">Retrieve the job stream identified by job stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-122">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-122">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStream">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetTestJobStream (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse GetTestJobStream(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStream(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTestJobStream (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, jobStreamId As String) As JobStreamGetResponse" />
      <MemberSignature Language="F#" Value="static member GetTestJobStream : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStream (operations, resourceGroupName, automationAccount, runbookName, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-123">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-123">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-124">Required.</span></span> <span data-ttu-id="76520-125">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-125">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-126">Required.</span></span> <span data-ttu-id="76520-127">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-127">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="76520-128">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-128">Required.</span></span> <span data-ttu-id="76520-129">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="76520-129">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="76520-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-130">Required.</span></span> <span data-ttu-id="76520-131">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-131">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-132">Abrufen ein Tests Auftrag, Runbook-Name und Stream-Id identifizierten Streams.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-132">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-133">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-133">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTestJobStreamAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt; GetTestJobStreamAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, string jobStreamId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStreamAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetTestJobStreamAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, jobStreamId As String) As Task(Of JobStreamGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetTestJobStreamAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.GetTestJobStreamAsync (operations, resourceGroupName, automationAccount, runbookName, jobStreamId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="jobStreamId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-134">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-134">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-135">Required.</span></span> <span data-ttu-id="76520-136">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-136">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-137">Required.</span></span> <span data-ttu-id="76520-138">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-138">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="76520-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-139">Required.</span></span> <span data-ttu-id="76520-140">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="76520-140">The runbook name.</span></span>
            </param>
        <param name="jobStreamId">
            <span data-ttu-id="76520-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-141">Required.</span></span> <span data-ttu-id="76520-142">Die Stream-Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="76520-142">The job stream id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-143">Abrufen ein Tests Auftrag, Runbook-Name und Stream-Id identifizierten Streams.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-143">Retrieve a test job streams identified by runbook name and stream id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-144">Das Antwort-Modell für den Get Job-Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-144">The response model for the get job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse List (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse List(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.List(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, parameters As JobStreamListParameters) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.List (operations, resourceGroupName, automationAccount, jobId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-145">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-145">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-146">Required.</span></span> <span data-ttu-id="76520-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-147">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-148">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-148">Required.</span></span> <span data-ttu-id="76520-149">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-149">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="76520-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-150">Required.</span></span> <span data-ttu-id="76520-151">Die Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="76520-151">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76520-152">Optional.</span><span class="sxs-lookup"><span data-stu-id="76520-152">Optional.</span></span> <span data-ttu-id="76520-153">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="76520-153">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-154">Rufen Sie eine Liste der Aufträge Datenströme durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-154">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-155">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-155">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, Guid jobId, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.Guid,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, jobId As Guid, parameters As JobStreamListParameters) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * Guid * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, jobId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-156">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-156">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-157">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-157">Required.</span></span> <span data-ttu-id="76520-158">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-158">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-159">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-159">Required.</span></span> <span data-ttu-id="76520-160">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-160">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="76520-161">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-161">Required.</span></span> <span data-ttu-id="76520-162">Die Auftrags-Id.</span><span class="sxs-lookup"><span data-stu-id="76520-162">The job Id.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76520-163">Optional.</span><span class="sxs-lookup"><span data-stu-id="76520-163">Optional.</span></span> <span data-ttu-id="76520-164">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="76520-164">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-165">Rufen Sie eine Liste der Aufträge Datenströme durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-165">Retrieve a list of jobs streams identified by job id.  (see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-166">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-166">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListNext (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListNext(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobStreamOperations, nextLink As String) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IJobStreamOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-167">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-167">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="76520-168">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-168">Required.</span></span> <span data-ttu-id="76520-169">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="76520-169">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-170">Ruft die nächste Seite der Auftrag Streams mit dem nächsten Link ab.</span><span class="sxs-lookup"><span data-stu-id="76520-170">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-171">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-171">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IJobStreamOperations, nextLink As String) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-172">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-172">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="76520-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-173">Required.</span></span> <span data-ttu-id="76520-174">NextLink aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="76520-174">NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-175">Ruft die nächste Seite der Auftrag Streams mit dem nächsten Link ab.</span><span class="sxs-lookup"><span data-stu-id="76520-175">Gets the next page of job streams using next link.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-176">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-176">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreams">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListTestJobStreams (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse ListTestJobStreams(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreams(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTestJobStreams (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, parameters As JobStreamListParameters) As JobStreamListResponse" />
      <MemberSignature Language="F#" Value="static member ListTestJobStreams : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobStreamListResponse" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreams (operations, resourceGroupName, automationAccount, runbookName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobStreamListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-177">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-177">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-178">Required.</span></span> <span data-ttu-id="76520-179">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-179">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-180">Required.</span></span> <span data-ttu-id="76520-181">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-181">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="76520-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-182">Required.</span></span> <span data-ttu-id="76520-183">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="76520-183">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76520-184">Optional.</span><span class="sxs-lookup"><span data-stu-id="76520-184">Optional.</span></span> <span data-ttu-id="76520-185">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="76520-185">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-186">Rufen Sie eine Liste der Test Auftrag Datenströme Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="76520-186">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="76520-187">(siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-187">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-188">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-188">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTestJobStreamsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync (this Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt; ListTestJobStreamsAsync(class Microsoft.Azure.Management.Automation.IJobStreamOperations operations, string resourceGroupName, string automationAccount, string runbookName, class Microsoft.Azure.Management.Automation.Models.JobStreamListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreamsAsync(Microsoft.Azure.Management.Automation.IJobStreamOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobStreamListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListTestJobStreamsAsync (operations As IJobStreamOperations, resourceGroupName As String, automationAccount As String, runbookName As String, parameters As JobStreamListParameters) As Task(Of JobStreamListResponse)" />
      <MemberSignature Language="F#" Value="static member ListTestJobStreamsAsync : Microsoft.Azure.Management.Automation.IJobStreamOperations * string * string * string * Microsoft.Azure.Management.Automation.Models.JobStreamListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobStreamOperationsExtensions.ListTestJobStreamsAsync (operations, resourceGroupName, automationAccount, runbookName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobStreamListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobStreamOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="runbookName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobStreamListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="76520-189">Verweis auf die Microsoft.Azure.Management.Automation.IJobStreamOperations.</span><span class="sxs-lookup"><span data-stu-id="76520-189">Reference to the Microsoft.Azure.Management.Automation.IJobStreamOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="76520-190">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-190">Required.</span></span> <span data-ttu-id="76520-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="76520-191">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="76520-192">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-192">Required.</span></span> <span data-ttu-id="76520-193">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="76520-193">The automation account name.</span></span>
            </param>
        <param name="runbookName">
            <span data-ttu-id="76520-194">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="76520-194">Required.</span></span> <span data-ttu-id="76520-195">Der Runbook-Name.</span><span class="sxs-lookup"><span data-stu-id="76520-195">The runbook name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="76520-196">Optional.</span><span class="sxs-lookup"><span data-stu-id="76520-196">Optional.</span></span> <span data-ttu-id="76520-197">Die Parameter für den auftragsdatenstrom Liste Stream Elemente zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="76520-197">The parameters supplied to the list job stream's stream items operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="76520-198">Rufen Sie eine Liste der Test Auftrag Datenströme Runbook namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="76520-198">Retrieve a list of test job streams identified by runbook name.</span></span>
            <span data-ttu-id="76520-199">(siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="76520-199">(see http://aka.ms/azureautomationsdk/jobstreamoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="76520-200">Das Antwort-Modell für die Liste Auftrag Stream-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="76520-200">The response model for the list job stream operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>