<Type Name="TaskStateMonitor" FullName="Microsoft.Azure.Batch.TaskStateMonitor">
  <TypeSignature Language="C#" Value="public class TaskStateMonitor : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskStateMonitor extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskStateMonitor" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskStateMonitor&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type TaskStateMonitor = class&#xA;    interface IInheritedBehaviors" />
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
            <span data-ttu-id="ebcae-101">Bietet Hilfsprogramme, die überwacht werden können CloudTask Status an.</span><span class="sxs-lookup"><span data-stu-id="ebcae-101">Provides utilities to help monitor CloudTask states.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />
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
            <span data-ttu-id="ebcae-102">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" />.</span><span class="sxs-lookup"><span data-stu-id="ebcae-102">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="ebcae-103">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="ebcae-103">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="ebcae-104">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="ebcae-104">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="ebcae-105">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="ebcae-105">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitAll">
      <MemberSignature Language="C#" Value="public void WaitAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void WaitAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WaitAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Sub WaitAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null)" />
      <MemberSignature Language="F#" Value="member this.WaitAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="taskStateMonitor.WaitAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
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
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor"><span data-ttu-id="ebcae-106">Die Auflistung von Aufgaben zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-106">The collection of tasks to monitor.</span></span></param>
        <param name="desiredState"><span data-ttu-id="ebcae-107">Die vorhergesagten Status der Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-107">The target state of the tasks.</span></span> <span data-ttu-id="ebcae-108">Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-108">The method will exit when all tasks have reached this state at least once.</span></span></param>
        <param name="timeout"><span data-ttu-id="ebcae-109">Die maximale Zeitspanne an, diesen Aufruf, bevor ein Timeout auftritt wartet.</span><span class="sxs-lookup"><span data-stu-id="ebcae-109">The maximum amount of time this call will wait before timing out.</span></span></param>
        <param name="controlParams"><span data-ttu-id="ebcae-110">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</span><span class="sxs-lookup"><span data-stu-id="ebcae-110">Controls various settings of the monitor, such as delay between each poll.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ebcae-111">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ebcae-111">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ebcae-112">Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.</span><span class="sxs-lookup"><span data-stu-id="ebcae-112">Monitors a <see cref="T:Microsoft.Azure.Batch.CloudTask" /> collection until each of its members has reached a desired state at least once.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="ebcae-113">Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="ebcae-113">The state of each <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instance is assumed to be authoritative at the time of the call.</span></span>
            <span data-ttu-id="ebcae-114">Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ebcae-114">Instances that are already at the <paramref name="desiredState" /> are ignored.</span></span>
            <span data-ttu-id="ebcae-115">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-115">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances in the collection are treated as read-only.</span></span>
            <span data-ttu-id="ebcae-116">Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-116">This means that when the call completes (timeout or not) the <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances should be refreshed before using.</span></span>
            </para>
          <para>
            <span data-ttu-id="ebcae-117">Dies ist ein blockierender Vorgang.</span><span class="sxs-lookup"><span data-stu-id="ebcae-117">This is a blocking operation.</span></span> <span data-ttu-id="ebcae-118">Eine nicht blockierende Entsprechung, finden Sie unter <see cref="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span><span class="sxs-lookup"><span data-stu-id="ebcae-118">For a non-blocking equivalent, see <see cref="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="ebcae-119">Wird ausgelöst, wenn die <paramref name="timeout" /> ist abgelaufen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-119">Thrown if the <paramref name="timeout" /> has elapsed.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, System.Threading.CancellationToken cancellationToken, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.Threading.CancellationToken cancellationToken, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.Threading.CancellationToken,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * System.Threading.CancellationToken * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, cancellationToken, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor"><span data-ttu-id="ebcae-120">Die Auflistung von Aufgaben zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-120">The collection of tasks to monitor.</span></span></param>
        <param name="desiredState"><span data-ttu-id="ebcae-121">Die vorhergesagten Status der Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-121">The target state of the tasks.</span></span> <span data-ttu-id="ebcae-122">Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-122">The method will exit when all tasks have reached this state at least once.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="ebcae-123">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="ebcae-123">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <param name="controlParams"><span data-ttu-id="ebcae-124">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</span><span class="sxs-lookup"><span data-stu-id="ebcae-124">Controls various settings of the monitor, such as delay between each poll.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ebcae-125">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ebcae-125">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ebcae-126">Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.</span><span class="sxs-lookup"><span data-stu-id="ebcae-126">Monitors a <see cref="T:Microsoft.Azure.Batch.CloudTask" /> collection until each of its members has reached a desired state at least once.</span></span>
            </summary>
        <returns><span data-ttu-id="ebcae-127">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ebcae-127">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="ebcae-128">Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="ebcae-128">The state of each <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instance is assumed to be authoritative at the time of the call.</span></span>
            <span data-ttu-id="ebcae-129">Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ebcae-129">Instances that are already at the <paramref name="desiredState" /> are ignored.</span></span>
            <span data-ttu-id="ebcae-130">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-130">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances in the collection are treated as read-only.</span></span>
            <span data-ttu-id="ebcae-131">Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-131">This means that when the call completes (timeout or not) the <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances should be refreshed before using.</span></span>
            </para>
          <para>
            <span data-ttu-id="ebcae-132">Diese Methode wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ebcae-132">This method runs asynchronously.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.OperationCanceledException"><span data-ttu-id="ebcae-133">Wird ausgelöst, wenn die <paramref name="cancellationToken" /> wurde abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-133">Thrown if the <paramref name="cancellationToken" /> was cancelled.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="WhenAll">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task WhenAll (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, Microsoft.Azure.Batch.Common.TaskState desiredState, TimeSpan timeout, Microsoft.Azure.Batch.ODATAMonitorControl controlParams = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task WhenAll(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasksToMonitor, valuetype Microsoft.Azure.Batch.Common.TaskState desiredState, valuetype System.TimeSpan timeout, class Microsoft.Azure.Batch.ODATAMonitorControl controlParams, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskStateMonitor.WhenAll(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask},Microsoft.Azure.Batch.Common.TaskState,System.TimeSpan,Microsoft.Azure.Batch.ODATAMonitorControl,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="VB.NET" Value="Public Function WhenAll (tasksToMonitor As IEnumerable(Of CloudTask), desiredState As TaskState, timeout As TimeSpan, Optional controlParams As ODATAMonitorControl = null, Optional additionalBehaviors As IEnumerable(Of BatchClientBehavior) = null) As Task" />
      <MemberSignature Language="F#" Value="member this.WhenAll : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; * Microsoft.Azure.Batch.Common.TaskState * TimeSpan * Microsoft.Azure.Batch.ODATAMonitorControl * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; System.Threading.Tasks.Task" Usage="taskStateMonitor.WhenAll (tasksToMonitor, desiredState, timeout, controlParams, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.TaskStateMonitor/&lt;WhenAll&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasksToMonitor" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
        <Parameter Name="desiredState" Type="Microsoft.Azure.Batch.Common.TaskState" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="controlParams" Type="Microsoft.Azure.Batch.ODATAMonitorControl" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="tasksToMonitor"><span data-ttu-id="ebcae-134">Die Auflistung von Aufgaben zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-134">The collection of tasks to monitor.</span></span></param>
        <param name="desiredState"><span data-ttu-id="ebcae-135">Die vorhergesagten Status der Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-135">The target state of the tasks.</span></span> <span data-ttu-id="ebcae-136">Die Methode wird beendet, wenn alle Aufgaben mindestens einmal dieser Status erreicht haben.</span><span class="sxs-lookup"><span data-stu-id="ebcae-136">The method will exit when all tasks have reached this state at least once.</span></span></param>
        <param name="timeout"><span data-ttu-id="ebcae-137">Die maximale Zeitspanne an, diesen Aufruf, bevor ein Timeout auftritt wartet.</span><span class="sxs-lookup"><span data-stu-id="ebcae-137">The maximum amount of time this call will wait before timing out.</span></span></param>
        <param name="controlParams"><span data-ttu-id="ebcae-138">Steuert verschiedene Einstellungen des Monitors, z. B. Verzögerung zwischen den einzelnen an.</span><span class="sxs-lookup"><span data-stu-id="ebcae-138">Controls various settings of the monitor, such as delay between each poll.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="ebcae-139">Eine Auflistung von <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> Instanzen, die für die Batchanforderung-Dienst nach gelten die <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span><span class="sxs-lookup"><span data-stu-id="ebcae-139">A collection of <see cref="T:Microsoft.Azure.Batch.BatchClientBehavior" /> instances that are applied to the Batch service request after the <see cref="P:Microsoft.Azure.Batch.TaskStateMonitor.CustomBehaviors" />.</span></span></param>
        <summary>
            <span data-ttu-id="ebcae-140">Monitore eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Auflistung erst jedes seiner Member mindestens einmal einen gewünschten Zustand erreicht.</span><span class="sxs-lookup"><span data-stu-id="ebcae-140">Monitors a <see cref="T:Microsoft.Azure.Batch.CloudTask" /> collection until each of its members has reached a desired state at least once.</span></span>
            </summary>
        <returns><span data-ttu-id="ebcae-141">Ein <see cref="T:System.Threading.Tasks.Task" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="ebcae-141">A <see cref="T:System.Threading.Tasks.Task" /> that represents the asynchronous operation.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="ebcae-142">Der Status der einzelnen <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanz wird davon ausgegangen, dass autorisierende zum Zeitpunkt des Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="ebcae-142">The state of each <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instance is assumed to be authoritative at the time of the call.</span></span>
            <span data-ttu-id="ebcae-143">Instanzen, die bereits an die <paramref name="desiredState" /> werden ignoriert.</span><span class="sxs-lookup"><span data-stu-id="ebcae-143">Instances that are already at the <paramref name="desiredState" /> are ignored.</span></span>
            <span data-ttu-id="ebcae-144">Die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen in der Auflistung als schreibgeschützt behandelt werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-144">The <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances in the collection are treated as read-only.</span></span>
            <span data-ttu-id="ebcae-145">Dies bedeutet, dass bei Beendigung des Aufrufs (Timeout oder nicht) die <see cref="T:Microsoft.Azure.Batch.CloudTask" /> Instanzen sollte vor der Verwendung aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="ebcae-145">This means that when the call completes (timeout or not) the <see cref="T:Microsoft.Azure.Batch.CloudTask" /> instances should be refreshed before using.</span></span>
            </para>
          <para>
            <span data-ttu-id="ebcae-146">Diese Methode wird asynchron ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="ebcae-146">This method runs asynchronously.</span></span>
            </para>
        </remarks>
        <exception cref="T:System.TimeoutException"><span data-ttu-id="ebcae-147">Wird ausgelöst, wenn die <paramref name="timeout" /> ist abgelaufen.</span><span class="sxs-lookup"><span data-stu-id="ebcae-147">Thrown if the <paramref name="timeout" /> has elapsed.</span></span></exception>
      </Docs>
    </Member>
  </Members>
</Type>