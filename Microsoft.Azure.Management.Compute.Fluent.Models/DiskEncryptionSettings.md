<Type Name="DiskEncryptionSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings">
  <TypeSignature Language="C#" Value="public class DiskEncryptionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DiskEncryptionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class DiskEncryptionSettings" />
  <TypeSignature Language="F#" Value="type DiskEncryptionSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Beschreibt Einstellungen für die Verschlüsselung für einen Datenträger
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskEncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der DiskEncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DiskEncryptionSettings (Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference diskEncryptionKey = null, Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference keyEncryptionKey = null, Nullable&lt;bool&gt; enabled = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference diskEncryptionKey, class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference keyEncryptionKey, valuetype System.Nullable`1&lt;bool&gt; enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference,Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference,System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional diskEncryptionKey As KeyVaultSecretReference = null, Optional keyEncryptionKey As KeyVaultKeyReference = null, Optional enabled As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference * Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings (diskEncryptionKey, keyEncryptionKey, enabled)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="diskEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference" />
        <Parameter Name="keyEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference" />
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="diskEncryptionKey">Der Datenträger Encryption Key, der ein Schlüssel Vault Geheimnis ist.</param>
        <param name="keyEncryptionKey">Die schlüsselverschlüsselungsschlüssel die Key Vault-Schlüssels ist.</param>
        <param name="enabled">Gibt an, ob die datenträgerverschlüsselung auf dem virtuellen Computer aktiviert werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der DiskEncryptionSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference DiskEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference DiskEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.DiskEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskEncryptionKey As KeyVaultSecretReference" />
      <MemberSignature Language="F#" Value="member this.DiskEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.DiskEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="diskEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest die Disk Encryption Key, die eine Key Vault geheime Schlüssel ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            Gibt an, ob es sich bei datenträgerverschlüsselung auf dem virtuellen Computer aktiviert werden soll, ruft ab oder legt ihn fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference KeyEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference KeyEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.KeyEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyEncryptionKey As KeyVaultKeyReference" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.KeyEncryptionKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyEncryptionKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultKeyReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt den Schlüsselverschlüsselung-Schlüssel, der Key Vault-Schlüssels ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="diskEncryptionSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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