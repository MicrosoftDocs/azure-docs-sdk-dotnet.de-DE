<Type Name="UserCredential" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential">
  <TypeSignature Language="C#" Value="public class UserCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UserCredential extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class UserCredential" />
  <TypeSignature Language="F#" Value="type UserCredential = class" />
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
            <span data-ttu-id="23be1-101">Anmeldeinformationen für die integrierte Authentifizierung für die Domäne eingebundenen Computer verwendet.</span><span class="sxs-lookup"><span data-stu-id="23be1-101">Credential used for integrated authentication on domain-joined machines.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="23be1-102">Konstruktor zum Erstellen von Benutzeranmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="23be1-102">Constructor to create user credential.</span></span> <span data-ttu-id="23be1-103">Mit diesem Konstruktor würden implizieren, integrierte Authentifizierung mit angemeldeten Benutzer und kann nur in der Domäne beigetreten Szenarien verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="23be1-103">Using this constructor would imply integrated authentication with logged in user and it can only be used in domain joined scenarios.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UserCredential (string userName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string userName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (userName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential : string -&gt; Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential" Usage="new Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential userName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="userName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="userName"><span data-ttu-id="23be1-104">Bezeichner der benutzeranwendung fordert-Token im Auftrag.</span><span class="sxs-lookup"><span data-stu-id="23be1-104">Identifier of the user application requests token on behalf.</span></span></param>
        <summary>
            <span data-ttu-id="23be1-105">Konstruktor zum Erstellen von Anmeldeinformationen mit Benutzernamen</span><span class="sxs-lookup"><span data-stu-id="23be1-105">Constructor to create credential with username</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserName">
      <MemberSignature Language="C#" Value="public string UserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential.UserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UserName As String" />
      <MemberSignature Language="F#" Value="member this.UserName : string" Usage="Microsoft.IdentityModel.Clients.ActiveDirectory.UserCredential.UserName" />
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
            <span data-ttu-id="23be1-106">Ruft die ID des Benutzers ab.</span><span class="sxs-lookup"><span data-stu-id="23be1-106">Gets identifier of the user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>