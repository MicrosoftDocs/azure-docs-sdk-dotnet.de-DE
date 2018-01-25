<Type Name="SymmetricEncryptionAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class SymmetricEncryptionAlgorithm : Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit SymmetricEncryptionAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class SymmetricEncryptionAlgorithm&#xA;Inherits EncryptionAlgorithm" />
  <TypeSignature Language="F#" Value="type SymmetricEncryptionAlgorithm = class&#xA;    inherit EncryptionAlgorithm" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0ac9-101">Abstrakte symmetrische Verschlüsselung-Algorithmus</span><span class="sxs-lookup"><span data-stu-id="d0ac9-101">Abstract SymmetricEncryption Algorithm</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected SymmetricEncryptionAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm name" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDecryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateDecryptor (byte[] key, byte[] iv, byte[] authenticationData, byte[] authenticationTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateDecryptor(unsigned int8[] key, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.CreateDecryptor(System.Byte[],System.Byte[],System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateDecryptor (key As Byte(), iv As Byte(), authenticationData As Byte(), authenticationTag As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateDecryptor : byte[] * byte[] * byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="symmetricEncryptionAlgorithm.CreateDecryptor (key, iv, authenticationData, authenticationTag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="authenticationTag" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0ac9-102">Das Schlüsselmaterial verwendet werden</span><span class="sxs-lookup"><span data-stu-id="d0ac9-102">The key material to be used</span></span></param>
        <param name="iv"><span data-ttu-id="d0ac9-103">Der Initialisierungsvektor, der verwendet werden</span><span class="sxs-lookup"><span data-stu-id="d0ac9-103">The initialization vector to be used</span></span></param>
        <param name="authenticationData"><span data-ttu-id="d0ac9-104">Die Authentifizierungsdaten beim Authentifizieren von Verschlüsselungsalgorithmen verwendet werden (nicht authentifizieren ignoriert Algorithmen)</span><span class="sxs-lookup"><span data-stu-id="d0ac9-104">The authentication data to be used with authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <param name="authenticationTag"><span data-ttu-id="d0ac9-105">Zu überprüfen, ob die Authentifizierung Verschlüsselungsalgorithmen mit Tags Authentifizierung (für nicht authentifizieren ignoriert Algorithmen)</span><span class="sxs-lookup"><span data-stu-id="d0ac9-105">The authentication tag to verify when using authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <summary>
            <span data-ttu-id="d0ac9-106">Erstellen Sie eine Entschlüsselungsmethode für den angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="d0ac9-106">Create a decryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="d0ac9-107">Ein ICryptoTransform zum Entschlüsseln von Daten</span><span class="sxs-lookup"><span data-stu-id="d0ac9-107">An ICryptoTransform for decrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEncryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateEncryptor (byte[] key, byte[] iv, byte[] authenticationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateEncryptor(unsigned int8[] key, unsigned int8[] iv, unsigned int8[] authenticationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.SymmetricEncryptionAlgorithm.CreateEncryptor(System.Byte[],System.Byte[],System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateEncryptor (key As Byte(), iv As Byte(), authenticationData As Byte()) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateEncryptor : byte[] * byte[] * byte[] -&gt; System.Security.Cryptography.ICryptoTransform" Usage="symmetricEncryptionAlgorithm.CreateEncryptor (key, iv, authenticationData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="d0ac9-108">Das Schlüsselmaterial verwendet werden</span><span class="sxs-lookup"><span data-stu-id="d0ac9-108">The key material to be used</span></span></param>
        <param name="iv"><span data-ttu-id="d0ac9-109">Der Initialisierungsvektor, der verwendet werden</span><span class="sxs-lookup"><span data-stu-id="d0ac9-109">The initialization vector to be used</span></span></param>
        <param name="authenticationData"><span data-ttu-id="d0ac9-110">Die Authentifizierungsdaten beim Authentifizieren von Verschlüsselungsalgorithmen verwendet werden (nicht authentifizieren ignoriert Algorithmen)</span><span class="sxs-lookup"><span data-stu-id="d0ac9-110">The authentication data to be used with authenticating encryption algorithms (ignored for non-authenticating algorithms)</span></span></param>
        <summary>
            <span data-ttu-id="d0ac9-111">Erstellen Sie eine Verschlüsselungsmethode anzugeben, für den angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="d0ac9-111">Create an encryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="d0ac9-112">Ein ICryptoTranform zum Verschlüsseln von Daten</span><span class="sxs-lookup"><span data-stu-id="d0ac9-112">An ICryptoTranform for encrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>