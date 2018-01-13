<Type Name="AuthenticationContext" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext">
  <TypeSignature Language="C#" Value="public sealed class AuthenticationContext" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit AuthenticationContext extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class AuthenticationContext" />
  <TypeSignature Language="F#" Value="type AuthenticationContext = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Klasse AuthenticationContext ruft Authentifizierungstoken von Azure Active Directory und AD FS-Diensten ab.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authority" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authority">Die Adresse der Autorisierungsstelle, die Token ausstellen.</param>
        <summary>
            Konstruktor, um den Kontext mit der Adresse der Autorisierungsstelle zu erstellen.
            Mithilfe dieses Konstruktors wird zur Validierung der Autorität für die URL in der Standardeinstellung verwandeln, wenn die Überprüfung für die Autorität für die Adresse unterstützt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority">Die Adresse der Autorisierungsstelle, die Token ausstellen.</param>
        <param name="tokenCache">Tokencache verwendet, um die zwischengespeicherte Token für Aufrufe von AcquireToken suchen</param>
        <summary>
            Konstruktor, um den Kontext mit der Adresse der Autorisierungsstelle zu erstellen.
            Mithilfe dieses Konstruktors wird zur Validierung der Autorität für die URL in der Standardeinstellung verwandeln, wenn die Überprüfung für die Autorität für die Adresse unterstützt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authority As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="authority">Die Adresse der Autorisierungsstelle, die Token ausstellen.</param>
        <param name="validateAuthority">Kennzeichen Sie, um die Adresse Überprüfung ON oder OFF zu aktivieren.</param>
        <summary>
            Konstruktor zum Erstellen des Kontexts mit der Adresse der Autorität und dem Flag Adressüberprüfung deaktivieren.
            Verwenden diesen Konstruktor, kann Adressüberprüfung deaktiviert werden. Stellen Sie sicher, dass Sie die Sicherheit Implikation überprüft nicht die Adresse zur Kenntnis genommen haben.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthenticationContext (string authority, bool validateAuthority, Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string authority, bool validateAuthority, class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache tokenCache) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.#ctor(System.String,System.Boolean,Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext : string * bool * Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext (authority, validateAuthority, tokenCache)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
        <Parameter Name="tokenCache" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" />
      </Parameters>
      <Docs>
        <param name="authority">Die Adresse der Autorisierungsstelle, die Token ausstellen.</param>
        <param name="validateAuthority">Kennzeichen Sie, um die Adresse Überprüfung ON oder OFF zu aktivieren.</param>
        <param name="tokenCache">Tokencache verwendet, um die zwischengespeicherte Token für Aufrufe von AcquireToken suchen</param>
        <summary>
            Konstruktor zum Erstellen des Kontexts mit der Adresse der Autorität und dem Flag Adressüberprüfung deaktivieren.
            Verwenden diesen Konstruktor, kann Adressüberprüfung deaktiviert werden. Stellen Sie sicher, dass Sie die Sicherheit Implikation überprüft nicht die Adresse zur Kenntnis genommen haben.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <summary>
            Ruft die Gerätecode von der Zertifizierungsstelle ab.
            </summary>
        <returns>Er enthält Gerätecode, dessen Ablauf Zeit Benutzercode.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync (string resource, string clientId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt; AcquireDeviceCodeAsync(string resource, string clientId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireDeviceCodeAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireDeviceCodeAsync (resource As String, clientId As String, extraQueryParameters As String) As Task(Of DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireDeviceCodeAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;" Usage="authenticationContext.AcquireDeviceCodeAsync (resource, clientId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireDeviceCodeAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            Ruft die Gerätecode von der Zertifizierungsstelle ab.
            </summary>
        <returns>Er enthält Gerätecode, dessen Ablauf Zeit Benutzercode.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientAssertion">Die Client-Assertion für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit. Refresh-Token-Eigenschaft wird für diese Überladung null sein.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCredential">Die Clientanmeldeinformationen für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit. Refresh-Token-Eigenschaft wird für diese Überladung null sein.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCertificate">Das Clientzertifikat für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit. Refresh-Token-Eigenschaft wird für diese Überladung null sein.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientAssertion, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientAssertion">Die Client-Assertion für tokenabruf verwendet werden soll.</param>
        <param name="userAssertion">Die Benutzer-Assertion (Token) für den tokenabruf verwendet.</param>
        <summary>
            Ruft die im Auftrag eines Benutzers ein Zugriffstoken von der Zertifizierungsstelle ab. Es muss bei Verwendung von Token des Benutzers bereits empfangen.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCredential, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCredential">Die Clientanmeldeinformationen für tokenabruf verwendet werden soll.</param>
        <param name="userAssertion">Die Benutzer-Assertion (Token) für den tokenabruf verwendet.</param>
        <summary>
            Ruft die im Auftrag eines Benutzers ein Zugriffstoken von der Zertifizierungsstelle ab. Es muss bei Verwendung von Token des Benutzers bereits empfangen.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientCertificate, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCertificate">Das Clientzertifikat für tokenabruf verwendet werden soll.</param>
        <param name="userAssertion">Die Benutzer-Assertion (Token) für den tokenabruf verwendet.</param>
        <summary>
            Ruft die im Auftrag eines Benutzers ein Zugriffstoken von der Zertifizierungsstelle ab. Es muss bei Verwendung von Token des Benutzers bereits empfangen.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="userAssertion">Die Assertion für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit. Refresh-Token-Eigenschaft wird für diese Überladung null sein.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="parameters">Ein Objekt des Typs PlatformParameters dem zusätzlichen Parameter, die für die Autorisierung verwendet übergeben werden kann.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="parameters">Ein Objekt des Typs PlatformParameters dem zusätzlichen Parameter, die für die Autorisierung verwendet übergeben werden kann.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Bei der Erstellung von DisplayableId, wird dieser Parameter für das Username-Feld in der Form der Authentifizierung Voraufgefüllte verwendet werden. Beachten Sie, dass der Endbenutzer können weiterhin das Benutzernamenfeld bearbeiten und als anderer Benutzer zu authentifizieren.
            Wenn Sie eine solche Änderung mit einer Ausnahme benachrichtigt werden möchten, erstellen Sie UserIdentifier mit RequiredDisplayableId-Typ. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="parameters">Für die interaktive Fluss Anfordern von Autorisierungscode erforderlichen Parameter. Übergeben Sie eine Instanz des PlatformParameters.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Bei der Erstellung von DisplayableId, wird dieser Parameter für das Username-Feld in der Form der Authentifizierung Voraufgefüllte verwendet werden. Beachten Sie, dass der Endbenutzer können weiterhin das Benutzernamenfeld bearbeiten und als anderer Benutzer zu authentifizieren.
            Wenn Sie eine solche Änderung mit einer Ausnahme benachrichtigt werden möchten, erstellen Sie UserIdentifier mit RequiredDisplayableId-Typ. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (resource As String, clientId As String, redirectUri As Uri, parameters As IPlatformParameters, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenAsync (resource, clientId, redirectUri, parameters, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="parameters">Die Instanz von PlatformParameters, die bestimmte Plattform von Argumenten und Informationen enthält.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="claims">Zusätzliche Ansprüche, die für die Authentifizierung erforderlich sind. Aus der AdalClaimChallengeException abgerufen</param>
        <summary>
            Ruft ein Zugriffstoken von der Zertifizierungsstelle im Auftrag eines Benutzers, der die erforderlichen Ansprüche für die Authentifizierung übergeben. Es muss bei Verwendung von Token des Benutzers bereits empfangen.
            </summary>
        <returns>Es enthält Zugriffstoken und das Zugriffstoken des Ablaufzeit.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Die umleitungs-Adresse zum Abrufen von Autorisierungscode verwendet.</param>
        <param name="clientAssertion">Die Client-Assertion für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft die Sicherheitstoken von der Zertifizierungsstelle, die über einen Autorisierungscode bereits empfangene ab.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="clientCredential">Die Anmeldeinformationen für den tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft den Sicherheitstoken von der Zertifizierungsstelle mithilfe des Autorisierungscodes zuvor empfangen.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Die umleitungs-Adresse zum Abrufen von Autorisierungscode verwendet.</param>
        <param name="clientCertificate">Das Clientzertifikat für tokenabruf verwendet werden soll.</param>
        <summary>
            Ruft die Sicherheitstoken von der Zertifizierungsstelle, die über einen Autorisierungscode bereits empfangene ab.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientAssertion, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Die umleitungs-Adresse zum Abrufen von Autorisierungscode verwendet.</param>
        <param name="clientAssertion">Die Client-Assertion für tokenabruf verwendet werden soll.</param>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist. Null, wenn zuvor bereitgestellten AuthorizationCode abrufen kann.</param>
        <summary>
            Ruft die Sicherheitstoken von der Zertifizierungsstelle, die über einen Autorisierungscode bereits empfangene ab.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,System.String)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCredential, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="clientCredential">Die Anmeldeinformationen für den tokenabruf verwendet werden soll.</param>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist. Null, wenn zuvor bereitgestellten AuthorizationCode abrufen kann.</param>
        <summary>
            Ruft die Sicherheitstoken von der Zertifizierungsstelle, die über einen Autorisierungscode bereits empfangene ab.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, string resource) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByAuthorizationCodeAsync(System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, redirectUri As Uri, clientCertificate As IClientAssertionCertificate, resource As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByAuthorizationCodeAsync : string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByAuthorizationCodeAsync (authorizationCode, redirectUri, clientCertificate, resource)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByAuthorizationCodeAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="resource" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="redirectUri">Die umleitungs-Adresse zum Abrufen von Autorisierungscode verwendet.</param>
        <param name="clientCertificate">Das Clientzertifikat für tokenabruf verwendet werden soll.</param>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist. Null, wenn zuvor bereitgestellten AuthorizationCode abrufen kann.</param>
        <summary>
            Ruft die Sicherheitstoken von der Zertifizierungsstelle, die über einen Autorisierungscode bereits empfangene ab.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenByDeviceCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync (Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenByDeviceCodeAsync(class Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult deviceCodeResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenByDeviceCodeAsync(Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenByDeviceCodeAsync : Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenByDeviceCodeAsync deviceCodeResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenByDeviceCodeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceCodeResult" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.DeviceCodeResult" />
      </Parameters>
      <Docs>
        <param name="deviceCodeResult">Das Gerät Code Ergebnis des Aufrufs von AcquireDeviceCodeAsync empfangen.</param>
        <summary>
            Ruft ab die Sicherheitstoken von der Zertifizierungsstelle, die mit einem Gerätecode bereits empfangen.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion clientAssertion, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientAssertion, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientAssertion" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertion" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientAssertion">Die Client-Assertion für tokenabruf verwendet werden soll.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCredential, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCredential">Die Clientanmeldeinformationen für tokenabruf verwendet werden soll.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, class Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate clientCertificate, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientCertificate As IClientAssertionCertificate, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientCertificate, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IClientAssertionCertificate" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientCertificate">Das Clientzertifikat für tokenabruf verwendet werden soll.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync (string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenSilentAsync(string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.AcquireTokenSilentAsync(System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (resource As String, clientId As String, userId As UserIdentifier, parameters As IPlatformParameters) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="member this.AcquireTokenSilentAsync : string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="authenticationContext.AcquireTokenSilentAsync (resource, clientId, userId, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;AcquireTokenSilentAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="parameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <param name="parameters">Die Instanz von PlatformParameters, die bestimmte Plattform von Argumenten und Informationen enthält.</param>
        <summary>
            Ruft die Sicherheitstoken ohne Aufforderung zur Benutzeranmeldeinformationen ab.
            </summary>
        <returns>Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen. Wenn das Token abrufen, ohne die Benutzeranmeldeinformationen nicht möglich ist, löst die Methode AdalException an.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Adresse der Autorisierungsstelle, die Token ausstellen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CorrelationId">
      <MemberSignature Language="C#" Value="public Guid CorrelationId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid CorrelationId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberSignature Language="VB.NET" Value="Public Property CorrelationId As Guid" />
      <MemberSignature Language="F#" Value="member this.CorrelationId : Guid with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.CorrelationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Korrelations-Id, die an den Dienst mit der nächsten Anforderung gesendet werden.
            Korrelations-Id ist für Diagnosezwecke verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtendedLifeTimeEnabled">
      <MemberSignature Language="C#" Value="public bool ExtendedLifeTimeEnabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExtendedLifeTimeEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Property ExtendedLifeTimeEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExtendedLifeTimeEnabled : bool with get, set" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ExtendedLifeTimeEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Das Kennzeichen festgelegt für AAD erweiterte lebensdauerperiode
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.
            </summary>
        <returns>URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (string resource, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(string resource, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userId, string extraQueryParameters, string claims) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.GetAuthorizationRequestUrlAsync(System.String,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (resource As String, clientId As String, redirectUri As Uri, userId As UserIdentifier, extraQueryParameters As String, claims As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="member this.GetAuthorizationRequestUrlAsync : string * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="authenticationContext.GetAuthorizationRequestUrlAsync (resource, clientId, redirectUri, userId, extraQueryParameters, claims)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext/&lt;GetAuthorizationRequestUrlAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="userId" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="claims" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resource">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</param>
        <param name="clientId">Der Bezeichner des Clients, die das Token anfordert.</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="userId">Bezeichner des Benutzertokens ist für angefordert. Dieser Parameter kann <see cref="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />. Alle.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="claims">Zusätzliche Ansprüche, die für die Authentifizierung erforderlich sind. Aus der AdalClaimChallengeException abgerufen. Dieser Parameter kann NULL sein.</param>
        <summary>
            URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.
            </summary>
        <returns>URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenCache">
      <MemberSignature Language="C#" Value="public Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache TokenCache" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TokenCache As TokenCache" />
      <MemberSignature Language="F#" Value="member this.TokenCache : Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.TokenCache" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.IdentityModel.Clients.ActiveDirectory.TokenCache</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Eigenschaft, die ADAL-Tokencache. Abhängig von der Plattform möglicherweise TokenCache eine permanente Standardcache aufweisen oder nicht.
            Bibliothek wird automatisch Token in Standard-TokenCache gespeichert, wenn Sie diese erhalten. Zwischengespeicherte Token werden nur für die Anwendung verfügbar sein, die sie gespeichert.
            Wenn der Cache erhalten bleiben, die darin gespeicherten Token werden die Ausführung der Anwendung Überleben und bei nachfolgenden Ausführungen verfügbar.
            Um das Zwischenspeichern von token zu deaktivieren, legen Sie TokenCache auf null fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab einen Wert, der angibt, ob die Adressüberprüfung auf ON festgelegt ist, oder deaktivieren.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>