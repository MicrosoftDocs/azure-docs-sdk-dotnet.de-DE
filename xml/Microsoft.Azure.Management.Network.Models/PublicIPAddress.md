<Type Name="PublicIPAddress" FullName="Microsoft.Azure.Management.Network.Models.PublicIPAddress">
  <TypeSignature Language="C#" Value="public class PublicIPAddress : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicIPAddress extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicIPAddress&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type PublicIPAddress = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bfed9-101">Öffentliche IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="bfed9-101">Public IP address resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PublicIPAddress.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-102">Initialisiert eine neue Instanz der PublicIPAddress-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfed9-102">Initializes a new instance of the PublicIPAddress class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddress (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.PublicIPAddressSku sku = null, string publicIPAllocationMethod = null, string publicIPAddressVersion = null, Microsoft.Azure.Management.Network.Models.IPConfiguration ipConfiguration = null, Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings dnsSettings = null, string ipAddress = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, string resourceGuid = null, string provisioningState = null, string etag = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.PublicIPAddressSku sku, string publicIPAllocationMethod, string publicIPAddressVersion, class Microsoft.Azure.Management.Network.Models.IPConfiguration ipConfiguration, class Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings dnsSettings, string ipAddress, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, string resourceGuid, string provisioningState, string etag, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PublicIPAddress.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.PublicIPAddressSku,System.String,System.String,Microsoft.Azure.Management.Network.Models.IPConfiguration,Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PublicIPAddress : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.PublicIPAddressSku * string * string * Microsoft.Azure.Management.Network.Models.IPConfiguration * Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings * string * Nullable&lt;int&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="new Microsoft.Azure.Management.Network.Models.PublicIPAddress (id, name, type, location, tags, sku, publicIPAllocationMethod, publicIPAddressVersion, ipConfiguration, dnsSettings, ipAddress, idleTimeoutInMinutes, resourceGuid, provisioningState, etag, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddressSku" />
        <Parameter Name="publicIPAllocationMethod" Type="System.String" />
        <Parameter Name="publicIPAddressVersion" Type="System.String" />
        <Parameter Name="ipConfiguration" Type="Microsoft.Azure.Management.Network.Models.IPConfiguration" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bfed9-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="bfed9-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="bfed9-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfed9-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="bfed9-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="bfed9-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="bfed9-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="bfed9-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="bfed9-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="bfed9-107">Resource tags.</span></span></param>
        <param name="sku"><span data-ttu-id="bfed9-108">Die öffentliche IP-Adresse-SKU.</span><span class="sxs-lookup"><span data-stu-id="bfed9-108">The public IP address SKU.</span></span></param>
        <param name="publicIPAllocationMethod"><span data-ttu-id="bfed9-109">Die öffentliche IP-Zuordnungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bfed9-109">The public IP allocation method.</span></span> <span data-ttu-id="bfed9-110">Mögliche Werte sind: "Static" und "Dynamic".</span><span class="sxs-lookup"><span data-stu-id="bfed9-110">Possible values are: 'Static' and 'Dynamic'.</span></span> <span data-ttu-id="bfed9-111">Folgende Werte sind möglich: "Static", "Dynamic"</span><span class="sxs-lookup"><span data-stu-id="bfed9-111">Possible values include: 'Static', 'Dynamic'</span></span></param>
        <param name="publicIPAddressVersion"><span data-ttu-id="bfed9-112">Die öffentliche IP-Adressversion.</span><span class="sxs-lookup"><span data-stu-id="bfed9-112">The public IP address version.</span></span>
            <span data-ttu-id="bfed9-113">Mögliche Werte sind: "IPv4" und "IPv6".</span><span class="sxs-lookup"><span data-stu-id="bfed9-113">Possible values are: 'IPv4' and 'IPv6'.</span></span> <span data-ttu-id="bfed9-114">Folgende Werte sind möglich: "IPv4", "IPv6"</span><span class="sxs-lookup"><span data-stu-id="bfed9-114">Possible values include: 'IPv4', 'IPv6'</span></span></param>
        <param name="ipConfiguration"><span data-ttu-id="bfed9-115">Die IP-Konfiguration, die öffentliche IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-115">The IP configuration associated with the public IP address.</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="bfed9-116">Der FQDN des DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-116">The FQDN of the DNS record associated with the public IP address.</span></span></param>
        <param name="ipAddress"><span data-ttu-id="bfed9-117">Die IP-Adresse der öffentlichen IP-Adressressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-117">The IP address associated with the public IP address resource.</span></span></param>
        <param name="idleTimeoutInMinutes"><span data-ttu-id="bfed9-118">Das Leerlauftimeout der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bfed9-118">The idle timeout of the public IP address.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="bfed9-119">Die Eigenschaft "Ressource" GUID der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="bfed9-119">The resource GUID property of the public IP resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="bfed9-120">Der Bereitstellungsstatus der PublicIP-Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfed9-120">The provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="bfed9-121">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="bfed9-121">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="bfed9-122">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="bfed9-122">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <param name="zones"><span data-ttu-id="bfed9-123">Eine Liste der Verfügbarkeit von Zonen, die für die Ressource zugeordnete IP-Adresse angibt, muss stammen.</span><span class="sxs-lookup"><span data-stu-id="bfed9-123">A list of availability zones denoting the IP allocated for the resource needs to come from.</span></span></param>
        <summary>
            <span data-ttu-id="bfed9-124">Initialisiert eine neue Instanz der PublicIPAddress-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bfed9-124">Initializes a new instance of the PublicIPAddress class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As PublicIPAddressDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-125">Ruft ab oder legt den FQDN des DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-125">Gets or sets the FQDN of the DNS record associated with the public IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-126">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="bfed9-126">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-127">Ruft ab oder legt das Leerlauftimeout der öffentlichen IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bfed9-127">Gets or sets the idle timeout of the public IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-128">Ruft ab oder legt die IP-Adresse der öffentlichen IP-Adressressource zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-128">Gets or sets the IP address associated with the public IP address resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.IPConfiguration IpConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.IPConfiguration IpConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpConfiguration As IPConfiguration" />
      <MemberSignature Language="F#" Value="member this.IpConfiguration : Microsoft.Azure.Management.Network.Models.IPConfiguration" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.IPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-129">Ruft die IP-Konfiguration, die die öffentliche IP-Adresse zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="bfed9-129">Gets the IP configuration associated with the public IP address.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-130">Abrufen oder festlegen den Bereitstellungsstatus der PublicIP-Ressource.</span><span class="sxs-lookup"><span data-stu-id="bfed9-130">Gets or sets the provisioning state of the PublicIP resource.</span></span>
            <span data-ttu-id="bfed9-131">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="bfed9-131">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PublicIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-132">Ruft ab oder legt die Version der öffentliche IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="bfed9-132">Gets or sets the public IP address version.</span></span> <span data-ttu-id="bfed9-133">Mögliche Werte sind: "IPv4" und "IPv6".</span><span class="sxs-lookup"><span data-stu-id="bfed9-133">Possible values are: 'IPv4' and 'IPv6'.</span></span> <span data-ttu-id="bfed9-134">Folgende Werte sind möglich: "IPv4", "IPv6"</span><span class="sxs-lookup"><span data-stu-id="bfed9-134">Possible values include: 'IPv4', 'IPv6'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PublicIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PublicIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-135">Ruft ab oder legt die öffentliche IP-Zuordnungsmethode.</span><span class="sxs-lookup"><span data-stu-id="bfed9-135">Gets or sets the public IP allocation method.</span></span> <span data-ttu-id="bfed9-136">Mögliche Werte sind: "Static" und "Dynamic".</span><span class="sxs-lookup"><span data-stu-id="bfed9-136">Possible values are: 'Static' and 'Dynamic'.</span></span> <span data-ttu-id="bfed9-137">Folgende Werte sind möglich: "Static", "Dynamic"</span><span class="sxs-lookup"><span data-stu-id="bfed9-137">Possible values include: 'Static', 'Dynamic'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-138">Ruft ab oder legt die GUID-Eigenschaft, der die öffentliche IP-Adressressource "Ressource".</span><span class="sxs-lookup"><span data-stu-id="bfed9-138">Gets or sets the resource GUID property of the public IP resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddressSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddressSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As PublicIPAddressSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.PublicIPAddressSku with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddressSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-139">Ruft ab oder legt die öffentliche IP-Adresse SKU.</span><span class="sxs-lookup"><span data-stu-id="bfed9-139">Gets or sets the public IP address SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bfed9-140">Ruft ab oder Festlegen einer Liste von Verfügbarkeit Zonen, die angibt, dass sich die IP-Adresse für die Ressource belegt stammen muss.</span><span class="sxs-lookup"><span data-stu-id="bfed9-140">Gets or sets a list of availability zones denoting the IP allocated for the resource needs to come from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>