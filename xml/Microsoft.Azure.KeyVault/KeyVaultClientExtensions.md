<Type Name="KeyVaultClientExtensions" FullName="Microsoft.Azure.KeyVault.KeyVaultClientExtensions">
  <TypeSignature Language="C#" Value="public static class KeyVaultClientExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit KeyVaultClientExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.KeyVaultClientExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module KeyVaultClientExtensions" />
  <TypeSignature Language="F#" Value="type KeyVaultClientExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="413ae-101">Erweiterungsmethoden für KeyVaultClient.</span><span class="sxs-lookup"><span data-stu-id="413ae-101">Extension methods for KeyVaultClient.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt; BackupKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupKeyAsync&gt;d__34))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupKeyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-102">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-103">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-103">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-104">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-104">The name of the key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-106">Fordert an, dass eine Sicherung des angegebenen Schlüssels an den Client heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-106">Requests that a backup of the specified key be downloaded to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-107">Der Schlüssel Sicherungsvorgang exportiert einen Schlüssel aus dem Azure-Schlüsseltresor in einer geschützten Form.</span><span class="sxs-lookup"><span data-stu-id="413ae-107">The Key Backup operation exports a key from Azure Key Vault in a protected form.</span></span> <span data-ttu-id="413ae-108">Beachten Sie, dass dieser Vorgang gibt keinen Schlüsselmaterial zurück, in ein Formular, das außerhalb der Azure Key Vault-System verwendet werden kann, das zurückgegebene Schlüsselmaterial ist entweder geschützt ein Azure-Schlüsseltresor-HSM oder Azure Key Vault selbst.</span><span class="sxs-lookup"><span data-stu-id="413ae-108">Note that this operation does NOT return key material in a form that can be used outside the Azure Key Vault system, the returned key material is either protected to a Azure Key Vault HSM or to Azure Key Vault itself.</span></span>
            <span data-ttu-id="413ae-109">Der Zweck dieses Vorgangs ist, kann einen Client einen Schlüssel in einer Instanz von Azure Key Vault, Sichern Sie den Schlüssel generieren und dann in eine andere Azure Key Vault-Instanz wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="413ae-109">The intent of this operation is to allow a client to GENERATE a key in one Azure Key Vault instance, BACKUP the key, and then RESTORE it into another Azure Key Vault instance.</span></span> <span data-ttu-id="413ae-110">Der Sicherungsvorgang kann verwendet werden, in geschützter Form jedes Schlüsseltyps im Azure Key Vault zu exportieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-110">The BACKUP operation may be used to export, in protected form, any key type from Azure Key Vault.</span></span> <span data-ttu-id="413ae-111">Einzelne Versionen eines Schlüssels können nicht gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-111">Individual versions of a key cannot be backed up.</span></span> <span data-ttu-id="413ae-112">Sicherung / Wiederherstellung nur; innerhalb geografischer Grenzen ausgeführt werden kann. Dies bedeutet, dass eine Sicherung aus einem geografischen Bereich nicht zu einem anderen geografischen Bereich wiederhergestellt werden kann.</span><span class="sxs-lookup"><span data-stu-id="413ae-112">BACKUP / RESTORE can be performed within geographical boundaries only; meaning that a BACKUP from one geographical area cannot be restored to another geographical area.</span></span> <span data-ttu-id="413ae-113">Beispielsweise kann eine Sicherung von geografischen Gebiet der USA in einer geografischen Bereich der EU wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-113">For example, a backup from the US geographical area cannot be restored in an EU geographical area.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt; BackupSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.BackupSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;BackupSecretAsync&gt;d__56))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.BackupSecretResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-114">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-114">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-115">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-115">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-116">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-116">The name of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-118">Fordert an, dass eine Sicherung des angegebenen geheimen Schlüssels an den Client heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-118">Requests that a backup of the specified secret be downloaded to the client.</span></span>
            <span data-ttu-id="413ae-119">Autorisierung: ist der geheime Schlüssel/Backup-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-119">Authorization: requires the secrets/backup permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; CreateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateCertificateAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateCertificateAsync&gt;d__68))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-120">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-120">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-121">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-121">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-122">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-122">The name of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="413ae-123">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-123">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="413ae-124">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="413ae-124">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-125">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-125">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-126">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-126">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-127">Erstellt ein neues Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="413ae-127">Creates a new certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-128">Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-128">If this is the first version, the certificate resource is created.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.NewKeyParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.NewKeyParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.NewKeyParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__10))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.KeyVault.Models.NewKeyParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl">To be added.</param>
        <param name="keyName">To be added.</param>
        <param name="parameters">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, Nullable&lt;int&gt; keySize = null, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; CreateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string kty, valuetype System.Nullable`1&lt;int32&gt; keySize, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.CreateKeyAsync (operations, vaultBaseUrl, keyName, kty, keySize, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;CreateKeyAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="kty" Type="System.String" />
        <Parameter Name="keySize" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-129">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-129">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-130">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-130">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-131">Der Name für den neuen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-131">The name for the new key.</span></span> <span data-ttu-id="413ae-132">Das System generiert den Versionsnamen für den neuen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-132">The system will generate the version name for the new key.</span></span>
            </param>
        <param name="kty">
            <span data-ttu-id="413ae-133">Der Typ des Schlüssels zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="413ae-133">The type of key to create.</span></span> <span data-ttu-id="413ae-134">Gültige Werte finden Sie unter JsonWebKeyType.</span><span class="sxs-lookup"><span data-stu-id="413ae-134">For valid values, see JsonWebKeyType.</span></span> <span data-ttu-id="413ae-135">Folgende Werte sind möglich: "EC", "EC-HSM", "RSA", "RSA-HSM", "oct"</span><span class="sxs-lookup"><span data-stu-id="413ae-135">Possible values include: 'EC', 'EC-HSM', 'RSA', 'RSA-HSM', 'oct'</span></span>
            </param>
        <param name="keySize">
            <span data-ttu-id="413ae-136">Die Schlüsselgröße in Bytes.</span><span class="sxs-lookup"><span data-stu-id="413ae-136">The key size in bytes.</span></span> <span data-ttu-id="413ae-137">Z. B. 1024 oder 2048.</span><span class="sxs-lookup"><span data-stu-id="413ae-137">For example, 1024 or 2048.</span></span>
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="413ae-138">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-138">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-139">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-139">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-140">Erstellt einen neuen Schlüssel, speichert ihn, dann gibt Schlüsselparameter und Attribute an den Client.</span><span class="sxs-lookup"><span data-stu-id="413ae-140">Creates a new key, stores it, then returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-141">Der Erstellvorgang Schlüssel kann zum Erstellen jedes Schlüsseltyps im Azure-Schlüsseltresor verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-141">The create key operation can be used to create any key type in Azure Key Vault.</span></span> <span data-ttu-id="413ae-142">Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-142">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] cipherText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] cipherText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, keyIdentifier, algorithm, cipherText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="cipherText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="413ae-143">Der vollständige Schlüsselbezeichner</span><span class="sxs-lookup"><span data-stu-id="413ae-143">The full key identifier</span></span></param>
        <param name="algorithm"><span data-ttu-id="413ae-144">Der Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-144">The algorithm.</span></span> <span data-ttu-id="413ae-145">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeyEncryptionAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-145">For more information on possible algorithm types, see JsonWebKeyEncryptionAlgorithm.</span></span></param>
        <param name="cipherText"><span data-ttu-id="413ae-146">Der Verschlüsselungstext</span><span class="sxs-lookup"><span data-stu-id="413ae-146">The cipher text</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-147">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-147">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-148">Einen einzelnen Block von verschlüsselten Daten entschlüsselt</span><span class="sxs-lookup"><span data-stu-id="413ae-148">Decrypts a single block of encrypted data</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-149">Das Ergebnis der Entschlüsselung</span><span class="sxs-lookup"><span data-stu-id="413ae-149">The decryption result</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DecryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; DecryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DecryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DecryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DecryptAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-150">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-150">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-151">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-151">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-152">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-152">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-153">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-153">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-154">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="413ae-154">algorithm identifier.</span></span> <span data-ttu-id="413ae-155">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="413ae-155">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-157">Entschlüsselt einen einzelnen Block von verschlüsselten Daten.</span><span class="sxs-lookup"><span data-stu-id="413ae-157">Decrypts a single block of encrypted data.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-158">Der DECRYPT-Vorgang entschlüsselt einen wohlgeformten Block mit verschlüsseltem Text transformiert, die mit dem Ziel-Verschlüsselungsschlüssel und angegebenen Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-158">The DECRYPT operation decrypts a well-formed block of ciphertext using the target encryption key and specified algorithm.</span></span> <span data-ttu-id="413ae-159">Dieser Vorgang ist die Umkehrung des ENCRYPT-Vorgangs; nur ein einzelner Datenblock entschlüsselt werden kann, ist die Größe dieses Blocks vom Zielschlüssel und dem zu verwendenden Algorithmus abhängig.</span><span class="sxs-lookup"><span data-stu-id="413ae-159">This operation is the reverse of the ENCRYPT operation; only a single block of data may be decrypted, the size of this block is dependent on the target key and the algorithm to be used.</span></span> <span data-ttu-id="413ae-160">Der DECRYPT-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="413ae-160">The DECRYPT operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; DeleteCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-161">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-161">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-162">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-162">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-163">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-163">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-165">Löscht ein Zertifikat aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-165">Deletes a certificate from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-166">Löscht alle Versionen eines Objekts Zertifikat zusammen mit der zugeordneten Richtlinien.</span><span class="sxs-lookup"><span data-stu-id="413ae-166">Deletes all versions of a certificate object along with its associated policy.</span></span> <span data-ttu-id="413ae-167">Löschen von Zertifikat kann nicht verwendet werden, um einzelne Versionen eines Objekts Zertifikat zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="413ae-167">Delete certificate cannot be used to remove individual versions of a certificate object.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; DeleteCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateContactsAsync&gt;d__62))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-168">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-169">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-169">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-170">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-170">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-171">Löscht die Zertifikat-Kontakte für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-171">Deletes the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-172">Löscht die Zertifikat-Kontakte für ein Zertifikat für die angegebene schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-172">Deletes the certificate contacts for a specified key vault certificate.</span></span>
            <span data-ttu-id="413ae-173">Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-173">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; DeleteCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateIssuerAsync&gt;d__67))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-174">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-174">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-175">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-175">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="413ae-176">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="413ae-176">The name of the issuer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-178">Löscht den angegebenen Zertifikataussteller an.</span><span class="sxs-lookup"><span data-stu-id="413ae-178">Deletes the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-179">Der Vorgang DeleteCertificateIssuer werden endgültig gelöscht der Aussteller des angegebenen Zertifikats aus dem Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-179">The DeleteCertificateIssuer operation permanently removes the specified certificate issuer from the vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; DeleteCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteCertificateOperationAsync&gt;d__77))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-180">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-180">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-181">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-181">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-182">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-182">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-183">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-183">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-184">Löscht den Vorgang für ein angegebenes Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-184">Deletes the operation for a specified certificate.</span></span> <span data-ttu-id="413ae-185">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-185">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; DeleteKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteKeyAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-186">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-187">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-187">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-188">Der Name des Schlüssels zu löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-188">The name of the key to delete.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-189">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-189">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-190">Löscht einen Schlüssel eines beliebigen Typs aus dem Speicher in Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="413ae-190">Deletes a key of any type from storage in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-191">Der Löschvorgang Schlüssel kann nicht zum Entfernen einzelner Versionen eines Schlüssels verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-191">The delete key operation cannot be used to remove individual versions of a key.</span></span> <span data-ttu-id="413ae-192">Dieser Vorgang entfernt das kryptografische Material, das dem Schlüssel, was bedeutet, dass der Schlüssel nicht für Sign/Verify-, Wrap/Unwrap- oder Encrypt/Decrypt-Vorgänge verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-192">This operation removes the cryptographic material associated with the key, which means the key is not usable for Sign/Verify, Wrap/Unwrap or Encrypt/Decrypt operations.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; DeleteSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSasDefinitionAsync&gt;d__90))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-193">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-193">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-194">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-194">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-195">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-195">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="413ae-196">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-196">The name of the SAS definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-197">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-197">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-198">Löscht eine SAS-Definition aus einem angegebenen Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="413ae-198">Deletes a SAS definition from a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; DeleteSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteSecretAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-199">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-199">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-200">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-200">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-201">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-201">The name of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-202">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-202">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-203">Löscht einen geheimen Schlüssel aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-203">Deletes a secret from a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-204">Der DELETE-Vorgang gilt für alle geheimen Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="413ae-204">The DELETE operation applies to any secret stored in Azure Key Vault.</span></span>
            <span data-ttu-id="413ae-205">DELETE kann nicht für eine einzelne Version eines geheimen Schlüssels angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-205">DELETE cannot be applied to an individual version of a secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; DeleteStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.DeleteStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;DeleteStorageAccountAsync&gt;d__84))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-206">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-206">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-207">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-207">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-208">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-208">The name of the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-209">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-209">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-210">Löscht ein Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="413ae-210">Deletes a storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] plainText, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] plainText, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, keyIdentifier, algorithm, plainText, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="plainText" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="413ae-211">Der vollständige Schlüsselbezeichner</span><span class="sxs-lookup"><span data-stu-id="413ae-211">The full key identifier</span></span></param>
        <param name="algorithm"><span data-ttu-id="413ae-212">Der Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-212">The algorithm.</span></span> <span data-ttu-id="413ae-213">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeyEncryptionAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-213">For more information on possible algorithm types, see JsonWebKeyEncryptionAlgorithm.</span></span></param>
        <param name="plainText"><span data-ttu-id="413ae-214">Nur-text</span><span class="sxs-lookup"><span data-stu-id="413ae-214">The plain text</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-215">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-215">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-216">Verschlüsselt einen einzelnen Block von Daten an.</span><span class="sxs-lookup"><span data-stu-id="413ae-216">Encrypts a single block of data.</span></span> <span data-ttu-id="413ae-217">Die Menge der Daten, die verschlüsselt werden möglicherweise richtet sich nach den Zieltyp für den Schlüssel und den Verschlüsselungsalgorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-217">The amount of data that may be encrypted is determined by the target key type and the encryption algorithm.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-218">Der verschlüsselte text</span><span class="sxs-lookup"><span data-stu-id="413ae-218">The encrypted text</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncryptAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; EncryptAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EncryptAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.EncryptAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;EncryptAsync&gt;d__36))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-219">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-219">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-220">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-220">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-221">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-221">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-222">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-222">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-223">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="413ae-223">algorithm identifier.</span></span> <span data-ttu-id="413ae-224">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="413ae-224">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-225">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-225">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-226">Verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in einem schlüsseltresor gespeichert sind.</span><span class="sxs-lookup"><span data-stu-id="413ae-226">Encrypts an arbitrary sequence of bytes using an encryption key that is stored in a key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-227">Der ENCRYPT-Vorgang verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in Azure Key Vault gespeichert ist.</span><span class="sxs-lookup"><span data-stu-id="413ae-227">The ENCRYPT operation encrypts an arbitrary sequence of bytes using an encryption key that is stored in Azure Key Vault.</span></span> <span data-ttu-id="413ae-228">Beachten Sie, dass der ENCRYPT-Vorgang nur einen einzelnen Block von Daten unterstützt, deren Größe vom Zielschlüssel und den zu verwendenden Verschlüsselungsalgorithmus abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="413ae-228">Note that the ENCRYPT operation only supports a single block of data, the size of which is dependent on the target key and the encryption algorithm to be used.</span></span> <span data-ttu-id="413ae-229">Der ENCRYPT-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mithilfe der öffentliche Teil des Schlüssels ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="413ae-229">The ENCRYPT operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using public portion of the key.</span></span> <span data-ttu-id="413ae-230">Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.</span><span class="sxs-lookup"><span data-stu-id="413ae-230">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, certificateIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__22))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier"><span data-ttu-id="413ae-231">Die URL für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-231">The URL for the certificate.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-232">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-232">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-233">Ruft ein Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-233">Gets a certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-234">Das abgerufene Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-234">The retrieved certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-235">Die URL für den Tresor, der das Zertifikat enthält.</span><span class="sxs-lookup"><span data-stu-id="413ae-235">The URL for the vault containing the certificate.</span></span></param>
        <param name="certificateName"><span data-ttu-id="413ae-236">Der Name des Zertifikats in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-236">The name of the certificate in the given vault.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-237">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-237">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-238">Ruft ein Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-238">Gets a certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-239">Das abgerufene Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-239">The retrieved certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; GetCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateAsync&gt;d__74))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-240">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-240">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-241">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-241">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-242">Der Name des Zertifikats in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-242">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="413ae-243">Die Version des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-243">The version of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-244">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-244">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-245">Ruft Informationen zu einem angegebenen Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-245">Gets information about a specified certificate.</span></span> <span data-ttu-id="413ae-246">Autorisierung: erfordert die Zertifikate/Get-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-246">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; GetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateContactsAsync (operations, vaultBaseUrl, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateContactsAsync&gt;d__61))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-247">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-247">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-248">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-248">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-249">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-249">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-250">Listet die Kontakte Zertifikat für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-250">Lists the certificate contacts for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-251">Der GetCertificateContacts-Vorgang gibt den Satz von Zertifikat Kontakt Ressourcen im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-251">The GetCertificateContacts operation returns the set of certificate contact resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; GetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuerAsync&gt;d__66))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-252">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-252">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-253">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-253">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="413ae-254">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="413ae-254">The name of the issuer.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-255">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-255">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-256">Listet den Aussteller des angegebenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="413ae-256">Lists the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-257">Der Vorgang GetCertificateIssuer gibt das angegebene Zertifikat Aussteller Ressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-257">The GetCertificateIssuer operation returns the specified certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersAsync&gt;d__63))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-258">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-258">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-259">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-259">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-260">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-260">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-261">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-261">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-262">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-262">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-263">Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-263">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-264">Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-264">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateIssuersNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt; GetCertificateIssuersNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateIssuersNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateIssuersNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateIssuersNextAsync&gt;d__101))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateIssuerItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-265">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-265">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-266">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-266">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-267">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-267">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-268">Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-268">List certificate issuers for a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-269">Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-269">The GetCertificateIssuers operation returns the set of certificate issuer resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; GetCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateOperationAsync&gt;d__76))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-270">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-270">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-271">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-271">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-272">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-272">The name of the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-273">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-273">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-274">Ruft ein angegebenes Zertifikat zugeordneten Vorgangs ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-274">Gets the operation associated with a specified certificate.</span></span> <span data-ttu-id="413ae-275">Autorisierung: erfordert die Zertifikate/Get-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-275">Authorization: requires the certificates/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; GetCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatePolicyAsync&gt;d__71))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-276">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-276">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-277">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-277">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-278">Der Name des Zertifikats in einer bestimmten schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-278">The name of the certificate in a given key vault.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-279">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-279">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-280">Listet die Richtlinie für ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="413ae-280">Lists the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-281">Der Vorgang GetCertificatePolicy gibt das angegebene Zertifikat Richtlinie Ressourcen im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-281">The GetCertificatePolicy operation returns the specified certificate policy resources in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesAsync&gt;d__58))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-282">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-282">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-283">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-283">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-284">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-284">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-285">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-285">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-286">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-286">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-287">Liste der Zertifikate in einem angegebenen Schlüssel Tresor</span><span class="sxs-lookup"><span data-stu-id="413ae-287">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-288">Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-288">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificatesNextAsync&gt;d__100))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-289">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-289">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-290">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-290">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-291">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-291">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-292">Liste der Zertifikate in einem angegebenen Schlüssel Tresor</span><span class="sxs-lookup"><span data-stu-id="413ae-292">List certificates in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-293">Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-293">The GetCertificates operation returns the set of certificates resources in the specified key vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsAsync (operations, vaultBaseUrl, certificateName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsAsync&gt;d__70))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-294">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-294">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-295">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-295">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-296">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-296">The name of the certificate.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-297">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-297">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-298">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-298">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-299">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-299">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-300">Liste der Versionen eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="413ae-300">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-301">Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-301">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetCertificateVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt; GetCertificateVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetCertificateVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetCertificateVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetCertificateVersionsNextAsync&gt;d__102))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.CertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-302">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-302">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-303">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-303">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-304">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-304">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-305">Liste der Versionen eines Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="413ae-305">List the versions of a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-306">Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor</span><span class="sxs-lookup"><span data-stu-id="413ae-306">The GetCertificateVersions operation returns the versions of a certificate in the specified key vault</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt; GetDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificateAsync&gt;d__80))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-307">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-307">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-308">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-308">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-309">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-309">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-310">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-310">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-311">Ruft Informationen über das angegebene gelöschten Zertifikat ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-311">Retrieves information about the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-312">Mit dem Vorgang GetDeletedCertificate abgerufen, die gelöschte Zertifikatinformationen sowie seiner Attribute, z. B. Aufbewahrungszeitraum, geplante permanent löschen und die aktuelle Ebene der Löschvorgang Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="413ae-312">The GetDeletedCertificate operation retrieves the deleted certificate information plus its attributes, such as retention interval, scheduled permanent deletion and the current deletion recovery level.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesAsync&gt;d__79))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-313">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-313">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-314">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-314">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-315">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-315">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-316">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-316">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-317">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-317">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-318">Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.</span><span class="sxs-lookup"><span data-stu-id="413ae-318">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-319">Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-319">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedCertificatesNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt; GetDeletedCertificatesNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedCertificatesNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedCertificatesNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedCertificatesNextAsync&gt;d__103))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedCertificateItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-320">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-320">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-321">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-321">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-322">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-322">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-323">Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.</span><span class="sxs-lookup"><span data-stu-id="413ae-323">Lists the deleted certificates in the specified vault, currently available for recovery.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-324">Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-324">The GetDeletedCertificates operation retrieves the certificates in the current vault which are in a deleted state and ready for recovery or purging.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt; GetDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeyAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-325">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-325">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-326">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-326">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-327">Der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-327">The name of the key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-328">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-328">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-329">Ruft ab, die gelöschte Schlüsselinformationen sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="413ae-329">Retrieves the deleted key information plus its attributes.</span></span> <span data-ttu-id="413ae-330">Autorisierung: Ist der Schlüssel/Get-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-330">Authorization: Requires the keys/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysAsync&gt;d__42))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-331">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-331">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-332">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-332">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-333">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-333">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-334">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-334">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-335">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-335">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-336">Liste gelöscht Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-336">List deleted keys in the specified vault.</span></span> <span data-ttu-id="413ae-337">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-337">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt; GetDeletedKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedKeysNextAsync&gt;d__96))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedKeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-338">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-338">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-339">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-339">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-340">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-340">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-341">Liste gelöscht Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-341">List deleted keys in the specified vault.</span></span> <span data-ttu-id="413ae-342">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-342">Authorization: Requires the keys/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt; GetDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-343">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-343">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-344">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-344">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-345">Der Name des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-345">The name of the secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-346">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-346">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-347">Ruft ab, die gelöschte geheimen Informationen sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="413ae-347">Retrieves the deleted secret information plus its attributes.</span></span>
            <span data-ttu-id="413ae-348">Autorisierung: ist der geheime Schlüssel/Get-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-348">Authorization: requires the secrets/get permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsAsync&gt;d__52))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-349">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-349">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-350">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-350">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-351">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-351">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-352">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-352">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-353">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-353">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-354">Liste gelöscht geheime Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-354">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="413ae-355">Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-355">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeletedSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt; GetDeletedSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDeletedSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetDeletedSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetDeletedSecretsNextAsync&gt;d__99))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.DeletedSecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-356">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-356">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-357">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-357">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-358">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-358">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-359">Liste gelöscht geheime Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-359">List deleted secrets in the specified vault.</span></span> <span data-ttu-id="413ae-360">Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-360">Authorization: requires the secrets/list permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, keyIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="413ae-361">Der Schlüsselbezeichner</span><span class="sxs-lookup"><span data-stu-id="413ae-361">The key identifier</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-362">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-362">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-363">Ruft den öffentlichen Teil eines Schlüssels sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="413ae-363">Retrieves the public portion of a key plus its attributes</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-364">Eine KeyBundle des Schlüssels und dessen Attribute</span><span class="sxs-lookup"><span data-stu-id="413ae-364">A KeyBundle of the key and its attributes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-365">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</span><span class="sxs-lookup"><span data-stu-id="413ae-365">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="413ae-366">der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-366">The key name</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-367">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-367">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-368">Ruft den öffentlichen Teil eines Schlüssels sowie seiner Attribute.</span><span class="sxs-lookup"><span data-stu-id="413ae-368">Retrieves the public portion of a key plus its attributes</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-369">Eine KeyBundle des Schlüssels und dessen Attribute</span><span class="sxs-lookup"><span data-stu-id="413ae-369">A KeyBundle of the key and its attributes</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; GetKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-370">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-370">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-371">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-371">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-372">Der Name des abzurufenden Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-372">The name of the key to get.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-373">Hinzufügen der "Version"-Parameter ruft eine bestimmte Version eines Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-373">Adding the version parameter retrieves a specific version of a key.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-374">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-374">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-375">Ruft den öffentlichen Teil eines gespeicherten Schlüssels ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-375">Gets the public part of a stored key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-376">Die wichtigsten Get-Vorgang gilt zwar für alle Schlüsseltypen.</span><span class="sxs-lookup"><span data-stu-id="413ae-376">The get key operation is applicable to all key types.</span></span> <span data-ttu-id="413ae-377">Wenn es sich bei der angeforderte Schlüssel symmetrisch ist, wird keine Schlüsselmaterial in der Antwort freigegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-377">If the requested key is symmetric, then no key material is released in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-378">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-378">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-379">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-379">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-380">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-380">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-381">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-381">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-382">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-382">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-383">Liste von Schlüsseln in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-383">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-384">Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten.</span><span class="sxs-lookup"><span data-stu-id="413ae-384">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="413ae-385">Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-385">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="413ae-386">Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="413ae-386">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="413ae-387">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-387">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeysNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeysNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeysNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeysNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeysNextAsync&gt;d__95))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-388">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-388">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-389">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-389">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-390">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-390">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-391">Liste von Schlüsseln in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-391">List keys in the specified vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-392">Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten.</span><span class="sxs-lookup"><span data-stu-id="413ae-392">Retrieves a list of the keys in the Key Vault as JSON Web Key structures that contain the public part of a stored key.</span></span> <span data-ttu-id="413ae-393">Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-393">The LIST operation is applicable to all key types, however only the base key identifier,attributes, and tags are provided in the response.</span></span> <span data-ttu-id="413ae-394">Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="413ae-394">Individual versions of a key are not listed in the response.</span></span> <span data-ttu-id="413ae-395">Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-395">Authorization: Requires the keys/list permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsAsync (operations, vaultBaseUrl, keyName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsAsync&gt;d__32))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-396">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-396">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-397">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-397">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-398">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-398">The name of the key.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-399">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-399">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-400">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-400">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-401">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-401">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-402">Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-402">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-403">Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-403">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetKeyVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt; GetKeyVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetKeyVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetKeyVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetKeyVersionsNextAsync&gt;d__94))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.KeyItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-404">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-404">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-405">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-405">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-406">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-406">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-407">Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-407">Retrieves a list of individual key versions with the same key name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-408">Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-408">The full key identifier, attributes, and tags are provided in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPendingCertificateSigningRequestAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;string&gt; GetPendingCertificateSigningRequestAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;string&gt; GetPendingCertificateSigningRequestAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetPendingCertificateSigningRequestAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetPendingCertificateSigningRequestAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetPendingCertificateSigningRequestAsync&gt;d__26))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-409">Die URL für den Tresor mit dem Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-409">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="413ae-410">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-410">The name of the certificate</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-411">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-411">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-412">Ruft Base64 ausstehende zertifikatsignieranforderung (PKCS bis 10)</span><span class="sxs-lookup"><span data-stu-id="413ae-412">Gets the Base64 pending certificate signing request (PKCS-10)</span></span> 
            </summary>
        <returns><span data-ttu-id="413ae-413">Die ausstehende zertifikatsignieranforderung als Base64-codierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="413ae-413">The pending certificate signing request as Base64 encoded string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; GetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionAsync&gt;d__91))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-414">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-414">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-415">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-415">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-416">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-416">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="413ae-417">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-417">The name of the SAS definition.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-418">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-418">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-419">Ruft Informationen über eine SAS-Definition für das angegebene Speicherkonto ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-419">Gets information about a SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsAsync (operations, vaultBaseUrl, storageAccountName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsAsync&gt;d__89))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-420">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-420">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-421">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-421">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-422">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-422">The name of the storage account.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-423">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-423">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-424">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-424">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-425">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-425">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-426">Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="413ae-426">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSasDefinitionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt; GetSasDefinitionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSasDefinitionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSasDefinitionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSasDefinitionsNextAsync&gt;d__105))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-427">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-427">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-428">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-428">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-429">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-429">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-430">Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.</span><span class="sxs-lookup"><span data-stu-id="413ae-430">List storage SAS definitions for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, secretIdentifier, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier"><span data-ttu-id="413ae-431">Die URL für den geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-431">The URL for the secret.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-432">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-432">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-433">Ruft einen geheimen Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-433">Gets a secret.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-434">Eine Antwortnachricht, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="413ae-434">A response message containing the secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-435">Die URL für den Tresor, der die geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="413ae-435">The URL for the vault containing the secrets.</span></span></param>
        <param name="secretName"><span data-ttu-id="413ae-436">Der Name der geheime Schlüssel in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-436">The name the secret in the given vault.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-437">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-437">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-438">Ruft einen geheimen Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-438">Gets a secret.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-439">Eine Antwortnachricht, die den geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="413ae-439">A response message containing the secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; GetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-440">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-440">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-441">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-441">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-442">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-442">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="413ae-443">die Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-443">The version of the secret.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-444">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-444">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-445">Erhalten Sie einen angegebenen Schlüssel aus einem angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-445">Get a specified secret from a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-446">Die GET-Vorgang gilt zwar für alle geheimen Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="413ae-446">The GET operation is applicable to any secret stored in Azure Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsAsync&gt;d__50))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-447">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-447">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-448">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-448">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-449">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-449">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-450">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-450">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-451">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-451">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-452">Auflisten geheimer Schlüssel in einer angegebenen Key Vault.</span><span class="sxs-lookup"><span data-stu-id="413ae-452">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-453">Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-453">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="413ae-454">Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="413ae-454">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretsNextAsync&gt;d__97))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-455">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-455">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-456">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-456">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-457">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-457">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-458">Auflisten geheimer Schlüssel in einer angegebenen Key Vault.</span><span class="sxs-lookup"><span data-stu-id="413ae-458">List secrets in a specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-459">Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-459">The LIST operation is applicable to the entire vault, however only the base secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="413ae-460">Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="413ae-460">Individual secret versions are not listed in the response.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsAsync (operations, vaultBaseUrl, secretName, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-461">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-461">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-462">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-462">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-463">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-463">The name of the secret.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-464">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-464">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-465">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-465">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-466">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-466">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-467">Liste der Versionen des angegebenen geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-467">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-468">Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-468">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="413ae-469">Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-469">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="413ae-470">Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="413ae-470">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSecretVersionsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt; GetSecretVersionsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetSecretVersionsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetSecretVersionsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetSecretVersionsNextAsync&gt;d__98))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.SecretItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-471">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-471">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-472">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-472">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-473">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-473">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-474">Liste der Versionen des angegebenen geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-474">List the versions of the specified secret.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-475">Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-475">The LIST VERSIONS operation can be applied to all versions having the same secret name in the same key vault.</span></span> <span data-ttu-id="413ae-476">Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-476">The full secret identifier and attributes are provided in the response.</span></span> <span data-ttu-id="413ae-477">Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.</span><span class="sxs-lookup"><span data-stu-id="413ae-477">No values are returned for the secrets and only current versions of a secret are listed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; GetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-478">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-478">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-479">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-479">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-480">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-480">The name of the storage account.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-481">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-481">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-482">Ruft Informationen über ein angegebenes Speicherkonto ab.</span><span class="sxs-lookup"><span data-stu-id="413ae-482">Gets information about a specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Nullable&lt;int&gt; maxresults = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, valuetype System.Nullable`1&lt;int32&gt; maxresults, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsAsync (operations, vaultBaseUrl, maxresults, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsAsync&gt;d__83))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="maxresults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-483">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-483">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-484">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-484">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="maxresults">
            <span data-ttu-id="413ae-485">Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-485">Maximum number of results to return in a page.</span></span> <span data-ttu-id="413ae-486">Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.</span><span class="sxs-lookup"><span data-stu-id="413ae-486">If not specified the service will return up to 25 results.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-487">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-487">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-488">Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="413ae-488">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetStorageAccountsNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt; GetStorageAccountsNextAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetStorageAccountsNextAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.GetStorageAccountsNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;GetStorageAccountsNextAsync&gt;d__104))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.KeyVault.Models.StorageAccountItem&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-489">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-489">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="413ae-490">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-490">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-491">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-491">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-492">Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden</span><span class="sxs-lookup"><span data-stu-id="413ae-492">List storage accounts managed by specified key vault</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection certificateCollection, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, certificateCollection, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__24))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateCollection" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-493">Die URL für den Tresor mit dem Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-493">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="413ae-494">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-494">The name of the certificate</span></span></param>
        <param name="certificateCollection"><span data-ttu-id="413ae-495">Die Auflistung der Zertifikate mit dem privaten Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-495">The certificate collection with the private key</span></span></param>
        <param name="certificatePolicy"><span data-ttu-id="413ae-496">Die Verwaltungsrichtlinie für das Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-496">The management policy for the certificate</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="413ae-497">Die Attribute des Zertifikats (optional)</span><span class="sxs-lookup"><span data-stu-id="413ae-497">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-498">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-498">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-499">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-499">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-500">Importiert eine neue Zertifikatversion an.</span><span class="sxs-lookup"><span data-stu-id="413ae-500">Imports a new certificate version.</span></span> <span data-ttu-id="413ae-501">Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-501">If this is the first version, the certificate resource is created.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-502">Importierte Zertifikat Paket in den Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-502">Imported certificate bundle to the vault.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password = null, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; ImportCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string base64EncodedCertificate, string password, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportCertificateAsync (operations, vaultBaseUrl, certificateName, base64EncodedCertificate, password, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportCertificateAsync&gt;d__69))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="base64EncodedCertificate" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-503">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-503">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-504">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-504">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-505">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-505">The name of the certificate.</span></span>
            </param>
        <param name="base64EncodedCertificate">
            <span data-ttu-id="413ae-506">Base64-codierte Darstellung des Objekts Zertifikat zu importieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-506">Base64 encoded representation of the certificate object to import.</span></span> <span data-ttu-id="413ae-507">Dieses Zertifikat muss den privaten Schlüssel enthalten.</span><span class="sxs-lookup"><span data-stu-id="413ae-507">This certificate needs to contain the private key.</span></span>
            </param>
        <param name="password">
            <span data-ttu-id="413ae-508">Wenn der private Schlüssel im base64EncodedCertificate verschlüsselt ist, können Sie das Kennwort für die Verschlüsselung verwendete.</span><span class="sxs-lookup"><span data-stu-id="413ae-508">If the private key in base64EncodedCertificate is encrypted, the password used for encryption.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="413ae-509">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-509">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="413ae-510">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="413ae-510">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-511">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-511">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-512">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-512">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-513">Wird ein Zertifikat in einem angegebenen schlüsseltresor importiert.</span><span class="sxs-lookup"><span data-stu-id="413ae-513">Imports a certificate into a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-514">Importiert ein vorhandenes gültiges Zertifikat ist, einen privaten Schlüssel enthält, in Azure Key Vault.</span><span class="sxs-lookup"><span data-stu-id="413ae-514">Imports an existing valid certificate, containing a private key, into Azure Key Vault.</span></span> <span data-ttu-id="413ae-515">Das Zertifikat importiert werden sollen, kann im PFX oder PEM-Format sein.</span><span class="sxs-lookup"><span data-stu-id="413ae-515">The certificate to be imported can be in either PFX or PEM format.</span></span> <span data-ttu-id="413ae-516">Wenn das Zertifikat im PEM-Format ist muss die PEM-Datei enthalten, den Schlüssel als auch X509 Zertifikate.</span><span class="sxs-lookup"><span data-stu-id="413ae-516">If the certificate is in PEM format the PEM file must contain the key as well as x509 certificates.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, Nullable&lt;bool&gt; importToHardware = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.Models.KeyBundle keyBundle, valuetype System.Nullable`1&lt;bool&gt; importToHardware, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.KeyBundle,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.KeyBundle * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, keyBundle, importToHardware, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyBundle" Type="Microsoft.Azure.KeyVault.Models.KeyBundle" />
        <Parameter Name="importToHardware" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-517">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</span><span class="sxs-lookup"><span data-stu-id="413ae-517">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="413ae-518">der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-518">The key name</span></span></param>
        <param name="keyBundle"> <span data-ttu-id="413ae-519">Key-Paket</span><span class="sxs-lookup"><span data-stu-id="413ae-519">Key bundle</span></span> </param>
        <param name="importToHardware"><span data-ttu-id="413ae-520">Angibt, ob als Hardwareschlüssel (HSM) oder Softwareschlüssel importieren</span><span class="sxs-lookup"><span data-stu-id="413ae-520">Whether to import as a hardware key (HSM) or software key</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="413ae-521">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-521">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-522">Importiert einen Schlüssel in den angegebenen Tresor</span><span class="sxs-lookup"><span data-stu-id="413ae-522">Imports a key into the specified vault</span></span>
            </summary>
        <returns> <span data-ttu-id="413ae-523">Importierte Schlüssel Paket in den Tresor</span><span class="sxs-lookup"><span data-stu-id="413ae-523">Imported key bundle to the vault</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, Nullable&lt;bool&gt; hsm = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; ImportKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, class Microsoft.Azure.KeyVault.WebKey.JsonWebKey key, valuetype System.Nullable`1&lt;bool&gt; hsm, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.WebKey.JsonWebKey,System.Nullable{System.Boolean},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ImportKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.WebKey.JsonWebKey * Nullable&lt;bool&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.ImportKeyAsync (operations, vaultBaseUrl, keyName, key, hsm, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;ImportKeyAsync&gt;d__28))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="key" Type="Microsoft.Azure.KeyVault.WebKey.JsonWebKey" />
        <Parameter Name="hsm" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-524">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-524">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-525">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-525">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-526">Der Name für den importierten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-526">Name for the imported key.</span></span>
            </param>
        <param name="key">
            <span data-ttu-id="413ae-527">Das Json Web key</span><span class="sxs-lookup"><span data-stu-id="413ae-527">The Json web key</span></span>
            </param>
        <param name="hsm">
            <span data-ttu-id="413ae-528">Ob als Hardwareschlüssel (HSM) oder Softwareschlüssel zu importieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-528">Whether to import as a hardware key (HSM) or software key.</span></span>
            </param>
        <param name="keyAttributes">
            <span data-ttu-id="413ae-529">Die schlüsselverwaltung-Attribute.</span><span class="sxs-lookup"><span data-stu-id="413ae-529">The key management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-530">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-530">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-531">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-531">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-532">Importiert einen extern erstellten Schlüssel, speichert ihn und gibt Schlüsselparameter und Attribute an den Client.</span><span class="sxs-lookup"><span data-stu-id="413ae-532">Imports an externally created key, stores it, and returns key parameters and attributes to the client.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-533">Beim Importieren kann verwendet werden, um jedes Schlüsseltyps in Azure Key Vault zu importieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-533">The import key operation may be used to import any key type into an Azure Key Vault.</span></span> <span data-ttu-id="413ae-534">Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-534">If the named key already exists, Azure Key Vault creates a new version of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Collections.Generic.IList&lt;byte[]&gt; x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Collections.Generic.IList`1&lt;unsigned int8[]&gt; x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Collections.Generic.IList{System.Byte[]},Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Collections.Generic.IList&lt;byte[]&gt; * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__78))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Collections.Generic.IList&lt;System.Byte[]&gt;" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-535">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-535">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-536">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-536">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-537">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-537">The name of the certificate.</span></span>
            </param>
        <param name="x509Certificates">
            <span data-ttu-id="413ae-538">Das Zertifikat oder der Zertifikatskette zum Zusammenführen.</span><span class="sxs-lookup"><span data-stu-id="413ae-538">The certificate or the certificate chain to merge.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="413ae-539">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="413ae-539">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-540">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-540">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-541">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-541">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-542">Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.</span><span class="sxs-lookup"><span data-stu-id="413ae-542">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-543">Der Vorgang MergeCertificate führt das Zusammenführen von einem Zertifikat oder der Zertifikatkette mit einem Schlüsselpaar, die zurzeit in den Dienst verfügbar.</span><span class="sxs-lookup"><span data-stu-id="413ae-543">The MergeCertificate operation performs the merging of a certificate or certificate chain with a key pair currently available in the service.</span></span>
            <span data-ttu-id="413ae-544">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-544">Authorization: requires the certificates/update permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MergeCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; MergeCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class System.Security.Cryptography.X509Certificates.X509Certificate2Collection x509Certificates, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Security.Cryptography.X509Certificates.X509Certificate2Collection,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member MergeCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Security.Cryptography.X509Certificates.X509Certificate2Collection * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.MergeCertificateAsync (operations, vaultBaseUrl, certificateName, x509Certificates, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;MergeCertificateAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="x509Certificates" Type="System.Security.Cryptography.X509Certificates.X509Certificate2Collection" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-545">Die URL für den Tresor mit dem Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-545">The URL for the vault containing the certificate</span></span></param>
        <param name="certificateName"><span data-ttu-id="413ae-546">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-546">The name of the certificate</span></span></param>
        <param name="x509Certificates"><span data-ttu-id="413ae-547">Das Zertifikat oder der Kette Certificte zusammenführen</span><span class="sxs-lookup"><span data-stu-id="413ae-547">The certificate or the certificte chain to merge</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="413ae-548">Die Attribute des Zertifikats (optional)</span><span class="sxs-lookup"><span data-stu-id="413ae-548">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-549">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-549">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-550">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-550">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-551">Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.</span><span class="sxs-lookup"><span data-stu-id="413ae-551">Merges a certificate or a certificate chain with a key pair existing on the server.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-552">Eine Antwortnachricht mit dem zusammengeführten Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-552">A response message containing the merged certificate.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__20))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-553">Die RecoveryId des gelöschten Zertifikats löschen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-553">The recoveryId of the deleted certificate, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-554">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-554">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-555">Löscht das gelöschte Zertifikat sofort an.</span><span class="sxs-lookup"><span data-stu-id="413ae-555">Purges the deleted certificate with immediate effect.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-556">Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-556">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedCertificateAsync&gt;d__81))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-557">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-557">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-558">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-558">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-559">Der Name des Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-559">The name of the certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-560">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-560">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-561">Dauerhaft löscht das angegebene Zertifikat gelöschte.</span><span class="sxs-lookup"><span data-stu-id="413ae-561">Permanently deletes the specified deleted certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-562">Der Vorgang PurgeDeletedCertificate führt eine Löschung des angegebenen Zertifikats, ohne Möglichkeit zur Wiederherstellung.</span><span class="sxs-lookup"><span data-stu-id="413ae-562">The PurgeDeletedCertificate operation performs an irreversible deletion of the specified certificate, without possibility for recovery.</span></span> <span data-ttu-id="413ae-563">Der Vorgang ist nicht verfügbar, wenn die Wiederherstellung Ebene keine "Purgeable" angibt.</span><span class="sxs-lookup"><span data-stu-id="413ae-563">The operation is not available if the recovery level does not specify 'Purgeable'.</span></span>
            <span data-ttu-id="413ae-564">Erfordert die explizite erteilen der Berechtigung "löschen".</span><span class="sxs-lookup"><span data-stu-id="413ae-564">Requires the explicit granting of the 'purge' permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-565">Die RecoveryId des gelöschten Schlüssels zurückgegeben löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-565">The recoveryId of the deleted key, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-566">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-566">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-567">Löscht den gelöschten Schlüssel sofort an.</span><span class="sxs-lookup"><span data-stu-id="413ae-567">Purges the deleted key immediately.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-568">Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-568">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedKeyAsync&gt;d__44))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-569">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-569">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-570">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-570">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-571">Der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-571">The name of the key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-572">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-572">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-573">Dauerhaft löscht den angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-573">Permanently deletes the specified key.</span></span> <span data-ttu-id="413ae-574">d. h. löscht den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-574">aka purges the key.</span></span> <span data-ttu-id="413ae-575">Autorisierung: Ist der Schlüssel/löschen-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-575">Authorization: Requires the keys/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__18))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-576">Die RecoveryId des gelöschten geheimen Schlüssels zurückgegeben löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-576">The recoveryId of the deleted secret, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-577">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-577">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-578">Löscht den gelöschten geheimen sofort an.</span><span class="sxs-lookup"><span data-stu-id="413ae-578">Purges the deleted secret immediately.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-579">Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-579">Task representing the asynchronous execution of this request.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PurgeDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PurgeDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PurgeDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.PurgeDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;PurgeDeletedSecretAsync&gt;d__54))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-580">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-580">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-581">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-581">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-582">Der Name des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-582">The name of the secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-583">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-583">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-584">Dauerhaft löscht den angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-584">Permanently deletes the specified secret.</span></span> <span data-ttu-id="413ae-585">AKA löscht den geheimen Schlüssel ein.</span><span class="sxs-lookup"><span data-stu-id="413ae-585">aka purges the secret.</span></span>
            <span data-ttu-id="413ae-586">Autorisierung: ist der geheime Schlüssel/löschen-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-586">Authorization: requires the secrets/purge permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-587">Die RecoveryId des gelöschten Zertifikats löschen zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-587">The recoveryId of the deleted certificate, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-588">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-588">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-589">Wird das gelöschte Zertifikat wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-589">Recovers the deleted certificate.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-590">Eine Antwortnachricht mit dem wiederhergestellten Zertifikat</span><span class="sxs-lookup"><span data-stu-id="413ae-590">A response message containing the recovered certificate</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; RecoverDeletedCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedCertificateAsync (operations, vaultBaseUrl, certificateName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedCertificateAsync&gt;d__82))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-591">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-591">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-592">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-592">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-593">Der Name des gelöschten Zertifikats</span><span class="sxs-lookup"><span data-stu-id="413ae-593">The name of the deleted certificate</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-594">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-594">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-595">Wird das gelöschte Zertifikat an die aktuelle Version unter Zertifikatinhaber wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-595">Recovers the deleted certificate back to its current version under /certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-596">Die RecoverDeletedCertificate werden die Umkehrung der Löschvorgang durchgeführt.</span><span class="sxs-lookup"><span data-stu-id="413ae-596">The RecoverDeletedCertificate operation performs the reversal of the Delete operation.</span></span> <span data-ttu-id="413ae-597">Der Vorgang gilt in Tresoren, die für die Soft-Delete aktiviert und während das beibehaltungsintervall (verfügbar in der gelöschten Zertifikats Attribute) ausgegeben werden muss.</span><span class="sxs-lookup"><span data-stu-id="413ae-597">The operation is applicable in vaults enabled for soft-delete, and must be issued during the retention interval (available in the deleted certificate's attributes).</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-598">Die RecoveryId des gelöschten Schlüssels zurückgegeben löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-598">The recoveryId of the deleted key, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-599">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-599">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-600">Wird den gelöschten Schlüssel wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-600">Recovers the deleted key.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-601">Eine Antwortnachricht mit dem wiederhergestellten Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-601">A response message containing the recovered key</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RecoverDeletedKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedKeyAsync (operations, vaultBaseUrl, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedKeyAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-602">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-602">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-603">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-603">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-604">Der Name des gelöschten Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-604">The name of the deleted key</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-605">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-605">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-606">Wird die gelöschten Schlüssel wieder mit ihrer aktuellen Version unter/Keys wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-606">Recovers the deleted key back to its current version under /keys.</span></span>
            <span data-ttu-id="413ae-607">Autorisierung: Ist der Schlüssel/Recover-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-607">Authorization: Requires the keys/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string recoveryId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, recoveryId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="recoveryId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="recoveryId"><span data-ttu-id="413ae-608">Die RecoveryId des gelöschten geheimen Schlüssels zurückgegeben löschen.</span><span class="sxs-lookup"><span data-stu-id="413ae-608">The recoveryId of the deleted secret, returned from deletion.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-609">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-609">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-610">Wird den gelöschten geheime Schlüssel wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-610">Recovers the deleted secret.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-611">Eine Antwortnachricht, die den wiederhergestellten geheimen Schlüssel enthält.</span><span class="sxs-lookup"><span data-stu-id="413ae-611">A response message containing the recovered secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecoverDeletedSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RecoverDeletedSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RecoverDeletedSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RecoverDeletedSecretAsync (operations, vaultBaseUrl, secretName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RecoverDeletedSecretAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-612">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-612">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-613">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-613">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-614">Der Name des gelöschten geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-614">The name of the deleted secret</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-615">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-615">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-616">Wird die gelöschte geheimen wieder mit ihrer aktuellen Version unter "/ Secrets" wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-616">Recovers the deleted secret back to its current version under /secrets.</span></span>
            <span data-ttu-id="413ae-617">Autorisierung: ist der geheime Schlüssel/Recover-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-617">Authorization: requires the secrets/recover permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegenerateStorageAccountKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; RegenerateStorageAccountKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string keyName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegenerateStorageAccountKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RegenerateStorageAccountKeyAsync (operations, vaultBaseUrl, storageAccountName, keyName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RegenerateStorageAccountKeyAsync&gt;d__88))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-618">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-618">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-619">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-619">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-620">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-620">The name of the storage account.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-621">Name des Speicherkontos Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-621">The storage account key name.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-622">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-622">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-623">Generiert die angegebenen Schlüsselwert für das angegebene Speicherkonto neu.</span><span class="sxs-lookup"><span data-stu-id="413ae-623">Regenerates the specified key value for the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] keyBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; RestoreKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] keyBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreKeyAsync (operations, vaultBaseUrl, keyBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreKeyAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-624">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-624">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-625">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-625">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyBundleBackup">
            <span data-ttu-id="413ae-626">Der Blob-Sicherungsdatei eine wichtige Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="413ae-626">The backup blob associated with a key bundle.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-627">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-627">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-628">Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.</span><span class="sxs-lookup"><span data-stu-id="413ae-628">Restores a backed up key to a vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-629">Importiert einen zuvor gesicherten Schlüssel in Azure Key Vault, den Schlüssel, der den Schlüsselbezeichner, Attribute und Zugriffssteuerungsrichtlinien wiederhergestellt.</span><span class="sxs-lookup"><span data-stu-id="413ae-629">Imports a previously backed up key into Azure Key Vault, restoring the key, its key identifier, attributes and access control policies.</span></span> <span data-ttu-id="413ae-630">Der Wiederherstellungsvorgang kann verwendet werden, um einen zuvor gesicherten Schlüssel zu importieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-630">The RESTORE operation may be used to import a previously backed up key.</span></span> <span data-ttu-id="413ae-631">Einzelne Versionen eines Schlüssels können nicht wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-631">Individual versions of a key cannot be restored.</span></span> <span data-ttu-id="413ae-632">Der Schlüssel wird in seiner Gesamtheit mit demselben Schlüsselnamen wiederhergestellt, wie er hatte, als er gesichert wurde.</span><span class="sxs-lookup"><span data-stu-id="413ae-632">The key is restored in its entirety with the same key name as it had when it was backed up.</span></span> <span data-ttu-id="413ae-633">Wenn Sie nicht den Namen des Schlüssels im zielschlüsseltresor verfügbar ist, wird der RESTORE-Vorgang abgelehnt.</span><span class="sxs-lookup"><span data-stu-id="413ae-633">If the key name is not available in the target Key Vault, the RESTORE operation will be rejected.</span></span> <span data-ttu-id="413ae-634">Während der Schlüsselname während der Wiederherstellung beibehalten wird, ändert die endgültige Schlüsselbezeichner, wenn der Schlüssel in einem anderen Tresor wiederhergestellt wird.</span><span class="sxs-lookup"><span data-stu-id="413ae-634">While the key name is retained during restore, the final key identifier will change if the key is restored to a different vault.</span></span> <span data-ttu-id="413ae-635">Wiederherstellen werden alle Versionen wiederherstellen und erhält die Versionsbezeichner.</span><span class="sxs-lookup"><span data-stu-id="413ae-635">Restore will restore all versions and preserve version identifiers.</span></span> <span data-ttu-id="413ae-636">Der RESTORE-Vorgang unterliegt sicherheitseinschränkungen: das Ziel Key Vault muss wie Key Vault Benutzer RESTORE-Berechtigung im zielschlüsseltresor nicht über die Quelle muss durch den gleichen Microsoft Azure-Abonnement besitzen.</span><span class="sxs-lookup"><span data-stu-id="413ae-636">The RESTORE operation is subject to security constraints: The target Key Vault must be owned by the same Microsoft Azure Subscription as the source Key Vault The user must have RESTORE permission in the target Key Vault.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, byte[] secretBundleBackup, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; RestoreSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, unsigned int8[] secretBundleBackup, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.RestoreSecretAsync (operations, vaultBaseUrl, secretBundleBackup, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;RestoreSecretAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-637">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-637">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-638">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-638">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretBundleBackup">
            <span data-ttu-id="413ae-639">Der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="413ae-639">The backup blob associated with a secret bundle.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-640">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-640">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-641">Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.</span><span class="sxs-lookup"><span data-stu-id="413ae-641">Restores a backed up secret to a vault.</span></span> <span data-ttu-id="413ae-642">Autorisierung: ist der geheime Schlüssel/Restore-Berechtigung erforderlich.</span><span class="sxs-lookup"><span data-stu-id="413ae-642">Authorization: requires the secrets/restore permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateContactsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, Microsoft.Azure.KeyVault.Models.Contacts contacts, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.Contacts&gt; SetCertificateContactsAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, class Microsoft.Azure.KeyVault.Models.Contacts contacts, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.Contacts,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateContactsAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.Contacts * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateContactsAsync (operations, vaultBaseUrl, contacts, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateContactsAsync&gt;d__60))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.Contacts&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="contacts" Type="Microsoft.Azure.KeyVault.Models.Contacts" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-643">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-643">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-644">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-644">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="contacts">
            <span data-ttu-id="413ae-645">Die Kontakte für das Zertifikat des Key Vault.</span><span class="sxs-lookup"><span data-stu-id="413ae-645">The contacts for the key vault certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-646">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-646">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-647">Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="413ae-647">Sets the certificate contacts for the specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-648">Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="413ae-648">Sets the certificate contacts for the specified key vault.</span></span> <span data-ttu-id="413ae-649">Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-649">Authorization: requires the certificates/managecontacts permission.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; SetCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetCertificateIssuerAsync&gt;d__64))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-650">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-650">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-651">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-651">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="413ae-652">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="413ae-652">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="413ae-653">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="413ae-653">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="413ae-654">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="413ae-654">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="413ae-655">Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-655">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="413ae-656">Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="413ae-656">Attributes of the issuer object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-657">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-657">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-658">Legt den angegebenen Zertifikataussteller fest.</span><span class="sxs-lookup"><span data-stu-id="413ae-658">Sets the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-659">Der Vorgang SetCertificateIssuer fügt hinzu oder aktualisiert den Aussteller des angegebenen Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-659">The SetCertificateIssuer operation adds or updates the specified certificate issuer.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; SetSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSasDefinitionAsync&gt;d__92))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-660">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-660">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-661">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-661">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-662">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-662">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="413ae-663">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-663">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="413ae-664">SAS-Definition Erstellung Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-664">Sas definition creation metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="413ae-665">Die Attribute der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-665">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-666">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-666">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-667">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-667">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-668">Erstellt oder aktualisiert eine neue SAS-Definition für das angegebene Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="413ae-668">Creates or updates a new SAS definition for the specified storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; SetSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetSecretAsync (operations, vaultBaseUrl, secretName, value, tags, contentType, secretAttributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetSecretAsync&gt;d__46))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-669">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-669">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-670">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-670">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-671">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-671">The name of the secret.</span></span>
            </param>
        <param name="value">
            <span data-ttu-id="413ae-672">Der Wert des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-672">The value of the secret.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-673">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-673">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="413ae-674">Typ des Werts für den geheimen z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="413ae-674">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="413ae-675">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="413ae-675">The secret management attributes.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-676">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-676">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-677">Legt einen geheimen Schlüssel in einer angegebenen schlüsseltresor fest.</span><span class="sxs-lookup"><span data-stu-id="413ae-677">Sets a secret in a specified key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-678">Der SET-Vorgang hinzugefügt der Azure-Schlüsseltresor einen geheimer Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-678">The SET operation adds a secret to the Azure Key Vault.</span></span> <span data-ttu-id="413ae-679">Wenn der benannte geheime Schlüssel bereits vorhanden ist, erstellt Azure-Schlüsseltresor eine neue Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-679">If the named secret already exists, Azure Key Vault creates a new version of that secret.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SetStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; SetStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string resourceId, string activeKeyName, bool autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Boolean,System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SetStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * bool * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SetStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, resourceId, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SetStorageAccountAsync&gt;d__86))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Boolean" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-680">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-680">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-681">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-681">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-682">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-682">The name of the storage account.</span></span>
            </param>
        <param name="resourceId">
            <span data-ttu-id="413ae-683">Ressourcen-Id des Speicher-Konto.</span><span class="sxs-lookup"><span data-stu-id="413ae-683">Storage account resource id.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="413ae-684">Aktuelle aktive Key Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-684">Current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="413ae-685">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="413ae-685">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="413ae-686">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-686">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="413ae-687">Die Attribute des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-687">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-688">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-688">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-689">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-689">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-690">Erstellt oder aktualisiert ein neues Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="413ae-690">Creates or updates a new storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, keyIdentifier, algorithm, digest, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="413ae-691">Der globale Schlüsselbezeichner des den Signaturschlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-691">The global key identifier of the signing key</span></span> </param>
        <param name="algorithm"><span data-ttu-id="413ae-692">Den Signaturalgorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-692">The signing algorithm.</span></span> <span data-ttu-id="413ae-693">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-693">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> </param>
        <param name="digest"><span data-ttu-id="413ae-694">Der Digest-Wert zum Signieren</span><span class="sxs-lookup"><span data-stu-id="413ae-694">The digest value to sign</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-695">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-695">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-696">Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel im Tresor</span><span class="sxs-lookup"><span data-stu-id="413ae-696">Creates a signature from a digest using the specified key in the vault</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-697">der Wert der Signatur</span><span class="sxs-lookup"><span data-stu-id="413ae-697">The signature value</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SignAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; SignAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member SignAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.SignAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;SignAsync&gt;d__38))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-698">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-698">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-699">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-699">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-700">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-700">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-701">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-701">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-702">Die ID des Signieren/überprüfen.</span><span class="sxs-lookup"><span data-stu-id="413ae-702">The signing/verification algorithm identifier.</span></span> <span data-ttu-id="413ae-703">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-703">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="413ae-704">Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"</span><span class="sxs-lookup"><span data-stu-id="413ae-704">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-705">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-705">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-706">Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-706">Creates a signature from a digest using the specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-707">Die Anmelde-Vorgang gilt zwar für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da dieser Vorgang den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="413ae-707">The SIGN operation is applicable to asymmetric and symmetric keys stored in Azure Key Vault since this operation uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] wrappedKey, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] wrappedKey, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, keyIdentifier, algorithm, wrappedKey, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="wrappedKey" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="413ae-708">Der globale Schlüsselbezeichner des Schlüssels Wrapping/Entpacken</span><span class="sxs-lookup"><span data-stu-id="413ae-708">The global key identifier of the wrapping/unwrapping key</span></span> </param>
        <param name="algorithm"><span data-ttu-id="413ae-709">Der Unwrap-Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-709">The unwrap algorithm.</span></span> <span data-ttu-id="413ae-710">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-710">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="wrappedKey"><span data-ttu-id="413ae-711">Der umschlossene symmetrische Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-711">The wrapped symmetric key</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-712">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-712">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-713">Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel im Tresor, der anfänglich für wrapping des Schlüssels verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="413ae-713">Unwraps a symmetric key using the specified key in the vault that has initially been used for wrapping the key.</span></span>
                </summary>
        <returns><span data-ttu-id="413ae-714">Die entpackte symmetrischen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-714">The unwrapped symmetric key</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnwrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; UnwrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnwrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UnwrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UnwrapKeyAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-715">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-715">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-716">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-716">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-717">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-717">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-718">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-718">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-719">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="413ae-719">algorithm identifier.</span></span> <span data-ttu-id="413ae-720">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="413ae-720">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-721">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-721">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-722">Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel, der ursprünglich für diesen Schlüssel wrapping verwendet wurde.</span><span class="sxs-lookup"><span data-stu-id="413ae-722">Unwraps a symmetric key using the specified key that was initially used for wrapping that key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-723">Die UNWRAP-Vorgang unterstützt die Entschlüsselung eines symmetrischen Schlüssels mit dem Zielschlüssel für die Schlüsselverschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="413ae-723">The UNWRAP operation supports decryption of a symmetric key using the target key encryption key.</span></span> <span data-ttu-id="413ae-724">Dieser Vorgang ist die Umkehrung des WRAP-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="413ae-724">This operation is the reverse of the WRAP operation.</span></span> <span data-ttu-id="413ae-725">Der UNWRAP-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.</span><span class="sxs-lookup"><span data-stu-id="413ae-725">The UNWRAP operation applies to asymmetric and symmetric keys stored in Azure Key Vault since it uses the private portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string certificateIdentifier, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, certificateIdentifier, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="certificateIdentifier" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="certificateIdentifier"><span data-ttu-id="413ae-726">Die URL für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-726">The URL for the certificate.</span></span></param>
        <param name="certificatePolicy"><span data-ttu-id="413ae-727">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-727">The management policy for the certificate.</span></span></param>
        <param name="certificateAttributes"><span data-ttu-id="413ae-728">Die Attribute des Zertifikats (optional)</span><span class="sxs-lookup"><span data-stu-id="413ae-728">The attributes of the certificate (optional)</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-729">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-729">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-730">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-730">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-731">Aktualisiert eine Zertifikatversion.</span><span class="sxs-lookup"><span data-stu-id="413ae-731">Updates a certificate version.</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-732">Das aktualisierte Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-732">The updated certificate.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy = null, Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateBundle&gt; UpdateCertificateAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, string certificateVersion, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, class Microsoft.Azure.KeyVault.Models.CertificateAttributes certificateAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,Microsoft.Azure.KeyVault.Models.CertificateAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * Microsoft.Azure.KeyVault.Models.CertificateAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateAsync (operations, vaultBaseUrl, certificateName, certificateVersion, certificatePolicy, certificateAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateAsync&gt;d__73))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificateVersion" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="certificateAttributes" Type="Microsoft.Azure.KeyVault.Models.CertificateAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-733">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-733">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-734">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-734">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-735">Der Name des Zertifikats im angegebenen schlüsseltresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-735">The name of the certificate in the given key vault.</span></span>
            </param>
        <param name="certificateVersion">
            <span data-ttu-id="413ae-736">Die Version des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-736">The version of the certificate.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="413ae-737">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-737">The management policy for the certificate.</span></span>
            </param>
        <param name="certificateAttributes">
            <span data-ttu-id="413ae-738">Die Attribute des Zertifikats (optional).</span><span class="sxs-lookup"><span data-stu-id="413ae-738">The attributes of the certificate (optional).</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-739">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-739">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-740">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-740">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-741">Aktualisiert die angegebenen Attribute, die dem angegebenen Zertifikat zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="413ae-741">Updates the specified attributes associated with the given certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-742">Der UpdateCertificate-Vorgang gilt das Update für das angegebene Zertifikat; Beachten Sie, dass die einzigen Elemente, die aktualisiert wird das Zertifikat Attribute sind.</span><span class="sxs-lookup"><span data-stu-id="413ae-742">The UpdateCertificate operation applies the specified update on the given certificate; note the only elements being updated are the certificate's attributes.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateIssuerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider = null, Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials = null, Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails = null, Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.IssuerBundle&gt; UpdateCertificateIssuerAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string issuerName, string provider, class Microsoft.Azure.KeyVault.Models.IssuerCredentials credentials, class Microsoft.Azure.KeyVault.Models.OrganizationDetails organizationDetails, class Microsoft.Azure.KeyVault.Models.IssuerAttributes attributes, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.IssuerCredentials,Microsoft.Azure.KeyVault.Models.OrganizationDetails,Microsoft.Azure.KeyVault.Models.IssuerAttributes,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateIssuerAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Microsoft.Azure.KeyVault.Models.IssuerCredentials * Microsoft.Azure.KeyVault.Models.OrganizationDetails * Microsoft.Azure.KeyVault.Models.IssuerAttributes * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateIssuerAsync (operations, vaultBaseUrl, issuerName, provider, credentials, organizationDetails, attributes, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateIssuerAsync&gt;d__65))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.IssuerBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="issuerName" Type="System.String" />
        <Parameter Name="provider" Type="System.String" />
        <Parameter Name="credentials" Type="Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
        <Parameter Name="organizationDetails" Type="Microsoft.Azure.KeyVault.Models.OrganizationDetails" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.IssuerAttributes" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-743">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-743">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-744">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-744">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="issuerName">
            <span data-ttu-id="413ae-745">Der Name des Ausstellers.</span><span class="sxs-lookup"><span data-stu-id="413ae-745">The name of the issuer.</span></span>
            </param>
        <param name="provider">
            <span data-ttu-id="413ae-746">Der Aussteller-Anbieter.</span><span class="sxs-lookup"><span data-stu-id="413ae-746">The issuer provider.</span></span>
            </param>
        <param name="credentials">
            <span data-ttu-id="413ae-747">Die Anmeldeinformationen für den Aussteller verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="413ae-747">The credentials to be used for the issuer.</span></span>
            </param>
        <param name="organizationDetails">
            <span data-ttu-id="413ae-748">Details der Organisation wie an den Aussteller angegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-748">Details of the organization as provided to the issuer.</span></span>
            </param>
        <param name="attributes">
            <span data-ttu-id="413ae-749">Attribute des Ausstellers-Objekts.</span><span class="sxs-lookup"><span data-stu-id="413ae-749">Attributes of the issuer object.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-750">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-750">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-751">Aktualisiert den Aussteller des angegebenen Zertifikats an.</span><span class="sxs-lookup"><span data-stu-id="413ae-751">Updates the specified certificate issuer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-752">Der UpdateCertificateIssuer-Vorgang führt ein Update für das angegebene Zertifikat Aussteller-Entität.</span><span class="sxs-lookup"><span data-stu-id="413ae-752">The UpdateCertificateIssuer operation performs an update on the specified certificate issuer entity.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificateOperationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificateOperation&gt; UpdateCertificateOperationAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, bool cancellationRequested, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificateOperationAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificateOperationAsync (operations, vaultBaseUrl, certificateName, cancellationRequested, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificateOperationAsync&gt;d__75))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificateOperation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="cancellationRequested" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-753">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-753">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-754">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-754">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-755">Der Name des Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="413ae-755">The name of the certificate.</span></span>
            </param>
        <param name="cancellationRequested">
            <span data-ttu-id="413ae-756">Gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.</span><span class="sxs-lookup"><span data-stu-id="413ae-756">Indicates if cancellation was requested on the certificate operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-757">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-757">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-758">Aktualisiert einen Zertifikat-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="413ae-758">Updates a certificate operation.</span></span> <span data-ttu-id="413ae-759">Autorisierung: erfordert die Zertifikate/Update-Berechtigung.</span><span class="sxs-lookup"><span data-stu-id="413ae-759">Authorization: requires the certificates/update permission.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateCertificatePolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt; UpdateCertificatePolicyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string certificateName, class Microsoft.Azure.KeyVault.Models.CertificatePolicy certificatePolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.CertificatePolicy,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateCertificatePolicyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.CertificatePolicy * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateCertificatePolicyAsync (operations, vaultBaseUrl, certificateName, certificatePolicy, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateCertificatePolicyAsync&gt;d__72))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.CertificatePolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="certificateName" Type="System.String" />
        <Parameter Name="certificatePolicy" Type="Microsoft.Azure.KeyVault.Models.CertificatePolicy" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-760">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-760">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-761">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-761">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="certificateName">
            <span data-ttu-id="413ae-762">Der Name des Zertifikats in den angegebenen Tresor.</span><span class="sxs-lookup"><span data-stu-id="413ae-762">The name of the certificate in the given vault.</span></span>
            </param>
        <param name="certificatePolicy">
            <span data-ttu-id="413ae-763">Die Richtlinie für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="413ae-763">The policy for the certificate.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-764">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-764">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-765">Aktualisiert die Richtlinie für ein Zertifikat an.</span><span class="sxs-lookup"><span data-stu-id="413ae-765">Updates the policy for a certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-766">Festzulegen Sie angegebene Member in der Zertifikatrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="413ae-766">Set specified members in the certificate policy.</span></span> <span data-ttu-id="413ae-767">Belassen Sie andere als Null.</span><span class="sxs-lookup"><span data-stu-id="413ae-767">Leave others as null.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, keyIdentifier, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"><span data-ttu-id="413ae-768">Der Schlüsselbezeichner</span><span class="sxs-lookup"><span data-stu-id="413ae-768">The key identifier</span></span></param>
        <param name="keyOps"><span data-ttu-id="413ae-769">JSON Web Key-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="413ae-769">Json web key operations.</span></span> <span data-ttu-id="413ae-770">Weitere Informationen finden Sie unter JsonWebKeyOperation.</span><span class="sxs-lookup"><span data-stu-id="413ae-770">For more information, see JsonWebKeyOperation.</span></span></param>
        <param name="attributes"><span data-ttu-id="413ae-771">Die neuen Attribute für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-771">The new attributes for the key.</span></span> <span data-ttu-id="413ae-772">Weitere Informationen zu den wichtigsten Attributen finden Sie unter KeyAttributes.</span><span class="sxs-lookup"><span data-stu-id="413ae-772">For more information on key attributes, see KeyAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-773">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-773">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-774">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-774">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-775">Aktualisiert die Schlüssel-Attribute, die dem angegebenen Schlüssel zugeordnet</span><span class="sxs-lookup"><span data-stu-id="413ae-775">Updates the Key Attributes associated with the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="413ae-776">Die aktualisierten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-776">The updated key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes attributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string[] keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes attributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String[],Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string[] * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyOps, attributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__8))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyOps" Type="System.String[]" />
        <Parameter Name="attributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="vaultBaseUrl"><span data-ttu-id="413ae-777">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</span><span class="sxs-lookup"><span data-stu-id="413ae-777">The vault name, e.g. https://myvault.vault.azure.net</span></span></param>
        <param name="keyName"><span data-ttu-id="413ae-778">der Name des Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-778">The key name</span></span></param>
        <param name="keyOps"><span data-ttu-id="413ae-779">JSON Web Key-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="413ae-779">Json web key operations.</span></span> <span data-ttu-id="413ae-780">Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.</span><span class="sxs-lookup"><span data-stu-id="413ae-780">For more information on possible key operations, see JsonWebKeyOperation.</span></span></param>
        <param name="attributes"><span data-ttu-id="413ae-781">Die neuen Attribute für den Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-781">The new attributes for the key.</span></span> <span data-ttu-id="413ae-782">Weitere Informationen zu den wichtigsten Attributen finden Sie unter KeyAttributes.</span><span class="sxs-lookup"><span data-stu-id="413ae-782">For more information on key attributes, see KeyAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-783">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-783">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="413ae-784">Aktualisiert die Schlüssel-Attribute, die dem angegebenen Schlüssel zugeordnet</span><span class="sxs-lookup"><span data-stu-id="413ae-784">Updates the Key Attributes associated with the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="413ae-785">Die aktualisierten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-785">The updated key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, System.Collections.Generic.IList&lt;string&gt; keyOps = null, Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyBundle&gt; UpdateKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, class System.Collections.Generic.IList`1&lt;string&gt; keyOps, class Microsoft.Azure.KeyVault.Models.KeyAttributes keyAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.KeyVault.Models.KeyAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.KeyVault.Models.KeyAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, keyOps, keyAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateKeyAsync&gt;d__30))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="keyOps" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="keyAttributes" Type="Microsoft.Azure.KeyVault.Models.KeyAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-786">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-786">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-787">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-787">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-788">Der Name der zu aktualisierende Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-788">The name of key to update.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-789">Die Version des Schlüssels zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="413ae-789">The version of the key to update.</span></span>
            </param>
        <param name="keyOps">
            <span data-ttu-id="413ae-790">JSON Web Key-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="413ae-790">Json web key operations.</span></span> <span data-ttu-id="413ae-791">Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.</span><span class="sxs-lookup"><span data-stu-id="413ae-791">For more information on possible key operations, see JsonWebKeyOperation.</span></span>
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            <span data-ttu-id="413ae-792">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-792">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-793">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-793">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-794">Die Änderungen am Update Schlüsselvorgang angegebene Attribute eines gespeicherten Schlüssels und können auf alle Schlüsseltypen und Schlüssel in Azure Key Vault gespeicherten Version angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-794">The update key operation changes specified attributes of a stored key and can be applied to any key type and key version stored in Azure Key Vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-795">Um diesen Vorgang auszuführen, muss der Schlüssel bereits im Schlüsseltresor vorhanden sein.</span><span class="sxs-lookup"><span data-stu-id="413ae-795">In order to perform this operation, the key must already exist in the Key Vault.</span></span> <span data-ttu-id="413ae-796">Hinweis: Das kryptografische Material eines Schlüssels selbst kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-796">Note: The cryptographic material of a key itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSasDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt; UpdateSasDefinitionAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string sasDefinitionName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes sasDefinitionAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSasDefinitionAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSasDefinitionAsync (operations, vaultBaseUrl, storageAccountName, sasDefinitionName, parameters, sasDefinitionAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSasDefinitionAsync&gt;d__93))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SasDefinitionBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="sasDefinitionName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sasDefinitionAttributes" Type="Microsoft.Azure.KeyVault.Models.SasDefinitionAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-797">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-797">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-798">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-798">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-799">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-799">The name of the storage account.</span></span>
            </param>
        <param name="sasDefinitionName">
            <span data-ttu-id="413ae-800">Der Name der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-800">The name of the SAS definition.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="413ae-801">SAS-definitionsaktualisierung Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-801">Sas definition update metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="sasDefinitionAttributes">
            <span data-ttu-id="413ae-802">Die Attribute der SAS-Definition.</span><span class="sxs-lookup"><span data-stu-id="413ae-802">The attributes of the SAS definition.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-803">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-803">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-804">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-804">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-805">Aktualisiert die angegebenen Attribute der bestimmten SAS-Definition zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="413ae-805">Updates the specified attributes associated with the given SAS definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.Dictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string secretIdentifier, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.Dictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.Dictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.Dictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, secretIdentifier, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__14))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="secretIdentifier" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.Dictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="secretIdentifier"><span data-ttu-id="413ae-806">Die URL des geheimen Schlüssels</span><span class="sxs-lookup"><span data-stu-id="413ae-806">The URL of the secret</span></span></param>
        <param name="contentType"><span data-ttu-id="413ae-807">Typ des Werts für den geheimen z. B. das Kennwort.</span><span class="sxs-lookup"><span data-stu-id="413ae-807">Type of the secret value such as password.</span></span></param>
        <param name="secretAttributes"><span data-ttu-id="413ae-808">Attribute für den geheimen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="413ae-808">Attributes for the secret.</span></span> <span data-ttu-id="413ae-809">Weitere Informationen zu möglichen Attributen finden Sie unter SecretAttributes.</span><span class="sxs-lookup"><span data-stu-id="413ae-809">For more information on possible attributes, see SecretAttributes.</span></span></param>
        <param name="tags"><span data-ttu-id="413ae-810">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</span><span class="sxs-lookup"><span data-stu-id="413ae-810">Application-specific metadata in the form of key-value pairs</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="413ae-811">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-811">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-812">Aktualisiert die Attribute, die mit dem angegebenen Schlüssel zugeordnete</span><span class="sxs-lookup"><span data-stu-id="413ae-812">Updates the attributes associated with the specified secret</span></span>
            </summary>
        <returns><span data-ttu-id="413ae-813">Eine Antwortnachricht mit den aktualisierten geheimen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-813">A response message containing the updated secret</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSecretAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType = null, Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.SecretBundle&gt; UpdateSecretAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string secretName, string secretVersion, string contentType, class Microsoft.Azure.KeyVault.Models.SecretAttributes secretAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,Microsoft.Azure.KeyVault.Models.SecretAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateSecretAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * Microsoft.Azure.KeyVault.Models.SecretAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateSecretAsync (operations, vaultBaseUrl, secretName, secretVersion, contentType, secretAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateSecretAsync&gt;d__48))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.SecretBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="secretName" Type="System.String" />
        <Parameter Name="secretVersion" Type="System.String" />
        <Parameter Name="contentType" Type="System.String" />
        <Parameter Name="secretAttributes" Type="Microsoft.Azure.KeyVault.Models.SecretAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-814">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-814">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-815">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-815">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="secretName">
            <span data-ttu-id="413ae-816">Der Name des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-816">The name of the secret.</span></span>
            </param>
        <param name="secretVersion">
            <span data-ttu-id="413ae-817">die Version des geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-817">The version of the secret.</span></span>
            </param>
        <param name="contentType">
            <span data-ttu-id="413ae-818">Typ des Werts für den geheimen z. B. eines Kennworts.</span><span class="sxs-lookup"><span data-stu-id="413ae-818">Type of the secret value such as a password.</span></span>
            </param>
        <param name="secretAttributes">
            <span data-ttu-id="413ae-819">Die Attribute für den geheimen Management.</span><span class="sxs-lookup"><span data-stu-id="413ae-819">The secret management attributes.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-820">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-820">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-821">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-821">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-822">Aktualisiert die Attribute, die mit einem angegebenen Schlüssel in einem angegebenen Schlüssel Tresor verknüpft sind.</span><span class="sxs-lookup"><span data-stu-id="413ae-822">Updates the attributes associated with a specified secret in a given key vault.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-823">Der UPDATE-Vorgang ändert angegebene Attribute einer vorhandenen gespeicherten, geheimen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-823">The UPDATE operation changes specified attributes of an existing stored secret.</span></span> <span data-ttu-id="413ae-824">Attribute, die nicht in der Anforderung angegeben werden bleiben unverändert.</span><span class="sxs-lookup"><span data-stu-id="413ae-824">Attributes that are not specified in the request are left unchanged.</span></span> <span data-ttu-id="413ae-825">Der Wert eines geheimen Schlüssels selbst kann nicht geändert werden.</span><span class="sxs-lookup"><span data-stu-id="413ae-825">The value of a secret itself cannot be changed.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateStorageAccountAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName = null, Nullable&lt;bool&gt; autoRegenerateKey = null, string regenerationPeriod = null, Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.StorageBundle&gt; UpdateStorageAccountAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string storageAccountName, string activeKeyName, valuetype System.Nullable`1&lt;bool&gt; autoRegenerateKey, string regenerationPeriod, class Microsoft.Azure.KeyVault.Models.StorageAccountAttributes storageAccountAttributes, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.Nullable{System.Boolean},System.String,Microsoft.Azure.KeyVault.Models.StorageAccountAttributes,System.Collections.Generic.IDictionary{System.String,System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateStorageAccountAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * Nullable&lt;bool&gt; * string * Microsoft.Azure.KeyVault.Models.StorageAccountAttributes * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.UpdateStorageAccountAsync (operations, vaultBaseUrl, storageAccountName, activeKeyName, autoRegenerateKey, regenerationPeriod, storageAccountAttributes, tags, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;UpdateStorageAccountAsync&gt;d__87))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.StorageBundle&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="storageAccountName" Type="System.String" />
        <Parameter Name="activeKeyName" Type="System.String" />
        <Parameter Name="autoRegenerateKey" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="regenerationPeriod" Type="System.String" />
        <Parameter Name="storageAccountAttributes" Type="Microsoft.Azure.KeyVault.Models.StorageAccountAttributes" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-826">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-826">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-827">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-827">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="storageAccountName">
            <span data-ttu-id="413ae-828">Der Name des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-828">The name of the storage account.</span></span>
            </param>
        <param name="activeKeyName">
            <span data-ttu-id="413ae-829">Der aktuellen aktiven Schlüssel speicherkontoname.</span><span class="sxs-lookup"><span data-stu-id="413ae-829">The current active storage account key name.</span></span>
            </param>
        <param name="autoRegenerateKey">
            <span data-ttu-id="413ae-830">Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.</span><span class="sxs-lookup"><span data-stu-id="413ae-830">whether keyvault should manage the storage account for the user.</span></span>
            </param>
        <param name="regenerationPeriod">
            <span data-ttu-id="413ae-831">Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.</span><span class="sxs-lookup"><span data-stu-id="413ae-831">The key regeneration time duration specified in ISO-8601 format.</span></span>
            </param>
        <param name="storageAccountAttributes">
            <span data-ttu-id="413ae-832">Die Attribute des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="413ae-832">The attributes of the storage account.</span></span>
            </param>
        <param name="tags">
            <span data-ttu-id="413ae-833">Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.</span><span class="sxs-lookup"><span data-stu-id="413ae-833">Application specific metadata in the form of key-value pairs.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-834">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-834">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-835">Aktualisiert die angegebenen Attributen, die das angegebene Speicherkonto zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="413ae-835">Updates the specified attributes associated with the given storage account.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, keyIdentifier, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="413ae-836">Der globale Schlüsselbezeichner des Schlüssels zum Signieren verwendet</span><span class="sxs-lookup"><span data-stu-id="413ae-836">The global key identifier of the key used for signing</span></span> </param>
        <param name="algorithm"> <span data-ttu-id="413ae-837">Der Algorithmus Signieren/überprüfen.</span><span class="sxs-lookup"><span data-stu-id="413ae-837">The signing/verification algorithm.</span></span> <span data-ttu-id="413ae-838">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-838">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="digest"> <span data-ttu-id="413ae-839">Der Hashwert, der zum Signieren verwendet</span><span class="sxs-lookup"><span data-stu-id="413ae-839">The digest used for signing</span></span> </param>
        <param name="signature"> <span data-ttu-id="413ae-840">Die zu überprüfende Signatur</span><span class="sxs-lookup"><span data-stu-id="413ae-840">The signature to be verified</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="413ae-841">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-841">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-842">Überprüft eine Signatur, die mit dem angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-842">Verifies a signature using the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="413ae-843">"true", wenn die Signatur verifiziert, "false" ist.</span><span class="sxs-lookup"><span data-stu-id="413ae-843">true if the signature is verified, false otherwise.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] digest, byte[] signature, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt; VerifyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] digest, unsigned int8[] signature, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member VerifyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.VerifyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, digest, signature, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;VerifyAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyVerifyResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="digest" Type="System.Byte[]" />
        <Parameter Name="signature" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-844">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-844">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-845">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-845">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-846">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-846">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-847">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-847">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-848">Der Algorithmus Signieren/überprüfen.</span><span class="sxs-lookup"><span data-stu-id="413ae-848">The signing/verification algorithm.</span></span> <span data-ttu-id="413ae-849">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-849">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span> <span data-ttu-id="413ae-850">Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"</span><span class="sxs-lookup"><span data-stu-id="413ae-850">Possible values include: 'PS256', 'PS384', 'PS512', 'RS256', 'RS384', 'RS512', 'RSNULL', 'ES256', 'ES384', 'ES512', 'ECDSA256'</span></span>
            </param>
        <param name="digest">
            <span data-ttu-id="413ae-851">Den Hashwert, der zum Signieren verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="413ae-851">The digest used for signing.</span></span>
            </param>
        <param name="signature">
            <span data-ttu-id="413ae-852">Die zu überprüfende Signatur.</span><span class="sxs-lookup"><span data-stu-id="413ae-852">The signature to be verified.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-853">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-853">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-854">Überprüft eine Signatur, die mithilfe eines angegebenen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-854">Verifies a signature using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-855">Die VERIFY-Vorgang gilt zwar für symmetrische Schlüssel in Azure Key Vault gespeichert.</span><span class="sxs-lookup"><span data-stu-id="413ae-855">The VERIFY operation is applicable to symmetric keys stored in Azure Key Vault.</span></span> <span data-ttu-id="413ae-856">Überprüfen Sie, ob ist nicht unbedingt erforderlich für asymmetrische Schlüssel im Azure-Schlüsseltresor gespeichert sind, da die signaturüberprüfung kann mit dem öffentlichen Teil des Schlüssels ausgeführt werden, aber dieser Vorgang wird als Annehmlichkeit unterstützt, für den Aufrufer, die nur einen Schlüssel-Verweis und nicht die öffentliche Teil des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-856">VERIFY is not strictly necessary for asymmetric keys stored in Azure Key Vault since signature verification can be performed using the public portion of the key but this operation is supported as a convenience for callers that only have a key-reference and not the public portion of the key.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, byte[] key, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string keyIdentifier, string algorithm, unsigned int8[] key, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, keyIdentifier, algorithm, key, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="keyIdentifier" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="key" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">To be added.</param>
        <param name="keyIdentifier"> <span data-ttu-id="413ae-857">Der globale Schlüsselbezeichner des Schlüssels für Textumbruch für</span><span class="sxs-lookup"><span data-stu-id="413ae-857">The global key identifier of the key used for wrapping</span></span> </param>
        <param name="algorithm"> <span data-ttu-id="413ae-858">Der Wrap-Algorithmus.</span><span class="sxs-lookup"><span data-stu-id="413ae-858">The wrap algorithm.</span></span> <span data-ttu-id="413ae-859">Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</span><span class="sxs-lookup"><span data-stu-id="413ae-859">For more information on possible algorithm types, see JsonWebKeySignatureAlgorithm.</span></span></param>
        <param name="key"> <span data-ttu-id="413ae-860">Der symmetrische Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-860">The symmetric key</span></span> </param>
        <param name="cancellationToken"><span data-ttu-id="413ae-861">Optionale Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="413ae-861">Optional cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="413ae-862">Dient als Wrapper für einen symmetrischen Schlüssel mit dem angegebenen Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-862">Wraps a symmetric key using the specified key</span></span>
            </summary>
        <returns> <span data-ttu-id="413ae-863">Der umschlossene symmetrische Schlüssel</span><span class="sxs-lookup"><span data-stu-id="413ae-863">The wrapped symmetric key</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WrapKeyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync (this Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, byte[] value, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt; WrapKeyAsync(class Microsoft.Azure.KeyVault.IKeyVaultClient operations, string vaultBaseUrl, string keyName, string keyVersion, string algorithm, unsigned int8[] value, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync(Microsoft.Azure.KeyVault.IKeyVaultClient,System.String,System.String,System.String,System.String,System.Byte[],System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member WrapKeyAsync : Microsoft.Azure.KeyVault.IKeyVaultClient * string * string * string * string * byte[] * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;" Usage="Microsoft.Azure.KeyVault.KeyVaultClientExtensions.WrapKeyAsync (operations, vaultBaseUrl, keyName, keyVersion, algorithm, value, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.KeyVault.KeyVaultClientExtensions/&lt;WrapKeyAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.KeyVault.Models.KeyOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.KeyVault.IKeyVaultClient" RefType="this" />
        <Parameter Name="vaultBaseUrl" Type="System.String" />
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="keyVersion" Type="System.String" />
        <Parameter Name="algorithm" Type="System.String" />
        <Parameter Name="value" Type="System.Byte[]" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="413ae-864">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="413ae-864">The operations group for this extension method.</span></span>
            </param>
        <param name="vaultBaseUrl">
            <span data-ttu-id="413ae-865">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.</span><span class="sxs-lookup"><span data-stu-id="413ae-865">The vault name, for example https://myvault.vault.azure.net.</span></span>
            </param>
        <param name="keyName">
            <span data-ttu-id="413ae-866">Der Name des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-866">The name of the key.</span></span>
            </param>
        <param name="keyVersion">
            <span data-ttu-id="413ae-867">die Version des Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-867">The version of the key.</span></span>
            </param>
        <param name="algorithm">
            <span data-ttu-id="413ae-868">Algorithmusbezeichner.</span><span class="sxs-lookup"><span data-stu-id="413ae-868">algorithm identifier.</span></span> <span data-ttu-id="413ae-869">Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"</span><span class="sxs-lookup"><span data-stu-id="413ae-869">Possible values include: 'RSA-OAEP', 'RSA-OAEP-256', 'RSA1_5'</span></span>
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            <span data-ttu-id="413ae-870">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="413ae-870">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="413ae-871">Umschließt einen symmetrischen Schlüssel mithilfe eines angegebenen Schlüssels.</span><span class="sxs-lookup"><span data-stu-id="413ae-871">Wraps a symmetric key using a specified key.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="413ae-872">Der WRAP-Vorgang unterstützt die Verschlüsselung eines symmetrischen Schlüssels mit einem schlüsselverschlüsselungsschlüssel, der zuvor in einem Azure-Schlüsseltresor gespeichert wurde.</span><span class="sxs-lookup"><span data-stu-id="413ae-872">The WRAP operation supports encryption of a symmetric key using a key encryption key that has previously been stored in an Azure Key Vault.</span></span> <span data-ttu-id="413ae-873">Der WRAP-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mit dem öffentlichen Teil des Schlüssels ausgeführt werden kann.</span><span class="sxs-lookup"><span data-stu-id="413ae-873">The WRAP operation is only strictly necessary for symmetric keys stored in Azure Key Vault since protection with an asymmetric key can be performed using the public portion of the key.</span></span> <span data-ttu-id="413ae-874">Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.</span><span class="sxs-lookup"><span data-stu-id="413ae-874">This operation is supported for asymmetric keys as a convenience for callers that have a key-reference but do not have access to the public key material.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>