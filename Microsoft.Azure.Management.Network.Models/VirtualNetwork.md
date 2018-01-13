<Type Name="VirtualNetwork" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetwork">
  <TypeSignature Language="C#" Value="public class VirtualNetwork : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetwork extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetwork&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetwork = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="ccf55-101">Virtuelles Netzwerk-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ccf55-101">Virtual Network resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetwork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetwork.#ctor" />
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
            <span data-ttu-id="ccf55-102">Initialisiert eine neue Instanz der VirtualNetwork-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ccf55-102">Initializes a new instance of the VirtualNetwork class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetwork (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.AddressSpace addressSpace = null, Microsoft.Azure.Management.Network.Models.DhcpOptions dhcpOptions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; virtualNetworkPeerings = null, string resourceGuid = null, string provisioningState = null, Nullable&lt;bool&gt; enableDdosProtection = null, Nullable&lt;bool&gt; enableVmProtection = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.AddressSpace addressSpace, class Microsoft.Azure.Management.Network.Models.DhcpOptions dhcpOptions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; subnets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; virtualNetworkPeerings, string resourceGuid, string provisioningState, valuetype System.Nullable`1&lt;bool&gt; enableDdosProtection, valuetype System.Nullable`1&lt;bool&gt; enableVmProtection, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetwork.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.AddressSpace,Microsoft.Azure.Management.Network.Models.DhcpOptions,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Subnet},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetwork : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.AddressSpace * Microsoft.Azure.Management.Network.Models.DhcpOptions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetwork" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetwork (id, name, type, location, tags, addressSpace, dhcpOptions, subnets, virtualNetworkPeerings, resourceGuid, provisioningState, enableDdosProtection, enableVmProtection, etag)" />
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
        <Parameter Name="addressSpace" Type="Microsoft.Azure.Management.Network.Models.AddressSpace" />
        <Parameter Name="dhcpOptions" Type="Microsoft.Azure.Management.Network.Models.DhcpOptions" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;" />
        <Parameter Name="virtualNetworkPeerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="enableDdosProtection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="enableVmProtection" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="ccf55-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="ccf55-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="ccf55-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="ccf55-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="ccf55-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="ccf55-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="ccf55-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="ccf55-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="ccf55-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="ccf55-107">Resource tags.</span></span></param>
        <param name="addressSpace"><span data-ttu-id="ccf55-108">Die AddressSpace, die ein Array von IP-Adressbereiche enthält, die von einem Subnetz verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="ccf55-108">The AddressSpace that contains an array of IP address ranges that can be used by subnets.</span></span></param>
        <param name="dhcpOptions"><span data-ttu-id="ccf55-109">Die DhcpOptions, die ein Array von DNS-Server im virtuellen Netzwerk bereitgestellten virtuellen Maschinen zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="ccf55-109">The dhcpOptions that contains an array of DNS servers available to VMs deployed in the virtual network.</span></span></param>
        <param name="subnets"><span data-ttu-id="ccf55-110">Eine Liste von Subnetzen in einem virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="ccf55-110">A list of subnets in a Virtual Network.</span></span></param>
        <param name="virtualNetworkPeerings"><span data-ttu-id="ccf55-111">Eine Liste der kann in einem virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="ccf55-111">A list of peerings in a Virtual Network.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="ccf55-112">Die resourceguid für Eigenschaft der Ressource Virtuellenetzwerk.</span><span class="sxs-lookup"><span data-stu-id="ccf55-112">The resourceGuid property of the Virtual Network resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="ccf55-113">Der Bereitstellungsstatus der PublicIP-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ccf55-113">The provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="ccf55-114">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="ccf55-114">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="enableDdosProtection"><span data-ttu-id="ccf55-115">Gibt an, ob DDoS-Schutz für die geschützten Ressourcen in einem virtuellen Netzwerk aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ccf55-115">Indicates if DDoS protection is enabled for all the protected resources in a Virtual Network.</span></span></param>
        <param name="enableVmProtection"><span data-ttu-id="ccf55-116">Gibt an, ob für alle Subnetze in einem virtuellen Netzwerk Vm-Schutz aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ccf55-116">Indicates if Vm protection is enabled for all the subnets in a Virtual Network.</span></span></param>
        <param name="etag"><span data-ttu-id="ccf55-117">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ccf55-117">Gets a unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="ccf55-118">Initialisiert eine neue Instanz der VirtualNetwork-Klasse.</span><span class="sxs-lookup"><span data-stu-id="ccf55-118">Initializes a new instance of the VirtualNetwork class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.AddressSpace AddressSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.AddressSpace AddressSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.AddressSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressSpace As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.AddressSpace : Microsoft.Azure.Management.Network.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.AddressSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-119">Abrufen oder Festlegen der AddressSpace, die ein Array von IP-Adressbereiche enthält, die von einem Subnetz verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="ccf55-119">Gets or sets the AddressSpace that contains an array of IP address ranges that can be used by subnets.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhcpOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.DhcpOptions DhcpOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.DhcpOptions DhcpOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.DhcpOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DhcpOptions As DhcpOptions" />
      <MemberSignature Language="F#" Value="member this.DhcpOptions : Microsoft.Azure.Management.Network.Models.DhcpOptions with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.DhcpOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dhcpOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.DhcpOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-120">Abrufen oder Festlegen der DhcpOptions, die ein Array von DNS-Server im virtuellen Netzwerk bereitgestellten virtuellen Maschinen zur Verfügung.</span><span class="sxs-lookup"><span data-stu-id="ccf55-120">Gets or sets the dhcpOptions that contains an array of DNS servers available to VMs deployed in the virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableDdosProtection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableDdosProtection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableDdosProtection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableDdosProtection" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableDdosProtection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableDdosProtection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableDdosProtection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableDdosProtection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-121">Ruft ab oder legt gibt an, ob DDoS-Schutz für die geschützten Ressourcen in einem virtuellen Netzwerk aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ccf55-121">Gets or sets indicates if DDoS protection is enabled for all the protected resources in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableVmProtection">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableVmProtection { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableVmProtection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableVmProtection" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableVmProtection As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableVmProtection : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.EnableVmProtection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableVmProtection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-122">Ruft ab oder legt gibt an, ob für alle Subnetze in einem virtuellen Netzwerk Vm-Schutz aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="ccf55-122">Gets or sets indicates if Vm protection is enabled for all the subnets in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.Etag" />
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
            <span data-ttu-id="ccf55-123">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="ccf55-123">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.ProvisioningState" />
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
            <span data-ttu-id="ccf55-124">Abrufen oder festlegen den Bereitstellungsstatus der PublicIP-Ressource.</span><span class="sxs-lookup"><span data-stu-id="ccf55-124">Gets or sets the provisioning state of the PublicIP resource.</span></span>
            <span data-ttu-id="ccf55-125">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="ccf55-125">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.ResourceGuid" />
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
            <span data-ttu-id="ccf55-126">Ruft ab oder legt die Eigenschaft resourceguid für das Virtuellenetzwerk Ressource fest.</span><span class="sxs-lookup"><span data-stu-id="ccf55-126">Gets or sets the resourceGuid property of the Virtual Network resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Subnet&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnets As IList(Of Subnet)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Subnet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-127">Ruft ab oder legt eine Liste von Subnetzen in einem virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="ccf55-127">Gets or sets a list of subnets in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; VirtualNetworkPeerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetwork.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkPeerings As IList(Of VirtualNetworkPeering)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetwork.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkPeerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkPeering&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="ccf55-128">Ruft ab oder legt eine Liste der kann in einem virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="ccf55-128">Gets or sets a list of peerings in a Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>