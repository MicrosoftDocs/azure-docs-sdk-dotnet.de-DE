<Type Name="NetworkInterface" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterface">
  <TypeSignature Language="C#" Value="public class NetworkInterface : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterface extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterface&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type NetworkInterface = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="8d575-101">Eine Netzwerkschnittstelle in einer Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="8d575-101">A network interface in a resource group.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterface ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterface.#ctor" />
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
            <span data-ttu-id="8d575-102">Initialisiert eine neue Instanz der Clusternetzwerkschnittstellen-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8d575-102">Initializes a new instance of the NetworkInterface class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterface (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.SubResource virtualMachine = null, Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ipConfigurations = null, Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings dnsSettings = null, string macAddress = null, Nullable&lt;bool&gt; primary = null, Nullable&lt;bool&gt; enableAcceleratedNetworking = null, Nullable&lt;bool&gt; enableIPForwarding = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.SubResource virtualMachine, class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup networkSecurityGroup, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; ipConfigurations, class Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings dnsSettings, string macAddress, valuetype System.Nullable`1&lt;bool&gt; primary, valuetype System.Nullable`1&lt;bool&gt; enableAcceleratedNetworking, valuetype System.Nullable`1&lt;bool&gt; enableIPForwarding, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterface.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration},Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterface : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; * Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterface" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterface (id, name, type, location, tags, virtualMachine, networkSecurityGroup, ipConfigurations, dnsSettings, macAddress, primary, enableAcceleratedNetworking, enableIPForwarding, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" />
        <Parameter Name="macAddress" Type="System.String" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableAcceleratedNetworking" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableIPForwarding" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8d575-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="8d575-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="8d575-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="8d575-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="8d575-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="8d575-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="8d575-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="8d575-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="8d575-107">Resource tags.</span></span></param>
        <param name="virtualMachine"><span data-ttu-id="8d575-108">Der Verweis eines virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="8d575-108">The reference of a virtual machine.</span></span></param>
        <param name="networkSecurityGroup"><span data-ttu-id="8d575-109">Der Verweis der NetworkSecurityGroup Ressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-109">The reference of the NetworkSecurityGroup resource.</span></span></param>
        <param name="ipConfigurations"><span data-ttu-id="8d575-110">Eine Liste der IP-Konfiguration der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8d575-110">A list of IPConfigurations of the network interface.</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="8d575-111">Die DNS-Einstellungen in der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8d575-111">The DNS settings in network interface.</span></span></param>
        <param name="macAddress"><span data-ttu-id="8d575-112">Die MAC-Adresse der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8d575-112">The MAC address of the network interface.</span></span></param>
        <param name="primary"><span data-ttu-id="8d575-113">Ruft ab, ob es sich um eine primäre Netzwerkschnittstelle auf einem virtuellen Computer handelt.</span><span class="sxs-lookup"><span data-stu-id="8d575-113">Gets whether this is a primary network interface on a virtual machine.</span></span></param>
        <param name="enableAcceleratedNetworking"><span data-ttu-id="8d575-114">Wenn die Netzwerkschnittstelle networking beschleunigt wird aktiviert.</span><span class="sxs-lookup"><span data-stu-id="8d575-114">If the network interface is accelerated networking enabled.</span></span></param>
        <param name="enableIPForwarding"><span data-ttu-id="8d575-115">Gibt an, ob die IP-Weiterleitung für diese Netzwerkschnittstelle aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="8d575-115">Indicates whether IP forwarding is enabled on this network interface.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="8d575-116">Die Eigenschaft "Ressource" GUID der Schnittstelle Netzwerkressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-116">The resource GUID property of the network interface resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="8d575-117">Der Bereitstellungsstatus der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-117">The provisioning state of the public IP resource.</span></span> <span data-ttu-id="8d575-118">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="8d575-118">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="8d575-119">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="8d575-119">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="8d575-120">Initialisiert eine neue Instanz der Clusternetzwerkschnittstellen-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8d575-120">Initializes a new instance of the NetworkInterface class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As NetworkInterfaceDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.DnsSettings" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-121">Ruft ab oder legt die DNS-Einstellungen in die Netzwerkschnittstelle fest.</span><span class="sxs-lookup"><span data-stu-id="8d575-121">Gets or sets the DNS settings in network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAcceleratedNetworking">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableAcceleratedNetworking { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableAcceleratedNetworking" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableAcceleratedNetworking" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableAcceleratedNetworking As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableAcceleratedNetworking : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableAcceleratedNetworking" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableAcceleratedNetworking")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-122">Ruft ab oder legt fest, ob die Netzwerkschnittstelle wird beschleunigt Networking aktiviert.</span><span class="sxs-lookup"><span data-stu-id="8d575-122">Gets or sets if the network interface is accelerated networking enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableIPForwarding">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableIPForwarding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableIPForwarding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableIPForwarding" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableIPForwarding As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableIPForwarding : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.EnableIPForwarding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableIPForwarding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-123">Gibt an, ob die IP-Weiterleitung für diese Netzwerkschnittstelle aktiviert ist, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="8d575-123">Gets or sets indicates whether IP forwarding is enabled on this network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.Etag" />
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
            <span data-ttu-id="8d575-124">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="8d575-124">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of NetworkInterfaceIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.IpConfigurations" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-125">Ruft ab oder legt eine Liste der IP-Konfiguration der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8d575-125">Gets or sets a list of IPConfigurations of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MacAddress">
      <MemberSignature Language="C#" Value="public string MacAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MacAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.MacAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property MacAddress As String" />
      <MemberSignature Language="F#" Value="member this.MacAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.MacAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.macAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-126">Ruft ab oder legt die MAC-Adresse der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="8d575-126">Gets or sets the MAC address of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup NetworkSecurityGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.NetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkSecurityGroup As NetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroup : Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.NetworkSecurityGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkSecurityGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.NetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-127">Ruft ab oder legt den Verweis der NetworkSecurityGroup Ressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-127">Gets or sets the reference of the NetworkSecurityGroup resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-128">Ruft ab, ob es sich um eine primäre Netzwerkschnittstelle auf einem virtuellen Computer handelt.</span><span class="sxs-lookup"><span data-stu-id="8d575-128">Gets whether this is a primary network interface on a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.ProvisioningState" />
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
            <span data-ttu-id="8d575-129">Ruft ab oder legt den Bereitstellungsstatus der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="8d575-129">Gets or sets the provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="8d575-130">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="8d575-130">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.ResourceGuid" />
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
            <span data-ttu-id="8d575-131">Ruft ab oder legt die GUID-Eigenschaft, der die Schnittstelle Netzwerkressource "Ressource".</span><span class="sxs-lookup"><span data-stu-id="8d575-131">Gets or sets the resource GUID property of the network interface resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource VirtualMachine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource VirtualMachine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterface.VirtualMachine" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachine As SubResource" />
      <MemberSignature Language="F#" Value="member this.VirtualMachine : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterface.VirtualMachine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachine")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8d575-132">Ruft ab oder legt den Verweis einer virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="8d575-132">Gets or sets the reference of a virtual machine.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>