<Type Name="Backup" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup">
  <TypeSignature Language="C#" Value="public class Backup : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Backup extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup" />
  <TypeSignature Language="VB.NET" Value="Public Class Backup&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type Backup = class&#xA;    inherit BaseModel" />
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
            Die Sicherung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Backup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Backup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Backup (DateTime createdOn, long sizeInBytes, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; elements, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; backupJobCreationType = null, string backupPolicyId = null, string ssmHostName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.DateTime createdOn, int64 sizeInBytes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; elements, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; backupType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; backupJobCreationType, string backupPolicyId, string ssmHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.#ctor(System.DateTime,System.Int64,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (createdOn As DateTime, sizeInBytes As Long, elements As IList(Of BackupElement), Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional kind As Nullable(Of Kind) = null, Optional backupType As Nullable(Of BackupType) = null, Optional backupJobCreationType As Nullable(Of BackupJobCreationType) = null, Optional backupPolicyId As String = null, Optional ssmHostName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.Backup : DateTime * int64 * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Backup" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.Backup (createdOn, sizeInBytes, elements, id, name, type, kind, backupType, backupJobCreationType, backupPolicyId, ssmHostName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="createdOn" Type="System.DateTime" />
        <Parameter Name="sizeInBytes" Type="System.Int64" />
        <Parameter Name="elements" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt;" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="backupType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt;" />
        <Parameter Name="backupJobCreationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt;" />
        <Parameter Name="backupPolicyId" Type="System.String" />
        <Parameter Name="ssmHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="createdOn">Die Zeit, wenn die Sicherung erstellt wurde.</param>
        <param name="sizeInBytes">Die Sicherungsgröße in Bytes.</param>
        <param name="elements">Die backup-Elemente.</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="backupType">Der Typ der Sicherung. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"</param>
        <param name="backupJobCreationType">Der Typ des Sicherungsauftrags, des erstellen.
            Folgende Werte sind möglich: "Ad-hoc-", "BySchedule", "BySSM"</param>
        <param name="backupPolicyId">Die Pfad-ID der Sicherungsrichtlinie.</param>
        <param name="ssmHostName">Der Hostname des StorSimple-Momentaufnahme-Managers.</param>
        <summary>
            Initialisiert eine neue Instanz der Backup-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupJobCreationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; BackupJobCreationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; BackupJobCreationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupJobCreationType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupJobCreationType As Nullable(Of BackupJobCreationType)" />
      <MemberSignature Language="F#" Value="member this.BackupJobCreationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupJobCreationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupJobCreationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupJobCreationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert den Typ der Sicherungsauftrag erstellen. Folgende Werte sind möglich: "Ad-hoc-", "BySchedule", "BySSM"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicyId">
      <MemberSignature Language="C#" Value="public string BackupPolicyId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupPolicyId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupPolicyId" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupPolicyId As String" />
      <MemberSignature Language="F#" Value="member this.BackupPolicyId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupPolicyId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backupPolicyId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Pfad-ID der Sicherungsrichtlinie.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; BackupType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupType As Nullable(Of BackupType)" />
      <MemberSignature Language="F#" Value="member this.BackupType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.BackupType" />
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
            Ruft ab oder legt den Typ der Sicherung. Folgende Werte sind möglich: "LocalSnapshot", "CloudSnapshot"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedOn">
      <MemberSignature Language="C#" Value="public DateTime CreatedOn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.CreatedOn" />
      <MemberSignature Language="VB.NET" Value="Public Property CreatedOn As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedOn : DateTime with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.CreatedOn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdOn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Uhrzeit der Erstellung die Sicherung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Elements">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; Elements { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; Elements" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Elements" />
      <MemberSignature Language="VB.NET" Value="Public Property Elements As IList(Of BackupElement)" />
      <MemberSignature Language="F#" Value="member this.Elements : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Elements" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elements")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Sicherung Elemente.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public long SizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeInBytes As Long" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : int64 with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SizeInBytes" />
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
            Ruft ab oder legt die Größe in Bytes fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SsmHostName">
      <MemberSignature Language="C#" Value="public string SsmHostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SsmHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SsmHostName" />
      <MemberSignature Language="VB.NET" Value="Public Property SsmHostName As String" />
      <MemberSignature Language="F#" Value="member this.SsmHostName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.SsmHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ssmHostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hostnamen für den StorSimple Snapshot Manager fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.Backup.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="backup.Validate " />
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