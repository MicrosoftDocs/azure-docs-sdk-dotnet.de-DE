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
            Anmeldeinformationen für die integrierte Authentifizierung für die Domäne eingebundenen Computer verwendet.
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
            Konstruktor zum Erstellen von Benutzeranmeldeinformationen. Mit diesem Konstruktor würden implizieren, integrierte Authentifizierung mit angemeldeten Benutzer und kann nur in der Domäne beigetreten Szenarien verwendet werden.
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
        <param name="userName">Bezeichner der benutzeranwendung fordert-Token im Auftrag.</param>
        <summary>
            Konstruktor zum Erstellen von Anmeldeinformationen mit Benutzernamen
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
            Ruft die ID des Benutzers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>