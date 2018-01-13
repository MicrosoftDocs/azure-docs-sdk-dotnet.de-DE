<Type Name="KeyVaultClient" FullName="Microsoft.Azure.KeyVault.KeyVaultClient">
  <TypeSignature Language="C#" Value="public class KeyVaultClient : Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;, IDisposable, Microsoft.Azure.KeyVault.IKeyVaultClient, Microsoft.Rest.Azure.IAzureClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeyVaultClient extends Microsoft.Rest.ServiceClient`1&lt;class Microsoft.Azure.KeyVault.KeyVaultClient&gt; implements class Microsoft.Azure.KeyVault.IKeyVaultClient, class Microsoft.Rest.Azure.IAzureClient, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClient" />
  <TypeSignature Language="VB.NET" Value="Public Class KeyVaultClient&#xA;Inherits ServiceClient(Of KeyVaultClient)&#xA;Implements IAzureClient, IDisposable, IKeyVaultClient" />
  <TypeSignature Language="F#" Value="type KeyVaultClient = class&#xA;    inherit ServiceClient&lt;KeyVaultClient&gt;&#xA;    interface IKeyVaultClient&#xA;    interface IDisposable&#xA;    interface IAzureClient" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Rest.ServiceClient&lt;Microsoft.Azure.KeyVault.KeyVaultClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.KeyVault.KeyVaultClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.KeyVault.IKeyVaultClient</InterfaceName>
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
            Kryptografische Schlüssel Vorgänge und Tresor Vorgänge für die Key Vault-Dienst-Client-Klasse.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient handlers" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
            Initialisiert eine neue Instanz der KeyVaultClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="handlers" Type="System.Net.Http.DelegatingHandler[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="authenticationCallback">Der authentifizierungsrückruf</param>
        <param name="handlers">Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.</param>
        <summary>
            Konstruktor
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback authenticationCallback, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultClient/AuthenticationCallback authenticationCallback, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultClient.AuthenticationCallback * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (authenticationCallback, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authenticationCallback" Type="Microsoft.Azure.KeyVault.KeyVaultClient+AuthenticationCallback" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="authenticationCallback">Der authentifizierungsrückruf</param>
        <param name="httpClient">Benutzerdefinierten HTTP-client </param>
        <summary>
            Konstruktor
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Azure.KeyVault.KeyVaultCredential credential, System.Net.Http.HttpClient httpClient);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.KeyVaultCredential credential, class System.Net.Http.HttpClient httpClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Azure.KeyVault.KeyVaultCredential,System.Net.Http.HttpClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Azure.KeyVault.KeyVaultCredential * System.Net.Http.HttpClient -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credential, httpClient)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credential" Type="Microsoft.Azure.KeyVault.KeyVaultCredential" />
        <Parameter Name="httpClient" Type="System.Net.Http.HttpClient" />
      </Parameters>
      <Docs>
        <param name="credential">Anmeldeinformationen für den schlüsseltresor-Vorgänge</param>
        <param name="httpClient">Benutzerdefinierten HTTP-client </param>
        <summary>
            Konstruktor
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
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
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected KeyVaultClient (System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
            Initialisiert eine neue Instanz der KeyVaultClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyVaultClient (Microsoft.Rest.ServiceClientCredentials credentials, System.Net.Http.HttpClientHandler rootHandler, params System.Net.Http.DelegatingHandler[] handlers);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Rest.ServiceClientCredentials credentials, class System.Net.Http.HttpClientHandler rootHandler, class System.Net.Http.DelegatingHandler[] handlers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.#ctor(Microsoft.Rest.ServiceClientCredentials,System.Net.Http.HttpClientHandler,System.Net.Http.DelegatingHandler[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (credentials As ServiceClientCredentials, rootHandler As HttpClientHandler, ParamArray handlers As DelegatingHandler())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyVaultClient : Microsoft.Rest.ServiceClientCredentials * System.Net.Http.HttpClientHandler * System.Net.Http.DelegatingHandler[] -&gt; Microsoft.Azure.KeyVault.KeyVaultClient" Usage="new Microsoft.Azure.KeyVault.KeyVaultClient (credentials, rootHandler, handlers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Rest.ServiceClientCredentials" />
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
        <param name="credentials">
            Erforderlich. Anmeldeinformationen für den Client zum Verbinden mit Azure erforderlich.
            </param>
        <param name="rootHandler">
            Optional. Der Client HTTP-Handler zum Verarbeiten von HTTP-Transport verwendet.
            </param>
        <param name="handlers">
            Optional. Die delegierenden Handler der HTTP-Client-Pipeline hinzu.
            </param>
        <summary>
            Initialisiert eine neue Instanz der KeyVaultClient-Klasse.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
      </Docs>
    </Member>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.AcceptLanguage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="ApiVersion">
      <MemberSignature Language="C#" Value="public string ApiVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ApiVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApiVersion As String" />
      <MemberSignature Language="F#" Value="member this.ApiVersion : string" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.ApiVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="BackupKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt; BackupKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;&#xA;override this.BackupKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;" Usage="keyVaultClient.BackupKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupKeyWithHttpMessagesAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fordert an, dass eine Sicherung des angegebenen Schlüssels an den Client heruntergeladen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Schlüssel Sicherungsvorgang exportiert einen Schlüssel aus dem Azure-Schlüsseltresor in einer geschützten Form. Beachten Sie, dass dieser Vorgang gibt keinen Schlüsselmaterial zurück, in ein Formular, das außerhalb der Azure Key Vault-System verwendet werden kann, das zurückgegebene Schlüsselmaterial ist entweder geschützt ein Azure-Schlüsseltresor-HSM oder Azure Key Vault selbst.
            Der Zweck dieses Vorgangs ist, kann einen Client einen Schlüssel in einer Instanz von Azure Key Vault, Sichern Sie den Schlüssel generieren und dann in eine andere Azure Key Vault-Instanz wiederherstellen. Der Sicherungsvorgang kann verwendet werden, in geschützter Form jedes Schlüsseltyps im Azure Key Vault zu exportieren. Einzelne Versionen eines Schlüssels können nicht gesichert werden. Sicherung / Wiederherstellung nur; innerhalb geografischer Grenzen ausgeführt werden kann. Dies bedeutet, dass eine Sicherung aus einem geografischen Bereich nicht zu einem anderen geografischen Bereich wiederhergestellt werden kann. Beispielsweise kann eine Sicherung von geografischen Gebiet der USA in einer geografischen Bereich der EU wiederhergestellt werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt; BackupSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;&#xA;override this.BackupSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;" Usage="keyVaultClient.BackupSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.BackupSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;BackupSecretWithHttpMessagesAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fordert an, dass eine Sicherung des angegebenen geheimen Schlüssels an den Client heruntergeladen werden.
            Autorisierung: ist der geheime Schlüssel/Backup-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; CreateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.CreateCertificateWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.CreateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateCertificateWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateCertificateWithHttpMessagesAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string curve = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; CreateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string curve, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.CreateKeyWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.CreateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, curve, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.CreateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;CreateKeyWithHttpMessagesAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="curve" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name für den neuen Schlüssel. Das System generiert den Versionsnamen für den neuen Schlüssel.
            </param>
        <param name="kty">
            Der Typ des Schlüssels zu erstellen. Gültige Werte finden Sie unter JsonWebKeyType. Folgende Werte sind möglich: "EC", "EC-HSM", "RSA", "RSA-HSM", "oct"
            </param>
        <param name="keySize">
            Die Schlüsselgröße in Bytes. Z. B. 1024 oder 2048.
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="curve">
            Name der Elliptische Kurve. Gültige Werte finden Sie unter JsonWebKeyCurveName. Folgende Werte sind möglich: "P-256", "P-384", "P-521", "SECP256K1"
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Schlüssel, speichert ihn, dann gibt Schlüsselparameter und Attribute an den Client.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Erstellvorgang Schlüssel kann zum Erstellen jedes Schlüsseltyps im Azure-Schlüsseltresor verwendet werden. Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="DecryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; DecryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.DecryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.DecryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DecryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DecryptWithHttpMessagesAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entschlüsselt einen einzelnen Block von verschlüsselten Daten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der DECRYPT-Vorgang entschlüsselt einen wohlgeformten Block mit verschlüsseltem Text transformiert, die mit dem Ziel-Verschlüsselungsschlüssel und angegebenen Algorithmus. Dieser Vorgang ist die Umkehrung des ENCRYPT-Vorgangs; nur ein einzelner Datenblock entschlüsselt werden kann, ist die Größe dieses Blocks vom Zielschlüssel und dem zu verwendenden Algorithmus abhängig. Der DECRYPT-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; DeleteCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.DeleteCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateContactsWithHttpMessagesAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die Zertifikat-Kontakte für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht die Zertifikat-Kontakte für ein Zertifikat für die angegebene schlüsseltresor.
            Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; DeleteCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.DeleteCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateIssuerWithHttpMessagesAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den angegebenen Zertifikataussteller an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang DeleteCertificateIssuer werden endgültig gelöscht der Aussteller des angegebenen Zertifikats aus dem Tresor.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; DeleteCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.DeleteCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateOperationWithHttpMessagesAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den Vorgang für ein angegebenes Zertifikat. Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; DeleteCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.DeleteCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.DeleteCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteCertificateWithHttpMessagesAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Zertifikat aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht alle Versionen eines Objekts Zertifikat zusammen mit der zugeordneten Richtlinien. Löschen von Zertifikat kann nicht verwendet werden, um einzelne Versionen eines Objekts Zertifikat zu entfernen.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; DeleteKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.DeleteKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.DeleteKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteKeyWithHttpMessagesAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels zu löschen.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Schlüssel eines beliebigen Typs aus dem Speicher in Azure Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Löschvorgang Schlüssel kann nicht zum Entfernen einzelner Versionen eines Schlüssels verwendet werden. Dieser Vorgang entfernt das kryptografische Material, das dem Schlüssel, was bedeutet, dass der Schlüssel nicht für Sign/Verify-, Wrap/Unwrap- oder Encrypt/Decrypt-Vorgänge verwendet werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; DeleteSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.DeleteSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSasDefinitionWithHttpMessagesAsync&gt;d__106))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine SAS-Definition aus einem angegebenen Speicherkonto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; DeleteSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.DeleteSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.DeleteSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteSecretWithHttpMessagesAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen geheimen Schlüssel aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der DELETE-Vorgang gilt für alle geheimen Schlüssel in Azure Key Vault gespeichert.
            DELETE kann nicht für eine einzelne Version eines geheimen Schlüssels angewendet werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; DeleteStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.DeleteStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.DeleteStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.DeleteStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;DeleteStorageAccountWithHttpMessagesAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Speicherkonto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="EncryptWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; EncryptWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.EncryptWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.EncryptWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.EncryptWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;EncryptWithHttpMessagesAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in einem schlüsseltresor gespeichert sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der ENCRYPT-Vorgang verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in Azure Key Vault gespeichert ist. Beachten Sie, dass der ENCRYPT-Vorgang nur einen einzelnen Block von Daten unterstützt, deren Größe vom Zielschlüssel und den zu verwendenden Verschlüsselungsalgorithmus abhängig ist. Der ENCRYPT-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mithilfe der öffentliche Teil des Schlüssels ausgeführt werden kann. Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.GenerateClientRequestId</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.GenerateClientRequestId</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="GetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; GetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.GetCertificateContactsWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.GetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateContactsWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateContactsWithHttpMessagesAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Kontakte Zertifikat für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der GetCertificateContacts-Vorgang gibt den Satz von Zertifikat Kontakt Ressourcen im angegebenen schlüsseltresor.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersNextWithHttpMessagesAsync&gt;d__117))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt; GetCertificateIssuersWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;&#xA;override this.GetCertificateIssuersWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuersWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuersWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuersWithHttpMessagesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; GetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.GetCertificateIssuerWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateIssuerWithHttpMessagesAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet den Aussteller des angegebenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuer gibt das angegebene Zertifikat Aussteller Ressourcen im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; GetCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.GetCertificateOperationWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.GetCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateOperationWithHttpMessagesAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein angegebenes Zertifikat zugeordneten Vorgangs ab. Autorisierung: erfordert die Zertifikate/Get-Berechtigung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; GetCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.GetCertificatePolicyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.GetCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatePolicyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatePolicyWithHttpMessagesAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in einer bestimmten schlüsseltresor.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Richtlinie für ein Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificatePolicy gibt das angegebene Zertifikat Richtlinie Ressourcen im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesNextWithHttpMessagesAsync&gt;d__116))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikate in einem angegebenen Schlüssel Tresor
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificatesWithHttpMessagesAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikate in einem angegebenen Schlüssel Tresor
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsNextWithHttpMessagesAsync&gt;d__118))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt; GetCertificateVersionsWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;&#xA;override this.GetCertificateVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetCertificateVersionsWithHttpMessagesAsync (vaultBaseUrl, certificateName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateVersionsWithHttpMessagesAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; GetCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.GetCertificateWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.GetCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetCertificateWithHttpMessagesAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in den angegebenen Tresor.
            </param>
        <param name="certificateVersion">
            Die Version des Zertifikats.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu einem angegebenen Zertifikat ab. Autorisierung: erfordert die Zertifikate/Get-Berechtigung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesNextWithHttpMessagesAsync&gt;d__119))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt; GetDeletedCertificatesWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;&#xA;override this.GetDeletedCertificatesWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificatesWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificatesWithHttpMessagesAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt; GetDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;&#xA;override this.GetDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedCertificateWithHttpMessagesAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über das angegebene gelöschten Zertifikat ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificate abgerufen, die gelöschte Zertifikatinformationen sowie seiner Attribute, z. B. Aufbewahrungszeitraum, geplante permanent löschen und die aktuelle Ebene der Löschvorgang Wiederherstellung.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysNextWithHttpMessagesAsync&gt;d__112))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht Schlüssel in den angegebenen Tresor. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt; GetDeletedKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;&#xA;override this.GetDeletedKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeysWithHttpMessagesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht Schlüssel in den angegebenen Tresor. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt; GetDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;&#xA;override this.GetDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedKeyWithHttpMessagesAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ab, die gelöschte Schlüsselinformationen sowie seiner Attribute. Autorisierung: Ist der Schlüssel/Get-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsNextWithHttpMessagesAsync&gt;d__115))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht geheime Schlüssel in den angegebenen Tresor. Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt; GetDeletedSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;&#xA;override this.GetDeletedSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretsWithHttpMessagesAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht geheime Schlüssel in den angegebenen Tresor. Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt; GetDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;&#xA;override this.GetDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;" Usage="keyVaultClient.GetDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetDeletedSecretWithHttpMessagesAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ab, die gelöschte geheimen Informationen sowie seiner Attribute.
            Autorisierung: ist der geheime Schlüssel/Get-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysNextWithHttpMessagesAsync&gt;d__111))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste von Schlüsseln in den angegebenen Tresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten. Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt. Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeysWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeysWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeysWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeysWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeysWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeysWithHttpMessagesAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste von Schlüsseln in den angegebenen Tresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten. Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt. Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsNextWithHttpMessagesAsync&gt;d__110))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt; GetKeyVersionsWithHttpMessagesAsync(string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;&#xA;override this.GetKeyVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;" Usage="keyVaultClient.GetKeyVersionsWithHttpMessagesAsync (vaultBaseUrl, keyName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyVersionsWithHttpMessagesAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; GetKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.GetKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.GetKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetKeyWithHttpMessagesAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des abzurufenden Schlüssels.
            </param>
        <param name="keyVersion">
            Hinzufügen der "Version"-Parameter ruft eine bestimmte Version eines Schlüssels ab.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den öffentlichen Teil eines gespeicherten Schlüssels ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die wichtigsten Get-Vorgang gilt zwar für alle Schlüsseltypen. Wenn es sich bei der angeforderte Schlüssel symmetrisch ist, wird keine Schlüsselmaterial in der Antwort freigegeben.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;string&gt;&gt; GetPendingCertificateSigningRequestWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;&#xA;override this.GetPendingCertificateSigningRequestWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;string&gt;&gt;" Usage="keyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetPendingCertificateSigningRequestWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetPendingCertificateSigningRequestWithHttpMessagesAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net
            </param>
        <param name="certificateName">
            Der Name des Zertifikats
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den ausstehenden CSR Anforderungsantwort ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsNextWithHttpMessagesAsync&gt;d__121))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt; GetSasDefinitionsWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;&#xA;override this.GetSasDefinitionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionsWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionsWithHttpMessagesAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; GetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.GetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.GetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSasDefinitionWithHttpMessagesAsync&gt;d__107))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über eine SAS-Definition für das angegebene Speicherkonto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsNextWithHttpMessagesAsync&gt;d__113))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Auflisten geheimer Schlüssel in einer angegebenen Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt. Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretsWithHttpMessagesAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Auflisten geheimer Schlüssel in einer angegebenen Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt. Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsNextWithHttpMessagesAsync&gt;d__114))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen des angegebenen geheimen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden. Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt. Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync (string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt; GetSecretVersionsWithHttpMessagesAsync(string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;&#xA;override this.GetSecretVersionsWithHttpMessagesAsync : string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;" Usage="keyVaultClient.GetSecretVersionsWithHttpMessagesAsync (vaultBaseUrl, secretName, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretVersionsWithHttpMessagesAsync(System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretVersionsWithHttpMessagesAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen des angegebenen geheimen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden. Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt. Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; GetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.GetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.GetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetSecretWithHttpMessagesAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="secretVersion">
            die Version des geheimen Schlüssels.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erhalten Sie einen angegebenen Schlüssel aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die GET-Vorgang gilt zwar für alle geheimen Schlüssel in Azure Key Vault gespeichert.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsNextWithHttpMessagesAsync&gt;d__120))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync (string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt; GetStorageAccountsWithHttpMessagesAsync(string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;&#xA;override this.GetStorageAccountsWithHttpMessagesAsync : string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;" Usage="keyVaultClient.GetStorageAccountsWithHttpMessagesAsync (vaultBaseUrl, maxresults, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountsWithHttpMessagesAsync(System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountsWithHttpMessagesAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; GetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.GetStorageAccountWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.GetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.GetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;GetStorageAccountWithHttpMessagesAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über ein angegebenes Speicherkonto ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; ImportCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.ImportCertificateWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.ImportCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportCertificateWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportCertificateWithHttpMessagesAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="base64EncodedCertificate">
            Base64-codierte Darstellung des Objekts Zertifikat zu importieren. Dieses Zertifikat muss den privaten Schlüssel enthalten.
            </param>
        <param name="password">
            Wenn der private Schlüssel im base64EncodedCertificate verschlüsselt ist, können Sie das Kennwort für die Verschlüsselung verwendete.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird ein Zertifikat in einem angegebenen schlüsseltresor importiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Importiert ein vorhandenes gültiges Zertifikat ist, einen privaten Schlüssel enthält, in Azure Key Vault. Das Zertifikat importiert werden sollen, kann im PFX oder PEM-Format sein. Wenn das Zertifikat im PEM-Format ist muss die PEM-Datei enthalten, den Schlüssel als auch X509 Zertifikate.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; ImportKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.ImportKeyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.ImportKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.ImportKeyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;ImportKeyWithHttpMessagesAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name für den importierten Schlüssel.
            </param>
        <param name="key">
            Das Json Web key
            </param>
        <param name="hsm">
            Ob als Hardwareschlüssel (HSM) oder Softwareschlüssel zu importieren.
            </param>
        <param name="keyAttributes">
            Die schlüsselverwaltung-Attribute.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Importiert einen extern erstellten Schlüssel, speichert ihn und gibt Schlüsselparameter und Attribute an den Client.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Importieren kann verwendet werden, um jedes Schlüsseltyps in Azure Key Vault zu importieren. Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.KeyVault.IKeyVaultClient.LongRunningOperationRetryTimeout</InterfaceMember>
        <InterfaceMember>P:Microsoft.Rest.Azure.IAzureClient.LongRunningOperationRetryTimeout</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="MergeCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; MergeCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.MergeCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.MergeCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.MergeCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;MergeCertificateWithHttpMessagesAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="x509Certificates">
            Das Zertifikat oder der Zertifikatskette zum Zusammenführen.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang MergeCertificate führt das Zusammenführen von einem Zertifikat oder der Zertifikatkette mit einem Schlüsselpaar, die zurzeit in den Dienst verfügbar.
            Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedCertificateWithHttpMessagesAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht das angegebene Zertifikat gelöschte.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang PurgeDeletedCertificate führt eine Löschung des angegebenen Zertifikats, ohne Möglichkeit zur Wiederherstellung. Der Vorgang ist nicht verfügbar, wenn die Wiederherstellung Ebene keine "Purgeable" angibt.
            Erfordert die explizite erteilen der Berechtigung "löschen".
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedKeyWithHttpMessagesAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht den angegebenen Schlüssel. d. h. löscht den Schlüssel. Autorisierung: Ist der Schlüssel/löschen-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse&gt; PurgeDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;&#xA;override this.PurgeDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;" Usage="keyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.PurgeDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;PurgeDeletedSecretWithHttpMessagesAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht den angegebenen Schlüssel. AKA löscht den geheimen Schlüssel ein.
            Autorisierung: ist der geheime Schlüssel/löschen-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; RecoverDeletedCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.RecoverDeletedCertificateWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedCertificateWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedCertificateWithHttpMessagesAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des gelöschten Zertifikats
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird das gelöschte Zertifikat an die aktuelle Version unter Zertifikatinhaber wiederhergestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die RecoverDeletedCertificate werden die Umkehrung der Löschvorgang durchgeführt. Der Vorgang gilt in Tresoren, die für die Soft-Delete aktiviert und während das beibehaltungsintervall (verfügbar in der gelöschten Zertifikats Attribute) ausgegeben werden muss.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RecoverDeletedKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RecoverDeletedKeyWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedKeyWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedKeyWithHttpMessagesAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des gelöschten Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird die gelöschten Schlüssel wieder mit ihrer aktuellen Version unter/Keys wiederhergestellt.
            Autorisierung: Ist der Schlüssel/Recover-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RecoverDeletedSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RecoverDeletedSecretWithHttpMessagesAsync : string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RecoverDeletedSecretWithHttpMessagesAsync(System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RecoverDeletedSecretWithHttpMessagesAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des gelöschten geheimen Schlüssels
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird die gelöschte geheimen wieder mit ihrer aktuellen Version unter "/ Secrets" wiederhergestellt.
            Autorisierung: ist der geheime Schlüssel/Recover-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string keyName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; RegenerateStorageAccountKeyWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string keyName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.RegenerateStorageAccountKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, keyName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RegenerateStorageAccountKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RegenerateStorageAccountKeyWithHttpMessagesAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="keyName">
            Name des Speicherkontos Schlüssel.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert die angegebenen Schlüsselwert für das angegebene Speicherkonto neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync (string vaultBaseUrl, byte[] keyBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; RestoreKeyWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] keyBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.RestoreKeyWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.RestoreKeyWithHttpMessagesAsync (vaultBaseUrl, keyBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreKeyWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreKeyWithHttpMessagesAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyBundleBackup">
            Der Blob-Sicherungsdatei eine wichtige Paket zugeordnet.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Importiert einen zuvor gesicherten Schlüssel in Azure Key Vault, den Schlüssel, der den Schlüsselbezeichner, Attribute und Zugriffssteuerungsrichtlinien wiederhergestellt. Der Wiederherstellungsvorgang kann verwendet werden, um einen zuvor gesicherten Schlüssel zu importieren. Einzelne Versionen eines Schlüssels können nicht wiederhergestellt werden. Der Schlüssel wird in seiner Gesamtheit mit demselben Schlüsselnamen wiederhergestellt, wie er hatte, als er gesichert wurde. Wenn Sie nicht den Namen des Schlüssels im zielschlüsseltresor verfügbar ist, wird der RESTORE-Vorgang abgelehnt. Während der Schlüsselname während der Wiederherstellung beibehalten wird, ändert die endgültige Schlüsselbezeichner, wenn der Schlüssel in einem anderen Tresor wiederhergestellt wird. Wiederherstellen werden alle Versionen wiederherstellen und erhält die Versionsbezeichner. Der RESTORE-Vorgang unterliegt sicherheitseinschränkungen: das Ziel Key Vault muss wie Key Vault Benutzer RESTORE-Berechtigung im zielschlüsseltresor nicht über die Quelle muss durch den gleichen Microsoft Azure-Abonnement besitzen.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync (string vaultBaseUrl, byte[] secretBundleBackup, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; RestoreSecretWithHttpMessagesAsync(string vaultBaseUrl, unsigned int8[] secretBundleBackup, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.RestoreSecretWithHttpMessagesAsync : string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.RestoreSecretWithHttpMessagesAsync (vaultBaseUrl, secretBundleBackup, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.RestoreSecretWithHttpMessagesAsync(System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;RestoreSecretWithHttpMessagesAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretBundleBackup">
            Der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her. Autorisierung: ist der geheime Schlüssel/Restore-Berechtigung erforderlich.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.KeyVault.KeyVaultClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
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
    <Member MemberName="SetCertificateContactsWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync (string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt; SetCertificateContactsWithHttpMessagesAsync(string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;&#xA;override this.SetCertificateContactsWithHttpMessagesAsync : string * Microsoft.Azure.KeyVault.Models.Contacts * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;" Usage="keyVaultClient.SetCertificateContactsWithHttpMessagesAsync (vaultBaseUrl, contacts, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateContactsWithHttpMessagesAsync(System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateContactsWithHttpMessagesAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="contacts">
            Die Kontakte für das Zertifikat des Key Vault.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest. Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; SetCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.SetCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.SetCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetCertificateIssuerWithHttpMessagesAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="provider">
            Der Aussteller-Anbieter.
            </param>
        <param name="credentials">
            Die Anmeldeinformationen für den Aussteller verwendet werden soll.
            </param>
        <param name="organizationDetails">
            Details der Organisation wie an den Aussteller angegeben.
            </param>
        <param name="attributes">
            Attribute des Ausstellers-Objekts.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den angegebenen Zertifikataussteller fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang SetCertificateIssuer fügt hinzu oder aktualisiert den Aussteller des angegebenen Zertifikats.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; SetSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.SetSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.SetSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSasDefinitionWithHttpMessagesAsync&gt;d__108))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="parameters">
            SAS-Definition Erstellung Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="sasDefinitionAttributes">
            Die Attribute der SAS-Definition.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine neue SAS-Definition für das angegebene Speicherkonto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; SetSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.SetSecretWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.SetSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetSecretWithHttpMessagesAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="value">
            Der Wert des geheimen Schlüssels.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="contentType">
            Typ des Werts für den geheimen z. B. eines Kennworts.
            </param>
        <param name="secretAttributes">
            Die Attribute für den geheimen Management.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt einen geheimen Schlüssel in einer angegebenen schlüsseltresor fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der SET-Vorgang hinzugefügt der Azure-Schlüsseltresor einen geheimer Schlüssel. Wenn der benannte geheime Schlüssel bereits vorhanden ist, erstellt Azure-Schlüsseltresor eine neue Version des geheimen Schlüssels.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; SetStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.SetStorageAccountWithHttpMessagesAsync : string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.SetStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SetStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SetStorageAccountWithHttpMessagesAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="resourceId">
            Ressourcen-Id des Speicher-Konto.
            </param>
        <param name="activeKeyName">
            Aktuelle aktive Key Name des Speicherkontos.
            </param>
        <param name="autoRegenerateKey">
            Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.
            </param>
        <param name="regenerationPeriod">
            Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.
            </param>
        <param name="storageAccountAttributes">
            Die Attribute des Speicherkontos.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein neues Speicherkonto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="SignWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; SignWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.SignWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.SignWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.SignWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;SignWithHttpMessagesAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Die ID des Signieren/überprüfen. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm. Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die Anmelde-Vorgang gilt zwar für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da dieser Vorgang den privaten Teil des Schlüssels verwendet.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; UnwrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.UnwrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.UnwrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UnwrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UnwrapKeyWithHttpMessagesAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel, der ursprünglich für diesen Schlüssel wrapping verwendet wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die UNWRAP-Vorgang unterstützt die Entschlüsselung eines symmetrischen Schlüssels mit dem Zielschlüssel für die Schlüsselverschlüsselung. Dieser Vorgang ist die Umkehrung des WRAP-Vorgangs. Der UNWRAP-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync (string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt; UpdateCertificateIssuerWithHttpMessagesAsync(string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;&#xA;override this.UpdateCertificateIssuerWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync (vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateIssuerWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateIssuerWithHttpMessagesAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="provider">
            Der Aussteller-Anbieter.
            </param>
        <param name="credentials">
            Die Anmeldeinformationen für den Aussteller verwendet werden soll.
            </param>
        <param name="organizationDetails">
            Details der Organisation wie an den Aussteller angegeben.
            </param>
        <param name="attributes">
            Attribute des Ausstellers-Objekts.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert den Aussteller des angegebenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UpdateCertificateIssuer-Vorgang führt ein Update für das angegebene Zertifikat Aussteller-Entität.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt; UpdateCertificateOperationWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, bool cancellationRequested, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;&#xA;override this.UpdateCertificateOperationWithHttpMessagesAsync : string * string * bool * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;" Usage="keyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync (vaultBaseUrl, certificateName, cancellationRequested, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateOperationWithHttpMessagesAsync(System.String,System.String,System.Boolean,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateOperationWithHttpMessagesAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationRequested">
            Gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert einen Zertifikat-Vorgang. Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt; UpdateCertificatePolicyWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;&#xA;override this.UpdateCertificatePolicyWithHttpMessagesAsync : string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;" Usage="keyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificatePolicy, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificatePolicyWithHttpMessagesAsync(System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificatePolicyWithHttpMessagesAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in den angegebenen Tresor.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Richtlinie für ein Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Festzulegen Sie angegebene Member in der Zertifikatrichtlinie. Belassen Sie andere als Null.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync (string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt; UpdateCertificateWithHttpMessagesAsync(string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;&#xA;override this.UpdateCertificateWithHttpMessagesAsync : string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;" Usage="keyVaultClient.UpdateCertificateWithHttpMessagesAsync (vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateCertificateWithHttpMessagesAsync(System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateCertificateWithHttpMessagesAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats im angegebenen schlüsseltresor.
            </param>
        <param name="certificateVersion">
            Die Version des Zertifikats.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attribute, die dem angegebenen Zertifikat zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UpdateCertificate-Vorgang gilt das Update für das angegebene Zertifikat; Beachten Sie, dass die einzigen Elemente, die aktualisiert wird das Zertifikat Attribute sind.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt; UpdateKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;&#xA;override this.UpdateKeyWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;" Usage="keyVaultClient.UpdateKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateKeyWithHttpMessagesAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name der zu aktualisierende Schlüssel.
            </param>
        <param name="keyVersion">
            Die Version des Schlüssels zu aktualisieren.
            </param>
        <param name="keyOps">
            JSON Web Key-Vorgänge. Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die Änderungen am Update Schlüsselvorgang angegebene Attribute eines gespeicherten Schlüssels und können auf alle Schlüsseltypen und Schlüssel in Azure Key Vault gespeicherten Version angewendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Um diesen Vorgang auszuführen, muss der Schlüssel bereits im Schlüsseltresor vorhanden sein. Hinweis: Das kryptografische Material eines Schlüssels selbst kann nicht geändert werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt; UpdateSasDefinitionWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;&#xA;override this.UpdateSasDefinitionWithHttpMessagesAsync : string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;" Usage="keyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSasDefinitionWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSasDefinitionWithHttpMessagesAsync&gt;d__109))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="parameters">
            SAS-definitionsaktualisierung Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="sasDefinitionAttributes">
            Die Attribute der SAS-Definition.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attribute der bestimmten SAS-Definition zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync (string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt; UpdateSecretWithHttpMessagesAsync(string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;&#xA;override this.UpdateSecretWithHttpMessagesAsync : string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;" Usage="keyVaultClient.UpdateSecretWithHttpMessagesAsync (vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateSecretWithHttpMessagesAsync(System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateSecretWithHttpMessagesAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="secretVersion">
            die Version des geheimen Schlüssels.
            </param>
        <param name="contentType">
            Typ des Werts für den geheimen z. B. eines Kennworts.
            </param>
        <param name="secretAttributes">
            Die Attribute für den geheimen Management.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Attribute, die mit einem angegebenen Schlüssel in einem angegebenen Schlüssel Tresor verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UPDATE-Vorgang ändert angegebene Attribute einer vorhandenen gespeicherten, geheimen Schlüssels. Attribute, die nicht in der Anforderung angegeben werden bleiben unverändert. Der Wert eines geheimen Schlüssels selbst kann nicht geändert werden.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync (string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt; UpdateStorageAccountWithHttpMessagesAsync(string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;&#xA;override this.UpdateStorageAccountWithHttpMessagesAsync : string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;" Usage="keyVaultClient.UpdateStorageAccountWithHttpMessagesAsync (vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.UpdateStorageAccountWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;UpdateStorageAccountWithHttpMessagesAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="activeKeyName">
            Der aktuellen aktiven Schlüssel speicherkontoname.
            </param>
        <param name="autoRegenerateKey">
            Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.
            </param>
        <param name="regenerationPeriod">
            Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.
            </param>
        <param name="storageAccountAttributes">
            Die Attribute des Speicherkontos.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attributen, die das angegebene Speicherkonto zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="VerifyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt; VerifyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;&#xA;override this.VerifyWithHttpMessagesAsync : string * string * string * string * byte[] * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;" Usage="keyVaultClient.VerifyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.VerifyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;VerifyWithHttpMessagesAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Der Algorithmus Signieren/überprüfen. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm. Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"
            </param>
        <param name="digest">
            Den Hashwert, der zum Signieren verwendet wird.
            </param>
        <param name="signature">
            Die zu überprüfende Signatur.
            </param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft eine Signatur, die mithilfe eines angegebenen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die VERIFY-Vorgang gilt zwar für symmetrische Schlüssel in Azure Key Vault gespeichert. Überprüfen Sie, ob ist nicht unbedingt erforderlich für asymmetrische Schlüssel im Azure-Schlüsseltresor gespeichert sind, da die signaturüberprüfung kann mit dem öffentlichen Teil des Schlüssels ausgeführt werden, aber dieser Vorgang wird als Annehmlichkeit unterstützt, für den Aufrufer, die nur einen Schlüssel-Verweis und nicht die öffentliche Teil des Schlüssels.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync (string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt; WrapKeyWithHttpMessagesAsync(string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;&#xA;override this.WrapKeyWithHttpMessagesAsync : string * string * string * string * byte[] * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;" Usage="keyVaultClient.WrapKeyWithHttpMessagesAsync (vaultBaseUrl, keyName, keyVersion, algorithm, value, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.KeyVault.IKeyVaultClient.WrapKeyWithHttpMessagesAsync(System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClient/&lt;WrapKeyWithHttpMessagesAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="customHeaders">
            Header, die hinzugefügt werden auf Anforderung.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Umschließt einen symmetrischen Schlüssel mithilfe eines angegebenen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der WRAP-Vorgang unterstützt die Verschlüsselung eines symmetrischen Schlüssels mit einem schlüsselverschlüsselungsschlüssel, der zuvor in einem Azure-Schlüsseltresor gespeichert wurde. Der WRAP-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mit dem öffentlichen Teil des Schlüssels ausgeführt werden kann. Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.
            </remarks>
        <exception cref="T:Microsoft.Azure.KeyVault.Models.KeyVaultErrorException">
            Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <exception cref="T:System.ArgumentNullException">
            Wird ausgelöst, wenn ein erforderlicher Parameter null ist.
            </exception>
        <return>
            Ein Response-Objekt, das mit dem Antworttext und Antwortheadern.
            </return>
      </Docs>
    </Member>
  </Members>
</Type>