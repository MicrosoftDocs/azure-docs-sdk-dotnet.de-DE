<Type Name="BackupVaultServicesManagementClient" FullName="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient">
  <TypeSignature Language="C#" Value="public class BackupVaultServicesManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;, IDisposable, Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BackupVaultServicesManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; implements class Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BackupVaultServicesManagementClient&#xA;Inherits ServiceClient(Of BackupVaultServicesManagementClient)&#xA;Implements IBackupVaultServicesManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type BackupVaultServicesManagementClient = class&#xA;    inherit ServiceClient&lt;BackupVaultServicesManagementClient&gt;&#xA;    interface IBackupVaultServicesManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </param>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            Der HTTP-client
            </param>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </param>
        <param name="httpClient">
            Der HTTP-client
            </param>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </param>
        <param name="baseUri">
            Optional. Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.
            </param>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BackupVaultServicesManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient" Usage="new Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </param>
        <param name="baseUri">
            Optional. Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.
            </param>
        <param name="httpClient">
            Der HTTP-client
            </param>
        <summary>
            Initialisiert eine neue Instanz der BackupVaultServicesManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
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
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
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
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of BackupVaultServicesManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt; -&gt; unit" Usage="backupVaultServicesManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            Instanz des BackupVaultServicesManagementClient zum Klonen in
            </param>
        <summary>
            Klont Eigenschaften aus der aktuellen Instanz in eine andere BackupVaultServicesManagementClient-Instanz
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IMarsContainerOperations Container { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IMarsContainerOperations Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Container" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Container As IMarsContainerOperations" />
      <MemberSignature Language="F#" Value="member this.Container : Microsoft.Azure.Management.BackupServices.IMarsContainerOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Container" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Container</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IMarsContainerOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Definition der containervorgänge für die Azure Backup-Erweiterung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
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
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
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
    <Member MemberName="Vault">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.BackupServices.IVaultOperations Vault { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BackupServices.IVaultOperations Vault" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Vault" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Vault As IVaultOperations" />
      <MemberSignature Language="F#" Value="member this.Vault : Microsoft.Azure.Management.BackupServices.IVaultOperations" Usage="Microsoft.Azure.Management.BackupServices.BackupVaultServicesManagementClient.Vault" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.BackupServices.IBackupVaultServicesManagementClient.Vault</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BackupServicesManagement</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BackupServices.IVaultOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Definition der Tresor-bezogenen Vorgänge für die Azure Backup-Erweiterung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>