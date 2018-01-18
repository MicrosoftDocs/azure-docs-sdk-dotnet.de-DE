<Type Name="JobScheduleOperations" FullName="Microsoft.Azure.Batch.JobScheduleOperations">
  <TypeSignature Language="C#" Value="public class JobScheduleOperations : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleOperations extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobScheduleOperations" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleOperations&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type JobScheduleOperations = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cbbc8-101">Führt Vorgänge für Azure Batch-Auftragszeitpläne.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-101">Performs operations on Azure Batch job schedules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
    <altmember cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />
  </Docs>
  <Members>
    <Member MemberName="CreateJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.CreateJobSchedule" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateJobSchedule () As CloudJobSchedule" />
      <MemberSignature Language="F#" Value="member this.CreateJobSchedule : unit -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.CreateJobSchedule " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="cbbc8-102">Erstellt eine Instanz des CloudJobSchedule, die entfernt wird, und verfügt nicht über eine Beziehung Konsistenz auf jeden Auftragszeitplan in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-102">Creates an instance of CloudJobSchedule that is unbound and does not have a consistency relationship to any job schedule in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-103">Ein <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> , einen neuen Auftragszeitplan, die nicht übermittelt wurden, des Batch-Diensts darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-103">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> representing a new job schedule that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule (string jobScheduleId, Microsoft.Azure.Batch.Schedule schedule, Microsoft.Azure.Batch.JobSpecification jobSpecification);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule CreateJobSchedule(string jobScheduleId, class Microsoft.Azure.Batch.Schedule schedule, class Microsoft.Azure.Batch.JobSpecification jobSpecification) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.CreateJobSchedule(System.String,Microsoft.Azure.Batch.Schedule,Microsoft.Azure.Batch.JobSpecification)" />
      <MemberSignature Language="F#" Value="member this.CreateJobSchedule : string * Microsoft.Azure.Batch.Schedule * Microsoft.Azure.Batch.JobSpecification -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.CreateJobSchedule (jobScheduleId, schedule, jobSpecification)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="schedule" Type="Microsoft.Azure.Batch.Schedule" />
        <Parameter Name="jobSpecification" Type="Microsoft.Azure.Batch.JobSpecification" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-104">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-104">The id of the job schedule.</span></span></param>
        <param name="schedule"><span data-ttu-id="cbbc8-105">Der Zeitplan, der bestimmt, wann die Aufträge erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-105">The schedule that determines when jobs will be created.</span></span></param>
        <param name="jobSpecification"><span data-ttu-id="cbbc8-106">eine <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> mit Details zu den Aufträgen gemäß erstellt werden die <paramref name="schedule" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-106">a <see cref="T:Microsoft.Azure.Batch.JobSpecification" /> containing details of the jobs to be created according to the <paramref name="schedule" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-107">Erstellt eine Instanz des CloudJobSchedule, die entfernt wird, und verfügt nicht über eine Beziehung Konsistenz auf jeden Auftragszeitplan in der Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-107">Creates an instance of CloudJobSchedule that is unbound and does not have a consistency relationship to any job schedule in the Batch Service.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-108">Ein <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> , einen neuen Auftragszeitplan, die nicht übermittelt wurden, des Batch-Diensts darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-108">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> representing a new job schedule that has not been submitted to the Batch service.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cbbc8-109">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.JobScheduleOperations" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-109">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.JobScheduleOperations" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="cbbc8-110">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-110">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="cbbc8-111">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-111">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="cbbc8-112">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-112">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobSchedule">
      <MemberSignature Language="C#" Value="public void DeleteJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DeleteJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DeleteJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.DeleteJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-113">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-113">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-114">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-114">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-115">Löscht den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-115">Deletes the specified job schedule.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="cbbc8-116">Der Löschvorgang fordert, dass der Auftragszeitplan gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-116">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="cbbc8-117">Die Anforderung legt den Zeitplan in das <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-117">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="cbbc8-118">Der Batch-Dienst löscht alle vorhandenen Aufträge und Aufgaben des Zeitplans für die Sie alle aktiven Aufträge einschließlich und das tatsächliche Auftrag Zeitplan löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-118">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="cbbc8-119">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-119">This is a blocking operation.</span></span> <span data-ttu-id="cbbc8-120">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-120">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DeleteJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.DeleteJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;DeleteJobScheduleAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-121">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-121">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-122">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-122">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cbbc8-123">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-123">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-124">Löscht den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-124">Deletes the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-125">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-125">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="cbbc8-126">Der Löschvorgang fordert, dass der Auftragszeitplan gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-126">The delete operation requests that the job schedule be deleted.</span></span>  <span data-ttu-id="cbbc8-127">Die Anforderung legt den Zeitplan in das <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-127">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Deleting" /> state.</span></span>
            <span data-ttu-id="cbbc8-128">Der Batch-Dienst löscht alle vorhandenen Aufträge und Aufgaben des Zeitplans für die Sie alle aktiven Aufträge einschließlich und das tatsächliche Auftrag Zeitplan löschen, ohne weitere Clientaktion ausführen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-128">The Batch service will delete any existing jobs and tasks under the schedule, including any active job, and perform the actual job schedule deletion without any further client action.</span></span></para>
          <para><span data-ttu-id="cbbc8-129">Der Löschvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-129">The delete operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobSchedule">
      <MemberSignature Language="C#" Value="public void DisableJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void DisableJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub DisableJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.DisableJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.DisableJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-130">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-130">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-131">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-131">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-132">Deaktiviert den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-132">Disables the specified job schedule.</span></span>  <span data-ttu-id="cbbc8-133">Deaktivierte Zeitpläne keine neuen Aufträge erstellen, aber möglicherweise erneut aktiviert werden weiter unten.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-133">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="cbbc8-134">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-134">This is a blocking operation.</span></span> <span data-ttu-id="cbbc8-135">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-135">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
          <para><span data-ttu-id="cbbc8-136">Um den Zeitplan erneut zu aktivieren, rufen <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-136">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DisableJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DisableJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.DisableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DisableJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.DisableJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-137">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-137">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-138">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-138">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cbbc8-139">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-139">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-140">Deaktiviert den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-140">Disables the specified job schedule.</span></span>  <span data-ttu-id="cbbc8-141">Deaktivierte Zeitpläne keine neuen Aufträge erstellen, aber möglicherweise erneut aktiviert werden weiter unten.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-141">Disabled schedules do not create new jobs, but may be re-enabled later.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-142">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-142">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="cbbc8-143">Der Deaktivierungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-143">The disable operation runs asynchronously.</span></span></para>
          <para><span data-ttu-id="cbbc8-144">Um den Zeitplan erneut zu aktivieren, rufen <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-144">To re-enable the schedule, call <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobSchedule">
      <MemberSignature Language="C#" Value="public void EnableJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void EnableJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub EnableJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.EnableJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.EnableJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-145">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-145">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-146">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-146">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-147">Ermöglicht den angegebenen Auftragszeitplan, sodass Aufträge gemäß erstellt werden seine <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-147">Enables the specified job schedule, allowing jobs to be created according to its <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="cbbc8-148">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-148">This is a blocking operation.</span></span> <span data-ttu-id="cbbc8-149">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-149">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task EnableJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task EnableJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.EnableJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.EnableJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.EnableJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-150">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-150">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-151">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-151">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cbbc8-152">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-152">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-153">Ermöglicht den angegebenen Auftragszeitplan, sodass Aufträge gemäß erstellt werden seine <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-153">Enables the specified job schedule, allowing jobs to be created according to its <see cref="P:Microsoft.Azure.Batch.CloudJobSchedule.Schedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-154">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-154">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="cbbc8-155">Der Aktivierungsvorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-155">The enable operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobSchedule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CloudJobSchedule GetJobSchedule (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.CloudJobSchedule GetJobSchedule(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobSchedule(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.GetJobSchedule : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.CloudJobSchedule" Usage="jobScheduleOperations.GetJobSchedule (jobScheduleId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-156">Die Id des Auftragszeitplans zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-156">The id of the job schedule to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="cbbc8-157">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-157">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-158">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-158">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-159">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> ab.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-159">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-160">Ein <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> mit Informationen über die angegebene Azure Batch-Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-160">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> containing information about the specified Azure Batch job schedule.</span></span></returns>
        <remarks><span data-ttu-id="cbbc8-161">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-161">This is a blocking operation.</span></span> <span data-ttu-id="cbbc8-162">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-162">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt; GetJobScheduleAsync (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.CloudJobSchedule&gt; GetJobScheduleAsync(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.GetJobScheduleAsync(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetJobScheduleAsync : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;" Usage="jobScheduleOperations.GetJobScheduleAsync (jobScheduleId, detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;GetJobScheduleAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-163">Die Id des Auftragszeitplans zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-163">The id of the job schedule to get.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="cbbc8-164">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> gesteuert, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-164">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-165">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-165">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cbbc8-166">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-166">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-167">Ruft den angegebenen <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> ab.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-167">Gets the specified <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-168">Ein <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> mit Informationen über die angegebene Azure Batch-Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-168">A <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" /> containing information about the specified Azure Batch job schedule.</span></span></returns>
        <remarks><span data-ttu-id="cbbc8-169">Get Job-Schedule-Vorgang wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-169">The get job schedule operation runs asynchronously.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt; ListJobs (string jobScheduleId, Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJob&gt; ListJobs(string jobScheduleId, class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobs(System.String,Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobs : string * Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;" Usage="jobScheduleOperations.ListJobs (jobScheduleId, detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJob&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-170">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-170">The id of the job schedule.</span></span></param>
        <param name="detailLevel"><span data-ttu-id="cbbc8-171">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-171">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-172">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-172">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-173">Listet die <see cref="T:Microsoft.Azure.Batch.CloudJob">Aufträge</see> unter der angegebenen Auftragszeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-173">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJob">jobs</see> created under the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-174">Ein <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , Aufträge aufgelistet werden, synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-174">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate jobs asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="cbbc8-175">Diese Methode gibt sofort zurück. nur, wenn die Auflistung aufgezählt wird, werden die Aufträge aus der Batch-Dienst abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-175">This method returns immediately; the jobs are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="cbbc8-176">Datenabruf ist nicht atomaren; Aufträge werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-176">Retrieval is non-atomic; jobs are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ListJobSchedules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt; ListJobSchedules (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;class Microsoft.Azure.Batch.CloudJobSchedule&gt; ListJobSchedules(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.ListJobSchedules(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.ListJobSchedules : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;" Usage="jobScheduleOperations.ListJobSchedules (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.IPagedEnumerable&lt;Microsoft.Azure.Batch.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="cbbc8-177">Ein <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> verwendet, der zum Filtern der Liste und zum Steuern, welche Eigenschaften aus dem Dienst abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-177">A <see cref="T:Microsoft.Azure.Batch.DetailLevel" /> used for filtering the list and for controlling which properties are retrieved from the service.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-178">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> und <paramref name="detailLevel" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-178">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" /> and <paramref name="detailLevel" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-179">Listet die <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule">Auftrag Zeitpläne</see> in dem Batch-Konto.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-179">Enumerates the <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule">job schedules</see> in the Batch account.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-180">Eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> , die zum Aufzählen von Auftragszeitplänen synchron oder asynchron verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-180">An <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> that can be used to enumerate job schedules asynchronously or synchronously.</span></span></returns>
        <remarks><span data-ttu-id="cbbc8-181">Diese Methode gibt sofort zurück. Die Auftragszeitpläne werden aus der Batch-Dienst abgerufen werden, nur, wenn die Auflistung aufgezählt wird.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-181">This method returns immediately; the job schedules are retrieved from the Batch service only when the collection is enumerated.</span></span>
            <span data-ttu-id="cbbc8-182">Datenabruf ist nicht atomaren; Zeitpläne werden in Seiten während der Enumeration der Auflistung abgerufen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-182">Retrieval is non-atomic; schedules are retrieved in pages during enumeration of the collection.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobSchedule">
      <MemberSignature Language="C#" Value="public void TerminateJobSchedule (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TerminateJobSchedule(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobSchedule(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TerminateJobSchedule (jobScheduleId As String, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobSchedule : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="jobScheduleOperations.TerminateJobSchedule (jobScheduleId, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-183">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-183">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-184">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-184">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-185">Beendet den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-185">Terminates the specified job schedule.</span></span>
            </summary>
        <remarks>
          <para><span data-ttu-id="cbbc8-186">Der Vorgang "Beenden" fordert, dass der Auftragszeitplan beendet werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-186">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="cbbc8-187">Die Anforderung legt den Zeitplan in das <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-187">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="cbbc8-188">Der Batch-Dienst wird warten Sie, bis alle aktiven Auftrag beendet und die Beendigung des tatsächlichen Auftrag-Zeitplan ohne weitere Aktion des Clients durchführen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-188">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="cbbc8-189">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-189">This is a blocking operation.</span></span> <span data-ttu-id="cbbc8-190">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-190">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateJobScheduleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task TerminateJobScheduleAsync (string jobScheduleId, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task TerminateJobScheduleAsync(string jobScheduleId, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.JobScheduleOperations.TerminateJobScheduleAsync(System.String,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.TerminateJobScheduleAsync : string * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="jobScheduleOperations.TerminateJobScheduleAsync (jobScheduleId, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.JobScheduleOperations/&lt;TerminateJobScheduleAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobScheduleId"><span data-ttu-id="cbbc8-191">Die Id des Auftragszeitplans.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-191">The id of the job schedule.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="cbbc8-192">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-192">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.JobScheduleOperations.CustomBehaviors" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="cbbc8-193">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-193">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="cbbc8-194">Beendet den angegebenen Auftrag-Zeitplan.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-194">Terminates the specified job schedule.</span></span>
            </summary>
        <returns><span data-ttu-id="cbbc8-195">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-195">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para><span data-ttu-id="cbbc8-196">Der Vorgang "Beenden" fordert, dass der Auftragszeitplan beendet werden.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-196">The terminate operation requests that the job schedule be terminated.</span></span>  <span data-ttu-id="cbbc8-197">Die Anforderung legt den Zeitplan in das <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> Zustand.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-197">The request puts the schedule in the <see cref="F:Microsoft.Azure.Batch.Common.JobScheduleState.Terminating" /> state.</span></span>
            <span data-ttu-id="cbbc8-198">Der Batch-Dienst wird warten Sie, bis alle aktiven Auftrag beendet und die Beendigung des tatsächlichen Auftrag-Zeitplan ohne weitere Aktion des Clients durchführen.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-198">The Batch service will wait for any active job to terminate, and perform the actual job schedule termination without any further client action.</span></span></para>
          <para><span data-ttu-id="cbbc8-199">Der Vorgang "Beenden" wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="cbbc8-199">The terminate operation runs asynchronously.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>