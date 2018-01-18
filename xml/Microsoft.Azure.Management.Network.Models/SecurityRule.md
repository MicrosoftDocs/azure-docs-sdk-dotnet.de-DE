<Type Name="SecurityRule" FullName="Microsoft.Azure.Management.Network.Models.SecurityRule">
  <TypeSignature Language="C#" Value="public class SecurityRule : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityRule extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.SecurityRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityRule&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type SecurityRule = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9f57f-101">Die netzwerksicherheitsregel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-101">Network security rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.#ctor" />
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
            <span data-ttu-id="9f57f-102">Initialisiert eine neue Instanz der SecurityRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9f57f-102">Initializes a new instance of the SecurityRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityRule (string protocol, string access, string direction, string id = null, string description = null, string sourcePortRange = null, string destinationPortRange = null, string sourceAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; sourceAddressPrefixes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; sourceApplicationSecurityGroups = null, string destinationAddressPrefix = null, System.Collections.Generic.IList&lt;string&gt; destinationAddressPrefixes = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; destinationApplicationSecurityGroups = null, System.Collections.Generic.IList&lt;string&gt; sourcePortRanges = null, System.Collections.Generic.IList&lt;string&gt; destinationPortRanges = null, Nullable&lt;int&gt; priority = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string protocol, string access, string direction, string id, string description, string sourcePortRange, string destinationPortRange, string sourceAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; sourceAddressPrefixes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; sourceApplicationSecurityGroups, string destinationAddressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; destinationAddressPrefixes, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; destinationApplicationSecurityGroups, class System.Collections.Generic.IList`1&lt;string&gt; sourcePortRanges, class System.Collections.Generic.IList`1&lt;string&gt; destinationPortRanges, valuetype System.Nullable`1&lt;int32&gt; priority, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.Nullable{System.Int32},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (protocol As String, access As String, direction As String, Optional id As String = null, Optional description As String = null, Optional sourcePortRange As String = null, Optional destinationPortRange As String = null, Optional sourceAddressPrefix As String = null, Optional sourceAddressPrefixes As IList(Of String) = null, Optional sourceApplicationSecurityGroups As IList(Of ApplicationSecurityGroup) = null, Optional destinationAddressPrefix As String = null, Optional destinationAddressPrefixes As IList(Of String) = null, Optional destinationApplicationSecurityGroups As IList(Of ApplicationSecurityGroup) = null, Optional sourcePortRanges As IList(Of String) = null, Optional destinationPortRanges As IList(Of String) = null, Optional priority As Nullable(Of Integer) = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.SecurityRule : string * string * string * string * string * string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;int&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.SecurityRule" Usage="new Microsoft.Azure.Management.Network.Models.SecurityRule (protocol, access, direction, id, description, sourcePortRange, destinationPortRange, sourceAddressPrefix, sourceAddressPrefixes, sourceApplicationSecurityGroups, destinationAddressPrefix, destinationAddressPrefixes, destinationApplicationSecurityGroups, sourcePortRanges, destinationPortRanges, priority, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="protocol" Type="System.String" />
        <Parameter Name="access" Type="System.String" />
        <Parameter Name="direction" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="sourcePortRange" Type="System.String" />
        <Parameter Name="destinationPortRange" Type="System.String" />
        <Parameter Name="sourceAddressPrefix" Type="System.String" />
        <Parameter Name="sourceAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="sourceApplicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="destinationAddressPrefix" Type="System.String" />
        <Parameter Name="destinationAddressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationApplicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="sourcePortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="destinationPortRanges" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="protocol"><span data-ttu-id="9f57f-103">Das Netzwerkprotokoll, die diese Regel gilt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-103">Network protocol this rule applies to.</span></span>
            <span data-ttu-id="9f57f-104">Mögliche Werte sind "Tcp", "Udp" und "*". Folgende Werte sind möglich: "Tcp", "Udp", "*"</span><span class="sxs-lookup"><span data-stu-id="9f57f-104">Possible values are 'Tcp', 'Udp', and '*'. Possible values include: 'Tcp', 'Udp', '*'</span></span></param>
        <param name="access"><span data-ttu-id="9f57f-105">Der Netzwerkdatenverkehr wird zugelassen oder verweigert.</span><span class="sxs-lookup"><span data-stu-id="9f57f-105">The network traffic is allowed or denied.</span></span>
            <span data-ttu-id="9f57f-106">Mögliche Werte sind: "Zulassen" und "Verweigern".</span><span class="sxs-lookup"><span data-stu-id="9f57f-106">Possible values are: 'Allow' and 'Deny'.</span></span> <span data-ttu-id="9f57f-107">Folgende Werte sind möglich: "Zulassen", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="9f57f-107">Possible values include: 'Allow', 'Deny'</span></span></param>
        <param name="direction"><span data-ttu-id="9f57f-108">Die Richtung der Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-108">The direction of the rule.</span></span> <span data-ttu-id="9f57f-109">Die Richtung gibt an, ob die Regel auf eingehenden oder outcoming Datenverkehr ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="9f57f-109">The direction specifies if rule will be evaluated on incoming or outcoming traffic.</span></span> <span data-ttu-id="9f57f-110">Mögliche Werte sind: "Eingehend" und "Ausgehend".</span><span class="sxs-lookup"><span data-stu-id="9f57f-110">Possible values are: 'Inbound' and 'Outbound'.</span></span> <span data-ttu-id="9f57f-111">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="9f57f-111">Possible values include: 'Inbound', 'Outbound'</span></span></param>
        <param name="id"><span data-ttu-id="9f57f-112">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="9f57f-112">Resource ID.</span></span></param>
        <param name="description"><span data-ttu-id="9f57f-113">Eine Beschreibung für diese Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-113">A description for this rule.</span></span> <span data-ttu-id="9f57f-114">Auf 140 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-114">Restricted to 140 chars.</span></span></param>
        <param name="sourcePortRange"><span data-ttu-id="9f57f-115">Den Quellport oder -Bereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-115">The source port or range.</span></span> <span data-ttu-id="9f57f-116">Ganze Zahl oder ein Bereich zwischen 0 und 65535 sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-116">Integer or range between 0 and 65535.</span></span> <span data-ttu-id="9f57f-117">Sternchen "\*" kann auch verwendet werden, um alle Ports zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-117">Asterix '\*' can also be used to match all ports.</span></span></param>
        <param name="destinationPortRange"><span data-ttu-id="9f57f-118">Den Zielport oder -Bereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-118">The destination port or range.</span></span>
            <span data-ttu-id="9f57f-119">Ganze Zahl oder ein Bereich zwischen 0 und 65535 sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-119">Integer or range between 0 and 65535.</span></span> <span data-ttu-id="9f57f-120">Sternchen "\*" kann auch verwendet werden, um alle Ports zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-120">Asterix '\*' can also be used to match all ports.</span></span></param>
        <param name="sourceAddressPrefix"><span data-ttu-id="9f57f-121">Der CIDR- oder Quell-IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-121">The CIDR or source IP range.</span></span>
            <span data-ttu-id="9f57f-122">Sternchen "\*" kann auch verwendet werden, um alle Quell-IP-Adressen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-122">Asterix '\*' can also be used to match all source IPs.</span></span> <span data-ttu-id="9f57f-123">Standard-tags wie "VirtualNetwork", "AzureLoadBalancer" und "Internet" können auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9f57f-123">Default tags such as 'VirtualNetwork', 'AzureLoadBalancer' and 'Internet' can also be used.</span></span> <span data-ttu-id="9f57f-124">Ist dies eine eingehende Regel, gibt an, in denen Netzwerkdatenverkehr stammt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-124">If this is an ingress rule, specifies where network traffic originates from.</span></span> </param>
        <param name="sourceAddressPrefixes"><span data-ttu-id="9f57f-125">Die CIDR- oder Quell-IP-Adressbereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-125">The CIDR or source IP ranges.</span></span></param>
        <param name="sourceApplicationSecurityGroups"><span data-ttu-id="9f57f-126">Die Sicherheitsgruppe für die Anwendung als Quelle angegeben.</span><span class="sxs-lookup"><span data-stu-id="9f57f-126">The application security group specified as source.</span></span></param>
        <param name="destinationAddressPrefix"><span data-ttu-id="9f57f-127">Das Adresspräfix "Ziel".</span><span class="sxs-lookup"><span data-stu-id="9f57f-127">The destination address prefix.</span></span> <span data-ttu-id="9f57f-128">CIDR oder IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-128">CIDR or destination IP range.</span></span> <span data-ttu-id="9f57f-129">Sternchen "\*" kann auch verwendet werden, um alle Quell-IP-Adressen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-129">Asterix '\*' can also be used to match all source IPs.</span></span> <span data-ttu-id="9f57f-130">Standard-tags wie "VirtualNetwork", "AzureLoadBalancer" und "Internet" können auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9f57f-130">Default tags such as 'VirtualNetwork', 'AzureLoadBalancer' and 'Internet' can also be used.</span></span></param>
        <param name="destinationAddressPrefixes"><span data-ttu-id="9f57f-131">Die Ziel-Adresspräfixe.</span><span class="sxs-lookup"><span data-stu-id="9f57f-131">The destination address prefixes.</span></span> <span data-ttu-id="9f57f-132">CIDR- oder Ziel-IP-Bereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-132">CIDR or destination IP ranges.</span></span></param>
        <param name="destinationApplicationSecurityGroups"><span data-ttu-id="9f57f-133">Die Sicherheitsgruppe für die Anwendung als Ziel angegeben.</span><span class="sxs-lookup"><span data-stu-id="9f57f-133">The application security group specified as destination.</span></span></param>
        <param name="sourcePortRanges"><span data-ttu-id="9f57f-134">Die Quellbereiche Port.</span><span class="sxs-lookup"><span data-stu-id="9f57f-134">The source port ranges.</span></span></param>
        <param name="destinationPortRanges"><span data-ttu-id="9f57f-135">Der Ziel-Portbereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-135">The destination port ranges.</span></span></param>
        <param name="priority"><span data-ttu-id="9f57f-136">Die Priorität der Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-136">The priority of the rule.</span></span> <span data-ttu-id="9f57f-137">Der Wert kann zwischen 100 und 4096 liegen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-137">The value can be between 100 and 4096.</span></span> <span data-ttu-id="9f57f-138">Die Prioritätsnummer muss für jede Regel in der Auflistung eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-138">The priority number must be unique for each rule in the collection.</span></span> <span data-ttu-id="9f57f-139">Je niedrigere die Prioritätsnummer ist, desto höher ist die Priorität der Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-139">The lower the priority number, the higher the priority of the rule.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="9f57f-140">Der Bereitstellungsstatus der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="9f57f-140">The provisioning state of the public IP resource.</span></span> <span data-ttu-id="9f57f-141">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="9f57f-141">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span></param>
        <param name="name"><span data-ttu-id="9f57f-142">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="9f57f-142">The name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="9f57f-143">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-143">This name can be used to access the resource.</span></span></param>
        <param name="etag"><span data-ttu-id="9f57f-144">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9f57f-144">A unique read-only string that changes whenever the resource is updated.</span></span></param>
        <summary>
            <span data-ttu-id="9f57f-145">Initialisiert eine neue Instanz der SecurityRule-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9f57f-145">Initializes a new instance of the SecurityRule class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-146">Ruft ab oder legt, die der Netzwerkdatenverkehr zugelassen oder verweigert wird.</span><span class="sxs-lookup"><span data-stu-id="9f57f-146">Gets or sets the network traffic is allowed or denied.</span></span> <span data-ttu-id="9f57f-147">Mögliche Werte sind: "Zulassen" und "Verweigern".</span><span class="sxs-lookup"><span data-stu-id="9f57f-147">Possible values are: 'Allow' and 'Deny'.</span></span> <span data-ttu-id="9f57f-148">Folgende Werte sind möglich: "Zulassen", "Ablehnen"</span><span class="sxs-lookup"><span data-stu-id="9f57f-148">Possible values include: 'Allow', 'Deny'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.description")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-149">Ruft ab oder legt eine Beschreibung für diese Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-149">Gets or sets a description for this rule.</span></span> <span data-ttu-id="9f57f-150">Auf 140 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-150">Restricted to 140 chars.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-151">Ermittelt oder definiert das Zieladresspräfix.</span><span class="sxs-lookup"><span data-stu-id="9f57f-151">Gets or sets the destination address prefix.</span></span> <span data-ttu-id="9f57f-152">CIDR oder IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-152">CIDR or destination IP range.</span></span> <span data-ttu-id="9f57f-153">Sternchen "\*" kann auch verwendet werden, um alle Quell-IP-Adressen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-153">Asterix '\*' can also be used to match all source IPs.</span></span>
            <span data-ttu-id="9f57f-154">Standard-tags wie "VirtualNetwork", "AzureLoadBalancer" und "Internet" können auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9f57f-154">Default tags such as 'VirtualNetwork', 'AzureLoadBalancer' and 'Internet' can also be used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-155">Ruft ab oder legt das Ziel-Adresspräfixe.</span><span class="sxs-lookup"><span data-stu-id="9f57f-155">Gets or sets the destination address prefixes.</span></span> <span data-ttu-id="9f57f-156">CIDR- oder Ziel-IP-Bereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-156">CIDR or destination IP ranges.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; DestinationApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; DestinationApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.DestinationApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationApplicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-157">Abrufen oder Festlegen der Sicherheitsgruppe "Anwendung", als Ziel angegeben.</span><span class="sxs-lookup"><span data-stu-id="9f57f-157">Gets or sets the application security group specified as destination.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRange">
      <MemberSignature Language="C#" Value="public string DestinationPortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationPortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRange As String" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationPortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-158">Ruft ab oder legt den Zielport oder-Bereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-158">Gets or sets the destination port or range.</span></span> <span data-ttu-id="9f57f-159">Ganze Zahl oder ein Bereich zwischen 0 und 65535 sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-159">Integer or range between 0 and 65535.</span></span> <span data-ttu-id="9f57f-160">Sternchen "\*" kann auch verwendet werden, um alle Ports zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-160">Asterix '\*' can also be used to match all ports.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DestinationPortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DestinationPortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property DestinationPortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.DestinationPortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.destinationPortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-161">Ruft ab oder legt das Ziel Portbereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-161">Gets or sets the destination port ranges.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Direction" />
      <MemberSignature Language="VB.NET" Value="Public Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.direction")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-162">Ruft ab oder legt die Richtung der Regel fest.</span><span class="sxs-lookup"><span data-stu-id="9f57f-162">Gets or sets the direction of the rule.</span></span> <span data-ttu-id="9f57f-163">Die Richtung gibt an, ob die Regel auf eingehenden oder outcoming Datenverkehr ausgewertet wird.</span><span class="sxs-lookup"><span data-stu-id="9f57f-163">The direction specifies if rule will be evaluated on incoming or outcoming traffic.</span></span> <span data-ttu-id="9f57f-164">Mögliche Werte sind: "Eingehend" und "Ausgehend".</span><span class="sxs-lookup"><span data-stu-id="9f57f-164">Possible values are: 'Inbound' and 'Outbound'.</span></span> <span data-ttu-id="9f57f-165">Folgende Werte sind möglich: "Inbound", "Ausgehend"</span><span class="sxs-lookup"><span data-stu-id="9f57f-165">Possible values include: 'Inbound', 'Outbound'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Etag" />
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
            <span data-ttu-id="9f57f-166">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="9f57f-166">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-167">Ruft ab oder legt den Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="9f57f-167">Gets or sets the name of the resource that is unique within a resource group.</span></span> <span data-ttu-id="9f57f-168">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-168">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-169">Ruft ab oder legt die Priorität der Regel fest.</span><span class="sxs-lookup"><span data-stu-id="9f57f-169">Gets or sets the priority of the rule.</span></span> <span data-ttu-id="9f57f-170">Der Wert kann zwischen 100 und 4096 liegen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-170">The value can be between 100 and 4096.</span></span> <span data-ttu-id="9f57f-171">Die Prioritätsnummer muss für jede Regel in der Auflistung eindeutig sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-171">The priority number must be unique for each rule in the collection.</span></span> <span data-ttu-id="9f57f-172">Je niedrigere die Prioritätsnummer ist, desto höher ist die Priorität der Regel.</span><span class="sxs-lookup"><span data-stu-id="9f57f-172">The lower the priority number, the higher the priority of the rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.protocol")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-173">Ruft ab, oder legt ihn fest-Netzwerkprotokoll mit dieser Regel gilt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-173">Gets or sets network protocol this rule applies to.</span></span> <span data-ttu-id="9f57f-174">Mögliche Werte sind "Tcp", "Udp" und "*". Folgende Werte sind möglich: "Tcp", "Udp", "*"</span><span class="sxs-lookup"><span data-stu-id="9f57f-174">Possible values are 'Tcp', 'Udp', and '*'. Possible values include: 'Tcp', 'Udp', '*'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.ProvisioningState" />
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
            <span data-ttu-id="9f57f-175">Ruft ab oder legt den Bereitstellungsstatus der öffentlichen IP-Adressressource.</span><span class="sxs-lookup"><span data-stu-id="9f57f-175">Gets or sets the provisioning state of the public IP resource.</span></span>
            <span data-ttu-id="9f57f-176">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="9f57f-176">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-177">Ruft ab oder legt den CIDR- oder Quell-IP-Adressbereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-177">Gets or sets the CIDR or source IP range.</span></span> <span data-ttu-id="9f57f-178">Sternchen "\*" kann auch verwendet werden, um alle Quell-IP-Adressen übereinstimmen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-178">Asterix '\*' can also be used to match all source IPs.</span></span> <span data-ttu-id="9f57f-179">Standard-tags wie "VirtualNetwork", "AzureLoadBalancer" und "Internet" können auch verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9f57f-179">Default tags such as 'VirtualNetwork', 'AzureLoadBalancer' and 'Internet' can also be used.</span></span> <span data-ttu-id="9f57f-180">Ist dies eine eingehende Regel, gibt an, in denen Netzwerkdatenverkehr stammt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-180">If this is an ingress rule, specifies where network traffic originates from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourceAddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourceAddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceAddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceAddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceAddressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-181">Ruft ab oder legt die CIDR- oder Quell-IP-Adressbereiche.</span><span class="sxs-lookup"><span data-stu-id="9f57f-181">Gets or sets the CIDR or source IP ranges.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; SourceApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; SourceApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourceApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.SourceApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourceApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourceApplicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-182">Abrufen oder Festlegen der Sicherheitsgruppe "Anwendung", als Quelle angegeben.</span><span class="sxs-lookup"><span data-stu-id="9f57f-182">Gets or sets the application security group specified as source.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRange">
      <MemberSignature Language="C#" Value="public string SourcePortRange { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRange" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRange As String" />
      <MemberSignature Language="F#" Value="member this.SourcePortRange : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePortRange")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-183">Ruft ab oder legt den Quellport oder-Bereich.</span><span class="sxs-lookup"><span data-stu-id="9f57f-183">Gets or sets the source port or range.</span></span> <span data-ttu-id="9f57f-184">Ganze Zahl oder ein Bereich zwischen 0 und 65535 sein.</span><span class="sxs-lookup"><span data-stu-id="9f57f-184">Integer or range between 0 and 65535.</span></span> <span data-ttu-id="9f57f-185">Sternchen "\*" kann auch verwendet werden, um alle Ports zu vergleichen.</span><span class="sxs-lookup"><span data-stu-id="9f57f-185">Asterix '\*' can also be used to match all ports.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SourcePortRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SourcePortRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePortRanges As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SourcePortRanges : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityRule.SourcePortRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePortRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-186">Ruft ab oder legt die Quelle Portbereiche fest.</span><span class="sxs-lookup"><span data-stu-id="9f57f-186">Gets or sets the source port ranges.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityRule.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="securityRule.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9f57f-187">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="9f57f-187">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9f57f-188">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="9f57f-188">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>