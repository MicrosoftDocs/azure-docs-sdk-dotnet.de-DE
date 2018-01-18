<Type Name="SecretIdentifier" FullName="Microsoft.Azure.KeyVault.SecretIdentifier">
  <TypeSignature Language="C#" Value="public sealed class SecretIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SecretIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.SecretIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SecretIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type SecretIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="a8997-101">Der geheime Key Vault-Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="a8997-101">The Key Vault secret identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SecretIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SecretIdentifier : string -&gt; Microsoft.Azure.KeyVault.SecretIdentifier" Usage="new Microsoft.Azure.KeyVault.SecretIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="a8997-102">Der Bezeichner für den geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="a8997-102">The identifier for secret.</span></span></param>
        <summary>
            <span data-ttu-id="a8997-103">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="a8997-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretIdentifier (string vaultBaseUrl, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SecretIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.SecretIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.SecretIdentifier" Usage="new Microsoft.Azure.KeyVault.SecretIdentifier (vaultBaseUrl, name, version)" />
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
        <param name="vaultBaseUrl"> <span data-ttu-id="a8997-104">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="a8997-104">the vault base URL</span></span></param>
        <param name="name"><span data-ttu-id="a8997-105">der Name des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="a8997-105">the name of the secret</span></span> </param>
        <param name="version"><span data-ttu-id="a8997-106">die Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="a8997-106">the version of the secret.</span></span></param>
        <summary>
            <span data-ttu-id="a8997-107">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="a8997-107">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSecretIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsSecretIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsSecretIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.SecretIdentifier.IsSecretIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsSecretIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsSecretIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.SecretIdentifier.IsSecretIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="a8997-108">der schlüsseltresor geheime Bezeichner.</span><span class="sxs-lookup"><span data-stu-id="a8997-108">The key vault secret identifier.</span></span></param>
        <summary>
            <span data-ttu-id="a8997-109">Überprüft, ob der Bezeichner für einen schlüsseltresor geheimen Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="a8997-109">Verifies whether the identifier belongs to a key vault secret.</span></span>
            </summary>
        <returns><span data-ttu-id="a8997-110">"true", wenn der Bezeichner für einen schlüsseltresor geheimen Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="a8997-110">True if the identifier belongs to a key vault secret.</span></span> <span data-ttu-id="a8997-111">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="a8997-111">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>