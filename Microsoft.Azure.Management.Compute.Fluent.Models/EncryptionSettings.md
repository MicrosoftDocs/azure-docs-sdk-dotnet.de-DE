<Type Name="EncryptionSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings">
  <TypeSignature Language="C#" Value="public class EncryptionSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EncryptionSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class EncryptionSettings" />
  <TypeSignature Language="F#" Value="type EncryptionSettings = class" />
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
            <span data-ttu-id="5c781-101">Verschlüsselungseinstellungen für Datenträger oder einer Momentaufnahme</span><span class="sxs-lookup"><span data-stu-id="5c781-101">Encryption settings for disk or snapshot</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5c781-102">Initialisiert eine neue Instanz der EncryptionSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5c781-102">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EncryptionSettings (Nullable&lt;bool&gt; enabled = null, Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference diskEncryptionKey = null, Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference keyEncryptionKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference diskEncryptionKey, class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference keyEncryptionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.#ctor(System.Nullable{System.Boolean},Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference,Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional enabled As Nullable(Of Boolean) = null, Optional diskEncryptionKey As KeyVaultAndSecretReference = null, Optional keyEncryptionKey As KeyVaultAndKeyReference = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings : Nullable&lt;bool&gt; * Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference * Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings (enabled, diskEncryptionKey, keyEncryptionKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="diskEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference" />
        <Parameter Name="keyEncryptionKey" Type="Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference" />
      </Parameters>
      <Docs>
        <param name="enabled"><span data-ttu-id="5c781-103">Legen Sie dieses Flag auf "true", und geben Sie DiskEncryptionKey und optionale KeyEncryptionKey, um die Verschlüsselung aktivieren.</span><span class="sxs-lookup"><span data-stu-id="5c781-103">Set this flag to true and provide DiskEncryptionKey and optional KeyEncryptionKey to enable encryption.</span></span> <span data-ttu-id="5c781-104">Legen Sie dieses Flag auf "false", und entfernen Sie DiskEncryptionKey und KeyEncryptionKey, um die Verschlüsselung zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="5c781-104">Set this flag to false and remove DiskEncryptionKey and KeyEncryptionKey to disable encryption.</span></span> <span data-ttu-id="5c781-105">Wenn EncryptionSettings in das Anforderungsobjekt null ist, bleiben die vorhandenen Einstellungen unverändert.</span><span class="sxs-lookup"><span data-stu-id="5c781-105">If EncryptionSettings is null in the request object, the existing settings remain unchanged.</span></span></param>
        <param name="diskEncryptionKey"><span data-ttu-id="5c781-106">Key Vault-Schlüssel-Url und Depot-Id des Verschlüsselungsschlüssels für Datenträger</span><span class="sxs-lookup"><span data-stu-id="5c781-106">Key Vault Secret Url and vault id of the disk encryption key</span></span></param>
        <param name="keyEncryptionKey"><span data-ttu-id="5c781-107">Key Vault-Schlüssel-Url und Depot-Id des Schlüssels Schlüsselverschlüsselung</span><span class="sxs-lookup"><span data-stu-id="5c781-107">Key Vault Key Url and vault id of the key encryption key</span></span></param>
        <summary>
            <span data-ttu-id="5c781-108">Initialisiert eine neue Instanz der EncryptionSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5c781-108">Initializes a new instance of the EncryptionSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DiskEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference DiskEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference DiskEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.DiskEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property DiskEncryptionKey As KeyVaultAndSecretReference" />
      <MemberSignature Language="F#" Value="member this.DiskEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.DiskEncryptionKey" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndSecretReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c781-109">Ruft ab oder legt sie fest, key Vault-Schlüssel-Url und Tresor-Id des Verschlüsselungsschlüssels für Datenträger</span><span class="sxs-lookup"><span data-stu-id="5c781-109">Gets or sets key Vault Secret Url and vault id of the disk encryption key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Enabled" />
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
            <span data-ttu-id="5c781-110">Legen Sie dieses Flag auf "true", und geben Sie DiskEncryptionKey und optionale KeyEncryptionKey, um die Verschlüsselung aktivieren, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="5c781-110">Gets or sets set this flag to true and provide DiskEncryptionKey and optional KeyEncryptionKey to enable encryption.</span></span> <span data-ttu-id="5c781-111">Legen Sie dieses Flag auf "false", und entfernen Sie DiskEncryptionKey und KeyEncryptionKey, um die Verschlüsselung zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="5c781-111">Set this flag to false and remove DiskEncryptionKey and KeyEncryptionKey to disable encryption.</span></span> <span data-ttu-id="5c781-112">Wenn EncryptionSettings in das Anforderungsobjekt null ist, bleiben die vorhandenen Einstellungen unverändert.</span><span class="sxs-lookup"><span data-stu-id="5c781-112">If EncryptionSettings is null in the request object, the existing settings remain unchanged.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyEncryptionKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference KeyEncryptionKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference KeyEncryptionKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.KeyEncryptionKey" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyEncryptionKey As KeyVaultAndKeyReference" />
      <MemberSignature Language="F#" Value="member this.KeyEncryptionKey : Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.KeyEncryptionKey" />
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
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.KeyVaultAndKeyReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5c781-113">Ruft ab oder legt key Vault-Schlüssel-Url und die Id des Verschlüsselungsschlüssels für Key vault</span><span class="sxs-lookup"><span data-stu-id="5c781-113">Gets or sets key Vault Key Url and vault id of the key encryption key</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.EncryptionSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryptionSettings.Validate " />
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
            <span data-ttu-id="5c781-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5c781-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5c781-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5c781-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>