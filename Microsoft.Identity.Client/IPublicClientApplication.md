<Type Name="IPublicClientApplication" FullName="Microsoft.Identity.Client.IPublicClientApplication">
  <TypeSignature Language="C#" Value="public interface IPublicClientApplication : Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPublicClientApplication implements class Microsoft.Identity.Client.IClientApplicationBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.IPublicClientApplication" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPublicClientApplication&#xA;Implements IClientApplicationBase" />
  <TypeSignature Language="F#" Value="type IPublicClientApplication = interface&#xA;    interface IClientApplicationBase" />
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
            Die Komponente für systemeigene Anwendungen (Desktop/UWP/iOS/Android) verwendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String)) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync scopes" />
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
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, parent)" />
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
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint)" />
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
        <Parameter Name="loginHint" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="extraScopesToConsent">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="extraScopesToConsent">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, Microsoft.Identity.Client.IUser user, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, class Microsoft.Identity.Client.IUser user, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},Microsoft.Identity.Client.IUser,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), user As IUser, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * Microsoft.Identity.Client.IUser * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, user, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
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
        <Parameter Name="user" Type="Microsoft.Identity.Client.IUser" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="user">User-Objekt, um denselben Benutzer authentifiziert werden, in der Webbenutzeroberfläche zu erzwingen.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="extraScopesToConsent">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync (System.Collections.Generic.IEnumerable&lt;string&gt; scopes, string loginHint, Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, System.Collections.Generic.IEnumerable&lt;string&gt; extraScopesToConsent, string authority, Microsoft.Identity.Client.UIParent parent);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Identity.Client.AuthenticationResult&gt; AcquireTokenAsync(class System.Collections.Generic.IEnumerable`1&lt;string&gt; scopes, string loginHint, valuetype Microsoft.Identity.Client.UIBehavior behavior, string extraQueryParameters, class System.Collections.Generic.IEnumerable`1&lt;string&gt; extraScopesToConsent, string authority, class Microsoft.Identity.Client.UIParent parent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Identity.Client.IPublicClientApplication.AcquireTokenAsync(System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIBehavior,System.String,System.Collections.Generic.IEnumerable{System.String},System.String,Microsoft.Identity.Client.UIParent)" />
      <MemberSignature Language="VB.NET" Value="Public Function AcquireTokenAsync (scopes As IEnumerable(Of String), loginHint As String, behavior As UIBehavior, extraQueryParameters As String, extraScopesToConsent As IEnumerable(Of String), authority As String, parent As UIParent) As Task(Of AuthenticationResult)" />
      <MemberSignature Language="F#" Value="abstract member AcquireTokenAsync : seq&lt;string&gt; * string * Microsoft.Identity.Client.UIBehavior * string * seq&lt;string&gt; * string * Microsoft.Identity.Client.UIParent -&gt; System.Threading.Tasks.Task&lt;Microsoft.Identity.Client.AuthenticationResult&gt;" Usage="iPublicClientApplication.AcquireTokenAsync (scopes, loginHint, behavior, extraQueryParameters, extraScopesToConsent, authority, parent)" />
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
        <Parameter Name="loginHint" Type="System.String" />
        <Parameter Name="behavior" Type="Microsoft.Identity.Client.UIBehavior" />
        <Parameter Name="extraQueryParameters" Type="System.String" />
        <Parameter Name="extraScopesToConsent" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="authority" Type="System.String" />
        <Parameter Name="parent" Type="Microsoft.Identity.Client.UIParent" />
      </Parameters>
      <Docs>
        <param name="scopes">Array von Bereichen, die für die Ressource angefordert</param>
        <param name="loginHint">Der Bezeichner des Benutzers. Im Allgemeinen einen UPN.</param>
        <param name="behavior">Steuern des Verhaltens des UI-Enumeration.</param>
        <param name="extraQueryParameters">Dieser Parameter wird unverändert an die Abfragezeichenfolge in der HTTP-Authentifizierung-Anforderung an die Zertifizierungsstelle angefügt. Der Parameter kann null sein.</param>
        <param name="extraScopesToConsent">Ein Array von Bereichen, die für die ein Entwickler die Zustimmung im Vorfeld anfordern kann.</param>
        <param name="authority">Spezifische Stelle, die für die das Token angefordert wird. Übergeben einen anderen Wert als die konfigurierte ändert nicht den konfigurierten Wert</param>
        <param name="parent">Objekt enthält Verweis auf das übergeordnete Fenster/Aktivität. Nur erforderlich für Xamarin.Android.</param>
        <summary>
            Interaktive Anforderung zum Abrufen von Token. 
            </summary>
        <returns>Das Ergebnis der Authentifizierung mit Token des Benutzers</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>