<Type Name="HostNameBinding" FullName="Microsoft.Azure.Management.WebSites.Models.HostNameBinding">
  <TypeSignature Language="C#" Value="public class HostNameBinding : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HostNameBinding extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.HostNameBinding" />
  <TypeSignature Language="VB.NET" Value="Public Class HostNameBinding&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type HostNameBinding = class&#xA;    inherit ProxyOnlyResource" />
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
            <span data-ttu-id="1c317-101">Hostname Binding-Objekt.</span><span class="sxs-lookup"><span data-stu-id="1c317-101">A hostname binding object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameBinding ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1c317-102">Initialisiert eine neue Instanz der HostNameBinding-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c317-102">Initializes a new instance of the HostNameBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HostNameBinding (string id = null, string name = null, string kind = null, string type = null, string siteName = null, string domainId = null, string azureResourceName = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; azureResourceType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; hostNameType = null, Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState = null, string thumbprint = null, string virtualIP = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string siteName, string domainId, string azureResourceName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; azureResourceType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; customHostNameDnsRecordType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; hostNameType, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; sslState, string thumbprint, string virtualIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.WebSites.Models.AzureResourceType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.HostNameType},System.Nullable{Microsoft.Azure.Management.WebSites.Models.SslState},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional siteName As String = null, Optional domainId As String = null, Optional azureResourceName As String = null, Optional azureResourceType As Nullable(Of AzureResourceType) = null, Optional customHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType) = null, Optional hostNameType As Nullable(Of HostNameType) = null, Optional sslState As Nullable(Of SslState) = null, Optional thumbprint As String = null, Optional virtualIP As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.HostNameBinding : string * string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; * Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; * string * string -&gt; Microsoft.Azure.Management.WebSites.Models.HostNameBinding" Usage="new Microsoft.Azure.Management.WebSites.Models.HostNameBinding (id, name, kind, type, siteName, domainId, azureResourceName, azureResourceType, customHostNameDnsRecordType, hostNameType, sslState, thumbprint, virtualIP)" />
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
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="domainId" Type="System.String" />
        <Parameter Name="azureResourceName" Type="System.String" />
        <Parameter Name="azureResourceType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt;" />
        <Parameter Name="customHostNameDnsRecordType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt;" />
        <Parameter Name="hostNameType" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt;" />
        <Parameter Name="sslState" Type="System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="virtualIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="1c317-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="1c317-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="1c317-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="1c317-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="1c317-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="1c317-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="1c317-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="1c317-106">Resource type.</span></span></param>
        <param name="siteName"><span data-ttu-id="1c317-107">App Service-app-Name.</span><span class="sxs-lookup"><span data-stu-id="1c317-107">App Service app name.</span></span></param>
        <param name="domainId"><span data-ttu-id="1c317-108">Vollqualifizierte ARM-Domänenressource URI.</span><span class="sxs-lookup"><span data-stu-id="1c317-108">Fully qualified ARM domain resource URI.</span></span></param>
        <param name="azureResourceName"><span data-ttu-id="1c317-109">Name des Azure-Ressource.</span><span class="sxs-lookup"><span data-stu-id="1c317-109">Azure resource name.</span></span></param>
        <param name="azureResourceType"><span data-ttu-id="1c317-110">Azure-Ressource-Typ.</span><span class="sxs-lookup"><span data-stu-id="1c317-110">Azure resource type.</span></span> <span data-ttu-id="1c317-111">Folgende Werte sind möglich: "Website", "TrafficManager"</span><span class="sxs-lookup"><span data-stu-id="1c317-111">Possible values include: 'Website', 'TrafficManager'</span></span></param>
        <param name="customHostNameDnsRecordType"><span data-ttu-id="1c317-112">Benutzerdefinierte DNS-Datensatztyp.</span><span class="sxs-lookup"><span data-stu-id="1c317-112">Custom DNS record type.</span></span>
            <span data-ttu-id="1c317-113">Folgende Werte sind möglich: "CName", "A"</span><span class="sxs-lookup"><span data-stu-id="1c317-113">Possible values include: 'CName', 'A'</span></span></param>
        <param name="hostNameType"><span data-ttu-id="1c317-114">Hostname-Typ.</span><span class="sxs-lookup"><span data-stu-id="1c317-114">Hostname type.</span></span> <span data-ttu-id="1c317-115">Folgende Werte sind möglich: "Überprüft", "Verwaltet"</span><span class="sxs-lookup"><span data-stu-id="1c317-115">Possible values include: 'Verified', 'Managed'</span></span></param>
        <param name="sslState"><span data-ttu-id="1c317-116">SSL-Typ.</span><span class="sxs-lookup"><span data-stu-id="1c317-116">SSL type.</span></span> <span data-ttu-id="1c317-117">Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"</span><span class="sxs-lookup"><span data-stu-id="1c317-117">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span></param>
        <param name="thumbprint"><span data-ttu-id="1c317-118">Fingerabdruck des SSL-Zertifikats</span><span class="sxs-lookup"><span data-stu-id="1c317-118">SSL certificate thumbprint</span></span></param>
        <param name="virtualIP"><span data-ttu-id="1c317-119">Virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1c317-119">Virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span></param>
        <summary>
            <span data-ttu-id="1c317-120">Initialisiert eine neue Instanz der HostNameBinding-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1c317-120">Initializes a new instance of the HostNameBinding class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceName">
      <MemberSignature Language="C#" Value="public string AzureResourceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AzureResourceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceName" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceName As String" />
      <MemberSignature Language="F#" Value="member this.AzureResourceName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureResourceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-121">Ruft ab oder legt Azure-Ressourcennamen.</span><span class="sxs-lookup"><span data-stu-id="1c317-121">Gets or sets azure resource name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureResourceType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; AzureResourceType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; AzureResourceType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceType" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureResourceType As Nullable(Of AzureResourceType)" />
      <MemberSignature Language="F#" Value="member this.AzureResourceType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.AzureResourceType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureResourceType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.AzureResourceType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-122">Ruft ab oder legt ihn fest Azure-Ressource.</span><span class="sxs-lookup"><span data-stu-id="1c317-122">Gets or sets azure resource type.</span></span> <span data-ttu-id="1c317-123">Folgende Werte sind möglich: "Website", "TrafficManager"</span><span class="sxs-lookup"><span data-stu-id="1c317-123">Possible values include: 'Website', 'TrafficManager'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHostNameDnsRecordType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; CustomHostNameDnsRecordType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.CustomHostNameDnsRecordType" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomHostNameDnsRecordType As Nullable(Of CustomHostNameDnsRecordType)" />
      <MemberSignature Language="F#" Value="member this.CustomHostNameDnsRecordType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.CustomHostNameDnsRecordType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.customHostNameDnsRecordType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.CustomHostNameDnsRecordType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-124">Ruft ab oder legt ihn fest benutzerdefinierten DNS-Eintragstyp.</span><span class="sxs-lookup"><span data-stu-id="1c317-124">Gets or sets custom DNS record type.</span></span> <span data-ttu-id="1c317-125">Folgende Werte sind möglich: "CName", "A"</span><span class="sxs-lookup"><span data-stu-id="1c317-125">Possible values include: 'CName', 'A'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DomainId">
      <MemberSignature Language="C#" Value="public string DomainId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DomainId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.DomainId" />
      <MemberSignature Language="VB.NET" Value="Public Property DomainId As String" />
      <MemberSignature Language="F#" Value="member this.DomainId : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.DomainId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.domainId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-126">Ruft ab, oder legt ihn fest vollqualifizierten ARM Domänenressource URI.</span><span class="sxs-lookup"><span data-stu-id="1c317-126">Gets or sets fully qualified ARM domain resource URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; HostNameType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; HostNameType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.HostNameType" />
      <MemberSignature Language="VB.NET" Value="Public Property HostNameType As Nullable(Of HostNameType)" />
      <MemberSignature Language="F#" Value="member this.HostNameType : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.HostNameType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostNameType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.HostNameType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-127">Ruft ab oder legt ihn fest Hostname.</span><span class="sxs-lookup"><span data-stu-id="1c317-127">Gets or sets hostname type.</span></span> <span data-ttu-id="1c317-128">Folgende Werte sind möglich: "Überprüft", "Verwaltet"</span><span class="sxs-lookup"><span data-stu-id="1c317-128">Possible values include: 'Verified', 'Managed'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.siteName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-129">Ruft ab oder legt Name des app Service-app.</span><span class="sxs-lookup"><span data-stu-id="1c317-129">Gets or sets app Service app name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.WebSites.Models.SslState&gt; SslState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SslState" />
      <MemberSignature Language="VB.NET" Value="Public Property SslState As Nullable(Of SslState)" />
      <MemberSignature Language="F#" Value="member this.SslState : Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.SslState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.WebSites.Models.SslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-130">Ruft ab oder legt ihn fest SSL.</span><span class="sxs-lookup"><span data-stu-id="1c317-130">Gets or sets SSL type.</span></span> <span data-ttu-id="1c317-131">Folgende Werte sind möglich: "Deaktiviert", "SniEnabled", "IpBasedEnabled"</span><span class="sxs-lookup"><span data-stu-id="1c317-131">Possible values include: 'Disabled', 'SniEnabled', 'IpBasedEnabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-132">Ruft ab oder legt ihn fest Fingerabdruck des SSL-Zertifikats</span><span class="sxs-lookup"><span data-stu-id="1c317-132">Gets or sets SSL certificate thumbprint</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualIP">
      <MemberSignature Language="C#" Value="public string VirtualIP { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.HostNameBinding.VirtualIP" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualIP As String" />
      <MemberSignature Language="F#" Value="member this.VirtualIP : string" Usage="Microsoft.Azure.Management.WebSites.Models.HostNameBinding.VirtualIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1c317-133">Ruft virtuelle IP-Adresse, den Hostnamen zugewiesen, wenn die IP-basiertes SSL aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1c317-133">Gets virtual IP address assigned to the hostname if IP based SSL is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>