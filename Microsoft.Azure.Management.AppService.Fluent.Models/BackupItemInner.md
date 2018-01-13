<Type Name="BackupItemInner" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner">
  <TypeSignature Language="C#" Value="public class BackupItemInner : Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupItemInner extends Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupItemInner&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type BackupItemInner = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.AppService.Fluent.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8e231-101">Beschreibung der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="8e231-101">Backup description.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupItemInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8e231-102">Initialisiert eine neue Instanz der BackupItemInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8e231-102">Initializes a new instance of the BackupItemInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupItemInner (string id = null, string name = null, string kind = null, string type = null, Nullable&lt;int&gt; backupId = null, string storageAccountUrl = null, string blobName = null, string backupItemName = null, Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt; status = null, Nullable&lt;long&gt; sizeInBytes = null, Nullable&lt;DateTime&gt; created = null, string log = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; databases = null, Nullable&lt;bool&gt; scheduled = null, Nullable&lt;DateTime&gt; lastRestoreTimeStamp = null, Nullable&lt;DateTime&gt; finishedTimeStamp = null, string correlationId = null, Nullable&lt;long&gt; websiteSizeInBytes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, valuetype System.Nullable`1&lt;int32&gt; backupId, string storageAccountUrl, string blobName, string backupItemName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt; status, valuetype System.Nullable`1&lt;int64&gt; sizeInBytes, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; created, string log, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; databases, valuetype System.Nullable`1&lt;bool&gt; scheduled, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRestoreTimeStamp, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; finishedTimeStamp, string correlationId, valuetype System.Nullable`1&lt;int64&gt; websiteSizeInBytes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus},System.Nullable{System.Int64},System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting},System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional backupId As Nullable(Of Integer) = null, Optional storageAccountUrl As String = null, Optional blobName As String = null, Optional backupItemName As String = null, Optional status As Nullable(Of BackupItemStatus) = null, Optional sizeInBytes As Nullable(Of Long) = null, Optional created As Nullable(Of DateTime) = null, Optional log As String = null, Optional databases As IList(Of DatabaseBackupSetting) = null, Optional scheduled As Nullable(Of Boolean) = null, Optional lastRestoreTimeStamp As Nullable(Of DateTime) = null, Optional finishedTimeStamp As Nullable(Of DateTime) = null, Optional correlationId As String = null, Optional websiteSizeInBytes As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner : string * string * string * string * Nullable&lt;int&gt; * string * string * string * Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt; * Nullable&lt;int64&gt; * Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner (id, name, kind, type, backupId, storageAccountUrl, blobName, backupItemName, status, sizeInBytes, created, log, databases, scheduled, lastRestoreTimeStamp, finishedTimeStamp, correlationId, websiteSizeInBytes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
        <Parameter Name="status" Type="System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt;" />
        <Parameter Name="sizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="created" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="log" Type="System.String" />
        <Parameter Name="databases" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt;" />
        <Parameter Name="scheduled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="lastRestoreTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="finishedTimeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="correlationId" Type="System.String" />
        <Parameter Name="websiteSizeInBytes" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="kind">To be added.</param>
        <param name="type">To be added.</param>
        <param name="backupId">To be added.</param>
        <param name="storageAccountUrl">To be added.</param>
        <param name="blobName">To be added.</param>
        <param name="backupItemName">To be added.</param>
        <param name="status">To be added.</param>
        <param name="sizeInBytes">To be added.</param>
        <param name="created">To be added.</param>
        <param name="log">To be added.</param>
        <param name="databases">To be added.</param>
        <param name="scheduled">To be added.</param>
        <param name="lastRestoreTimeStamp">To be added.</param>
        <param name="finishedTimeStamp">To be added.</param>
        <param name="correlationId">To be added.</param>
        <param name="websiteSizeInBytes">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BackupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BackupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BackupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BackupId : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BackupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-103">Ruft die Id des Sicherungssatzes ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-103">Gets id of the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupItemName">
      <MemberSignature Language="C#" Value="public string BackupItemName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupItemName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BackupItemName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupItemName As String" />
      <MemberSignature Language="F#" Value="member this.BackupItemName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BackupItemName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-104">Ruft die Namen dieser Sicherung ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-104">Gets name of this backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BlobName">
      <MemberSignature Language="C#" Value="public string BlobName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BlobName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BlobName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BlobName As String" />
      <MemberSignature Language="F#" Value="member this.BlobName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.BlobName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-105">Ruft den Namen des BLOBs die Daten für diese Sicherung enthält.</span><span class="sxs-lookup"><span data-stu-id="8e231-105">Gets name of the blob which contains data for this backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public string CorrelationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CorrelationId As String" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-106">Ruft die eindeutige Korrelations-ID ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-106">Gets unique correlation identifier.</span></span> <span data-ttu-id="8e231-107">Verwenden Sie diese zusammen mit dem Zeitstempel, bei der Kommunikation mit Azure-Support.</span><span class="sxs-lookup"><span data-stu-id="8e231-107">Please use this along with the timestamp while communicating with Azure support.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Created">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; Created { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; Created" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Created" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Created As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.Created : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Created" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-108">Ruft den Zeitstempel der Erstellung der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="8e231-108">Gets timestamp of the backup creation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Databases">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; Databases { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt; Databases" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Databases" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Databases As IList(Of DatabaseBackupSetting)" />
      <MemberSignature Language="F#" Value="member this.Databases : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Databases" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databases")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DatabaseBackupSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e231-109">Ruft die Liste der Datenbanken, die in der Sicherung enthalten.</span><span class="sxs-lookup"><span data-stu-id="8e231-109">Gets list of databases included in the backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FinishedTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; FinishedTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; FinishedTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.FinishedTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FinishedTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.FinishedTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.FinishedTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-110">Ruft Zeitstempel ab, wenn Sie diese Sicherung fertig sind.</span><span class="sxs-lookup"><span data-stu-id="8e231-110">Gets timestamp when this backup finished.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRestoreTimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRestoreTimeStamp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRestoreTimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.LastRestoreTimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRestoreTimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRestoreTimeStamp : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.LastRestoreTimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-111">Ruft die Zeitstempel von einem letzten Restore-Vorgang der Sicherung verwendet.</span><span class="sxs-lookup"><span data-stu-id="8e231-111">Gets timestamp of a last restore operation which used this backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Log">
      <MemberSignature Language="C#" Value="public string Log { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Log" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Log" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Log As String" />
      <MemberSignature Language="F#" Value="member this.Log : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Log" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-112">Ruft Details in Bezug auf diese Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="8e231-112">Gets details regarding this backup.</span></span> <span data-ttu-id="8e231-113">Sie enthalten eine Fehlermeldung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="8e231-113">Might contain an error message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Scheduled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Scheduled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Scheduled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Scheduled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Scheduled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Scheduled : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Scheduled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-114">Ruft "true", wenn aufgrund eines Zeitplans wird ausgelöst, diese Sicherung erstellt wurde.</span><span class="sxs-lookup"><span data-stu-id="8e231-114">Gets true if this backup has been created due to a schedule being triggered.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; SizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; SizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.SizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.SizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.SizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-115">Ruft die Größe des Sicherungssatzes in Bytes ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-115">Gets size of the backup in bytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt; Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt; Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As Nullable(Of BackupItemStatus)" />
      <MemberSignature Language="F#" Value="member this.Status : Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8e231-116">Ruft Sicherungsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-116">Gets backup status.</span></span> <span data-ttu-id="8e231-117">Folgende Werte sind möglich: "InProgress", "Fehler", "Succeeded", "TimedOut", "Erstellt", "Übersprungen", "" partiallysucceeded "aufweist., 'DeleteInProgress',"DeleteFailed","Gelöscht"</span><span class="sxs-lookup"><span data-stu-id="8e231-117">Possible values include: 'InProgress', 'Failed', 'Succeeded', 'TimedOut', 'Created', 'Skipped', 'PartiallySucceeded', 'DeleteInProgress', 'DeleteFailed', 'Deleted'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccountUrl">
      <MemberSignature Language="C#" Value="public string StorageAccountUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StorageAccountUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.StorageAccountUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccountUrl As String" />
      <MemberSignature Language="F#" Value="member this.StorageAccountUrl : string" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.StorageAccountUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-118">Ruft den SAS-URL für den Container des Speicherkontos enthält diese Sicherung ab.</span><span class="sxs-lookup"><span data-stu-id="8e231-118">Gets SAS URL for the storage account container which contains this backup.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WebsiteSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; WebsiteSizeInBytes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; WebsiteSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.WebsiteSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebsiteSizeInBytes As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.WebsiteSizeInBytes : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.BackupItemInner.WebsiteSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="8e231-119">Ruft die Größe der ursprünglichen Web-app die gesichert wurde.</span><span class="sxs-lookup"><span data-stu-id="8e231-119">Gets size of the original web app which has been backed up.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>