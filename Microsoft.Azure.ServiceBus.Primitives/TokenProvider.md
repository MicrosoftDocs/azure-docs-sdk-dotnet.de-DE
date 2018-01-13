<Type Name="TokenProvider" FullName="Microsoft.Azure.ServiceBus.Primitives.TokenProvider">
  <TypeSignature Language="C#" Value="public abstract class TokenProvider : Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit TokenProvider extends System.Object implements class Microsoft.Azure.ServiceBus.Primitives.ITokenProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class TokenProvider&#xA;Implements ITokenProvider" />
  <TypeSignature Language="F#" Value="type TokenProvider = class&#xA;    interface ITokenProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.ServiceBus.Primitives.ITokenProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Dieser abstrakten Basisklasse kann erweitert werden, um zusätzliche Tokenanbieter zu implementieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected TokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate clientAssertionCertificate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientAssertionCertificate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientAssertionCertificate" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientAssertionCertificate" />
      </Parameters>
      <Docs>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientAssertionCertificate">Die zertifikatsanmeldeinformationen für den Client-Assertion.</param>
        <summary>Erstellt eine Azure Active Directory-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, class Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential clientCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
      </Parameters>
      <Docs>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientCredential">Die app-Anmeldeinformationen.</param>
        <summary>Erstellt eine Azure Active Directory-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAadTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider (Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, Uri redirectUri, Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateAadTokenProvider(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext authContext, string clientId, class System.Uri redirectUri, class Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters platformParameters, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier userIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.Uri,Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters,Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier)" />
      <MemberSignature Language="F#" Value="static member CreateAadTokenProvider : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * Uri * Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters * Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateAadTokenProvider (authContext, clientId, redirectUri, platformParameters, userIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="authContext" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="redirectUri" Type="System.Uri" />
        <Parameter Name="platformParameters" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.IPlatformParameters" />
        <Parameter Name="userIdentifier" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserIdentifier" />
      </Parameters>
      <Docs>
        <param name="authContext">AuthenticationContext für AAD.</param>
        <param name="clientId">ClientId für AAD.</param>
        <param name="redirectUri">Die RedirectUri auf Client-App.</param>
        <param name="platformParameters">Platform-Parameter</param>
        <param name="userIdentifier">Benutzer-ID</param>
        <summary>Erstellt eine Azure Active Directory-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateManagedServiceIdentityTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateManagedServiceIdentityTokenProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateManagedServiceIdentityTokenProvider() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateManagedServiceIdentityTokenProvider" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateManagedServiceIdentityTokenProvider () As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateManagedServiceIdentityTokenProvider : unit -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateManagedServiceIdentityTokenProvider " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>Erstellt Azure verwaltet Dienstidentität-Tokenanbieter.</summary>
        <returns>Die <see cref="T:Microsoft.Azure.ServiceBus.Primitives.TokenProvider" /> für die Rückgabe von Json-webtoken.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string sharedAccessSignature);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string sharedAccessSignature) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (sharedAccessSignature As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider sharedAccessSignature" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sharedAccessSignature" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sharedAccessSignature">Die SAS</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf einer SharedAccessSignature.
            </summary>
        <returns>Einen TokenProvider dar, die mit der freigegebenen zugriffssignatur initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</param>
        <param name="sharedAccessKey">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.
            </summary>
        <returns>Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,Microsoft.Azure.ServiceBus.Primitives.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * Microsoft.Azure.ServiceBus.Primitives.TokenScope -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.ServiceBus.Primitives.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</param>
        <param name="sharedAccessKey">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</param>
        <param name="tokenScope">Die TokenScope Token anfordern.</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.
            </summary>
        <returns>Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateSharedAccessSignatureTokenProvider (keyName As String, sharedAccessKey As String, tokenTimeToLive As TimeSpan) As TokenProvider" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</param>
        <param name="sharedAccessKey">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</param>
        <param name="tokenTimeToLive">Die token Zeit Gültigkeitsdauer</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.
            </summary>
        <returns>Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateSharedAccessSignatureTokenProvider">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider (string keyName, string sharedAccessKey, TimeSpan tokenTimeToLive, Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.ServiceBus.Primitives.TokenProvider CreateSharedAccessSignatureTokenProvider(string keyName, string sharedAccessKey, valuetype System.TimeSpan tokenTimeToLive, valuetype Microsoft.Azure.ServiceBus.Primitives.TokenScope tokenScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider(System.String,System.String,System.TimeSpan,Microsoft.Azure.ServiceBus.Primitives.TokenScope)" />
      <MemberSignature Language="F#" Value="static member CreateSharedAccessSignatureTokenProvider : string * string * TimeSpan * Microsoft.Azure.ServiceBus.Primitives.TokenScope -&gt; Microsoft.Azure.ServiceBus.Primitives.TokenProvider" Usage="Microsoft.Azure.ServiceBus.Primitives.TokenProvider.CreateSharedAccessSignatureTokenProvider (keyName, sharedAccessKey, tokenTimeToLive, tokenScope)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.ServiceBus.Primitives.TokenProvider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="sharedAccessKey" Type="System.String" />
        <Parameter Name="tokenTimeToLive" Type="System.TimeSpan" />
        <Parameter Name="tokenScope" Type="Microsoft.Azure.ServiceBus.Primitives.TokenScope" />
      </Parameters>
      <Docs>
        <param name="keyName">Der Schlüsselname des entsprechenden SharedAccessKeyAuthorizationRule.</param>
        <param name="sharedAccessKey">Die SharedAccessKeyAuthorizationRule zugeordneter Schlüssel</param>
        <param name="tokenTimeToLive">Die token Zeit Gültigkeitsdauer</param>
        <param name="tokenScope">Die TokenScope Token anfordern.</param>
        <summary>
            Erstellen Sie einen TokenProvider dar, die basierend auf den bereitgestellten Schlüsselname und freigegebene Zugriffsschlüssel an.
            </summary>
        <returns>Einen TokenProvider dar, die mit den bereitgestellten RuleId und das Kennwort initialisiert</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTokenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync (string appliesTo, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt; GetTokenAsync(string appliesTo, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.ServiceBus.Primitives.TokenProvider.GetTokenAsync(System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTokenAsync (appliesTo As String, timeout As TimeSpan) As Task(Of SecurityToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTokenAsync : string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;" Usage="tokenProvider.GetTokenAsync (appliesTo, timeout)" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.ServiceBus.Primitives.ITokenProvider.GetTokenAsync(System.String,System.TimeSpan)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.ServiceBus.Primitives.SecurityToken&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appliesTo" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="appliesTo">Der URI, der das Zugriffstoken gilt.</param>
        <param name="timeout">Die Zeitspanne an, die angibt, den Timeoutwert für die Nachricht abruft, die das Sicherheitstoken</param>
        <summary>
            Ruft eine <see cref="T:Microsoft.Azure.ServiceBus.Primitives.SecurityToken" /> für die angegebene Zielgruppe und die Dauer.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>