<Type Name="IStorSimpleManagementClient" FullName="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient">
  <TypeSignature Language="C#" Value="public interface IStorSimpleManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IStorSimpleManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IStorSimpleManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IStorSimpleManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die API-Version ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Backup">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations Backup { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations Backup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Backup" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backup As IBackupOperations" />
      <MemberSignature Language="F#" Value="member this.Backup : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Backup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der Sicherung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations BackupPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations BackupPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BackupPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BackupPolicy As IBackupPolicyOperations" />
      <MemberSignature Language="F#" Value="member this.BackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BackupPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der Backup-Richtlinien
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneVolume">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations CloneVolume { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations CloneVolume" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloneVolume" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloneVolume As ICloneVolumeOperations" />
      <MemberSignature Language="F#" Value="member this.CloneVolume : Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloneVolume" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit CloneVolume (http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx für Weitere Informationen siehe)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudServiceName">
      <MemberSignature Language="C#" Value="public string CloudServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CloudServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloudServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudServiceName As String" />
      <MemberSignature Language="F#" Value="member this.CloudServiceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.CloudServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.SubscriptionCloudCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataContainer">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations DataContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations DataContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DataContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataContainer As IDataContainerOperations" />
      <MemberSignature Language="F#" Value="member this.DataContainer : Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DataContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDataContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit Volumecontainern
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceDetails">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations DeviceDetails { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations DeviceDetails" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceDetails" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceDetails As IDeviceDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceDetails" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der Gerätedetails
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceFailover">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations DeviceFailover { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations DeviceFailover" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceFailover" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceFailover As IDeviceFailoverOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceFailover : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceFailover" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der Geräte-Failover
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeviceJob">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations DeviceJob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations DeviceJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceJob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeviceJob As IDeviceJobOperations" />
      <MemberSignature Language="F#" Value="member this.DeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DeviceJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit Aufträgen Gerät
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DevicePublicKey">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations DevicePublicKey { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations DevicePublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DevicePublicKey" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DevicePublicKey As IDevicePublicKeyOperations" />
      <MemberSignature Language="F#" Value="member this.DevicePublicKey : Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.DevicePublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDevicePublicKeyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit Gerät öffentliche Schlüssel
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Devices">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations Devices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations Devices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Devices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Devices As IDeviceOperations" />
      <MemberSignature Language="F#" Value="member this.Devices : Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.Devices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IDeviceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der Geräte
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync (string taskId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; GetOperationStatusAsync(string taskId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iStorSimpleManagementClient.GetOperationStatusAsync (taskId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="taskId">
            Der Task-Id für die Anforderung, die Sie nachverfolgen möchten.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Der Vorgangsstatus abrufen gibt den Status der angegebenen Task-Id zurück. Nach dem Aufrufen einer asynchronen Aufgabe an, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.
            </summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IscsiConnection">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations IscsiConnection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations IscsiConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.IscsiConnection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IscsiConnection As IIscsiConnectionDetailsOperations" />
      <MemberSignature Language="F#" Value="member this.IscsiConnection : Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.IscsiConnection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IIscsiConnectionDetailsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit iSCSI-Verbindung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ursprüngliche Timeout für zeitintensive Vorgänge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das wiederholungstimeout für zeitintensive Vorgänge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrateLegacyAppliance">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations MigrateLegacyAppliance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations MigrateLegacyAppliance" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.MigrateLegacyAppliance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MigrateLegacyAppliance As IMigrationOperations" />
      <MemberSignature Language="F#" Value="member this.MigrateLegacyAppliance : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.MigrateLegacyAppliance" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Migration von Legacy-Appliance
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceEncryptionKeys">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations ResourceEncryptionKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations ResourceEncryptionKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceEncryptionKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceEncryptionKeys As IResourceEncryptionKeyOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceEncryptionKeys : Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceEncryptionKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IResourceEncryptionKeyOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit dem kryptografischen Schlüssel
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceName">
      <MemberSignature Language="C#" Value="public string ResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceName As String" />
      <MemberSignature Language="F#" Value="member this.ResourceName : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNamespace">
      <MemberSignature Language="C#" Value="public string ResourceNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceNamespace : string with get, set" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ResourceNamespace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceConfig">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations ServiceConfig { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations ServiceConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ServiceConfig" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceConfig As IServiceConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.ServiceConfig : Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.ServiceConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IServiceConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit Dienstkonfigurationen
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDevice">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations VirtualDevice { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations VirtualDevice" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDevice" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualDevice As IVirtualDeviceOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualDevice : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDevice" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit virtuellen Geräts
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualDisk">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations VirtualDisk { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations VirtualDisk" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDisk" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualDisk As IVirtualDiskOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualDisk : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations" Usage="Microsoft.WindowsAzure.Management.StorSimple.IStorSimpleManagementClient.VirtualDisk" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.IVirtualDiskOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Alle Vorgänge im Zusammenhang mit der virtuellen Datenträger
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>