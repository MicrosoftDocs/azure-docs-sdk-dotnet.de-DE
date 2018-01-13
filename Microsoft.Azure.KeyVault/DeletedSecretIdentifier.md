<Type Name="DeletedSecretIdentifier" FullName="Microsoft.Azure.KeyVault.DeletedSecretIdentifier">
  <TypeSignature Language="C#" Value="public sealed class DeletedSecretIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletedSecretIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.DeletedSecretIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletedSecretIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type DeletedSecretIdentifier = class&#xA;    inherit ObjectIdentifier" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.ObjectIdentifier</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Schlüsseltresor gelöscht geheimen Schlüsselbezeichner. D. h. die RecoveryId.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSecretIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedSecretIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedSecretIdentifier : string -&gt; Microsoft.Azure.KeyVault.DeletedSecretIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedSecretIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">Der Bezeichner für die gelöschten geheimen Schlüssel. Die RecoveryId AKA zurückgeben möchten, löschen.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedSecretIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedSecretIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedSecretIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.DeletedSecretIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedSecretIdentifier (vaultBaseUrl, name)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> Die Vault-Basis-URL</param>
        <param name="name">Der Name des gelöschten geheimen Schlüssels </param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeletedSecretIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsDeletedSecretIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDeletedSecretIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedSecretIdentifier.IsDeletedSecretIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsDeletedSecretIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDeletedSecretIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.DeletedSecretIdentifier.IsDeletedSecretIdentifier identifier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">der schlüsseltresor geheime Bezeichner.</param>
        <summary>
            Überprüft, ob der Bezeichner für einen schlüsseltresor gelöscht geheimen Schlüssel gehört.
            </summary>
        <returns>"True", wenn der Bezeichner für einen schlüsseltresor gelöscht geheimen Schlüssel gehört. "False" andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>