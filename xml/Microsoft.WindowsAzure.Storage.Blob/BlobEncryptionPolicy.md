<Type Name="BlobEncryptionPolicy" FullName="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy">
  <TypeSignature Language="C#" Value="public sealed class BlobEncryptionPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit BlobEncryptionPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class BlobEncryptionPolicy" />
  <TypeSignature Language="F#" Value="type BlobEncryptionPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="bd713-101">Stellt eine Verschlüsselungsrichtlinie für die Durchführung der Umschlag Verschlüsselung/Entschlüsselung von Azure-Blobs dar.</span><span class="sxs-lookup"><span data-stu-id="bd713-101">Represents an encryption policy for performing envelope encryption/decryption of Azure blobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobEncryptionPolicy (Microsoft.Azure.KeyVault.Core.IKey key, Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.KeyVault.Core.IKey key, class Microsoft.Azure.KeyVault.Core.IKeyResolver keyResolver) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.#ctor(Microsoft.Azure.KeyVault.Core.IKey,Microsoft.Azure.KeyVault.Core.IKeyResolver)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (key As IKey, keyResolver As IKeyResolver)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy : Microsoft.Azure.KeyVault.Core.IKey * Microsoft.Azure.KeyVault.Core.IKeyResolver -&gt; Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" Usage="new Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy (key, keyResolver)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.Core.IKey" />
        <Parameter Name="keyResolver" Type="Microsoft.Azure.KeyVault.Core.IKeyResolver" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="bd713-102">Ein Objekt des Typs <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> , Wrap/des Inhaltsschlüssels während der Verschlüsselung Entpacken von verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bd713-102">An object of type <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> that is used to wrap/unwrap the content key during encryption.</span></span></param>
        <param name="keyResolver"><span data-ttu-id="bd713-103">Der Key-Konfliktlöser verwendet, um den richtigen Schlüssel zum Entschlüsseln der vorhandene Blobs auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="bd713-103">The key resolver used to select the correct key for decrypting existing blobs.</span></span></param>
        <summary>
            <span data-ttu-id="bd713-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" /> Klasse mit dem angegebenen Schlüssel und den Konfliktlöser.</span><span class="sxs-lookup"><span data-stu-id="bd713-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy" /> class with the specified key and resolver.</span></span>
            </summary>
        <remarks><span data-ttu-id="bd713-105">Ist die generierte Richtlinie für die Verschlüsselung verwendet werden, werden Benutzer geben Sie einen Schlüssel mindestens erwartet.</span><span class="sxs-lookup"><span data-stu-id="bd713-105">If the generated policy is to be used for encryption, users are expected to provide a key at the minimum.</span></span>
            <span data-ttu-id="bd713-106">Das Fehlen des Schlüssels wird dazu führen, dass eine Ausnahme ausgelöst wird, während der Verschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="bd713-106">The absence of key will cause an exception to be thrown during encryption.</span></span><br />
            <span data-ttu-id="bd713-107">Wenn die generierte Richtlinie für die Entschlüsselung verwendet werden soll, können Benutzern Resolvern Schlüssel bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="bd713-107">If the generated policy is intended to be used for decryption, users can provide a key resolver.</span></span> <span data-ttu-id="bd713-108">Die Clientbibliothek wird:</span><span class="sxs-lookup"><span data-stu-id="bd713-108">The client library will:</span></span><br />
            1. <span data-ttu-id="bd713-109">Rufen Sie die wichtigsten Konfliktlöser, auf, wenn angegeben, um den Schlüssel zu erhalten.</span><span class="sxs-lookup"><span data-stu-id="bd713-109">Invoke the key resolver, if specified, to get the key.</span></span><br />
            2. <span data-ttu-id="bd713-110">Wenn der Konfliktlöser wird nicht angegeben, aber ein Schlüssel angegeben worden ist, entspricht die Clientbibliothek des Schlüssels ID für die Schlüssel und die Verwendung des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="bd713-110">If resolver is not specified but a key is specified, the client library will match the key ID against the key and use the key.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Key">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKey Key { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKey Key" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.Key" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Key As IKey" />
      <MemberSignature Language="F#" Value="member this.Key : Microsoft.Azure.KeyVault.Core.IKey" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.Key" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKey</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd713-111">Ein Objekt des Typs <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> , Wrap/des Inhaltsschlüssels während der Verschlüsselung Entpacken von verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="bd713-111">An object of type <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" /> that is used to wrap/unwrap the content key during encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyResolver">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.KeyVault.Core.IKeyResolver KeyResolver" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.KeyResolver" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property KeyResolver As IKeyResolver" />
      <MemberSignature Language="F#" Value="member this.KeyResolver : Microsoft.Azure.KeyVault.Core.IKeyResolver" Usage="Microsoft.WindowsAzure.Storage.Blob.BlobEncryptionPolicy.KeyResolver" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.Core.IKeyResolver</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bd713-112">Abrufen oder festlegen den Schlüssel Konfliktlöser verwendet, um den richtigen Schlüssel zum Entschlüsseln der vorhandene Blobs auszuwählen.</span><span class="sxs-lookup"><span data-stu-id="bd713-112">Gets or sets the key resolver used to select the correct key for decrypting existing blobs.</span></span>
            </summary>
        <value><span data-ttu-id="bd713-113">Einen Konfliktlöser, der gibt eine <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />, angegebenen ein Schlüssel-ID auf.</span><span class="sxs-lookup"><span data-stu-id="bd713-113">A resolver that returns an <see cref="T:Microsoft.Azure.KeyVault.Core.IKey" />, given a key ID.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>