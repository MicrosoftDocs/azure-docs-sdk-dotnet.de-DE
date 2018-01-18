<Type Name="KeyIdentifier" FullName="Microsoft.Azure.KeyVault.KeyIdentifier">
  <TypeSignature Language="C#" Value="public sealed class KeyIdentifier : Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit KeyIdentifier extends Microsoft.Azure.KeyVault.ObjectIdentifier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyIdentifier" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class KeyIdentifier&#xA;Inherits ObjectIdentifier" />
  <TypeSignature Language="F#" Value="type KeyIdentifier = class&#xA;    inherit ObjectIdentifier" />
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
            <span data-ttu-id="604bb-101">Der Schlüsselbezeichner des Key Vault.</span><span class="sxs-lookup"><span data-stu-id="604bb-101">The Key Vault key identifier.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (identifier As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyIdentifier : string -&gt; Microsoft.Azure.KeyVault.KeyIdentifier" Usage="new Microsoft.Azure.KeyVault.KeyIdentifier identifier" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="identifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="identifier"><span data-ttu-id="604bb-102">Der Bezeichner für die Key-Objekt</span><span class="sxs-lookup"><span data-stu-id="604bb-102">The identifier for key object</span></span></param>
        <summary>
            <span data-ttu-id="604bb-103">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="604bb-103">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeyIdentifier (string vaultBaseUrl, string name, string version = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string vaultBaseUrl, string name, string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (vaultBaseUrl As String, name As String, Optional version As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.KeyIdentifier : string * string * string -&gt; Microsoft.Azure.KeyVault.KeyIdentifier" Usage="new Microsoft.Azure.KeyVault.KeyIdentifier (vaultBaseUrl, name, version)" />
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
        <param name="vaultBaseUrl"> <span data-ttu-id="604bb-104">Die Vault-Basis-URL</span><span class="sxs-lookup"><span data-stu-id="604bb-104">The vault base URL</span></span></param>
        <param name="name"> <span data-ttu-id="604bb-105">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="604bb-105">the name of the key.</span></span> </param>
        <param name="version"> <span data-ttu-id="604bb-106">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="604bb-106">the version of the key.</span></span></param>
        <summary>
            <span data-ttu-id="604bb-107">Konstruktor.</span><span class="sxs-lookup"><span data-stu-id="604bb-107">Constructor.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsKeyIdentifier">
      <MemberSignature Language="C#" Value="public static bool IsKeyIdentifier (string identifier);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsKeyIdentifier(string identifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyIdentifier.IsKeyIdentifier(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function IsKeyIdentifier (identifier As String) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsKeyIdentifier : string -&gt; bool" Usage="Microsoft.Azure.KeyVault.KeyIdentifier.IsKeyIdentifier identifier" />
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
        <param name="identifier"><span data-ttu-id="604bb-108">Der Schlüsselbezeichner schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="604bb-108">The key vault key identifier.</span></span></param>
        <summary>
            <span data-ttu-id="604bb-109">Überprüft, ob der Bezeichner für einen schlüsseltresor Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="604bb-109">Verifies whether the identifier belongs to a key vault key.</span></span>
            </summary>
        <returns><span data-ttu-id="604bb-110">"true", wenn der Bezeichner für einen schlüsseltresor Schlüssel gehört.</span><span class="sxs-lookup"><span data-stu-id="604bb-110">True if the identifier belongs to a key vault key.</span></span> <span data-ttu-id="604bb-111">"False" andernfalls.</span><span class="sxs-lookup"><span data-stu-id="604bb-111">False otherwise.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>