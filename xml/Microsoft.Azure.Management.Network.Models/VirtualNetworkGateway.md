<Type Name="VirtualNetworkGateway" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGateway : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGateway extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGateway&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGateway = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="9bb8f-101">Eine allgemeine Klasse für allgemeine Ressourceninformationen</span><span class="sxs-lookup"><span data-stu-id="9bb8f-101">A common class for general resource information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor" />
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
            <span data-ttu-id="9bb8f-102">Initialisiert eine neue Instanz der VirtualNetworkGateway-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-102">Initializes a new instance of the VirtualNetworkGateway class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations = null, string gatewayType = null, string vpnType = null, Nullable&lt;bool&gt; enableBgp = null, Nullable&lt;bool&gt; activeActive = null, Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite = null, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku = null, Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration = null, Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations, string gatewayType, string vpnType, valuetype System.Nullable`1&lt;bool&gt; enableBgp, valuetype System.Nullable`1&lt;bool&gt; activeActive, class Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku, class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration, class Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku,Microsoft.Azure.Management.Network.Models.VpnClientConfiguration,Microsoft.Azure.Management.Network.Models.BgpSettings,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku * Microsoft.Azure.Management.Network.Models.VpnClientConfiguration * Microsoft.Azure.Management.Network.Models.BgpSettings * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway (id, name, type, location, tags, ipConfigurations, gatewayType, vpnType, enableBgp, activeActive, gatewayDefaultSite, sku, vpnClientConfiguration, bgpSettings, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;" />
        <Parameter Name="gatewayType" Type="System.String" />
        <Parameter Name="vpnType" Type="System.String" />
        <Parameter Name="enableBgp" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="activeActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="gatewayDefaultSite" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku" />
        <Parameter Name="vpnClientConfiguration" Type="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration" />
        <Parameter Name="bgpSettings" Type="Microsoft.Azure.Management.Network.Models.BgpSettings" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="9bb8f-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="9bb8f-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="9bb8f-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="9bb8f-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="9bb8f-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="9bb8f-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-107">Resource tags.</span></span></param>
        <param name="ipConfigurations"><span data-ttu-id="9bb8f-108">IP-Konfigurationen für das Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-108">IP configurations for virtual network gateway.</span></span></param>
        <param name="gatewayType"><span data-ttu-id="9bb8f-109">Der Typ des diesem Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-109">The type of this virtual network gateway.</span></span>
            <span data-ttu-id="9bb8f-110">Mögliche Werte sind: "Vpn" und "ExpressRoute".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-110">Possible values are: 'Vpn' and 'ExpressRoute'.</span></span> <span data-ttu-id="9bb8f-111">Folgende Werte sind möglich: "Vpn", "ExpressRoute"</span><span class="sxs-lookup"><span data-stu-id="9bb8f-111">Possible values include: 'Vpn', 'ExpressRoute'</span></span></param>
        <param name="vpnType"><span data-ttu-id="9bb8f-112">Der Typ des diesem Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-112">The type of this virtual network gateway.</span></span>
            <span data-ttu-id="9bb8f-113">Mögliche Werte sind: "PolicyBased" und "Als routebased festgelegt".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-113">Possible values are: 'PolicyBased' and 'RouteBased'.</span></span> <span data-ttu-id="9bb8f-114">Folgende Werte sind möglich: "PolicyBased", "Als routebased festgelegt"</span><span class="sxs-lookup"><span data-stu-id="9bb8f-114">Possible values include: 'PolicyBased', 'RouteBased'</span></span></param>
        <param name="enableBgp"><span data-ttu-id="9bb8f-115">Gibt an, ob BGP für dieses virtuelle Netzwerkgateway oder nicht aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-115">Whether BGP is enabled for this virtual network gateway or not.</span></span></param>
        <param name="activeActive"><span data-ttu-id="9bb8f-116">ActiveActive-flag</span><span class="sxs-lookup"><span data-stu-id="9bb8f-116">ActiveActive flag</span></span></param>
        <param name="gatewayDefaultSite"><span data-ttu-id="9bb8f-117">Der Verweis der Gatewayverbindung Ressource, die Website im lokalen Netzwerk mit Standardrouten darstellt.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-117">The reference of the LocalNetworkGateway resource which represents local network site having default routes.</span></span> <span data-ttu-id="9bb8f-118">Zuweisen von Null-Wert im Falle vorhandene Standardeinstellung entfernen.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-118">Assign Null value in case of removing existing default site setting.</span></span></param>
        <param name="sku"><span data-ttu-id="9bb8f-119">Der Verweis der VirtualNetworkGatewaySku Ressource die SKU für das virtuelle Netzwerkgateway ausgewählt dar.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-119">The reference of the VirtualNetworkGatewaySku resource which represents the SKU selected for Virtual network gateway.</span></span></param>
        <param name="vpnClientConfiguration"><span data-ttu-id="9bb8f-120">Der Verweis der VpnClientConfiguration Ressource die P2S VpnClient Konfigurationen dar.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-120">The reference of the VpnClientConfiguration resource which represents the P2S VpnClient configurations.</span></span></param>
        <param name="bgpSettings"><span data-ttu-id="9bb8f-121">Virtuelles Netzwerk-Gateway-BGP-sprechender Benutzer-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-121">Virtual network gateway's BGP speaker settings.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="9bb8f-122">Die GUID-Eigenschaft der Ressource VirtualNetworkGateway-Ressource.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-122">The resource GUID property of the VirtualNetworkGateway resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="9bb8f-123">Der Bereitstellungsstatus der VirtualNetworkGateway Ressource.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-123">The provisioning state of the VirtualNetworkGateway resource.</span></span> <span data-ttu-id="9bb8f-124">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-124">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="9bb8f-125">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-125">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="9bb8f-126">Initialisiert eine neue Instanz der VirtualNetworkGateway-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-126">Initializes a new instance of the VirtualNetworkGateway class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ActiveActive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ActiveActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ActiveActive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-127">Ruft ab bzw. legt ActiveActive-Flag fest</span><span class="sxs-lookup"><span data-stu-id="9bb8f-127">Gets or sets activeActive flag</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpSettings As BgpSettings" />
      <MemberSignature Language="F#" Value="member this.BgpSettings : Microsoft.Azure.Management.Network.Models.BgpSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-128">Ruft ab, oder legt ihn fest Gateways des virtuellen Netzwerks BGP sprechender Benutzer Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-128">Gets or sets virtual network gateway's BGP speaker settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBgp">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBgp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBgp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBgp As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBgp : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBgp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-129">Ruft ab oder legt fest, ob BGP für dieses virtuelle Netzwerkgateway aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-129">Gets or sets whether BGP is enabled for this virtual network gateway or not.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
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
            <span data-ttu-id="9bb8f-130">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-130">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayDefaultSite">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayDefaultSite As SubResource" />
      <MemberSignature Language="F#" Value="member this.GatewayDefaultSite : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayDefaultSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-131">Ruft ab oder legt den Verweis der Gatewayverbindung Ressource, die Website im lokalen Netzwerk mit Standardrouten darstellt.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-131">Gets or sets the reference of the LocalNetworkGateway resource which represents local network site having default routes.</span></span> <span data-ttu-id="9bb8f-132">Zuweisen von Null-Wert im Falle vorhandene Standardeinstellung entfernen.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-132">Assign Null value in case of removing existing default site setting.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayType">
      <MemberSignature Language="C#" Value="public string GatewayType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayType As String" />
      <MemberSignature Language="F#" Value="member this.GatewayType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-133">Ruft ab oder legt den Typ dieses Gateway des virtuellen Netzwerks fest.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-133">Gets or sets the type of this virtual network gateway.</span></span> <span data-ttu-id="9bb8f-134">Mögliche Werte sind: "Vpn" und "ExpressRoute".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-134">Possible values are: 'Vpn' and 'ExpressRoute'.</span></span> <span data-ttu-id="9bb8f-135">Folgende Werte sind möglich: "Vpn", "ExpressRoute"</span><span class="sxs-lookup"><span data-stu-id="9bb8f-135">Possible values include: 'Vpn', 'ExpressRoute'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of VirtualNetworkGatewayIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-136">Abrufen oder Festlegen der IP-Konfigurationen für das Gateway des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-136">Gets or sets IP configurations for virtual network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
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
            <span data-ttu-id="9bb8f-137">Ruft den Bereitstellungsstatus der VirtualNetworkGateway Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-137">Gets the provisioning state of the VirtualNetworkGateway resource.</span></span>
            <span data-ttu-id="9bb8f-138">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-138">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
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
            <span data-ttu-id="9bb8f-139">Ruft ab oder legt die GUID-Eigenschaft der Ressource VirtualNetworkGateway "Ressource" ".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-139">Gets or sets the resource GUID property of the VirtualNetworkGateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As VirtualNetworkGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-140">Ruft ab oder legt den Verweis der VirtualNetworkGatewaySku Ressource die SKU für das virtuelle Netzwerkgateway ausgewählt dar.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-140">Gets or sets the reference of the VirtualNetworkGatewaySku resource which represents the SKU selected for Virtual network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientConfiguration As VpnClientConfiguration" />
      <MemberSignature Language="F#" Value="member this.VpnClientConfiguration : Microsoft.Azure.Management.Network.Models.VpnClientConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnClientConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VpnClientConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-141">Ruft ab oder legt den Verweis der VpnClientConfiguration Ressource die P2S VpnClient Konfigurationen dar.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-141">Gets or sets the reference of the VpnClientConfiguration resource which represents the P2S VpnClient configurations.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnType">
      <MemberSignature Language="C#" Value="public string VpnType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VpnType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnType As String" />
      <MemberSignature Language="F#" Value="member this.VpnType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9bb8f-142">Ruft ab oder legt den Typ dieses Gateway des virtuellen Netzwerks fest.</span><span class="sxs-lookup"><span data-stu-id="9bb8f-142">Gets or sets the type of this virtual network gateway.</span></span> <span data-ttu-id="9bb8f-143">Mögliche Werte sind: "PolicyBased" und "Als routebased festgelegt".</span><span class="sxs-lookup"><span data-stu-id="9bb8f-143">Possible values are: 'PolicyBased' and 'RouteBased'.</span></span> <span data-ttu-id="9bb8f-144">Folgende Werte sind möglich: "PolicyBased", "Als routebased festgelegt"</span><span class="sxs-lookup"><span data-stu-id="9bb8f-144">Possible values include: 'PolicyBased', 'RouteBased'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>