<Type Name="TaskConstraints" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints">
  <TypeSignature Language="C#" Value="public class TaskConstraints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskConstraints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskConstraints" />
  <TypeSignature Language="F#" Value="type TaskConstraints = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="02455-101">Ausführungseinschränkungen eine Aufgabe zuweisen.</span><span class="sxs-lookup"><span data-stu-id="02455-101">Execution constraints to apply to a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="02455-102">Initialisiert eine neue Instanz der TaskConstraints-Klasse.</span><span class="sxs-lookup"><span data-stu-id="02455-102">Initializes a new instance of the TaskConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskConstraints (Nullable&lt;TimeSpan&gt; maxWallClockTime = null, Nullable&lt;TimeSpan&gt; retentionTime = null, Nullable&lt;int&gt; maxTaskRetryCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; maxWallClockTime, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; retentionTime, valuetype System.Nullable`1&lt;int32&gt; maxTaskRetryCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.#ctor(System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional maxWallClockTime As Nullable(Of TimeSpan) = null, Optional retentionTime As Nullable(Of TimeSpan) = null, Optional maxTaskRetryCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints : Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskConstraints" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskConstraints (maxWallClockTime, retentionTime, maxTaskRetryCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="maxWallClockTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="retentionTime" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="maxTaskRetryCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="maxWallClockTime"><span data-ttu-id="02455-103">Die maximal verstrichene Zeit, die der Task ausgeführt werden kann, gemessen ab dem Zeitpunkt der Task beginnt.</span><span class="sxs-lookup"><span data-stu-id="02455-103">The maximum elapsed time that the task may run, measured from the time the task starts.</span></span> <span data-ttu-id="02455-104">Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.</span><span class="sxs-lookup"><span data-stu-id="02455-104">If the task does not complete within the time limit, the Batch service terminates it.</span></span></param>
        <param name="retentionTime"><span data-ttu-id="02455-105">Die minimale Zeit, das Task-Verzeichnis auf dem Computeknoten beizubehalten, wo es ab dem Zeitpunkt Lief, Ausführung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="02455-105">The minimum time to retain the task directory on the compute node where it ran, from the time it completes execution.</span></span> <span data-ttu-id="02455-106">Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.</span><span class="sxs-lookup"><span data-stu-id="02455-106">After this time, the Batch service may delete the task directory and all its contents.</span></span></param>
        <param name="maxTaskRetryCount"><span data-ttu-id="02455-107">Gibt an, wie oft der Task maximal wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="02455-107">The maximum number of times the task may be retried.</span></span> <span data-ttu-id="02455-108">Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</span><span class="sxs-lookup"><span data-stu-id="02455-108">The Batch service retries a task if its exit code is nonzero.</span></span></param>
        <summary>
            <span data-ttu-id="02455-109">Initialisiert eine neue Instanz der TaskConstraints-Klasse.</span><span class="sxs-lookup"><span data-stu-id="02455-109">Initializes a new instance of the TaskConstraints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTaskRetryCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTaskRetryCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTaskRetryCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTaskRetryCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxTaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTaskRetryCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02455-110">Ruft ab oder legt die maximale Anzahl der Häufigkeit, mit die der Vorgang wiederholt werden kann.</span><span class="sxs-lookup"><span data-stu-id="02455-110">Gets or sets the maximum number of times the task may be retried.</span></span>
            <span data-ttu-id="02455-111">Der Batch-Dienst wiederholt einen Task, wenn sein Exitcode ungleich null ist.</span><span class="sxs-lookup"><span data-stu-id="02455-111">The Batch service retries a task if its exit code is nonzero.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="02455-112">Beachten Sie, dass dieser Wert die Anzahl der Wiederholungen ausdrücklich steuert.</span><span class="sxs-lookup"><span data-stu-id="02455-112">Note that this value specifically controls the number of retries.</span></span>
            <span data-ttu-id="02455-113">Der Batch-Dienst wiederholt den Task einmal und kann ihn anschließend bis zu diesem Grenzwert wiederholen.</span><span class="sxs-lookup"><span data-stu-id="02455-113">The Batch service will try the task once, and may then retry up to this limit.</span></span> <span data-ttu-id="02455-114">Beispielsweise ist die maximale Anzahl von Wiederholungsversuchen 3, Batch versucht die Aufgabe bis zu 4 Mal (einen ersten Versuch und 3 Wiederholungen).</span><span class="sxs-lookup"><span data-stu-id="02455-114">For example, if the maximum retry count is 3, Batch tries the task up to 4 times (one initial try and 3 retries).</span></span> <span data-ttu-id="02455-115">Wenn die maximale Anzahl von Wiederholungsversuchen 0 ist, wird der Batch-Dienst nicht die Aufgabe erneut versucht.</span><span class="sxs-lookup"><span data-stu-id="02455-115">If the maximum retry count is 0, the Batch service does not retry the task.</span></span> <span data-ttu-id="02455-116">Wenn die maximale Anzahl wiederholen ist-1, die Batch-Dienst Wiederholungen der Task unbegrenzt.</span><span class="sxs-lookup"><span data-stu-id="02455-116">If the maximum retry count is -1, the Batch service retries the task without limit.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxWallClockTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; MaxWallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; MaxWallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxWallClockTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.MaxWallClockTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.MaxWallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxWallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02455-117">Ruft ab oder legt die maximale Zeitspanne, die der Task ausgeführt werden kann, gemessen ab dem Zeitpunkt, den der Task beginnt.</span><span class="sxs-lookup"><span data-stu-id="02455-117">Gets or sets the maximum elapsed time that the task may run, measured from the time the task starts.</span></span> <span data-ttu-id="02455-118">Wenn die Aufgabe nicht innerhalb des Zeitlimits abgeschlossen wird, der Batch-Dienst beendet wird.</span><span class="sxs-lookup"><span data-stu-id="02455-118">If the task does not complete within the time limit, the Batch service terminates it.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="02455-119">Wenn dies nicht angegeben wird, ist es nicht zeitlich begrenzt auf, wie lange der Vorgang ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="02455-119">If this is not specified, there is no time limit on how long the task may run.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RetentionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RetentionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionTime As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RetentionTime : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskConstraints.RetentionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retentionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="02455-120">Ruft ab oder legt die minimale Zeit, das Task-Verzeichnis auf dem Computeknoten beizubehalten, auf dem ausgeführt, ab dem Zeitpunkt, die Ausführung abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="02455-120">Gets or sets the minimum time to retain the task directory on the compute node where it ran, from the time it completes execution.</span></span>
            <span data-ttu-id="02455-121">Nach dieser Zeit kann der Batch-Dienst das Task-Verzeichnis und seinen gesamten Inhalt löschen.</span><span class="sxs-lookup"><span data-stu-id="02455-121">After this time, the Batch service may delete the task directory and all its contents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="02455-122">Die Standardeinstellung ist unendlich, d. h. das Verzeichnis Aufgabe werden beibehalten, bis die Compute-Knoten entfernt oder ein reimaging ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="02455-122">The default is infinite, i.e. the task directory will be retained until the compute node is removed or reimaged.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>