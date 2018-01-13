<Type Name="DataLakeStoreFileSystemManagementClient" FullName="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient">
  <TypeSignature Language="C#" Value="public class DataLakeStoreFileSystemManagementClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient&gt;, IDisposable, Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataLakeStoreFileSystemManagementClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient&gt; implements class Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class DataLakeStoreFileSystemManagementClient&#xA;Inherits ServiceClient(Of DataLakeStoreFileSystemManagementClient)&#xA;Implements IAzureClient, IDataLakeStoreFileSystemManagementClient, IDisposable" />
  <TypeSignature Language="F#" Value="type DataLakeStoreFileSystemManagementClient = class&#xA;    inherit ServiceClient&lt;DataLakeStoreFileSystemManagementClient&gt;&#xA;    interface IDataLakeStoreFileSystemManagementClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient</InterfaceName>
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
            Erstellt einen Data Lake-Speicher Filesystem-Management-Client.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeStoreFileSystemManagementClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Initialisiert eine neue Instanz der DataLakeStoreFileSystemManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected DataLakeStoreFileSystemManagementClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            Initialisiert eine neue Instanz der DataLakeStoreFileSystemManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFileSystemManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion = &quot;&quot;, string adlsFileSystemDnsSuffix = &quot;azuredatalakestore.net&quot;, int clientTimeoutInMinutes = 5, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, string userAgentAssemblyVersion, string adlsFileSystemDnsSuffix, int32 clientTimeoutInMinutes, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.String,System.String,System.Int32,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlsFileSystemDnsSuffix As String = &quot;azuredatalakestore.net&quot;, Optional clientTimeoutInMinutes As Integer = 5, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient : Microsoft.Rest.ServiceClientCredentials * string * string * int * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient (credentials, userAgentAssemblyVersion, adlsFileSystemDnsSuffix, clientTimeoutInMinutes, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlsFileSystemDnsSuffix" Type="System.String" />
        <Parameter Name="clientTimeoutInMinutes" Type="System.Int32" />
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
        <param name="adlsFileSystemDnsSuffix">
            Optional. Das DNS-Suffix für alle Anforderungen für diese Clientinstanz verwendet. Der Standardwert ist "azuredatalakestore.net".
            </param>
        <param name="clientTimeoutInMinutes">
            Optional. Die maximale Zeitdauer wartet der Client für den Server, auf eine Anforderung zu reagieren. Der Standardwert beträgt fünf Minuten.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreFileSystemManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataLakeStoreFileSystemManagementClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion = &quot;&quot;, string adlsFileSystemDnsSuffix = &quot;azuredatalakestore.net&quot;, int clientTimeoutInMinutes = 5, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, string userAgentAssemblyVersion, string adlsFileSystemDnsSuffix, int32 clientTimeoutInMinutes, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.String,System.String,System.Int32,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, Optional userAgentAssemblyVersion As String = &quot;&quot;, Optional adlsFileSystemDnsSuffix As String = &quot;azuredatalakestore.net&quot;, Optional clientTimeoutInMinutes As Integer = 5, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * string * string * int * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient" Usage="new Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient (credentials, rootHandler, userAgentAssemblyVersion, adlsFileSystemDnsSuffix, clientTimeoutInMinutes, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
        <Parameter Name="rootHandler" Type="System.Net.Http.HttpClientHandler" />
        <Parameter Name="userAgentAssemblyVersion" Type="System.String" />
        <Parameter Name="adlsFileSystemDnsSuffix" Type="System.String" />
        <Parameter Name="clientTimeoutInMinutes" Type="System.Int32" />
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
        <param name="adlsFileSystemDnsSuffix">
            Optional. Das DNS-Suffix für alle Anforderungen für diese Clientinstanz verwendet. Der Standardwert ist "azuredatalakestore.net".
            </param>
        <param name="clientTimeoutInMinutes">
            Optional. Die maximale Zeitdauer wartet der Client für den Server, auf eine Anforderung zu reagieren. Der Standardwert beträgt fünf Minuten.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der DataLakeStoreFileSystemManagementClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="AdlsFileSystemDnsSuffix">
      <MemberSignature Language="C#" Value="public string AdlsFileSystemDnsSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdlsFileSystemDnsSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.AdlsFileSystemDnsSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property AdlsFileSystemDnsSuffix As String" />
      <MemberSignature Language="F#" Value="member this.AdlsFileSystemDnsSuffix : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.AdlsFileSystemDnsSuffix" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient.AdlsFileSystemDnsSuffix</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den URI, der als Basis für alle Cloud-Service-Requests verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
    <Member MemberName="FileSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations FileSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations FileSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.FileSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FileSystem As IFileSystemOperations" />
      <MemberSignature Language="F#" Value="member this.FileSystem : Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.FileSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.IFileSystemOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IFileSystemOperations ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.DataLake.Store.IDataLakeStoreFileSystemManagementClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.DataLake.Store.DataLakeStoreFileSystemManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
  </Members>
</Type>