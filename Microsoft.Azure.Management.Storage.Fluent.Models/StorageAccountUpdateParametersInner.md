<Type Name="StorageAccountUpdateParametersInner" FullName="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner">
  <TypeSignature Language="C#" Value="public class StorageAccountUpdateParametersInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountUpdateParametersInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountUpdateParametersInner" />
  <TypeSignature Language="F#" Value="type StorageAccountUpdateParametersInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="917c8-101">Die Parameter, die beim Aktualisieren der speicherkontoeigenschaften bereitgestellt werden können.</span><span class="sxs-lookup"><span data-stu-id="917c8-101">The parameters that can be provided when updating the storage account properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParametersInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="917c8-102">Initialisiert eine neue Instanz der StorageAccountUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="917c8-102">Initializes a new instance of the StorageAccountUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountUpdateParametersInner (Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption = null, Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Fluent.Models.Sku sku, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption encryption, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; accessTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.#ctor(Microsoft.Azure.Management.Storage.Fluent.Models.Sku,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain,Microsoft.Azure.Management.Storage.Fluent.Models.Encryption,System.Nullable{Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner : Microsoft.Azure.Management.Storage.Fluent.Models.Sku * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain * Microsoft.Azure.Management.Storage.Fluent.Models.Encryption * Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; -&gt; Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner" Usage="new Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner (sku, tags, customDomain, encryption, accessTier)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Sku" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Fluent.Models.Encryption" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;" />
      </Parameters>
      <Docs>
        <param name="sku"><span data-ttu-id="917c8-103">Ruft ab oder legt den SKU-Namen.</span><span class="sxs-lookup"><span data-stu-id="917c8-103">Gets or sets the SKU name.</span></span> <span data-ttu-id="917c8-104">Beachten Sie, dass die SKU-Name kann nicht aktualisiert werden, um "standard_zrs" oder "premium_lrs", noch in einen anderen Wert Konten dieser Sku-Namen aktualisiert werden können.</span><span class="sxs-lookup"><span data-stu-id="917c8-104">Note that the SKU name cannot be updated to Standard_ZRS or Premium_LRS, nor can accounts of those sku names be updated to any other value.</span></span></param>
        <param name="tags"><span data-ttu-id="917c8-105">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben.</span><span class="sxs-lookup"><span data-stu-id="917c8-105">Gets or sets a list of key value pairs that describe the resource.</span></span> <span data-ttu-id="917c8-106">Diese Tags können über Ressourcengruppen hinweg zum Anzeigen und Gruppieren von Ressourcen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="917c8-106">These tags can be used in viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="917c8-107">Für eine Ressource kann maximal 15 Tags bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="917c8-107">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="917c8-108">Jedes Tag muss einen Schlüssel, die nicht größer als 128 Zeichen und einen Wert in der Länge nicht länger als 256 Zeichen lang enthalten.</span><span class="sxs-lookup"><span data-stu-id="917c8-108">Each tag must have a key no greater in length than 128 characters and a value no greater in length than 256 characters.</span></span></param>
        <param name="customDomain"><span data-ttu-id="917c8-109">Benutzerdefinierte Domäne auf das Speicherkonto, das vom Benutzer zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="917c8-109">Custom domain assigned to the storage account by the user.</span></span> <span data-ttu-id="917c8-110">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="917c8-110">Name is the CNAME source.</span></span> <span data-ttu-id="917c8-111">Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt.</span><span class="sxs-lookup"><span data-stu-id="917c8-111">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="917c8-112">Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="917c8-112">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span></param>
        <param name="encryption"><span data-ttu-id="917c8-113">Stellt die Einstellungen für die Verschlüsselung für das Konto an.</span><span class="sxs-lookup"><span data-stu-id="917c8-113">Provides the encryption settings on the account.</span></span> <span data-ttu-id="917c8-114">Die Standardeinstellung ist unverschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="917c8-114">The default setting is unencrypted.</span></span></param>
        <param name="accessTier"><span data-ttu-id="917c8-115">Erforderlich für Speicherkonten, Kind = BlobStorage.</span><span class="sxs-lookup"><span data-stu-id="917c8-115">Required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="917c8-116">Der Access-Ebene für die Abrechnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="917c8-116">The access tier used for billing.</span></span> <span data-ttu-id="917c8-117">Folgende Werte sind möglich: "Hot", "Super"</span><span class="sxs-lookup"><span data-stu-id="917c8-117">Possible values include: 'Hot', 'Cool'</span></span></param>
        <summary>
            <span data-ttu-id="917c8-118">Initialisiert eine neue Instanz der StorageAccountUpdateParametersInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="917c8-118">Initializes a new instance of the StorageAccountUpdateParametersInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Fluent.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="917c8-119">Ruft ab oder legt ihn fest erforderlich, für Speicherkonten, Kind = BlobStorage.</span><span class="sxs-lookup"><span data-stu-id="917c8-119">Gets or sets required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="917c8-120">Der Access-Ebene für die Abrechnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="917c8-120">The access tier used for billing.</span></span> <span data-ttu-id="917c8-121">Folgende Werte sind möglich: "Hot", "Super"</span><span class="sxs-lookup"><span data-stu-id="917c8-121">Possible values include: 'Hot', 'Cool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="917c8-122">Ruft ab, oder legt ihn fest benutzerdefinierten Domäne auf das Speicherkonto, das vom Benutzer zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="917c8-122">Gets or sets custom domain assigned to the storage account by the user.</span></span> <span data-ttu-id="917c8-123">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="917c8-123">Name is the CNAME source.</span></span> <span data-ttu-id="917c8-124">Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt.</span><span class="sxs-lookup"><span data-stu-id="917c8-124">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="917c8-125">Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="917c8-125">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Fluent.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="917c8-126">Ruft ab oder legt stellt die Einstellungen für die Verschlüsselung für das Konto bereit.</span><span class="sxs-lookup"><span data-stu-id="917c8-126">Gets or sets provides the encryption settings on the account.</span></span> <span data-ttu-id="917c8-127">Die Standardeinstellung ist unverschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="917c8-127">The default setting is unencrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Fluent.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="917c8-128">Ruft ab oder legt den SKU-Namen.</span><span class="sxs-lookup"><span data-stu-id="917c8-128">Gets or sets the SKU name.</span></span> <span data-ttu-id="917c8-129">Beachten Sie, dass die SKU-Name kann nicht aktualisiert werden, um "standard_zrs" oder "premium_lrs", noch in einen anderen Wert Konten dieser Sku-Namen aktualisiert werden können.</span><span class="sxs-lookup"><span data-stu-id="917c8-129">Note that the SKU name cannot be updated to Standard_ZRS or Premium_LRS, nor can accounts of those sku names be updated to any other value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="917c8-130">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben.</span><span class="sxs-lookup"><span data-stu-id="917c8-130">Gets or sets a list of key value pairs that describe the resource.</span></span>
            <span data-ttu-id="917c8-131">Diese Tags können über Ressourcengruppen hinweg zum Anzeigen und Gruppieren von Ressourcen verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="917c8-131">These tags can be used in viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="917c8-132">Für eine Ressource kann maximal 15 Tags bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="917c8-132">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="917c8-133">Jedes Tag muss einen Schlüssel, die nicht größer als 128 Zeichen und einen Wert in der Länge nicht länger als 256 Zeichen lang enthalten.</span><span class="sxs-lookup"><span data-stu-id="917c8-133">Each tag must have a key no greater in length than 128 characters and a value no greater in length than 256 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Fluent.Models.StorageAccountUpdateParametersInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountUpdateParametersInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="917c8-134">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="917c8-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="917c8-135">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="917c8-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>