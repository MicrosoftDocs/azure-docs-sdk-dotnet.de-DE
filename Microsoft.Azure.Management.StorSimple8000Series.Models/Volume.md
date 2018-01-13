<Type Name="Volume" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume">
  <TypeSignature Language="C#" Value="public class Volume : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Volume extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
  <TypeSignature Language="VB.NET" Value="Public Class Volume&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Volume = class&#xA;    inherit BaseModel" />
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
            Das Volume.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Volume-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Volume (long sizeInBytes, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType volumeType, System.Collections.Generic.IList&lt;string&gt; accessControlRecordIds, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus volumeStatus, Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus monitoringStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, string volumeContainerId = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; operationStatus = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; backupStatus = null, System.Collections.Generic.IList&lt;string&gt; backupPolicyIds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 sizeInBytes, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType volumeType, class System.Collections.Generic.IList`1&lt;string&gt; accessControlRecordIds, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus volumeStatus, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus monitoringStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, string volumeContainerId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; operationStatus, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; backupStatus, class System.Collections.Generic.IList`1&lt;string&gt; backupPolicyIds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.#ctor(System.Int64,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus,Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Volume : int64 * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus * Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Volume (sizeInBytes, volumeType, accessControlRecordIds, volumeStatus, monitoringStatus, id, name, type, kind, volumeContainerId, operationStatus, backupStatus, backupPolicyIds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sizeInBytes" Type="System.Int64" />
        <Parameter Name="volumeType" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType" />
        <Parameter Name="accessControlRecordIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="volumeStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus" />
        <Parameter Name="monitoringStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="volumeContainerId" Type="System.String" />
        <Parameter Name="operationStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt;" />
        <Parameter Name="backupStatus" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt;" />
        <Parameter Name="backupPolicyIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="sizeInBytes">Die Größe des Volumes in Bytes.</param>
        <param name="volumeType">Der Typ des Volumes. Folgende Werte sind möglich: "Mehrstufigen", "Archivierung", "LocallyPinned"</param>
        <param name="accessControlRecordIds">Die IDs der zugriffssteuerungsdatensatz, mit dem Volume verknüpft sind.</param>
        <param name="volumeStatus">Der Status des Volumes. Folgende Werte sind möglich: "Online", "Offline"</param>
        <param name="monitoringStatus">Der Überwachungsstatus des Volumes.
            Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="volumeContainerId">Die ID der Volume-Container, in dem dieses Volume erstellt wird.</param>
        <param name="operationStatus">Der Vorgangsstatus auf dem Volume.
            Folgende Werte sind möglich: 'None', 'Aktualisieren', 'Löschen', 'Wiederherstellen'</param>
        <param name="backupStatus">Der Sicherungsstatus des Volumes.
            Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="backupPolicyIds">Die IDs der Sicherungsrichtlinien, in denen dieses Volume gehört.</param>
        <summary>
            Initialisiert eine neue Instanz der Volume-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessControlRecordIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AccessControlRecordIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AccessControlRecordIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.AccessControlRecordIds" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessControlRecordIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AccessControlRecordIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.AccessControlRecordIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessControlRecordIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die IDs des Zugriffs Access Control Records, mit dem Volume verknüpft sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; BackupPolicyIds { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; BackupPolicyIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupPolicyIds" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupPolicyIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IDs der Sicherungsrichtlinien, in denen dieses Volume gehört.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; BackupStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; BackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupStatus As Nullable(Of BackupStatus)" />
      <MemberSignature Language="F#" Value="member this.BackupStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.BackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Sicherungsstatus des Volumes an. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus MonitoringStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus MonitoringStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.MonitoringStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitoringStatus As MonitoringStatus" />
      <MemberSignature Language="F#" Value="member this.MonitoringStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.MonitoringStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitoringStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MonitoringStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Überwachungsstatus des Volumes. Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationStatus">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; OperationStatus { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; OperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.OperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property OperationStatus As Nullable(Of OperationStatus)" />
      <MemberSignature Language="F#" Value="member this.OperationStatus : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.OperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.operationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.OperationStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Vorgangsstatus auf dem Volume. Folgende Werte sind möglich: 'None', 'Aktualisieren', 'Löschen', 'Wiederherstellen'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Größe des Volumes in Bytes fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="volume.Validate " />
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
    <Member MemberName="VolumeContainerId">
      <MemberSignature Language="C#" Value="public string VolumeContainerId { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainerId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeContainerId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeContainerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ID der Volume-Container, in dem dieses Volume erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus VolumeStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus VolumeStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeStatus As VolumeStatus" />
      <MemberSignature Language="F#" Value="member this.VolumeStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status des Volumes. Folgende Werte sind möglich: "Online", "Offline"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType VolumeType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType VolumeType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeType" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeType As VolumeType" />
      <MemberSignature Language="F#" Value="member this.VolumeType : Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume.VolumeType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumeType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Volumes fest. Folgende Werte sind möglich: "Mehrstufigen", "Archivierung", "LocallyPinned"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>