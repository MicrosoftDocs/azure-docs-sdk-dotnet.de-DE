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
            Erweiterungsmethoden für KeyVaultClient.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fordert an, dass eine Sicherung des angegebenen Schlüssels an den Client heruntergeladen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Schlüssel Sicherungsvorgang exportiert einen Schlüssel aus dem Azure-Schlüsseltresor in einer geschützten Form. Beachten Sie, dass dieser Vorgang gibt keinen Schlüsselmaterial zurück, in ein Formular, das außerhalb der Azure Key Vault-System verwendet werden kann, das zurückgegebene Schlüsselmaterial ist entweder geschützt ein Azure-Schlüsseltresor-HSM oder Azure Key Vault selbst.
            Der Zweck dieses Vorgangs ist, kann einen Client einen Schlüssel in einer Instanz von Azure Key Vault, Sichern Sie den Schlüssel generieren und dann in eine andere Azure Key Vault-Instanz wiederherstellen. Der Sicherungsvorgang kann verwendet werden, in geschützter Form jedes Schlüsseltyps im Azure Key Vault zu exportieren. Einzelne Versionen eines Schlüssels können nicht gesichert werden. Sicherung / Wiederherstellung nur; innerhalb geografischer Grenzen ausgeführt werden kann. Dies bedeutet, dass eine Sicherung aus einem geografischen Bereich nicht zu einem anderen geografischen Bereich wiederhergestellt werden kann. Beispielsweise kann eine Sicherung von geografischen Gebiet der USA in einer geografischen Bereich der EU wiederhergestellt werden.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fordert an, dass eine Sicherung des angegebenen geheimen Schlüssels an den Client heruntergeladen werden.
            Autorisierung: ist der geheime Schlüssel/Backup-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt ein neues Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name für den neuen Schlüssel. Das System generiert den Versionsnamen für den neuen Schlüssel.
            </param>
        <param name="kty">
            Der Typ des Schlüssels zu erstellen. Gültige Werte finden Sie unter JsonWebKeyType. Folgende Werte sind möglich: "EC", "EC-HSM", "RSA", "RSA-HSM", "oct"
            </param>
        <param name="keySize">
            Die Schlüsselgröße in Bytes. Z. B. 1024 oder 2048.
            </param>
        <param name="keyOps"></param>
        <param name="keyAttributes"></param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt einen neuen Schlüssel, speichert ihn, dann gibt Schlüsselparameter und Attribute an den Client.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Erstellvorgang Schlüssel kann zum Erstellen jedes Schlüsseltyps im Azure-Schlüsseltresor verwendet werden. Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.
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
        <param name="keyIdentifier">Der vollständige Schlüsselbezeichner</param>
        <param name="algorithm">Der Algorithmus. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeyEncryptionAlgorithm.</param>
        <param name="cipherText">Der Verschlüsselungstext</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Einen einzelnen Block von verschlüsselten Daten entschlüsselt
            </summary>
        <returns>Das Ergebnis der Entschlüsselung</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entschlüsselt einen einzelnen Block von verschlüsselten Daten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der DECRYPT-Vorgang entschlüsselt einen wohlgeformten Block mit verschlüsseltem Text transformiert, die mit dem Ziel-Verschlüsselungsschlüssel und angegebenen Algorithmus. Dieser Vorgang ist die Umkehrung des ENCRYPT-Vorgangs; nur ein einzelner Datenblock entschlüsselt werden kann, ist die Größe dieses Blocks vom Zielschlüssel und dem zu verwendenden Algorithmus abhängig. Der DECRYPT-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Zertifikat aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht alle Versionen eines Objekts Zertifikat zusammen mit der zugeordneten Richtlinien. Löschen von Zertifikat kann nicht verwendet werden, um einzelne Versionen eines Objekts Zertifikat zu entfernen.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht die Zertifikat-Kontakte für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löscht die Zertifikat-Kontakte für ein Zertifikat für die angegebene schlüsseltresor.
            Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den angegebenen Zertifikataussteller an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang DeleteCertificateIssuer werden endgültig gelöscht der Aussteller des angegebenen Zertifikats aus dem Tresor.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht den Vorgang für ein angegebenes Zertifikat. Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels zu löschen.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Schlüssel eines beliebigen Typs aus dem Speicher in Azure Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Löschvorgang Schlüssel kann nicht zum Entfernen einzelner Versionen eines Schlüssels verwendet werden. Dieser Vorgang entfernt das kryptografische Material, das dem Schlüssel, was bedeutet, dass der Schlüssel nicht für Sign/Verify-, Wrap/Unwrap- oder Encrypt/Decrypt-Vorgänge verwendet werden.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht eine SAS-Definition aus einem angegebenen Speicherkonto.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen geheimen Schlüssel aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der DELETE-Vorgang gilt für alle geheimen Schlüssel in Azure Key Vault gespeichert.
            DELETE kann nicht für eine einzelne Version eines geheimen Schlüssels angewendet werden.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Speicherkonto an.
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
        <param name="keyIdentifier">Der vollständige Schlüsselbezeichner</param>
        <param name="algorithm">Der Algorithmus. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeyEncryptionAlgorithm.</param>
        <param name="plainText">Nur-text</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Verschlüsselt einen einzelnen Block von Daten an. Die Menge der Daten, die verschlüsselt werden möglicherweise richtet sich nach den Zieltyp für den Schlüssel und den Verschlüsselungsalgorithmus.
            </summary>
        <returns>Der verschlüsselte text</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in einem schlüsseltresor gespeichert sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der ENCRYPT-Vorgang verschlüsselt eine beliebige Abfolge von Bytes, die mithilfe eines Verschlüsselungsschlüssels, das in Azure Key Vault gespeichert ist. Beachten Sie, dass der ENCRYPT-Vorgang nur einen einzelnen Block von Daten unterstützt, deren Größe vom Zielschlüssel und den zu verwendenden Verschlüsselungsalgorithmus abhängig ist. Der ENCRYPT-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mithilfe der öffentliche Teil des Schlüssels ausgeführt werden kann. Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.
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
        <param name="certificateIdentifier">Die URL für das Zertifikat.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft ein Zertifikat ab.
            </summary>
        <returns>Das abgerufene Zertifikat</returns>
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
        <param name="vaultBaseUrl">Die URL für den Tresor, der das Zertifikat enthält.</param>
        <param name="certificateName">Der Name des Zertifikats in den angegebenen Tresor.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft ein Zertifikat ab.
            </summary>
        <returns>Das abgerufene Zertifikat</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in den angegebenen Tresor.
            </param>
        <param name="certificateVersion">
            Die Version des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen zu einem angegebenen Zertifikat ab. Autorisierung: erfordert die Zertifikate/Get-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Kontakte Zertifikat für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der GetCertificateContacts-Vorgang gibt den Satz von Zertifikat Kontakt Ressourcen im angegebenen schlüsseltresor.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet den Aussteller des angegebenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuer gibt das angegebene Zertifikat Aussteller Ressourcen im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikataussteller für einen angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateIssuers gibt den Satz der Aussteller zertifikatressourcen im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ein angegebenes Zertifikat zugeordneten Vorgangs ab. Autorisierung: erfordert die Zertifikate/Get-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in einer bestimmten schlüsseltresor.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Richtlinie für ein Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificatePolicy gibt das angegebene Zertifikat Richtlinie Ressourcen im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikate in einem angegebenen Schlüssel Tresor
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Zertifikate in einem angegebenen Schlüssel Tresor
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificates gibt den Satz von Ressourcen für Zertifikate im angegebenen schlüsseltresor.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen eines Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang GetCertificateVersions gibt die Versionen eines Zertifikats im angegebenen schlüsseltresor
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über das angegebene gelöschten Zertifikat ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificate abgerufen, die gelöschte Zertifikatinformationen sowie seiner Attribute, z. B. Aufbewahrungszeitraum, geplante permanent löschen und die aktuelle Ebene der Löschvorgang Wiederherstellung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die gelöschten Zertifikate in den angegebenen Tresor, die derzeit für die Wiederherstellung verfügbar.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Mit dem Vorgang GetDeletedCertificates abgerufen, die Zertifikate im aktuellen Tresor sind in einem gelöschten Zustand befindet und bereit zur Wiederherstellung oder zum Löschen.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ab, die gelöschte Schlüsselinformationen sowie seiner Attribute. Autorisierung: Ist der Schlüssel/Get-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht Schlüssel in den angegebenen Tresor. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht Schlüssel in den angegebenen Tresor. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft ab, die gelöschte geheimen Informationen sowie seiner Attribute.
            Autorisierung: ist der geheime Schlüssel/Get-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht geheime Schlüssel in den angegebenen Tresor. Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste gelöscht geheime Schlüssel in den angegebenen Tresor. Autorisierung: ist der geheime Schlüssel/List-Berechtigung erforderlich.
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
        <param name="keyIdentifier">Der Schlüsselbezeichner</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft den öffentlichen Teil eines Schlüssels sowie seiner Attribute.
            </summary>
        <returns>Eine KeyBundle des Schlüssels und dessen Attribute</returns>
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
        <param name="vaultBaseUrl">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</param>
        <param name="keyName">der Name des Schlüssels</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft den öffentlichen Teil eines Schlüssels sowie seiner Attribute.
            </summary>
        <returns>Eine KeyBundle des Schlüssels und dessen Attribute</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des abzurufenden Schlüssels.
            </param>
        <param name="keyVersion">
            Hinzufügen der "Version"-Parameter ruft eine bestimmte Version eines Schlüssels ab.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft den öffentlichen Teil eines gespeicherten Schlüssels ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die wichtigsten Get-Vorgang gilt zwar für alle Schlüsseltypen. Wenn es sich bei der angeforderte Schlüssel symmetrisch ist, wird keine Schlüsselmaterial in der Antwort freigegeben.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste von Schlüsseln in den angegebenen Tresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten. Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt. Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste von Schlüsseln in den angegebenen Tresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Ruft eine Liste der Schlüssel im Schlüsseltresor als JSON Web Key-Strukturen, die den öffentlichen Teil eines gespeicherten Schlüssels enthalten. Der LIST-Vorgang gilt für alle Schlüsseltypen, die in der Antwort werden jedoch nur der schlüsselbasisbezeichner, Attribute und tags bereitgestellt. Einzelne Versionen eines Schlüssels werden nicht in der Antwort aufgeführt. Autorisierung: Ist der Schlüssel/List-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft eine Liste der einzelnen schlüsselversionen mit demselben Schlüsselnamen ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der vollständige Schlüsselbezeichner, Attribute und Tags werden in der Antwort bereitgestellt.
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
        <param name="vaultBaseUrl">Die URL für den Tresor mit dem Zertifikat</param>
        <param name="certificateName">Der Name des Zertifikats</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft Base64 ausstehende zertifikatsignieranforderung (PKCS bis 10) 
            </summary>
        <returns>Die ausstehende zertifikatsignieranforderung als Base64-codierte Zeichenfolge.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über eine SAS-Definition für das angegebene Speicherkonto ab.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicher-SAS-Listendefinitionen für das angegebene Speicherkonto an.
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
        <param name="secretIdentifier">Die URL für den geheimen Schlüssel.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft einen geheimen Schlüssel ab.
            </summary>
        <returns>Eine Antwortnachricht, die den geheimen Schlüssel enthält.</returns>
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
        <param name="vaultBaseUrl">Die URL für den Tresor, der die geheimen Schlüssel enthält.</param>
        <param name="secretName">Der Name der geheime Schlüssel in den angegebenen Tresor.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Ruft einen geheimen Schlüssel ab.
            </summary>
        <returns>Eine Antwortnachricht, die den geheimen Schlüssel enthält.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="secretVersion">
            die Version des geheimen Schlüssels.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erhalten Sie einen angegebenen Schlüssel aus einem angegebenen schlüsseltresor.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die GET-Vorgang gilt zwar für alle geheimen Schlüssel in Azure Key Vault gespeichert.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Auflisten geheimer Schlüssel in einer angegebenen Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt. Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Auflisten geheimer Schlüssel in einer angegebenen Key Vault.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST-Vorgang gilt zwar für den gesamten Tresor, doch nur die geheime basisschlüsselbezeichner und Attribute werden in der Antwort bereitgestellt. Einzelne Versionen des Schlüssels sind nicht in der Antwort aufgeführt.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen des angegebenen geheimen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden. Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt. Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste der Versionen des angegebenen geheimen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der LIST VERSIONS-Vorgang kann auf alle Versionen, die denselben geheime Schlüsselnamen im selben schlüsseltresor angewendet werden. Der vollständige geheime Bezeichner und Attribute werden in der Antwort bereitgestellt. Es werden keine Werte für die geheimen Schlüssel zurückgegeben, und nur die aktuelle Versionen eines geheimen Schlüssels werden aufgelistet.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über ein angegebenes Speicherkonto ab.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="maxresults">
            Maximale Anzahl der Ergebnisse in einer Seite zurückzugeben. Wenn nicht angegeben, der Dienst bis zu 25 Ergebnisse zurück.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Speicherkonten auflisten, die von der angegebenen schlüsseltresor verwaltet werden
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
        <param name="vaultBaseUrl">Die URL für den Tresor mit dem Zertifikat</param>
        <param name="certificateName">Der Name des Zertifikats</param>
        <param name="certificateCollection">Die Auflistung der Zertifikate mit dem privaten Schlüssel</param>
        <param name="certificatePolicy">Die Verwaltungsrichtlinie für das Zertifikat</param>
        <param name="certificateAttributes">Die Attribute des Zertifikats (optional)</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Importiert eine neue Zertifikatversion an. Wenn dies die erste Version ist, wird die zertifikatsressource erstellt.
            </summary>
        <returns>Importierte Zertifikat Paket in den Tresor.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="base64EncodedCertificate">
            Base64-codierte Darstellung des Objekts Zertifikat zu importieren. Dieses Zertifikat muss den privaten Schlüssel enthalten.
            </param>
        <param name="password">
            Wenn der private Schlüssel im base64EncodedCertificate verschlüsselt ist, können Sie das Kennwort für die Verschlüsselung verwendete.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird ein Zertifikat in einem angegebenen schlüsseltresor importiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Importiert ein vorhandenes gültiges Zertifikat ist, einen privaten Schlüssel enthält, in Azure Key Vault. Das Zertifikat importiert werden sollen, kann im PFX oder PEM-Format sein. Wenn das Zertifikat im PEM-Format ist muss die PEM-Datei enthalten, den Schlüssel als auch X509 Zertifikate.
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
        <param name="vaultBaseUrl">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</param>
        <param name="keyName">der Name des Schlüssels</param>
        <param name="keyBundle"> Key-Paket </param>
        <param name="importToHardware">Angibt, ob als Hardwareschlüssel (HSM) oder Softwareschlüssel importieren </param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Importiert einen Schlüssel in den angegebenen Tresor
            </summary>
        <returns> Importierte Schlüssel Paket in den Tresor </returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name für den importierten Schlüssel.
            </param>
        <param name="key">
            Das Json Web key
            </param>
        <param name="hsm">
            Ob als Hardwareschlüssel (HSM) oder Softwareschlüssel zu importieren.
            </param>
        <param name="keyAttributes">
            Die schlüsselverwaltung-Attribute.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Importiert einen extern erstellten Schlüssel, speichert ihn und gibt Schlüsselparameter und Attribute an den Client.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Beim Importieren kann verwendet werden, um jedes Schlüsseltyps in Azure Key Vault zu importieren. Wenn der benannte Schlüssel bereits vorhanden ist, wird eine neue Version des Schlüssels von Azure Key Vault erstellt.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="x509Certificates">
            Das Zertifikat oder der Zertifikatskette zum Zusammenführen.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang MergeCertificate führt das Zusammenführen von einem Zertifikat oder der Zertifikatkette mit einem Schlüsselpaar, die zurzeit in den Dienst verfügbar.
            Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
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
        <param name="vaultBaseUrl">Die URL für den Tresor mit dem Zertifikat</param>
        <param name="certificateName">Der Name des Zertifikats</param>
        <param name="x509Certificates">Das Zertifikat oder der Kette Certificte zusammenführen</param>
        <param name="certificateAttributes">Die Attribute des Zertifikats (optional)</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Führt ein Zertifikat oder eine Zertifikatkette mit einem Schlüsselpaar aus, auf dem Server vorhandenen zusammen.
            </summary>
        <returns>Eine Antwortnachricht mit dem zusammengeführten Zertifikat.</returns>
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
        <param name="recoveryId">Die RecoveryId des gelöschten Zertifikats löschen zurückgegeben.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Löscht das gelöschte Zertifikat sofort an.
            </summary>
        <returns>Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht das angegebene Zertifikat gelöschte.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang PurgeDeletedCertificate führt eine Löschung des angegebenen Zertifikats, ohne Möglichkeit zur Wiederherstellung. Der Vorgang ist nicht verfügbar, wenn die Wiederherstellung Ebene keine "Purgeable" angibt.
            Erfordert die explizite erteilen der Berechtigung "löschen".
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
        <param name="recoveryId">Die RecoveryId des gelöschten Schlüssels zurückgegeben löschen.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Löscht den gelöschten Schlüssel sofort an.
            </summary>
        <returns>Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht den angegebenen Schlüssel. d. h. löscht den Schlüssel. Autorisierung: Ist der Schlüssel/löschen-Berechtigung erforderlich.
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
        <param name="recoveryId">Die RecoveryId des gelöschten geheimen Schlüssels zurückgegeben löschen.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Löscht den gelöschten geheimen sofort an.
            </summary>
        <returns>Aufgabe, die die asynchrone Ausführung der Anforderung darstellt.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Dauerhaft löscht den angegebenen Schlüssel. AKA löscht den geheimen Schlüssel ein.
            Autorisierung: ist der geheime Schlüssel/löschen-Berechtigung erforderlich.
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
        <param name="recoveryId">Die RecoveryId des gelöschten Zertifikats löschen zurückgegeben.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Wird das gelöschte Zertifikat wiederhergestellt.
            </summary>
        <returns>Eine Antwortnachricht mit dem wiederhergestellten Zertifikat</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des gelöschten Zertifikats
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird das gelöschte Zertifikat an die aktuelle Version unter Zertifikatinhaber wiederhergestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die RecoverDeletedCertificate werden die Umkehrung der Löschvorgang durchgeführt. Der Vorgang gilt in Tresoren, die für die Soft-Delete aktiviert und während das beibehaltungsintervall (verfügbar in der gelöschten Zertifikats Attribute) ausgegeben werden muss.
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
        <param name="recoveryId">Die RecoveryId des gelöschten Schlüssels zurückgegeben löschen.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Wird den gelöschten Schlüssel wiederhergestellt.
            </summary>
        <returns>Eine Antwortnachricht mit dem wiederhergestellten Schlüssel</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des gelöschten Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird die gelöschten Schlüssel wieder mit ihrer aktuellen Version unter/Keys wiederhergestellt.
            Autorisierung: Ist der Schlüssel/Recover-Berechtigung erforderlich.
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
        <param name="recoveryId">Die RecoveryId des gelöschten geheimen Schlüssels zurückgegeben löschen.</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Wird den gelöschten geheime Schlüssel wiederhergestellt.
            </summary>
        <returns>Eine Antwortnachricht, die den wiederhergestellten geheimen Schlüssel enthält.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des gelöschten geheimen Schlüssels
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Wird die gelöschte geheimen wieder mit ihrer aktuellen Version unter "/ Secrets" wiederhergestellt.
            Autorisierung: ist der geheime Schlüssel/Recover-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="keyName">
            Name des Speicherkontos Schlüssel.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Generiert die angegebenen Schlüsselwert für das angegebene Speicherkonto neu.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyBundleBackup">
            Der Blob-Sicherungsdatei eine wichtige Paket zugeordnet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Importiert einen zuvor gesicherten Schlüssel in Azure Key Vault, den Schlüssel, der den Schlüsselbezeichner, Attribute und Zugriffssteuerungsrichtlinien wiederhergestellt. Der Wiederherstellungsvorgang kann verwendet werden, um einen zuvor gesicherten Schlüssel zu importieren. Einzelne Versionen eines Schlüssels können nicht wiederhergestellt werden. Der Schlüssel wird in seiner Gesamtheit mit demselben Schlüsselnamen wiederhergestellt, wie er hatte, als er gesichert wurde. Wenn Sie nicht den Namen des Schlüssels im zielschlüsseltresor verfügbar ist, wird der RESTORE-Vorgang abgelehnt. Während der Schlüsselname während der Wiederherstellung beibehalten wird, ändert die endgültige Schlüsselbezeichner, wenn der Schlüssel in einem anderen Tresor wiederhergestellt wird. Wiederherstellen werden alle Versionen wiederherstellen und erhält die Versionsbezeichner. Der RESTORE-Vorgang unterliegt sicherheitseinschränkungen: das Ziel Key Vault muss wie Key Vault Benutzer RESTORE-Berechtigung im zielschlüsseltresor nicht über die Quelle muss durch den gleichen Microsoft Azure-Abonnement besitzen.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretBundleBackup">
            Der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Stellt Sie einen gesicherten Schlüssel in einem Tresor wieder her. Autorisierung: ist der geheime Schlüssel/Restore-Berechtigung erforderlich.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="contacts">
            Die Kontakte für das Zertifikat des Key Vault.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Legt die Kontakte Zertifikat für den angegebenen schlüsseltresor fest. Autorisierung: erfordert die Zertifikate/Managecontacts-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="provider">
            Der Aussteller-Anbieter.
            </param>
        <param name="credentials">
            Die Anmeldeinformationen für den Aussteller verwendet werden soll.
            </param>
        <param name="organizationDetails">
            Details der Organisation wie an den Aussteller angegeben.
            </param>
        <param name="attributes">
            Attribute des Ausstellers-Objekts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den angegebenen Zertifikataussteller fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der Vorgang SetCertificateIssuer fügt hinzu oder aktualisiert den Aussteller des angegebenen Zertifikats.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="parameters">
            SAS-Definition Erstellung Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="sasDefinitionAttributes">
            Die Attribute der SAS-Definition.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert eine neue SAS-Definition für das angegebene Speicherkonto.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="value">
            Der Wert des geheimen Schlüssels.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="contentType">
            Typ des Werts für den geheimen z. B. eines Kennworts.
            </param>
        <param name="secretAttributes">
            Die Attribute für den geheimen Management.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt einen geheimen Schlüssel in einer angegebenen schlüsseltresor fest.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der SET-Vorgang hinzugefügt der Azure-Schlüsseltresor einen geheimer Schlüssel. Wenn der benannte geheime Schlüssel bereits vorhanden ist, erstellt Azure-Schlüsseltresor eine neue Version des geheimen Schlüssels.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="resourceId">
            Ressourcen-Id des Speicher-Konto.
            </param>
        <param name="activeKeyName">
            Aktuelle aktive Key Name des Speicherkontos.
            </param>
        <param name="autoRegenerateKey">
            Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.
            </param>
        <param name="regenerationPeriod">
            Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.
            </param>
        <param name="storageAccountAttributes">
            Die Attribute des Speicherkontos.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt oder aktualisiert ein neues Speicherkonto.
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
        <param name="keyIdentifier"> Der globale Schlüsselbezeichner des den Signaturschlüssel </param>
        <param name="algorithm">Den Signaturalgorithmus. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm. </param>
        <param name="digest">Der Digest-Wert zum Signieren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel im Tresor
            </summary>
        <returns>der Wert der Signatur</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Die ID des Signieren/überprüfen. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm. Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erstellt eine Signatur aus einen Digest mit dem angegebenen Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die Anmelde-Vorgang gilt zwar für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da dieser Vorgang den privaten Teil des Schlüssels verwendet.
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
        <param name="keyIdentifier"> Der globale Schlüsselbezeichner des Schlüssels Wrapping/Entpacken </param>
        <param name="algorithm">Der Unwrap-Algorithmus. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</param>
        <param name="wrappedKey">Der umschlossene symmetrische Schlüssel</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel im Tresor, der anfänglich für wrapping des Schlüssels verwendet wurde.
                </summary>
        <returns>Die entpackte symmetrischen Schlüssel</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Entpackt einen symmetrischen Schlüssel mit dem angegebenen Schlüssel, der ursprünglich für diesen Schlüssel wrapping verwendet wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die UNWRAP-Vorgang unterstützt die Entschlüsselung eines symmetrischen Schlüssels mit dem Zielschlüssel für die Schlüsselverschlüsselung. Dieser Vorgang ist die Umkehrung des WRAP-Vorgangs. Der UNWRAP-Vorgang gilt für asymmetrische und symmetrische Schlüssel in Azure Key Vault gespeichert werden, da er den privaten Teil des Schlüssels verwendet.
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
        <param name="certificateIdentifier">Die URL für das Zertifikat.</param>
        <param name="certificatePolicy">Die Richtlinie für das Zertifikat.</param>
        <param name="certificateAttributes">Die Attribute des Zertifikats (optional)</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Aktualisiert eine Zertifikatversion.
            </summary>
        <returns>Das aktualisierte Zertifikat.</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats im angegebenen schlüsseltresor.
            </param>
        <param name="certificateVersion">
            Die Version des Zertifikats.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="certificateAttributes">
            Die Attribute des Zertifikats (optional).
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attribute, die dem angegebenen Zertifikat zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UpdateCertificate-Vorgang gilt das Update für das angegebene Zertifikat; Beachten Sie, dass die einzigen Elemente, die aktualisiert wird das Zertifikat Attribute sind.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="issuerName">
            Der Name des Ausstellers.
            </param>
        <param name="provider">
            Der Aussteller-Anbieter.
            </param>
        <param name="credentials">
            Die Anmeldeinformationen für den Aussteller verwendet werden soll.
            </param>
        <param name="organizationDetails">
            Details der Organisation wie an den Aussteller angegeben.
            </param>
        <param name="attributes">
            Attribute des Ausstellers-Objekts.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert den Aussteller des angegebenen Zertifikats an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UpdateCertificateIssuer-Vorgang führt ein Update für das angegebene Zertifikat Aussteller-Entität.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats.
            </param>
        <param name="cancellationRequested">
            Gibt an, ob für den Zertifikat-Vorgang ein Abbruch angefordert wurde.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert einen Zertifikat-Vorgang. Autorisierung: erfordert die Zertifikate/Update-Berechtigung.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="certificateName">
            Der Name des Zertifikats in den angegebenen Tresor.
            </param>
        <param name="certificatePolicy">
            Die Richtlinie für das Zertifikat.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Richtlinie für ein Zertifikat an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Festzulegen Sie angegebene Member in der Zertifikatrichtlinie. Belassen Sie andere als Null.
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
        <param name="keyIdentifier">Der Schlüsselbezeichner</param>
        <param name="keyOps">JSON Web Key-Vorgänge. Weitere Informationen finden Sie unter JsonWebKeyOperation.</param>
        <param name="attributes">Die neuen Attribute für den Schlüssel. Weitere Informationen zu den wichtigsten Attributen finden Sie unter KeyAttributes.</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Aktualisiert die Schlüssel-Attribute, die dem angegebenen Schlüssel zugeordnet
            </summary>
        <returns> Die aktualisierten Schlüssel. </returns>
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
        <param name="vaultBaseUrl">Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net</param>
        <param name="keyName">der Name des Schlüssels</param>
        <param name="keyOps">JSON Web Key-Vorgänge. Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.</param>
        <param name="attributes">Die neuen Attribute für den Schlüssel. Weitere Informationen zu den wichtigsten Attributen finden Sie unter KeyAttributes.</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktualisiert die Schlüssel-Attribute, die dem angegebenen Schlüssel zugeordnet
            </summary>
        <returns> Die aktualisierten Schlüssel. </returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name der zu aktualisierende Schlüssel.
            </param>
        <param name="keyVersion">
            Die Version des Schlüssels zu aktualisieren.
            </param>
        <param name="keyOps">
            JSON Web Key-Vorgänge. Weitere Informationen zu möglichen Schlüsselvorgänge finden Sie unter JsonWebKeyOperation.
            </param>
        <param name="keyAttributes"></param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Die Änderungen am Update Schlüsselvorgang angegebene Attribute eines gespeicherten Schlüssels und können auf alle Schlüsseltypen und Schlüssel in Azure Key Vault gespeicherten Version angewendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Um diesen Vorgang auszuführen, muss der Schlüssel bereits im Schlüsseltresor vorhanden sein. Hinweis: Das kryptografische Material eines Schlüssels selbst kann nicht geändert werden.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="sasDefinitionName">
            Der Name der SAS-Definition.
            </param>
        <param name="parameters">
            SAS-definitionsaktualisierung Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="sasDefinitionAttributes">
            Die Attribute der SAS-Definition.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attribute der bestimmten SAS-Definition zugeordnet.
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
        <param name="secretIdentifier">Die URL des geheimen Schlüssels</param>
        <param name="contentType">Typ des Werts für den geheimen z. B. das Kennwort.</param>
        <param name="secretAttributes">Attribute für den geheimen Schlüssel. Weitere Informationen zu möglichen Attributen finden Sie unter SecretAttributes.</param>
        <param name="tags">Anwendungsspezifische Metadaten in Form von Schlüssel-Wert-Paaren</param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Aktualisiert die Attribute, die mit dem angegebenen Schlüssel zugeordnete
            </summary>
        <returns>Eine Antwortnachricht mit den aktualisierten geheimen Schlüssel</returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="secretName">
            Der Name des geheimen Schlüssels.
            </param>
        <param name="secretVersion">
            die Version des geheimen Schlüssels.
            </param>
        <param name="contentType">
            Typ des Werts für den geheimen z. B. eines Kennworts.
            </param>
        <param name="secretAttributes">
            Die Attribute für den geheimen Management.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Attribute, die mit einem angegebenen Schlüssel in einem angegebenen Schlüssel Tresor verknüpft sind.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der UPDATE-Vorgang ändert angegebene Attribute einer vorhandenen gespeicherten, geheimen Schlüssels. Attribute, die nicht in der Anforderung angegeben werden bleiben unverändert. Der Wert eines geheimen Schlüssels selbst kann nicht geändert werden.
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="storageAccountName">
            Der Name des Speicherkontos.
            </param>
        <param name="activeKeyName">
            Der aktuellen aktiven Schlüssel speicherkontoname.
            </param>
        <param name="autoRegenerateKey">
            Gibt an, ob Keyvault das Speicherkonto für den Benutzer verwaltet werden sollen.
            </param>
        <param name="regenerationPeriod">
            Die schlüsselneugenerierung Dauer im ISO 8601-Format angegeben.
            </param>
        <param name="storageAccountAttributes">
            Die Attribute des Speicherkontos.
            </param>
        <param name="tags">
            Anwendung bestimmter Metadaten in Form von Schlüssel-Wert-Paaren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die angegebenen Attributen, die das angegebene Speicherkonto zugeordnet.
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
        <param name="keyIdentifier"> Der globale Schlüsselbezeichner des Schlüssels zum Signieren verwendet </param>
        <param name="algorithm"> Der Algorithmus Signieren/überprüfen. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</param>
        <param name="digest"> Der Hashwert, der zum Signieren verwendet </param>
        <param name="signature"> Die zu überprüfende Signatur </param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Überprüft eine Signatur, die mit dem angegebenen Schlüssel
            </summary>
        <returns> "true", wenn die Signatur verifiziert, "false" ist. </returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Der Algorithmus Signieren/überprüfen. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm. Folgende Werte sind möglich: "PS256", "PS384", "PS512", "RS256", "RS384", "RS512", "RSNULL", "ES256", "ES384", "ES512", "ECDSA256"
            </param>
        <param name="digest">
            Den Hashwert, der zum Signieren verwendet wird.
            </param>
        <param name="signature">
            Die zu überprüfende Signatur.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft eine Signatur, die mithilfe eines angegebenen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Die VERIFY-Vorgang gilt zwar für symmetrische Schlüssel in Azure Key Vault gespeichert. Überprüfen Sie, ob ist nicht unbedingt erforderlich für asymmetrische Schlüssel im Azure-Schlüsseltresor gespeichert sind, da die signaturüberprüfung kann mit dem öffentlichen Teil des Schlüssels ausgeführt werden, aber dieser Vorgang wird als Annehmlichkeit unterstützt, für den Aufrufer, die nur einen Schlüssel-Verweis und nicht die öffentliche Teil des Schlüssels.
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
        <param name="keyIdentifier"> Der globale Schlüsselbezeichner des Schlüssels für Textumbruch für </param>
        <param name="algorithm"> Der Wrap-Algorithmus. Weitere Informationen zu möglichen Algorithmustypen finden Sie unter JsonWebKeySignatureAlgorithm.</param>
        <param name="key"> Der symmetrische Schlüssel </param>
        <param name="cancellationToken">Optionale Abbruchtoken</param>
        <summary>
            Dient als Wrapper für einen symmetrischen Schlüssel mit dem angegebenen Schlüssel
            </summary>
        <returns> Der umschlossene symmetrische Schlüssel </returns>
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
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="vaultBaseUrl">
            Den Namen des sicherungstresors, z. B. https://myvault.vault.azure.net.
            </param>
        <param name="keyName">
            Der Name des Schlüssels.
            </param>
        <param name="keyVersion">
            die Version des Schlüssels.
            </param>
        <param name="algorithm">
            Algorithmusbezeichner. Folgende Werte sind möglich: "RSA-OAEP", "RSA-OAEP-256", "RSA1_5"
            </param>
        <param name="value"></param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Umschließt einen symmetrischen Schlüssel mithilfe eines angegebenen Schlüssels.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Der WRAP-Vorgang unterstützt die Verschlüsselung eines symmetrischen Schlüssels mit einem schlüsselverschlüsselungsschlüssel, der zuvor in einem Azure-Schlüsseltresor gespeichert wurde. Der WRAP-Vorgang ist nur unbedingt notwendig, die für symmetrische Schlüssel in Azure Key Vault gespeichert werden, da der Schutz mit einem asymmetrischen Schlüssel mit dem öffentlichen Teil des Schlüssels ausgeführt werden kann. Dieser Vorgang wird für asymmetrische Schlüssel zur Vereinfachung für Aufrufer unterstützt, die einen Schlüssel-Verweis, aber keinen Zugriff auf das öffentliche Schlüsselmaterial.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>