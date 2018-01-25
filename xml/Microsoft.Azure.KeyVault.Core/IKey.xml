<Type Name="IKey" FullName="Microsoft.Azure.KeyVault.Core.IKey">
  <TypeSignature Language="C#" Value="public interface IKey : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IKey implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Core.IKey" />
  <TypeSignature Language="VB.NET" Value="Public Interface IKey&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IKey = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="16deb-101">Eine Schnittstelle für Schlüssel</span><span class="sxs-lookup"><span data-stu-id="16deb-101">Interface for Keys</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; DecryptAsync (byte[] ciphertext, byte[] iv, byte[] authenticationData, byte[] authenticationTag, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; DecryptAsync(unsigned int8[] ciphertext, unsigned int8[] iv, unsigned int8[] authenticationData, unsigned int8[] authenticationTag, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.DecryptAsync(System.Byte[],System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function DecryptAsync (ciphertext As Byte(), iv As Byte(), authenticationData As Byte(), authenticationTag As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member DecryptAsync : byte[] * byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.DecryptAsync (ciphertext, iv, authenticationData, authenticationTag, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ciphertext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="authenticationTag" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="ciphertext"><span data-ttu-id="16deb-102">Der Verschlüsselungstext entschlüsselt</span><span class="sxs-lookup"><span data-stu-id="16deb-102">The cipher text to decrypt</span></span></param>
        <param name="iv"><span data-ttu-id="16deb-103">Der Initialisierungsvektor</span><span class="sxs-lookup"><span data-stu-id="16deb-103">The initialization vector</span></span></param>
        <param name="authenticationData"><span data-ttu-id="16deb-104">Die Authentifizierungsdaten</span><span class="sxs-lookup"><span data-stu-id="16deb-104">The authentication data</span></span></param>
        <param name="authenticationTag">To be added.</param>
        <param name="algorithm"><span data-ttu-id="16deb-105">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-105">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-106">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-106">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-107">Entschlüsselt den angegebenen Verschlüsselungstext.</span><span class="sxs-lookup"><span data-stu-id="16deb-107">Decrypts the specified cipher text.</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-108">Nur-text</span><span class="sxs-lookup"><span data-stu-id="16deb-108">The plain text</span></span></returns>
        <remarks><span data-ttu-id="16deb-109">Wenn kein Algorithmus angegeben ist, sollte eine Implementierung der Standardalgorithmus verwenden.</span><span class="sxs-lookup"><span data-stu-id="16deb-109">If algorithm is not specified, an implementation should use its default algorithm.</span></span>
            <span data-ttu-id="16deb-110">Nicht alle Algorithmen erfordern oder alle Parameter zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="16deb-110">Not all algorithms require, or support, all parameters.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultEncryptionAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultEncryptionAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultEncryptionAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultEncryptionAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultEncryptionAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultEncryptionAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16deb-111">Der standardmäßige Verschlüsselungsalgorithmus für diesen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="16deb-111">The default encryption algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultKeyWrapAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultKeyWrapAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultKeyWrapAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultKeyWrapAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultKeyWrapAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16deb-112">Der Standardschlüssel wrap-Algorithmus für diesen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="16deb-112">The default key wrap algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultSignatureAlgorithm">
      <MemberSignature Language="C#" Value="public string DefaultSignatureAlgorithm { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultSignatureAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultSignatureAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.DefaultSignatureAlgorithm : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.DefaultSignatureAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16deb-113">Der Standardalgorithmus für die Signatur für diesen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="16deb-113">The default signature algorithm for this key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],byte[],string&gt;&gt; EncryptAsync (byte[] plaintext, byte[] iv, byte[] authenticationData, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`3&lt;unsigned int8[], unsigned int8[], string&gt;&gt; EncryptAsync(unsigned int8[] plaintext, unsigned int8[] iv, unsigned int8[] authenticationData, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.EncryptAsync(System.Byte[],System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function EncryptAsync (plaintext As Byte(), iv As Byte(), authenticationData As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member EncryptAsync : byte[] * byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * byte[] * string&gt;" Usage="iKey.EncryptAsync (plaintext, iv, authenticationData, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="plaintext" Type="System.Byte[]" />
        <Parameter Name="iv" Type="System.Byte[]" />
        <Parameter Name="authenticationData" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="plaintext"><span data-ttu-id="16deb-114">Der Klartext verschlüsselt</span><span class="sxs-lookup"><span data-stu-id="16deb-114">The plain text to encrypt</span></span></param>
        <param name="iv"><span data-ttu-id="16deb-115">Der Initialisierungsvektor</span><span class="sxs-lookup"><span data-stu-id="16deb-115">The initialization vector</span></span></param>
        <param name="authenticationData"><span data-ttu-id="16deb-116">Die Authentifizierungsdaten</span><span class="sxs-lookup"><span data-stu-id="16deb-116">The authentication data</span></span></param>
        <param name="algorithm"><span data-ttu-id="16deb-117">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-117">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-118">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-118">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-119">Verschlüsselt den angegebenen nur-Text.</span><span class="sxs-lookup"><span data-stu-id="16deb-119">Encrypts the specified plain text.</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-120">Ein Tupel bestehend aus verschlüsseltem Text, der authentifizierungstag (falls zutreffend), der verwendete Algorithmus</span><span class="sxs-lookup"><span data-stu-id="16deb-120">A Tuple consisting of the cipher text, the authentication tag (if applicable), the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="16deb-121">Wenn der Algorithmus nicht angegeben wird, sollte eine Implementierung der Standardalgorithmus verwenden.</span><span class="sxs-lookup"><span data-stu-id="16deb-121">If the algorithm is not specified, an implementation should use its default algorithm.</span></span>
            <span data-ttu-id="16deb-122">Nicht alle Algorithyms erfordern oder alle Parameter zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="16deb-122">Not all algorithyms require, or support, all parameters.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="Kid">
      <MemberSignature Language="C#" Value="public string Kid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kid As String" />
      <MemberSignature Language="F#" Value="member this.Kid : string" Usage="Microsoft.Azure.KeyVault.Core.IKey.Kid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="16deb-123">Der Schlüsselbezeichner</span><span class="sxs-lookup"><span data-stu-id="16deb-123">The key identifier</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; SignAsync (byte[] digest, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; SignAsync(unsigned int8[] digest, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.SignAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function SignAsync (digest As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member SignAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.SignAsync (digest, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="16deb-124">Der Digest anmelden</span><span class="sxs-lookup"><span data-stu-id="16deb-124">The digest to sign</span></span></param>
        <param name="algorithm"><span data-ttu-id="16deb-125">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-125">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-126">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-126">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-127">Registriert den angegebenen Hashwert.</span><span class="sxs-lookup"><span data-stu-id="16deb-127">Signs the specified digest.</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-128">Ein Tupel bestehend aus der Signatur und den verwendeten Algorithmus</span><span class="sxs-lookup"><span data-stu-id="16deb-128">A Tuple consisting of the signature and the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="16deb-129">Wenn der Algorithmus nicht angegeben wird, sollte eine Implementierung der Standardalgorithmus verwenden.</span><span class="sxs-lookup"><span data-stu-id="16deb-129">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;byte[]&gt; UnwrapKeyAsync (byte[] encryptedKey, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;unsigned int8[]&gt; UnwrapKeyAsync(unsigned int8[] encryptedKey, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.UnwrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnwrapKeyAsync (encryptedKey As Byte(), algorithm As String, token As CancellationToken) As Task(Of Byte())" />
      <MemberSignature Language="F#" Value="abstract member UnwrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[]&gt;" Usage="iKey.UnwrapKeyAsync (encryptedKey, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Byte[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptedKey" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encryptedKey"><span data-ttu-id="16deb-130">Das verschlüsselte Schlüsselmaterial</span><span class="sxs-lookup"><span data-stu-id="16deb-130">The encrypted key material</span></span></param>
        <param name="algorithm"><span data-ttu-id="16deb-131">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-131">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-132">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-132">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-133">Entschlüsselt den angegebenen Schlüsselmaterials.</span><span class="sxs-lookup"><span data-stu-id="16deb-133">Decrypts the specified key material.</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-134">Das entschlüsselte Schlüsselmaterial</span><span class="sxs-lookup"><span data-stu-id="16deb-134">The decrypted key material</span></span></returns>
        <remarks><span data-ttu-id="16deb-135">Wenn der Algorithmus nicht angegeben wird, sollte eine Implementierung der Standardalgorithmus verwenden.</span><span class="sxs-lookup"><span data-stu-id="16deb-135">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (byte[] digest, byte[] signature, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(unsigned int8[] digest, unsigned int8[] signature, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.VerifyAsync(System.Byte[],System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function VerifyAsync (digest As Byte(), signature As Byte(), algorithm As String, token As CancellationToken) As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member VerifyAsync : byte[] * byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iKey.VerifyAsync (digest, signature, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="digest"><span data-ttu-id="16deb-136">Der digest</span><span class="sxs-lookup"><span data-stu-id="16deb-136">The digest</span></span></param>
        <param name="signature"><span data-ttu-id="16deb-137">der Wert der Signatur</span><span class="sxs-lookup"><span data-stu-id="16deb-137">The signature value</span></span></param>
        <param name="algorithm"><span data-ttu-id="16deb-138">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-138">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-139">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-139">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-140">Überprüft den Wert der angegebenen Signatur</span><span class="sxs-lookup"><span data-stu-id="16deb-140">Verifies the specified signature value</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-141">Einen booleschen Wert, der angibt, ob die Signatur wurde erfolgreich überprüft wurde</span><span class="sxs-lookup"><span data-stu-id="16deb-141">A bool indicating whether the signature was successfully verified</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Tuple&lt;byte[],string&gt;&gt; WrapKeyAsync (byte[] key, string algorithm, System.Threading.CancellationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Tuple`2&lt;unsigned int8[], string&gt;&gt; WrapKeyAsync(unsigned int8[] key, string algorithm, valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Core.IKey.WrapKeyAsync(System.Byte[],System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function WrapKeyAsync (key As Byte(), algorithm As String, token As CancellationToken) As Task(Of Tuple(Of Byte(), String))" />
      <MemberSignature Language="F#" Value="abstract member WrapKeyAsync : byte[] * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;byte[] * string&gt;" Usage="iKey.WrapKeyAsync (key, algorithm, token)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault.Core</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Tuple&lt;System.Byte[],System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="16deb-142">Das Schlüsselmaterial verschlüsseln</span><span class="sxs-lookup"><span data-stu-id="16deb-142">The key material to encrypt</span></span></param>
        <param name="algorithm"><span data-ttu-id="16deb-143">Zu verwendenden Algorithmus an</span><span class="sxs-lookup"><span data-stu-id="16deb-143">The algorithm to use</span></span></param>
        <param name="token"><span data-ttu-id="16deb-144">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="16deb-144">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="16deb-145">Verschlüsselt den angegebenen Schlüsselmaterials.</span><span class="sxs-lookup"><span data-stu-id="16deb-145">Encrypts the specified key material.</span></span>
            </summary>
        <returns><span data-ttu-id="16deb-146">Ein Tupel bestehend aus den verschlüsselten Schlüssel und den verwendeten Algorithmus</span><span class="sxs-lookup"><span data-stu-id="16deb-146">A Tuple consisting of the encrypted key and the algorithm used</span></span></returns>
        <remarks><span data-ttu-id="16deb-147">Wenn der Algorithmus nicht angegeben wird, sollte eine Implementierung der Standardalgorithmus verwenden.</span><span class="sxs-lookup"><span data-stu-id="16deb-147">If the algorithm is not specified, an implementation should use its default algorithm</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>