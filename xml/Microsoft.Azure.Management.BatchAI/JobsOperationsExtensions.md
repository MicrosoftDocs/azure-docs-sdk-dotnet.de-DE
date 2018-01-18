<Type Name="JobsOperationsExtensions" FullName="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="484ef-101">Erweiterungsmethoden für JobsOperations.</span><span class="sxs-lookup"><span data-stu-id="484ef-101">Extension methods for JobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job BeginCreate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job BeginCreate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IJobsOperations, resourceGroupName As String, jobName As String, parameters As JobCreateParameters) As Job" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreate (operations, resourceGroupName, jobName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-103">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-103">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-104">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-104">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-105">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-105">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-106">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-106">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="484ef-107">Die Parameter für die auftragserstellung bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="484ef-107">The parameters to provide for job creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-108">Fügt einen Auftrag, der auf einem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="484ef-108">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; BeginCreateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; BeginCreateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginCreateAsync (operations, resourceGroupName, jobName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginCreateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-109">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-110">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-110">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-111">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-111">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-112">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-112">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-113">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-113">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="484ef-114">Die Parameter für die auftragserstellung bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="484ef-114">The parameters to provide for job creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-116">Fügt einen Auftrag, der auf einem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="484ef-116">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-117">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-118">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-118">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-119">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-119">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-120">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-120">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-121">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-121">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-122">Löscht den angegebenen Batch AI-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="484ef-122">Deletes the specified Batch AI job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-123">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-124">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-124">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-125">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-125">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-126">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-126">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-127">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-127">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-129">Löscht den angegebenen Batch AI-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="484ef-129">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTerminate">
      <MemberSignature Language="C#" Value="public static void BeginTerminate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginTerminate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginTerminate (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginTerminate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminate (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-131">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-131">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-132">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-132">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-133">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-133">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-134">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-134">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-135">Einen Auftrag wird beendet.</span><span class="sxs-lookup"><span data-stu-id="484ef-135">Terminates a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginTerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginTerminateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginTerminateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginTerminateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.BeginTerminateAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;BeginTerminateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-137">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-137">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-138">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-138">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-139">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-139">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-140">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-140">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-141">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-141">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-142">Einen Auftrag wird beendet.</span><span class="sxs-lookup"><span data-stu-id="484ef-142">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job Create (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job Create(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Create(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IJobsOperations, resourceGroupName As String, jobName As String, parameters As JobCreateParameters) As Job" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Create (operations, resourceGroupName, jobName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-144">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-144">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-145">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-145">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-146">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-146">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-147">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-147">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="484ef-148">Die Parameter für die auftragserstellung bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="484ef-148">The parameters to provide for job creation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-149">Fügt einen Auftrag, der auf einem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="484ef-149">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; CreateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; CreateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.CreateAsync (operations, resourceGroupName, jobName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;CreateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.BatchAI.Models.JobCreateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-150">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-151">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-151">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-152">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-152">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-153">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-153">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-154">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-154">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="484ef-155">Die Parameter für die auftragserstellung bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="484ef-155">The parameters to provide for job creation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-157">Fügt einen Auftrag, der auf einem Cluster ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="484ef-157">Adds a Job that gets executed on a cluster.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Delete(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-158">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-159">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-159">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-160">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-160">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-161">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-161">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-162">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-162">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-163">Löscht den angegebenen Batch AI-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="484ef-163">Deletes the specified Batch AI job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-164">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-165">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-165">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-166">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-166">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-167">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-167">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-168">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-168">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-170">Löscht den angegebenen Batch AI-Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="484ef-170">Deletes the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.BatchAI.Models.Job Get (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.BatchAI.Models.Job Get(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Get(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IJobsOperations, resourceGroupName As String, jobName As String) As Job" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.Job" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Get (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.Job</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-171">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-172">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-172">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-173">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-173">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-174">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-174">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-175">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-175">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-176">Ruft Informationen über den angegebenen Batch AI-Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="484ef-176">Gets information about the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; GetAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; GetAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-177">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-177">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-178">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-178">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-179">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-179">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-180">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-180">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-181">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-181">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-182">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-182">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-183">Ruft Informationen über den angegebenen Batch AI-Auftrag ab.</span><span class="sxs-lookup"><span data-stu-id="484ef-183">Gets information about the specified Batch AI job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; List (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; List(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, class Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.List(Microsoft.Azure.Management.BatchAI.IJobsOperations,Microsoft.Azure.Management.BatchAI.Models.JobsListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.BatchAI.IJobsOperations * Microsoft.Azure.Management.BatchAI.Models.JobsListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.List (operations, jobsListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="jobsListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-184">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-184">The operations group for this extension method.</span></span>
            </param>
        <param name="jobsListOptions">
            <span data-ttu-id="484ef-185">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-185">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-186">Ruft Informationen zu den Aufträgen, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="484ef-186">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, class Microsoft.Azure.Management.BatchAI.Models.JobsListOptions jobsListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,Microsoft.Azure.Management.BatchAI.Models.JobsListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * Microsoft.Azure.Management.BatchAI.Models.JobsListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListAsync (operations, jobsListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="jobsListOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-187">The operations group for this extension method.</span></span>
            </param>
        <param name="jobsListOptions">
            <span data-ttu-id="484ef-188">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-188">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-190">Ruft Informationen zu den Aufträgen, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="484ef-190">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroup (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroup(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, jobsListByResourceGroupOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobsListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-191">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-192">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-192">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobsListByResourceGroupOptions">
            <span data-ttu-id="484ef-193">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-193">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-194">Ruft Informationen zu den Batch AI-Aufträgen, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="484ef-194">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, class Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions jobsListByResourceGroupOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, jobsListByResourceGroupOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobsListByResourceGroupOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListByResourceGroupOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-195">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-196">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-196">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobsListByResourceGroupOptions">
            <span data-ttu-id="484ef-197">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-197">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-198">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-198">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-199">Ruft Informationen zu den Batch AI-Aufträgen, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="484ef-199">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-200">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-200">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-201">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-201">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-202">Ruft Informationen zu den Batch AI-Aufträgen, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="484ef-202">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-203">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-203">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-204">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-204">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-205">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-205">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-206">Ruft Informationen zu den Batch AI-Aufträgen, die innerhalb der angegebenen Ressourcengruppe verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="484ef-206">Gets information about the Batch AI jobs associated within the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt; ListNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of Job)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-207">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-207">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-208">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-208">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-209">Ruft Informationen zu den Aufträgen, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="484ef-209">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.Job&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-210">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-211">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-211">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-212">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-212">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-213">Ruft Informationen zu den Aufträgen, die dem Abonnement zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="484ef-213">Gets information about the jobs associated with the subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFiles">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFiles (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFiles(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFiles(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions)" />
      <MemberSignature Language="F#" Value="static member ListOutputFiles : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFiles (operations, resourceGroupName, jobName, jobsListOutputFilesOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="jobsListOutputFilesOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-214">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-214">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-215">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-215">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-216">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-216">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-217">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-217">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-218">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-218">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="jobsListOutputFilesOptions">
            <span data-ttu-id="484ef-219">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-219">Additional parameters for the operation</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-220">Listen Sie alle Dateien im angegebenen Ausgabeverzeichnis (nur, wenn das Ausgabeverzeichnis für Azure-Dateifreigabe oder Azure Storage-Container ist).</span><span class="sxs-lookup"><span data-stu-id="484ef-220">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions jobsListOutputFilesOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesAsync (operations, resourceGroupName, jobName, jobsListOutputFilesOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListOutputFilesAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="jobsListOutputFilesOptions" Type="Microsoft.Azure.Management.BatchAI.Models.JobsListOutputFilesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-221">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-221">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-222">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-222">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-223">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-223">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-224">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-224">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-225">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-225">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="jobsListOutputFilesOptions">
            <span data-ttu-id="484ef-226">Zusätzliche Parameter für den Vorgang</span><span class="sxs-lookup"><span data-stu-id="484ef-226">Additional parameters for the operation</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-227">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-227">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-228">Listen Sie alle Dateien im angegebenen Ausgabeverzeichnis (nur, wenn das Ausgabeverzeichnis für Azure-Dateifreigabe oder Azure Storage-Container ist).</span><span class="sxs-lookup"><span data-stu-id="484ef-228">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFilesNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt; ListOutputFilesNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListOutputFilesNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of File)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-229">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-229">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-230">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-230">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-231">Listen Sie alle Dateien im angegebenen Ausgabeverzeichnis (nur, wenn das Ausgabeverzeichnis für Azure-Dateifreigabe oder Azure Storage-Container ist).</span><span class="sxs-lookup"><span data-stu-id="484ef-231">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListOutputFilesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt; ListOutputFilesNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListOutputFilesNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListOutputFilesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListOutputFilesNextAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.File&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-232">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-232">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-233">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-233">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-234">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-234">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-235">Listen Sie alle Dateien im angegebenen Ausgabeverzeichnis (nur, wenn das Ausgabeverzeichnis für Azure-Dateifreigabe oder Azure Storage-Container ist).</span><span class="sxs-lookup"><span data-stu-id="484ef-235">List all files inside the given output directory (Only if the output directory is on Azure File Share or Azure Storage container).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformation">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformation(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformation(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformation (operations As IJobsOperations, resourceGroupName As String, jobName As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformation : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformation (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-236">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-236">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-237">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-237">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-238">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-238">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-239">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-239">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-240">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-240">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-241">Ruft die IP-Adresse und Anschlussnummer Informationen von den Compute-Knoten die für die Ausführung eines Auftrags verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="484ef-241">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListRemoteLoginInformationAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-242">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-242">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-243">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-243">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-244">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-244">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-245">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-245">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-246">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-246">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-247">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-247">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-248">Ruft die IP-Adresse und Anschlussnummer Informationen von den Compute-Knoten die für die Ausführung eines Auftrags verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="484ef-248">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt; ListRemoteLoginInformationNext(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNext(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRemoteLoginInformationNext (operations As IJobsOperations, nextPageLink As String) As IPage(Of RemoteLoginInformation)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNext : Microsoft.Azure.Management.BatchAI.IJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-249">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-249">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-250">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-250">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-251">Ruft die IP-Adresse und Anschlussnummer Informationen von den Compute-Knoten die für die Ausführung eines Auftrags verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="484ef-251">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRemoteLoginInformationNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt; ListRemoteLoginInformationNextAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNextAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRemoteLoginInformationNextAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.ListRemoteLoginInformationNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;ListRemoteLoginInformationNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.BatchAI.Models.RemoteLoginInformation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-252">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="484ef-253">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="484ef-253">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-254">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-254">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-255">Ruft die IP-Adresse und Anschlussnummer Informationen von den Compute-Knoten die für die Ausführung eines Auftrags verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="484ef-255">Gets the IP address and port information of all the compute nodes which are used for job execution.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static void Terminate (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Terminate(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Terminate(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Terminate (operations As IJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.Terminate (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-256">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-256">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-257">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-257">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-258">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-258">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-259">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-259">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-260">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-260">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-261">Einen Auftrag wird beendet.</span><span class="sxs-lookup"><span data-stu-id="484ef-261">Terminates a job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task TerminateAsync (this Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task TerminateAsync(class Microsoft.Azure.Management.BatchAI.IJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.TerminateAsync(Microsoft.Azure.Management.BatchAI.IJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Management.BatchAI.IJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions.TerminateAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.BatchAI.JobsOperationsExtensions/&lt;TerminateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.BatchAI.IJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="484ef-262">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="484ef-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="484ef-263">Der Name der Ressourcengruppe, zu der die Ressource gehört.</span><span class="sxs-lookup"><span data-stu-id="484ef-263">Name of the resource group to which the resource belongs.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="484ef-264">Der Name des Auftrags innerhalb der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="484ef-264">The name of the job within the specified resource group.</span></span> <span data-ttu-id="484ef-265">Auftragsnamen können nur eine Kombination aus alphanumerischen Zeichen sowie Bindestriche (-) und Unterstrich (_) enthalten.</span><span class="sxs-lookup"><span data-stu-id="484ef-265">Job names can only contain a combination of alphanumeric characters along with dash (-) and underscore (_).</span></span> <span data-ttu-id="484ef-266">Der Name muss zwischen 1 und 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="484ef-266">The name must be from 1 through 64 characters long.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="484ef-267">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="484ef-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="484ef-268">Einen Auftrag wird beendet.</span><span class="sxs-lookup"><span data-stu-id="484ef-268">Terminates a job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>