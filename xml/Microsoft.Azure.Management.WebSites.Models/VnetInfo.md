<Type Name="VnetInfo" FullName="Microsoft.Azure.Management.WebSites.Models.VnetInfo">
  <TypeSignature Language="C#" Value="public class VnetInfo : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VnetInfo extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.VnetInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class VnetInfo&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type VnetInfo = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="52da6-101">Virtuelles Netzwerk Informationen Vertrag.</span><span class="sxs-lookup"><span data-stu-id="52da6-101">Virtual Network information contract.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="52da6-102">Initialisiert eine neue Instanz der VnetInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="52da6-102">Initializes a new instance of the VnetInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VnetInfo (string id = null, string name = null, string kind = null, string type = null, string vnetResourceId = null, string certThumbprint = null, byte[] certBlob = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; routes = null, Nullable&lt;bool&gt; resyncRequired = null, string dnsServers = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string vnetResourceId, string certThumbprint, unsigned int8[] certBlob, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; routes, valuetype System.Nullable`1&lt;bool&gt; resyncRequired, string dnsServers) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.VnetInfo.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Byte[],System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.VnetRoute},System.Nullable{System.Boolean},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional vnetResourceId As String = null, Optional certThumbprint As String = null, Optional certBlob As Byte() = null, Optional routes As IList(Of VnetRoute) = null, Optional resyncRequired As Nullable(Of Boolean) = null, Optional dnsServers As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.VnetInfo : string * string * string * string * string * string * byte[] * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; * Nullable&lt;bool&gt; * string -&gt; Microsoft.Azure.Management.WebSites.Models.VnetInfo" Usage="new Microsoft.Azure.Management.WebSites.Models.VnetInfo (id, name, kind, type, vnetResourceId, certThumbprint, certBlob, routes, resyncRequired, dnsServers)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="vnetResourceId" Type="System.String" />
        <Parameter Name="certThumbprint" Type="System.String" />
        <Parameter Name="certBlob" Type="System.Byte[]" />
        <Parameter Name="routes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" />
        <Parameter Name="resyncRequired" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="dnsServers" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="52da6-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="52da6-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="52da6-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="52da6-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="52da6-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="52da6-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="52da6-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="52da6-106">Resource type.</span></span></param>
        <param name="vnetResourceId"><span data-ttu-id="52da6-107">Das Virtuellenetzwerk-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="52da6-107">The Virtual Network's resource ID.</span></span></param>
        <param name="certThumbprint"><span data-ttu-id="52da6-108">Der Fingerabdruck des Clientzertifikats.</span><span class="sxs-lookup"><span data-stu-id="52da6-108">The client certificate thumbprint.</span></span></param>
        <param name="certBlob"><span data-ttu-id="52da6-109">Eine Zertifikat-Datei (. cer)-Blob enthält den öffentlichen Schlüssel des privaten Schlüssels verwendet, um eine Punkt-zu-Standort-VPN-Verbindung zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="52da6-109">A certificate file (.cer) blob containing the public key of the private key used to authenticate a Point-To-Site VPN connection.</span></span></param>
        <param name="routes"><span data-ttu-id="52da6-110">Die Routen, die diese Verbindung des virtuellen Netzwerks verwendet.</span><span class="sxs-lookup"><span data-stu-id="52da6-110">The routes that this Virtual Network connection uses.</span></span></param>
        <param name="resyncRequired"><span data-ttu-id="52da6-111">&lt;Code&gt;"true"&lt;/code&gt; ist eine neusynchronisierung erforderlich ist, andernfalls &lt;Code&gt;"false"&lt;/code&gt;.</span><span class="sxs-lookup"><span data-stu-id="52da6-111">&lt;code&gt;true&lt;/code&gt; if a resync is required; otherwise, &lt;code&gt;false&lt;/code&gt;.</span></span></param>
        <param name="dnsServers"><span data-ttu-id="52da6-112">DNS-Server, die von diesem virtuellen Netzwerk verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="52da6-112">DNS servers to be used by this Virtual Network.</span></span> <span data-ttu-id="52da6-113">Dies sollte eine durch Trennzeichen getrennte Liste von IP-Adressen sein.</span><span class="sxs-lookup"><span data-stu-id="52da6-113">This should be a comma-separated list of IP addresses.</span></span></param>
        <summary>
            <span data-ttu-id="52da6-114">Initialisiert eine neue Instanz der VnetInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="52da6-114">Initializes a new instance of the VnetInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertBlob">
      <MemberSignature Language="C#" Value="public byte[] CertBlob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] CertBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.CertBlob" />
      <MemberSignature Language="VB.NET" Value="Public Property CertBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.CertBlob : byte[] with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.CertBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certBlob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-115">Ermittelt oder definiert einen zertifikatblob-Datei (. cer) enthält den öffentlichen Schlüssel des privaten Schlüssels verwendet, um eine Punkt-zu-Standort-VPN-Verbindung zu authentifizieren.</span><span class="sxs-lookup"><span data-stu-id="52da6-115">Gets or sets a certificate file (.cer) blob containing the public key of the private key used to authenticate a Point-To-Site VPN connection.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertThumbprint">
      <MemberSignature Language="C#" Value="public string CertThumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertThumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.CertThumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertThumbprint As String" />
      <MemberSignature Language="F#" Value="member this.CertThumbprint : string" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.CertThumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certThumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-116">Ruft den Fingerabdruck des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="52da6-116">Gets the client certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServers">
      <MemberSignature Language="C#" Value="public string DnsServers { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.DnsServers" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsServers As String" />
      <MemberSignature Language="F#" Value="member this.DnsServers : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.DnsServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-117">Ruft ab oder legt die DNS-Servern, die von diesem virtuellen Netzwerk verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="52da6-117">Gets or sets DNS servers to be used by this Virtual Network.</span></span> <span data-ttu-id="52da6-118">Dies sollte eine durch Trennzeichen getrennte Liste von IP-Adressen sein.</span><span class="sxs-lookup"><span data-stu-id="52da6-118">This should be a comma-separated list of IP addresses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResyncRequired">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ResyncRequired { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ResyncRequired" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.ResyncRequired" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResyncRequired As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ResyncRequired : Nullable&lt;bool&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.ResyncRequired" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resyncRequired")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-119">Ruft &amp;Lt; Code&amp;Gt; "true"&amp;Lt; / code&amp;Gt; ist eine neusynchronisierung erforderlich ist, andernfalls &amp;Lt; Code&amp;Gt "false"&amp;Lt; / code&amp;Gt;.</span><span class="sxs-lookup"><span data-stu-id="52da6-119">Gets &amp;lt;code&amp;gt;true&amp;lt;/code&amp;gt; if a resync is required; otherwise, &amp;lt;code&amp;gt;false&amp;lt;/code&amp;gt;.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Routes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; Routes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt; Routes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.Routes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Routes As IList(Of VnetRoute)" />
      <MemberSignature Language="F#" Value="member this.Routes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.Routes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.VnetRoute&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-120">Ruft die Routen, die diese Verbindung des virtuellen Netzwerks verwendet.</span><span class="sxs-lookup"><span data-stu-id="52da6-120">Gets the routes that this Virtual Network connection uses.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VnetResourceId">
      <MemberSignature Language="C#" Value="public string VnetResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VnetResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.VnetInfo.VnetResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property VnetResourceId As String" />
      <MemberSignature Language="F#" Value="member this.VnetResourceId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.VnetInfo.VnetResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vnetResourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="52da6-121">Ruft ab oder legt das Virtuellenetzwerk-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="52da6-121">Gets or sets the Virtual Network's resource ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>