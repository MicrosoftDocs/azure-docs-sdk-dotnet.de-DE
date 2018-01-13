<Type Name="AppServiceAuthenticationHandler" FullName="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler">
  <TypeSignature Language="C#" Value="public class AppServiceAuthenticationHandler : Microsoft.Owin.Security.Infrastructure.AuthenticationHandler&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceAuthenticationHandler extends Microsoft.Owin.Security.Infrastructure.AuthenticationHandler`1&lt;class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceAuthenticationHandler&#xA;Inherits AuthenticationHandler(Of AppServiceAuthenticationOptions)" />
  <TypeSignature Language="F#" Value="type AppServiceAuthenticationHandler = class&#xA;    inherit AuthenticationHandler&lt;AppServiceAuthenticationOptions&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Owin.Security.Infrastructure.AuthenticationHandler&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b530-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" /> authentifiziert einen Aufrufer, die bereits mit dem Controller Anmeldung authentifiziert hat.</span><span class="sxs-lookup"><span data-stu-id="2b530-101">The <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" /> authenticates a caller who has already authenticated using the Login controller.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceAuthenticationHandler (Microsoft.Owin.Logging.ILogger logger);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Owin.Logging.ILogger logger) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.#ctor(Microsoft.Owin.Logging.ILogger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (logger As ILogger)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler : Microsoft.Owin.Logging.ILogger -&gt; Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" Usage="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler logger" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="logger" Type="Microsoft.Owin.Logging.ILogger" />
      </Parameters>
      <Docs>
        <param name="logger"><span data-ttu-id="2b530-102">Die <see cref="T:Microsoft.Owin.Logging.ILogger" /> für die Protokollierung verwenden.</span><span class="sxs-lookup"><span data-stu-id="2b530-102">The <see cref="T:Microsoft.Owin.Logging.ILogger" /> to use for logging.</span></span></param>
        <summary>
            <span data-ttu-id="2b530-103">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" /> -Klasse mit der angegebenen <paramref name="logger" />.</span><span class="sxs-lookup"><span data-stu-id="2b530-103">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler" /> class with the given <paramref name="logger" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Owin.Security.AuthenticationTicket Authenticate (Microsoft.Owin.IOwinRequest request, Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Owin.Security.AuthenticationTicket Authenticate(class Microsoft.Owin.IOwinRequest request, class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.Authenticate(Microsoft.Owin.IOwinRequest,Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function Authenticate (request As IOwinRequest, options As AppServiceAuthenticationOptions) As AuthenticationTicket" />
      <MemberSignature Language="F#" Value="abstract member Authenticate : Microsoft.Owin.IOwinRequest * Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions -&gt; Microsoft.Owin.Security.AuthenticationTicket&#xA;override this.Authenticate : Microsoft.Owin.IOwinRequest * Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions -&gt; Microsoft.Owin.Security.AuthenticationTicket" Usage="appServiceAuthenticationHandler.Authenticate (request, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Owin.Security.AuthenticationTicket</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="Microsoft.Owin.IOwinRequest" />
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions" />
      </Parameters>
      <Docs>
        <param name="request">To be added.</param>
        <param name="options">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticateCoreAsync">
      <MemberSignature Language="C#" Value="protected override System.Threading.Tasks.Task&lt;Microsoft.Owin.Security.AuthenticationTicket&gt; AuthenticateCoreAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Owin.Security.AuthenticationTicket&gt; AuthenticateCoreAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.AuthenticateCoreAsync" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function AuthenticateCoreAsync () As Task(Of AuthenticationTicket)" />
      <MemberSignature Language="F#" Value="override this.AuthenticateCoreAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Owin.Security.AuthenticationTicket&gt;" Usage="appServiceAuthenticationHandler.AuthenticateCoreAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Owin.Security.AuthenticationTicket&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationHeaderName">
      <MemberSignature Language="C#" Value="public const string AuthenticationHeaderName;" />
      <MemberSignature Language="ILAsm" Value=".field public static literal string AuthenticationHeaderName" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.AuthenticationHeaderName" />
      <MemberSignature Language="VB.NET" Value="Public Const AuthenticationHeaderName As String " />
      <MemberSignature Language="F#" Value="val mutable AuthenticationHeaderName : string" Usage="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.AuthenticationHeaderName" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAuthenticationTicket">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Owin.Security.AuthenticationTicket CreateAuthenticationTicket (System.Security.Claims.ClaimsIdentity identity);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Owin.Security.AuthenticationTicket CreateAuthenticationTicket(class System.Security.Claims.ClaimsIdentity identity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.CreateAuthenticationTicket(System.Security.Claims.ClaimsIdentity)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateAuthenticationTicket (identity As ClaimsIdentity) As AuthenticationTicket" />
      <MemberSignature Language="F#" Value="abstract member CreateAuthenticationTicket : System.Security.Claims.ClaimsIdentity -&gt; Microsoft.Owin.Security.AuthenticationTicket&#xA;override this.CreateAuthenticationTicket : System.Security.Claims.ClaimsIdentity -&gt; Microsoft.Owin.Security.AuthenticationTicket" Usage="appServiceAuthenticationHandler.CreateAuthenticationTicket identity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Owin.Security.AuthenticationTicket</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identity" Type="System.Security.Claims.ClaimsIdentity" />
      </Parameters>
      <Docs>
        <param name="identity">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateIdentity">
      <MemberSignature Language="C#" Value="protected virtual System.Security.Claims.ClaimsIdentity ValidateIdentity (Microsoft.Owin.IOwinRequest request, Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Security.Claims.ClaimsIdentity ValidateIdentity(class Microsoft.Owin.IOwinRequest request, class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationHandler.ValidateIdentity(Microsoft.Owin.IOwinRequest,Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function ValidateIdentity (request As IOwinRequest, options As AppServiceAuthenticationOptions) As ClaimsIdentity" />
      <MemberSignature Language="F#" Value="abstract member ValidateIdentity : Microsoft.Owin.IOwinRequest * Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions -&gt; System.Security.Claims.ClaimsIdentity&#xA;override this.ValidateIdentity : Microsoft.Owin.IOwinRequest * Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions -&gt; System.Security.Claims.ClaimsIdentity" Usage="appServiceAuthenticationHandler.ValidateIdentity (request, options)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Claims.ClaimsIdentity</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="Microsoft.Owin.IOwinRequest" />
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="2b530-104">Das zu authentifizierende <see cref="T:Microsoft.Owin.IOwinRequest" />.</span><span class="sxs-lookup"><span data-stu-id="2b530-104">The <see cref="T:Microsoft.Owin.IOwinRequest" /> to authenticate.</span></span></param>
        <param name="options"><span data-ttu-id="2b530-105">Authentifizierungsoptionen.</span><span class="sxs-lookup"><span data-stu-id="2b530-105">Authentication options.</span></span></param>
        <summary>
            <span data-ttu-id="2b530-106">Authentifiziert das Anmeldetoken aus der <see cref="T:Microsoft.Owin.IOwinRequest" /> -Header, sofern er vorhanden ist, und gibt eine <see cref="T:System.Security.Claims.ClaimsIdentity" /> wenn Authentifizierung erfolgreich war, oder "false" bei einem Authentifizierungsfehler.</span><span class="sxs-lookup"><span data-stu-id="2b530-106">Authenticates the login token from the <see cref="T:Microsoft.Owin.IOwinRequest" /> header, if it exists, and returns a <see cref="T:System.Security.Claims.ClaimsIdentity" /> if authentication succeeded, or false if authentication failed.</span></span> <span data-ttu-id="2b530-107">Wenn Fehler bei der Analyse von token, zurück null.</span><span class="sxs-lookup"><span data-stu-id="2b530-107">If token parsing failed, returns null.</span></span>
            </summary>
        <returns><span data-ttu-id="2b530-108">Gibt die <see cref="T:System.Security.Claims.ClaimsIdentity" /> bei erfolgreicher Überprüfung des Tokens.</span><span class="sxs-lookup"><span data-stu-id="2b530-108">Returns the <see cref="T:System.Security.Claims.ClaimsIdentity" /> if token validation succeeded.</span></span>
            <span data-ttu-id="2b530-109">Gibt null zurück, wenn das token aus irgendeinem Grund Fehler bei der Analyse.</span><span class="sxs-lookup"><span data-stu-id="2b530-109">Returns null if token parsing failed for any reason.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>