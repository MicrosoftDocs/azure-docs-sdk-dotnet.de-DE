<Type Name="ClientCredential" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential">
  <TypeSignature Language="C#" Value="public sealed class ClientCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ClientCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ClientCredential" />
  <TypeSignature Language="F#" Value="type ClientCredential = class" />
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
            <span data-ttu-id="4c1e0-101">Anmeldeinformationen, einschließlich Client-Id und den geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-101">Credential including client id and secret.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCredential (string clientId, Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret secureClientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, class Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret secureClientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential.#ctor(System.String,Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, secureClientSecret As ISecureClientSecret)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential : string * Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential (clientId, secureClientSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="secureClientSecret" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.ISecureClientSecret" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="4c1e0-102">Der Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-102">Identifier of the client requesting the token.</span></span></param>
        <param name="secureClientSecret"><span data-ttu-id="4c1e0-103">Sichere geheime Schlüssel des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-103">Secure secret of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="4c1e0-104">Konstruktor zum Erstellen von Anmeldeinformationen mit Client-Id und geheimer.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-104">Constructor to create credential with client id and secret.</span></span> <span data-ttu-id="4c1e0-105">Dies ist nur verfügbar, auf dem Desktop.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-105">This is only available on desktop.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClientCredential (string clientId, string clientSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string clientId, string clientSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (clientId As String, clientSecret As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential : string * string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential (clientId, clientSecret)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="clientId" Type="System.String" />
        <Parameter Name="clientSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="clientId"><span data-ttu-id="4c1e0-106">Der Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-106">Identifier of the client requesting the token.</span></span></param>
        <param name="clientSecret"><span data-ttu-id="4c1e0-107">Geheime Schlüssel des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-107">Secret of the client requesting the token.</span></span></param>
        <summary>
            <span data-ttu-id="4c1e0-108">Konstruktor zum Erstellen von Anmeldeinformationen mit Client-Id und geheimer</span><span class="sxs-lookup"><span data-stu-id="4c1e0-108">Constructor to create credential with client id and secret</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientId">
      <MemberSignature Language="C#" Value="public string ClientId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ClientId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential.ClientId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientId As String" />
      <MemberSignature Language="F#" Value="member this.ClientId : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.ClientCredential.ClientId" />
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
            <span data-ttu-id="4c1e0-109">Ruft den Bezeichner des Clients, die das Token anfordert.</span><span class="sxs-lookup"><span data-stu-id="4c1e0-109">Gets the identifier of the client requesting the token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>