<Type Name="DatabaseUpdate" FullName="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate">
  <TypeSignature Language="C#" Value="public class DatabaseUpdate : Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatabaseUpdate extends Microsoft.Azure.Management.Sql.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Class DatabaseUpdate&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type DatabaseUpdate = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Sql.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9eaa4-101">Stellt eine Aktualisierung der Datenbank dar.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-101">Represents a database update.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-102">Initialisiert eine neue Instanz der DatabaseUpdate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-102">Initializes a new instance of the DatabaseUpdate class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatabaseUpdate (string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string collation = null, Nullable&lt;DateTime&gt; creationDate = null, Nullable&lt;long&gt; containmentState = null, Nullable&lt;Guid&gt; currentServiceObjectiveId = null, Nullable&lt;Guid&gt; databaseId = null, Nullable&lt;DateTime&gt; earliestRestoreDate = null, string createMode = null, string sourceDatabaseId = null, Nullable&lt;DateTime&gt; sourceDatabaseDeletionDate = null, Nullable&lt;DateTime&gt; restorePointInTime = null, string recoveryServicesRecoveryPointResourceId = null, string edition = null, string maxSizeBytes = null, Nullable&lt;Guid&gt; requestedServiceObjectiveId = null, string requestedServiceObjectiveName = null, string serviceLevelObjective = null, string status = null, string elasticPoolName = null, string defaultSecondaryLocation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex = null, string failoverGroupId = null, Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale = null, string sampleName = null, Nullable&lt;bool&gt; zoneRedundant = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string collation, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationDate, valuetype System.Nullable`1&lt;int64&gt; containmentState, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; currentServiceObjectiveId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; databaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; earliestRestoreDate, string createMode, string sourceDatabaseId, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; sourceDatabaseDeletionDate, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; restorePointInTime, string recoveryServicesRecoveryPointResourceId, string edition, string maxSizeBytes, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; requestedServiceObjectiveId, string requestedServiceObjectiveName, string serviceLevelObjective, string status, string elasticPoolName, string defaultSecondaryLocation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; serviceTierAdvisors, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; transparentDataEncryption, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; recommendedIndex, string failoverGroupId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; readScale, string sampleName, valuetype System.Nullable`1&lt;bool&gt; zoneRedundant) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.#ctor(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{System.DateTime},System.Nullable{System.Int64},System.Nullable{System.Guid},System.Nullable{System.Guid},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.String,System.Nullable{System.Guid},System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption},System.Collections.Generic.IList{Microsoft.Azure.Management.Sql.Models.RecommendedIndex},System.String,System.Nullable{Microsoft.Azure.Management.Sql.Models.ReadScale},System.String,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional tags As IDictionary(Of String, String) = null, Optional collation As String = null, Optional creationDate As Nullable(Of DateTime) = null, Optional containmentState As Nullable(Of Long) = null, Optional currentServiceObjectiveId As Nullable(Of Guid) = null, Optional databaseId As Nullable(Of Guid) = null, Optional earliestRestoreDate As Nullable(Of DateTime) = null, Optional createMode As String = null, Optional sourceDatabaseId As String = null, Optional sourceDatabaseDeletionDate As Nullable(Of DateTime) = null, Optional restorePointInTime As Nullable(Of DateTime) = null, Optional recoveryServicesRecoveryPointResourceId As String = null, Optional edition As String = null, Optional maxSizeBytes As String = null, Optional requestedServiceObjectiveId As Nullable(Of Guid) = null, Optional requestedServiceObjectiveName As String = null, Optional serviceLevelObjective As String = null, Optional status As String = null, Optional elasticPoolName As String = null, Optional defaultSecondaryLocation As String = null, Optional serviceTierAdvisors As IList(Of ServiceTierAdvisor) = null, Optional transparentDataEncryption As IList(Of TransparentDataEncryption) = null, Optional recommendedIndex As IList(Of RecommendedIndex) = null, Optional failoverGroupId As String = null, Optional readScale As Nullable(Of ReadScale) = null, Optional sampleName As String = null, Optional zoneRedundant As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;DateTime&gt; * Nullable&lt;int64&gt; * Nullable&lt;Guid&gt; * Nullable&lt;Guid&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * string * Nullable&lt;Guid&gt; * string * string * string * string * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; * string * Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; * string * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Sql.Models.DatabaseUpdate" Usage="new Microsoft.Azure.Management.Sql.Models.DatabaseUpdate (id, name, type, tags, collation, creationDate, containmentState, currentServiceObjectiveId, databaseId, earliestRestoreDate, createMode, sourceDatabaseId, sourceDatabaseDeletionDate, restorePointInTime, recoveryServicesRecoveryPointResourceId, edition, maxSizeBytes, requestedServiceObjectiveId, requestedServiceObjectiveName, serviceLevelObjective, status, elasticPoolName, defaultSecondaryLocation, serviceTierAdvisors, transparentDataEncryption, recommendedIndex, failoverGroupId, readScale, sampleName, zoneRedundant)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="collation" Type="System.String" />
        <Parameter Name="creationDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="containmentState" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="currentServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="databaseId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="earliestRestoreDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="createMode" Type="System.String" />
        <Parameter Name="sourceDatabaseId" Type="System.String" />
        <Parameter Name="sourceDatabaseDeletionDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="restorePointInTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recoveryServicesRecoveryPointResourceId" Type="System.String" />
        <Parameter Name="edition" Type="System.String" />
        <Parameter Name="maxSizeBytes" Type="System.String" />
        <Parameter Name="requestedServiceObjectiveId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="requestedServiceObjectiveName" Type="System.String" />
        <Parameter Name="serviceLevelObjective" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="elasticPoolName" Type="System.String" />
        <Parameter Name="defaultSecondaryLocation" Type="System.String" />
        <Parameter Name="serviceTierAdvisors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" />
        <Parameter Name="transparentDataEncryption" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" />
        <Parameter Name="recommendedIndex" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" />
        <Parameter Name="failoverGroupId" Type="System.String" />
        <Parameter Name="readScale" Type="System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;" />
        <Parameter Name="sampleName" Type="System.String" />
        <Parameter Name="zoneRedundant" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="9eaa4-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="9eaa4-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="9eaa4-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="9eaa4-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-105">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="9eaa4-106">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-106">Resource tags.</span></span></param>
        <param name="collation"><span data-ttu-id="9eaa4-107">Die Sortierung der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-107">The collation of the database.</span></span> <span data-ttu-id="9eaa4-108">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-108">If createMode is not Default, this value is ignored.</span></span></param>
        <param name="creationDate"><span data-ttu-id="9eaa4-109">Das Erstellungsdatum der Datenbank (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="9eaa4-109">The creation date of the database (ISO8601 format).</span></span></param>
        <param name="containmentState"><span data-ttu-id="9eaa4-110">Die Containment-Status der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-110">The containment state of the database.</span></span></param>
        <param name="currentServiceObjectiveId"><span data-ttu-id="9eaa4-111">Die aktuelle Ebene dienstziel-ID der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-111">The current service level objective ID of the database.</span></span> <span data-ttu-id="9eaa4-112">Dies ist die ID des SLO, das derzeit aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-112">This is the ID of the service level objective that is currently active.</span></span></param>
        <param name="databaseId"><span data-ttu-id="9eaa4-113">Die ID der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-113">The ID of the database.</span></span></param>
        <param name="earliestRestoreDate"><span data-ttu-id="9eaa4-114">Diese Datensätze der frühesten Startdatum und-Uhrzeit, den die Wiederherstellung ist für diese Datenbank (ISO8601-Format) verfügbar.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-114">This records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span></param>
        <param name="createMode"><span data-ttu-id="9eaa4-115">Gibt den Modus der Datenbankerstellung.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-115">Specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="9eaa4-116">Standard: reguläre Datenbank erstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-116">Default: regular database creation.</span></span>
            
             <span data-ttu-id="9eaa4-117">Kopie: erstellt eine Datenbank als Kopie einer vorhandenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-117">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="9eaa4-118">SourceDatabaseId muss als die Ressourcen-ID der Quelldatenbank angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-118">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="9eaa4-119">OnlineSecondary/NonReadableSecondary: erstellt eine Datenbank als ein sekundäres Replikat (lesbar ist oder nicht lesbar) einer vorhandenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-119">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="9eaa4-120">SourceDatabaseId muss als die Ressourcen-ID der vorhandenen primären Datenbank angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-120">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="9eaa4-121">PointInTimeRestore: Erstellt eine Datenbank, indem Sie einen Punkt in der Sicherung einer vorhandenen Datenbank wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-121">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="9eaa4-122">SourceDatabaseId muss angegeben werden, wie die Ressourcen-ID der vorhandenen Datenbank und RestorePointInTime muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-122">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="9eaa4-123">Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung geografisch repliziert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-123">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="9eaa4-124">SourceDatabaseId muss als wiederherzustellenden die wiederherstellbare Datenbank Ressourcen-ID angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-124">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="9eaa4-125">Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung einer gelöschten Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-125">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="9eaa4-126">SourceDatabaseId muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-126">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="9eaa4-127">Wenn SourceDatabaseId ursprünglichen Ressourcen-ID der Datenbank ist, muss SourceDatabaseDeletionDate angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-127">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="9eaa4-128">Andernfalls muss SourceDatabaseId wiederherstellbare gelöschte Datenbank-Ressourcen-ID und SourceDatabaseDeletionDate wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-128">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="9eaa4-129">RestorePointInTime kann auch angegeben werden, aus einem früheren Zeitpunkt wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-129">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="9eaa4-130">RestoreLongTermRetentionBackup: Erstellt eine Datenbank über eine langfristige Beibehaltungsdauer Tresor wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-130">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="9eaa4-131">RecoveryServicesRecoveryPointResourceId muss als das Recovery Point-Ressourcen-ID angegeben werden</span><span class="sxs-lookup"><span data-stu-id="9eaa4-131">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="9eaa4-132">Copy-, NonReadableSecondary, OnlineSecondary und RestoreLongTermRetentionBackup werden für die Data Warehouse-Edition nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-132">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="9eaa4-133">Folgende Werte sind möglich: 'Kopieren', 'Default', "NonReadableSecondary", "OnlineSecondary", "PointInTimeRestore", 'Wiederherstellen', 'Wiederherstellen', 'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="9eaa4-133">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span></param>
        <param name="sourceDatabaseId"><span data-ttu-id="9eaa4-134">Bedingte.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-134">Conditional.</span></span> <span data-ttu-id="9eaa4-135">Wenn CreateMode kopieren, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Wiederherstellung oder Wiederherstellung ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-135">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="9eaa4-136">Gibt die Ressourcen-ID der Quelldatenbank an.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-136">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="9eaa4-137">Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, muss der Name der Quelldatenbank identisch mit der neuen Datenbank erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-137">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span></param>
        <param name="sourceDatabaseDeletionDate"><span data-ttu-id="9eaa4-138">Bedingte.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-138">Conditional.</span></span> <span data-ttu-id="9eaa4-139">Wenn CreateMode ist die Wiederherstellung und SourceDatabaseId ist die gelöschte Datenbank ursprünglichen-Ressourcen-Id aus, wenn sie (im Gegensatz zu seiner aktuellen wiederherstellbare gelöschte Datenbank-Id) vorhanden waren, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-139">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="9eaa4-140">Gibt die Zeit, die die Datenbank gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-140">Specifies the time that the database was deleted.</span></span></param>
        <param name="restorePointInTime"><span data-ttu-id="9eaa4-141">Bedingte.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-141">Conditional.</span></span> <span data-ttu-id="9eaa4-142">Wenn CreateMode PointInTimeRestore ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-142">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="9eaa4-143">Wenn CreateMode Wiederherstellung ist, ist dieser Wert optional.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-143">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="9eaa4-144">Angibt, an dem Punkt (ISO8601-Format) von der Quelldatenbank, die zum Erstellen der neuen Datenbank wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-144">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span> <span data-ttu-id="9eaa4-145">Muss größer als oder gleich der Quelldatenbank EarliestRestoreDate Wert sein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-145">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span></param>
        <param name="recoveryServicesRecoveryPointResourceId"><span data-ttu-id="9eaa4-146">Bedingte.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-146">Conditional.</span></span>
             <span data-ttu-id="9eaa4-147">Wenn CreateMode RestoreLongTermRetentionBackup ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-147">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span> <span data-ttu-id="9eaa4-148">Gibt die Ressourcen-ID des Wiederherstellungspunkts aus wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-148">Specifies the resource ID of the recovery point to restore from.</span></span></param>
        <param name="edition"><span data-ttu-id="9eaa4-149">Die Edition der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-149">The edition of the database.</span></span> <span data-ttu-id="9eaa4-150">Die DatabaseEditions-Enumeration enthält alle gültigen Editionen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-150">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="9eaa4-151">Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-151">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="9eaa4-152">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".</span><span class="sxs-lookup"><span data-stu-id="9eaa4-152">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="9eaa4-153">Folgende Werte sind möglich: 'Web', ' Business', 'Basic', 'Standard', "Premium", "Free", "Stretch", "Data Warehouse", "System", "System 2"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-153">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span></param>
        <param name="maxSizeBytes"><span data-ttu-id="9eaa4-154">Die maximale Größe der Datenbank in Bytes ausgedrückt.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-154">The max size of the database expressed in bytes.</span></span> <span data-ttu-id="9eaa4-155">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-155">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="9eaa4-156">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</span><span class="sxs-lookup"><span data-stu-id="9eaa4-156">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveId"><span data-ttu-id="9eaa4-157">Die konfigurierten Servicelevel dienstziel-ID der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-157">The configured service level objective ID of the database.</span></span> <span data-ttu-id="9eaa4-158">Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-158">This is the service level objective that is in the process of being applied to the database.</span></span>
             <span data-ttu-id="9eaa4-159">Nachdem erfolgreich aktualisiert wurde, wird es den Wert der Eigenschaft CurrentServiceObjectiveId überein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-159">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="9eaa4-160">Wenn RequestedServiceObjectiveId und RequestedServiceObjectiveName aktualisiert werden, überschreibt der Wert des RequestedServiceObjectiveId den Wert der RequestedServiceObjectiveName an.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-160">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="9eaa4-161">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</span><span class="sxs-lookup"><span data-stu-id="9eaa4-161">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span></param>
        <param name="requestedServiceObjectiveName"><span data-ttu-id="9eaa4-162">Der Name des konfigurierten SLO der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-162">The name of the configured service level objective of the database.</span></span> <span data-ttu-id="9eaa4-163">Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-163">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="9eaa4-164">Nachdem erfolgreich aktualisiert, wird es den Wert der Eigenschaft ServiceLevelObjective überein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-164">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span> <span data-ttu-id="9eaa4-165">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".</span><span class="sxs-lookup"><span data-stu-id="9eaa4-165">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
             <span data-ttu-id="9eaa4-166">Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-166">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="serviceLevelObjective"><span data-ttu-id="9eaa4-167">Das aktuelle SLO der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-167">The current service level objective of the database.</span></span> <span data-ttu-id="9eaa4-168">Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-168">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span></param>
        <param name="status"><span data-ttu-id="9eaa4-169">Der Status der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-169">The status of the database.</span></span></param>
        <param name="elasticPoolName"><span data-ttu-id="9eaa4-170">Der Name des elastischen Pools der Datenbank wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-170">The name of the elastic pool the database is in.</span></span> <span data-ttu-id="9eaa4-171">Wenn ElasticPoolName und RequestedServiceObjectiveName aktualisiert werden, wird der Wert der RequestedServiceObjectiveName ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-171">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="9eaa4-172">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-172">Not supported for DataWarehouse edition.</span></span></param>
        <param name="defaultSecondaryLocation"><span data-ttu-id="9eaa4-173">Die Standardeinstellung sekundäre Region für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-173">The default secondary region for this database.</span></span></param>
        <param name="serviceTierAdvisors"><span data-ttu-id="9eaa4-174">Die Liste der Service Tier Ratgeber für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-174">The list of service tier advisors for this database.</span></span> <span data-ttu-id="9eaa4-175">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="9eaa4-175">Expanded property</span></span></param>
        <param name="transparentDataEncryption"><span data-ttu-id="9eaa4-176">Transparent Data Encryption Info für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-176">The transparent data encryption info for this database.</span></span></param>
        <param name="recommendedIndex"><span data-ttu-id="9eaa4-177">Die empfohlenen Indizes für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-177">The recommended indices for this database.</span></span></param>
        <param name="failoverGroupId"><span data-ttu-id="9eaa4-178">Der Ressourcenbezeichner der Gruppe "Failover", die diese Datenbank enthält.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-178">The resource identifier of the failover group containing this database.</span></span></param>
        <param name="readScale"><span data-ttu-id="9eaa4-179">Bedingte.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-179">Conditional.</span></span> <span data-ttu-id="9eaa4-180">Wenn die Datenbank über geografische sekundäres Replikat ist, überprüfen, ob ReadScale schreibgeschützte Verbindungen zu dieser Datenbank zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-180">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="9eaa4-181">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-181">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="9eaa4-182">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-182">Possible values include: 'Enabled', 'Disabled'</span></span></param>
        <param name="sampleName"><span data-ttu-id="9eaa4-183">Gibt den Namen des Schemas, Beispiel angewendet, wenn diese Datenbank zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-183">Indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="9eaa4-184">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-184">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="9eaa4-185">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-185">Not supported for DataWarehouse edition.</span></span>
             <span data-ttu-id="9eaa4-186">Folgende Werte sind möglich: "AdventureWorksLT" ""</span><span class="sxs-lookup"><span data-stu-id="9eaa4-186">Possible values include: 'AdventureWorksLT'</span></span></param>
        <param name="zoneRedundant"><span data-ttu-id="9eaa4-187">Davon, ob diese Datenbank zonenredundant, ist also die Replikate für diese Datenbank wird auf mehreren Verfügbarkeit Zonen verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-187">Whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span></param>
        <summary>
             <span data-ttu-id="9eaa4-188">Initialisiert eine neue Instanz der DatabaseUpdate-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-188">Initializes a new instance of the DatabaseUpdate class.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Collation">
      <MemberSignature Language="C#" Value="public string Collation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Collation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberSignature Language="VB.NET" Value="Public Property Collation As String" />
      <MemberSignature Language="F#" Value="member this.Collation : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Collation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.collation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-189">Ruft ab oder legt die Sortierung der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-189">Gets or sets the collation of the database.</span></span> <span data-ttu-id="9eaa4-190">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-190">If createMode is not Default, this value is ignored.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainmentState">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ContainmentState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ContainmentState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainmentState As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ContainmentState : Nullable&lt;int64&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ContainmentState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.containmentState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-191">Ruft die Containment-Status der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-191">Gets the containment state of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public string CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As String" />
      <MemberSignature Language="F#" Value="member this.CreateMode : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             <span data-ttu-id="9eaa4-192">Ruft ab oder legt gibt den Modus der Erstellung der Datenbank an.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-192">Gets or sets specifies the mode of database creation.</span></span>
            
             <span data-ttu-id="9eaa4-193">Standard: reguläre Datenbank erstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-193">Default: regular database creation.</span></span>
            
             <span data-ttu-id="9eaa4-194">Kopie: erstellt eine Datenbank als Kopie einer vorhandenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-194">Copy: creates a database as a copy of an existing database.</span></span>
             <span data-ttu-id="9eaa4-195">SourceDatabaseId muss als die Ressourcen-ID der Quelldatenbank angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-195">sourceDatabaseId must be specified as the resource ID of the source database.</span></span>
             
            <span data-ttu-id="9eaa4-196">OnlineSecondary/NonReadableSecondary: erstellt eine Datenbank als ein sekundäres Replikat (lesbar ist oder nicht lesbar) einer vorhandenen Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-196">OnlineSecondary/NonReadableSecondary: creates a database as a (readable or nonreadable) secondary replica of an existing database.</span></span> <span data-ttu-id="9eaa4-197">SourceDatabaseId muss als die Ressourcen-ID der vorhandenen primären Datenbank angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-197">sourceDatabaseId must be specified as the resource ID of the existing primary database.</span></span>
             
             <span data-ttu-id="9eaa4-198">PointInTimeRestore: Erstellt eine Datenbank, indem Sie einen Punkt in der Sicherung einer vorhandenen Datenbank wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-198">PointInTimeRestore: Creates a database by restoring a point in time backup of an existing database.</span></span> <span data-ttu-id="9eaa4-199">SourceDatabaseId muss angegeben werden, wie die Ressourcen-ID der vorhandenen Datenbank und RestorePointInTime muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-199">sourceDatabaseId must be specified as the resource ID of the existing database, and restorePointInTime must be specified.</span></span>
             
             <span data-ttu-id="9eaa4-200">Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung geografisch repliziert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-200">Recovery: Creates a database by restoring a geo-replicated backup.</span></span>
            <span data-ttu-id="9eaa4-201">SourceDatabaseId muss als wiederherzustellenden die wiederherstellbare Datenbank Ressourcen-ID angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-201">sourceDatabaseId must be specified as the recoverable database resource ID to restore.</span></span>
             
             <span data-ttu-id="9eaa4-202">Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung einer gelöschten Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-202">Restore: Creates a database by restoring a backup of a deleted database.</span></span> <span data-ttu-id="9eaa4-203">SourceDatabaseId muss angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-203">sourceDatabaseId must be specified.</span></span> <span data-ttu-id="9eaa4-204">Wenn SourceDatabaseId ursprünglichen Ressourcen-ID der Datenbank ist, muss SourceDatabaseDeletionDate angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-204">If sourceDatabaseId is the database's original resource ID, then sourceDatabaseDeletionDate must be specified.</span></span> <span data-ttu-id="9eaa4-205">Andernfalls muss SourceDatabaseId wiederherstellbare gelöschte Datenbank-Ressourcen-ID und SourceDatabaseDeletionDate wird ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-205">Otherwise sourceDatabaseId must be the restorable dropped database resource ID and sourceDatabaseDeletionDate is ignored.</span></span> <span data-ttu-id="9eaa4-206">RestorePointInTime kann auch angegeben werden, aus einem früheren Zeitpunkt wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-206">restorePointInTime may also be specified to restore from an earlier point in time.</span></span>
             
             <span data-ttu-id="9eaa4-207">RestoreLongTermRetentionBackup: Erstellt eine Datenbank über eine langfristige Beibehaltungsdauer Tresor wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-207">RestoreLongTermRetentionBackup: Creates a database by restoring from a long term retention vault.</span></span>
            <span data-ttu-id="9eaa4-208">RecoveryServicesRecoveryPointResourceId muss als das Recovery Point-Ressourcen-ID angegeben werden</span><span class="sxs-lookup"><span data-stu-id="9eaa4-208">recoveryServicesRecoveryPointResourceId must be specified as the recovery point resource ID.</span></span>
             
             <span data-ttu-id="9eaa4-209">Copy-, NonReadableSecondary, OnlineSecondary und RestoreLongTermRetentionBackup werden für die Data Warehouse-Edition nicht unterstützt.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-209">Copy, NonReadableSecondary, OnlineSecondary and RestoreLongTermRetentionBackup are not supported for DataWarehouse edition.</span></span> <span data-ttu-id="9eaa4-210">Folgende Werte sind möglich: 'Kopieren', 'Default', "NonReadableSecondary", "OnlineSecondary", "PointInTimeRestore", 'Wiederherstellen', 'Wiederherstellen', 'RestoreLongTermRetentionBackup'</span><span class="sxs-lookup"><span data-stu-id="9eaa4-210">Possible values include: 'Copy', 'Default', 'NonReadableSecondary', 'OnlineSecondary', 'PointInTimeRestore', 'Recovery', 'Restore', 'RestoreLongTermRetentionBackup'</span></span>
             </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CreationDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-211">Ruft das Erstellungsdatum der Datenbank (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="9eaa4-211">Gets the creation date of the database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; CurrentServiceObjectiveId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; CurrentServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.CurrentServiceObjectiveId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.CurrentServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-212">Ruft die aktuelle Ebene dienstziel-ID der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-212">Gets the current service level objective ID of the database.</span></span> <span data-ttu-id="9eaa4-213">Dies ist die ID des SLO, das derzeit aktiv ist.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-213">This is the ID of the service level objective that is currently active.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DatabaseId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; DatabaseId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; DatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DatabaseId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.DatabaseId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.databaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-214">Ruft die ID der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-214">Gets the ID of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSecondaryLocation">
      <MemberSignature Language="C#" Value="public string DefaultSecondaryLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSecondaryLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSecondaryLocation As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSecondaryLocation : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.DefaultSecondaryLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.defaultSecondaryLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-215">Ruft die standardmäßige sekundäre Region für diese Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-215">Gets the default secondary region for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EarliestRestoreDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EarliestRestoreDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EarliestRestoreDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EarliestRestoreDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EarliestRestoreDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.EarliestRestoreDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.earliestRestoreDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-216">Ruft diese Datensätze der frühesten Startdatum und-Uhrzeit, den die Wiederherstellung ist für diese Datenbank (ISO8601-Format) verfügbar.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-216">Gets this records the earliest start date and time that restore is available for this database (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Edition">
      <MemberSignature Language="C#" Value="public string Edition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Edition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberSignature Language="VB.NET" Value="Public Property Edition As String" />
      <MemberSignature Language="F#" Value="member this.Edition : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Edition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.edition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-217">Ruft ab oder legt die Edition der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-217">Gets or sets the edition of the database.</span></span> <span data-ttu-id="9eaa4-218">Die DatabaseEditions-Enumeration enthält alle gültigen Editionen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-218">The DatabaseEditions enumeration contains all the valid editions.</span></span> <span data-ttu-id="9eaa4-219">Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-219">If createMode is NonReadableSecondary or OnlineSecondary, this value is ignored.</span></span> <span data-ttu-id="9eaa4-220">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".</span><span class="sxs-lookup"><span data-stu-id="9eaa4-220">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="9eaa4-221">Folgende Werte sind möglich: 'Web', ' Business', 'Basic', 'Standard', "Premium", "Free", "Stretch", "Data Warehouse", "System", "System 2"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-221">Possible values include: 'Web', 'Business', 'Basic', 'Standard', 'Premium', 'Free', 'Stretch', 'DataWarehouse', 'System', 'System2'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElasticPoolName">
      <MemberSignature Language="C#" Value="public string ElasticPoolName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ElasticPoolName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberSignature Language="VB.NET" Value="Public Property ElasticPoolName As String" />
      <MemberSignature Language="F#" Value="member this.ElasticPoolName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ElasticPoolName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.elasticPoolName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-222">Ruft ab oder legt den Namen des elastischen Pools, in dem die Datenbank befindet.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-222">Gets or sets the name of the elastic pool the database is in.</span></span> <span data-ttu-id="9eaa4-223">Wenn ElasticPoolName und RequestedServiceObjectiveName aktualisiert werden, wird der Wert der RequestedServiceObjectiveName ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-223">If elasticPoolName and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveName is ignored.</span></span> <span data-ttu-id="9eaa4-224">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-224">Not supported for DataWarehouse edition.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FailoverGroupId">
      <MemberSignature Language="C#" Value="public string FailoverGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FailoverGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FailoverGroupId As String" />
      <MemberSignature Language="F#" Value="member this.FailoverGroupId : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.FailoverGroupId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.failoverGroupId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-225">Ruft den Ressourcenbezeichner der Gruppe "Failover", die diese Datenbank enthält.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-225">Gets the resource identifier of the failover group containing this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxSizeBytes">
      <MemberSignature Language="C#" Value="public string MaxSizeBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MaxSizeBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxSizeBytes As String" />
      <MemberSignature Language="F#" Value="member this.MaxSizeBytes : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.MaxSizeBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxSizeBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-226">Ruft ab oder legt die maximale Größe der Datenbank in Bytes ausgedrückt.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-226">Gets or sets the max size of the database expressed in bytes.</span></span> <span data-ttu-id="9eaa4-227">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-227">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="9eaa4-228">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</span><span class="sxs-lookup"><span data-stu-id="9eaa4-228">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadScale">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Sql.Models.ReadScale&gt; ReadScale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberSignature Language="VB.NET" Value="Public Property ReadScale As Nullable(Of ReadScale)" />
      <MemberSignature Language="F#" Value="member this.ReadScale : Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ReadScale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.readScale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Sql.Models.ReadScale&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-229">Ruft ab, oder legt Sie bedingte fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-229">Gets or sets conditional.</span></span> <span data-ttu-id="9eaa4-230">Wenn die Datenbank über geografische sekundäres Replikat ist, überprüfen, ob ReadScale schreibgeschützte Verbindungen zu dieser Datenbank zulässig sind.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-230">If the database is a geo-secondary, readScale indicates whether read-only connections are allowed to this database or not.</span></span> <span data-ttu-id="9eaa4-231">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-231">Not supported for DataWarehouse edition.</span></span>
            <span data-ttu-id="9eaa4-232">Folgende Werte sind möglich: "Enabled", "Disabled"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-232">Possible values include: 'Enabled', 'Disabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecommendedIndex">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt; RecommendedIndex" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecommendedIndex As IList(Of RecommendedIndex)" />
      <MemberSignature Language="F#" Value="member this.RecommendedIndex : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecommendedIndex" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recommendedIndex")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.RecommendedIndex&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-233">Ruft die empfohlenen Indizes für diese Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-233">Gets the recommended indices for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoveryServicesRecoveryPointResourceId">
      <MemberSignature Language="C#" Value="public string RecoveryServicesRecoveryPointResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecoveryServicesRecoveryPointResourceId As String" />
      <MemberSignature Language="F#" Value="member this.RecoveryServicesRecoveryPointResourceId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RecoveryServicesRecoveryPointResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.recoveryServicesRecoveryPointResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-234">Ruft ab, oder legt Sie bedingte fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-234">Gets or sets conditional.</span></span> <span data-ttu-id="9eaa4-235">Wenn CreateMode RestoreLongTermRetentionBackup ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-235">If createMode is RestoreLongTermRetentionBackup, then this value is required.</span></span>
            <span data-ttu-id="9eaa4-236">Gibt die Ressourcen-ID des Wiederherstellungspunkts aus wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-236">Specifies the resource ID of the recovery point to restore from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RequestedServiceObjectiveId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RequestedServiceObjectiveId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-237">Ruft ab oder legt die konfigurierten Servicelevel dienstziel-ID der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-237">Gets or sets the configured service level objective ID of the database.</span></span> <span data-ttu-id="9eaa4-238">Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-238">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="9eaa4-239">Nachdem erfolgreich aktualisiert wurde, wird es den Wert der Eigenschaft CurrentServiceObjectiveId überein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-239">Once successfully updated, it will match the value of currentServiceObjectiveId property.</span></span> <span data-ttu-id="9eaa4-240">Wenn RequestedServiceObjectiveId und RequestedServiceObjectiveName aktualisiert werden, überschreibt der Wert des RequestedServiceObjectiveId den Wert der RequestedServiceObjectiveName an.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-240">If requestedServiceObjectiveId and requestedServiceObjectiveName are both updated, the value of requestedServiceObjectiveId overrides the value of requestedServiceObjectiveName.</span></span> <span data-ttu-id="9eaa4-241">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</span><span class="sxs-lookup"><span data-stu-id="9eaa4-241">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation."</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestedServiceObjectiveName">
      <MemberSignature Language="C#" Value="public string RequestedServiceObjectiveName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestedServiceObjectiveName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberSignature Language="VB.NET" Value="Public Property RequestedServiceObjectiveName As String" />
      <MemberSignature Language="F#" Value="member this.RequestedServiceObjectiveName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RequestedServiceObjectiveName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.requestedServiceObjectiveName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-242">Ruft ab oder legt den Namen des konfigurierten SLO der Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-242">Gets or sets the name of the configured service level objective of the database.</span></span> <span data-ttu-id="9eaa4-243">Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-243">This is the service level objective that is in the process of being applied to the database.</span></span> <span data-ttu-id="9eaa4-244">Nachdem erfolgreich aktualisiert, wird es den Wert der Eigenschaft ServiceLevelObjective überein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-244">Once successfully updated, it will match the value of serviceLevelObjective property.</span></span>
            <span data-ttu-id="9eaa4-245">Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".</span><span class="sxs-lookup"><span data-stu-id="9eaa4-245">To see possible values, query the capabilities API (/subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) referred to by operationId: "Capabilities_ListByLocation.".</span></span>
            <span data-ttu-id="9eaa4-246">Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-246">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestorePointInTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RestorePointInTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RestorePointInTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberSignature Language="VB.NET" Value="Public Property RestorePointInTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RestorePointInTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.RestorePointInTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.restorePointInTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-247">Ruft ab, oder legt Sie bedingte fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-247">Gets or sets conditional.</span></span> <span data-ttu-id="9eaa4-248">Wenn CreateMode PointInTimeRestore ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-248">If createMode is PointInTimeRestore, this value is required.</span></span> <span data-ttu-id="9eaa4-249">Wenn CreateMode Wiederherstellung ist, ist dieser Wert optional.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-249">If createMode is Restore, this value is optional.</span></span> <span data-ttu-id="9eaa4-250">Angibt, an dem Punkt (ISO8601-Format) von der Quelldatenbank, die zum Erstellen der neuen Datenbank wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-250">Specifies the point in time (ISO8601 format) of the source database that will be restored to create the new database.</span></span>
            <span data-ttu-id="9eaa4-251">Muss größer als oder gleich der Quelldatenbank EarliestRestoreDate Wert sein.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-251">Must be greater than or equal to the source database's earliestRestoreDate value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SampleName">
      <MemberSignature Language="C#" Value="public string SampleName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SampleName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberSignature Language="VB.NET" Value="Public Property SampleName As String" />
      <MemberSignature Language="F#" Value="member this.SampleName : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SampleName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sampleName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-252">Gibt an den Namen des Schemas, Beispiel angewendet, wenn diese Datenbank zu erstellen, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-252">Gets or sets indicates the name of the sample schema to apply when creating this database.</span></span> <span data-ttu-id="9eaa4-253">Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-253">If createMode is not Default, this value is ignored.</span></span> <span data-ttu-id="9eaa4-254">Für Data Warehouse-Edition unterstützt nicht.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-254">Not supported for DataWarehouse edition.</span></span> <span data-ttu-id="9eaa4-255">Folgende Werte sind möglich: "AdventureWorksLT" ""</span><span class="sxs-lookup"><span data-stu-id="9eaa4-255">Possible values include: 'AdventureWorksLT'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceLevelObjective">
      <MemberSignature Language="C#" Value="public string ServiceLevelObjective { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceLevelObjective" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceLevelObjective As String" />
      <MemberSignature Language="F#" Value="member this.ServiceLevelObjective : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceLevelObjective" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceLevelObjective")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-256">Ruft das aktuelle SLO der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-256">Gets the current service level objective of the database.</span></span> <span data-ttu-id="9eaa4-257">Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</span><span class="sxs-lookup"><span data-stu-id="9eaa4-257">Possible values include: 'Basic', 'S0', 'S1', 'S2', 'S3', 'P1', 'P2', 'P3', 'P4', 'P6', 'P11', 'P15', 'System', 'System2', 'ElasticPool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTierAdvisors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt; ServiceTierAdvisors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTierAdvisors As IList(Of ServiceTierAdvisor)" />
      <MemberSignature Language="F#" Value="member this.ServiceTierAdvisors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ServiceTierAdvisors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceTierAdvisors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.ServiceTierAdvisor&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-258">Ruft die Liste der Service Tier Ratgeber für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-258">Gets the list of service tier advisors for this database.</span></span> <span data-ttu-id="9eaa4-259">Erweiterte Eigenschaft</span><span class="sxs-lookup"><span data-stu-id="9eaa4-259">Expanded property</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseDeletionDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; SourceDatabaseDeletionDate { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; SourceDatabaseDeletionDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseDeletionDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseDeletionDate : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseDeletionDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseDeletionDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-260">Ruft ab, oder legt Sie bedingte fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-260">Gets or sets conditional.</span></span> <span data-ttu-id="9eaa4-261">Wenn CreateMode ist die Wiederherstellung und SourceDatabaseId ist die gelöschte Datenbank ursprünglichen-Ressourcen-Id aus, wenn sie (im Gegensatz zu seiner aktuellen wiederherstellbare gelöschte Datenbank-Id) vorhanden waren, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-261">If createMode is Restore and sourceDatabaseId is the deleted database's original resource id when it existed (as opposed to its current restorable dropped database id), then this value is required.</span></span> <span data-ttu-id="9eaa4-262">Gibt die Zeit, die die Datenbank gelöscht wurde.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-262">Specifies the time that the database was deleted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDatabaseId">
      <MemberSignature Language="C#" Value="public string SourceDatabaseId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDatabaseId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDatabaseId As String" />
      <MemberSignature Language="F#" Value="member this.SourceDatabaseId : string with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.SourceDatabaseId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceDatabaseId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-263">Ruft ab, oder legt Sie bedingte fest.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-263">Gets or sets conditional.</span></span> <span data-ttu-id="9eaa4-264">Wenn CreateMode kopieren, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Wiederherstellung oder Wiederherstellung ist, ist dieser Wert erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-264">If createMode is Copy, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Recovery, or Restore, then this value is required.</span></span> <span data-ttu-id="9eaa4-265">Gibt die Ressourcen-ID der Quelldatenbank an.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-265">Specifies the resource ID of the source database.</span></span> <span data-ttu-id="9eaa4-266">Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, muss der Name der Quelldatenbank identisch mit der neuen Datenbank erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-266">If createMode is NonReadableSecondary or OnlineSecondary, the name of the source database must be the same as the new database being created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-267">Ruft den Status der Datenbank ab.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-267">Gets the status of the database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-268">Ermittelt oder Ressourcen-Tags definiert.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-268">Gets or sets resource tags.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TransparentDataEncryption">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt; TransparentDataEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TransparentDataEncryption As IList(Of TransparentDataEncryption)" />
      <MemberSignature Language="F#" Value="member this.TransparentDataEncryption : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.TransparentDataEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transparentDataEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryption&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-269">Ruft die transparenten Verschlüsselungsinformationen für diese Datenbank.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-269">Gets the transparent data encryption info for this database.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ZoneRedundant">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ZoneRedundant { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ZoneRedundant" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberSignature Language="VB.NET" Value="Public Property ZoneRedundant As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ZoneRedundant : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.DatabaseUpdate.ZoneRedundant" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.zoneRedundant")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9eaa4-270">Ruft ab oder legt sie fest, und zwar unabhängig davon, ob diese Datenbank ist, dass mehrere Verfügbarkeit Zonen zonenredundant, d. die Replikate für diese Datenbank h. verteilt werden.</span><span class="sxs-lookup"><span data-stu-id="9eaa4-270">Gets or sets whether or not this database is zone redundant, which means the replicas of this database will be spread across multiple availability zones.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>