<Type Name="IAppServiceTokenHandler" FullName="Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler">
  <TypeSignature Language="C#" Value="public interface IAppServiceTokenHandler" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceTokenHandler" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceTokenHandler" />
  <TypeSignature Language="F#" Value="type IAppServiceTokenHandler = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8b1b0-101">Stellt eine Abstraktion für die Behandlung von Sicherheitstoken bereit.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-101">Provides an abstraction for handling security tokens.</span></span> <span data-ttu-id="8b1b0-102">Diese Abstraktion kann verwendet werden, für die Validierung der Sicherheitstoken und Erstellen von <see cref="T:System.Security.Claims.ClaimsPrincipal" /> Instanzen.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-102">This abstraction can be used for validating security tokens and creating <see cref="T:System.Security.Claims.ClaimsPrincipal" /> instances.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateUserId">
      <MemberSignature Language="C#" Value="public string CreateUserId (string providerName, string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance string CreateUserId(string providerName, string providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.CreateUserId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateUserId (providerName As String, providerUserId As String) As String" />
      <MemberSignature Language="F#" Value="abstract member CreateUserId : string * string -&gt; string" Usage="iAppServiceTokenHandler.CreateUserId (providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="providerName" Type="System.String" />
        <Parameter Name="providerUserId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="providerName"><span data-ttu-id="8b1b0-103">Der Anbietername für die Anmeldung.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-103">The login provider name.</span></span></param>
        <param name="providerUserId"><span data-ttu-id="8b1b0-104">Der Anbieter-spezifischen Benutzer-Id an.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-104">The provider specific user id.</span></span></param>
        <summary>
            <span data-ttu-id="8b1b0-105">Erstellt einen Benutzer-Id-Wert, der als Bestandteil einer <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-105">Creates a user id value contained within a <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />.</span></span> <span data-ttu-id="8b1b0-106">Die Benutzer-Id weist das Format <c>ProviderName:ProviderId</c> , in dem die <c>ProviderName</c> ist der eindeutige Bezeichner für den Anmeldeanbieter und <c>ProviderId</c> ist der Anbieter spezifische Id für einen bestimmten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-106">The user id is of the form <c>ProviderName:ProviderId</c> where the <c>ProviderName</c> is the unique identifier for the login provider and the <c>ProviderId</c> is the provider specific id for a given user.</span></span>
            </summary>
        <returns><span data-ttu-id="8b1b0-107">Eine formatierte <see cref="T:System.String" /> , die den resultierenden Wert darstellt.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-107">A formatted <see cref="T:System.String" /> representing the resulting value.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryParseUserId">
      <MemberSignature Language="C#" Value="public bool TryParseUserId (string userId, out string providerName, out string providerUserId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryParseUserId(string userId, [out] string&amp; providerName, [out] string&amp; providerUserId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryParseUserId(System.String,System.String@,System.String@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryParseUserId (userId As String, ByRef providerName As String, ByRef providerUserId As String) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryParseUserId : string *  *  -&gt; bool" Usage="iAppServiceTokenHandler.TryParseUserId (userId, providerName, providerUserId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1021:AvoidOutParameters", Justification="This is not unreasonable for this API.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="userId" Type="System.String" />
        <Parameter Name="providerName" Type="System.String&amp;" RefType="out" />
        <Parameter Name="providerUserId" Type="System.String&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="userId"><span data-ttu-id="8b1b0-108">Der Eingabewert, zu analysieren.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-108">The input value to parse.</span></span></param>
        <param name="providerName"><span data-ttu-id="8b1b0-109">Der Anbietername für die Anmeldung; oder <c>null</c> Wenn die <paramref name="userId" /> ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-109">The login provider name; or <c>null</c> if the <paramref name="userId" /> is not valid.</span></span></param>
        <param name="providerUserId"><span data-ttu-id="8b1b0-110">Die Anbieter-spezifischen Benutzer-Id; oder <c>null</c> ist die <paramref name="userId" /> ist ungültig.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-110">The provider specific user id; or <c>null</c> is the <paramref name="userId" /> is not valid.</span></span></param>
        <summary>
            <span data-ttu-id="8b1b0-111">Analysiert eine Benutzer-Id in die zwei Komponenten: eine <c>ProviderName</c> die eindeutig den Anmeldeanbieter identifiziert und die <c>ProviderId</c> identifiziert die bestimmten Anbieter-Id für einen bestimmten Benutzer.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-111">Parses a user id into its two components: a <c>ProviderName</c> which uniquely identifies the login provider and the <c>ProviderId</c> which identifies the provider specific id for a given user.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="8b1b0-112"><c>"true"</c> Wenn <paramref name="userId" /> gültig ist andernfalls <c>"false"</c>/</span><span class="sxs-lookup"><span data-stu-id="8b1b0-112"><c>true</c> if <paramref name="userId" /> is valid; otherwise <c>false</c>/</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TryValidateLoginToken">
      <MemberSignature Language="C#" Value="public bool TryValidateLoginToken (string token, string signingKey, System.Collections.Generic.IEnumerable&lt;string&gt; validAudiences, System.Collections.Generic.IEnumerable&lt;string&gt; validIssuers, out System.Security.Claims.ClaimsPrincipal claimsPrincipal);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool TryValidateLoginToken(string token, string signingKey, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validAudiences, class System.Collections.Generic.IEnumerable`1&lt;string&gt; validIssuers, [out] class System.Security.Claims.ClaimsPrincipal&amp; claimsPrincipal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler.TryValidateLoginToken(System.String,System.String,System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{System.String},System.Security.Claims.ClaimsPrincipal@)" />
      <MemberSignature Language="VB.NET" Value="Public Function TryValidateLoginToken (token As String, signingKey As String, validAudiences As IEnumerable(Of String), validIssuers As IEnumerable(Of String), ByRef claimsPrincipal As ClaimsPrincipal) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member TryValidateLoginToken : string * string * seq&lt;string&gt; * seq&lt;string&gt; *  -&gt; bool" Usage="iAppServiceTokenHandler.TryValidateLoginToken (token, signingKey, validAudiences, validIssuers, claimsPrincipal)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.String" />
        <Parameter Name="signingKey" Type="System.String" />
        <Parameter Name="validAudiences" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="validIssuers" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="claimsPrincipal" Type="System.Security.Claims.ClaimsPrincipal&amp;" RefType="out" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="8b1b0-113">Ein <see cref="T:System.String" /> Darstellung des Authentifizierungstokens zu überprüfen.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-113">A <see cref="T:System.String" /> representation of the authentication token to validate.</span></span></param>
        <param name="signingKey"><span data-ttu-id="8b1b0-114">Der geheime Schlüssel, mit dem das Token signiert wurde.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-114">The secret key with which the token has been signed.</span></span></param>
        <param name="validAudiences"><span data-ttu-id="8b1b0-115">Die gültigen Zielgruppen tokenüberprüfung zu.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-115">The valid audiences to accept in token validation.</span></span></param>
        <param name="validIssuers"><span data-ttu-id="8b1b0-116">Die gültigen Aussteller in tokenüberprüfung annehmen.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-116">The valid issuers to accept in token validation.</span></span></param>
        <param name="claimsPrincipal"><span data-ttu-id="8b1b0-117">Das resultierende <see cref="T:System.Security.Claims.ClaimsPrincipal" /> , wenn das Token gültig ist; andernfalls null.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-117">The resulting <see cref="T:System.Security.Claims.ClaimsPrincipal" /> if the token is valid; null otherwise.</span></span></param>
        <summary>
            <span data-ttu-id="8b1b0-118">Überprüft eine Zeichenfolgendarstellung für einen mobilen Dienst Authentifizierungstoken, die zum Authentifizieren einer Anforderung des Benutzers verwendet.</span><span class="sxs-lookup"><span data-stu-id="8b1b0-118">Validates a string representation of a mobile service authentication token used to authenticate a user request.</span></span>
            </summary>
        <returns>
          <span data-ttu-id="8b1b0-119"><c>"true"</c> Wenn <paramref name="token" /> gültig ist andernfalls <c>"false"</c>/</span><span class="sxs-lookup"><span data-stu-id="8b1b0-119"><c>true</c> if <paramref name="token" /> is valid; otherwise <c>false</c>/</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>