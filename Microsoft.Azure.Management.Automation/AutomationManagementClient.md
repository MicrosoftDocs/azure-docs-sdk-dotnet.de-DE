<Type Name="AutomationManagementClient" FullName="Microsoft.Azure.Management.Automation.AutomationManagementClient">
  <TypeSignature Language="C#" Value="public class AutomationManagementClient : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;, IDisposable, Microsoft.Azure.Management.Automation.IAutomationManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutomationManagementClient extends Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; implements class Microsoft.Azure.Management.Automation.IAutomationManagementClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.AutomationManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class AutomationManagementClient&#xA;Inherits ServiceClient(Of AutomationManagementClient)&#xA;Implements IAutomationManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type AutomationManagementClient = class&#xA;    inherit ServiceClient&lt;AutomationManagementClient&gt;&#xA;    interface IAutomationManagementClient&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Automation.AutomationManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Automation.IAutomationManagementClient</InterfaceName>
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
      <MemberSignature Language="C#" Value="public AutomationManagementClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient credentials" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.SubscriptionCloudCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die abonnementanmeldeinformationen ab Microsoft Azure-Abonnement eindeutig identifiziert. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient httpClient" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="httpClient">
            Der HTTP-client
            </param>
        <summary>
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As SubscriptionCloudCredentials, baseUri As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, baseUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutomationManagementClient (Microsoft.Azure.SubscriptionCloudCredentials credentials, Uri baseUri, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.SubscriptionCloudCredentials credentials, class System.Uri baseUri, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.#ctor(Microsoft.Azure.SubscriptionCloudCredentials,System.Uri,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Automation.AutomationManagementClient : Microsoft.Azure.SubscriptionCloudCredentials * Uri * System.Net.Http.HttpClient -&gt; Microsoft.Azure.Management.Automation.AutomationManagementClient" Usage="new Microsoft.Azure.Management.Automation.AutomationManagementClient (credentials, baseUri, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Initialisiert eine neue Instanz der Klasse "automationmanagementclient".
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Activities">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IActivityOperations Activities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IActivityOperations Activities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Activities" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Activities As IActivityOperations" />
      <MemberSignature Language="F#" Value="member this.Activities : Microsoft.Azure.Management.Automation.IActivityOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Activities" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Activities</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IActivityOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für-automatisierungsaktivitäten auf.  (siehe http://aka.ms/azureautomationsdk/activityoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AgentRegistrationInformation">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAgentRegistrationOperation AgentRegistrationInformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.AgentRegistrationInformation" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property AgentRegistrationInformation As IAgentRegistrationOperation" />
      <MemberSignature Language="F#" Value="member this.AgentRegistrationInformation : Microsoft.Azure.Management.Automation.IAgentRegistrationOperation" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.AgentRegistrationInformation" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AgentRegistrationInformation</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAgentRegistrationOperation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation agentregistrierungsinformationen.
            (siehe http://aka.ms/azureautomationsdk/agentregistrationoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ApiVersion</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="AutomationAccounts">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IAutomationAccountOperations AutomationAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.AutomationAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property AutomationAccounts As IAutomationAccountOperations" />
      <MemberSignature Language="F#" Value="member this.AutomationAccounts : Microsoft.Azure.Management.Automation.IAutomationAccountOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.AutomationAccounts" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.AutomationAccounts</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IAutomationAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Konten.  (siehe http://aka.ms/azureautomationsdk/automationaccountoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ICertificateOperations Certificates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICertificateOperations Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Certificates As ICertificateOperations" />
      <MemberSignature Language="F#" Value="member this.Certificates : Microsoft.Azure.Management.Automation.ICertificateOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Certificates" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Certificates</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Zertifikate.  (siehe http://aka.ms/azureautomationsdk/certificateoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="protected override void Clone (Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; client);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Clone(class Hyak.Common.ServiceClient`1&lt;class Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.Clone(Hyak.Common.ServiceClient{Microsoft.Azure.Management.Automation.AutomationManagementClient})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Clone (client As ServiceClient(Of AutomationManagementClient))" />
      <MemberSignature Language="F#" Value="override this.Clone : Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt; -&gt; unit" Usage="automationManagementClient.Clone client" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="Hyak.Common.ServiceClient&lt;Microsoft.Azure.Management.Automation.AutomationManagementClient&gt;" />
      </Parameters>
      <Docs>
        <param name="client">
            Instanz von "automationmanagementclient" zum Klonen in
            </param>
        <summary>
            Klont Eigenschaften aus der aktuellen Instanz in eine andere Instanz von "automationmanagementclient"
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompilationJobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscCompilationJobOperations CompilationJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.CompilationJobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property CompilationJobs As IDscCompilationJobOperations" />
      <MemberSignature Language="F#" Value="member this.CompilationJobs : Microsoft.Azure.Management.Automation.IDscCompilationJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.CompilationJobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.CompilationJobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscCompilationJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Dienstvorgang Automation dsc-Konfiguration kompilieren Aufträge.
            (siehe http://aka.ms/azureautomationsdk/dscccompilationjoboperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configurations">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscConfigurationOperations Configurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Configurations" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Configurations As IDscConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.Configurations : Microsoft.Azure.Management.Automation.IDscConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Configurations" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Configurations</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Konfigurationen.  (siehe http://aka.ms/azureautomationsdk/configurationoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Connections">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IConnectionOperations Connections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionOperations Connections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Connections" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Connections As IConnectionOperations" />
      <MemberSignature Language="F#" Value="member this.Connections : Microsoft.Azure.Management.Automation.IConnectionOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Connections" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Connections</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Verbindungen.  (siehe http://aka.ms/azureautomationsdk/connectionoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IConnectionTypeOperations ConnectionTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ConnectionTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ConnectionTypes As IConnectionTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ConnectionTypes : Microsoft.Azure.Management.Automation.IConnectionTypeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ConnectionTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ConnectionTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IConnectionTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation Connectiontypes.  (siehe http://aka.ms/azureautomationsdk/connectiontypeoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinuationTokenHandler&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.List&lt;T&gt; ContinuationTokenHandler&lt;T&gt; (Func&lt;string,Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;T&gt;&gt; listFunc);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.List`1&lt;!!T&gt; ContinuationTokenHandler&lt;T&gt;(class System.Func`2&lt;string, class Microsoft.Azure.Management.Automation.ResponseWithSkipToken`1&lt;!!T&gt;&gt; listFunc) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.ContinuationTokenHandler``1(System.Func{System.String,Microsoft.Azure.Management.Automation.ResponseWithSkipToken{``0}})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ContinuationTokenHandler(Of T) (listFunc As Func(Of String, ResponseWithSkipToken(Of T))) As List(Of T)" />
      <MemberSignature Language="F#" Value="static member ContinuationTokenHandler : Func&lt;string, Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;'T&gt;&gt; -&gt; System.Collections.Generic.List&lt;'T&gt;" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ContinuationTokenHandler listFunc" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.List&lt;T&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="listFunc" Type="System.Func&lt;System.String,Microsoft.Azure.Management.Automation.ResponseWithSkipToken&lt;T&gt;&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="listFunc">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.SubscriptionCloudCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.SubscriptionCloudCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As SubscriptionCloudCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.SubscriptionCloudCredentials" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Credentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="GetOperationResultStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync (string operationStatusLink, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt; GetOperationResultStatusAsync(string operationStatusLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.GetOperationResultStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationResultStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;&#xA;override this.GetOperationResultStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;" Usage="automationManagementClient.GetOperationResultStatusAsync (operationStatusLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationResultStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Automation.AutomationManagementClient/&lt;GetOperationResultStatusAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationResultResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operationStatusLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operationStatusLink">
            Erforderlich. Location-Wert, durch die Begin-Vorgang zurückgegeben wurden.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Der Vorgang Get Operation Status Gibt den Status des angegebenen Vorgangs zurück. Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.
            </summary>
        <returns>
            Eine standarddienstantwort für lang ausgeführte Vorgänge.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetOperationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync (string requestId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt; GetOperationStatusAsync(string requestId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.AutomationManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;&#xA;override this.GetOperationStatusAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;" Usage="automationManagementClient.GetOperationStatusAsync (requestId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Management.Automation.IAutomationManagementClient.GetOperationStatusAsync(System.String,System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Automation.AutomationManagementClient/&lt;GetOperationStatusAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.LongRunningOperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestId">
            Erforderlich. Die Anforderungs-ID für die Anforderung, die Sie verfolgen möchten. Die Anforderungs-ID wird in der X-ms-Request-Id-Antwort-Header für jede Anforderung zurückgegeben.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Der Vorgang Get Operation Status Gibt den Status des Vorgangs Thespecified zurück. Nach dem Aufrufen eines asynchronen Vorgangs, können Sie aufrufen Vorgangsstatus abrufen, um festzustellen, ob der Vorgang erfolgreich war, fehlgeschlagen ist, oder ist noch nicht abgeschlossen.  (siehe http://msdn.microsoft.com/en-us/library/windowsazure/ee460783.aspx für Weitere Informationen)
            </summary>
        <returns>
            Der Antworttext enthält den Status des angegebenen asynchronen Vorgangs, der angibt, ob es erfolgreich war, in Bearbeitung, oder fehlgeschlagen ist. Beachten Sie, dass dieser Status aus der HTTP-Statuscode zurückgegeben, die für den Get Operation Status Vorgang selbst eindeutig sind.  Wenn der asynchrone Vorgang erfolgreich war, enthält der Antworttext den HTTP-Statuscode für die erfolgreiche Anforderung.  Wenn der asynchrone Vorgang fehlgeschlagen ist, wird der Antworttext enthält den HTTP-Statuscode für die fehlerhafte Anforderung, und enthält auch Informationen zum Fehler.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridRunbookWorkerGroups">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations HybridRunbookWorkerGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property HybridRunbookWorkerGroups As IHybridRunbookWorkerGroupOperations" />
      <MemberSignature Language="F#" Value="member this.HybridRunbookWorkerGroups : Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.HybridRunbookWorkerGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.HybridRunbookWorkerGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IHybridRunbookWorkerGroupOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation Hybrid Runbook Worker-Gruppe.  (siehe http://aka.ms/azureautomationsdk/hybridrunbookworkergroupoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Jobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobOperations Jobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobOperations Jobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Jobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Jobs As IJobOperations" />
      <MemberSignature Language="F#" Value="member this.Jobs : Microsoft.Azure.Management.Automation.IJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Jobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Jobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Aufträge.  (siehe http://aka.ms/azureautomationsdk/joboperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobSchedules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobScheduleOperations JobSchedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.JobSchedules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property JobSchedules As IJobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobSchedules : Microsoft.Azure.Management.Automation.IJobScheduleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.JobSchedules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobSchedules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Auftragszeitpläne.  (siehe http://aka.ms/azureautomationsdk/jobscheduleoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobStreams">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IJobStreamOperations JobStreams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.JobStreams" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property JobStreams As IJobStreamOperations" />
      <MemberSignature Language="F#" Value="member this.JobStreams : Microsoft.Azure.Management.Automation.IJobStreamOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.JobStreams" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.JobStreams</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IJobStreamOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Auftrag-Streams.  (siehe http://aka.ms/azureautomationsdk/jobstreamoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationInitialTimeout">
      <MemberSignature Language="C#" Value="public int LongRunningOperationInitialTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 LongRunningOperationInitialTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationInitialTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationInitialTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationInitialTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationInitialTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Integer" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : int with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="Modules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IModuleOperations Modules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IModuleOperations Modules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Modules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Modules As IModuleOperations" />
      <MemberSignature Language="F#" Value="member this.Modules : Microsoft.Azure.Management.Automation.IModuleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Modules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Modules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IModuleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Module.  (siehe http://aka.ms/azureautomationsdk/moduleoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeConfigurations">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations NodeConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property NodeConfigurations As IDscNodeConfigurationOperations" />
      <MemberSignature Language="F#" Value="member this.NodeConfigurations : Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeConfigurations" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeConfigurations</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeConfigurationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation dsc-Knotenkonfigurationen.  (siehe http://aka.ms/azureautomationsdk/dscnodeconfigurations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeReports">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeReportsOperations NodeReports" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeReports" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property NodeReports As IDscNodeReportsOperations" />
      <MemberSignature Language="F#" Value="member this.NodeReports : Microsoft.Azure.Management.Automation.IDscNodeReportsOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.NodeReports" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.NodeReports</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeReportsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Knoten Berichte.  (siehe http://aka.ms/azureautomationsdk/dscnodereportoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Nodes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IDscNodeOperations Nodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Nodes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Nodes As IDscNodeOperations" />
      <MemberSignature Language="F#" Value="member this.Nodes : Microsoft.Azure.Management.Automation.IDscNodeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Nodes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Nodes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IDscNodeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für dsc-Knoten.  (siehe http://aka.ms/azureautomationsdk/dscnodeoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ObjectDataTypes">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IObjectDataTypeOperations ObjectDataTypes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ObjectDataTypes" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property ObjectDataTypes As IObjectDataTypeOperations" />
      <MemberSignature Language="F#" Value="member this.ObjectDataTypes : Microsoft.Azure.Management.Automation.IObjectDataTypeOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ObjectDataTypes" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ObjectDataTypes</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IObjectDataTypeOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation Object-Datentypen.  (siehe http://aka.ms/azureautomationsdk/objectdatatypeoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PsCredentials">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ICredentialOperations PsCredentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.PsCredentials" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property PsCredentials As ICredentialOperations" />
      <MemberSignature Language="F#" Value="member this.PsCredentials : Microsoft.Azure.Management.Automation.ICredentialOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.PsCredentials" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.PsCredentials</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ICredentialOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Anmeldeinformationen.  (siehe http://aka.ms/azureautomationsdk/credentialoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceNamespace">
      <MemberSignature Language="C#" Value="public string ResourceNamespace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceNamespace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.ResourceNamespace" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceNamespace As String" />
      <MemberSignature Language="F#" Value="member this.ResourceNamespace : string with get, set" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.ResourceNamespace" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.ResourceNamespace</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ressourcennamespace.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunbookDraft">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookDraftOperations RunbookDraft" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.RunbookDraft" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property RunbookDraft As IRunbookDraftOperations" />
      <MemberSignature Language="F#" Value="member this.RunbookDraft : Microsoft.Azure.Management.Automation.IRunbookDraftOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.RunbookDraft" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.RunbookDraft</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookDraftOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-runbookentwurfs.  (siehe http://aka.ms/azureautomationsdk/runbookdraftoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Runbooks">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IRunbookOperations Runbooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Runbooks" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Runbooks As IRunbookOperations" />
      <MemberSignature Language="F#" Value="member this.Runbooks : Microsoft.Azure.Management.Automation.IRunbookOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Runbooks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Runbooks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IRunbookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Runbooks.  (siehe http://aka.ms/azureautomationsdk/runbookoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Schedules">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IScheduleOperations Schedules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IScheduleOperations Schedules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Schedules" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Schedules As IScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.Schedules : Microsoft.Azure.Management.Automation.IScheduleOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Schedules" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Schedules</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Zeitpläne.  (siehe http://aka.ms/azureautomationsdk/scheduleoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistics">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IStatisticsOperations Statistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Statistics" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Statistics As IStatisticsOperations" />
      <MemberSignature Language="F#" Value="member this.Statistics : Microsoft.Azure.Management.Automation.IStatisticsOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Statistics" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Statistics</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IStatisticsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Statistiken.  (siehe http://aka.ms/azureautomationsdk/statisticsoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestJobs">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITestJobOperations TestJobs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.TestJobs" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TestJobs As ITestJobOperations" />
      <MemberSignature Language="F#" Value="member this.TestJobs : Microsoft.Azure.Management.Automation.ITestJobOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.TestJobs" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TestJobs</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITestJobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation Testaufträge.  (siehe http://aka.ms/azureautomationsdk/testjoboperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TypeFields">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.ITypeFieldOperations TypeFields" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.TypeFields" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property TypeFields As ITypeFieldOperations" />
      <MemberSignature Language="F#" Value="member this.TypeFields : Microsoft.Azure.Management.Automation.ITypeFieldOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.TypeFields" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.TypeFields</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.ITypeFieldOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Feldern.  (siehe http://aka.ms/azureautomationsdk/typefieldoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usages">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IUsageOperations Usages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IUsageOperations Usages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Usages" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Usages As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usages : Microsoft.Azure.Management.Automation.IUsageOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Usages" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Usages</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation Verwendungen.  (siehe http://aka.ms/azureautomationsdk/usageoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Variables">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IVariableOperations Variables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IVariableOperations Variables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Variables" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Variables As IVariableOperations" />
      <MemberSignature Language="F#" Value="member this.Variables : Microsoft.Azure.Management.Automation.IVariableOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Variables" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Variables</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IVariableOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Variablen.  (siehe http://aka.ms/azureautomationsdk/variableoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Webhooks">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Automation.IWebhookOperations Webhooks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Automation.AutomationManagementClient.Webhooks" />
      <MemberSignature Language="VB.NET" Value="Public Overridable ReadOnly Property Webhooks As IWebhookOperations" />
      <MemberSignature Language="F#" Value="member this.Webhooks : Microsoft.Azure.Management.Automation.IWebhookOperations" Usage="Microsoft.Azure.Management.Automation.AutomationManagementClient.Webhooks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Automation.IAutomationManagementClient.Webhooks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Automation.IWebhookOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Der Dienstvorgang für Automation-Webhook.  (siehe http://aka.ms/azureautomationsdk/webhookoperations für Weitere Informationen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>