<Type Name="JobScheduleStatistics" FullName="Microsoft.Azure.Batch.JobScheduleStatistics">
  <TypeSignature Language="C#" Value="public class JobScheduleStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.JobScheduleStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleStatistics" />
  <TypeSignature Language="F#" Value="type JobScheduleStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="dad99-101">Statistiken zum Ressourceneinsatz während einer <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span><span class="sxs-lookup"><span data-stu-id="dad99-101">Resource usage statistics for a <see cref="T:Microsoft.Azure.Batch.CloudJobSchedule" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FailedTaskCount">
      <MemberSignature Language="C#" Value="public long FailedTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 FailedTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.FailedTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailedTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.FailedTaskCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.FailedTaskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-102">Ruft die Gesamtzahl der Aufgaben im Auftrag, die während des angegebenen Zeitraums fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="dad99-102">Gets the total number of tasks in the job that failed during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.KernelCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KernelCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.KernelCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-103">Ruft die gesamten Kernel CPU-Zeit im (pro Kern) aller Aufgaben im Auftragszeitplan ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-103">Gets the total kernel mode CPU time (per core) consumed by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-104">Ruft den Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="dad99-104">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="dad99-105">Alle Statistiken sind beschränkt auf den Bereich zwischen <see cref="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" /> und diesen Wert.</span><span class="sxs-lookup"><span data-stu-id="dad99-105">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-106">Ruft die gesamte Gibibytes e/a-Lesevorgängen aller Aufgaben im Auftragszeitplan vom Datenträger ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-106">Gets the total gibibytes of I/O read from disk by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-107">Ruft die Gesamtanzahl der Datenträger-Lesevorgänge aller Aufgaben im Auftragszeitplan ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-107">Gets the total number of disk read operations made by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-108">Ruft die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="dad99-108">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SucceededTaskCount">
      <MemberSignature Language="C#" Value="public long SucceededTaskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SucceededTaskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.SucceededTaskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SucceededTaskCount As Long" />
      <MemberSignature Language="F#" Value="member this.SucceededTaskCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.SucceededTaskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-109">Ruft die Gesamtzahl der Aufgaben erfolgreich abgeschlossen wird, in der Auftragszeitplan ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-109">Gets the total number of tasks successfully completed in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRetryCount">
      <MemberSignature Language="C#" Value="public long TaskRetryCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TaskRetryCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.TaskRetryCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskRetryCount As Long" />
      <MemberSignature Language="F#" Value="member this.TaskRetryCount : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.TaskRetryCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-110">Ruft die Gesamtanzahl der Wiederholungen, die aufgetreten sind für alle Aufgaben im Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="dad99-110">Gets the total number of retries that occurred on all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-111">Ruft die URL der Statistik ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-111">Gets the URL of the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCpuTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCpuTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCpuTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.UserCpuTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserCpuTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCpuTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.UserCpuTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-112">Ruft die Gesamtzeit CPU-Zeit im (pro Kern) aller Aufgaben im Auftragszeitplan ab.</span><span class="sxs-lookup"><span data-stu-id="dad99-112">Gets the total user mode CPU time (per core) consumed by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-113">Ruft die Gesamtwartezeit für alle Aufgaben bei Aufträgen, die unter dem der Zeitplan erstellt.</span><span class="sxs-lookup"><span data-stu-id="dad99-113">Gets the total wait time of all tasks in jobs created under the schedule.</span></span> <span data-ttu-id="dad99-114">Die Wartezeit für eine Aufgabe wird als die Zeitspanne zwischen dem Erstellen der Aufgabe und dem Start der Ausführung der Aufgabe definiert.</span><span class="sxs-lookup"><span data-stu-id="dad99-114">The wait time for a task is defined as the elapsed time between the creation of the task and the start of task execution.</span></span> <span data-ttu-id="dad99-115">(Wenn die Aufgabe aufgrund von Fehlern wiederholt wird, ist die Wartezeit der Zeit der letzten Ausführung der Aufgabe.)</span><span class="sxs-lookup"><span data-stu-id="dad99-115">(If the task is retried due to failures, the wait time is the time to the most recent task execution.)</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="dad99-116">Dieser Wert wird nur in der lebensdauerstatistiken Konto gemeldet.</span><span class="sxs-lookup"><span data-stu-id="dad99-116">This value is only reported in the account lifetime statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-117">Ruft die gesamtbetrachtungszeit aller Aufgaben im Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="dad99-117">Gets the total wall clock time of all tasks in the job schedule.</span></span> <span data-ttu-id="dad99-118">Beachten Sie, dass wenn eine Aufgabe mehrere Male wiederholt wurde, dies die gesamtbetrachtungszeit alle Wiederholungen der Aufgabe einschließt.</span><span class="sxs-lookup"><span data-stu-id="dad99-118">Note that if any task was retried multiple times, this includes the wall clock time of all the task retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-119">Ruft die gesamte Gibibytes e/a durch alle Aufgaben im Auftragszeitplan auf den Datenträger geschrieben.</span><span class="sxs-lookup"><span data-stu-id="dad99-119">Gets the total gibibytes of I/O written to disk by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64" Usage="Microsoft.Azure.Batch.JobScheduleStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dad99-120">Ruft die Gesamtzahl der Schreibvorgänge auf Datenträger durch alle Aufgaben im Auftragszeitplan vorgenommen.</span><span class="sxs-lookup"><span data-stu-id="dad99-120">Gets the total number of disk write operations made by all tasks in the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>