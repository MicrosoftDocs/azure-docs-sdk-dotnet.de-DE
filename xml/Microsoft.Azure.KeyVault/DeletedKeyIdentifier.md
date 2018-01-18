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
            <span data-ttu-id="0ac92-101">Der Schlüsseltresor gelöscht Schlüsselbezeichner.</span><span class="sxs-lookup"><span data-stu-id="0ac92-101">The Key Vault deleted key identifier.</span></span> <span data-ttu-id="0ac92-102">D. h. die RecoveryId.</span><span class="sxs-lookup"><span data-stu-id="0ac92-102">Aka the recoveryId.</span></span>
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
        <param name="identifier"><span data-ttu-id="0ac92-103">Der Bezeichner für den Schlüssel gelöscht.</span><span class="sxs-lookup"><span data-stu-id="0ac92-103">The identifier for the deleted key.</span></span> <span data-ttu-id="0ac92-104">Die RecoveryId AKA zurückgeben möchten, löschen.</span><span class="sxs-lookup"><span data-stu-id="0ac92-104">Aka the recoveryId return from deletion.</span></span></param>
        <summary>
            <span data-ttu-id="0ac92-105">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="0ac92-105">Constructor.</span></span>
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
        <param name="vaultBaseUrl"> <span data-ttu-id="0ac92-106">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="0ac92-106">the vault base URL</span></span></param>
        <param name="name"><span data-ttu-id="0ac92-107">Der Name des gelöschten Schlüssels</span><span class="sxs-lookup"><span data-stu-id="0ac92-107">the name of the deleted key</span></span> </param>
        <summary>
            <span data-ttu-id="0ac92-108">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="0ac92-108">Constructor.</span></span>
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
        <param name="identifier"><span data-ttu-id="0ac92-109">Der schlüsseltresor gelöscht Schlüsselbezeichner.</span><span class="sxs-lookup"><span data-stu-id="0ac92-109">The key vault deleted key identifier.</span></span></param>
        <summary>
            <span data-ttu-id="0ac92-110">Überprüft, ob der Bezeichner für einen schlüsseltresor gelöscht Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="0ac92-110">Verifies whether the identifier belongs to a key vault deleted key.</span></span>
            </summary>
        <returns><span data-ttu-id="0ac92-111">"True", wenn der Bezeichner für einen schlüsseltresor gelöscht Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="0ac92-111">True if the identifier belongs to a key vault deleted key.</span></span> <span data-ttu-id="0ac92-112">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="0ac92-112">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>