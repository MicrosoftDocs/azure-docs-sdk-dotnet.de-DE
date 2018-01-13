<Type Name="AsymmetricEncryptionAlgorithm" FullName="Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm">
  <TypeSignature Language="C#" Value="public abstract class AsymmetricEncryptionAlgorithm : Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit AsymmetricEncryptionAlgorithm extends Microsoft.Azure.KeyVault.Cryptography.EncryptionAlgorithm" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class AsymmetricEncryptionAlgorithm&#xA;Inherits EncryptionAlgorithm" />
  <TypeSignature Language="F#" Value="type AsymmetricEncryptionAlgorithm = class&#xA;    inherit EncryptionAlgorithm" />
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
            <span data-ttu-id="828b8-101">Abstrakte Verschlüsselungsalgorithmus für asymmetrischen</span><span class="sxs-lookup"><span data-stu-id="828b8-101">Abstract Asymmetric Encryption Algorithm</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AsymmetricEncryptionAlgorithm (string name);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (name As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm : string -&gt; Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm" Usage="new Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm name" />
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
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateDecryptor (System.Security.Cryptography.AsymmetricAlgorithm key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateDecryptor(class System.Security.Cryptography.AsymmetricAlgorithm key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm.CreateDecryptor(System.Security.Cryptography.AsymmetricAlgorithm)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateDecryptor (key As AsymmetricAlgorithm) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateDecryptor : System.Security.Cryptography.AsymmetricAlgorithm -&gt; System.Security.Cryptography.ICryptoTransform" Usage="asymmetricEncryptionAlgorithm.CreateDecryptor key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Security.Cryptography.AsymmetricAlgorithm" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="828b8-102">Der Schlüssel zum Erstellen von Entschlüsselungsmethode</span><span class="sxs-lookup"><span data-stu-id="828b8-102">The key used to create decryptor</span></span></param>
        <summary>
            <span data-ttu-id="828b8-103">Erstellen Sie eine Entschlüsselungsmethode für den angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="828b8-103">Create a decryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="828b8-104">Ein ICryptoTransform zum Verschlüsseln von Daten</span><span class="sxs-lookup"><span data-stu-id="828b8-104">An ICryptoTransform for encrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateEncryptor">
      <MemberSignature Language="C#" Value="public abstract System.Security.Cryptography.ICryptoTransform CreateEncryptor (System.Security.Cryptography.AsymmetricAlgorithm key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Security.Cryptography.ICryptoTransform CreateEncryptor(class System.Security.Cryptography.AsymmetricAlgorithm key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Cryptography.AsymmetricEncryptionAlgorithm.CreateEncryptor(System.Security.Cryptography.AsymmetricAlgorithm)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateEncryptor (key As AsymmetricAlgorithm) As ICryptoTransform" />
      <MemberSignature Language="F#" Value="abstract member CreateEncryptor : System.Security.Cryptography.AsymmetricAlgorithm -&gt; System.Security.Cryptography.ICryptoTransform" Usage="asymmetricEncryptionAlgorithm.CreateEncryptor key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Cryptography</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Security.Cryptography.ICryptoTransform</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Security.Cryptography.AsymmetricAlgorithm" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="828b8-105">So erstellen die Verschlüsselung verwendete Schlüssel</span><span class="sxs-lookup"><span data-stu-id="828b8-105">The key used to create the encryptor</span></span></param>
        <summary>
            <span data-ttu-id="828b8-106">Erstellen Sie eine Verschlüsselungsmethode anzugeben, für den angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="828b8-106">Create an encryptor for the specified key</span></span>
            </summary>
        <returns><span data-ttu-id="828b8-107">Ein ICryptoTransform zum Verschlüsseln von Daten</span><span class="sxs-lookup"><span data-stu-id="828b8-107">An ICryptoTransform for encrypting data</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>