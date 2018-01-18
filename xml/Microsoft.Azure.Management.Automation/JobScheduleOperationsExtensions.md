<Type Name="JobScheduleOperationsExtensions" FullName="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobScheduleOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobScheduleOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobScheduleOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobScheduleOperationsExtensions = class" />
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse Create (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse Create(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Create(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As JobScheduleCreateParameters) As JobScheduleCreateResponse" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters -&gt; Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Create (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-101">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-101">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-102">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-102">Required.</span></span> <span data-ttu-id="b89e8-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-104">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-104">Required.</span></span> <span data-ttu-id="b89e8-105">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-105">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b89e8-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-106">Required.</span></span> <span data-ttu-id="b89e8-107">Die Parameter, die auf den Auftrag-Zeitplan Erstellungsvorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="b89e8-107">The parameters supplied to the create job schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-108">Erstellen Sie einen Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b89e8-108">Create a job schedule.</span></span>  <span data-ttu-id="b89e8-109">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-109">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-110">Das Antwort-Modell für den Auftrag-Zeitplan Erstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-110">The response model for the create job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse&gt; CreateAsync (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse&gt; CreateAsync(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, class Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.CreateAsync(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateAsync (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, parameters As JobScheduleCreateParameters) As Task(Of JobScheduleCreateResponse)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.CreateAsync (operations, resourceGroupName, automationAccount, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleCreateResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Automation.Models.JobScheduleCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-111">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-111">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-112">Required.</span></span> <span data-ttu-id="b89e8-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-113">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-114">Required.</span></span> <span data-ttu-id="b89e8-115">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-115">The automation account name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="b89e8-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-116">Required.</span></span> <span data-ttu-id="b89e8-117">Die Parameter, die auf den Auftrag-Zeitplan Erstellungsvorgang angegeben.</span><span class="sxs-lookup"><span data-stu-id="b89e8-117">The parameters supplied to the create job schedule operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-118">Erstellen Sie einen Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="b89e8-118">Create a job schedule.</span></span>  <span data-ttu-id="b89e8-119">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-119">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-120">Das Antwort-Modell für den Auftrag-Zeitplan Erstellungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-120">The response model for the create job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse Delete (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Guid jobScheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse Delete(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobScheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Delete(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, jobScheduleName As Guid) As AzureOperationResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Guid -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Delete (operations, resourceGroupName, automationAccount, jobScheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobScheduleName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-121">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-121">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-122">Required.</span></span> <span data-ttu-id="b89e8-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-123">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-124">Required.</span></span> <span data-ttu-id="b89e8-125">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-125">The automation account name.</span></span>
            </param>
        <param name="jobScheduleName">
            <span data-ttu-id="b89e8-126">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-126">Required.</span></span> <span data-ttu-id="b89e8-127">Der Name des Auftrags planen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-127">The job schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-128">Löschen Sie den Auftragszeitplan Auftrag Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b89e8-128">Delete the job schedule identified by job schedule name.</span></span>  <span data-ttu-id="b89e8-129">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-129">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-130">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b89e8-130">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Guid jobScheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobScheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteAsync (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, jobScheduleName As Guid) As Task(Of AzureOperationResponse)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.DeleteAsync (operations, resourceGroupName, automationAccount, jobScheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobScheduleName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-131">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-131">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-132">Required.</span></span> <span data-ttu-id="b89e8-133">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-133">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-134">Required.</span></span> <span data-ttu-id="b89e8-135">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-135">The automation account name.</span></span>
            </param>
        <param name="jobScheduleName">
            <span data-ttu-id="b89e8-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-136">Required.</span></span> <span data-ttu-id="b89e8-137">Der Name des Auftrags planen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-137">The job schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-138">Löschen Sie den Auftragszeitplan Auftrag Zeitplan namentlich identifiziert.</span><span class="sxs-lookup"><span data-stu-id="b89e8-138">Delete the job schedule identified by job schedule name.</span></span>  <span data-ttu-id="b89e8-139">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-139">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-140">Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.</span><span class="sxs-lookup"><span data-stu-id="b89e8-140">A standard service response including an HTTP status code and request ID.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse Get (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Guid jobScheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse Get(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobScheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Get(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, jobScheduleName As Guid) As JobScheduleGetResponse" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Guid -&gt; Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.Get (operations, resourceGroupName, automationAccount, jobScheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobScheduleName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-141">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-141">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-142">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-142">Required.</span></span> <span data-ttu-id="b89e8-143">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-143">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-144">Required.</span></span> <span data-ttu-id="b89e8-145">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-145">The automation account name.</span></span>
            </param>
        <param name="jobScheduleName">
            <span data-ttu-id="b89e8-146">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-146">Required.</span></span> <span data-ttu-id="b89e8-147">Der Name des Auftrags planen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-147">The job schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-148">Abgerufen Sie den Zeitplanname Auftrag identifizierten Auftragszeitplan werden.</span><span class="sxs-lookup"><span data-stu-id="b89e8-148">Retrieve the job schedule identified by job schedule name.</span></span>  <span data-ttu-id="b89e8-149">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-149">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-150">Das Antwort-Modell für den Get Job Schedule-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-150">The response model for the get job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse&gt; GetAsync (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, Guid jobScheduleName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse&gt; GetAsync(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount, valuetype System.Guid jobScheduleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.GetAsync(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String,System.Guid)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetAsync (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String, jobScheduleName As Guid) As Task(Of JobScheduleGetResponse)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string * Guid -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.GetAsync (operations, resourceGroupName, automationAccount, jobScheduleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="jobScheduleName" Type="System.Guid" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-151">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-151">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-152">Required.</span></span> <span data-ttu-id="b89e8-153">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-153">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-154">Required.</span></span> <span data-ttu-id="b89e8-155">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-155">The automation account name.</span></span>
            </param>
        <param name="jobScheduleName">
            <span data-ttu-id="b89e8-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-156">Required.</span></span> <span data-ttu-id="b89e8-157">Der Name des Auftrags planen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-157">The job schedule name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-158">Abgerufen Sie den Zeitplanname Auftrag identifizierten Auftragszeitplan werden.</span><span class="sxs-lookup"><span data-stu-id="b89e8-158">Retrieve the job schedule identified by job schedule name.</span></span>  <span data-ttu-id="b89e8-159">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-159">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-160">Das Antwort-Modell für den Get Job Schedule-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-160">The response model for the get job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse List (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse List(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.List(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String) As JobScheduleListResponse" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string -&gt; Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.List (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-161">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-161">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-162">Required.</span></span> <span data-ttu-id="b89e8-163">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-163">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-164">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-164">Required.</span></span> <span data-ttu-id="b89e8-165">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-165">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-166">Rufen Sie eine Liste von Auftragszeitplänen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-166">Retrieve a list of job schedules.</span></span>  <span data-ttu-id="b89e8-167">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-167">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-168">Das Antwort-Modell für die Auftrag-Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-168">The response model for the list job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt; ListAsync (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt; ListAsync(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string resourceGroupName, string automationAccount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListAsync(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAsync (operations As IJobScheduleOperations, resourceGroupName As String, automationAccount As String) As Task(Of JobScheduleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListAsync (operations, resourceGroupName, automationAccount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-169">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-169">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="b89e8-170">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-170">Required.</span></span> <span data-ttu-id="b89e8-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="b89e8-171">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="b89e8-172">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-172">Required.</span></span> <span data-ttu-id="b89e8-173">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="b89e8-173">The automation account name.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-174">Rufen Sie eine Liste von Auftragszeitplänen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-174">Retrieve a list of job schedules.</span></span>  <span data-ttu-id="b89e8-175">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-175">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-176">Das Antwort-Modell für die Auftrag-Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-176">The response model for the list job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse ListNext (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse ListNext(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListNext(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobScheduleOperations, nextLink As String) As JobScheduleListResponse" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string -&gt; Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListNext (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-177">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-177">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b89e8-178">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-178">Required.</span></span> <span data-ttu-id="b89e8-179">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-179">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-180">Abrufen von weiter Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-180">Retrieve next list of schedules.</span></span>  <span data-ttu-id="b89e8-181">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-181">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-182">Das Antwort-Modell für die Auftrag-Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-182">The response model for the list job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt; ListNextAsync (this Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string nextLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt; ListNextAsync(class Microsoft.Azure.Management.Automation.IJobScheduleOperations operations, string nextLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Automation.IJobScheduleOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNextAsync (operations As IJobScheduleOperations, nextLink As String) As Task(Of JobScheduleListResponse)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Automation.IJobScheduleOperations * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt;" Usage="Microsoft.Azure.Management.Automation.JobScheduleOperationsExtensions.ListNextAsync (operations, nextLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.JobScheduleListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Automation.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="b89e8-183">Verweis auf die Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span><span class="sxs-lookup"><span data-stu-id="b89e8-183">Reference to the Microsoft.Azure.Management.Automation.IJobScheduleOperations.</span></span>
            </param>
        <param name="nextLink">
            <span data-ttu-id="b89e8-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="b89e8-184">Required.</span></span> <span data-ttu-id="b89e8-185">Der Link zum Abrufen des nächsten Satzes von Elementen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-185">The link to retrieve next set of items.</span></span>
            </param>
        <summary>
            <span data-ttu-id="b89e8-186">Abrufen von weiter Liste auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="b89e8-186">Retrieve next list of schedules.</span></span>  <span data-ttu-id="b89e8-187">(siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="b89e8-187">(see http://aka.ms/azureautomationsdk/jobscheduleoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="b89e8-188">Das Antwort-Modell für die Auftrag-Zeitplan Auflistungsvorgang.</span><span class="sxs-lookup"><span data-stu-id="b89e8-188">The response model for the list job schedule operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>