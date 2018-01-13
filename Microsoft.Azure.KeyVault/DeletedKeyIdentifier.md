<Type Name="DeletedKeyIdentifier" FullName="Microsoft.Azure.KeyVault.DeletedKeyIdentifier">
  <TypeSignature Language="C#" Value="public sealed class DeletedKeyIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeletedKeyIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.DeletedKeyIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeletedKeyIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type DeletedKeyIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Der Schlüsseltresor gelöscht Schlüsselbezeichner. D. h. die RecoveryId.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedKeyIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedKeyIdentifier : string -&gt; Microsoft.Azure.KeyVault.DeletedKeyIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedKeyIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">Der Bezeichner für den Schlüssel gelöscht. Die RecoveryId AKA zurückgeben möchten, löschen.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DeletedKeyIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedKeyIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.DeletedKeyIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.DeletedKeyIdentifier" Usage="new Microsoft.Azure.KeyVault.DeletedKeyIdentifier (vaultBaseUrl, name)" />
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
        <param name="name">Der Name des gelöschten Schlüssels </param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDeletedKeyIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsDeletedKeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsDeletedKeyIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.DeletedKeyIdentifier.IsDeletedKeyIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsDeletedKeyIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsDeletedKeyIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.DeletedKeyIdentifier.IsDeletedKeyIdentifier identifier" />
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
        <param name="identifier">Der schlüsseltresor gelöscht Schlüsselbezeichner.</param>
        <summary>
            Überprüft, ob der Bezeichner für einen schlüsseltresor gelöscht Schlüssel gehört.
            </summary>
        <returns>"True", wenn der Bezeichner für einen schlüsseltresor gelöscht Schlüssel gehört. "False" andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>