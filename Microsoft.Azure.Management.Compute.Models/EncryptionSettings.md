<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.Compute.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Verschlüsselungseinstellungen für Datenträger oder einer Momentaufnahme
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der EncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Nullable&lt;bool&gt; enabled = null, Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference diskEncryptionKey = null, Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference keyEncryptionKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, class Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference diskEncryptionKey, class Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference keyEncryptionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.#ctor(System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference,Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional diskEncryptionKey As KeyVaultAndSecretReference = null, Optional keyEncryptionKey As KeyVaultAndKeyReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Models.EncryptionSettings : Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference * Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference -&gt; Microsoft.Azure.Management.Compute.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.Compute.Models.EncryptionSettings (enabled, diskEncryptionKey, keyEncryptionKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="diskEncryptionKey" Type="Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference" />
        <Parameter Name="keyEncryptionKey" Type="Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference" />
      </Parameters>
      <Docs>
        <param name="enabled">Legen Sie dieses Flag auf "true", und geben Sie DiskEncryptionKey und optionale KeyEncryptionKey, um die Verschlüsselung aktivieren. Legen Sie dieses Flag auf "false", und entfernen Sie DiskEncryptionKey und KeyEncryptionKey, um die Verschlüsselung zu deaktivieren. Wenn EncryptionSettings in das Anforderungsobjekt null ist, bleiben die vorhandenen Einstellungen unverändert.</param>
        <param name="diskEncryptionKey">Key Vault-Schlüssel-Url und Depot-Id des Verschlüsselungsschlüssels für Datenträger</param>
        <param name="keyEncryptionKey">Key Vault-Schlüssel-Url und Depot-Id des Schlüssels Schlüsselverschlüsselung</param>
        <summary>
            Initialisiert eine neue Instanz der EncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference DiskEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference DiskEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.DiskEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskEncryptionKey As KeyVaultAndSecretReference" />
      <MemberSignature Language="F#" Value="member this.DiskEncryptionKey : Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.EncryptionSettings.DiskEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.KeyVaultAndSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, key Vault-Schlüssel-Url und Tresor-Id des Verschlüsselungsschlüssels für Datenträger
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Models.EncryptionSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Legen Sie dieses Flag auf "true", und geben Sie DiskEncryptionKey und optionale KeyEncryptionKey, um die Verschlüsselung aktivieren, ruft ab oder legt ihn fest. Legen Sie dieses Flag auf "false", und entfernen Sie DiskEncryptionKey und KeyEncryptionKey, um die Verschlüsselung zu deaktivieren. Wenn EncryptionSettings in das Anforderungsobjekt null ist, bleiben die vorhandenen Einstellungen unverändert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference KeyEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference KeyEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.KeyEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyEncryptionKey As KeyVaultAndKeyReference" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKey : Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference with get, set" Usage="Microsoft.Azure.Management.Compute.Models.EncryptionSettings.KeyEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.KeyVaultAndKeyReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt key Vault-Schlüssel-Url und die Id des Verschlüsselungsschlüssels für Key vault
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>