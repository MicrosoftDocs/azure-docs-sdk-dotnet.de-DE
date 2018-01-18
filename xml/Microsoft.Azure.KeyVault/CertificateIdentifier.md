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
            <span data-ttu-id="1f06f-101">Der Bezeichner des Key Vault-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="1f06f-101">The Key Vault certificate identifier.</span></span>
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
        <param name="identifier"><span data-ttu-id="1f06f-102">Der Bezeichner für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="1f06f-102">The identifier for certificate.</span></span></param>
        <summary>
            <span data-ttu-id="1f06f-103">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="1f06f-103">Constructor.</span></span>
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
        <param name="vaultBaseUrl"> <span data-ttu-id="1f06f-104">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="1f06f-104">the vault base URL</span></span></param>
        <param name="name"><span data-ttu-id="1f06f-105">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="1f06f-105">the name of the certificate.</span></span></param>
        <param name="version"><span data-ttu-id="1f06f-106">Die Version des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="1f06f-106">the version of the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="1f06f-107">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="1f06f-107">Constructor.</span></span>
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
        <param name="identifier"><span data-ttu-id="1f06f-108">Der Bezeichner für den schlüsseltresor-Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="1f06f-108">The key vault certificate identifier.</span></span></param>
        <summary>
            <span data-ttu-id="1f06f-109">Überprüft, ob der Bezeichner, der einem Zertifikat schlüsseltresor gehört.</span><span class="sxs-lookup"><span data-stu-id="1f06f-109">Verifies whether the identifier belongs to a key vault certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="1f06f-110">"True", wenn der Bezeichner, der einem Zertifikat schlüsseltresor gehört.</span><span class="sxs-lookup"><span data-stu-id="1f06f-110">True if the identifier belongs to a key vault certificate.</span></span> <span data-ttu-id="1f06f-111">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="1f06f-111">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>