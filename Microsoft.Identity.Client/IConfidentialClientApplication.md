<Type Name="IConfidentialClientApplication" FullName="Microsoft.Identity.Client.IConfidentialClientApplication">
  <TypeSignature Language="C#" Value="public interface IConfidentialClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IConfidentialClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IConfidentialClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IConfidentialClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IConfidentialClientApplication = interface&#xA;    interface IClientApplicationBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Identity.Client.IClientApplicationBase</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Komponente für vertrauliche Clientanwendungen wie Web Apps /-API verwendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenByAuthorizationCodeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync (string authorizationCode, System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenByAuthorizationCodeAsync(string authorizationCode, class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync(System.String,System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenByAuthorizationCodeAsync (authorizationCode As String, scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenByAuthorizationCodeAsync : string * seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenByAuthorizationCodeAsync (authorizationCode, scopes)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authorizationCode" Type="System.String" />
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="authorizationCode">Der Autorisierungscode vom autorisierungsendpunkt Dienst empfangen.</param>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <summary>
            Ruft den Sicherheitstoken von der Zertifizierungsstelle mithilfe des Autorisierungscodes zuvor empfangen.
            Diese Methode ist nicht Tokencache nachschlagen, sondern speichert das Ergebnis, damit er gesucht werden kann mit anderen Methoden wie z. B. <see cref="M:Microsoft.Identity.Client.IClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />.
            </summary>
        <returns>Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync scopes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <summary>
            Ruft die Token vom Dienst für den vertraulichen Client ab. Diese Methode versucht, gültige Zugriffstoken im Cache nachzuschlagen.
            </summary>
        <returns>Authentifizierungsergebnis anwendungstoken für die angeforderten Bereiche mit</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenForClientAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenForClientAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenForClientAsync(System.Collections.Generic.IEnumerable{System.String},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenForClientAsync (scopes As IEnumerable(Of String), forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenForClientAsync : seq&lt;string&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenForClientAsync (scopes, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="forceRefresh">Bei "true", API ignoriert das Zugriffstoken im Cache und versucht, neue Clientanmeldeinformationen mit Zugriffstoken zu erhalten</param>
        <summary>
            Ruft die Token vom Dienst für den vertraulichen Client ab. Diese Methode versucht, gültige Zugriffstoken im Cache nachzuschlagen.
            </summary>
        <returns>Authentifizierungsergebnis anwendungstoken für die angeforderten Bereiche mit</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="userAssertion">In der Instanz von UserAssertion enthält Benutzer werden token.</param>
        <summary>
            Ruft mithilfe der On-Behalf-Of-Flow-token.
            </summary>
        <returns>Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenOnBehalfOfAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UserAssertion userAssertion, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenOnBehalfOfAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UserAssertion userAssertion, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.AcquireTokenOnBehalfOfAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UserAssertion,System.String)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenOnBehalfOfAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UserAssertion * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iConfidentialClientApplication.AcquireTokenOnBehalfOfAsync (scopes, userAssertion, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="userAssertion" Type="Microsoft.Identity.Client.UserAssertion" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="userAssertion">In der Instanz von UserAssertion enthält Benutzer werden token.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <summary>
            Ruft mithilfe der On-Behalf-Of-Flow-token.
            </summary>
        <returns>Token des Benutzers für die angeforderten Bereiche mit Authentifizierungsergebnis</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), loginHint As String, extraQueryParameters As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, loginHint, extraQueryParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.
            </summary>
        <returns>URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthorizationRequestUrlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Uri&gt; GetAuthorizationRequestUrlAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Uri&gt; GetAuthorizationRequestUrlAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string redirectUri, string loginHint, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IConfidentialClientApplication.GetAuthorizationRequestUrlAsync(System.Collections.Generic.IEnumerable{System.String},System.String,System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthorizationRequestUrlAsync (scopes As IEnumerable(Of String), redirectUri As String, loginHint As String, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of Uri)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthorizationRequestUrlAsync : seq&lt;string&gt; * string * string * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Uri&gt;" Usage="iConfidentialClientApplication.GetAuthorizationRequestUrlAsync (scopes, redirectUri, loginHint, extraQueryParameters, extraScopesToConsent, authority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Uri&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="redirectUri">Beheben Sie damit wieder beim Empfang einer Antwort von der Zertifizierungsstelle.</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="extraScopesToConsent">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <summary>
            URL der Authorize-Endpunkt, einschließlich der Abfrageparameter ab.
            </summary>
        <returns>URL des Authorize-Endpunkt, einschließlich der Abfrageparameter.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>