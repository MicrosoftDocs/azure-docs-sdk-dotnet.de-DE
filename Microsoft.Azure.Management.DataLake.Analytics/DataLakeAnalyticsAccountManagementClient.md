<Type Name="DataLakeAnalyticsAccountManagementClient" FullName="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient">
  <TypeSignature Language="C#" Value="public class DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeAnalyticsAccountManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt; implements class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeAnalyticsAccountManagementClient&#xA;Inherits ServiceClient(Of DataLakeAnalyticsAccountManagementClient)&#xA;Implements IAzureClient, IDataLakeAnalyticsAccountManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataLakeAnalyticsAccountManagementClient = class&#xA;    inherit ServiceClient&lt;DataLakeAnalyticsAccountManagementClient&gt;&#xA;    interface IDataLakeAnalyticsAccountManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Rest.Azure.IAzureClient</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Erstellt einen Verwaltungsclient für Data Lake-Speicher-Konto an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (Uri baseUri, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClientCredentials * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (credentials, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die Anmeldeinformationen für Azure-Abonnement ab.
            </param>
        <param name="userAgentAssemblyVersion">
            Optional. Die Versionszeichenfolge, die im Benutzer-Agent-Header für alle Anforderungen gesendet werden soll. Die Standardeinstellung ist die aktuelle Version des SDK.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeAnalyticsAccountManagementClient (Uri baseUri, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (baseUri As Uri, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeAnalyticsAccountManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (credentials, rootHandler, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="credentials">
            Erforderlich. Ruft die Anmeldeinformationen für Azure-Abonnement ab.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="userAgentAssemblyVersion">
            Optional. Die Versionszeichenfolge, die im Benutzer-Agent-Header für alle Anforderungen gesendet werden soll. Die Standardeinstellung ist die aktuelle Version des SDK.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, credentials, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="credentials">
            Erforderlich. Ruft die Anmeldeinformationen für Azure-Abonnement ab.
            </param>
        <param name="userAgentAssemblyVersion">
            Optional. Die Versionszeichenfolge, die im Benutzer-Agent-Header für alle Anforderungen gesendet werden soll. Die Standardeinstellung ist die aktuelle Version des SDK.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeAnalyticsAccountManagementClient (Uri baseUri, Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.#ctor(System.Uri,Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient : Uri * Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient (baseUri, credentials, rootHandler, userAgentAssemblyVersion, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="baseUri">
            Optional. Die Basis-URI des Diensts.
            </param>
        <param name="credentials">
            Erforderlich. Ruft die Anmeldeinformationen für Azure-Abonnement ab.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="userAgentAssemblyVersion">
            Optional. Die Versionszeichenfolge, die im Benutzer-Agent-Header für alle Anforderungen gesendet werden soll. Die Standardeinstellung ist die aktuelle Version des SDK.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die bevorzugte Sprache für die Antwort.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Account">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations Account { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations Account" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Account" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Account As IAccountOperations" />
      <MemberSignature Language="F#" Value="member this.Account : Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Account" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IAccountOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IAccountOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Client-API-Version.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.BaseUri</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Basis-URI des Diensts.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputePolicies">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations ComputePolicies { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations ComputePolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ComputePolicies" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputePolicies As IComputePoliciesOperations" />
      <MemberSignature Language="F#" Value="member this.ComputePolicies : Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.ComputePolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IComputePoliciesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IComputePoliciesOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLakeStoreAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations DataLakeStoreAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations DataLakeStoreAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DataLakeStoreAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataLakeStoreAccounts As IDataLakeStoreAccountsOperations" />
      <MemberSignature Language="F#" Value="member this.DataLakeStoreAccounts : Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DataLakeStoreAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IDataLakeStoreAccountsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IDataLakeStoreAccountsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Deserialisierung Einstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FirewallRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations FirewallRules { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations FirewallRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.FirewallRules" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FirewallRules As IFirewallRulesOperations" />
      <MemberSignature Language="F#" Value="member this.FirewallRules : Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.FirewallRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IFirewallRulesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IFirewallRulesOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bei Festlegung werden auf einen eindeutigen X-ms-Client-Request-Id-Wert "true" generiert und in jeder Anforderung enthalten. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das wiederholungstimeout in Sekunden für zeitintensive Vorgänge.
            Standardwert ist 30.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder Json-Serialisierungseinstellungen definiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations StorageAccounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageAccounts As IStorageAccountsOperations" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.IStorageAccountsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IStorageAccountsOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.DataLakeAnalyticsAccountManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Analytics.IDataLakeAnalyticsAccountManagementClient.SubscriptionId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Rufen Sie die abonnementanmeldeinformationen, die Microsoft Azure-Abonnement eindeutig identifiziert werden. Die Abonnement-ID ist Teil der URI für jeden Dienstaufruf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>