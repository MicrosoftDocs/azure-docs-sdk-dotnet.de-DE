<Type Name="SecretRestoreParameters" FullName="Microsoft.Azure.KeyVault.Models.SecretRestoreParameters">
  <TypeSignature Language="C#" Value="public class SecretRestoreParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecretRestoreParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.SecretRestoreParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class SecretRestoreParameters" />
  <TypeSignature Language="F#" Value="type SecretRestoreParameters = class" />
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
            <span data-ttu-id="07e25-101">Die Wiederherstellungsparameter für den geheimen.</span><span class="sxs-lookup"><span data-stu-id="07e25-101">The secret restore parameters.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretRestoreParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretRestoreParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07e25-102">Initialisiert eine neue Instanz der SecretRestoreParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07e25-102">Initializes a new instance of the SecretRestoreParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecretRestoreParameters (byte[] secretBundleBackup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(unsigned int8[] secretBundleBackup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretRestoreParameters.#ctor(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (secretBundleBackup As Byte())" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.SecretRestoreParameters : byte[] -&gt; Microsoft.Azure.KeyVault.Models.SecretRestoreParameters" Usage="new Microsoft.Azure.KeyVault.Models.SecretRestoreParameters secretBundleBackup" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="secretBundleBackup" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="secretBundleBackup"><span data-ttu-id="07e25-103">Der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="07e25-103">The backup blob associated with a secret bundle.</span></span></param>
        <summary>
            <span data-ttu-id="07e25-104">Initialisiert eine neue Instanz der SecretRestoreParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="07e25-104">Initializes a new instance of the SecretRestoreParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecretBundleBackup">
      <MemberSignature Language="C#" Value="public byte[] SecretBundleBackup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] SecretBundleBackup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.SecretRestoreParameters.SecretBundleBackup" />
      <MemberSignature Language="VB.NET" Value="Public Property SecretBundleBackup As Byte()" />
      <MemberSignature Language="F#" Value="member this.SecretBundleBackup : byte[] with get, set" Usage="Microsoft.Azure.KeyVault.Models.SecretRestoreParameters.SecretBundleBackup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Microsoft.Rest.Serialization.Base64UrlJsonConverter))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="07e25-105">Abrufen oder Festlegen der Blob-Sicherungsdatei für den geheimen Paket zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="07e25-105">Gets or sets the backup blob associated with a secret bundle.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.SecretRestoreParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="secretRestoreParameters.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="07e25-106">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="07e25-106">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="07e25-107">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="07e25-107">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>