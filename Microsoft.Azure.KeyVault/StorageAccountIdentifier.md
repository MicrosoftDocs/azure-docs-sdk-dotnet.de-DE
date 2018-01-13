<Type Name="StorageAccountIdentifier" FullName="Microsoft.Azure.KeyVault.StorageAccountIdentifier">
  <TypeSignature Language="C#" Value="public sealed class StorageAccountIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StorageAccountIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.StorageAccountIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StorageAccountIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type StorageAccountIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Der Bezeichner der Key Vault Storage-Konto.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.StorageAccountIdentifier : string -&gt; Microsoft.Azure.KeyVault.StorageAccountIdentifier" Usage="new Microsoft.Azure.KeyVault.StorageAccountIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">Der Bezeichner der Key Vault Storage-Konto.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountIdentifier (string vaultBaseUrl, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.StorageAccountIdentifier : string * string -&gt; Microsoft.Azure.KeyVault.StorageAccountIdentifier" Usage="new Microsoft.Azure.KeyVault.StorageAccountIdentifier (vaultBaseUrl, name)" />
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
        <param name="vaultBaseUrl">Die Vault-Basis-URL.</param>
        <param name="name">Der Name des Speicherkontos.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsStorageAccountIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsStorageAccountIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsStorageAccountIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.StorageAccountIdentifier.IsStorageAccountIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsStorageAccountIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsStorageAccountIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.StorageAccountIdentifier.IsStorageAccountIdentifier identifier" />
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
        <param name="identifier">Der Bezeichner der schlüsseltresor Storage-Konto.</param>
        <summary>
            Überprüft, ob der Bezeichner für ein Speicherkonto schlüsseltresor gehört.
            </summary>
        <returns>"True", wenn der Bezeichner für ein Speicherkonto schlüsseltresor gehört. "False" andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>