<Type Name="AuthenticationContextIntegratedAuthExtensions" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions">
  <TypeSignature Language="C#" Value="public static class AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit AuthenticationContextIntegratedAuthExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module AuthenticationContextIntegratedAuthExtensions" />
  <TypeSignature Language="F#" Value="type AuthenticationContextIntegratedAuthExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20459-101">Der Erweiterungsklasse an Benutzername/Kennwort-Datenfluss zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="20459-101">Extension class to support username/password flow.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcquireTokenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync (this Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext ctx, string resource, string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential userCredential);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt; AcquireTokenAsync(class Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext ctx, string resource, string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential userCredential) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions.AcquireTokenAsync(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext,System.String,System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential)" />
      <MemberSignature Language="F#" Value="static member AcquireTokenAsync : Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext * string * string * Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential -&gt; System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions.AcquireTokenAsync (ctx, resource, clientId, userCredential)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory.Platform</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContextIntegratedAuthExtensions/&lt;AcquireTokenAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ctx" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.AuthenticationContext" RefType="this" />
        <Parameter Name="resource" Type="System.String" />
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="userCredential" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" />
      </Parameters>
      <Docs>
        <param name="ctx"><span data-ttu-id="20459-102">Kontextinstanz Authentifizierung</span><span class="sxs-lookup"><span data-stu-id="20459-102">Authentication context instance</span></span></param>
        <param name="resource"><span data-ttu-id="20459-103">Der Bezeichner der Zielressource, die den Empfänger des angeforderten Tokens ist.</span><span class="sxs-lookup"><span data-stu-id="20459-103">Identifier of the target resource that is the recipient of the requested token.</span></span></param>
        <param name="clientId"><span data-ttu-id="20459-104">Der Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="20459-104">Identifier of the client requesting the token.</span></span></param>
        <param name="userCredential"><span data-ttu-id="20459-105">Die Anmeldeinformationen des Benutzers, der für den tokenabruf verwendet.</span><span class="sxs-lookup"><span data-stu-id="20459-105">The user credential to use for token acquisition.</span></span></param>
        <summary>
            <span data-ttu-id="20459-106">Ruft das Sicherheitstoken von der Zertifizierungsstelle ab.</span><span class="sxs-lookup"><span data-stu-id="20459-106">Acquires security token from the authority.</span></span>
            </summary>
        <returns><span data-ttu-id="20459-107">Es enthält Zugriffstoken, die für den Ablauf, Benutzerinformationen.</span><span class="sxs-lookup"><span data-stu-id="20459-107">It contains Access Token, its expiration time, user information.</span></span></returns>
        <remarks><span data-ttu-id="20459-108">Diese Funktion ist nur für Azure Active Directory und Active Directory Federation Services (ADFS) unter Windows 10 unterstützt.</span><span class="sxs-lookup"><span data-stu-id="20459-108">This feature is supported only for Azure Active Directory and Active Directory Federation Services (ADFS) on Windows 10.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>