<Type Name="KeyValueStoreReplica" FullName="System.Fabric.KeyValueStoreReplica">
  <TypeSignature Language="C#" Value="public class KeyValueStoreReplica : System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyValueStoreReplica extends System.Object implements class System.Fabric.IStatefulServiceReplica" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.KeyValueStoreReplica" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyValueStoreReplica&#xA;Implements IStatefulServiceReplica" />
  <TypeSignature Language="F#" Value="type KeyValueStoreReplica = class&#xA;    interface IStatefulServiceReplica&#xA;    interface IBackupRestoreReplica" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Fabric.IStatefulServiceReplica</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
      <para>Stellt eine Komponente Transaktions-, assoziative replizierten Daten für Service-Writer - bereit für die Integration in jeder Service Fabric-Dienst bereit.</para>
            Dies wird von älteren Service Fabric-Diensten. Alle neuen Dienste verwenden, sollten die <see href="https://docs.microsoft.com/azure/service-fabric/service-fabric-reliable-services-reliable-collections">zuverlässige Sammlungen</see>.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storeName As String)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica storeName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert-Geschäftsnamen.</para>
        </summary>
        <remarks>
          <para>Der Speichername muss gültige Dateinamenzeichen entsprechen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </param>
        <param name="localStoreSettings">
          <para>Die optionalen Einstellungen für den lokalen Speicher.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Namen und Einstellungen für lokalen Speicher.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </param>
        <param name="replicatorSettings">
          <para>Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> -Klasse mit den angegebenen Schlüssel/Wert-Geschäftsnamen und Replikator Einstellungen speichern.</para>
        </summary>
        <remarks>
          <para>Der Speichername muss gültige Dateinamenzeichen entsprechen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </param>
        <param name="localStoreSettings">
          <para>Die optionalen Einstellungen für den lokalen Speicher.</para>
        </param>
        <param name="replicatorSettings">
          <para>Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Name, der lokalen Speicher und Replikator Einstellungen.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode notificationMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode notificationMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, notificationMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="notificationMode" Type="System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode" />
      </Parameters>
      <Docs>
        <param name="storeName">
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </param>
        <param name="localStoreSettings">
          <para>Die optionalen Einstellungen für den lokalen Speicher.</para>
        </param>
        <param name="replicatorSettings">
          <para>Die optionseinstellungen für den Schlüssel/Wert speichern Replikator.</para>
        </param>
        <param name="notificationMode">
          <para>So aktivieren Sie die sekundäre Benachrichtigungsmodus <see cref="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" /> und <see cref="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" /> Rückrufe auf diesem Replikat.</para>
        </param>
        <summary>
          <para>Initialisiert eine neue Instanz der dem <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse mit dem angegebenen Schlüssel/Wert zu speichern, Name, der lokalen Speicher und Replikator Einstellungen. Sekundäres Replikat Benachrichtigungen sind über den Benachrichtigungsmodus aktiviert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyValueStoreReplica (string storeName, System.Fabric.LocalStoreSettings localStoreSettings, System.Fabric.ReplicatorSettings replicatorSettings, System.Fabric.KeyValueStoreReplicaSettings kvsSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storeName, class System.Fabric.LocalStoreSettings localStoreSettings, class System.Fabric.ReplicatorSettings replicatorSettings, class System.Fabric.KeyValueStoreReplicaSettings kvsSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.#ctor(System.String,System.Fabric.LocalStoreSettings,System.Fabric.ReplicatorSettings,System.Fabric.KeyValueStoreReplicaSettings)" />
      <MemberSignature Language="F#" Value="new System.Fabric.KeyValueStoreReplica : string * System.Fabric.LocalStoreSettings * System.Fabric.ReplicatorSettings * System.Fabric.KeyValueStoreReplicaSettings -&gt; System.Fabric.KeyValueStoreReplica" Usage="new System.Fabric.KeyValueStoreReplica (storeName, localStoreSettings, replicatorSettings, kvsSettings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storeName" Type="System.String" />
        <Parameter Name="localStoreSettings" Type="System.Fabric.LocalStoreSettings" />
        <Parameter Name="replicatorSettings" Type="System.Fabric.ReplicatorSettings" />
        <Parameter Name="kvsSettings" Type="System.Fabric.KeyValueStoreReplicaSettings" />
      </Parameters>
      <Docs>
        <param name="storeName">Der Name des Schlüssel/Wert-Speichers.</param>
        <param name="localStoreSettings">Die optionalen Einstellungen für den lokalen Speicher.</param>
        <param name="replicatorSettings">Die optionalen Einstellungen für den Schlüssel/Wert speichern Replikator.</param>
        <param name="kvsSettings">Die optionalen Einstellungen für das Replikat der Schlüssel/Wert-Speicher.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse mit der angegebene Schlüssel-Wert-Speichername, Einstellungen des lokalen Speicher Replikator Einstellungen und replikateinstellungen KeyValueStoreReplica.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Abort">
      <MemberSignature Language="C#" Value="public void Abort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Abort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Abort" />
      <MemberSignature Language="VB.NET" Value="Public Sub Abort ()" />
      <MemberSignature Language="F#" Value="abstract member Abort : unit -&gt; unit&#xA;override this.Abort : unit -&gt; unit" Usage="keyValueStoreReplica.Abort " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Abort</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Bricht diese Instanz die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Klasse.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public void Add (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Add(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Add(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Add : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Add (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als eine Zeichenfolge) hinzugefügt werden. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <param name="value">
          <para>Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</para>
        </param>
        <summary>
          <para>Fügt einen Wert, der durch den angegebenen Schlüssel im Schlüssel/Wert-Speicher indiziert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public void Backup (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Backup(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Backup(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Backup (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Backup : string -&gt; unit" Usage="keyValueStoreReplica.Backup backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use BackupAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para>Der vollständige Pfad des Verzeichnisses Sicherungsziel.</para>
        </param>
        <summary>
          <para>ALS VERALTET MARKIERT. Führt eine vollständige Sicherung der lokale Speicher das Replikat des angegebenen Zielverzeichnisses an. </para>
        </summary>
        <remarks>
          <para>
            Diese Methode ist veraltet. Verwenden Sie stattdessen <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</para>
          <para>
            Inkrementelle Sicherungen werden nach dem Erstellen einer vollständigen Sicherung, die mit dieser Methode nicht unterstützt. Verwendung <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" /> , eine vollständige Sicherung zu erstellen, wenn es sich bei nachfolgende inkrementelle Sicherungen erstellt werden sollen.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />
      <MemberSignature Language="VB.NET" Value="Public Function BackupAsync (backupDirectory As String, backupOption As StoreBackupOption, postBackupAsyncFunc As Func(Of StoreBackupInfo, Task(Of Boolean))) As Task" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            Das Verzeichnis, in dem die Sicherung gespeichert werden soll. Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, sollte dieser Parameter werden <b>null</b>.
            Dieser Parameter darf nicht sein, anderenfalls <b>null</b>, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            Wenn das Verzeichnis nicht vorhanden ist, wird es erstellt. Wenn es vorhanden ist und nicht leer ist, misslingt die inkrementeller Sicherung mit <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.
            </param>
        <param name="backupOption">
          <para>Die Optionen für die Sicherung.</para>
        </param>
        <param name="postBackupAsyncFunc">
            Im Beitrag sichern asynchrone Methode, die von Service Fabric, damit der Benutzer alle nach der Sicherung Aktivität abgeschlossen wird, vor dem Zurückgeben der Steuerung an das System kann aufgerufen wird.
            Wenn <b>null</b> übergeben, inkrementelle Sicherungen sind nicht zulässig.
            Wenn die Methode nach der Sicherung auf "false" zurückgibt, sind dann erneut inkrementelle Sicherungen nicht zulässig.
            </param>
        <summary>
          <para>Erstellt asynchron eine Sicherung des Schlüssel/Wert-Speichers.</para>
        </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Die <b>PostBackupAsyncFunc</b> wird nicht aufgerufen, wenn während der Sicherung ein Fehler aufgetreten ist. Außerdem ist es nicht aufgerufen wird, wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> , da es ist keine weitere Aktion, die vom Benutzer in diesem Fall einen einzelnen Sicherungszyklus abgeschlossen erforderlich.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>BackupDirectory</b> ist <b>null</b> Wenn <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen beim <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> oder <b>BackupDirectory</b> nicht <b>null</b> bei <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> und das Sicherungsverzeichnis Dateien oder Unterverzeichnisse bereits enthält.        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            Wenn eine zuvor begonnene Sicherung gerade ausgeführt wird.
            </exception>
        <example>
            Im folgenden finden Sie ein Beispiel für eine einfache Implementierung der <b>PostBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="BackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BackupAsync (string backupDirectory, System.Fabric.StoreBackupOption backupOption, Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;bool&gt;&gt; postBackupAsyncFunc, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task BackupAsync(string backupDirectory, valuetype System.Fabric.StoreBackupOption backupOption, class System.Func`2&lt;class System.Fabric.StoreBackupInfo, class System.Threading.Tasks.Task`1&lt;bool&gt;&gt; postBackupAsyncFunc, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.BackupAsync : string * System.Fabric.StoreBackupOption * Func&lt;System.Fabric.StoreBackupInfo, System.Threading.Tasks.Task&lt;bool&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.BackupAsync (backupDirectory, backupOption, postBackupAsyncFunc, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="backupOption" Type="System.Fabric.StoreBackupOption" />
        <Parameter Name="postBackupAsyncFunc" Type="System.Func&lt;System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task&lt;System.Boolean&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            Das Verzeichnis, in dem die Sicherung gespeichert werden soll. Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />, sollte dieser Parameter werden <b>null</b>.
            Dieser Parameter darf nicht sein, anderenfalls <b>null</b>, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            Wenn das Verzeichnis nicht vorhanden ist, wird es erstellt. Wenn es vorhanden ist und nicht leer ist, misslingt die inkrementeller Sicherung mit <see cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException" />.
            </param>
        <param name="backupOption">
          <para>Die Optionen für die Sicherung.</para>
        </param>
        <param name="postBackupAsyncFunc">
            Im Beitrag sichern asynchrone Methode, die von Service Fabric, damit der Benutzer alle nach der Sicherung Aktivität abgeschlossen wird, vor dem Zurückgeben der Steuerung an das System kann aufgerufen wird.
            Wenn <b>null</b> übergeben, inkrementelle Sicherungen sind nicht zulässig.
            Wenn die Methode nach der Sicherung auf "false" zurückgibt, sind dann erneut inkrementelle Sicherungen nicht zulässig.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Erstellt asynchron eine Sicherung des Schlüssel/Wert-Speichers.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen backup-Vorgang darstellt.</returns>
        <remarks>
            Die <b>PostBackupAsyncFunc</b> wird nicht aufgerufen, wenn während der Sicherung ein Fehler aufgetreten ist. Außerdem ist es nicht aufgerufen wird, wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> , da es ist keine weitere Aktion, die vom Benutzer in diesem Fall einen einzelnen Sicherungszyklus abgeschlossen erforderlich.
            </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>BackupDirectory</b> ist <b>null</b> Wenn <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen beim <b>BackupOption</b> nicht <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" /> oder <b>BackupDirectory</b> nicht <b>null</b> bei <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.TruncateLogsOnly" />.
            </exception>
        <exception cref="T:System.Fabric.FabricBackupDirectoryNotEmptyException">
            Wenn <b>BackupOption</b> ist <see cref="F:System.Fabric.StoreBackupOption.Incremental" /> und das Sicherungsverzeichnis Dateien oder Unterverzeichnisse bereits enthält.        
            </exception>
        <exception cref="T:System.Fabric.FabricBackupInProgressException">
            Wenn eine zuvor begonnene Sicherung gerade ausgeführt wird.
            </exception>
        <example>
            Im folgenden finden Sie ein Beispiel für eine einfache Implementierung der <b>PostBackupAsyncFunc</b><code>
            private async Task&lt;bool&gt; SimplePostBackupHandler(StoreBackupInfo info)
            {
                return await CopyBackupToAzureBlobStorage(info);
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="ChangeRoleAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; ChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; ChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.ChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.ChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.ChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;ChangeRoleAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para>Die replikatrolle Ziel.</para>
        </param>
        <param name="cancellationToken">
          <para>Derzeit wird nicht verwendet. Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Ändert die replikatrolle, der das Replikat als auch ihre Replikator an.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, deren Ergebnis die Adresse für dieses Replikat ist.</para>
        </returns>
        <remarks>
          <para>Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster. In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" /> stattdessen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.CloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.CloseAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;CloseAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Derzeit wird nicht verwendet. Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Schließt das Replikat und ihre Replikator Vorbereitung aus einem Replikatsatz offline geschaltet.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Das Replikat nicht zwangsläufig entfernt dauerhaft aus dem Replikatsatz und kann zu einem späteren Zeitpunkt erneut geöffnet werden. Die häufigsten Ursachen für das Schließen eines Replikats ist als Vorbereitung für das Upgrade oder Lastenausgleich ein ordnungsgemäßes Herunterfahren. Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster. In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" /> stattdessen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Contains">
      <MemberSignature Language="C#" Value="public bool Contains (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool Contains(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Contains(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Contains : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.Contains (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts, die (als Zeichenfolge) gesucht. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Bestimmt, ob ein Wert im Schlüssel/Wert-Speicher enthalten ist.</para>
        </summary>
        <returns>
          <para>
            <languageKeyword>"true"</languageKeyword> , wenn der Wert im Schlüssel/Wert-Speicher; enthalten ist <languageKeyword>"false"</languageKeyword>, andernfalls.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction () As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : unit -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Erstellt einen eindeutigen <see cref="T:System.Fabric.Transaction" /> -Instanz, die verwendet wird, um einen commit oder Rollback-Gruppen von Schlüssel/Wert-Speichervorgänge.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.Transaction" /> Objekt, das eine Transaktion darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateTransaction">
      <MemberSignature Language="C#" Value="public System.Fabric.Transaction CreateTransaction (System.Fabric.KeyValueStoreTransactionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.Transaction CreateTransaction(class System.Fabric.KeyValueStoreTransactionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.CreateTransaction(System.Fabric.KeyValueStoreTransactionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTransaction (settings As KeyValueStoreTransactionSettings) As Transaction" />
      <MemberSignature Language="F#" Value="member this.CreateTransaction : System.Fabric.KeyValueStoreTransactionSettings -&gt; System.Fabric.Transaction" Usage="keyValueStoreReplica.CreateTransaction settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Transaction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.KeyValueStoreTransactionSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Die transaktionseinstellungen.</para>
        </param>
        <summary>
          <para>Erstellt einen eindeutigen <see cref="T:System.Fabric.Transaction" /> -Instanz, die verwendet wird, um einen commit oder Rollback-Gruppen von Schlüssel/Wert-Speichervorgänge.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.Transaction" /> Objekt, das eine Transaktion darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLossReported">
      <MemberSignature Language="C#" Value="public event EventHandler DataLossReported;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler DataLossReported" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.KeyValueStoreReplica.DataLossReported" />
      <MemberSignature Language="VB.NET" Value="Public Event DataLossReported As EventHandler " />
      <MemberSignature Language="F#" Value="member this.DataLossReported : EventHandler " Usage="member this.DataLossReported : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Handler für einem Datenverlust.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <summary>
          <para>Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert-Speicher.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</para>
        </returns>
        <remarks>
          <para>
            Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="keyPrefix">
          <para>Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge). Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert speichern, bei denen die Wert-Schlüssel für das angegebene Präfix übereinstimmen.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</para>
        </returns>
        <remarks>
          <para>
            Entspricht dem Aufruf von <see cref="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" /> mit <b>StrictPrefix</b> festgelegt <languageKeyword>"true"</languageKeyword>.
            </para>
          <para>
            Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enumerate">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt; Enumerate (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItem&gt; Enumerate(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Enumerate(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enumerate : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;" Usage="keyValueStoreReplica.Enumerate (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItem&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="keyPrefix">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge). Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="strictPrefix">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben. Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind. Der Standardwert ist <b>True</b>.</param>
        <summary>
            Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItem" /> Werte im Schlüssel/Wert-Speicher.
            </summary>
        <returns>Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Enumerator.</returns>
        <remarks>
          <para>
            Die Elemente werden in aufsteigender lexikografisch nach Schlüssel aufgelistet.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata transactionBase" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <summary>
          <para>Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert-Speicher.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="keyPrefix">
          <para>Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge). Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert speichern, bei denen die Wert-Schlüssel für das angegebene Präfix übereinstimmen.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</para>
        </returns>
        <remarks>
            Entspricht dem Aufruf von <see cref="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" /> mit <b>StrictPrefix</b> festgelegt <languageKeyword>"true"</languageKeyword>.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnumerateMetadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata (System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreItemMetadata&gt; EnumerateMetadata(class System.Fabric.TransactionBase transactionBase, string keyPrefix, bool strictPrefix) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.EnumerateMetadata(System.Fabric.TransactionBase,System.String,System.Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnumerateMetadata : System.Fabric.TransactionBase * string * bool -&gt; System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;" Usage="keyValueStoreReplica.EnumerateMetadata (transactionBase, keyPrefix, strictPrefix)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreItemMetadata&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="keyPrefix" Type="System.String" />
        <Parameter Name="strictPrefix" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="keyPrefix">Der Schlüssel oder Index, Präfix entsprechend (als Zeichenfolge). Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="strictPrefix">Wenn "true" werden nur Schlüssel, die durch den Wert für das Präfix <b>KeyPrefix</b> werden zurückgegeben. Andernfalls Enumeration beginnt bei den ersten Schlüssel übereinstimmenden oder lexikografisch größer als <b>KeyPrefix</b> und wird fortgesetzt, bis keine weitere Schlüssel sind. Der Standardwert ist <b>True</b>.</param>
        <summary>
            Gibt einen Enumerator, der durchläuft die <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Werte im Schlüssel/Wert-Speicher.
            </summary>
        <returns>Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Enumerator.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem Get (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem Get(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Get(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Get : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.Get (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Ruft den gespeicherten Wert als ein <see cref="T:System.Fabric.KeyValueStoreItem" /> -Objekt, dem angegebenen Schlüssel zugeordnet.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt, das den gespeicherten Wert darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCurrentEpoch">
      <MemberSignature Language="C#" Value="public System.Fabric.Epoch GetCurrentEpoch ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance valuetype System.Fabric.Epoch GetCurrentEpoch() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetCurrentEpoch" />
      <MemberSignature Language="VB.NET" Value="Public Function GetCurrentEpoch () As Epoch" />
      <MemberSignature Language="F#" Value="member this.GetCurrentEpoch : unit -&gt; System.Fabric.Epoch" Usage="keyValueStoreReplica.GetCurrentEpoch " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Epoch</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Ruft die aktuelle Epoche für den Schlüssel/Wert-Speicher ab.</para>
        </summary>
        <returns>
          <para>Der aktuelle Epoche für den Schlüssel/Wert-Speicher.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata GetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata GetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.GetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Ruft die Metadaten als eine <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt für den angegebenen Schlüssel zugeordnete Wert.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> Objekt, das den angegebenen Wert zugeordnete Metadaten darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetValue">
      <MemberSignature Language="C#" Value="public byte[] GetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] GetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.GetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.GetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.GetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Ruft den gespeicherten Wert als ein Byte-Array, das dem angegebenen Schlüssel zugeordnet.</para>
        </summary>
        <returns>
          <para>Ein Bytearray, das den gespeicherten Wert darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreSequenceNumberCheck">
      <MemberSignature Language="C#" Value="public const long IgnoreSequenceNumberCheck = 0;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal int64 IgnoreSequenceNumberCheck = (0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberSignature Language="VB.NET" Value="Public Const IgnoreSequenceNumberCheck As Long  = 0" />
      <MemberSignature Language="F#" Value="val mutable IgnoreSequenceNumberCheck : int64" Usage="System.Fabric.KeyValueStoreReplica.IgnoreSequenceNumberCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass es sich bei Sequence Number Überprüfung nicht ausgeführt werden soll.</para>
        </summary>
        <remarks>
          <para>
             Kann verwendet werden in einer Check Sequence-Number-Parameter akzeptieren-APIs um anzugeben, dass die Sequenz Anzahl Überprüfung nicht ausgeführt werden soll:<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" /></description></item></list>
             
             Dies ist äquivalent zum Aufrufen des API-Überladungen, die nicht über eine Check Sequence-Number-Parameter verfügen:<list type="bullet"><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" /></description></item><item><description><see cref="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" /></description></item></list></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Initialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.Initialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.Initialize initializationParameters" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.Initialize(System.Fabric.StatefulServiceInitializationParameters)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para>Die Initialisierungsinformationen für das Replikat.</para>
        </param>
        <summary>
          <para>Initialisiert das Replikat als Vorbereitung für das Öffnen.</para>
        </summary>
        <remarks>
          <para>Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster. In diesem Fall sollte die anwendungsreplikaten überschreiben <see cref="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" /> stattdessen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyValueStoreReplicaSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.KeyValueStoreReplicaSettings KeyValueStoreReplicaSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyValueStoreReplicaSettings As KeyValueStoreReplicaSettings" />
      <MemberSignature Language="F#" Value="member this.KeyValueStoreReplicaSettings : System.Fabric.KeyValueStoreReplicaSettings" Usage="System.Fabric.KeyValueStoreReplica.KeyValueStoreReplicaSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplicaSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die optionseinstellungen für die <see cref="T:System.Fabric.KeyValueStoreReplica" />.</para>
        </summary>
        <value>
          <para>Die <see cref="T:System.Fabric.KeyValueStoreReplica" /> option Einstellungen.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalStoreSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.LocalStoreSettings LocalStoreSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.LocalStoreSettings LocalStoreSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalStoreSettings As LocalStoreSettings" />
      <MemberSignature Language="F#" Value="member this.LocalStoreSettings : System.Fabric.LocalStoreSettings" Usage="System.Fabric.KeyValueStoreReplica.LocalStoreSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.LocalStoreSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die optionseinstellungen für den lokalen Schlüssel/Wert-Speicher.</para>
        </summary>
        <value>
          <para>Die Einstellungen für den lokalen Speicher-Option.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NotificationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode NotificationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.KeyValueStoreReplica/SecondaryNotificationMode NotificationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NotificationMode As KeyValueStoreReplica.SecondaryNotificationMode" />
      <MemberSignature Language="F#" Value="member this.NotificationMode : System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" Usage="System.Fabric.KeyValueStoreReplica.NotificationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreReplica+SecondaryNotificationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die sekundäre Benachrichtigungsmodus während der Erstellung dieses Replikats angegeben.</para>
        </summary>
        <value>
          <para>Der aktuelle Benachrichtigungsmodus des sekundären</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAbort">
      <MemberSignature Language="C#" Value="protected virtual void OnAbort ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnAbort() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnAbort" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnAbort ()" />
      <MemberSignature Language="F#" Value="abstract member OnAbort : unit -&gt; unit&#xA;override this.OnAbort : unit -&gt; unit" Usage="keyValueStoreReplica.OnAbort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
          <para>Wird aufgerufen, um diese Instanz zu beenden.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnChangeRoleAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;string&gt; OnChangeRoleAsync (System.Fabric.ReplicaRole newRole, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string&gt; OnChangeRoleAsync(valuetype System.Fabric.ReplicaRole newRole, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnChangeRoleAsync(System.Fabric.ReplicaRole,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;&#xA;override this.OnChangeRoleAsync : System.Fabric.ReplicaRole * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="keyValueStoreReplica.OnChangeRoleAsync (newRole, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="newRole" Type="System.Fabric.ReplicaRole" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="newRole">
          <para>Die Zielrolle.</para>
        </param>
        <param name="cancellationToken">
          <para>Derzeit wird nicht verwendet. Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Gibt an, dass dieses Replikat Rollen geändert hat.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, deren Ergebnis die auflösbaren Adresse für dieses Replikat ist.</para>
        </returns>
        <remarks>
          <para>Das Replikat für die Anwendung sollte diese Methode außer Kraft setzen, ableiten von <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster. Das Replikat für die Anwendung sollte Zurückgeben einer <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis ist die Adresse von diesem Replikat. Diese Adresse Replikat wird als ist und kann abgerufen (unverändert) mit vom System gespeichert <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />. Die Anwendung muss darauf achten, den Rollenwechsel rechtzeitig abgeschlossen werden, da die Neukonfiguration der Replikatgruppe hinter den Abschluss aller ausstehenden Änderung Rolle Aufrufe blockiert werden.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCloseAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnCloseAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnCloseAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCloseAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnCloseAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnCloseAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
          <para>Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das der Vorgang überwacht wird, die verwendet werden kann, um die Aufgabe des Abbruchs zu benachrichtigen.</para>
        </param>
        <summary>
          <para>Wird aufgerufen, wenn dieses Replikat Dienst beendet wird, und muss geschlossen.</para>
        </summary>
        <returns>
          <para>Der asynchrone Vorgang.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnCopyComplete">
      <MemberSignature Language="C#" Value="protected virtual void OnCopyComplete (System.Fabric.KeyValueStoreEnumerator enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnCopyComplete(class System.Fabric.KeyValueStoreEnumerator enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnCopyComplete(System.Fabric.KeyValueStoreEnumerator)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnCopyComplete (enumerator As KeyValueStoreEnumerator)" />
      <MemberSignature Language="F#" Value="abstract member OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit&#xA;override this.OnCopyComplete : System.Fabric.KeyValueStoreEnumerator -&gt; unit" Usage="keyValueStoreReplica.OnCopyComplete enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Fabric.KeyValueStoreEnumerator" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para>Der Enumerator, der zum Lesen von Daten auf dem sekundären Replikat verwendet wird.</para>
        </param>
        <summary>
          <para>Vom System auf sekundären Replikaten aufgerufen, wenn sie erstellen, die vom primären Server abgeschlossen haben und bereit sind, starten Replikationsvorgängen anwenden.</para>
          <para>Diese Methode wird nur auf sekundären Replikaten aufgerufen werden, wenn die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Objekt erstellt wurde, durch einen gültigen <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" /> Parameter.</para>
        </summary>
        <remarks>
          <para>Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> Objekt kann verwendet werden, um Daten auf dem sekundären Replikat im Rahmen dieser Methode lesen, bevor alle Replikationsvorgängen angewendet werden. Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> Objekt ist nicht mehr gültig, nachdem diese Methode zurückgegeben und kann nicht im Kontext dieser Methode verwendet werden. Die Anwendung muss diesen Rückruf rechtzeitig abgeschlossen, da Replikationsvorgängen sind auf dem sekundären Replikat in die Warteschlange gestellt und erste angewendet, bis dieser Methode werden nicht gestartet werden. achten. Die <see cref="T:System.Fabric.KeyValueStoreEnumerator" /> -Objekt wird in einer einzelnen zugrunde liegenden lokale Transaktion gesichert und ist nicht threadsicher.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDataLossAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task&lt;bool&gt; OnDataLossAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; OnDataLossAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDataLossAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.OnDataLossAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="keyValueStoreReplica.OnDataLossAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Das Token verwendet, um nach einem Abbruch des Vorgangs überprüfen.</param>
        <summary>
            Signale, die das Replikat festgelegt, können Datenverlust aufgetreten sind. Die Anwendung kann entweder überschreiben diese Methode, um das Ereignis asynchron zu verarbeiten, oder verwenden Sie die <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Ereignis synchron zu verarbeiten. Beide stellen das gleiche Ereignis dar.
            </summary>
        <returns>"True", um anzugeben, dass die Daten wurden geändert, während der Wiederherstellung, und legen Sie das Replikat muss neu synchronisiert werden. Andernfalls "false", um anzugeben, dass die Daten nicht modifiziert wurden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDatalossReported">
      <MemberSignature Language="C#" Value="protected virtual void OnDatalossReported (EventArgs args);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDatalossReported(class System.EventArgs args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnDatalossReported(System.EventArgs)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnDatalossReported (args As EventArgs)" />
      <MemberSignature Language="F#" Value="abstract member OnDatalossReported : EventArgs -&gt; unit&#xA;override this.OnDatalossReported : EventArgs -&gt; unit" Usage="keyValueStoreReplica.OnDatalossReported args" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="args" Type="System.EventArgs" />
      </Parameters>
      <Docs>
        <param name="args">
          <para>Derzeit enthält keine Daten. Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Signale, die das Replikat festgelegt, können Datenverlust aufgetreten sind. Die Anwendung kann diese Methode überschreiben, oder merken Sie sich die <see cref="E:System.Fabric.KeyValueStoreReplica.DataLossReported" /> Ereignis. Sowohl darstellen das gleiche Ereignis</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnInitialize">
      <MemberSignature Language="C#" Value="protected virtual void OnInitialize (System.Fabric.StatefulServiceInitializationParameters initializationParameters);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnInitialize(class System.Fabric.StatefulServiceInitializationParameters initializationParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnInitialize(System.Fabric.StatefulServiceInitializationParameters)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnInitialize (initializationParameters As StatefulServiceInitializationParameters)" />
      <MemberSignature Language="F#" Value="abstract member OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit&#xA;override this.OnInitialize : System.Fabric.StatefulServiceInitializationParameters -&gt; unit" Usage="keyValueStoreReplica.OnInitialize initializationParameters" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="initializationParameters" Type="System.Fabric.StatefulServiceInitializationParameters" />
      </Parameters>
      <Docs>
        <param name="initializationParameters">
          <para>Der Initialisierungsparameter für das Replikat Dienst dargestellt, als ein <see cref="T:System.Fabric.StatefulServiceInitializationParameters" /> Objekt.</para>
        </param>
        <summary>
          <para>Initialisiert eine neu erstellte dienstreplikats an.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnOpenAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnOpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnOpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnOpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnOpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnOpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para>Ein <see cref="T:System.Fabric.ReplicaOpenMode" /> Objekt, das für dieses Replikat angibt, ob es sich um neuen oder wiederhergestellten handelt.</para>
        </param>
        <param name="partition">
          <para>Ein <see cref="T:System.Fabric.IStatefulServicePartition" /> Objekt, das die Partitionsinformationen zustandsbehaftete Dienst für dieses Replikat darstellt. </para>
        </param>
        <param name="cancellationToken">
          <para>Ein <see cref="T:System.Threading.CancellationToken" /> Objekt, das der Vorgang überwacht wird, die verwendet werden kann, um die Aufgabe des Abbruchs zu benachrichtigen.</para>
        </param>
        <summary>
          <para>Wird aufgerufen, auf einem Replikat initialisierten Dienst, um ihn zu öffnen, sodass zusätzliche Aktionen ausgeführt werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> Objekt, das den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnReplicationOperation">
      <MemberSignature Language="C#" Value="protected virtual void OnReplicationOperation (System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; enumerator);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnReplicationOperation(class System.Collections.Generic.IEnumerator`1&lt;class System.Fabric.KeyValueStoreNotification&gt; enumerator) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnReplicationOperation(System.Collections.Generic.IEnumerator{System.Fabric.KeyValueStoreNotification})" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub OnReplicationOperation (enumerator As IEnumerator(Of KeyValueStoreNotification))" />
      <MemberSignature Language="F#" Value="abstract member OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit&#xA;override this.OnReplicationOperation : System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt; -&gt; unit" Usage="keyValueStoreReplica.OnReplicationOperation enumerator" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enumerator" Type="System.Collections.Generic.IEnumerator&lt;System.Fabric.KeyValueStoreNotification&gt;" />
      </Parameters>
      <Docs>
        <param name="enumerator">
          <para>Der Enumerator, der zum Lesen der Daten in diesen Replikationsvorgang verwendet wird.</para>
        </param>
        <summary>
          <para>Vom System auf sekundären Replikaten für eingehende Replikationsvorgängen aufgerufen. Jede <see cref="T:System.Fabric.KeyValueStoreNotification" /> Objekt enthält alle Daten für einen einzelnen atomic Replikationsvorgang.</para>
        </summary>
        <remarks>
          <para>Diese Methode wird nur auf sekundären Replikaten aufgerufen werden, wenn die <see cref="T:System.Fabric.KeyValueStoreReplica" /> Objekt erstellt wurde, durch einen gültigen <see cref="T:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode" />.</para>
          <para>Wenn die <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.BlockSecondaryAck" /> Modus wurde angegeben, wird der eingehende Replikationsvorgang ist nicht lokal auf dem sekundären Replikat angewendet und mit dem primären Replikat bestätigt wurde, bis die Methode einen Wert zurückgibt. Dies bedeutet, dass die Anwendung dafür sorgen, dass muss zum Blockieren der replikationsdatenstrom Vermeiden von dieser Methode rechtzeitig zurückgegeben. Da die Bestätigung nicht mit dem primären Replikat gesendet werden, bis diese Methode einen Wert zurückgibt, es kann nicht als gegeben angenommen, dass der beobachteten Replikationsvorgang bereits wurde (oder ist garantiert in der Zukunft) durch ein Quorum der Replikate in der Replikatgruppe angewendet.</para>
          <para>Wenn die <see cref="F:System.Fabric.KeyValueStoreReplica.SecondaryNotificationMode.NonBlockingQuorumAcked" /> -Modus festgelegt wurde, dann wird sichergestellt, dass der beobachteten Replikationsvorgang bereits durch ein Quorum der Replikate in der Replikatgruppe angewendet wurden. Darüber hinaus der beobachteten Replikationsvorgang möglicherweise bereits lokal durch diese sekundäre Datenbank angewendet und bestätigt wurden mit dem primären Replikat zu dem Zeitpunkt, den die Methode, die vom System aufgerufen wird. Der Rückruf für die Methode wird nicht verhindert, die replikationsdatenstrom in diesem Modus, aber die Replikation Benachrichtigung vorgangsdatenstrom weiterhin blockiert. D. h. ist es rein eine ausstehende OnReplicationOperation Methode Rückruf zu einem beliebigen Zeitpunkt.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnRestoreCompletedAsync">
      <MemberSignature Language="C#" Value="protected virtual System.Threading.Tasks.Task OnRestoreCompletedAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task OnRestoreCompletedAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OnRestoreCompletedAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.OnRestoreCompletedAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.OnRestoreCompletedAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Das Token verwendet, um nach einem Abbruch des Vorgangs überprüfen.</param>
        <summary>
            Signalisiert, dass das Replikat Zustand erfolgreich vom System wiederhergestellt wurde.
            Dies wird nur aufgerufen, wenn System intern eine Wiederherstellung über den Service Wiederherstellung ausgelöst.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt; OpenAsync (System.Fabric.ReplicaOpenMode openMode, System.Fabric.IStatefulServicePartition partition, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.IReplicator&gt; OpenAsync(valuetype System.Fabric.ReplicaOpenMode openMode, class System.Fabric.IStatefulServicePartition partition, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;&#xA;override this.OpenAsync : System.Fabric.ReplicaOpenMode * System.Fabric.IStatefulServicePartition * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;" Usage="keyValueStoreReplica.OpenAsync (openMode, partition, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Fabric.IStatefulServiceReplica.OpenAsync(System.Fabric.ReplicaOpenMode,System.Fabric.IStatefulServicePartition,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(System.Fabric.KeyValueStoreReplica/&lt;OpenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.IReplicator&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="openMode" Type="System.Fabric.ReplicaOpenMode" />
        <Parameter Name="partition" Type="System.Fabric.IStatefulServicePartition" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="openMode">
          <para>Gibt den Kontext, unter dem dieses Replikat geöffnet wird.</para>
        </param>
        <param name="partition">
          <para>Enthält Informationen zur Beschreibung der Replikatgruppe zu dem das Replikat gehört.</para>
        </param>
        <param name="cancellationToken">
          <para>Derzeit wird nicht verwendet. Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Öffnet das Replikat als auch ihre Replikator als Vorbereitung für die in einer Replikatgruppe online geschaltet.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe an, dass der Abschluss der geöffneten <see cref="T:System.Threading.Tasks.Task`1" />.</para>
        </returns>
        <remarks>
          <para>Diese Methode muss nicht explizit aufgerufen werden, wenn das Replikat für die Anwendung abgeleitet <see cref="T:System.Fabric.KeyValueStoreReplica" />, dies ist das empfohlene Muster. In diesem Fall sollte die anwendungsreplikaten OnOpenAsync stattdessen außer Kraft setzen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <summary>
          <para>Entfernt den Wert, der durch den angegebenen Schlüssel indiziert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Remove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Remove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Remove : System.Fabric.TransactionBase * string * int64 -&gt; unit" Usage="keyValueStoreReplica.Remove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <param name="checkSequenceNumber">
          <para>Die erwartete Sequenznummer des Schlüssels, der entfernt werden soll.</para>
        </param>
        <summary>
          <para>Entfernt den Wert, der durch den angegebenen Schlüssel indiziert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplicatorSettings">
      <MemberSignature Language="C#" Value="public System.Fabric.ReplicatorSettings ReplicatorSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ReplicatorSettings ReplicatorSettings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReplicatorSettings As ReplicatorSettings" />
      <MemberSignature Language="F#" Value="member this.ReplicatorSettings : System.Fabric.ReplicatorSettings" Usage="System.Fabric.KeyValueStoreReplica.ReplicatorSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ReplicatorSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt die optionseinstellungen für Schlüssel/Wert-Speicher Replikator.</para>
        </summary>
        <value>
          <para>Die Einstellungen der Store Replikator-Option.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public void Restore (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Restore(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Restore(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restore (backupDirectory As String)" />
      <MemberSignature Language="F#" Value="member this.Restore : string -&gt; unit" Usage="keyValueStoreReplica.Restore backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RestoreAsync instead")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
          <para>Der vollständige Pfad zu einem Verzeichnis mit einer Sicherung.</para>
        </param>
        <summary>
          <para>Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</para>
        </summary>
        <remarks>
          <para>Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt. Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden. Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</para>
          <para>Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestoreAsync (backupDirectory As String) As Task" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync backupDirectory" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <summary>
          <para>Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</para>
        </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
          <para>Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>. </para>
          <para>Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt. Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden. Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</para>
          <para>Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>BackupDirectory</b> ist <b>null</b>.
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>BackupDirectory</b> ist nicht vorhanden.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <param name="cancellationToken">
          <para>das Abbruchtoken, das</para>
        </param>
        <summary>
          <para>Dieses Replikat lokalen Speicher-Datenbank aus einer Sicherung, die zuvor durch den Aufruf erstellt wurde wiederhergestellt <see cref="M:System.Fabric.KeyValueStoreReplica.BackupAsync(System.String,System.Fabric.StoreBackupOption,System.Func{System.Fabric.StoreBackupInfo,System.Threading.Tasks.Task{System.Boolean}})" />.</para>
        </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
          <para>Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>. </para>
          <para>Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt. Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden. Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</para>
          <para>Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>BackupDirectory</b> ist <b>null</b>.
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>BackupDirectory</b> ist nicht vorhanden.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestoreAsync (string backupDirectory, System.Fabric.RestoreSettings settings, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestoreAsync(string backupDirectory, class System.Fabric.RestoreSettings settings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.RestoreAsync(System.String,System.Fabric.RestoreSettings,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestoreAsync : string * System.Fabric.RestoreSettings * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="keyValueStoreReplica.RestoreAsync (backupDirectory, settings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backupDirectory" Type="System.String" />
        <Parameter Name="settings" Type="System.Fabric.RestoreSettings" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="backupDirectory">
            Das Verzeichnis, in dem das Replikat aus wiederhergestellt werden.
            Dieser Parameter kann nicht null, leer oder enthält nur Leerzeichen. UNC-Pfade können auch angegeben werden.
            </param>
        <param name="settings">
            Verhalten wiederherstellen, die Einstellungen zu ändern.
            </param>
        <param name="cancellationToken">Das Token zum überwachen von Abbruchanforderungen.</param>
        <summary>
            Asynchron wiederhergestellt, das Schlüssel/Wert-Speicher-Replikat.
            </summary>
        <returns>Eine Aufgabe, die den asynchronen Restore-Vorgang darstellt.</returns>
        <remarks>
          <para>Es wird empfohlen, alle Schreibvorgänge in den Schlüssel/Wert-Speicher nicht ausgeführt werden, während die Wiederherstellung ausgeführt wird, da die aktualisierten Daten verloren gehen würden aus den Dateien in der Speicher wiederhergestellt wird <b>BackupDirectory</b>. </para>
          <para>Dies ist nur ein lokales Replikat wiederherstellen und die Replikatgruppe werden nicht automatisch wiederhergestellt. Die gesamte Replikatgruppe muss zusätzliche Schritte ausführen, die dazu führen, dass einen natürlichen Build der anderen Replikate über die Neukonfiguration wiederhergestellt werden. Die empfohlene Vorgehensweise ist in einem leeren Dienst mit nur einem einzelnen Replikat und danach mit einem Aufruf von Größe der zielreplikatgruppe Erhöhung wiederherstellen <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" /> bei Bedarf.</para>
          <para>Wenn die Wiederherstellung erfolgreich ist, wird das Replikat sich selbst neu starten und beginnen mit den wiederhergestellten lokalen Daten nach wieder online geschaltet, davon ausgehend, dass die Empfehlung, die in einer Replikatgruppe, enthält nur ein einzelnes Replikat wiederherstellen ausgeführt wurde.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">
          <b>BackupDirectory</b> ist <b>null</b>.
            </exception>
        <exception cref="T:System.ArgumentException">
          <b>BackupDirectory</b> ist leer oder enthält nur Leerzeichen.
            </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <b>BackupDirectory</b> ist nicht vorhanden.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="StoreName">
      <MemberSignature Language="C#" Value="public string StoreName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoreName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreName As String" />
      <MemberSignature Language="F#" Value="member this.StoreName : string" Usage="System.Fabric.KeyValueStoreReplica.StoreName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft ab oder legt den Namen des Schlüssel/Wert-Speichers.</para>
        </summary>
        <value>
          <para>Der Name des Schlüssel/Wert-Speichers.</para>
        </value>
        <remarks>
          <para>Der Speichername muss gültige Dateinamenzeichen entsprechen.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="TryAdd">
      <MemberSignature Language="C#" Value="public bool TryAdd (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryAdd(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryAdd(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryAdd : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryAdd (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als eine Zeichenfolge) hinzugefügt werden. Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="value">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</param>
        <summary>
            Speichern Versuche, einen Wert, der durch den angegebenen Schlüssel auf den Schlüssel/Wert indiziert hinzuzufügen.
            </summary>
        <returns>"True", wenn der angegebene Schlüssel nicht bereits gefunden und hinzugefügt wurde. "False", wenn der angegebene Schlüssel bereits vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGet">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItem TryGet (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItem TryGet(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGet(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGet : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItem" Usage="keyValueStoreReplica.TryGet (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</param>
        <summary>
            Versucht, erhalten den gespeicherten Wert als ein <see cref="T:System.Fabric.KeyValueStoreItem" /> -Objekt, dem angegebenen Schlüssel zugeordnet.
            </summary>
        <returns>Ein <see cref="T:System.Fabric.KeyValueStoreItem" /> Objekt, das den gespeicherten Wert darstellt, oder null, wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetMetadata">
      <MemberSignature Language="C#" Value="public System.Fabric.KeyValueStoreItemMetadata TryGetMetadata (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Fabric.KeyValueStoreItemMetadata TryGetMetadata(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetMetadata(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetMetadata : System.Fabric.TransactionBase * string -&gt; System.Fabric.KeyValueStoreItemMetadata" Usage="keyValueStoreReplica.TryGetMetadata (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.KeyValueStoreItemMetadata</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</param>
        <summary>
            Versucht, die Metadaten als Abrufen einer <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt für den angegebenen Schlüssel zugeordnete Wert.
            </summary>
        <returns>Ein <see cref="T:System.Fabric.KeyValueStoreItemMetadata" /> -Objekt, das die Metadaten darstellt, die mit dem angegebenen Wert verknüpft sind, oder null, wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryGetValue">
      <MemberSignature Language="C#" Value="public byte[] TryGetValue (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance unsigned int8[] TryGetValue(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryGetValue(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryGetValue : System.Fabric.TransactionBase * string -&gt; byte[]" Usage="keyValueStoreReplica.TryGetValue (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) abgerufen werden sollen. Beschränkt auf 800 Zeichen lang sein.</param>
        <summary>
            Versucht, den gespeicherten Wert als ein Bytearray mit dem angegebenen Schlüssel verknüpfte abzurufen.
            </summary>
        <returns>Ein Bytearray, das den gespeicherten Wert oder Null darstellt, wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll. Beschränkt auf 800 Zeichen lang sein.</param>
        <summary>
            Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu entfernen.
            </summary>
        <returns>"True", wenn der angegebene Schlüssel gefunden und entfernt wurde. "False", wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryRemove">
      <MemberSignature Language="C#" Value="public bool TryRemove (System.Fabric.TransactionBase transactionBase, string key, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryRemove(class System.Fabric.TransactionBase transactionBase, string key, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryRemove(System.Fabric.TransactionBase,System.String,System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryRemove : System.Fabric.TransactionBase * string * int64 -&gt; bool" Usage="keyValueStoreReplica.TryRemove (transactionBase, key, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) entfernt werden soll. Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="checkSequenceNumber">Die erwartete Sequenznummer des Schlüssels, der entfernt werden soll.</param>
        <summary>
            Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu entfernen.
            </summary>
        <returns>"True", wenn der angegebene Schlüssel gefunden und entfernt wurde. "False", wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) aktualisiert werden. Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="value">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</param>
        <summary>
            Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu aktualisieren.
            </summary>
        <returns>"True", wenn der angegebene Schlüssel gefunden und aktualisiert wurde. "False", wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryUpdate">
      <MemberSignature Language="C#" Value="public bool TryUpdate (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool TryUpdate(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.TryUpdate(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.TryUpdate : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; bool" Usage="keyValueStoreReplica.TryUpdate (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">Die Transaktion-Instanz.</param>
        <param name="key">Der Schlüssel oder Index, der den Wert (als Zeichenfolge) aktualisiert werden. Beschränkt auf 800 Zeichen lang sein.</param>
        <param name="value">Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</param>
        <param name="checkSequenceNumber">Die erwartete Sequenznummer des zu aktualisierenden Schlüssels.</param>
        <summary>
            Versucht, den Wert, der durch den angegebenen Schlüssel indiziert zu aktualisieren.
            </summary>
        <returns>"True", wenn der angegebene Schlüssel gefunden und aktualisiert wurde. "False", wenn der angegebene Schlüssel nicht vorhanden ist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[])" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als Zeichenfolge) aktualisiert werden. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <param name="value">
          <para>Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</para>
        </param>
        <summary>
          <para>Aktualisiert den gespeicherten Wert, der dem angegebenen Schlüssel zugeordnet.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public void Update (System.Fabric.TransactionBase transactionBase, string key, byte[] value, long checkSequenceNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Update(class System.Fabric.TransactionBase transactionBase, string key, unsigned int8[] value, int64 checkSequenceNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.Update(System.Fabric.TransactionBase,System.String,System.Byte[],System.Int64)" />
      <MemberSignature Language="F#" Value="member this.Update : System.Fabric.TransactionBase * string * byte[] * int64 -&gt; unit" Usage="keyValueStoreReplica.Update (transactionBase, key, value, checkSequenceNumber)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="transactionBase" Type="System.Fabric.TransactionBase" />
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="checkSequenceNumber" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="transactionBase">
          <para>Die Transaktion-Instanz.</para>
        </param>
        <param name="key">
          <para>Der Schlüssel oder Index des Werts (als Zeichenfolge) aktualisiert werden. Beschränkt auf 800 Zeichen lang sein.</para>
        </param>
        <param name="value">
          <para>Der Wert (als Bytearray) gespeichert werden, beschränkt auf 2GB umfassen.</para>
        </param>
        <param name="checkSequenceNumber">
          <para>Die erwartete Sequenznummer des zu aktualisierenden Schlüssels.</para>
        </param>
        <summary>
          <para>Aktualisiert den Wert, der durch den angegebenen Schlüssel indiziert.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateReplicatorSettings">
      <MemberSignature Language="C#" Value="public void UpdateReplicatorSettings (System.Fabric.ReplicatorSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UpdateReplicatorSettings(class System.Fabric.ReplicatorSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.KeyValueStoreReplica.UpdateReplicatorSettings(System.Fabric.ReplicatorSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UpdateReplicatorSettings (settings As ReplicatorSettings)" />
      <MemberSignature Language="F#" Value="member this.UpdateReplicatorSettings : System.Fabric.ReplicatorSettings -&gt; unit" Usage="keyValueStoreReplica.UpdateReplicatorSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="System.Fabric.ReplicatorSettings" />
      </Parameters>
      <Docs>
        <param name="settings">
          <para>Die Einstellungen, die zum Aktualisieren der Schlüssel-Wert zu Replikator speichern.</para>
        </param>
        <summary>
          <para>Aktualisiert die Schlüssel/Wert-Speicher Replicator mit den Einstellungen in der angegebenen <see cref="T:System.Fabric.ReplicatorSettings" /> Objekt.</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>