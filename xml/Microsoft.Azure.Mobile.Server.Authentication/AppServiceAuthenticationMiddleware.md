<Type Name="AppServiceAuthenticationMiddleware" FullName="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware">
  <TypeSignature Language="C#" Value="public class AppServiceAuthenticationMiddleware : Microsoft.Owin.Security.Infrastructure.AuthenticationMiddleware&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AppServiceAuthenticationMiddleware extends Microsoft.Owin.Security.Infrastructure.AuthenticationMiddleware`1&lt;class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" />
  <TypeSignature Language="VB.NET" Value="Public Class AppServiceAuthenticationMiddleware&#xA;Inherits AuthenticationMiddleware(Of AppServiceAuthenticationOptions)" />
  <TypeSignature Language="F#" Value="type AppServiceAuthenticationMiddleware = class&#xA;    inherit AuthenticationMiddleware&lt;AppServiceAuthenticationOptions&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Owin.Security.Infrastructure.AuthenticationMiddleware&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="0cc30-101">Die <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" /> bietet die owin-Middleware zum Authentifizieren von eines Aufrufers, die bereits mit dem Controller Anmeldung authentifiziert hat.</span><span class="sxs-lookup"><span data-stu-id="0cc30-101">The <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" /> provides the OWIN middleware for authenticating a caller who has already authenticated using the Login controller.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AppServiceAuthenticationMiddleware (Microsoft.Owin.OwinMiddleware next, Owin.IAppBuilder appBuilder, Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Owin.OwinMiddleware next, class Owin.IAppBuilder appBuilder, class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware.#ctor(Microsoft.Owin.OwinMiddleware,Owin.IAppBuilder,Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (next As OwinMiddleware, appBuilder As IAppBuilder, options As AppServiceAuthenticationOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware : Microsoft.Owin.OwinMiddleware * Owin.IAppBuilder * Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions -&gt; Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" Usage="new Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware (next, appBuilder, options)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="next" Type="Microsoft.Owin.OwinMiddleware" />
        <Parameter Name="appBuilder" Type="Owin.IAppBuilder" />
        <Parameter Name="options" Type="Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions" />
      </Parameters>
      <Docs>
        <param name="next"><span data-ttu-id="0cc30-102">Der nächste <see cref="T:Microsoft.Owin.OwinMiddleware" />.</span><span class="sxs-lookup"><span data-stu-id="0cc30-102">The next <see cref="T:Microsoft.Owin.OwinMiddleware" />.</span></span></param>
        <param name="appBuilder"><span data-ttu-id="0cc30-103">Die <see cref="T:Owin.IAppBuilder" /> konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="0cc30-103">The <see cref="T:Owin.IAppBuilder" /> to configure.</span></span></param>
        <param name="options"><span data-ttu-id="0cc30-104">Die Optionen für diese Middleware.</span><span class="sxs-lookup"><span data-stu-id="0cc30-104">The options for this middleware.</span></span></param>
        <summary>
            <span data-ttu-id="0cc30-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="0cc30-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateHandler">
      <MemberSignature Language="C#" Value="protected override Microsoft.Owin.Security.Infrastructure.AuthenticationHandler&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt; CreateHandler ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance class Microsoft.Owin.Security.Infrastructure.AuthenticationHandler`1&lt;class Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt; CreateHandler() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationMiddleware.CreateHandler" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function CreateHandler () As AuthenticationHandler(Of AppServiceAuthenticationOptions)" />
      <MemberSignature Language="F#" Value="override this.CreateHandler : unit -&gt; Microsoft.Owin.Security.Infrastructure.AuthenticationHandler&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;" Usage="appServiceAuthenticationMiddleware.CreateHandler " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Owin.Security.Infrastructure.AuthenticationHandler&lt;Microsoft.Azure.Mobile.Server.Authentication.AppServiceAuthenticationOptions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
  </Members>
</Type>