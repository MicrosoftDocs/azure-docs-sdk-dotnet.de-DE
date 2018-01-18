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
            <span data-ttu-id="dd720-101">Der Schlüsseltresor gelöscht geheimen Schlüsselbezeichner.</span><span class="sxs-lookup"><span data-stu-id="dd720-101">The Key Vault deleted secret identifier.</span></span> <span data-ttu-id="dd720-102">D. h. die RecoveryId.</span><span class="sxs-lookup"><span data-stu-id="dd720-102">Aka the recoveryId.</span></span>
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
        <param name="identifier"><span data-ttu-id="dd720-103">Der Bezeichner für die gelöschten geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="dd720-103">The identifier for the deleted secret.</span></span> <span data-ttu-id="dd720-104">Die RecoveryId AKA zurückgeben möchten, löschen.</span><span class="sxs-lookup"><span data-stu-id="dd720-104">Aka the recoveryId return from deletion.</span></span></param>
        <summary>
            <span data-ttu-id="dd720-105">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="dd720-105">Constructor.</span></span>
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
        <param name="vaultBaseUrl"> <span data-ttu-id="dd720-106">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="dd720-106">the vault base URL</span></span></param>
        <param name="name"><span data-ttu-id="dd720-107">Der Name des gelöschten geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="dd720-107">the name of the deleted secret</span></span> </param>
        <summary>
            <span data-ttu-id="dd720-108">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="dd720-108">Constructor.</span></span>
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
        <param name="identifier"><span data-ttu-id="dd720-109">der schlüsseltresor geheime Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="dd720-109">The key vault secret identifier.</span></span></param>
        <summary>
            <span data-ttu-id="dd720-110">Überprüft, ob der Bezeichner für einen schlüsseltresor gelöscht geheimen Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="dd720-110">Verifies whether the identifier belongs to a key vault deleted secret.</span></span>
            </summary>
        <returns><span data-ttu-id="dd720-111">"True", wenn der Bezeichner für einen schlüsseltresor gelöscht geheimen Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="dd720-111">True if the identifier belongs to a key vault deleted secret.</span></span> <span data-ttu-id="dd720-112">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="dd720-112">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>