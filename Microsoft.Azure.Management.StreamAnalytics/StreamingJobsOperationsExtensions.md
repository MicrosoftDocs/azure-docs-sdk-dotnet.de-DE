<Type Name="StreamingJobsOperationsExtensions" FullName="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class StreamingJobsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit StreamingJobsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module StreamingJobsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type StreamingJobsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="291a1-101">Erweiterungsmethoden für StreamingJobsOperations.</span><span class="sxs-lookup"><span data-stu-id="291a1-101">Extension methods for StreamingJobsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob BeginCreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-102">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-103">Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-103">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-104">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-104">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-105">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-105">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-106">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-106">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-107">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-107">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-108">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-108">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-109">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-109">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="291a1-110">Legen Sie auf "\*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="291a1-110">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="291a1-111">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-111">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-112">Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="291a1-112">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; BeginCreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginCreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginCreateOrReplaceAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-113">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-113">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-114">Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-114">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-115">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-115">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-116">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-116">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-117">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-117">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-118">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-118">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-119">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-119">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-120">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-120">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="291a1-121">Legen Sie auf "\*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="291a1-121">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="291a1-122">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-122">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-123">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-123">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-124">Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="291a1-124">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDelete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-125">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-126">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-126">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-127">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-127">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-128">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-128">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-129">Löscht eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-129">Deletes a streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-130">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-131">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-131">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-132">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-132">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-133">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-133">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-135">Löscht eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-135">Deletes a streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static void BeginStart (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStart(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStart (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStart (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-136">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-137">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-137">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-138">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-138">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-139">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-139">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="291a1-140">Parameter für einen Einstieg streaming Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="291a1-140">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-141">Startet eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-141">Starts a streaming job.</span></span> <span data-ttu-id="291a1-142">Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.</span><span class="sxs-lookup"><span data-stu-id="291a1-142">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStartAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-143">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-144">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-144">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-145">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-145">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-146">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-146">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="291a1-147">Parameter für einen Einstieg streaming Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="291a1-147">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-148">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-148">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-149">Startet eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-149">Starts a streaming job.</span></span> <span data-ttu-id="291a1-150">Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.</span><span class="sxs-lookup"><span data-stu-id="291a1-150">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStop">
      <MemberSignature Language="C#" Value="public static void BeginStop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginStop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginStop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member BeginStop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-151">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-152">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-152">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-153">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-153">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-154">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-154">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-155">Beendet einen laufenden streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-155">Stops a running streaming job.</span></span> <span data-ttu-id="291a1-156">Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="291a1-156">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginStopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginStopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.BeginStopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;BeginStopAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-157">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-158">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-158">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-159">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-159">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-160">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-160">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-161">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-161">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-162">Beendet einen laufenden streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-162">Stops a running streaming job.</span></span> <span data-ttu-id="291a1-163">Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="291a1-163">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplace">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob CreateOrReplace(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplace : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplace (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-164">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-165">Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-165">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-166">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-166">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-167">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-167">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-168">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-168">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-169">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-169">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-170">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-170">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-171">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-171">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="291a1-172">Legen Sie auf "\*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="291a1-172">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="291a1-173">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-173">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-174">Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="291a1-174">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrReplaceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, string ifNoneMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; CreateOrReplaceAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, string ifNoneMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrReplaceAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.CreateOrReplaceAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, ifNoneMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;CreateOrReplaceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="ifNoneMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-175">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-176">Die Definition des streamingauftrags, die zum Erstellen eines neuen streamingauftrags oder Ersetzen der vorhandenen Dateigruppe verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-176">The definition of the streaming job that will be used to create a new streaming job or replace the existing one.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-177">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-177">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-178">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-178">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-179">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-179">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-180">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-180">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-181">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-181">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-182">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-182">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="ifNoneMatch">
            <span data-ttu-id="291a1-183">Legen Sie auf "\*" damit wird eine neue streamingauftrag erstellt werden, aber um zu verhindern, aktualisieren eine vorhandene Satz aufzeichnen.</span><span class="sxs-lookup"><span data-stu-id="291a1-183">Set to '\*' to allow a new streaming job to be created, but to prevent updating an existing record set.</span></span> <span data-ttu-id="291a1-184">Andere Werte führt 412 Antwort vor Bedingung fehlerhaft ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-184">Other values will result in a 412 Pre-condition Failed response.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-185">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-185">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-186">Ein streaming-Auftrags erstellt oder eine bereits vorhandene streamingauftrag ersetzt.</span><span class="sxs-lookup"><span data-stu-id="291a1-186">Creates a streaming job or replaces an already existing streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Delete (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-187">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-188">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-188">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-189">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-189">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-190">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-190">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-191">Löscht eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-191">Deletes a streaming job.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.DeleteAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-192">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-193">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-193">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-194">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-194">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-195">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-195">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-196">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-196">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-197">Löscht eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-197">Deletes a streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Get(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional expand As String = null) As StreamingJob" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Get (operations, resourceGroupName, jobName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-198">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-199">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-199">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-200">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-200">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-201">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-201">The name of the streaming job.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-202">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-202">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-203">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-203">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-204">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-204">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-205">Ruft Details zu dem angegebenen streaming-Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="291a1-205">Gets details about the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; GetAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.GetAsync (operations, resourceGroupName, jobName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-206">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-207">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-207">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-208">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-208">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-209">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-209">The name of the streaming job.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-210">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-210">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-211">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-211">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-212">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-212">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-213">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-213">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-214">Ruft Details zu dem angegebenen streaming-Auftrags ab.</span><span class="sxs-lookup"><span data-stu-id="291a1-214">Gets details about the specified streaming job.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; List(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IStreamingJobsOperations, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.List (operations, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-215">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-215">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-216">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-216">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-217">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-217">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-218">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-218">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-219">Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="291a1-219">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListAsync (operations, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-220">The operations group for this extension method.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-221">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-221">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-222">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-222">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-223">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-223">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-224">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-224">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-225">Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="291a1-225">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroup">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroup(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroup (operations As IStreamingJobsOperations, resourceGroupName As String, Optional expand As String = null) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroup : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroup (operations, resourceGroupName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-226">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-226">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-227">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-227">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-228">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-228">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-229">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-229">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-230">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-230">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-231">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-231">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-232">Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="291a1-232">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupAsync (operations, resourceGroupName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-233">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-233">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-234">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-234">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-235">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-235">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="expand">
            <span data-ttu-id="291a1-236">Die $expand-OData-Abfrageparameter.</span><span class="sxs-lookup"><span data-stu-id="291a1-236">The $expand OData query parameter.</span></span> <span data-ttu-id="291a1-237">Dies ist eine durch Trennzeichen getrennte Liste der zusätzlichen streaming Auftragseigenschaften einschließen, die in der Antwort, jenseits der Standardgrenze zurückgegebenen festgelegt, wenn dieser Parameter nicht vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="291a1-237">This is a comma-separated list of additional streaming job properties to include in the response, beyond the default set returned when this parameter is absent.</span></span> <span data-ttu-id="291a1-238">Standardmäßig ist streaming Auftragseigenschaften als "Eingaben", "Transformation", "Ausgaben" und "Funktionen".</span><span class="sxs-lookup"><span data-stu-id="291a1-238">The default set is all streaming job properties other than 'inputs', 'transformation', 'outputs', and 'functions'.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-239">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-239">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-240">Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="291a1-240">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListByResourceGroupNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResourceGroupNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-241">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-241">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="291a1-242">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="291a1-242">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-243">Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="291a1-243">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceGroupNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListByResourceGroupNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceGroupNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListByResourceGroupNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListByResourceGroupNextAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-244">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-244">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="291a1-245">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="291a1-245">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-246">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-246">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-247">Zeigt eine Liste aller streaming Aufträge in der angegebenen Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="291a1-247">Lists all of the streaming jobs in the specified resource group.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; ListNext(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IStreamingJobsOperations, nextPageLink As String) As IPage(Of StreamingJob)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-248">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-248">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="291a1-249">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="291a1-249">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-250">Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="291a1-250">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;ListNextAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-251">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-251">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="291a1-252">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="291a1-252">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-253">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-253">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-254">Zeigt eine Liste aller der datenstromauftrag im angegebenen Abonnement.</span><span class="sxs-lookup"><span data-stu-id="291a1-254">Lists all of the streaming jobs in the given subscription.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static void Start (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Start(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Start (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String, Optional startJobParameters As StartStreamingJobParameters = null)" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Start (operations, resourceGroupName, jobName, startJobParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-255">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-255">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-256">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-256">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-257">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-257">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-258">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-258">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="291a1-259">Parameter für einen Einstieg streaming Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="291a1-259">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-260">Startet eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-260">Starts a streaming job.</span></span> <span data-ttu-id="291a1-261">Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.</span><span class="sxs-lookup"><span data-stu-id="291a1-261">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StartAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StartAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, class Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters startJobParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StartAsync (operations, resourceGroupName, jobName, startJobParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StartAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="startJobParameters" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-262">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-262">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-263">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-263">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-264">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-264">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-265">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-265">The name of the streaming job.</span></span>
            </param>
        <param name="startJobParameters">
            <span data-ttu-id="291a1-266">Parameter für einen Einstieg streaming Job-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="291a1-266">Parameters applicable to a start streaming job operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-267">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-268">Startet eine streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-268">Starts a streaming job.</span></span> <span data-ttu-id="291a1-269">Nachdem ein Auftrag gestartet wird sie beginnt mit der Verarbeitung der Eingabeereignisse und Ausgabe erzeugt.</span><span class="sxs-lookup"><span data-stu-id="291a1-269">Once a job is started it will start processing input events and produce output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public static void Stop (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Stop(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Stop (operations As IStreamingJobsOperations, resourceGroupName As String, jobName As String)" />
      <MemberSignature Language="F#" Value="static member Stop : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Stop (operations, resourceGroupName, jobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-270">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-270">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-271">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-271">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-272">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-272">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-273">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-273">The name of the streaming job.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-274">Beendet einen laufenden streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-274">Stops a running streaming job.</span></span> <span data-ttu-id="291a1-275">Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="291a1-275">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task StopAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task StopAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, string resourceGroupName, string jobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StopAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.StopAsync (operations, resourceGroupName, jobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;StopAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-276">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-276">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-277">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-277">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-278">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-278">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-279">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-279">The name of the streaming job.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-280">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-280">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-281">Beendet einen laufenden streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-281">Stops a running streaming job.</span></span> <span data-ttu-id="291a1-282">Dies bewirkt einen gerade ausgeführten streaming-Auftrag zum Beenden der Verarbeitung der Eingabeereignisse und Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="291a1-282">This will cause a running streaming job to stop processing input events and producing output.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob Update(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.Update (operations, streamingJob, resourceGroupName, jobName, ifMatch)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-283">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-283">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-284">Ein streaming Job-Objekt.</span><span class="sxs-lookup"><span data-stu-id="291a1-284">A streaming job object.</span></span> <span data-ttu-id="291a1-285">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen streamingauftrag (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="291a1-285">The properties specified here will overwrite the corresponding properties in the existing streaming job (ie. Those properties will be updated).</span></span> <span data-ttu-id="291a1-286">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.</span><span class="sxs-lookup"><span data-stu-id="291a1-286">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-287">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-287">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-288">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-288">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-289">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-289">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-290">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-290">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-291">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-291">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-292">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-292">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-293">Aktualisiert eine vorhandene streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-293">Updates an existing streaming job.</span></span> <span data-ttu-id="291a1-294">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="291a1-294">This can be used to partially update (ie.</span></span> <span data-ttu-id="291a1-295">Aktualisieren Sie eine oder zwei Eigenschaften) einen streamingauftrag ohne den Rest der Auftragsdefinition.</span><span class="sxs-lookup"><span data-stu-id="291a1-295">update one or two properties) a streaming job without affecting the rest the job definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync (this Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt; UpdateAsync(class Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations operations, class Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob streamingJob, string resourceGroupName, string jobName, string ifMatch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations,Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations * Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions.UpdateAsync (operations, streamingJob, resourceGroupName, jobName, ifMatch, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StreamAnalytics.StreamingJobsOperationsExtensions/&lt;UpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StreamAnalytics.IStreamingJobsOperations" RefType="this" />
        <Parameter Name="streamingJob" Type="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="jobName" Type="System.String" />
        <Parameter Name="ifMatch" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="291a1-296">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="291a1-296">The operations group for this extension method.</span></span>
            </param>
        <param name="streamingJob">
            <span data-ttu-id="291a1-297">Ein streaming Job-Objekt.</span><span class="sxs-lookup"><span data-stu-id="291a1-297">A streaming job object.</span></span> <span data-ttu-id="291a1-298">Die Eigenschaften, die hier angegebene überschreibt die entsprechenden Eigenschaften in der vorhandenen streamingauftrag (d. h. Diese Eigenschaften werden aktualisiert).</span><span class="sxs-lookup"><span data-stu-id="291a1-298">The properties specified here will overwrite the corresponding properties in the existing streaming job (ie. Those properties will be updated).</span></span> <span data-ttu-id="291a1-299">Alle Eigenschaften, die werden auf null festgelegt, hier bedeutet, dass die entsprechende Eigenschaft in der vorhandenen Eingabe identisch bleibt und nicht als Ergebnis dieser PATCH-Vorgang geändert.</span><span class="sxs-lookup"><span data-stu-id="291a1-299">Any properties that are set to null here will mean that the corresponding property in the existing input will remain the same and not change as a result of this PATCH operation.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="291a1-300">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="291a1-300">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="291a1-301">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="291a1-301">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="jobName">
            <span data-ttu-id="291a1-302">Der Name des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-302">The name of the streaming job.</span></span>
            </param>
        <param name="ifMatch">
            <span data-ttu-id="291a1-303">Das ETag des streamingauftrags.</span><span class="sxs-lookup"><span data-stu-id="291a1-303">The ETag of the streaming job.</span></span> <span data-ttu-id="291a1-304">Lassen Sie diesen Wert, um die aktuellen Ressourceneintragssatz immer überschrieben.</span><span class="sxs-lookup"><span data-stu-id="291a1-304">Omit this value to always overwrite the current record set.</span></span> <span data-ttu-id="291a1-305">Geben Sie die letzten gesehen ETag-Wert um versehentlich Overwritting gleichzeitige Änderungen zu verhindern.</span><span class="sxs-lookup"><span data-stu-id="291a1-305">Specify the last-seen ETag value to prevent accidentally overwritting concurrent changes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="291a1-306">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="291a1-306">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="291a1-307">Aktualisiert eine vorhandene streaming-Auftrags an.</span><span class="sxs-lookup"><span data-stu-id="291a1-307">Updates an existing streaming job.</span></span> <span data-ttu-id="291a1-308">Dies kann verwendet werden, aktualisieren Sie teilweise (d. h.</span><span class="sxs-lookup"><span data-stu-id="291a1-308">This can be used to partially update (ie.</span></span> <span data-ttu-id="291a1-309">Aktualisieren Sie eine oder zwei Eigenschaften) einen streamingauftrag ohne den Rest der Auftragsdefinition.</span><span class="sxs-lookup"><span data-stu-id="291a1-309">update one or two properties) a streaming job without affecting the rest the job definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>