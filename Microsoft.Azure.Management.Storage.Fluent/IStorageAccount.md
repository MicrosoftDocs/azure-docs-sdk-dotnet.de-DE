<Type Name="IStorageAccount" FullName="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount">
  <TypeSignature Language="C#" Value="public interface IStorageAccount : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorageAccount implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageManager, class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorageAccount&#xA;Implements IGroupableResource(Of IStorageManager, StorageAccountInner), IHasInner(Of StorageAccountInner), IHasManager(Of IStorageManager), IRefreshable(Of IStorageAccount), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IStorageAccount = interface&#xA;    interface IGroupableResource&lt;IStorageManager, StorageAccountInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IStorageManager&gt;&#xA;    interface IHasInner&lt;StorageAccountInner&gt;&#xA;    interface IRefreshable&lt;IStorageAccount&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager,Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Storage.Fluent.IStorageAccount&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Storage.Fluent.StorageAccount.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung von Azure Storage-Konto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier AccessTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessTier As AccessTier" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Zugriff auf Dienstebene, die für die Abrechnung verwendet. Zugriffstarifs kann mehr als einmal alle 7 Tage (168 Stunden) geändert werden. Zugriffstarifs kann nicht für StandardLRS, StandardGRS, StandardRAGRS oder PremiumLRS Kontotypen festgelegt werden.
            Folgende Werte sind möglich: "Hot", "Super".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountStatuses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.AccountStatuses AccountStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.AccountStatuses AccountStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccountStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccountStatuses As AccountStatuses" />
      <MemberSignature Language="F#" Value="member this.AccountStatuses : Microsoft.Azure.Management.Storage.Fluent.AccountStatuses" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.AccountStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.AccountStatuses</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status, der angibt, ob die primären und sekundären Standort des Speicherkontos verfügbar oder nicht verfügbar ist. Folgende Werte sind möglich: "Verfügbar", "Nicht verfügbar".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public DateTime CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreationTime : DateTime" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Erstellungsdatum und die Uhrzeit des Speicherkontos (UTC) an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Erhält der Benutzer, die benutzerdefinierte Domäne dieses Speicherkonto zugewiesen zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Einstellungen für die Verschlüsselung für das Konto an. Sofern nicht angegeben, das Konto ist unverschlüsselt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionKeySource">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource EncryptionKeySource { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource EncryptionKeySource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionKeySource" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionKeySource As StorageAccountEncryptionKeySource" />
      <MemberSignature Language="F#" Value="member this.EncryptionKeySource : Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionKeySource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.StorageAccountEncryptionKeySource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptionStatuses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService,Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt; EncryptionStatuses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;class Microsoft.Azure.Management.Storage.Fluent.StorageService, class Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt; EncryptionStatuses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionStatuses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EncryptionStatuses As IReadOnlyDictionary(Of StorageService, IStorageAccountEncryptionStatus)" />
      <MemberSignature Language="F#" Value="member this.EncryptionStatuses : System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService, Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt;" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EncryptionStatuses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;Microsoft.Azure.Management.Storage.Fluent.StorageService,Microsoft.Azure.Management.Storage.Fluent.IStorageAccountEncryptionStatus&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPoints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints EndPoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints EndPoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EndPoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndPoints As PublicEndpoints" />
      <MemberSignature Language="F#" Value="member this.EndPoints : Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.EndPoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.PublicEndpoints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URLs, die für den Abruf eines öffentlichen BLOB-, Warteschlange oder Tabelle-Objekts verwendet werden. Beachten Sie, dass Konten StandardZRS "und" PremiumLRS nur der blobendpunkt zurückgegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; GetKeys ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; GetKeys() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.GetKeys" />
      <MemberSignature Language="VB.NET" Value="Public Function GetKeys () As IReadOnlyList(Of StorageAccountKey)" />
      <MemberSignature Language="F#" Value="abstract member GetKeys : unit -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;" Usage="iStorageAccount.GetKeys " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Rufen Sie die auf dem neuesten Stand Zugriffsschlüssel für dieses Speicherkonto aus Azure ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Der Zugriffsschlüssel für dieses Speicherkonto.</return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; GetKeysAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; GetKeysAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.GetKeysAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;" Usage="iStorageAccount.GetKeysAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Rufen Sie die auf dem neuesten Stand Zugriffsschlüssel von Azure für dieses Speicherkonto asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt für die Zugriffsschlüssel für dieses Speicherkonto.</return>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Fluent.Models.Kind" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Art des Speicherkontos. Mögliche Werte sind "Storage", "BlobStorage".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastGeoFailoverTime">
      <MemberSignature Language="C#" Value="public DateTime LastGeoFailoverTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastGeoFailoverTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.LastGeoFailoverTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastGeoFailoverTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastGeoFailoverTime : DateTime" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.LastGeoFailoverTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitstempel der letzten Instanz eines Failovers zum sekundären Speicherort ab. Nur die neueste Zeitstempel wird beibehalten. Dieses Element wird nicht zurückgegeben, wenn es nie eine Failoverinstanz noch war.
            Nur verfügbar, wenn die AccountType StandardGRS oder StandardRAGRS ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status des Speicherkontos zu dem Zeitpunkt, der Vorgang aufgerufen wurde. Folgende Werte sind möglich: "Erstellen", "ResolvingDNS", "erfolgreich abgeschlossen".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKey">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; RegenerateKey (string keyName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt; RegenerateKey(string keyName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.RegenerateKey(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegenerateKey (keyName As String) As IReadOnlyList(Of StorageAccountKey)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKey : string -&gt; System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;" Usage="iStorageAccount.RegenerateKey keyName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">Wenn der Name des Schlüssels.</param>
        <summary>
            Generiert die Zugriffsschlüssel für dieses Speicherkonto neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die generierten Zugriffsschlüssel für dieses Speicherkonto.</return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; RegenerateKeyAsync (string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt; RegenerateKeyAsync(string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.RegenerateKeyAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateKeyAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;" Usage="iStorageAccount.RegenerateKeyAsync (keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountKey&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="keyName">Wenn der Name des Schlüssels.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Die Zugriffsschlüssel für dieses Speicherkonto asynchron generiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt für die Zugriffsschlüssel für dieses Speicherkonto.</return>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Storage.Fluent.IStorageAccount.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Sku des dieses Speicherkonto ab. Mögliche Namen enthalten: "Standard_LRS", "standard_zrs" "", "Standard_GRS", "Standard_RAGRS", "Premium_LRS". Mögliche Ebenen enthalten: "Standard", "Premium".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>