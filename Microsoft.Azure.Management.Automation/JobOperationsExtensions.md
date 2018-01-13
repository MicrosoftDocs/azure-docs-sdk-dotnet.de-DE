<Type Name="JobOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.JobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.JobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobOperationsExtensions = class" />
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
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobCreateResponse Create (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobCreateResponse Create(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Create(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobCreateParameters) As JobCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobCreateResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-101">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-101">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-102">Required.</span></span> <span data-ttu-id="ad96e-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-104">Required.</span></span> <span data-ttu-id="ad96e-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ad96e-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-106">Required.</span></span> <span data-ttu-id="ad96e-107">Die Parameter für den Auftragsvorgang erstellen angegeben.</span><span class="sxs-lookup"><span data-stu-id="ad96e-107">The parameters supplied to the create job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-108">Erstellen Sie einen Auftrag des Runbooks.</span><span class="sxs-lookup"><span data-stu-id="ad96e-108">Create a job of the runbook.</span></span>  <span data-ttu-id="ad96e-109">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-109">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-110">Das Antwort-Modell für den Auftragsvorgang erstellen.</span><span class="sxs-lookup"><span data-stu-id="ad96e-110">The response model for the create job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobCreateParameters) As Task(Of JobCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-111">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-111">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-112">Required.</span></span> <span data-ttu-id="ad96e-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-114">Required.</span></span> <span data-ttu-id="ad96e-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ad96e-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-116">Required.</span></span> <span data-ttu-id="ad96e-117">Die Parameter für den Auftragsvorgang erstellen angegeben.</span><span class="sxs-lookup"><span data-stu-id="ad96e-117">The parameters supplied to the create job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-118">Erstellen Sie einen Auftrag des Runbooks.</span><span class="sxs-lookup"><span data-stu-id="ad96e-118">Create a job of the runbook.</span></span>  <span data-ttu-id="ad96e-119">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-119">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-120">Das Antwort-Modell für den Auftragsvorgang erstellen.</span><span class="sxs-lookup"><span data-stu-id="ad96e-120">The response model for the create job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetResponse Get (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetResponse Get(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-121">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-121">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-122">Required.</span></span> <span data-ttu-id="ad96e-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-124">Required.</span></span> <span data-ttu-id="ad96e-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-125">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-126">Required.</span></span> <span data-ttu-id="ad96e-127">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-127">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-128">Abgerufen Sie den Auftrag mit der Auftrags-Id werden.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-128">Retrieve the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-129">Das Antwort-Modell für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-129">The response model for the get job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-130">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-130">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-131">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-131">Required.</span></span> <span data-ttu-id="ad96e-132">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-132">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-133">Required.</span></span> <span data-ttu-id="ad96e-134">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-134">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-135">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-135">Required.</span></span> <span data-ttu-id="ad96e-136">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-136">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-137">Abgerufen Sie den Auftrag mit der Auftrags-Id werden.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-137">Retrieve the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-138">Das Antwort-Modell für den Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-138">The response model for the get job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutput">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse GetOutput (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse GetOutput(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutput(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutput (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetOutputResponse" />
      <MemberSignature Language="F#" Value="static member GetOutput : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutput (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-139">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-139">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-140">Required.</span></span> <span data-ttu-id="ad96e-141">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-141">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-142">Required.</span></span> <span data-ttu-id="ad96e-143">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-143">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-144">Required.</span></span> <span data-ttu-id="ad96e-145">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-145">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-146">Abrufen der Auftragsausgabe durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-146">Retrieve the job output identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-147">Das Antwort-Modell für die Get-Job Vorgang ausgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-147">The response model for the get job output operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOutputAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt; GetOutputAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutputAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetOutputAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetOutputResponse)" />
      <MemberSignature Language="F#" Value="static member GetOutputAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetOutputAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetOutputResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-148">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-148">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-149">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-149">Required.</span></span> <span data-ttu-id="ad96e-150">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-150">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-151">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-151">Required.</span></span> <span data-ttu-id="ad96e-152">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-152">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-153">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-153">Required.</span></span> <span data-ttu-id="ad96e-154">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-154">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-155">Abrufen der Auftragsausgabe durch Auftrags-Id identifiziert.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-155">Retrieve the job output identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-156">Das Antwort-Modell für die Get-Job Vorgang ausgegeben werden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-156">The response model for the get job output operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContent">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse GetRunbookContent (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse GetRunbookContent(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContent(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRunbookContent (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As JobGetRunbookContentResponse" />
      <MemberSignature Language="F#" Value="static member GetRunbookContent : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContent (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-157">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-157">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-158">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-158">Required.</span></span> <span data-ttu-id="ad96e-159">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-159">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-160">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-160">Required.</span></span> <span data-ttu-id="ad96e-161">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-161">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-162">Required.</span></span> <span data-ttu-id="ad96e-163">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-163">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-164">Abrufen des runbookinhalts aus der der Auftrag mit der Auftrags-Id an.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-164">Retrieve the runbook content of the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-165">Das Antwort-Modell für den runbookinhalt Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-165">The response model for the get runbook content of the job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRunbookContentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt; GetRunbookContentAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContentAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetRunbookContentAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of JobGetRunbookContentResponse)" />
      <MemberSignature Language="F#" Value="static member GetRunbookContentAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.GetRunbookContentAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobGetRunbookContentResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-166">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-166">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-167">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-167">Required.</span></span> <span data-ttu-id="ad96e-168">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-168">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-169">Required.</span></span> <span data-ttu-id="ad96e-170">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-170">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-171">Required.</span></span> <span data-ttu-id="ad96e-172">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-172">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-173">Abrufen des runbookinhalts aus der der Auftrag mit der Auftrags-Id an.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-173">Retrieve the runbook content of the job identified by job id.  (see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-174">Das Antwort-Modell für den runbookinhalt Get Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-174">The response model for the get runbook content of the job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobListResponse List (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobListResponse List(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.List(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobListParameters) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobListResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.List (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-175">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-175">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-176">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-176">Required.</span></span> <span data-ttu-id="ad96e-177">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-177">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-178">Required.</span></span> <span data-ttu-id="ad96e-179">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-179">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ad96e-180">Optional.</span><span class="sxs-lookup"><span data-stu-id="ad96e-180">Optional.</span></span> <span data-ttu-id="ad96e-181">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="ad96e-181">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-182">Rufen Sie eine Liste der Aufträge an.</span><span class="sxs-lookup"><span data-stu-id="ad96e-182">Retrieve a list of jobs.</span></span>  <span data-ttu-id="ad96e-183">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-183">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-184">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-184">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobListParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobListParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobListParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, parameters As JobListParameters) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobListParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobListParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-185">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-185">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-186">Required.</span></span> <span data-ttu-id="ad96e-187">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-187">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-188">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-188">Required.</span></span> <span data-ttu-id="ad96e-189">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-189">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="ad96e-190">Optional.</span><span class="sxs-lookup"><span data-stu-id="ad96e-190">Optional.</span></span> <span data-ttu-id="ad96e-191">Die Parameter für die Liste zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="ad96e-191">The parameters supplied to the list operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-192">Rufen Sie eine Liste der Aufträge an.</span><span class="sxs-lookup"><span data-stu-id="ad96e-192">Retrieve a list of jobs.</span></span>  <span data-ttu-id="ad96e-193">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-193">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-194">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-194">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobListResponse ListNext (this Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobListResponse ListNext(class Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobOperations, nextLink As String) As JobListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IJobOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.JobListResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-195">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-195">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ad96e-196">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-196">Required.</span></span> <span data-ttu-id="ad96e-197">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="ad96e-197">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-198">Abgerufen Sie weitere Liste der Aufträge werden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-198">Retrieve next list of jobs.</span></span>  <span data-ttu-id="ad96e-199">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-199">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-200">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-200">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IJobOperations, nextLink As String) As Task(Of JobListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IJobOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-201">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-201">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="ad96e-202">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-202">Required.</span></span> <span data-ttu-id="ad96e-203">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="ad96e-203">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-204">Abgerufen Sie weitere Liste der Aufträge werden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-204">Retrieve next list of jobs.</span></span>  <span data-ttu-id="ad96e-205">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-205">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-206">Das Antwort-Modell für die Liste Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ad96e-206">The response model for the list job operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Resume">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Resume (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Resume(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Resume(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Resume (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Resume : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Resume (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-207">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-207">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-208">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-208">Required.</span></span> <span data-ttu-id="ad96e-209">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-209">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-210">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-210">Required.</span></span> <span data-ttu-id="ad96e-211">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-211">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-212">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-212">Required.</span></span> <span data-ttu-id="ad96e-213">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-213">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-214">Den Auftrag mit JobId wird fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="ad96e-214">Resume the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-215">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-215">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-216">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-216">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResumeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ResumeAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.ResumeAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ResumeAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member ResumeAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.ResumeAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-217">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-217">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-218">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-218">Required.</span></span> <span data-ttu-id="ad96e-219">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-219">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-220">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-220">Required.</span></span> <span data-ttu-id="ad96e-221">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-221">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-222">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-222">Required.</span></span> <span data-ttu-id="ad96e-223">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-223">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-224">Den Auftrag mit JobId wird fortgesetzt.</span><span class="sxs-lookup"><span data-stu-id="ad96e-224">Resume the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-225">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-225">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-226">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-226">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Stop (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Stop(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Stop(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Stop (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Stop (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-227">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-227">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-228">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-228">Required.</span></span> <span data-ttu-id="ad96e-229">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-229">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-230">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-230">Required.</span></span> <span data-ttu-id="ad96e-231">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-231">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-232">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-232">Required.</span></span> <span data-ttu-id="ad96e-233">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-233">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-234">Den Auftrag mit JobId zu beenden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-234">Stop the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-235">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-235">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-236">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-236">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; StopAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; StopAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.StopAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function StopAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.StopAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-237">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-237">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-238">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-238">Required.</span></span> <span data-ttu-id="ad96e-239">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-239">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-240">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-240">Required.</span></span> <span data-ttu-id="ad96e-241">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-241">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-242">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-242">Required.</span></span> <span data-ttu-id="ad96e-243">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-243">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-244">Den Auftrag mit JobId zu beenden.</span><span class="sxs-lookup"><span data-stu-id="ad96e-244">Stop the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-245">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-245">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-246">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-246">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Suspend">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Suspend (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Suspend(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.Suspend(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Suspend (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Suspend : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.Suspend (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-247">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-247">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-248">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-248">Required.</span></span> <span data-ttu-id="ad96e-249">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-249">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-250">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-250">Required.</span></span> <span data-ttu-id="ad96e-251">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-251">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-252">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-252">Required.</span></span> <span data-ttu-id="ad96e-253">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-253">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-254">Anhalten des Auftrags mit JobId an.</span><span class="sxs-lookup"><span data-stu-id="ad96e-254">Suspend the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-255">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-255">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-256">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-256">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SuspendAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync (this Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, Guid jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; SuspendAsync(class Microsoft.Azure.Management.Automation.IJobOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobOperationsExtensions.SuspendAsync(Microsoft.Azure.Management.Automation.IJobOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function SuspendAsync (operations As IJobOperations, resourceGroupName As String, automationAccount As String, jobId As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member SuspendAsync : Microsoft.Azure.Management.Automation.IJobOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobOperationsExtensions.SuspendAsync (operations, resourceGroupName, automationAccount, jobId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobId" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="ad96e-257">Verweis auf die Microsoft.Azure.Management.Automation.IJobOperations.</span><span class="sxs-lookup"><span data-stu-id="ad96e-257">Reference to the Microsoft.Azure.Management.Automation.IJobOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="ad96e-258">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-258">Required.</span></span> <span data-ttu-id="ad96e-259">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="ad96e-259">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="ad96e-260">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-260">Required.</span></span> <span data-ttu-id="ad96e-261">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="ad96e-261">The automation account name.</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="ad96e-262">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="ad96e-262">Required.</span></span> <span data-ttu-id="ad96e-263">Die Id des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="ad96e-263">The job id.</span></span>
            </param>
        <summary>
            <span data-ttu-id="ad96e-264">Anhalten des Auftrags mit JobId an.</span><span class="sxs-lookup"><span data-stu-id="ad96e-264">Suspend the job identified by jobId.</span></span>  <span data-ttu-id="ad96e-265">(siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="ad96e-265">(see http://aka.ms/azureautomationsdk/joboperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="ad96e-266">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="ad96e-266">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>