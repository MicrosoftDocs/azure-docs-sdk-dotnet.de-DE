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
            Der Auftrag.
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
            Initialisiert eine neue Instanz der Klasse Auftrag an.
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
        <param name="status">Den aktuellen Status des Auftrags. Folgende Werte sind möglich: "Wird ausgeführt", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "abgebrochen"</param>
        <param name="percentComplete">Der Prozentsatz des Auftrags, der bereits abgeschlossen ist.</param>
        <param name="jobType">Der Typ des Auftrags. Folgende Werte sind möglich: "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", "CreateCloudAppliance"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="startTime">Die UTC-Zeit, an der der Auftrag gestartet wurde.</param>
        <param name="endTime">Die UTC-Zeit, zu der der Auftrag abgeschlossen wurde.</param>
        <param name="error">Die Fehlerdetails, sofern vorhanden, für den Auftrag.</param>
        <param name="dataStats">Die Daten Statistikeigenschaften des Auftrags.</param>
        <param name="entityLabel">Der Entitätsbezeichner, für den der Auftrag ausgeführt wurde.</param>
        <param name="entityType">Der Entitätstyp, für den der Auftrag ausgeführt wurde.</param>
        <param name="jobStages">Die Phasen des Auftrags.</param>
        <param name="deviceId">Die Geräte-ID in der der Auftrag ausgeführt wurde.</param>
        <param name="isCancellable">Stellt dar, ob der Auftrag abgebrochen werden oder nicht.</param>
        <param name="backupType">Die Art der Sicherung (CloudSnapshot | LocalSnapshot). Gilt nur für Sicherungsaufträge. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"</param>
        <param name="sourceDeviceId">Die Quelle Geräte-ID des Auftrags Failover.</param>
        <param name="backupPointInTime">Der Zeitpunkt der Sicherung für das Failover verwendet werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Auftrag an.
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
            Ruft ab oder legt den Zeitpunkt der Sicherung für das Failover verwendet.
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
            Ruft ab oder legt den Sicherungstyp (CloudSnapshot | LocalSnapshot).
            Gilt nur für Sicherungsaufträge. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"
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
            Ruft ab oder legt die Eigenschaften des Daten-Statistiken des Auftrags.
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
            Ruft ab oder legt die Geräte-ID, die in der der Auftrag ausgeführt wurde.
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
            Ruft ab oder legt die UTC-Zeit, zu der der Auftrag abgeschlossen wurde.
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
            Ruft ab oder legt den Bezeichner für die Entität für die der Auftrag ausgeführt wurde.
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
            Ruft ab oder legt den Entitätstyp, für den der Auftrag ausgeführt wurde.
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
            Ruft ab oder legt die Fehlerdetails, sofern vorhanden, für den Auftrag.
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
            Ruft ab oder legt darstellt, ob der Auftrag abgebrochen werden oder nicht.
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
            Ermittelt oder definiert die Phasen des Auftrags.
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
            Ruft ab oder legt den Typ des Auftrags fest. Folgende Werte sind möglich: "'ScheduledBackup'", "ManualBackup", "RestoreBackup", "CloneVolume", "FailoverVolumeContainers", "CreateLocallyPinnedVolume", "ModifyVolume", "InstallUpdates", "SupportPackageLogs", "CreateCloudAppliance"
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
            Ruft ab oder legt den Prozentsatz des Auftrags, der bereits abgeschlossen ist.
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
            Ruft ab oder legt die Quelle Geräte-ID des Auftrags Failover.
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
            Ruft ab oder legt die UTC-Zeit, an der der Auftrag gestartet wurde.
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
            Ruft ab oder legt den aktuellen Status des Auftrags. Folgende Werte sind möglich: "Wird ausgeführt", "Erfolgreich abgeschlossen", "Fehlgeschlagen", "abgebrochen"
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>