<Type Name="VaultProperties" FullName="Microsoft.Azure.Management.KeyVault.Models.VaultProperties">
  <TypeSignature Language="C#" Value="public class VaultProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VaultProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.KeyVault.Models.VaultProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class VaultProperties" />
  <TypeSignature Language="F#" Value="type VaultProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="dbcdb-101">Eigenschaften des Tresors</span><span class="sxs-lookup"><span data-stu-id="dbcdb-101">Properties of the vault</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-102">Initialisiert eine neue Instanz der VaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-102">Initializes a new instance of the VaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VaultProperties (Guid tenantId, Microsoft.Azure.Management.KeyVault.Models.Sku sku, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; accessPolicies = null, string vaultUri = null, Nullable&lt;bool&gt; enabledForDeployment = null, Nullable&lt;bool&gt; enabledForDiskEncryption = null, Nullable&lt;bool&gt; enabledForTemplateDeployment = null, Nullable&lt;bool&gt; enableSoftDelete = null, Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; createMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid tenantId, class Microsoft.Azure.Management.KeyVault.Models.Sku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; accessPolicies, string vaultUri, valuetype System.Nullable`1&lt;bool&gt; enabledForDeployment, valuetype System.Nullable`1&lt;bool&gt; enabledForDiskEncryption, valuetype System.Nullable`1&lt;bool&gt; enabledForTemplateDeployment, valuetype System.Nullable`1&lt;bool&gt; enableSoftDelete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; createMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.#ctor(System.Guid,Microsoft.Azure.Management.KeyVault.Models.Sku,System.Collections.Generic.IList{Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry},System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.KeyVault.Models.CreateMode})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.KeyVault.Models.VaultProperties : Guid * Microsoft.Azure.Management.KeyVault.Models.Sku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; -&gt; Microsoft.Azure.Management.KeyVault.Models.VaultProperties" Usage="new Microsoft.Azure.Management.KeyVault.Models.VaultProperties (tenantId, sku, accessPolicies, vaultUri, enabledForDeployment, enabledForDiskEncryption, enabledForTemplateDeployment, enableSoftDelete, createMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tenantId" Type="System.Guid" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.KeyVault.Models.Sku" />
        <Parameter Name="accessPolicies" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt;" />
        <Parameter Name="vaultUri" Type="System.String" />
        <Parameter Name="enabledForDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForDiskEncryption" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enabledForTemplateDeployment" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableSoftDelete" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="createMode" Type="System.Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt;" />
      </Parameters>
      <Docs>
        <param name="tenantId"><span data-ttu-id="dbcdb-103">Die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-103">The Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span></param>
        <param name="sku"><span data-ttu-id="dbcdb-104">SKU-Informationen</span><span class="sxs-lookup"><span data-stu-id="dbcdb-104">SKU details</span></span></param>
        <param name="accessPolicies"><span data-ttu-id="dbcdb-105">Ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-105">An array of 0 to 16 identities that have access to the key vault.</span></span> <span data-ttu-id="dbcdb-106">Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-106">All identities in the array must use the same tenant ID as the key vault's tenant ID.</span></span></param>
        <param name="vaultUri"><span data-ttu-id="dbcdb-107">Der URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-107">The URI of the vault for performing operations on keys and secrets.</span></span></param>
        <param name="enabledForDeployment"><span data-ttu-id="dbcdb-108">Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-108">Property to specify whether Azure Virtual Machines are permitted to retrieve certificates stored as secrets from the key vault.</span></span></param>
        <param name="enabledForDiskEncryption"><span data-ttu-id="dbcdb-109">Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-109">Property to specify whether Azure Disk Encryption is permitted to retrieve secrets from the vault and unwrap keys.</span></span></param>
        <param name="enabledForTemplateDeployment"><span data-ttu-id="dbcdb-110">Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-110">Property to specify whether Azure Resource Manager is permitted to retrieve secrets from the key vault.</span></span></param>
        <param name="enableSoftDelete"><span data-ttu-id="dbcdb-111">Eigenschaft, um anzugeben, ob die Funktion "vorläufiges löschen" für diesen schlüsseltresor aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-111">Property to specify whether the 'soft delete' functionality is enabled for this key vault.</span></span> <span data-ttu-id="dbcdb-112">Wert "false" werden nicht angenommen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-112">It does not accept false value.</span></span></param>
        <param name="createMode"><span data-ttu-id="dbcdb-113">Der Tresor erstellen Modus, um anzugeben, ob der Tresor oder nicht wiederhergestellt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-113">The vault's create mode to indicate whether the vault need to be recovered or not.</span></span> <span data-ttu-id="dbcdb-114">Folgende Werte sind möglich: 'Wiederherstellen', 'Default'</span><span class="sxs-lookup"><span data-stu-id="dbcdb-114">Possible values include: 'recover', 'default'</span></span></param>
        <summary>
            <span data-ttu-id="dbcdb-115">Initialisiert eine neue Instanz der VaultProperties-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-115">Initializes a new instance of the VaultProperties class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessPolicies">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; AccessPolicies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; AccessPolicies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.AccessPolicies" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessPolicies As IList(Of AccessPolicyEntry)" />
      <MemberSignature Language="F#" Value="member this.AccessPolicies : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.AccessPolicies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="accessPolicies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.KeyVault.Models.AccessPolicyEntry&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-116">Ruft ab oder legt ein Array von 0 bis 16-Identitäten, die Zugriff auf den schlüsseltresor verfügen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-116">Gets or sets an array of 0 to 16 identities that have access to the key vault.</span></span> <span data-ttu-id="dbcdb-117">Alle Identitäten im Array müssen die gleichen Mandanten-ID als die schlüsseltresor-Mandanten-ID verwenden.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-117">All identities in the array must use the same tenant ID as the key vault's tenant ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; CreateMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; CreateMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.CreateMode" />
      <MemberSignature Language="VB.NET" Value="Public Property CreateMode As Nullable(Of CreateMode)" />
      <MemberSignature Language="F#" Value="member this.CreateMode : Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.CreateMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="createMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.KeyVault.Models.CreateMode&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-118">Ruft ab oder legt Erstellen des Tresors Modus, um anzugeben, ob der Tresor oder nicht wiederhergestellt werden müssen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-118">Gets or sets the vault's create mode to indicate whether the vault need to be recovered or not.</span></span> <span data-ttu-id="dbcdb-119">Folgende Werte sind möglich: 'Wiederherstellen', 'Default'</span><span class="sxs-lookup"><span data-stu-id="dbcdb-119">Possible values include: 'recover', 'default'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-120">Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure Virtual Machines zulässig sind, um Zertifikate als geheime Schlüssel aus dem schlüsseltresor gespeicherte abzurufen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-120">Gets or sets property to specify whether Azure Virtual Machines are permitted to retrieve certificates stored as secrets from the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForDiskEncryption">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForDiskEncryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForDiskEncryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForDiskEncryption As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForDiskEncryption : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForDiskEncryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForDiskEncryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-121">Ruft ab, oder legt ihn fest Eigenschaft, um anzugeben, ob Azure Datenträgerverschlüsselung zum Abrufen der geheimen Schlüssel aus dem Tresor und Schlüssel unwrap zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-121">Gets or sets property to specify whether Azure Disk Encryption is permitted to retrieve secrets from the vault and unwrap keys.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledForTemplateDeployment">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnabledForTemplateDeployment { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnabledForTemplateDeployment" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberSignature Language="VB.NET" Value="Public Property EnabledForTemplateDeployment As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnabledForTemplateDeployment : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnabledForTemplateDeployment" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabledForTemplateDeployment")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-122">Ruft ab oder legt die Eigenschaft, um anzugeben, ob Azure-Ressourcen-Manager zum Abrufen der geheimen Schlüssel aus dem schlüsseltresor zulässig ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-122">Gets or sets property to specify whether Azure Resource Manager is permitted to retrieve secrets from the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSoftDelete">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableSoftDelete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableSoftDelete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnableSoftDelete" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableSoftDelete As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableSoftDelete : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.EnableSoftDelete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enableSoftDelete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-123">Ruft ab oder legt die Eigenschaft, um anzugeben, ob die Funktion "vorläufiges löschen" für diesen schlüsseltresor aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-123">Gets or sets property to specify whether the 'soft delete' functionality is enabled for this key vault.</span></span> <span data-ttu-id="dbcdb-124">Wert "false" werden nicht angenommen.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-124">It does not accept false value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.KeyVault.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.KeyVault.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.KeyVault.Models.Sku with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.KeyVault.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-125">Ruft ab oder legt ihn fest SKU-details</span><span class="sxs-lookup"><span data-stu-id="dbcdb-125">Gets or sets SKU details</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantId">
      <MemberSignature Language="C#" Value="public Guid TenantId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid TenantId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.TenantId" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantId As Guid" />
      <MemberSignature Language="F#" Value="member this.TenantId : Guid with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.TenantId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tenantId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-126">Ruft ab oder legt die Azure Active Directory-Mandanten-ID, die zum Authentifizieren von Anforderungen für den schlüsseltresor verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-126">Gets or sets the Azure Active Directory tenant ID that should be used for authenticating requests to the key vault.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="vaultProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dbcdb-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dbcdb-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VaultUri">
      <MemberSignature Language="C#" Value="public string VaultUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VaultUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.KeyVault.Models.VaultProperties.VaultUri" />
      <MemberSignature Language="VB.NET" Value="Public Property VaultUri As String" />
      <MemberSignature Language="F#" Value="member this.VaultUri : string with get, set" Usage="Microsoft.Azure.Management.KeyVault.Models.VaultProperties.VaultUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="vaultUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dbcdb-129">Ruft ab oder legt den URI des Tresors für das Ausführen von Vorgängen für Schlüssel und geheimen Bereiche fest.</span><span class="sxs-lookup"><span data-stu-id="dbcdb-129">Gets or sets the URI of the vault for performing operations on keys and secrets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>