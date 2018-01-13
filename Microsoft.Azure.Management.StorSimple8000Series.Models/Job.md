<Type Name="Job" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Job">
  <TypeSignature Language="C#" Value="public class Job : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Job extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Job" />
  <TypeSignature Language="VB.NET" Value="Public Class Job&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Job = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5ab02-101">Der Auftrag.</span><span class="sxs-lookup"><span data-stu-id="5ab02-101">The job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-102">Initialisiert eine neue Instanz der Klasse Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="5ab02-102">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Job (Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus status, int percentComplete, Microsoft.Azure.Management.StorSimple8000Series.Models.JobType jobType, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails error = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics dataStats = null, string entityLabel = null, string entityType = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; jobStages = null, string deviceId = null, Nullable&lt;bool&gt; isCancellable = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType = null, string sourceDeviceId = null, Nullable&lt;DateTime&gt; backupPointInTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus status, int32 percentComplete, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobType jobType, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, class Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails error, class Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics dataStats, string entityLabel, string entityType, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; jobStages, string deviceId, valuetype System.Nullable`1&lt;bool&gt; isCancellable, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType, string sourceDeviceId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; backupPointInTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus,System.Int32,Microsoft.Azure.Management.StorSimple8000Series.Models.JobType,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails,Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage},System.String,System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType},System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Job : Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus * int * Microsoft.Azure.Management.StorSimple8000Series.Models.JobType * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails * Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; * string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Job" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Job (status, percentComplete, jobType, id, name, type, kind, startTime, endTime, error, dataStats, entityLabel, entityType, jobStages, deviceId, isCancellable, backupType, sourceDeviceId, backupPointInTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus" />
        <Parameter Name="percentComplete" Type="System.Int32" />
        <Parameter Name="jobType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.JobType" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="error" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails" />
        <Parameter Name="dataStats" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics" />
        <Parameter Name="entityLabel" Type="System.String" />
        <Parameter Name="entityType" Type="System.String" />
        <Parameter Name="jobStages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt;" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="isCancellable" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="backupType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt;" />
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="backupPointInTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="5ab02-103">Den aktuellen Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-103">The current status of the job.</span></span> <span data-ttu-id="5ab02-104">Folgende Werte sind möglich: "Wird ausgeführt", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="5ab02-104">Possible values include: 'Running', 'Succeeded', 'Failed', 'Canceled'</span></span></param>
        <param name="percentComplete"><span data-ttu-id="5ab02-105">Der Prozentsatz des Auftrags, der bereits abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5ab02-105">The percentage of the job that is already complete.</span></span></param>
        <param name="jobType"><span data-ttu-id="5ab02-106">Der Typ des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-106">The type of the job.</span></span> <span data-ttu-id="5ab02-107">Folgende Werte sind möglich: "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", "CreateCloudAppliance"</span><span class="sxs-lookup"><span data-stu-id="5ab02-107">Possible values include: 'ScheduledBackup', 'ManualBackup', 'RestoreBackup', 'CloneVolume', 'FailoverVolumeContainers', 'CreateLocallyPinnedVolume', 'ModifyVolume', 'InstallUpdates', 'SupportPackageLogs', 'CreateCloudAppliance'</span></span></param>
        <param name="id"><span data-ttu-id="5ab02-108">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="5ab02-108">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="5ab02-109">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="5ab02-109">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="5ab02-110">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="5ab02-110">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="5ab02-111">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="5ab02-111">The Kind of the object.</span></span> <span data-ttu-id="5ab02-112">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="5ab02-112">Currently only Series8000 is supported.</span></span> <span data-ttu-id="5ab02-113">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="5ab02-113">Possible values include: 'Series8000'</span></span></param>
        <param name="startTime"><span data-ttu-id="5ab02-114">Die UTC-Zeit, an der der Auftrag gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-114">The UTC time at which the job was started.</span></span></param>
        <param name="endTime"><span data-ttu-id="5ab02-115">Die UTC-Zeit, zu der der Auftrag abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-115">The UTC time at which the job completed.</span></span></param>
        <param name="error"><span data-ttu-id="5ab02-116">Die Fehlerdetails, sofern vorhanden, für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="5ab02-116">The error details, if any, for the job.</span></span></param>
        <param name="dataStats"><span data-ttu-id="5ab02-117">Die Daten Statistikeigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-117">The data statistics properties of the job.</span></span></param>
        <param name="entityLabel"><span data-ttu-id="5ab02-118">Der Entitätsbezeichner, für den der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-118">The entity identifier for which the job ran.</span></span></param>
        <param name="entityType"><span data-ttu-id="5ab02-119">Der Entitätstyp, für den der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-119">The entity type for which the job ran.</span></span></param>
        <param name="jobStages"><span data-ttu-id="5ab02-120">Die Phasen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-120">The job stages.</span></span></param>
        <param name="deviceId"><span data-ttu-id="5ab02-121">Die Geräte-ID in der der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-121">The device ID in which the job ran.</span></span></param>
        <param name="isCancellable"><span data-ttu-id="5ab02-122">Stellt dar, ob der Auftrag abgebrochen werden oder nicht.</span><span class="sxs-lookup"><span data-stu-id="5ab02-122">Represents whether the job is cancellable or not.</span></span></param>
        <param name="backupType"><span data-ttu-id="5ab02-123">Die Art der Sicherung (CloudSnapshot | LocalSnapshot).</span><span class="sxs-lookup"><span data-stu-id="5ab02-123">The backup type (CloudSnapshot | LocalSnapshot).</span></span> <span data-ttu-id="5ab02-124">Gilt nur für Sicherungsaufträge.</span><span class="sxs-lookup"><span data-stu-id="5ab02-124">Applicable only for backup jobs.</span></span> <span data-ttu-id="5ab02-125">Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"</span><span class="sxs-lookup"><span data-stu-id="5ab02-125">Possible values include: 'LocalSnapshot', 'CloudSnapshot'</span></span></param>
        <param name="sourceDeviceId"><span data-ttu-id="5ab02-126">Die Quelle Geräte-ID des Auftrags Failover.</span><span class="sxs-lookup"><span data-stu-id="5ab02-126">The source device ID of the failover job.</span></span></param>
        <param name="backupPointInTime"><span data-ttu-id="5ab02-127">Der Zeitpunkt der Sicherung für das Failover verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ab02-127">The time of the backup used for the failover.</span></span></param>
        <summary>
            <span data-ttu-id="5ab02-128">Initialisiert eine neue Instanz der Klasse Auftrag an.</span><span class="sxs-lookup"><span data-stu-id="5ab02-128">Initializes a new instance of the Job class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPointInTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; BackupPointInTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; BackupPointInTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.BackupPointInTime" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPointInTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.BackupPointInTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.BackupPointInTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPointInTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-129">Ruft ab oder legt den Zeitpunkt der Sicherung für das Failover verwendet.</span><span class="sxs-lookup"><span data-stu-id="5ab02-129">Gets or sets the time of the backup used for the failover.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As Nullable(Of BackupType)" />
      <MemberSignature Language="F#" Value="member this.BackupType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.BackupType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-130">Ruft ab oder legt den Sicherungstyp (CloudSnapshot | LocalSnapshot).</span><span class="sxs-lookup"><span data-stu-id="5ab02-130">Gets or sets the backup type (CloudSnapshot | LocalSnapshot).</span></span>
            <span data-ttu-id="5ab02-131">Gilt nur für Sicherungsaufträge.</span><span class="sxs-lookup"><span data-stu-id="5ab02-131">Applicable only for backup jobs.</span></span> <span data-ttu-id="5ab02-132">Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"</span><span class="sxs-lookup"><span data-stu-id="5ab02-132">Possible values include: 'LocalSnapshot', 'CloudSnapshot'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataStats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics DataStats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics DataStats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.DataStats" />
      <MemberSignature Language="VB.NET" Value="Public Property DataStats As DataStatistics" />
      <MemberSignature Language="F#" Value="member this.DataStats : Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.DataStats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataStats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-133">Ruft ab oder legt die Eigenschaften des Daten-Statistiken des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-133">Gets or sets the data statistics properties of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceId">
      <MemberSignature Language="C#" Value="public string DeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.DeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property DeviceId As String" />
      <MemberSignature Language="F#" Value="member this.DeviceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.DeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-134">Ruft ab oder legt die Geräte-ID, die in der der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-134">Gets or sets the device ID in which the job ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-135">Ruft ab oder legt die UTC-Zeit, zu der der Auftrag abgeschlossen wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-135">Gets or sets the UTC time at which the job completed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityLabel">
      <MemberSignature Language="C#" Value="public string EntityLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EntityLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityLabel As String" />
      <MemberSignature Language="F#" Value="member this.EntityLabel : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EntityLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.entityLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-136">Ruft ab oder legt den Bezeichner für die Entität für die der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-136">Gets or sets the entity identifier for which the job ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityType">
      <MemberSignature Language="C#" Value="public string EntityType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EntityType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EntityType" />
      <MemberSignature Language="VB.NET" Value="Public Property EntityType As String" />
      <MemberSignature Language="F#" Value="member this.EntityType : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.EntityType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.entityType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-137">Ruft ab oder legt den Entitätstyp, für den der Auftrag ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-137">Gets or sets the entity type for which the job ran.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails Error { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.Error" />
      <MemberSignature Language="VB.NET" Value="Public Property Error As JobErrorDetails" />
      <MemberSignature Language="F#" Value="member this.Error : Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.JobErrorDetails</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-138">Ruft ab oder legt die Fehlerdetails, sofern vorhanden, für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="5ab02-138">Gets or sets the error details, if any, for the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCancellable">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsCancellable { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsCancellable" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.IsCancellable" />
      <MemberSignature Language="VB.NET" Value="Public Property IsCancellable As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsCancellable : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.IsCancellable" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.isCancellable")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-139">Ruft ab oder legt darstellt, ob der Auftrag abgebrochen werden oder nicht.</span><span class="sxs-lookup"><span data-stu-id="5ab02-139">Gets or sets represents whether the job is cancellable or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobStages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; JobStages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; JobStages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.JobStages" />
      <MemberSignature Language="VB.NET" Value="Public Property JobStages As IList(Of JobStage)" />
      <MemberSignature Language="F#" Value="member this.JobStages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.JobStages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobStages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.JobStage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-140">Ermittelt oder definiert die Phasen des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-140">Gets or sets the job stages.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.JobType JobType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobType JobType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.JobType" />
      <MemberSignature Language="VB.NET" Value="Public Property JobType As JobType" />
      <MemberSignature Language="F#" Value="member this.JobType : Microsoft.Azure.Management.StorSimple8000Series.Models.JobType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.JobType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-141">Ruft ab oder legt den Typ des Auftrags fest.</span><span class="sxs-lookup"><span data-stu-id="5ab02-141">Gets or sets the type of the job.</span></span> <span data-ttu-id="5ab02-142">Folgende Werte sind möglich: "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", "CreateCloudAppliance"</span><span class="sxs-lookup"><span data-stu-id="5ab02-142">Possible values include: 'ScheduledBackup', 'ManualBackup', 'RestoreBackup', 'CloneVolume', 'FailoverVolumeContainers', 'CreateLocallyPinnedVolume', 'ModifyVolume', 'InstallUpdates', 'SupportPackageLogs', 'CreateCloudAppliance'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PercentComplete">
      <MemberSignature Language="C#" Value="public int PercentComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 PercentComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.PercentComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property PercentComplete As Integer" />
      <MemberSignature Language="F#" Value="member this.PercentComplete : int with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.PercentComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="percentComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-143">Ruft ab oder legt den Prozentsatz des Auftrags, der bereits abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="5ab02-143">Gets or sets the percentage of the job that is already complete.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDeviceId">
      <MemberSignature Language="C#" Value="public string SourceDeviceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDeviceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.SourceDeviceId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDeviceId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDeviceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.SourceDeviceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDeviceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-144">Ruft ab oder legt die Quelle Geräte-ID des Auftrags Failover.</span><span class="sxs-lookup"><span data-stu-id="5ab02-144">Gets or sets the source device ID of the failover job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-145">Ruft ab oder legt die UTC-Zeit, an der der Auftrag gestartet wurde.</span><span class="sxs-lookup"><span data-stu-id="5ab02-145">Gets or sets the UTC time at which the job was started.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As JobStatus" />
      <MemberSignature Language="F#" Value="member this.Status : Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Job.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.JobStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-146">Ruft ab oder legt den aktuellen Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="5ab02-146">Gets or sets the current status of the job.</span></span> <span data-ttu-id="5ab02-147">Folgende Werte sind möglich: "Wird ausgeführt", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "abgebrochen"</span><span class="sxs-lookup"><span data-stu-id="5ab02-147">Possible values include: 'Running', 'Succeeded', 'Failed', 'Canceled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Job.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="job.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ab02-148">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5ab02-148">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5ab02-149">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5ab02-149">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>