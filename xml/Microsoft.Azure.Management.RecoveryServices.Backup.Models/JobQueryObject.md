<Type Name="JobQueryObject" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject">
  <TypeSignature Language="C#" Value="public class JobQueryObject" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobQueryObject extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject" />
  <TypeSignature Language="VB.NET" Value="Public Class JobQueryObject" />
  <TypeSignature Language="F#" Value="type JobQueryObject = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="971a0-101">Filter, die eine Liste der Aufträge.</span><span class="sxs-lookup"><span data-stu-id="971a0-101">Filters to list the jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobQueryObject ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="971a0-102">Initialisiert eine neue Instanz der JobQueryObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="971a0-102">Initializes a new instance of the JobQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobQueryObject (string status = null, string backupManagementType = null, string operation = null, string jobId = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string status, string backupManagementType, string operation, string jobId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional status As String = null, Optional backupManagementType As String = null, Optional operation As String = null, Optional jobId As String = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject : string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject (status, backupManagementType, operation, jobId, startTime, endTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="backupManagementType" Type="System.String" />
        <Parameter Name="operation" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="status"><span data-ttu-id="971a0-103">Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="971a0-103">Status of the job.</span></span> <span data-ttu-id="971a0-104">Folgende Werte sind möglich: "Ungültig", "InProgress", "Abgeschlossen", "Fehlgeschlagen", "CompletedWithWarnings", "Abgebrochen", "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="971a0-104">Possible values include: 'Invalid', 'InProgress', 'Completed', 'Failed', 'CompletedWithWarnings', 'Cancelled', 'Cancelling'</span></span></param>
        <param name="backupManagementType"><span data-ttu-id="971a0-105">Typ der Sicherung Managmenent für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="971a0-105">Type of backup managmenent for the job.</span></span> <span data-ttu-id="971a0-106">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="971a0-106">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span></param>
        <param name="operation"><span data-ttu-id="971a0-107">Der Typ des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="971a0-107">Type of operation.</span></span> <span data-ttu-id="971a0-108">Folgende Werte sind möglich: "Ungültig", "Registrieren", 'UnRegister', "ConfigureBackup", "Backup", "Restore", "DisableBackup", "DeleteBackupData"</span><span class="sxs-lookup"><span data-stu-id="971a0-108">Possible values include: 'Invalid', 'Register', 'UnRegister', 'ConfigureBackup', 'Backup', 'Restore', 'DisableBackup', 'DeleteBackupData'</span></span></param>
        <param name="jobId"><span data-ttu-id="971a0-109">"JobID"-Wert den Auftrag eindeutig darstellt.</span><span class="sxs-lookup"><span data-stu-id="971a0-109">JobID represents the job uniquely.</span></span></param>
        <param name="startTime"><span data-ttu-id="971a0-110">Auftrag wurde zu diesem Zeitpunkt gestartet.</span><span class="sxs-lookup"><span data-stu-id="971a0-110">Job has started at this time.</span></span> <span data-ttu-id="971a0-111">Wert ist in UTC angegeben.</span><span class="sxs-lookup"><span data-stu-id="971a0-111">Value is in UTC.</span></span></param>
        <param name="endTime"><span data-ttu-id="971a0-112">Auftrag wurde zu diesem Zeitpunkt beendet.</span><span class="sxs-lookup"><span data-stu-id="971a0-112">Job has ended at this time.</span></span> <span data-ttu-id="971a0-113">Wert ist in UTC angegeben.</span><span class="sxs-lookup"><span data-stu-id="971a0-113">Value is in UTC.</span></span></param>
        <summary>
            <span data-ttu-id="971a0-114">Initialisiert eine neue Instanz der JobQueryObject-Klasse.</span><span class="sxs-lookup"><span data-stu-id="971a0-114">Initializes a new instance of the JobQueryObject class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupManagementType">
      <MemberSignature Language="C#" Value="public string BackupManagementType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupManagementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.BackupManagementType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupManagementType As String" />
      <MemberSignature Language="F#" Value="member this.BackupManagementType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.BackupManagementType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupManagementType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="971a0-115">Ruft ab oder legt ihn fest backup Managmenent für den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="971a0-115">Gets or sets type of backup managmenent for the job.</span></span> <span data-ttu-id="971a0-116">Folgende Werte sind möglich: "Ungültig", "AzureIaasVM", "MAB", "DPM", "AzureBackupServer", "Azure SQL"</span><span class="sxs-lookup"><span data-stu-id="971a0-116">Possible values include: 'Invalid', 'AzureIaasVM', 'MAB', 'DPM', 'AzureBackupServer', 'AzureSql'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="971a0-117">Ruft ab oder legt ihn fest Auftrag wurde beendet, zu diesem Zeitpunkt.</span><span class="sxs-lookup"><span data-stu-id="971a0-117">Gets or sets job has ended at this time.</span></span> <span data-ttu-id="971a0-118">Wert ist in UTC angegeben.</span><span class="sxs-lookup"><span data-stu-id="971a0-118">Value is in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="971a0-119">Ruft ab oder legt ihn fest "JobID"-Wert stellt den Auftrag eindeutig.</span><span class="sxs-lookup"><span data-stu-id="971a0-119">Gets or sets jobID represents the job uniquely.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Operation">
      <MemberSignature Language="C#" Value="public string Operation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Operation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.Operation" />
      <MemberSignature Language="VB.NET" Value="Public Property Operation As String" />
      <MemberSignature Language="F#" Value="member this.Operation : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.Operation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="971a0-120">Ruft ab oder legt ihn fest des Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="971a0-120">Gets or sets type of operation.</span></span> <span data-ttu-id="971a0-121">Folgende Werte sind möglich: "Ungültig", "Registrieren", 'UnRegister', "ConfigureBackup", "Backup", "Restore", "DisableBackup", "DeleteBackupData"</span><span class="sxs-lookup"><span data-stu-id="971a0-121">Possible values include: 'Invalid', 'Register', 'UnRegister', 'ConfigureBackup', 'Backup', 'Restore', 'DisableBackup', 'DeleteBackupData'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="971a0-122">Ruft ab oder legt ihn fest Auftrag wurde zu diesem Zeitpunkt gestartet.</span><span class="sxs-lookup"><span data-stu-id="971a0-122">Gets or sets job has started at this time.</span></span> <span data-ttu-id="971a0-123">Wert ist in UTC angegeben.</span><span class="sxs-lookup"><span data-stu-id="971a0-123">Value is in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.Status" />
      <MemberSignature Language="VB.NET" Value="Public Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.JobQueryObject.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="971a0-124">Abrufen oder Festlegen des Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="971a0-124">Gets or sets status of the job.</span></span> <span data-ttu-id="971a0-125">Folgende Werte sind möglich: "Ungültig", "InProgress", "Abgeschlossen", "Fehlgeschlagen", "CompletedWithWarnings", "Abgebrochen", "Abbrechen"</span><span class="sxs-lookup"><span data-stu-id="971a0-125">Possible values include: 'Invalid', 'InProgress', 'Completed', 'Failed', 'CompletedWithWarnings', 'Cancelled', 'Cancelling'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>