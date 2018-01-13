<Type Name="BackupItem" FullName="Microsoft.Azure.Management.WebSites.Models.BackupItem">
  <TypeSignature Language="C#" Value="public class BackupItem : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupItem extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.BackupItem" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupItem&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type BackupItem = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibung der Sicherung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupItem ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.BackupItem.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupItem (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; backupId = null, string storageAccountUrl = null, string blobName = null, string backupItemName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt; status = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;DateTime&gt; created = null, string log = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; scheduled = null, Nullable&lt;DateTime&gt; lastRestoreTimeStamp = null, Nullable&lt;DateTime&gt; finishedTimeStamp = null, string correlationId = null, Nullable&lt;long&gt; websiteSizeInBytes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; backupId, string storageAccountUrl, string blobName, string backupItemName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt; status, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, string log, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; scheduled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRestoreTimeStamp, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; finishedTimeStamp, string correlationId, valuetype System.Nullable`1&lt;int64&gt; websiteSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.BackupItem.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.BackupItemStatus},System.Nullable{System.Int64},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional backupId As Nullable(Of Integer) = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional backupItemName As String = null, Optional status As Nullable(Of BackupItemStatus) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional created As Nullable(Of DateTime) = null, Optional log As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional scheduled As Nullable(Of Boolean) = null, Optional lastRestoreTimeStamp As Nullable(Of DateTime) = null, Optional finishedTimeStamp As Nullable(Of DateTime) = null, Optional correlationId As String = null, Optional websiteSizeInBytes As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.BackupItem : string * string * string * string * Nullable&lt;int&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.BackupItem" Usage="new Microsoft.Azure.Management.WebSites.Models.BackupItem (id, name, kind, type, backupId, storageAccountUrl, blobName, backupItemName, status, sizeInBytes, created, log, databases, scheduled, lastRestoreTimeStamp, finishedTimeStamp, correlationId, websiteSizeInBytes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="backupId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="storageAccountUrl" Type="System.String" />
        <Parameter Name="blobName" Type="System.String" />
        <Parameter Name="backupItemName" Type="System.String" />
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="log" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="scheduled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastRestoreTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="finishedTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="websiteSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id.</param>
        <param name="name">Ressourcenname.</param>
        <param name="kind">Die Art der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="backupId">Die ID der Sicherung.</param>
        <param name="storageAccountUrl">SAS-URL für den Container des Speicherkontos, der Sicherung enthält.</param>
        <param name="blobName">Der Name des BLOBs die Daten für diese Sicherung enthält.</param>
        <param name="backupItemName">Der Name dieser Sicherung.</param>
        <param name="status">Sicherungsstatus. Folgende Werte sind möglich: "InProgress", "Fehler", "Succeeded", "TimedOut", "Erstellt", "Übersprungen", "" partiallysucceeded "aufweist., 'DeleteInProgress',"DeleteFailed","Gelöscht"</param>
        <param name="sizeInBytes">Die Größe des Sicherungssatzes in Byte.</param>
        <param name="created">Zeitstempel der Erstellung der Sicherung.</param>
        <param name="log">Details in Bezug auf diese Sicherung. Sie enthalten eine Fehlermeldung angezeigt.</param>
        <param name="databases">Die Liste der Datenbanken, die in der Sicherung enthalten.</param>
        <param name="scheduled">"True", wenn aufgrund eines Zeitplans wird ausgelöst, diese Sicherung erstellt wurde.</param>
        <param name="lastRestoreTimeStamp">Zeitstempel einer letzten Wiederherstellung der Sicherung verwendet.</param>
        <param name="finishedTimeStamp">Zeitstempel für diese Sicherung abgeschlossen war.</param>
        <param name="correlationId">Eindeutige Korrelations-ID. Verwenden Sie diese zusammen mit dem Zeitstempel, bei der Kommunikation mit Azure-Support.</param>
        <param name="websiteSizeInBytes">Die Größe der ursprünglichen Web-app die gesichert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der BackupItem-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.BackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackupId : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.BackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Id des Sicherungssatzes ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupItemName">
      <MemberSignature Language="C#" Value="public string BackupItemName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupItemName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.BackupItemName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupItemName As String" />
      <MemberSignature Language="F#" Value="member this.BackupItemName : string" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.BackupItemName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Namen dieser Sicherung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.blobName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des BLOBs die Daten für diese Sicherung enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.correlationId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die eindeutige Korrelations-ID ab. Verwenden Sie diese zusammen mit dem Zeitstempel, bei der Kommunikation mit Azure-Support.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.created")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel der Erstellung der Sicherung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Datenbanken, die in der Sicherung enthalten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinishedTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FinishedTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FinishedTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.FinishedTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FinishedTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FinishedTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.FinishedTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.finishedTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Zeitstempel ab, wenn Sie diese Sicherung fertig sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRestoreTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRestoreTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRestoreTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.LastRestoreTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRestoreTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRestoreTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.LastRestoreTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastRestoreTimeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeitstempel von einem letzten Restore-Vorgang der Sicherung verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Log">
      <MemberSignature Language="C#" Value="public string Log { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Log" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.Log" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Log As String" />
      <MemberSignature Language="F#" Value="member this.Log : string" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.Log" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.log")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Details in Bezug auf diese Sicherung an. Sie enthalten eine Fehlermeldung angezeigt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheduled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Scheduled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Scheduled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.Scheduled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scheduled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Scheduled : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.Scheduled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scheduled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn aufgrund eines Zeitplans wird ausgelöst, diese Sicherung erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe des Sicherungssatzes in Bytes ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of BackupItemStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.BackupItemStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Sicherungsstatus ab. Folgende Werte sind möglich: "InProgress", "Fehler", "Succeeded", "TimedOut", "Erstellt", "Übersprungen", "" partiallysucceeded "aufweist., 'DeleteInProgress',"DeleteFailed","Gelöscht"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccountUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den SAS-URL für den Container des Speicherkontos enthält diese Sicherung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebsiteSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; WebsiteSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; WebsiteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.BackupItem.WebsiteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebsiteSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.WebsiteSizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.BackupItem.WebsiteSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.websiteSizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe der ursprünglichen Web-app die gesichert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>