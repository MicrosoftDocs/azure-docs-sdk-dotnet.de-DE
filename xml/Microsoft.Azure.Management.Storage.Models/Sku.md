<Type Name="Sku" FullName="Microsoft.Azure.Management.Storage.Models.Sku">
  <TypeSignature Language="C#" Value="public class Sku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Sku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Sku" />
  <TypeSignature Language="VB.NET" Value="Public Class Sku" />
  <TypeSignature Language="F#" Value="type Sku = class" />
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
            <span data-ttu-id="64758-101">Die SKU des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="64758-101">The SKU of the storage account.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="64758-102">Initialisiert eine neue Instanz der Sku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="64758-102">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Sku (Microsoft.Azure.Management.Storage.Models.SkuName name, Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier = null, string resourceType = null, Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; kind = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Storage.Models.SkuName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; tier, string resourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; kind, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; capabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; restrictions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.#ctor(Microsoft.Azure.Management.Storage.Models.SkuName,System.Nullable{Microsoft.Azure.Management.Storage.Models.SkuTier},System.String,System.Nullable{Microsoft.Azure.Management.Storage.Models.Kind},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.SKUCapability},System.Collections.Generic.IList{Microsoft.Azure.Management.Storage.Models.Restriction})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As SkuName, Optional tier As Nullable(Of SkuTier) = null, Optional resourceType As String = null, Optional kind As Nullable(Of Kind) = null, Optional locations As IList(Of String) = null, Optional capabilities As IList(Of SKUCapability) = null, Optional restrictions As IList(Of Restriction) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Sku : Microsoft.Azure.Management.Storage.Models.SkuName * Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; * string * Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; -&gt; Microsoft.Azure.Management.Storage.Models.Sku" Usage="new Microsoft.Azure.Management.Storage.Models.Sku (name, tier, resourceType, kind, locations, capabilities, restrictions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.Storage.Models.SkuName" />
        <Parameter Name="tier" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" />
        <Parameter Name="resourceType" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" />
        <Parameter Name="restrictions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="64758-103">Ruft ab oder legt den Sku-Namen.</span><span class="sxs-lookup"><span data-stu-id="64758-103">Gets or sets the sku name.</span></span> <span data-ttu-id="64758-104">Für die kontoerstellung erforderlich; Dies ist optional für das Update.</span><span class="sxs-lookup"><span data-stu-id="64758-104">Required for account creation; optional for update.</span></span> <span data-ttu-id="64758-105">Beachten Sie, dass in früheren Versionen können Sku-Name AccountType aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="64758-105">Note that in older versions, sku name was called accountType.</span></span> <span data-ttu-id="64758-106">Folgende Werte sind möglich: "Standard_LRS", "Standard_GRS", "Standard_RAGRS", "standard_zrs" "", "premium_lrs" ""</span><span class="sxs-lookup"><span data-stu-id="64758-106">Possible values include: 'Standard_LRS', 'Standard_GRS', 'Standard_RAGRS', 'Standard_ZRS', 'Premium_LRS'</span></span></param>
        <param name="tier"><span data-ttu-id="64758-107">Ruft die Sku-Tarif.</span><span class="sxs-lookup"><span data-stu-id="64758-107">Gets the sku tier.</span></span> <span data-ttu-id="64758-108">Dies basiert auf der SKU-Name.</span><span class="sxs-lookup"><span data-stu-id="64758-108">This is based on the SKU name.</span></span> <span data-ttu-id="64758-109">Folgende Werte sind möglich: "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="64758-109">Possible values include: 'Standard', 'Premium'</span></span></param>
        <param name="resourceType"><span data-ttu-id="64758-110">Der Typ der Ressource, in der Regel ist "storageaccounts werden".</span><span class="sxs-lookup"><span data-stu-id="64758-110">The type of the resource, usually it is 'storageAccounts'.</span></span></param>
        <param name="kind"><span data-ttu-id="64758-111">Gibt den Typ des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="64758-111">Indicates the type of storage account.</span></span> <span data-ttu-id="64758-112">Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</span><span class="sxs-lookup"><span data-stu-id="64758-112">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span></param>
        <param name="locations"><span data-ttu-id="64758-113">Der Satz von Speicherorten, dass die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="64758-113">The set of locations that the SKU is available.</span></span> <span data-ttu-id="64758-114">Dies wird unterstützt und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</span><span class="sxs-lookup"><span data-stu-id="64758-114">This will be supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span></param>
        <param name="capabilities"><span data-ttu-id="64758-115">Informationen über die Funktionen in der angegebenen Sku, einschließlich Verschlüsselung, Netzwerk-Acls, die Benachrichtigung.</span><span class="sxs-lookup"><span data-stu-id="64758-115">The capability information in the specified sku, including file encryption, network acls, change notification, etc.</span></span></param>
        <param name="restrictions"><span data-ttu-id="64758-116">Die Einschränkungen aufgrund, die SKU verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="64758-116">The restrictions because of which SKU cannot be used.</span></span> <span data-ttu-id="64758-117">Dies ist leer, wenn es keine Einschränkungen gibt.</span><span class="sxs-lookup"><span data-stu-id="64758-117">This is empty if there are no restrictions.</span></span></param>
        <summary>
            <span data-ttu-id="64758-118">Initialisiert eine neue Instanz der Sku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="64758-118">Initializes a new instance of the Sku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.SKUCapability&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capabilities As IList(Of SKUCapability)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.SKUCapability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-119">Ruft Informationen über die Funktionen in der angegebenen Sku, einschließlich Verschlüsselung, Netzwerk-Acls, die Benachrichtigung ab.</span><span class="sxs-lookup"><span data-stu-id="64758-119">Gets the capability information in the specified sku, including file encryption, network acls, change notification, etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.Kind&gt; Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As Nullable(Of Kind)" />
      <MemberSignature Language="F#" Value="member this.Kind : Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Kind" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.Kind&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-120">Ruft gibt den Typ des Speicherkontos.</span><span class="sxs-lookup"><span data-stu-id="64758-120">Gets indicates the type of storage account.</span></span> <span data-ttu-id="64758-121">Folgende Werte sind möglich: "Storage", "StorageV2", "BlobStorage"</span><span class="sxs-lookup"><span data-stu-id="64758-121">Possible values include: 'Storage', 'StorageV2', 'BlobStorage'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-122">Ruft die Gruppe von Standorten, dass die SKU verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="64758-122">Gets the set of locations that the SKU is available.</span></span> <span data-ttu-id="64758-123">Dies wird unterstützt und registrierten geografische Azure-Regionen (z. B. Westen USA, Osten USA, Südostasien usw.).</span><span class="sxs-lookup"><span data-stu-id="64758-123">This will be supported and registered Azure Geo Regions (e.g. West US, East US, Southeast Asia, etc.).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Storage.Models.SkuName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Storage.Models.SkuName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As SkuName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Storage.Models.SkuName with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Storage.Models.SkuName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-124">Ruft ab oder legt den Sku-Namen.</span><span class="sxs-lookup"><span data-stu-id="64758-124">Gets or sets the sku name.</span></span> <span data-ttu-id="64758-125">Für die kontoerstellung erforderlich; Dies ist optional für das Update.</span><span class="sxs-lookup"><span data-stu-id="64758-125">Required for account creation; optional for update.</span></span> <span data-ttu-id="64758-126">Beachten Sie, dass in früheren Versionen können Sku-Name AccountType aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="64758-126">Note that in older versions, sku name was called accountType.</span></span> <span data-ttu-id="64758-127">Folgende Werte sind möglich: "Standard_LRS", "Standard_GRS", "Standard_RAGRS", "standard_zrs" "", "premium_lrs" ""</span><span class="sxs-lookup"><span data-stu-id="64758-127">Possible values include: 'Standard_LRS', 'Standard_GRS', 'Standard_RAGRS', 'Standard_ZRS', 'Premium_LRS'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceType">
      <MemberSignature Language="C#" Value="public string ResourceType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceType As String" />
      <MemberSignature Language="F#" Value="member this.ResourceType : string" Usage="Microsoft.Azure.Management.Storage.Models.Sku.ResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-128">Ruft den Typ der Ressource, in der Regel, die es ist "storageaccounts werden" ab.</span><span class="sxs-lookup"><span data-stu-id="64758-128">Gets the type of the resource, usually it is 'storageAccounts'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restrictions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Storage.Models.Restriction&gt; Restrictions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberSignature Language="VB.NET" Value="Public Property Restrictions As IList(Of Restriction)" />
      <MemberSignature Language="F#" Value="member this.Restrictions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt; with get, set" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Restrictions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="restrictions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Storage.Models.Restriction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-129">Abrufen / definieren die Einschränkungen, die aufgrund, die SKU verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="64758-129">Gets or sets the restrictions because of which SKU cannot be used.</span></span>
            <span data-ttu-id="64758-130">Dies ist leer, wenn es keine Einschränkungen gibt.</span><span class="sxs-lookup"><span data-stu-id="64758-130">This is empty if there are no restrictions.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Storage.Models.SkuTier&gt; Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Tier As Nullable(Of SkuTier)" />
      <MemberSignature Language="F#" Value="member this.Tier : Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;" Usage="Microsoft.Azure.Management.Storage.Models.Sku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Storage.Models.SkuTier&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64758-131">Ruft die Sku-Tarif.</span><span class="sxs-lookup"><span data-stu-id="64758-131">Gets the sku tier.</span></span> <span data-ttu-id="64758-132">Dies basiert auf der SKU-Name.</span><span class="sxs-lookup"><span data-stu-id="64758-132">This is based on the SKU name.</span></span> <span data-ttu-id="64758-133">Folgende Werte sind möglich: "Standard", "Premium"</span><span class="sxs-lookup"><span data-stu-id="64758-133">Possible values include: 'Standard', 'Premium'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Sku.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="sku.Validate " />
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
            <span data-ttu-id="64758-134">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="64758-134">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="64758-135">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="64758-135">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>