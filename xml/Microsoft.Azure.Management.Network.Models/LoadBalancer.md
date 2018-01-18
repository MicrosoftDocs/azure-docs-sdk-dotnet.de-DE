<Type Name="LoadBalancer" FullName="Microsoft.Azure.Management.Network.Models.LoadBalancer">
  <TypeSignature Language="C#" Value="public class LoadBalancer : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LoadBalancer extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.LoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Class LoadBalancer&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LoadBalancer = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="fde32-101">LoadBalancer-Ressource</span><span class="sxs-lookup"><span data-stu-id="fde32-101">LoadBalancer resource</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancer.#ctor" />
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
            <span data-ttu-id="fde32-102">Initialisiert eine neue Instanz der LoadBalancer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fde32-102">Initializes a new instance of the LoadBalancer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadBalancer (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.LoadBalancerSku sku = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; frontendIPConfigurations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; backendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; loadBalancingRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; probes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; inboundNatRules = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; inboundNatPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; outboundNatRules = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.LoadBalancerSku sku, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; frontendIPConfigurations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; backendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; loadBalancingRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; probes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; inboundNatRules, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; inboundNatPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; outboundNatRules, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.LoadBalancer.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.LoadBalancerSku,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.LoadBalancingRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.Probe},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatRule},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.OutboundNatRule},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional sku As LoadBalancerSku = null, Optional frontendIPConfigurations As IList(Of FrontendIPConfiguration) = null, Optional backendAddressPools As IList(Of BackendAddressPool) = null, Optional loadBalancingRules As IList(Of LoadBalancingRule) = null, Optional probes As IList(Of Probe) = null, Optional inboundNatRules As IList(Of InboundNatRule) = null, Optional inboundNatPools As IList(Of InboundNatPool) = null, Optional outboundNatRules As IList(Of OutboundNatRule) = null, Optional resourceGuid As String = null, Optional provisioningState As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.LoadBalancer : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.LoadBalancerSku * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.LoadBalancer" Usage="new Microsoft.Azure.Management.Network.Models.LoadBalancer (id, name, type, location, tags, sku, frontendIPConfigurations, backendAddressPools, loadBalancingRules, probes, inboundNatRules, inboundNatPools, outboundNatRules, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.LoadBalancerSku" />
        <Parameter Name="frontendIPConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;" />
        <Parameter Name="backendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" />
        <Parameter Name="loadBalancingRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;" />
        <Parameter Name="probes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;" />
        <Parameter Name="inboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" />
        <Parameter Name="inboundNatPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt;" />
        <Parameter Name="outboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="fde32-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="fde32-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="fde32-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="fde32-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="fde32-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="fde32-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="fde32-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="fde32-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="fde32-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="fde32-107">Resource tags.</span></span></param>
        <param name="sku"><span data-ttu-id="fde32-108">Der Load-Balancer-SKU.</span><span class="sxs-lookup"><span data-stu-id="fde32-108">The load balancer SKU.</span></span></param>
        <param name="frontendIPConfigurations"><span data-ttu-id="fde32-109">Das darstellt, des Front-End-IP-Adressen für den Lastenausgleich verwendet werden soll</span><span class="sxs-lookup"><span data-stu-id="fde32-109">Object representing the frontend IPs to be used for the load balancer</span></span></param>
        <param name="backendAddressPools"><span data-ttu-id="fde32-110">Auflistung von Back-End-Adresspools, die von einem Lastenausgleich verwendet</span><span class="sxs-lookup"><span data-stu-id="fde32-110">Collection of backend address pools used by a load balancer</span></span></param>
        <param name="loadBalancingRules"><span data-ttu-id="fde32-111">Ruft eine objektauflistung, die der Load balancer-Regeln darstellt, die Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="fde32-111">Object collection representing the load balancing rules Gets the provisioning</span></span> </param>
        <param name="probes"><span data-ttu-id="fde32-112">Auflistung von Testobjekten, die in der Load Balancer verwendet</span><span class="sxs-lookup"><span data-stu-id="fde32-112">Collection of probe objects used in the load balancer</span></span></param>
        <param name="inboundNatRules"><span data-ttu-id="fde32-113">Die Auflistung von eingehenden NAT-Regeln, die von einem Lastenausgleich verwendet.</span><span class="sxs-lookup"><span data-stu-id="fde32-113">Collection of inbound NAT Rules used by a load balancer.</span></span> <span data-ttu-id="fde32-114">Definieren von NAT-Eingangsregeln für Ihr Lastenausgleichsmodul wird mit der Definition eines eingehenden NAT-Pools sich gegenseitig ausschließende.</span><span class="sxs-lookup"><span data-stu-id="fde32-114">Defining inbound NAT rules on your load balancer is mutually exclusive with defining an inbound NAT pool.</span></span>
            <span data-ttu-id="fde32-115">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-115">Inbound NAT pools are referenced from virtual machine scale sets.</span></span>
            <span data-ttu-id="fde32-116">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehende NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-116">NICs that are associated with individual virtual machines cannot reference an Inbound NAT pool.</span></span> <span data-ttu-id="fde32-117">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-117">They have to reference individual inbound NAT rules.</span></span></param>
        <param name="inboundNatPools"><span data-ttu-id="fde32-118">Definiert einen externe Portbereich für eingehenden NAT-Datenverkehr an einen einzelnen Back-End-Port für NICs, die einem Lastenausgleichsmodul zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fde32-118">Defines an external port range for inbound NAT to a single backend port on NICs associated with a load balancer.</span></span> <span data-ttu-id="fde32-119">Eingehende NAT-Regeln werden für jede Netzwerkkarte, die das Lastenausgleichsmodul mit einer externen Port aus diesem Bereich zugeordneten automatisch erstellt.</span><span class="sxs-lookup"><span data-stu-id="fde32-119">Inbound NAT rules are created automatically for each NIC associated with the Load Balancer using an external port from this range.</span></span> <span data-ttu-id="fde32-120">Definieren einen eingehende NAT-Pool für Ihr Lastenausgleichsmodul wird sich gegenseitig ausschließende mit Nat-Eingangsregeln definieren.</span><span class="sxs-lookup"><span data-stu-id="fde32-120">Defining an Inbound NAT pool on your Load Balancer is mutually exclusive with defining inbound Nat rules.</span></span> <span data-ttu-id="fde32-121">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-121">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="fde32-122">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehenden NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-122">NICs that are associated with individual virtual machines cannot reference an inbound NAT pool.</span></span> <span data-ttu-id="fde32-123">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-123">They have to reference individual inbound NAT rules.</span></span></param>
        <param name="outboundNatRules"><span data-ttu-id="fde32-124">Die ausgehende NAT-Regeln.</span><span class="sxs-lookup"><span data-stu-id="fde32-124">The outbound NAT rules.</span></span></param>
        <param name="resourceGuid"><span data-ttu-id="fde32-125">Die Ressource der lastenausgleichsressource GUID-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="fde32-125">The resource GUID property of the load balancer resource.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="fde32-126">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="fde32-126">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="fde32-127">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="fde32-127">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="etag"><span data-ttu-id="fde32-128">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-128">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="fde32-129">Initialisiert eine neue Instanz der LoadBalancer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fde32-129">Initializes a new instance of the LoadBalancer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; BackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; BackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.BackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property BackendAddressPools As IList(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.BackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.BackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.backendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-130">Ruft ab oder legt die Auflistung von Back-End-Adresspools, die von einem Lastenausgleich verwendet</span><span class="sxs-lookup"><span data-stu-id="fde32-130">Gets or sets collection of backend address pools used by a load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Etag" />
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
            <span data-ttu-id="fde32-131">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-131">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FrontendIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; FrontendIPConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; FrontendIPConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.FrontendIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property FrontendIPConfigurations As IList(Of FrontendIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.FrontendIPConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.FrontendIPConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.frontendIPConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.FrontendIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-132">Ruft ab oder legt ihn fest-Objekt, das Front-End-IP-Adressen für den Lastenausgleich zu verwendende darstellt</span><span class="sxs-lookup"><span data-stu-id="fde32-132">Gets or sets object representing the frontend IPs to be used for the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; InboundNatPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; InboundNatPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatPools As IList(Of InboundNatPool)" />
      <MemberSignature Language="F#" Value="member this.InboundNatPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-133">Ruft ab oder legt ihn fest definiert einen externe Portbereich für eingehenden NAT-Datenverkehr an einen einzelnen Back-End-Port für NICs, die einem Lastenausgleichsmodul zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="fde32-133">Gets or sets defines an external port range for inbound NAT to a single backend port on NICs associated with a load balancer.</span></span>
            <span data-ttu-id="fde32-134">Eingehende NAT-Regeln werden für jede Netzwerkkarte, die das Lastenausgleichsmodul mit einer externen Port aus diesem Bereich zugeordneten automatisch erstellt.</span><span class="sxs-lookup"><span data-stu-id="fde32-134">Inbound NAT rules are created automatically for each NIC associated with the Load Balancer using an external port from this range.</span></span>
            <span data-ttu-id="fde32-135">Definieren einen eingehende NAT-Pool für Ihr Lastenausgleichsmodul wird sich gegenseitig ausschließende mit Nat-Eingangsregeln definieren.</span><span class="sxs-lookup"><span data-stu-id="fde32-135">Defining an Inbound NAT pool on your Load Balancer is mutually exclusive with defining inbound Nat rules.</span></span> <span data-ttu-id="fde32-136">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-136">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="fde32-137">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehenden NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-137">NICs that are associated with individual virtual machines cannot reference an inbound NAT pool.</span></span> <span data-ttu-id="fde32-138">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-138">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; InboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; InboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property InboundNatRules As IList(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.InboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.InboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-139">Abrufen oder Festlegen der Auflistung der eingehenden NAT-Regeln, die von einem Lastenausgleich verwendet.</span><span class="sxs-lookup"><span data-stu-id="fde32-139">Gets or sets collection of inbound NAT Rules used by a load balancer.</span></span> <span data-ttu-id="fde32-140">Definieren von NAT-Eingangsregeln für Ihr Lastenausgleichsmodul wird mit der Definition eines eingehenden NAT-Pools sich gegenseitig ausschließende.</span><span class="sxs-lookup"><span data-stu-id="fde32-140">Defining inbound NAT rules on your load balancer is mutually exclusive with defining an inbound NAT pool.</span></span> <span data-ttu-id="fde32-141">Eingehende NAT-Pools aus VM-skalierungsgruppen verwiesen wird.</span><span class="sxs-lookup"><span data-stu-id="fde32-141">Inbound NAT pools are referenced from virtual machine scale sets.</span></span> <span data-ttu-id="fde32-142">NICs, die einzelnen virtuellen Maschinen zugeordnet sind, können keinen eingehende NAT-Pool verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-142">NICs that are associated with individual virtual machines cannot reference an Inbound NAT pool.</span></span> <span data-ttu-id="fde32-143">Sie müssen einzelne NAT-Eingangsregeln verweisen.</span><span class="sxs-lookup"><span data-stu-id="fde32-143">They have to reference individual inbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancingRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; LoadBalancingRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; LoadBalancingRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.LoadBalancingRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancingRules As IList(Of LoadBalancingRule)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancingRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.LoadBalancingRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancingRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.LoadBalancingRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-144">Ruft ab oder legt eine objektauflistung, die den Lastenausgleich Regeln ruft darstellt, die Bereitstellung</span><span class="sxs-lookup"><span data-stu-id="fde32-144">Gets or sets object collection representing the load balancing rules Gets the provisioning</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; OutboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; OutboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.OutboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property OutboundNatRules As IList(Of OutboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.OutboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.OutboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.OutboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-145">Ruft ab oder legt die Regeln für ausgehenden NAT.</span><span class="sxs-lookup"><span data-stu-id="fde32-145">Gets or sets the outbound NAT rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; Probes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.Probe&gt; Probes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Probes" />
      <MemberSignature Language="VB.NET" Value="Public Property Probes As IList(Of Probe)" />
      <MemberSignature Language="F#" Value="member this.Probes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Probes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.probes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.Probe&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-146">Ruft ab oder legt die Auflistung von Testobjekten, die in der Load Balancer verwendet</span><span class="sxs-lookup"><span data-stu-id="fde32-146">Gets or sets collection of probe objects used in the load balancer</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.ProvisioningState" />
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
            <span data-ttu-id="fde32-147">Ruft den Bereitstellungsstatus der die öffentliche IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="fde32-147">Gets the provisioning state of the PublicIP resource.</span></span> <span data-ttu-id="fde32-148">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="fde32-148">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.ResourceGuid" />
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
            <span data-ttu-id="fde32-149">Abrufen oder festlegen die Ressource die lastenausgleichsressource GUID-Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="fde32-149">Gets or sets the resource GUID property of the load balancer resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.LoadBalancerSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.LoadBalancerSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.LoadBalancer.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As LoadBalancerSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.LoadBalancerSku with get, set" Usage="Microsoft.Azure.Management.Network.Models.LoadBalancer.Sku" />
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
        <ReturnType>Microsoft.Azure.Management.Network.Models.LoadBalancerSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fde32-150">Abrufen oder Festlegen der Load-Balancer-SKU.</span><span class="sxs-lookup"><span data-stu-id="fde32-150">Gets or sets the load balancer SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>