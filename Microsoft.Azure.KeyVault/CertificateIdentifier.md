<Type Name="CertificateIdentifier" FullName="Microsoft.Azure.KeyVault.CertificateIdentifier">
  <TypeSignature Language="C#" Value="public sealed class CertificateIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CertificateIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.CertificateIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CertificateIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type CertificateIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            Der Bezeichner des Key Vault-Zertifikat.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateIdentifier : string -&gt; Microsoft.Azure.KeyVault.CertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier">Der Bezeichner für das Zertifikat.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CertificateIdentifier (string vaultBaseUrl, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.CertificateIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.CertificateIdentifier" Usage="new Microsoft.Azure.KeyVault.CertificateIdentifier (vaultBaseUrl, name, version)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vaultBaseUrl"> Die Vault-Basis-URL</param>
        <param name="name">Der Name des Zertifikats.</param>
        <param name="version">Die Version des Zertifikats.</param>
        <summary>
            Konstruktor.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCertificateIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsCertificateIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsCertificateIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.CertificateIdentifier.IsCertificateIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsCertificateIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsCertificateIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.CertificateIdentifier.IsCertificateIdentifier identifier" />
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
        <param name="identifier">Der Bezeichner für den schlüsseltresor-Zertifikat.</param>
        <summary>
            Überprüft, ob der Bezeichner, der einem Zertifikat schlüsseltresor gehört.
            </summary>
        <returns>"True", wenn der Bezeichner, der einem Zertifikat schlüsseltresor gehört. "False" andernfalls.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>