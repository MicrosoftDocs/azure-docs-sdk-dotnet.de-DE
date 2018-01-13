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
            Stellt eine Abstraktion für die Behandlung von Sicherheitstoken bereit. Diese Abstraktion kann verwendet werden, für die Validierung der Sicherheitstoken und Erstellen von <see cref="T:System.Security.Claims.ClaimsPrincipal" /> Instanzen.
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
        <param name="providerName">Der Anbietername für die Anmeldung.</param>
        <param name="providerUserId">Der Anbieter-spezifischen Benutzer-Id an.</param>
        <summary>
            Erstellt einen Benutzer-Id-Wert, der als Bestandteil einer <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />. Die Benutzer-Id weist das Format <c>ProviderName:ProviderId</c> , in dem die <c>ProviderName</c> ist der eindeutige Bezeichner für den Anmeldeanbieter und <c>ProviderId</c> ist der Anbieter spezifische Id für einen bestimmten Benutzer.
            </summary>
        <returns>Eine formatierte <see cref="T:System.String" /> , die den resultierenden Wert darstellt.</returns>
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
        <param name="userId">Der Eingabewert, zu analysieren.</param>
        <param name="providerName">Der Anbietername für die Anmeldung; oder <c>null</c> Wenn die <paramref name="userId" /> ist ungültig.</param>
        <param name="providerUserId">Die Anbieter-spezifischen Benutzer-Id; oder <c>null</c> ist die <paramref name="userId" /> ist ungültig.</param>
        <summary>
            Analysiert eine Benutzer-Id in die zwei Komponenten: eine <c>ProviderName</c> die eindeutig den Anmeldeanbieter identifiziert und die <c>ProviderId</c> identifiziert die bestimmten Anbieter-Id für einen bestimmten Benutzer.
            </summary>
        <returns>
          <c>"true"</c> Wenn <paramref name="userId" /> gültig ist andernfalls <c>"false"</c>/</returns>
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
        <param name="token">Ein <see cref="T:System.String" /> Darstellung des Authentifizierungstokens zu überprüfen.</param>
        <param name="signingKey">Der geheime Schlüssel, mit dem das Token signiert wurde.</param>
        <param name="validAudiences">Die gültigen Zielgruppen tokenüberprüfung zu.</param>
        <param name="validIssuers">Die gültigen Aussteller in tokenüberprüfung annehmen.</param>
        <param name="claimsPrincipal">Das resultierende <see cref="T:System.Security.Claims.ClaimsPrincipal" /> , wenn das Token gültig ist; andernfalls null.</param>
        <summary>
            Überprüft eine Zeichenfolgendarstellung für einen mobilen Dienst Authentifizierungstoken, die zum Authentifizieren einer Anforderung des Benutzers verwendet.
            </summary>
        <returns>
          <c>"true"</c> Wenn <paramref name="token" /> gültig ist andernfalls <c>"false"</c>/</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>