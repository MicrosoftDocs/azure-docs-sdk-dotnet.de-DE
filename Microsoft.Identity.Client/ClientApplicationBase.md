<Type Name="ClientApplicationBase" FullName="Microsoft.Identity.Client.ClientApplicationBase">
  <TypeSignature Language="C#" Value="public abstract class ClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ClientApplicationBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.ClientApplicationBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ClientApplicationBase" />
  <TypeSignature Language="F#" Value="type ClientApplicationBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
    <Summary>
            Abstrakte Klasse, die allgemeine API-Methoden und Eigenschaften enthält. Diese Klasse wird von der PublicClientApplication und ConfidentialClientApplication erweitert.
            </Summary>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ClientApplicationBase (string clientId, string authority, string redirectUri, bool validateAuthority);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string clientId, string authority, string redirectUri, bool validateAuthority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.#ctor(System.String,System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (clientId As String, authority As String, redirectUri As String, validateAuthority As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Identity.Client.ClientApplicationBase : string * string * string * bool -&gt; Microsoft.Identity.Client.ClientApplicationBase" Usage="new Microsoft.Identity.Client.ClientApplicationBase (clientId, authority, redirectUri, validateAuthority)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.String" />
        <Parameter Name="validateAuthority" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="clientId"></param>
        <param name="authority"></param>
        <param name="redirectUri"></param>
        <param name="validateAuthority"></param>
        <summary />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">Benutzer, die für die das Token angefordert wird. <see cref="T:Microsoft.Identity.Client.IUser" /></param>
        <summary>
            Versucht, das Zugriffstoken aus dem Cache abzurufen. Zugriffstoken wird als Übereinstimmung betrachtet, wenn er mindestens der angeforderten Bereiche enthält.
            Dies bedeutet, dass ein Zugriffstoken mit mehr Gültigkeitsbereiche als angeforderten ebenfalls zurückgegeben werden konnte. Wenn das Zugriffstoken abgelaufen ist oder bald abläuft (innerhalb von 5-Minuten-Fenster), wird Aktualisierungstoken (falls verfügbar), ein neues Zugriffstoken abzurufen, durch einen Netzwerkaufruf verwendet.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenSilentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenSilentAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, string authority, bool forceRefresh) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.AcquireTokenSilentAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenSilentAsync (scopes As IEnumerable(Of String), user As IUser, authority As String, forceRefresh As Boolean) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;&#xA;override this.AcquireTokenSilentAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="clientApplicationBase.AcquireTokenSilentAsync (scopes, user, authority, forceRefresh)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Identity.Client.ClientApplicationBase/&lt;AcquireTokenSilentAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="scopes" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="forceRefresh" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">Benutzer, die für die das Token angefordert wird<see cref="T:Microsoft.Identity.Client.User" /></param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <param name="forceRefresh">Bei "true", API ignoriert das Zugriffstoken im Cache und versuchen zum Abrufen neuer Zugriffstokens mithilfe des aktualisierungstokens, falls verfügbar</param>
        <summary>
            Versucht, das Zugriffstoken aus dem Cache abzurufen. Zugriffstoken wird als Übereinstimmung betrachtet, wenn er mindestens der angeforderten Bereiche enthält.
            Dies bedeutet, dass ein Zugriffstoken mit mehr Gültigkeitsbereiche als angeforderten ebenfalls zurückgegeben werden konnte. Wenn das Zugriffstoken abgelaufen ist oder bald abläuft (innerhalb von 5-Minuten-Fenster), wird Aktualisierungstoken (falls verfügbar), ein neues Zugriffstoken abzurufen, durch einen Netzwerkaufruf verwendet.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authority">
      <MemberSignature Language="C#" Value="public string Authority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Authority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Authority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Authority As String" />
      <MemberSignature Language="F#" Value="member this.Authority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.Authority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <Summary>
            Autorität für die bereitgestellten, durch die Entwickler oder Default-Behörde, die von der Bibliothek verwendet.
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.ClientId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ein Standardwert wird festgelegt werden. Kann vom Entwickler überschrieben werden. Einmal festgelegt, wird Anwendung an den Client-ID gebunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Component">
      <MemberSignature Language="C#" Value="public string Component { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Component" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Component" />
      <MemberSignature Language="VB.NET" Value="Public Property Component As String" />
      <MemberSignature Language="F#" Value="member this.Component : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.Component" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Bezeichner der Komponente verbrauchte MSAL und es dient für Bibliotheken-SDKs, die MSAL nutzen. Dadurch können für Mehrdeutigkeit zwischen MSAL-Nutzung durch die app Vs MSAL Verwendung von Komponentenbibliotheken.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultAuthority">
      <MemberSignature Language="C#" Value="protected const string DefaultAuthority;" />
      <MemberSignature Language="ILAsm" Value=".field family static literal string DefaultAuthority" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberSignature Language="VB.NET" Value="Protected Const DefaultAuthority As String " />
      <MemberSignature Language="F#" Value="val mutable DefaultAuthority : string" Usage="Microsoft.Identity.Client.ClientApplicationBase.DefaultAuthority" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <Summary>
            Standard-Authority für interaktive Aufrufe verwendet.
            </Summary>
      </Docs>
    </Member>
    <Member MemberName="GetUser">
      <MemberSignature Language="C#" Value="public Microsoft.Identity.Client.IUser GetUser (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Identity.Client.IUser GetUser(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.GetUser(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetUser (identifier As String) As IUser" />
      <MemberSignature Language="F#" Value="abstract member GetUser : string -&gt; Microsoft.Identity.Client.IUser&#xA;override this.GetUser : string -&gt; Microsoft.Identity.Client.IUser" Usage="clientApplicationBase.GetUser identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Identity.Client.IUser</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">Benutzer-ID</param>
        <summary>
            Benutzer von Bezeichner von Benutzern verfügbar im Cache abrufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedirectUri">
      <MemberSignature Language="C#" Value="public string RedirectUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedirectUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
      <MemberSignature Language="VB.NET" Value="Public Property RedirectUri As String" />
      <MemberSignature Language="F#" Value="member this.RedirectUri : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.RedirectUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Umleitungs-Uri in das app-registrierungsportal konfiguriert. PublicClientApplication hat den Standardwert Urn: Ietf:wg:oauth:2.0:oob. Diese Standardeinstellung gilt nicht für IOS- und Android, wie die Bibliothek System Webview für die Authentifizierung zu nutzen muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Remove">
      <MemberSignature Language="C#" Value="public void Remove (Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Remove(class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.ClientApplicationBase.Remove(Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Remove (user As IUser)" />
      <MemberSignature Language="F#" Value="abstract member Remove : Microsoft.Identity.Client.IUser -&gt; unit&#xA;override this.Remove : Microsoft.Identity.Client.IUser -&gt; unit" Usage="clientApplicationBase.Remove user" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="user">Instanz des Benutzers, der entfernt werden muss</param>
        <summary>
            Entfernt alle zwischengespeicherte Token für den angegebenen Benutzer.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SliceParameters">
      <MemberSignature Language="C#" Value="public string SliceParameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SliceParameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
      <MemberSignature Language="VB.NET" Value="Public Property SliceParameters As String" />
      <MemberSignature Language="F#" Value="member this.SliceParameters : string with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.SliceParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legt fest oder ruft die benutzerdefinierten Abfrageparameter, die an den STS zu Testzwecken Dogfood gesendet werden können. Dieser Parameter sollte nicht vom Entwickler festgelegt werden, da es negative Auswirkungen auf die Anwendung möglicherweise.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Users">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt; Users { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Identity.Client.IUser&gt; Users" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.Users" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Users As IEnumerable(Of IUser)" />
      <MemberSignature Language="F#" Value="member this.Users : seq&lt;Microsoft.Identity.Client.IUser&gt;" Usage="Microsoft.Identity.Client.ClientApplicationBase.Users" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Identity.Client.IUser&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt zentriertes Benutzeransichten über den Cache, der eine Liste aller verfügbaren Benutzer im Cache für die Anwendung bereitstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateAuthority">
      <MemberSignature Language="C#" Value="public bool ValidateAuthority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ValidateAuthority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidateAuthority As Boolean" />
      <MemberSignature Language="F#" Value="member this.ValidateAuthority : bool with get, set" Usage="Microsoft.Identity.Client.ClientApplicationBase.ValidateAuthority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Identity.Client</AssemblyName>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            / Legt einen Wert, der angibt, ob die Autorität für die Überprüfung auf ON festgelegt ist, oder deaktivieren. Wert ist standardmäßig "true". Es sollte von der Deveopers für B2C-Anwendungen auf "false" festgelegt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>