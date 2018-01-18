<Type Name="RedisResource" FullName="Microsoft.Azure.Management.Redis.Models.RedisResource">
  <TypeSignature Language="C#" Value="public class RedisResource : Microsoft.Azure.Management.Redis.Models.TrackedResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RedisResource extends Microsoft.Azure.Management.Redis.Models.TrackedResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Models.RedisResource" />
  <TypeSignature Language="VB.NET" Value="Public Class RedisResource&#xA;Inherits TrackedResource" />
  <TypeSignature Language="F#" Value="type RedisResource = class&#xA;    inherit TrackedResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Redis.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.Redis.Models.TrackedResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4b618-101">Ein einzelnes Redis-Element, das in der Liste "oder" Get-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="4b618-101">A single Redis item in List or Get Operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4b618-102">Initialisiert eine neue Instanz der RedisResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4b618-102">Initializes a new instance of the RedisResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RedisResource (string location, Microsoft.Azure.Management.Redis.Models.Sku sku, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration = null, Nullable&lt;bool&gt; enableNonSslPort = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tenantSettings = null, Nullable&lt;int&gt; shardCount = null, string subnetId = null, string staticIP = null, string redisVersion = null, string provisioningState = null, string hostName = null, Nullable&lt;int&gt; port = null, Nullable&lt;int&gt; sslPort = null, Microsoft.Azure.Management.Redis.Models.RedisAccessKeys accessKeys = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; linkedServers = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, class Microsoft.Azure.Management.Redis.Models.Sku sku, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration, valuetype System.Nullable`1&lt;bool&gt; enableNonSslPort, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tenantSettings, valuetype System.Nullable`1&lt;int32&gt; shardCount, string subnetId, string staticIP, string redisVersion, string provisioningState, string hostName, valuetype System.Nullable`1&lt;int32&gt; port, valuetype System.Nullable`1&lt;int32&gt; sslPort, class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys accessKeys, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; linkedServers, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.#ctor(System.String,Microsoft.Azure.Management.Redis.Models.Sku,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Boolean},System.Collections.Generic.IDictionary{System.String,System.String},System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Redis.Models.RedisAccessKeys,System.Collections.Generic.IList{Microsoft.Azure.Management.Redis.Models.RedisLinkedServer},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Redis.Models.RedisResource : string * Microsoft.Azure.Management.Redis.Models.Sku * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;bool&gt; * System.Collections.Generic.IDictionary&lt;string, string&gt; * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Redis.Models.RedisAccessKeys * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Redis.Models.RedisResource" Usage="new Microsoft.Azure.Management.Redis.Models.RedisResource (location, sku, id, name, type, tags, redisConfiguration, enableNonSslPort, tenantSettings, shardCount, subnetId, staticIP, redisVersion, provisioningState, hostName, port, sslPort, accessKeys, linkedServers, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Redis.Models.Sku" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="enableNonSslPort" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="tenantSettings" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="shardCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="subnetId" Type="System.String" />
        <Parameter Name="staticIP" Type="System.String" />
        <Parameter Name="redisVersion" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="port" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sslPort" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="accessKeys" Type="Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" />
        <Parameter Name="linkedServers" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="location"><span data-ttu-id="4b618-103">Der geografische Standort, in dem die Ressource aktiv ist</span><span class="sxs-lookup"><span data-stu-id="4b618-103">The geo-location where the resource lives</span></span></param>
        <param name="sku"><span data-ttu-id="4b618-104">Die SKU des Redis-Caches bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="4b618-104">The SKU of the Redis cache to deploy.</span></span></param>
        <param name="id"><span data-ttu-id="4b618-105">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="4b618-105">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="4b618-106">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="4b618-106">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="4b618-107">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="4b618-107">Resource type.</span></span></param>
        <param name="tags"><span data-ttu-id="4b618-108">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="4b618-108">Resource tags.</span></span></param>
        <param name="redisConfiguration"><span data-ttu-id="4b618-109">Alle Redis-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="4b618-109">All Redis Settings.</span></span> <span data-ttu-id="4b618-110">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="4b618-110">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span></param>
        <param name="enableNonSslPort"><span data-ttu-id="4b618-111">Gibt an, ob die nicht-Ssl-Redis-Server (6379) port aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="4b618-111">Specifies whether the non-ssl Redis server port (6379) is enabled.</span></span></param>
        <param name="tenantSettings"><span data-ttu-id="4b618-112">Ein Wörterbuch von mandanteneinstellungen</span><span class="sxs-lookup"><span data-stu-id="4b618-112">A dictionary of tenant settings</span></span></param>
        <param name="shardCount"><span data-ttu-id="4b618-113">Die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="4b618-113">The number of shards to be created on a Premium Cluster Cache.</span></span></param>
        <param name="subnetId"><span data-ttu-id="4b618-114">Die vollständige Ressourcen-ID eines Subnetzes in einem virtuellen Netzwerk den Redis-Cache bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="4b618-114">The full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="4b618-115">Beispiel für das Format: / Subscriptions / {Subid} / ResourceGroups / {ResourceGroupName} / Microsoft. {Netzwerk | ClassicNetwork} / VirtualNetworks/vnet1/Subnetze/subnet1</span><span class="sxs-lookup"><span data-stu-id="4b618-115">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span></param>
        <param name="staticIP"><span data-ttu-id="4b618-116">Statische IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="4b618-116">Static IP address.</span></span> <span data-ttu-id="4b618-117">Erforderlich, wenn einen Redis-Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="4b618-117">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span></param>
        <param name="redisVersion"><span data-ttu-id="4b618-118">Die redis-Version.</span><span class="sxs-lookup"><span data-stu-id="4b618-118">Redis version.</span></span></param>
        <param name="provisioningState"><span data-ttu-id="4b618-119">Die redis-Instanz Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="4b618-119">Redis instance provisioning status.</span></span></param>
        <param name="hostName"><span data-ttu-id="4b618-120">Die redis-Hostnamen an.</span><span class="sxs-lookup"><span data-stu-id="4b618-120">Redis host name.</span></span></param>
        <param name="port"><span data-ttu-id="4b618-121">Die redis-nicht-SSL-Port.</span><span class="sxs-lookup"><span data-stu-id="4b618-121">Redis non-SSL port.</span></span></param>
        <param name="sslPort"><span data-ttu-id="4b618-122">Die redis-SSL-Port.</span><span class="sxs-lookup"><span data-stu-id="4b618-122">Redis SSL port.</span></span></param>
        <param name="accessKeys"><span data-ttu-id="4b618-123">Die Schlüssel des Redis-Cache - nicht festgelegt werden, wenn dieses Objekt nicht die Antwort zu erstellen oder Aktualisieren des redis-cache</span><span class="sxs-lookup"><span data-stu-id="4b618-123">The keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span></param>
        <param name="linkedServers"><span data-ttu-id="4b618-124">Liste von Verbindungsservern, die dem Cache zugeordnet</span><span class="sxs-lookup"><span data-stu-id="4b618-124">List of the linked servers associated with the cache</span></span></param>
        <param name="zones"><span data-ttu-id="4b618-125">Eine Liste der Verfügbarkeit Zonen, die angibt, in denen die Ressource stammen muss.</span><span class="sxs-lookup"><span data-stu-id="4b618-125">A list of availability zones denoting where the resource needs to come from.</span></span></param>
        <summary>
            <span data-ttu-id="4b618-126">Initialisiert eine neue Instanz der RedisResource-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4b618-126">Initializes a new instance of the RedisResource class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKeys">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.RedisAccessKeys AccessKeys { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Models.RedisAccessKeys AccessKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.AccessKeys" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AccessKeys As RedisAccessKeys" />
      <MemberSignature Language="F#" Value="member this.AccessKeys : Microsoft.Azure.Management.Redis.Models.RedisAccessKeys" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.AccessKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.RedisAccessKeys</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-127">Ruft die Schlüssel des Redis-Cache - nicht festgelegt, wenn dieses Objekt nicht die Antwort zu erstellen ist oder Aktualisieren des redis-cache</span><span class="sxs-lookup"><span data-stu-id="4b618-127">Gets the keys of the Redis cache - not set if this object is not the response to Create or Update redis cache</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableNonSslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableNonSslPort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableNonSslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.EnableNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableNonSslPort As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableNonSslPort : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.EnableNonSslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableNonSslPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-128">Ruft ab oder legt ihn fest, gibt Sie an, ob die nicht-Ssl-Redis-Server (6379) port aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="4b618-128">Gets or sets specifies whether the non-ssl Redis server port (6379) is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-129">Ruft die redis-Hostnamen an.</span><span class="sxs-lookup"><span data-stu-id="4b618-129">Gets redis host name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; LinkedServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt; LinkedServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.LinkedServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServers As IList(Of RedisLinkedServer)" />
      <MemberSignature Language="F#" Value="member this.LinkedServers : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.LinkedServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.linkedServers")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Redis.Models.RedisLinkedServer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-130">Ruft die Liste von Verbindungsservern, die dem Cache zugeordnet</span><span class="sxs-lookup"><span data-stu-id="4b618-130">Gets list of the linked servers associated with the cache</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Port">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Port { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Port" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Port" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Port As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Port : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Port" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.port")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-131">Ruft die redis-nicht-SSL-Port.</span><span class="sxs-lookup"><span data-stu-id="4b618-131">Gets redis non-SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4b618-132">Ruft die redis-Instanz Bereitstellungsstatus.</span><span class="sxs-lookup"><span data-stu-id="4b618-132">Gets redis instance provisioning status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisConfiguration">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; RedisConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; RedisConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.RedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property RedisConfiguration As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.RedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.RedisConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redisConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-133">Ruft ab oder legt alle Redis-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="4b618-133">Gets or sets all Redis Settings.</span></span> <span data-ttu-id="4b618-134">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span><span class="sxs-lookup"><span data-stu-id="4b618-134">Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedisVersion">
      <MemberSignature Language="C#" Value="public string RedisVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RedisVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.RedisVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RedisVersion As String" />
      <MemberSignature Language="F#" Value="member this.RedisVersion : string" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.RedisVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.redisVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-135">Ruft die redis-Version.</span><span class="sxs-lookup"><span data-stu-id="4b618-135">Gets redis version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ShardCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; ShardCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; ShardCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.ShardCount" />
      <MemberSignature Language="VB.NET" Value="Public Property ShardCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.ShardCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.ShardCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.shardCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-136">Ruft ab oder legt die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.</span><span class="sxs-lookup"><span data-stu-id="4b618-136">Gets or sets the number of shards to be created on a Premium Cluster Cache.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Redis.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Redis.Models.Sku with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-137">Ruft ab oder legt die SKU des Redis-Caches zum Bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="4b618-137">Gets or sets the SKU of the Redis cache to deploy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslPort">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SslPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SslPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.SslPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SslPort As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SslPort : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.SslPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslPort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-138">Ruft die redis-SSL-Port.</span><span class="sxs-lookup"><span data-stu-id="4b618-138">Gets redis SSL port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StaticIP">
      <MemberSignature Language="C#" Value="public string StaticIP { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StaticIP" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.StaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Property StaticIP As String" />
      <MemberSignature Language="F#" Value="member this.StaticIP : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.StaticIP" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.staticIP")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-139">Ruft ab oder legt die statische IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="4b618-139">Gets or sets static IP address.</span></span> <span data-ttu-id="4b618-140">Erforderlich, wenn einen Redis-Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="4b618-140">Required when deploying a Redis cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetId">
      <MemberSignature Language="C#" Value="public string SubnetId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.SubnetId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetId As String" />
      <MemberSignature Language="F#" Value="member this.SubnetId : string with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.SubnetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnetId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-141">Ruft ab, oder legt Sie die vollständige Ressourcen-ID eines Subnetzes in einem virtuellen Netzwerk zum Bereitstellen des Redis-Caches in fest.</span><span class="sxs-lookup"><span data-stu-id="4b618-141">Gets or sets the full resource ID of a subnet in a virtual network to deploy the Redis cache in.</span></span> <span data-ttu-id="4b618-142">Beispiel für das Format: / Subscriptions / {Subid} / ResourceGroups / {ResourceGroupName} / Microsoft. {Netzwerk | ClassicNetwork} / VirtualNetworks/vnet1/Subnetze/subnet1</span><span class="sxs-lookup"><span data-stu-id="4b618-142">Example format: /subscriptions/{subid}/resourceGroups/{resourceGroupName}/Microsoft.{Network|ClassicNetwork}/VirtualNetworks/vnet1/subnets/subnet1</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TenantSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; TenantSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; TenantSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.TenantSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property TenantSettings As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.TenantSettings : System.Collections.Generic.IDictionary&lt;string, string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.TenantSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.tenantSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b618-143">Ruft ab oder legt ein Wörterbuch von Mandanten Einstellungen</span><span class="sxs-lookup"><span data-stu-id="4b618-143">Gets or sets a dictionary of tenant settings</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Models.RedisResource.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="redisResource.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4b618-144">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4b618-144">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4b618-145">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4b618-145">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Redis.Models.RedisResource.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Redis.Models.RedisResource.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="4b618-146">Ruft ab oder legt ihn fest-Zonen eine Liste der Verfügbarkeit, die angibt, in denen die Ressource stammen muss.</span><span class="sxs-lookup"><span data-stu-id="4b618-146">Gets or sets a list of availability zones denoting where the resource needs to come from.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>