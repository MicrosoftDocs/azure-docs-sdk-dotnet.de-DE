<Type Name="Encryption" FullName="Microsoft.Azure.Management.Storage.Models.Encryption">
  <TypeSignature Language="C#" Value="public class Encryption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Encryption extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Encryption" />
  <TypeSignature Language="VB.NET" Value="Public Class Encryption" />
  <TypeSignature Language="F#" Value="type Encryption = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3e215-101">Die verschlüsselungseinstellungen für das Speicherkonto.</span><span class="sxs-lookup"><span data-stu-id="3e215-101">The encryption settings on the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e215-102">Initialisiert eine neue Instanz der Klasse Verschlüsselung an.</span><span class="sxs-lookup"><span data-stu-id="3e215-102">Initializes a new instance of the Encryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Encryption (string keySource, Microsoft.Azure.Management.Storage.Models.EncryptionServices services = null, Microsoft.Azure.Management.Storage.Models.KeyVaultProperties keyVaultProperties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keySource, class Microsoft.Azure.Management.Storage.Models.EncryptionServices services, class Microsoft.Azure.Management.Storage.Models.KeyVaultProperties keyVaultProperties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.#ctor(System.String,Microsoft.Azure.Management.Storage.Models.EncryptionServices,Microsoft.Azure.Management.Storage.Models.KeyVaultProperties)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Encryption : string * Microsoft.Azure.Management.Storage.Models.EncryptionServices * Microsoft.Azure.Management.Storage.Models.KeyVaultProperties -&gt; Microsoft.Azure.Management.Storage.Models.Encryption" Usage="new Microsoft.Azure.Management.Storage.Models.Encryption (keySource, services, keyVaultProperties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keySource" Type="System.String" />
        <Parameter Name="services" Type="Microsoft.Azure.Management.Storage.Models.EncryptionServices" />
        <Parameter Name="keyVaultProperties" Type="Microsoft.Azure.Management.Storage.Models.KeyVaultProperties" />
      </Parameters>
      <Docs>
        <param name="keySource"><span data-ttu-id="3e215-103">Die Verschlüsselung KeySource (Anbieter).</span><span class="sxs-lookup"><span data-stu-id="3e215-103">The encryption keySource (provider).</span></span>
            <span data-ttu-id="3e215-104">Mögliche Werte (Groß-/Kleinschreibung): Microsoft.Storage, Microsoft.Keyvault.</span><span class="sxs-lookup"><span data-stu-id="3e215-104">Possible values (case-insensitive):  Microsoft.Storage, Microsoft.Keyvault.</span></span> <span data-ttu-id="3e215-105">Folgende Werte sind möglich: "Microsoft.Storage", "Microsoft.Keyvault"</span><span class="sxs-lookup"><span data-stu-id="3e215-105">Possible values include: 'Microsoft.Storage', 'Microsoft.Keyvault'</span></span></param>
        <param name="services"><span data-ttu-id="3e215-106">Liste der Dienste, die Verschlüsselung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="3e215-106">List of services which support encryption.</span></span></param>
        <param name="keyVaultProperties"><span data-ttu-id="3e215-107">Eigenschaften von schlüsseltresor bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3e215-107">Properties provided by key vault.</span></span></param>
        <summary>
            <span data-ttu-id="3e215-108">Initialisiert eine neue Instanz der Klasse Verschlüsselung an.</span><span class="sxs-lookup"><span data-stu-id="3e215-108">Initializes a new instance of the Encryption class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeySource">
      <MemberSignature Language="C#" Value="public string KeySource { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeySource" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.KeySource" />
      <MemberSignature Language="VB.NET" Value="Public Property KeySource As String" />
      <MemberSignature Language="F#" Value="member this.KeySource : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.KeySource" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keySource")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e215-109">Abrufen oder Festlegen der Verschlüsselung KeySource (Anbieter).</span><span class="sxs-lookup"><span data-stu-id="3e215-109">Gets or sets the encryption keySource (provider).</span></span> <span data-ttu-id="3e215-110">Mögliche Werte (Groß-/Kleinschreibung): Microsoft.Storage, Microsoft.Keyvault.</span><span class="sxs-lookup"><span data-stu-id="3e215-110">Possible values (case-insensitive):  Microsoft.Storage, Microsoft.Keyvault.</span></span>
            <span data-ttu-id="3e215-111">Folgende Werte sind möglich: "Microsoft.Storage", "Microsoft.Keyvault"</span><span class="sxs-lookup"><span data-stu-id="3e215-111">Possible values include: 'Microsoft.Storage', 'Microsoft.Keyvault'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyVaultProperties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.KeyVaultProperties KeyVaultProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.KeyVaultProperties KeyVaultProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.KeyVaultProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property KeyVaultProperties As KeyVaultProperties" />
      <MemberSignature Language="F#" Value="member this.KeyVaultProperties : Microsoft.Azure.Management.Storage.Models.KeyVaultProperties with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.KeyVaultProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keyvaultproperties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.KeyVaultProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e215-112">Abrufen oder Festlegen von Eigenschaften, die vom schlüsseltresor bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="3e215-112">Gets or sets properties provided by key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Services">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.EncryptionServices Services { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.EncryptionServices Services" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Encryption.Services" />
      <MemberSignature Language="VB.NET" Value="Public Property Services As EncryptionServices" />
      <MemberSignature Language="F#" Value="member this.Services : Microsoft.Azure.Management.Storage.Models.EncryptionServices with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Encryption.Services" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="services")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.EncryptionServices</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e215-113">Ruft ab oder legt die Liste der Dienste, die Verschlüsselung unterstützt.</span><span class="sxs-lookup"><span data-stu-id="3e215-113">Gets or sets list of services which support encryption.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Encryption.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="encryption.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e215-114">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="3e215-114">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="3e215-115">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="3e215-115">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>