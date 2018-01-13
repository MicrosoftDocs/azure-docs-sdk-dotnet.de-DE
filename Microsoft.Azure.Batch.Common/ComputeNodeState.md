<Type Name="ComputeNodeState" FullName="Microsoft.Azure.Batch.Common.ComputeNodeState">
  <TypeSignature Language="C#" Value="public enum ComputeNodeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeState" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeState" />
  <TypeSignature Language="F#" Value="type ComputeNodeState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="15839-101">Der Status der Compute-Knoten.</span><span class="sxs-lookup"><span data-stu-id="15839-101">The state of a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Creating">
      <MemberSignature Language="C#" Value="Creating" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Creating = int32(5)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Creating" />
      <MemberSignature Language="VB.NET" Value="Creating" />
      <MemberSignature Language="F#" Value="Creating = 5" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Creating" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-102">Der Batch-Dienst hat die zugrunde liegende virtuelle Computer aus Azure Compute abgerufen, aber es wurde noch nicht gestartet, der einen Pool einzubinden.</span><span class="sxs-lookup"><span data-stu-id="15839-102">The Batch service has obtained the underlying virtual machine from Azure Compute, but it has not yet started to join a pool.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Idle">
      <MemberSignature Language="C#" Value="Idle" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Idle = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />
      <MemberSignature Language="VB.NET" Value="Idle" />
      <MemberSignature Language="F#" Value="Idle = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Idle" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-103">Die Compute-Knoten wird einen Task zurzeit nicht ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="15839-103">The compute node is not currently running a task.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="LeavingPool">
      <MemberSignature Language="C#" Value="LeavingPool" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState LeavingPool = int32(10)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.LeavingPool" />
      <MemberSignature Language="VB.NET" Value="LeavingPool" />
      <MemberSignature Language="F#" Value="LeavingPool = 10" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.LeavingPool" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>10</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-104">Die Compute-Knoten verlässt den Pool daran, dass der Benutzer explizit entfernt oder der Pool Ändern der Größe oder die automatische Skalierung nach unten ist.</span><span class="sxs-lookup"><span data-stu-id="15839-104">The compute node is leaving the pool, either because the user explicitly removed it or because the pool is resizing or autoscaling down.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Offline">
      <MemberSignature Language="C#" Value="Offline" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Offline = int32(11)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Offline" />
      <MemberSignature Language="VB.NET" Value="Offline" />
      <MemberSignature Language="F#" Value="Offline = 11" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Offline" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>11</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-105">Der Batch-Dienst wird nicht auf den Computeknoten neue Vorgänge planen.</span><span class="sxs-lookup"><span data-stu-id="15839-105">The Batch service will not schedule any new tasks on the compute node.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Preempted">
      <MemberSignature Language="C#" Value="Preempted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Preempted = int32(12)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Preempted" />
      <MemberSignature Language="VB.NET" Value="Preempted" />
      <MemberSignature Language="F#" Value="Preempted = 12" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Preempted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>12</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-106">Die Compute-Knoten wurde unterbrochen.</span><span class="sxs-lookup"><span data-stu-id="15839-106">The compute node has been preempted.</span></span>
            </summary>
        <remarks>
          <para>
            <span data-ttu-id="15839-107">Der Batch-Dienst wird nicht planen, neue Vorgänge auf den Computeknoten und alle Aufgaben, die zum Zeitpunkt der Unterbrechung ausgeführt wurden wurden in die Warteschlange.</span><span class="sxs-lookup"><span data-stu-id="15839-107">The Batch service will not schedule any new tasks on the compute node and any tasks which were running at the time of preemption were requeued.</span></span>
            <span data-ttu-id="15839-108">Der Batch-Dienst versucht, die Knoten Wiederherstellung durchführen, der in diesem Zustand befinden.</span><span class="sxs-lookup"><span data-stu-id="15839-108">The Batch service will attempt to recover nodes which are in this state.</span></span> <span data-ttu-id="15839-109">Nach der Wiederherstellung alle Daten, die auf dem Knoten zum Zeitpunkt der die Unterbrechung wurde nicht mehr vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="15839-109">After recovery, all data that was on the node at the time of the preemption is gone.</span></span>
            </para>
          <para>
            <span data-ttu-id="15839-110">Sie sind nicht für Serverknoten in Rechnung gestellt, die vorweggenommen haben.</span><span class="sxs-lookup"><span data-stu-id="15839-110">You are not charged for compute nodes that have been preempted.</span></span>
            </para>
          <para>
            <span data-ttu-id="15839-111">Dies kann nur sicherheitsbezogener auf Knoten, auf dem <see cref="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" /> lautet "false".</span><span class="sxs-lookup"><span data-stu-id="15839-111">This can only occurr on nodes where <see cref="P:Microsoft.Azure.Batch.ComputeNode.IsDedicated" /> is false.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Rebooting">
      <MemberSignature Language="C#" Value="Rebooting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Rebooting = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Rebooting" />
      <MemberSignature Language="VB.NET" Value="Rebooting" />
      <MemberSignature Language="F#" Value="Rebooting = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Rebooting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-112">Die Compute-Knoten neu gestartet.</span><span class="sxs-lookup"><span data-stu-id="15839-112">The compute node is rebooting.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Reimaging">
      <MemberSignature Language="C#" Value="Reimaging" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Reimaging = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Reimaging" />
      <MemberSignature Language="VB.NET" Value="Reimaging" />
      <MemberSignature Language="F#" Value="Reimaging = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Reimaging" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-113">Die Compute-Knoten ist ein reimaging ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="15839-113">The compute node is being reimaged.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Running = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-114">Die Compute-Knoten wird eine oder mehrere Aufgaben (mit Ausnahme der Startaufgabe) ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="15839-114">The compute node is running one or more tasks (other than the start task).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Starting">
      <MemberSignature Language="C#" Value="Starting" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Starting = int32(6)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Starting" />
      <MemberSignature Language="VB.NET" Value="Starting" />
      <MemberSignature Language="F#" Value="Starting = 6" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Starting" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-115">Der Batch-Dienst wird auf dem zugrunde liegenden virtuellen Computer gestartet.</span><span class="sxs-lookup"><span data-stu-id="15839-115">The Batch service is starting on the underlying virtual machine.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="StartTaskFailed">
      <MemberSignature Language="C#" Value="StartTaskFailed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState StartTaskFailed = int32(8)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.StartTaskFailed" />
      <MemberSignature Language="VB.NET" Value="StartTaskFailed" />
      <MemberSignature Language="F#" Value="StartTaskFailed = 8" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.StartTaskFailed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>8</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-116">Die Startaufgabe konnte nicht auf den Computeknoten (und alle Wiederholungen ausgeschöpft) aufweist und WaitForSuccess festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="15839-116">The start task has failed on the compute node (and exhausted all retries), and waitForSuccess is set.</span></span>  <span data-ttu-id="15839-117">Der Knoten ist nicht zum Ausführen von Aufgaben verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="15839-117">The node is not usable for running tasks.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unknown">
      <MemberSignature Language="C#" Value="Unknown" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Unknown = int32(9)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Unknown" />
      <MemberSignature Language="VB.NET" Value="Unknown" />
      <MemberSignature Language="F#" Value="Unknown = 9" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Unknown" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>9</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-118">Der Batch-Dienst hat hat die Verbindung mit dem Computeknoten und Datenbankzustands "true" ist nicht bekannt.</span><span class="sxs-lookup"><span data-stu-id="15839-118">The Batch service has lost contact with the compute node, and does not know its true state.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Unusable">
      <MemberSignature Language="C#" Value="Unusable" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState Unusable = int32(4)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.Unusable" />
      <MemberSignature Language="VB.NET" Value="Unusable" />
      <MemberSignature Language="F#" Value="Unusable = 4" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.Unusable" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-119">Die Compute-Knoten kann nicht für die Ausführung der Aufgabe aufgrund von Fehlern verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="15839-119">The compute node cannot be used for task execution due to errors.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="WaitingForStartTask">
      <MemberSignature Language="C#" Value="WaitingForStartTask" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeState WaitingForStartTask = int32(7)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeState.WaitingForStartTask" />
      <MemberSignature Language="VB.NET" Value="WaitingForStartTask" />
      <MemberSignature Language="F#" Value="WaitingForStartTask = 7" Usage="Microsoft.Azure.Batch.Common.ComputeNodeState.WaitingForStartTask" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeState</ReturnType>
      </ReturnValue>
      <MemberValue>7</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="15839-120">Die Startaufgabe wurde gestartet, die auf dem Computeknoten ausgeführt, aber WaitForSuccess festgelegt ist, und die Startaufgabe noch nicht abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="15839-120">The start task has started running on the compute node, but waitForSuccess is set and the start task has not yet completed.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>