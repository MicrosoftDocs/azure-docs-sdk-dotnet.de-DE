<Type Name="StorageAccountCreateParameters" FullName="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters">
  <TypeSignature Language="C#" Value="public class StorageAccountCreateParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCreateParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCreateParameters" />
  <TypeSignature Language="F#" Value="type StorageAccountCreateParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1ba0e-101">Die Parameter verwendet, wenn ein Speicherkonto erstellen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-101">The parameters used when creating a storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-102">Initialisiert eine neue Instanz der StorageAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-102">Initializes a new instance of the StorageAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCreateParameters (Microsoft.Azure.Management.Storage.Models.Sku sku, Microsoft.Azure.Management.Storage.Models.Kind kind, string location, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Storage.Models.Identity identity = null, Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain = null, Microsoft.Azure.Management.Storage.Models.Encryption encryption = null, Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier = null, Nullable&lt;bool&gt; enableHttpsTrafficOnly = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Storage.Models.Sku sku, valuetype Microsoft.Azure.Management.Storage.Models.Kind kind, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Storage.Models.Identity identity, class Microsoft.Azure.Management.Storage.Models.CustomDomain customDomain, class Microsoft.Azure.Management.Storage.Models.Encryption encryption, class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet networkRuleSet, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; accessTier, valuetype System.Nullable`1&lt;bool&gt; enableHttpsTrafficOnly) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.#ctor(Microsoft.Azure.Management.Storage.Models.Sku,Microsoft.Azure.Management.Storage.Models.Kind,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Storage.Models.Identity,Microsoft.Azure.Management.Storage.Models.CustomDomain,Microsoft.Azure.Management.Storage.Models.Encryption,Microsoft.Azure.Management.Storage.Models.NetworkRuleSet,System.Nullable{Microsoft.Azure.Management.Storage.Models.AccessTier},System.Nullable{System.Boolean})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters : Microsoft.Azure.Management.Storage.Models.Sku * Microsoft.Azure.Management.Storage.Models.Kind * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Storage.Models.Identity * Microsoft.Azure.Management.Storage.Models.CustomDomain * Microsoft.Azure.Management.Storage.Models.Encryption * Microsoft.Azure.Management.Storage.Models.NetworkRuleSet * Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters" Usage="new Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters (sku, kind, location, tags, identity, customDomain, encryption, networkRuleSet, accessTier, enableHttpsTrafficOnly)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Storage.Models.Sku" />
        <Parameter Name="kind" Type="Microsoft.Azure.Management.Storage.Models.Kind" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="identity" Type="Microsoft.Azure.Management.Storage.Models.Identity" />
        <Parameter Name="customDomain" Type="Microsoft.Azure.Management.Storage.Models.CustomDomain" />
        <Parameter Name="encryption" Type="Microsoft.Azure.Management.Storage.Models.Encryption" />
        <Parameter Name="networkRuleSet" Type="Microsoft.Azure.Management.Storage.Models.NetworkRuleSet" />
        <Parameter Name="accessTier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;" />
        <Parameter Name="enableHttpsTrafficOnly" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="sku"><span data-ttu-id="1ba0e-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-103">Required.</span></span> <span data-ttu-id="1ba0e-104">Ruft ab oder legt den Sku-Namen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-104">Gets or sets the sku name.</span></span></param>
        <param name="kind"><span data-ttu-id="1ba0e-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-105">Required.</span></span> <span data-ttu-id="1ba0e-106">Gibt den Typ des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-106">Indicates the type of storage account.</span></span>
            <span data-ttu-id="1ba0e-107">Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</span><span class="sxs-lookup"><span data-stu-id="1ba0e-107">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span></param>
        <param name="location"><span data-ttu-id="1ba0e-108">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-108">Required.</span></span> <span data-ttu-id="1ba0e-109">Ruft ab oder legt den Speicherort der Ressource fest.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-109">Gets or sets the location of the resource.</span></span> <span data-ttu-id="1ba0e-110">Dies ist einer der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</span><span class="sxs-lookup"><span data-stu-id="1ba0e-110">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="1ba0e-111">Die geografische Region für eine Ressource kann nicht geändert werden, nachdem er erstellt, aber wenn Sie eine identische geografische Region für Update angegeben ist, wird die Anforderung erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-111">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span></param>
        <param name="tags"><span data-ttu-id="1ba0e-112">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-112">Gets or sets a list of key value pairs that describe the resource.</span></span> <span data-ttu-id="1ba0e-113">Diese Tags können verwendet werden, für die Anzeige und gruppieren diese Ressource (über Ressourcengruppen hinweg).</span><span class="sxs-lookup"><span data-stu-id="1ba0e-113">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="1ba0e-114">Für eine Ressource kann maximal 15 Tags bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-114">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="1ba0e-115">Jedes Tag muss es sich um einen Schlüssel mit einer Länge von 128 Zeichen nicht überschreiten und einen Wert mit einer Länge von maximal 256 Zeichen verfügen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-115">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span></param>
        <param name="identity"><span data-ttu-id="1ba0e-116">Die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-116">The identity of the resource.</span></span></param>
        <param name="customDomain"><span data-ttu-id="1ba0e-117">Die Domäne des Benutzers, dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-117">User domain assigned to the storage account.</span></span> <span data-ttu-id="1ba0e-118">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-118">Name is the CNAME source.</span></span> <span data-ttu-id="1ba0e-119">Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-119">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="1ba0e-120">Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-120">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span></param>
        <param name="encryption"><span data-ttu-id="1ba0e-121">Stellt die Einstellungen für die Verschlüsselung für das Konto an.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-121">Provides the encryption settings on the account.</span></span> <span data-ttu-id="1ba0e-122">Wenn die Verschlüsselung kontoeinstellungen bleibt gleich nicht angegeben.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-122">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="1ba0e-123">Die Standardeinstellung ist unverschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-123">The default setting is unencrypted.</span></span></param>
        <param name="networkRuleSet"><span data-ttu-id="1ba0e-124">Netzwerk-Regelsatz</span><span class="sxs-lookup"><span data-stu-id="1ba0e-124">Network rule set</span></span></param>
        <param name="accessTier"><span data-ttu-id="1ba0e-125">Erforderlich für Speicherkonten, Kind = BlobStorage.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-125">Required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="1ba0e-126">Der Access-Ebene für die Abrechnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-126">The access tier used for billing.</span></span> <span data-ttu-id="1ba0e-127">Folgende Werte sind möglich: "Hot", "Super"</span><span class="sxs-lookup"><span data-stu-id="1ba0e-127">Possible values include: 'Hot', 'Cool'</span></span></param>
        <param name="enableHttpsTrafficOnly"><span data-ttu-id="1ba0e-128">Https-Datenverkehr nur für Storage-Dienst ermöglicht, wenn auf "true" festgelegt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-128">Allows https traffic only to storage service if sets to true.</span></span></param>
        <summary>
            <span data-ttu-id="1ba0e-129">Initialisiert eine neue Instanz der StorageAccountCreateParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-129">Initializes a new instance of the StorageAccountCreateParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.AccessTier&gt; AccessTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.AccessTier" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTier As Nullable(Of AccessTier)" />
      <MemberSignature Language="F#" Value="member this.AccessTier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.AccessTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessTier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.AccessTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-130">Ruft ab oder legt ihn fest erforderlich, für Speicherkonten, Kind = BlobStorage.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-130">Gets or sets required for storage accounts where kind = BlobStorage.</span></span> <span data-ttu-id="1ba0e-131">Der Access-Ebene für die Abrechnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-131">The access tier used for billing.</span></span> <span data-ttu-id="1ba0e-132">Folgende Werte sind möglich: "Hot", "Super"</span><span class="sxs-lookup"><span data-stu-id="1ba0e-132">Possible values include: 'Hot', 'Cool'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.CustomDomain CustomDomain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.CustomDomain" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomDomain As CustomDomain" />
      <MemberSignature Language="F#" Value="member this.CustomDomain : Microsoft.Azure.Management.Storage.Models.CustomDomain with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.CustomDomain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customDomain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.CustomDomain</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-133">Abrufen oder Festlegen der Domäne des Benutzers mit dem Speicherkonto zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-133">Gets or sets user domain assigned to the storage account.</span></span> <span data-ttu-id="1ba0e-134">Der Name ist der CNAME-Quelle.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-134">Name is the CNAME source.</span></span> <span data-ttu-id="1ba0e-135">Pro Speicherkonto wird nur eine benutzerdefinierte Domäne zu diesem Zeitpunkt unterstützt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-135">Only one custom domain is supported per storage account at this time.</span></span> <span data-ttu-id="1ba0e-136">Um die vorhandene benutzerdefinierte Domäne zu löschen, verwenden Sie eine leere Zeichenfolge für die benutzerdefinierte Domäne Name-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-136">To clear the existing custom domain, use an empty string for the custom domain name property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableHttpsTrafficOnly">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableHttpsTrafficOnly { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableHttpsTrafficOnly" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.EnableHttpsTrafficOnly" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableHttpsTrafficOnly As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableHttpsTrafficOnly : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.EnableHttpsTrafficOnly" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.supportsHttpsTrafficOnly")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-137">Ruft ab oder legt ermöglicht Https-Datenverkehr nur für Storage-Dienst auf, wenn auf "true" festgelegt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-137">Gets or sets allows https traffic only to storage service if sets to true.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encryption">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Encryption Encryption { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Encryption Encryption" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Encryption" />
      <MemberSignature Language="VB.NET" Value="Public Property Encryption As Encryption" />
      <MemberSignature Language="F#" Value="member this.Encryption : Microsoft.Azure.Management.Storage.Models.Encryption with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Encryption" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.encryption")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Encryption</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-138">Ruft ab oder legt stellt die Einstellungen für die Verschlüsselung für das Konto bereit.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-138">Gets or sets provides the encryption settings on the account.</span></span> <span data-ttu-id="1ba0e-139">Wenn die Verschlüsselung kontoeinstellungen bleibt gleich nicht angegeben.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-139">If left unspecified the account encryption settings will remain the same.</span></span> <span data-ttu-id="1ba0e-140">Die Standardeinstellung ist unverschlüsselt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-140">The default setting is unencrypted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Identity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Identity Identity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Identity Identity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Identity" />
      <MemberSignature Language="VB.NET" Value="Public Property Identity As Identity" />
      <MemberSignature Language="F#" Value="member this.Identity : Microsoft.Azure.Management.Storage.Models.Identity with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Identity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="identity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Identity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-141">Ruft ab oder legt die Identität der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-141">Gets or sets the identity of the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Kind Kind { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.Kind Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Kind" />
      <MemberSignature Language="VB.NET" Value="Public Property Kind As Kind" />
      <MemberSignature Language="F#" Value="member this.Kind : Microsoft.Azure.Management.Storage.Models.Kind with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="kind")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Kind</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-142">Ruft ab oder legt erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-142">Gets or sets required.</span></span> <span data-ttu-id="1ba0e-143">Gibt den Typ des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-143">Indicates the type of storage account.</span></span>
            <span data-ttu-id="1ba0e-144">Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</span><span class="sxs-lookup"><span data-stu-id="1ba0e-144">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Location">
      <MemberSignature Language="C#" Value="public string Location { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Location" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Location" />
      <MemberSignature Language="VB.NET" Value="Public Property Location As String" />
      <MemberSignature Language="F#" Value="member this.Location : string with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Location" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="location")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-145">Ruft ab oder legt erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-145">Gets or sets required.</span></span> <span data-ttu-id="1ba0e-146">Ruft ab oder legt den Speicherort der Ressource fest.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-146">Gets or sets the location of the resource.</span></span>
            <span data-ttu-id="1ba0e-147">Dies ist einer der unterstützten und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</span><span class="sxs-lookup"><span data-stu-id="1ba0e-147">This will be one of the supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span> <span data-ttu-id="1ba0e-148">Die geografische Region für eine Ressource kann nicht geändert werden, nachdem er erstellt, aber wenn Sie eine identische geografische Region für Update angegeben ist, wird die Anforderung erfolgreich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-148">The geo region of a resource cannot be changed once it is created, but if an identical geo region is specified on update, the request will succeed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkRuleSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.NetworkRuleSet NetworkRuleSet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.NetworkRuleSet" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkRuleSet As NetworkRuleSet" />
      <MemberSignature Language="F#" Value="member this.NetworkRuleSet : Microsoft.Azure.Management.Storage.Models.NetworkRuleSet with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.NetworkRuleSet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkAcls")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.NetworkRuleSet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-149">Ruft ab oder legt Netzwerk-Regelsatz</span><span class="sxs-lookup"><span data-stu-id="1ba0e-149">Gets or sets network rule set</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Storage.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Storage.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1ba0e-150">Ruft ab oder legt erforderlich.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-150">Gets or sets required.</span></span> <span data-ttu-id="1ba0e-151">Ruft ab oder legt den Sku-Namen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-151">Gets or sets the sku name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tags">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Tags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Tags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Tags" />
      <MemberSignature Language="VB.NET" Value="Public Property Tags As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Tags : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Tags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="1ba0e-152">Ruft ab oder legt eine Liste von Schlüssel-Wert-Paaren, die die Ressource beschreiben.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-152">Gets or sets a list of key value pairs that describe the resource.</span></span>
            <span data-ttu-id="1ba0e-153">Diese Tags können verwendet werden, für die Anzeige und gruppieren diese Ressource (über Ressourcengruppen hinweg).</span><span class="sxs-lookup"><span data-stu-id="1ba0e-153">These tags can be used for viewing and grouping this resource (across resource groups).</span></span> <span data-ttu-id="1ba0e-154">Für eine Ressource kann maximal 15 Tags bereitgestellt werden.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-154">A maximum of 15 tags can be provided for a resource.</span></span> <span data-ttu-id="1ba0e-155">Jedes Tag muss es sich um einen Schlüssel mit einer Länge von 128 Zeichen nicht überschreiten und einen Wert mit einer Länge von maximal 256 Zeichen verfügen.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-155">Each tag must have a key with a length no greater than 128 characters and a value with a length no greater than 256 characters.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.StorageAccountCreateParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCreateParameters.Validate " />
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
            <span data-ttu-id="1ba0e-156">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1ba0e-156">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1ba0e-157">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1ba0e-157">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>