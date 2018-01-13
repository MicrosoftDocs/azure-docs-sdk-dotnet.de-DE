<Type Name="BackupSchedule" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule">
  <TypeSignature Language="C#" Value="public class BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupSchedule extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupSchedule&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type BackupSchedule = class&#xA;    inherit BaseModel" />
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
            Der Sicherungszeitplan.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupSchedule (Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, long retentionCount, DateTime startTime, Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;DateTime&gt; lastSuccessfulRun = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence scheduleRecurrence, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType backupType, int64 retentionCount, valuetype System.DateTime startTime, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus scheduleStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastSuccessfulRun) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType,System.Int64,System.DateTime,Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType * int64 * DateTime * Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule (scheduleRecurrence, backupType, retentionCount, startTime, scheduleStatus, id, name, type, kind, lastSuccessfulRun)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="scheduleRecurrence" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence" />
        <Parameter Name="backupType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType" />
        <Parameter Name="retentionCount" Type="System.Int64" />
        <Parameter Name="startTime" Type="System.DateTime" />
        <Parameter Name="scheduleStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="lastSuccessfulRun" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="scheduleRecurrence">Der Zeitplan für Wiederholungen.</param>
        <param name="backupType">Der Typ der Sicherung dar, die ausgeführt werden muss. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"</param>
        <param name="retentionCount">Die Anzahl der Sicherungen aufbewahrt werden sollen.</param>
        <param name="startTime">Die Startzeit des Zeitplans.</param>
        <param name="scheduleStatus">Den Zeitplanstatus. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="lastSuccessfulRun">Der letzten erfolgreichen Sicherung ausführen, die für den Zeitplan ausgelöst wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der BackupSchedule-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As BackupType" />
      <MemberSignature Language="F#" Value="member this.BackupType : Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.BackupType" />
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
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ der Sicherung dar, die ausgeführt werden muss. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSuccessfulRun">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastSuccessfulRun { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastSuccessfulRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberSignature Language="VB.NET" Value="Public Property LastSuccessfulRun As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastSuccessfulRun : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.LastSuccessfulRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastSuccessfulRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die letzte erfolgreiche Sicherung ausführen, die für den Zeitplan ausgelöst wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetentionCount">
      <MemberSignature Language="C#" Value="public long RetentionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RetentionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property RetentionCount As Long" />
      <MemberSignature Language="F#" Value="member this.RetentionCount : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.RetentionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.retentionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Sicherungen aufbewahrt werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleRecurrence">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence ScheduleRecurrence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleRecurrence As ScheduleRecurrence" />
      <MemberSignature Language="F#" Value="member this.ScheduleRecurrence : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleRecurrence" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleRecurrence")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleRecurrence</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt der Zeitplan für Wiederholungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScheduleStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus ScheduleStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ScheduleStatus As ScheduleStatus" />
      <MemberSignature Language="F#" Value="member this.ScheduleStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.ScheduleStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduleStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.ScheduleStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitplanstatus. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit des Zeitplans.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backupSchedule.Validate " />
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