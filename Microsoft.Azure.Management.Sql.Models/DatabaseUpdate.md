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
            Stellt eine Aktualisierung der Datenbank dar.
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
            Initialisiert eine neue Instanz der DatabaseUpdate-Klasse.
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
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="collation">Die Sortierung der Datenbank. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.</param>
        <param name="creationDate">Das Erstellungsdatum der Datenbank (ISO8601-Format).</param>
        <param name="containmentState">Die Containment-Status der Datenbank.</param>
        <param name="currentServiceObjectiveId">Die aktuelle Ebene dienstziel-ID der Datenbank. Dies ist die ID des SLO, das derzeit aktiv ist.</param>
        <param name="databaseId">Die ID der Datenbank.</param>
        <param name="earliestRestoreDate">Diese Datensätze der frühesten Startdatum und-Uhrzeit, den die Wiederherstellung ist für diese Datenbank (ISO8601-Format) verfügbar.</param>
        <param name="createMode">Gibt den Modus der Datenbankerstellung.
            
             Standard: reguläre Datenbank erstellen.
            
             Kopie: erstellt eine Datenbank als Kopie einer vorhandenen Datenbank.
             SourceDatabaseId muss als die Ressourcen-ID der Quelldatenbank angegeben werden.
             
            OnlineSecondary/NonReadableSecondary: erstellt eine Datenbank als ein sekundäres Replikat (lesbar ist oder nicht lesbar) einer vorhandenen Datenbank. SourceDatabaseId muss als die Ressourcen-ID der vorhandenen primären Datenbank angegeben werden.
             
             PointInTimeRestore: Erstellt eine Datenbank, indem Sie einen Punkt in der Sicherung einer vorhandenen Datenbank wiederherstellen. SourceDatabaseId muss angegeben werden, wie die Ressourcen-ID der vorhandenen Datenbank und RestorePointInTime muss angegeben werden.
             
             Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung geografisch repliziert.
            SourceDatabaseId muss als wiederherzustellenden die wiederherstellbare Datenbank Ressourcen-ID angegeben werden.
             
             Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung einer gelöschten Datenbank. SourceDatabaseId muss angegeben werden. Wenn SourceDatabaseId ursprünglichen Ressourcen-ID der Datenbank ist, muss SourceDatabaseDeletionDate angegeben werden. Andernfalls muss SourceDatabaseId wiederherstellbare gelöschte Datenbank-Ressourcen-ID und SourceDatabaseDeletionDate wird ignoriert. RestorePointInTime kann auch angegeben werden, aus einem früheren Zeitpunkt wiederherstellen.
             
             RestoreLongTermRetentionBackup: Erstellt eine Datenbank über eine langfristige Beibehaltungsdauer Tresor wiederherstellen.
            RecoveryServicesRecoveryPointResourceId muss als das Recovery Point-Ressourcen-ID angegeben werden
             
             Copy-, NonReadableSecondary, OnlineSecondary und RestoreLongTermRetentionBackup werden für die Data Warehouse-Edition nicht unterstützt. Folgende Werte sind möglich: 'Kopieren', 'Default', "NonReadableSecondary", "OnlineSecondary", "PointInTimeRestore", 'Wiederherstellen', 'Wiederherstellen', 'RestoreLongTermRetentionBackup'</param>
        <param name="sourceDatabaseId">Bedingte. Wenn CreateMode kopieren, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Wiederherstellung oder Wiederherstellung ist, ist dieser Wert erforderlich. Gibt die Ressourcen-ID der Quelldatenbank an. Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, muss der Name der Quelldatenbank identisch mit der neuen Datenbank erstellt wird.</param>
        <param name="sourceDatabaseDeletionDate">Bedingte. Wenn CreateMode ist die Wiederherstellung und SourceDatabaseId ist die gelöschte Datenbank ursprünglichen-Ressourcen-Id aus, wenn sie (im Gegensatz zu seiner aktuellen wiederherstellbare gelöschte Datenbank-Id) vorhanden waren, ist dieser Wert erforderlich. Gibt die Zeit, die die Datenbank gelöscht wurde.</param>
        <param name="restorePointInTime">Bedingte. Wenn CreateMode PointInTimeRestore ist, ist dieser Wert erforderlich. Wenn CreateMode Wiederherstellung ist, ist dieser Wert optional. Angibt, an dem Punkt (ISO8601-Format) von der Quelldatenbank, die zum Erstellen der neuen Datenbank wiederhergestellt werden. Muss größer als oder gleich der Quelldatenbank EarliestRestoreDate Wert sein.</param>
        <param name="recoveryServicesRecoveryPointResourceId">Bedingte.
             Wenn CreateMode RestoreLongTermRetentionBackup ist, ist dieser Wert erforderlich. Gibt die Ressourcen-ID des Wiederherstellungspunkts aus wiederherstellen.</param>
        <param name="edition">Die Edition der Datenbank. Die DatabaseEditions-Enumeration enthält alle gültigen Editionen. Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, wird dieser Wert ignoriert. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".
             Folgende Werte sind möglich: 'Web', ' Business', 'Basic', 'Standard', "Premium", "Free", "Stretch", "Data Warehouse", "System", "System 2"</param>
        <param name="maxSizeBytes">Die maximale Größe der Datenbank in Bytes ausgedrückt. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</param>
        <param name="requestedServiceObjectiveId">Die konfigurierten Servicelevel dienstziel-ID der Datenbank. Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird.
             Nachdem erfolgreich aktualisiert wurde, wird es den Wert der Eigenschaft CurrentServiceObjectiveId überein. Wenn RequestedServiceObjectiveId und RequestedServiceObjectiveName aktualisiert werden, überschreibt der Wert des RequestedServiceObjectiveId den Wert der RequestedServiceObjectiveName an. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."</param>
        <param name="requestedServiceObjectiveName">Der Name des konfigurierten SLO der Datenbank. Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird. Nachdem erfolgreich aktualisiert, wird es den Wert der Eigenschaft ServiceLevelObjective überein. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".
             Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</param>
        <param name="serviceLevelObjective">Das aktuelle SLO der Datenbank. Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"</param>
        <param name="status">Der Status der Datenbank.</param>
        <param name="elasticPoolName">Der Name des elastischen Pools der Datenbank wird. Wenn ElasticPoolName und RequestedServiceObjectiveName aktualisiert werden, wird der Wert der RequestedServiceObjectiveName ignoriert. Für Data Warehouse-Edition unterstützt nicht.</param>
        <param name="defaultSecondaryLocation">Die Standardeinstellung sekundäre Region für diese Datenbank.</param>
        <param name="serviceTierAdvisors">Die Liste der Service Tier Ratgeber für diese Datenbank. Erweiterte Eigenschaft</param>
        <param name="transparentDataEncryption">Transparent Data Encryption Info für diese Datenbank.</param>
        <param name="recommendedIndex">Die empfohlenen Indizes für diese Datenbank.</param>
        <param name="failoverGroupId">Der Ressourcenbezeichner der Gruppe "Failover", die diese Datenbank enthält.</param>
        <param name="readScale">Bedingte. Wenn die Datenbank über geografische sekundäres Replikat ist, überprüfen, ob ReadScale schreibgeschützte Verbindungen zu dieser Datenbank zulässig sind. Für Data Warehouse-Edition unterstützt nicht. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="sampleName">Gibt den Namen des Schemas, Beispiel angewendet, wenn diese Datenbank zu erstellen. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert. Für Data Warehouse-Edition unterstützt nicht.
             Folgende Werte sind möglich: "AdventureWorksLT" ""</param>
        <param name="zoneRedundant">Davon, ob diese Datenbank zonenredundant, ist also die Replikate für diese Datenbank wird auf mehreren Verfügbarkeit Zonen verteilt werden.</param>
        <summary>
             Initialisiert eine neue Instanz der DatabaseUpdate-Klasse.
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
            Ruft ab oder legt die Sortierung der Datenbank. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert.
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
            Ruft die Containment-Status der Datenbank ab.
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
             Ruft ab oder legt gibt den Modus der Erstellung der Datenbank an.
            
             Standard: reguläre Datenbank erstellen.
            
             Kopie: erstellt eine Datenbank als Kopie einer vorhandenen Datenbank.
             SourceDatabaseId muss als die Ressourcen-ID der Quelldatenbank angegeben werden.
             
            OnlineSecondary/NonReadableSecondary: erstellt eine Datenbank als ein sekundäres Replikat (lesbar ist oder nicht lesbar) einer vorhandenen Datenbank. SourceDatabaseId muss als die Ressourcen-ID der vorhandenen primären Datenbank angegeben werden.
             
             PointInTimeRestore: Erstellt eine Datenbank, indem Sie einen Punkt in der Sicherung einer vorhandenen Datenbank wiederherstellen. SourceDatabaseId muss angegeben werden, wie die Ressourcen-ID der vorhandenen Datenbank und RestorePointInTime muss angegeben werden.
             
             Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung geografisch repliziert.
            SourceDatabaseId muss als wiederherzustellenden die wiederherstellbare Datenbank Ressourcen-ID angegeben werden.
             
             Wiederherstellung: Erstellt eine Datenbank durch Wiederherstellen einer Sicherung einer gelöschten Datenbank. SourceDatabaseId muss angegeben werden. Wenn SourceDatabaseId ursprünglichen Ressourcen-ID der Datenbank ist, muss SourceDatabaseDeletionDate angegeben werden. Andernfalls muss SourceDatabaseId wiederherstellbare gelöschte Datenbank-Ressourcen-ID und SourceDatabaseDeletionDate wird ignoriert. RestorePointInTime kann auch angegeben werden, aus einem früheren Zeitpunkt wiederherstellen.
             
             RestoreLongTermRetentionBackup: Erstellt eine Datenbank über eine langfristige Beibehaltungsdauer Tresor wiederherstellen.
            RecoveryServicesRecoveryPointResourceId muss als das Recovery Point-Ressourcen-ID angegeben werden
             
             Copy-, NonReadableSecondary, OnlineSecondary und RestoreLongTermRetentionBackup werden für die Data Warehouse-Edition nicht unterstützt. Folgende Werte sind möglich: 'Kopieren', 'Default', "NonReadableSecondary", "OnlineSecondary", "PointInTimeRestore", 'Wiederherstellen', 'Wiederherstellen', 'RestoreLongTermRetentionBackup'
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
            Ruft das Erstellungsdatum der Datenbank (ISO8601-Format).
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
            Ruft die aktuelle Ebene dienstziel-ID der Datenbank ab. Dies ist die ID des SLO, das derzeit aktiv ist.
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
            Ruft die ID der Datenbank ab.
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
            Ruft die standardmäßige sekundäre Region für diese Datenbank ab.
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
            Ruft diese Datensätze der frühesten Startdatum und-Uhrzeit, den die Wiederherstellung ist für diese Datenbank (ISO8601-Format) verfügbar.
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
            Ruft ab oder legt die Edition der Datenbank. Die DatabaseEditions-Enumeration enthält alle gültigen Editionen. Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, wird dieser Wert ignoriert. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".
            Folgende Werte sind möglich: 'Web', ' Business', 'Basic', 'Standard', "Premium", "Free", "Stretch", "Data Warehouse", "System", "System 2"
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
            Ruft ab oder legt den Namen des elastischen Pools, in dem die Datenbank befindet. Wenn ElasticPoolName und RequestedServiceObjectiveName aktualisiert werden, wird der Wert der RequestedServiceObjectiveName ignoriert. Für Data Warehouse-Edition unterstützt nicht.
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
            Ruft den Ressourcenbezeichner der Gruppe "Failover", die diese Datenbank enthält.
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
            Ruft ab oder legt die maximale Größe der Datenbank in Bytes ausgedrückt. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."
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
            Ruft ab, oder legt Sie bedingte fest. Wenn die Datenbank über geografische sekundäres Replikat ist, überprüfen, ob ReadScale schreibgeschützte Verbindungen zu dieser Datenbank zulässig sind. Für Data Warehouse-Edition unterstützt nicht.
            Folgende Werte sind möglich: "Enabled", "Disabled"
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
            Ruft die empfohlenen Indizes für diese Datenbank ab.
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
            Ruft ab, oder legt Sie bedingte fest. Wenn CreateMode RestoreLongTermRetentionBackup ist, ist dieser Wert erforderlich.
            Gibt die Ressourcen-ID des Wiederherstellungspunkts aus wiederherstellen.
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
            Ruft ab oder legt die konfigurierten Servicelevel dienstziel-ID der Datenbank. Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird. Nachdem erfolgreich aktualisiert wurde, wird es den Wert der Eigenschaft CurrentServiceObjectiveId überein. Wenn RequestedServiceObjectiveId und RequestedServiceObjectiveName aktualisiert werden, überschreibt der Wert des RequestedServiceObjectiveId den Wert der RequestedServiceObjectiveName an. Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation."
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
            Ruft ab oder legt den Namen des konfigurierten SLO der Datenbank. Dies ist der Servicelevel-Zielpunkt, der gerade auf die Datenbank angewendet wird. Nachdem erfolgreich aktualisiert, wird es den Wert der Eigenschaft ServiceLevelObjective überein.
            Um mögliche Werte anzuzeigen, Fragen Sie die API-Funktionen (/ subscriptions/{subscriptionId}/providers/Microsoft.Sql/locations/{locationID}/capabilities) verweist auf OperationId: "Capabilities_ListByLocation.".
            Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"
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
            Ruft ab, oder legt Sie bedingte fest. Wenn CreateMode PointInTimeRestore ist, ist dieser Wert erforderlich. Wenn CreateMode Wiederherstellung ist, ist dieser Wert optional. Angibt, an dem Punkt (ISO8601-Format) von der Quelldatenbank, die zum Erstellen der neuen Datenbank wiederhergestellt werden.
            Muss größer als oder gleich der Quelldatenbank EarliestRestoreDate Wert sein.
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
            Gibt an den Namen des Schemas, Beispiel angewendet, wenn diese Datenbank zu erstellen, ruft ab oder legt ihn fest. Wenn CreateMode nicht standardmäßige ist, wird dieser Wert ignoriert. Für Data Warehouse-Edition unterstützt nicht. Folgende Werte sind möglich: "AdventureWorksLT" ""
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
            Ruft das aktuelle SLO der Datenbank ab. Folgende Werte sind möglich: "Basic", "S0", "S1", "S2", "S3", "P1", "P2", "P3", "P4", "P6", "P11", "P15", "System", "System 2", "ElasticPool"
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
            Ruft die Liste der Service Tier Ratgeber für diese Datenbank. Erweiterte Eigenschaft
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
            Ruft ab, oder legt Sie bedingte fest. Wenn CreateMode ist die Wiederherstellung und SourceDatabaseId ist die gelöschte Datenbank ursprünglichen-Ressourcen-Id aus, wenn sie (im Gegensatz zu seiner aktuellen wiederherstellbare gelöschte Datenbank-Id) vorhanden waren, ist dieser Wert erforderlich. Gibt die Zeit, die die Datenbank gelöscht wurde.
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
            Ruft ab, oder legt Sie bedingte fest. Wenn CreateMode kopieren, NonReadableSecondary, OnlineSecondary, PointInTimeRestore, Wiederherstellung oder Wiederherstellung ist, ist dieser Wert erforderlich. Gibt die Ressourcen-ID der Quelldatenbank an. Wenn CreateMode NonReadableSecondary oder OnlineSecondary ist, muss der Name der Quelldatenbank identisch mit der neuen Datenbank erstellt wird.
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
            Ruft den Status der Datenbank ab.
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
            Ermittelt oder Ressourcen-Tags definiert.
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
            Ruft die transparenten Verschlüsselungsinformationen für diese Datenbank.
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
            Ruft ab oder legt sie fest, und zwar unabhängig davon, ob diese Datenbank ist, dass mehrere Verfügbarkeit Zonen zonenredundant, d. die Replikate für diese Datenbank h. verteilt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>