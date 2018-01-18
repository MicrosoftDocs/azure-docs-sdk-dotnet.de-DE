<Type Name="JobStatistics" FullName="Microsoft.Azure.Batch.Protocol.Models.JobStatistics">
  <TypeSignature Language="C#" Value="public class JobStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class JobStatistics" />
  <TypeSignature Language="F#" Value="type JobStatistics = class" />
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
            <span data-ttu-id="406af-101">Statistiken zum Ressourceneinsatz während eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="406af-101">Resource usage statistics for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.#ctor" />
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
            <span data-ttu-id="406af-102">Initialisiert eine neue Instanz der JobStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="406af-102">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobStatistics (string url, DateTime startTime, DateTime lastUpdateTime, TimeSpan userCPUTime, TimeSpan kernelCPUTime, TimeSpan wallClockTime, long readIOps, long writeIOps, double readIOGiB, double writeIOGiB, long numSucceededTasks, long numFailedTasks, long numTaskRetries, TimeSpan waitTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string url, valuetype System.DateTime startTime, valuetype System.DateTime lastUpdateTime, valuetype System.TimeSpan userCPUTime, valuetype System.TimeSpan kernelCPUTime, valuetype System.TimeSpan wallClockTime, int64 readIOps, int64 writeIOps, float64 readIOGiB, float64 writeIOGiB, int64 numSucceededTasks, int64 numFailedTasks, int64 numTaskRetries, valuetype System.TimeSpan waitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.#ctor(System.String,System.DateTime,System.DateTime,System.TimeSpan,System.TimeSpan,System.TimeSpan,System.Int64,System.Int64,System.Double,System.Double,System.Int64,System.Int64,System.Int64,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (url As String, startTime As DateTime, lastUpdateTime As DateTime, userCPUTime As TimeSpan, kernelCPUTime As TimeSpan, wallClockTime As TimeSpan, readIOps As Long, writeIOps As Long, readIOGiB As Double, writeIOGiB As Double, numSucceededTasks As Long, numFailedTasks As Long, numTaskRetries As Long, waitTime As TimeSpan)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobStatistics : string * DateTime * DateTime * TimeSpan * TimeSpan * TimeSpan * int64 * int64 * double * double * int64 * int64 * int64 * TimeSpan -&gt; Microsoft.Azure.Batch.Protocol.Models.JobStatistics" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobStatistics (url, startTime, lastUpdateTime, userCPUTime, kernelCPUTime, wallClockTime, readIOps, writeIOps, readIOGiB, writeIOGiB, numSucceededTasks, numFailedTasks, numTaskRetries, waitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="lastUpdateTime" Type="System.DateTime" />
        <Parameter Name="userCPUTime" Type="System.TimeSpan" />
        <Parameter Name="kernelCPUTime" Type="System.TimeSpan" />
        <Parameter Name="wallClockTime" Type="System.TimeSpan" />
        <Parameter Name="readIOps" Type="System.Int64" />
        <Parameter Name="writeIOps" Type="System.Int64" />
        <Parameter Name="readIOGiB" Type="System.Double" />
        <Parameter Name="writeIOGiB" Type="System.Double" />
        <Parameter Name="numSucceededTasks" Type="System.Int64" />
        <Parameter Name="numFailedTasks" Type="System.Int64" />
        <Parameter Name="numTaskRetries" Type="System.Int64" />
        <Parameter Name="waitTime" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="url"><span data-ttu-id="406af-103">Die URL der Statistik.</span><span class="sxs-lookup"><span data-stu-id="406af-103">The URL of the statistics.</span></span></param>
        <param name="startTime"><span data-ttu-id="406af-104">Die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="406af-104">The start time of the time range covered by the statistics.</span></span></param>
        <param name="lastUpdateTime"><span data-ttu-id="406af-105">Der Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="406af-105">The time at which the statistics were last updated.</span></span> <span data-ttu-id="406af-106">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="406af-106">All statistics are limited to the range between startTime and lastUpdateTime.</span></span></param>
        <param name="userCPUTime"><span data-ttu-id="406af-107">Die Gesamtzeit Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-107">The total user mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span></param>
        <param name="kernelCPUTime"><span data-ttu-id="406af-108">Die insgesamt Kernel-Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-108">The total kernel mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span></param>
        <param name="wallClockTime"><span data-ttu-id="406af-109">Die gesamtbetrachtungszeit aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-109">The total wall clock time of all tasks in the job.</span></span></param>
        <param name="readIOps"><span data-ttu-id="406af-110">Die Gesamtanzahl der Datenträger Lesevorgänge aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-110">The total number of disk read operations made by all tasks in the job.</span></span></param>
        <param name="writeIOps"><span data-ttu-id="406af-111">Die Gesamtanzahl der Datenträger Schreibvorgänge aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-111">The total number of disk write operations made by all tasks in the job.</span></span></param>
        <param name="readIOGiB"><span data-ttu-id="406af-112">Die Gesamtmenge der Daten in gib betragen Lesen vom Datenträger durch alle Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-112">The total amount of data in GiB read from disk by all tasks in the job.</span></span></param>
        <param name="writeIOGiB"><span data-ttu-id="406af-113">Die Gesamtmenge der Daten in gib betragen, indem Sie alle Aufgaben im Auftrag auf den Datenträger geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="406af-113">The total amount of data in GiB written to disk by all tasks in the job.</span></span></param>
        <param name="numSucceededTasks"><span data-ttu-id="406af-114">Die Gesamtzahl der Aufgaben, die im Auftrag während des angegebenen Zeitraums erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="406af-114">The total number of tasks successfully completed in the job during the given time range.</span></span></param>
        <param name="numFailedTasks"><span data-ttu-id="406af-115">Die Gesamtanzahl von Aufgaben im Auftrag, die während des angegebenen Zeitraums fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="406af-115">The total number of tasks in the job that failed during the given time range.</span></span></param>
        <param name="numTaskRetries"><span data-ttu-id="406af-116">Die Gesamtanzahl der Wiederholungen für alle Aufgaben im Auftrag während des angegebenen Zeitraums.</span><span class="sxs-lookup"><span data-stu-id="406af-116">The total number of retries on all the tasks in the job during the given time range.</span></span></param>
        <param name="waitTime"><span data-ttu-id="406af-117">Die Gesamtwartezeit für alle Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-117">The total wait time of all tasks in the job.</span></span></param>
        <summary>
            <span data-ttu-id="406af-118">Initialisiert eine neue Instanz der JobStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="406af-118">Initializes a new instance of the JobStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KernelCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan KernelCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan KernelCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.KernelCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property KernelCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.KernelCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.KernelCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kernelCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-119">Ruft ab oder legt den insgesamt Kernel-Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-119">Gets or sets the total kernel mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-120">Ruft ab oder legt die Zeit, an der die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="406af-120">Gets or sets the time at which the statistics were last updated.</span></span>
            <span data-ttu-id="406af-121">Alle Statistiken sind beschränkt auf den Bereich zwischen StartTime und LastUpdateTime.</span><span class="sxs-lookup"><span data-stu-id="406af-121">All statistics are limited to the range between startTime and lastUpdateTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumFailedTasks">
      <MemberSignature Language="C#" Value="public long NumFailedTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumFailedTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumFailedTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property NumFailedTasks As Long" />
      <MemberSignature Language="F#" Value="member this.NumFailedTasks : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumFailedTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numFailedTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-122">Ruft ab oder legt die Gesamtzahl der Aufgaben im Auftrag, die während des angegebenen Zeitraums fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="406af-122">Gets or sets the total number of tasks in the job that failed during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="406af-123">Ein Task fehlschlägt, wenn sie die maximale Anzahl von Wiederholungsversuchen schöpft, ohne den Exitcode 0 zurückgeben.</span><span class="sxs-lookup"><span data-stu-id="406af-123">A task fails if it exhausts its maximum retry count without returning exit code 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumSucceededTasks">
      <MemberSignature Language="C#" Value="public long NumSucceededTasks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumSucceededTasks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumSucceededTasks" />
      <MemberSignature Language="VB.NET" Value="Public Property NumSucceededTasks As Long" />
      <MemberSignature Language="F#" Value="member this.NumSucceededTasks : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumSucceededTasks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numSucceededTasks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-124">Ruft ab oder legt die Gesamtzahl der Aufgaben im Auftrag während des angegebenen Zeitraums erfolgreich abgeschlossen.</span><span class="sxs-lookup"><span data-stu-id="406af-124">Gets or sets the total number of tasks successfully completed in the job during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="406af-125">Eine Aufgabe wird erfolgreich abgeschlossen, wenn es den Exitcode 0 zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="406af-125">A task completes successfully if it returns exit code 0.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NumTaskRetries">
      <MemberSignature Language="C#" Value="public long NumTaskRetries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumTaskRetries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumTaskRetries" />
      <MemberSignature Language="VB.NET" Value="Public Property NumTaskRetries As Long" />
      <MemberSignature Language="F#" Value="member this.NumTaskRetries : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.NumTaskRetries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numTaskRetries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-126">Ruft ab oder legt die Gesamtanzahl der Wiederholungen für alle Aufgaben im Auftrag während des angegebenen Zeitraums fest.</span><span class="sxs-lookup"><span data-stu-id="406af-126">Gets or sets the total number of retries on all the tasks in the job during the given time range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOGiB">
      <MemberSignature Language="C#" Value="public double ReadIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 ReadIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.ReadIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-127">Ruft ab oder legt die Gesamtmenge der Daten in gib betragen, die vom Datenträger gelesen werden, indem Sie alle Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-127">Gets or sets the total amount of data in GiB read from disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadIOps">
      <MemberSignature Language="C#" Value="public long ReadIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 ReadIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadIOps As Long" />
      <MemberSignature Language="F#" Value="member this.ReadIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.ReadIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="readIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-128">Ruft ab oder legt die Gesamtanzahl der Datenträger-Lesevorgänge aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-128">Gets or sets the total number of disk read operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-129">Ruft ab oder legt die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="406af-129">Gets or sets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-130">Ruft ab oder legt die URL der Statistik.</span><span class="sxs-lookup"><span data-stu-id="406af-130">Gets or sets the URL of the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserCPUTime">
      <MemberSignature Language="C#" Value="public TimeSpan UserCPUTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan UserCPUTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.UserCPUTime" />
      <MemberSignature Language="VB.NET" Value="Public Property UserCPUTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.UserCPUTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.UserCPUTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="userCPUTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-131">Ruft ab oder legt die Gesamtzeit Modus CPU-Zeit (addierten auf alle Kerne und alle Serverknoten) aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-131">Gets or sets the total user mode CPU time (summed across all cores and all compute nodes) consumed by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobStatistics.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="406af-132">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="406af-132">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="406af-133">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="406af-133">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="WaitTime">
      <MemberSignature Language="C#" Value="public TimeSpan WaitTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WaitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WaitTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WaitTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WaitTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WaitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="waitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-134">Ruft ab oder legt die Gesamtwartezeit für alle Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-134">Gets or sets the total wait time of all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="406af-135">Die Wartezeit für eine Aufgabe wird als die Zeitspanne zwischen dem Erstellen der Aufgabe und dem Start der Ausführung der Aufgabe definiert.</span><span class="sxs-lookup"><span data-stu-id="406af-135">The wait time for a task is defined as the elapsed time between the creation of the task and the start of task execution.</span></span> <span data-ttu-id="406af-136">(Wenn die Aufgabe aufgrund von Fehlern wiederholt wird, ist die Wartezeit der Zeit der letzten Ausführung der Aufgabe.) Dieser Wert wird nur in der lebensdauerstatistiken Konto gemeldet; Es ist nicht in der Auftragsstatistik enthalten.</span><span class="sxs-lookup"><span data-stu-id="406af-136">(If the task is retried due to failures, the wait time is the time to the most recent task execution.) This value is only reported in the account lifetime statistics; it is not included in the job statistics.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WallClockTime">
      <MemberSignature Language="C#" Value="public TimeSpan WallClockTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan WallClockTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WallClockTime" />
      <MemberSignature Language="VB.NET" Value="Public Property WallClockTime As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.WallClockTime : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WallClockTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="wallClockTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-137">Ruft ab oder legt die gesamtbetrachtungszeit aller Aufgaben im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="406af-137">Gets or sets the total wall clock time of all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="406af-138">Die gesamtbetrachtungszeit wird von den Beginn des Tasks ausführen auf einem Serverknoten, wenn er abgeschlossen verstrichene Zeit (oder zum Zeitpunkt letzten Statistiken wurden aktualisiert, wenn die Aufgabe wurde nicht abgeschlossen war).</span><span class="sxs-lookup"><span data-stu-id="406af-138">The wall clock time is the elapsed time from when the task started running on a compute node to when it finished (or to the last time the statistics were updated, if the task had not finished by then).</span></span>
            <span data-ttu-id="406af-139">Wenn eine Aufgabe wiederholt wurde, schließt dies die gesamtbetrachtungszeit alle Wiederholungen der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="406af-139">If a task was retried, this includes the wall clock time of all the task retries.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOGiB">
      <MemberSignature Language="C#" Value="public double WriteIOGiB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 WriteIOGiB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOGiB" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOGiB As Double" />
      <MemberSignature Language="F#" Value="member this.WriteIOGiB : double with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOGiB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOGiB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-140">Ruft ab oder legt die Gesamtmenge der Daten in gib betragen, indem Sie alle Aufgaben im Auftrag auf den Datenträger geschrieben.</span><span class="sxs-lookup"><span data-stu-id="406af-140">Gets or sets the total amount of data in GiB written to disk by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WriteIOps">
      <MemberSignature Language="C#" Value="public long WriteIOps { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 WriteIOps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOps" />
      <MemberSignature Language="VB.NET" Value="Public Property WriteIOps As Long" />
      <MemberSignature Language="F#" Value="member this.WriteIOps : int64 with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobStatistics.WriteIOps" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="writeIOps")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="406af-141">Ruft ab oder legt die Gesamtanzahl der Schreibvorgänge auf Datenträger durch alle Aufgaben im Auftrag vorgenommen.</span><span class="sxs-lookup"><span data-stu-id="406af-141">Gets or sets the total number of disk write operations made by all tasks in the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>