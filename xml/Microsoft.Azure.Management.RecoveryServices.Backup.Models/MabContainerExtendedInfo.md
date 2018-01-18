<Type Name="MabContainerExtendedInfo" FullName="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo">
  <TypeSignature Language="C#" Value="public class MabContainerExtendedInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MabContainerExtendedInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class MabContainerExtendedInfo" />
  <TypeSignature Language="F#" Value="type MabContainerExtendedInfo = class" />
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
            <span data-ttu-id="d7e14-101">Zusätzliche Informationen des Containers.</span><span class="sxs-lookup"><span data-stu-id="d7e14-101">Additional information of the container.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabContainerExtendedInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-102">Initialisiert eine neue Instanz der MabContainerExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d7e14-102">Initializes a new instance of the MabContainerExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MabContainerExtendedInfo (Nullable&lt;DateTime&gt; lastRefreshedAt = null, string backupItemType = null, System.Collections.Generic.IList&lt;string&gt; backupItems = null, string policyName = null, string lastBackupStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastRefreshedAt, string backupItemType, class System.Collections.Generic.IList`1&lt;string&gt; backupItems, string policyName, string lastBackupStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.#ctor(System.Nullable{System.DateTime},System.String,System.Collections.Generic.IList{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lastRefreshedAt As Nullable(Of DateTime) = null, Optional backupItemType As String = null, Optional backupItems As IList(Of String) = null, Optional policyName As String = null, Optional lastBackupStatus As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo : Nullable&lt;DateTime&gt; * string * System.Collections.Generic.IList&lt;string&gt; * string * string -&gt; Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo" Usage="new Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo (lastRefreshedAt, backupItemType, backupItems, policyName, lastBackupStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lastRefreshedAt" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="backupItemType" Type="System.String" />
        <Parameter Name="backupItems" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="lastBackupStatus" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="lastRefreshedAt"><span data-ttu-id="d7e14-103">Zeitstempel, wenn dieser Container aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="d7e14-103">Time stamp when this container was refreshed.</span></span></param>
        <param name="backupItemType"><span data-ttu-id="d7e14-104">Typ der Sicherung Elemente, die diesem Container zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="d7e14-104">Type of backup items associated with this container.</span></span> <span data-ttu-id="d7e14-105">Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</span><span class="sxs-lookup"><span data-stu-id="d7e14-105">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span></param>
        <param name="backupItems"><span data-ttu-id="d7e14-106">Liste der Sicherungselemente, die diesem Container zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="d7e14-106">List of backup items associated with this container.</span></span></param>
        <param name="policyName"><span data-ttu-id="d7e14-107">Sicherungsrichtlinie, die diesem Container zugeordnet sind.</span><span class="sxs-lookup"><span data-stu-id="d7e14-107">Backup policy associated with this container.</span></span></param>
        <param name="lastBackupStatus"><span data-ttu-id="d7e14-108">Aktuelle Sicherungsstatus dieses Containers.</span><span class="sxs-lookup"><span data-stu-id="d7e14-108">Latest backup status of this container.</span></span></param>
        <summary>
            <span data-ttu-id="d7e14-109">Initialisiert eine neue Instanz der MabContainerExtendedInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d7e14-109">Initializes a new instance of the MabContainerExtendedInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupItems">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; BackupItems { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; BackupItems" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.BackupItems" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupItems As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.BackupItems : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.BackupItems" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupItems")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-110">Ruft ab oder legt die Liste der Sicherungselemente, die diesem Container zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="d7e14-110">Gets or sets list of backup items associated with this container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupItemType">
      <MemberSignature Language="C#" Value="public string BackupItemType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BackupItemType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.BackupItemType" />
      <MemberSignature Language="VB.NET" Value="Public Property BackupItemType As String" />
      <MemberSignature Language="F#" Value="member this.BackupItemType : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.BackupItemType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="backupItemType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-111">Ruft ab oder legt ihn fest Sicherungselemente, die diesem Container zugeordneten.</span><span class="sxs-lookup"><span data-stu-id="d7e14-111">Gets or sets type of backup items associated with this container.</span></span>
            <span data-ttu-id="d7e14-112">Folgende Werte sind möglich: "Ungültig", "VM", "FileFolder", "AzureSqlDb", "SQLDB", "Exchange", "Sharepoint", "VMwareVM", "SystemState", "Client", "GenericDataSource"</span><span class="sxs-lookup"><span data-stu-id="d7e14-112">Possible values include: 'Invalid', 'VM', 'FileFolder', 'AzureSqlDb', 'SQLDB', 'Exchange', 'Sharepoint', 'VMwareVM', 'SystemState', 'Client', 'GenericDataSource'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastBackupStatus">
      <MemberSignature Language="C#" Value="public string LastBackupStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastBackupStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.LastBackupStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property LastBackupStatus As String" />
      <MemberSignature Language="F#" Value="member this.LastBackupStatus : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.LastBackupStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastBackupStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-113">Abrufen oder Festlegen der aktuelle Sicherungsstatus dieses Containers.</span><span class="sxs-lookup"><span data-stu-id="d7e14-113">Gets or sets latest backup status of this container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRefreshedAt">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastRefreshedAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastRefreshedAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.LastRefreshedAt" />
      <MemberSignature Language="VB.NET" Value="Public Property LastRefreshedAt As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastRefreshedAt : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.LastRefreshedAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastRefreshedAt")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-114">Ruft ab oder legt Zeitstempel aus, wenn dieser Container aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="d7e14-114">Gets or sets time stamp when this container was refreshed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PolicyName">
      <MemberSignature Language="C#" Value="public string PolicyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PolicyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.PolicyName" />
      <MemberSignature Language="VB.NET" Value="Public Property PolicyName As String" />
      <MemberSignature Language="F#" Value="member this.PolicyName : string with get, set" Usage="Microsoft.Azure.Management.RecoveryServices.Backup.Models.MabContainerExtendedInfo.PolicyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.RecoveryServices.Backup</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="policyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7e14-115">Ruft ab, oder legt die Sicherungsrichtlinie, die diesem Container zugeordneten fest.</span><span class="sxs-lookup"><span data-stu-id="d7e14-115">Gets or sets backup policy associated with this container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>