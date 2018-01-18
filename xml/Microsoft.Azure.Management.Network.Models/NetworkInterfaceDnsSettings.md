<Type Name="NetworkInterfaceDnsSettings" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceDnsSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceDnsSettings" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceDnsSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c1a6b-101">DNS-Einstellungen für eine Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-101">DNS settings of a network interface.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.#ctor" />
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
            <span data-ttu-id="c1a6b-102">Initialisiert eine neue Instanz der NetworkInterfaceDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-102">Initializes a new instance of the NetworkInterfaceDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceDnsSettings (System.Collections.Generic.IList&lt;string&gt; dnsServers = null, System.Collections.Generic.IList&lt;string&gt; appliedDnsServers = null, string internalDnsNameLabel = null, string internalFqdn = null, string internalDomainNameSuffix = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; dnsServers, class System.Collections.Generic.IList`1&lt;string&gt; appliedDnsServers, string internalDnsNameLabel, string internalFqdn, string internalDomainNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dnsServers As IList(Of String) = null, Optional appliedDnsServers As IList(Of String) = null, Optional internalDnsNameLabel As String = null, Optional internalFqdn As String = null, Optional internalDomainNameSuffix As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings (dnsServers, appliedDnsServers, internalDnsNameLabel, internalFqdn, internalDomainNameSuffix)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="appliedDnsServers" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="internalDnsNameLabel" Type="System.String" />
        <Parameter Name="internalFqdn" Type="System.String" />
        <Parameter Name="internalDomainNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsServers"><span data-ttu-id="c1a6b-103">Liste der IP-Adressen von DNS-Server.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-103">List of DNS servers IP addresses.</span></span> <span data-ttu-id="c1a6b-104">Verwenden Sie "AzureProvidedDNS" So wechseln Sie in Azure bereitgestellten DNS-Auflösung.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-104">Use 'AzureProvidedDNS' to switch to azure provided DNS resolution.</span></span>
            <span data-ttu-id="c1a6b-105">Wert "AzureProvidedDNS" kann nicht mit anderen IPs kombiniert werden, muss er der einzige Wert in der DnsServers-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-105">'AzureProvidedDNS' value cannot be combined with other IPs, it must be the only value in dnsServers collection.</span></span></param>
        <param name="appliedDnsServers"><span data-ttu-id="c1a6b-106">Wenn der virtuelle Computer, die diese NIC verwendet Bestandteil einer Verfügbarkeitssammlung ist, wird diese Liste die Vereinigung aller DNS-Server von allen NICs haben, Teil der Verfügbarkeitsgruppe sind.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-106">If the VM that uses this NIC is part of an Availability Set, then this list will have the union of all DNS servers from all NICs that are part of the Availability Set.</span></span> <span data-ttu-id="c1a6b-107">Diese Eigenschaft ist, was auf jedem dieser virtuellen Computer konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-107">This property is what is configured on each of those VMs.</span></span></param>
        <param name="internalDnsNameLabel"><span data-ttu-id="c1a6b-108">Relative DNS-Name für diesen Netzwerkadapter für die interne Kommunikation zwischen virtuellen Computern im selben virtuellen Netzwerk verwendet.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-108">Relative DNS name for this NIC used for internal communications between VMs in the same virtual network.</span></span></param>
        <param name="internalFqdn"><span data-ttu-id="c1a6b-109">Vollständig qualifizierten DNS-Name interne Kommunikation zwischen virtuellen Computern im selben virtuellen Netzwerk zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-109">Fully qualified DNS name supporting internal communications between VMs in the same virtual network.</span></span></param>
        <param name="internalDomainNameSuffix"><span data-ttu-id="c1a6b-110">Auch wenn InternalDnsNameLabel nicht angegeben ist, wird ein DNS-Eintrag für die primäre NIC des virtuellen Computers erstellt.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-110">Even if internalDnsNameLabel is not specified, a DNS entry is created for the primary NIC of the VM.</span></span> <span data-ttu-id="c1a6b-111">Diese DNS-Namen kann erstellt werden, durch den Namen der virtuellen Maschine mit dem Wert des InternalDomainNameSuffix verketten.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-111">This DNS name can be constructed by concatenating the VM name with the value of internalDomainNameSuffix.</span></span></param>
        <summary>
            <span data-ttu-id="c1a6b-112">Initialisiert eine neue Instanz der NetworkInterfaceDnsSettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-112">Initializes a new instance of the NetworkInterfaceDnsSettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AppliedDnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AppliedDnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AppliedDnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property AppliedDnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AppliedDnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.AppliedDnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="appliedDnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a6b-113">Ruft ab oder legt fest, wenn der virtuelle Computer, die diese NIC verwendet Bestandteil einer Verfügbarkeitssammlung ist, und klicken Sie dann diese Liste die Vereinigung aller DNS-Server aus allen Netzwerkkarten verfügt, die Teil der Verfügbarkeitsgruppe sind.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-113">Gets or sets if the VM that uses this NIC is part of an Availability Set, then this list will have the union of all DNS servers from all NICs that are part of the Availability Set.</span></span> <span data-ttu-id="c1a6b-114">Diese Eigenschaft ist, was auf jedem dieser virtuellen Computer konfiguriert ist.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-114">This property is what is configured on each of those VMs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServers : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a6b-115">Ruft ab oder legt die Liste der IP-Adressen von DNS-Server.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-115">Gets or sets list of DNS servers IP addresses.</span></span> <span data-ttu-id="c1a6b-116">Verwenden Sie "AzureProvidedDNS" So wechseln Sie in Azure bereitgestellten DNS-Auflösung.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-116">Use 'AzureProvidedDNS' to switch to azure provided DNS resolution.</span></span>
            <span data-ttu-id="c1a6b-117">Wert "AzureProvidedDNS" kann nicht mit anderen IPs kombiniert werden, muss er der einzige Wert in der DnsServers-Auflistung.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-117">'AzureProvidedDNS' value cannot be combined with other IPs, it must be the only value in dnsServers collection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDnsNameLabel">
      <MemberSignature Language="C#" Value="public string InternalDnsNameLabel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDnsNameLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDnsNameLabel As String" />
      <MemberSignature Language="F#" Value="member this.InternalDnsNameLabel : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDnsNameLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDnsNameLabel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a6b-118">Ruft ab, oder legt ihn fest relativen DNS-Namen für diesen Netzwerkadapter für die interne Kommunikation zwischen virtuellen Computern im selben virtuellen Netzwerk verwendet.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-118">Gets or sets relative DNS name for this NIC used for internal communications between VMs in the same virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalDomainNameSuffix">
      <MemberSignature Language="C#" Value="public string InternalDomainNameSuffix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalDomainNameSuffix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalDomainNameSuffix As String" />
      <MemberSignature Language="F#" Value="member this.InternalDomainNameSuffix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalDomainNameSuffix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalDomainNameSuffix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a6b-119">Ruft ab oder legt fest, selbst wenn InternalDnsNameLabel nicht angegeben ist, ein DNS-Eintrag für die primäre NIC des virtuellen Computers erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-119">Gets or sets even if internalDnsNameLabel is not specified, a DNS entry is created for the primary NIC of the VM.</span></span> <span data-ttu-id="c1a6b-120">Diese DNS-Namen kann erstellt werden, durch den Namen der virtuellen Maschine mit dem Wert des InternalDomainNameSuffix verketten.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-120">This DNS name can be constructed by concatenating the VM name with the value of internalDomainNameSuffix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InternalFqdn">
      <MemberSignature Language="C#" Value="public string InternalFqdn { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InternalFqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberSignature Language="VB.NET" Value="Public Property InternalFqdn As String" />
      <MemberSignature Language="F#" Value="member this.InternalFqdn : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceDnsSettings.InternalFqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="internalFqdn")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c1a6b-121">Ruft ab, oder legt ihn fest vollqualifizierten DNS-Namen, die interne Kommunikation zwischen virtuellen Computern im selben virtuellen Netzwerk zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="c1a6b-121">Gets or sets fully qualified DNS name supporting internal communications between VMs in the same virtual network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>