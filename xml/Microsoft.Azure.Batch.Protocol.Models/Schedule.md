<Type Name="Schedule" FullName="Microsoft.Azure.Batch.Protocol.Models.Schedule">
  <TypeSignature Language="C#" Value="public class Schedule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Schedule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.Schedule" />
  <TypeSignature Language="VB.NET" Value="Public Class Schedule" />
  <TypeSignature Language="F#" Value="type Schedule = class" />
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
            <span data-ttu-id="34d82-101">Der Zeitplan entsprechend, den Aufträge erstellt werden soll</span><span class="sxs-lookup"><span data-stu-id="34d82-101">The schedule according to which jobs will be created</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor" />
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
            <span data-ttu-id="34d82-102">Initialisiert eine neue Instanz der Klasse Zeitplan an.</span><span class="sxs-lookup"><span data-stu-id="34d82-102">Initializes a new instance of the Schedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Schedule (Nullable&lt;DateTime&gt; doNotRunUntil = null, Nullable&lt;DateTime&gt; doNotRunAfter = null, Nullable&lt;TimeSpan&gt; startWindow = null, Nullable&lt;TimeSpan&gt; recurrenceInterval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunUntil, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; doNotRunAfter, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; startWindow, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; recurrenceInterval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Schedule.#ctor(System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.TimeSpan},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional doNotRunUntil As Nullable(Of DateTime) = null, Optional doNotRunAfter As Nullable(Of DateTime) = null, Optional startWindow As Nullable(Of TimeSpan) = null, Optional recurrenceInterval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.Schedule : Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;TimeSpan&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.Schedule" Usage="new Microsoft.Azure.Batch.Protocol.Models.Schedule (doNotRunUntil, doNotRunAfter, startWindow, recurrenceInterval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="doNotRunUntil" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="doNotRunAfter" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="startWindow" Type="System.Nullable&lt;System.TimeSpan&gt;" />
        <Parameter Name="recurrenceInterval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="doNotRunUntil"><span data-ttu-id="34d82-103">Die früheste Uhrzeit, an dem ein Auftrag unter diesem Auftragszeitplan erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="34d82-103">The earliest time at which any job may be created under this job schedule.</span></span></param>
        <param name="doNotRunAfter"><span data-ttu-id="34d82-104">Eine Uhrzeit, nach der kein Auftrag unter diesem Auftragszeitplan erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="34d82-104">A time after which no job will be created under this job schedule.</span></span> <span data-ttu-id="34d82-105">Der Zeitplan wird in den abgeschlossenen Zustand verschoben, sobald diese Frist überschritten ist und es kein aktiver Auftrag unter diesem Auftragszeitplan ist.</span><span class="sxs-lookup"><span data-stu-id="34d82-105">The schedule will move to the completed state as soon as this deadline is past and there is no active job under this job schedule.</span></span></param>
        <param name="startWindow"><span data-ttu-id="34d82-106">Das Zeitintervall sollte ab dem Zeitpunkt, zu dem gemäß dem Zeitplan einen Auftrag, erstellt werden, in dem ein Auftrag erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="34d82-106">The time interval, starting from the time at which the schedule indicates a job should be created, within which a job must be created.</span></span></param>
        <param name="recurrenceInterval"><span data-ttu-id="34d82-107">Das Zeitintervall zwischen den Startzeiten von zwei aufeinander folgenden Aufträgen unter der Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="34d82-107">The time interval between the start times of two successive jobs under the job schedule.</span></span> <span data-ttu-id="34d82-108">Zeitplan für einen Auftrag kann zu einem beliebigen Zeitpunkt höchstens einen aktiven Auftrag unter sich haben.</span><span class="sxs-lookup"><span data-stu-id="34d82-108">A job schedule can have at most one active job under it at any given time.</span></span></param>
        <summary>
            <span data-ttu-id="34d82-109">Initialisiert eine neue Instanz der Klasse Zeitplan an.</span><span class="sxs-lookup"><span data-stu-id="34d82-109">Initializes a new instance of the Schedule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunAfter">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunAfter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunAfter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunAfter As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunAfter : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunAfter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunAfter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d82-110">Ermittelt oder definiert einen Zeitpunkt nach dem kein Auftrag unter diesem Auftragszeitplan erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="34d82-110">Gets or sets a time after which no job will be created under this job schedule.</span></span> <span data-ttu-id="34d82-111">Der Zeitplan wird in den abgeschlossenen Zustand verschoben, sobald diese Frist überschritten ist und es kein aktiver Auftrag unter diesem Auftragszeitplan ist.</span><span class="sxs-lookup"><span data-stu-id="34d82-111">The schedule will move to the completed state as soon as this deadline is past and there is no active job under this job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34d82-112">Wenn Sie eine Zeit DoNotRunAfter nicht angeben und Sie einen Zeitplan für wiederkehrende Aufträge erstellen, wird der Auftragszeitplan aktiv bleibt, bis Sie explizit beenden.</span><span class="sxs-lookup"><span data-stu-id="34d82-112">If you do not specify a doNotRunAfter time, and you are creating a recurring job schedule, the job schedule will remain active until you explicitly terminate it.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DoNotRunUntil">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DoNotRunUntil { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DoNotRunUntil" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberSignature Language="VB.NET" Value="Public Property DoNotRunUntil As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DoNotRunUntil : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.DoNotRunUntil" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="doNotRunUntil")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d82-113">Ruft ab oder legt den frühesten Zeitpunkt, an dem ein Auftrag unter diesem Auftragszeitplan erstellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="34d82-113">Gets or sets the earliest time at which any job may be created under this job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34d82-114">Wenn Sie keine DoNotRunUntil Zeit angeben, wird der Zeitplan bereit, um Aufträge sofort zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="34d82-114">If you do not specify a doNotRunUntil time, the schedule becomes ready to create jobs immediately.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceInterval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; RecurrenceInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; RecurrenceInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceInterval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceInterval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.RecurrenceInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceInterval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d82-115">Ruft ab oder legt das Zeitintervall zwischen den Startzeiten von zwei aufeinander folgenden Aufträgen unter der Auftragszeitplan fest.</span><span class="sxs-lookup"><span data-stu-id="34d82-115">Gets or sets the time interval between the start times of two successive jobs under the job schedule.</span></span> <span data-ttu-id="34d82-116">Zeitplan für einen Auftrag kann zu einem beliebigen Zeitpunkt höchstens einen aktiven Auftrag unter sich haben.</span><span class="sxs-lookup"><span data-stu-id="34d82-116">A job schedule can have at most one active job under it at any given time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34d82-117">Zeitplan für einen Auftrag einem bestimmten Zeitpunkt höchstens einen aktiven Auftrag unter sich haben kann, wenn Sie jetzt einen neuen Auftrag unter Zeitplan für einen Auftrag erstellen, aber der vorherige Auftrag noch ausgeführt wird, wird der Batch-Dienst nicht den neuen Auftrag erstellen, bis der vorherige Auftrag abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="34d82-117">Because a job schedule can have at most one active job under it at any given time, if it is time to create a new job under a job schedule, but the previous job is still running, the Batch service will not create the new job until the previous job finishes.</span></span> <span data-ttu-id="34d82-118">Wenn der vorherige Auftrag nicht innerhalb des Zeitraums "startwindow" neue RecurrenceInterval beendet wird, wird kein neuer Auftrag für dieses Intervall geplant.</span><span class="sxs-lookup"><span data-stu-id="34d82-118">If the previous job does not finish within the startWindow period of the new recurrenceInterval, then no new job will be scheduled for that interval.</span></span> <span data-ttu-id="34d82-119">Für wiederkehrende Aufträge sollten Sie normalerweise eine JobManagerTask in die jobspecification wirken angeben.</span><span class="sxs-lookup"><span data-stu-id="34d82-119">For recurring jobs, you should normally specify a jobManagerTask in the jobSpecification.</span></span> <span data-ttu-id="34d82-120">Wenn Sie nicht JobManagerTask verwenden, benötigen Sie einen externen Prozess überwachen, wann Aufträge erstellt werden, Hinzufügen von Tasks Aufträge aus, und beenden die Aufträge für die nächste Wiederholung bereit.</span><span class="sxs-lookup"><span data-stu-id="34d82-120">If you do not use jobManagerTask, you will need an external process to monitor when jobs are created, add tasks to the jobs and terminate the jobs ready for the next recurrence.</span></span> <span data-ttu-id="34d82-121">Die Standardeinstellung ist, dass der Zeitplan nicht wiederholt werden kann: ein Auftrag erstellt, in der "startwindow" nach der Zeit DoNotRunUntil und der Zeitplan ist abgeschlossen, sobald der Auftrag abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="34d82-121">The default is that the schedule does not recur: one job is created, within the startWindow after the doNotRunUntil time, and the schedule is complete as soon as that job finishes.</span></span> <span data-ttu-id="34d82-122">Der Mindestwert ist 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="34d82-122">The minimum value is 1 minute.</span></span> <span data-ttu-id="34d82-123">Wenn Sie einen niedrigeren Wert angeben, weist der Batch-Dienst den Zeitplan mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="34d82-123">If you specify a lower value, the Batch service rejects the schedule with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StartWindow">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; StartWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; StartWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property StartWindow As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.StartWindow : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Schedule.StartWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="34d82-124">Ruft ab oder legt das Zeitintervall ab dem Zeitpunkt, zu dem gemäß dem Zeitplan, dass ein Auftrag erstellt werden soll, in dem ein Auftrag erstellt werden muss.</span><span class="sxs-lookup"><span data-stu-id="34d82-124">Gets or sets the time interval, starting from the time at which the schedule indicates a job should be created, within which a job must be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="34d82-125">Wenn ein Auftrag nicht innerhalb des Intervalls für "startwindow" erstellt wird, ist "Verkaufschance" verloren. bis die nächste Wiederholung des Zeitplans wird kein Agentauftrag erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="34d82-125">If a job is not created within the startWindow interval, then the 'opportunity' is lost; no job will be created until the next recurrence of the schedule.</span></span> <span data-ttu-id="34d82-126">Wenn der Zeitplan wiederholt wird, und die "startwindow" länger als das Wiederholungsintervall ist, entspricht dies eine unendliche "startwindow", da Auftrags, due in einem RecurrenceInterval ist, nicht in der nächsten Wiederholungsintervall übernommen wird.</span><span class="sxs-lookup"><span data-stu-id="34d82-126">If the schedule is recurring, and the startWindow is longer than the recurrence interval, then this is equivalent to an infinite startWindow, because the job that is 'due' in one recurrenceInterval is not carried forward into the next recurrence interval.</span></span> <span data-ttu-id="34d82-127">Der Standardwert ist unendlich.</span><span class="sxs-lookup"><span data-stu-id="34d82-127">The default is infinite.</span></span> <span data-ttu-id="34d82-128">Der Mindestwert ist 1 Minute.</span><span class="sxs-lookup"><span data-stu-id="34d82-128">The minimum value is 1 minute.</span></span> <span data-ttu-id="34d82-129">Wenn Sie einen niedrigeren Wert angeben, weist der Batch-Dienst den Zeitplan mit einem Fehler zurück; Wenn Sie die REST-API direkt aufrufen, wird der HTTP-Statuscode 400 (Ungültige Anforderung).</span><span class="sxs-lookup"><span data-stu-id="34d82-129">If you specify a lower value, the Batch service rejects the schedule with an error; if you are calling the REST API directly, the HTTP status code is 400 (Bad Request).</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>