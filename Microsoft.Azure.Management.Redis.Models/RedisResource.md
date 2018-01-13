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
            Ein einzelnes Redis-Element, das in der Liste "oder" Get-Vorgang.
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
            Initialisiert eine neue Instanz der RedisResource-Klasse.
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
        <param name="location">Der geografische Standort, in dem die Ressource aktiv ist</param>
        <param name="sku">Die SKU des Redis-Caches bereitstellen.</param>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="redisConfiguration">Alle Redis-Einstellungen. Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.</param>
        <param name="enableNonSslPort">Gibt an, ob die nicht-Ssl-Redis-Server (6379) port aktiviert ist.</param>
        <param name="tenantSettings">Ein Wörterbuch von mandanteneinstellungen</param>
        <param name="shardCount">Die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.</param>
        <param name="subnetId">Die vollständige Ressourcen-ID eines Subnetzes in einem virtuellen Netzwerk den Redis-Cache bereitstellen. Beispiel für das Format: / Subscriptions / {Subid} / ResourceGroups / {ResourceGroupName} / Microsoft. {Netzwerk | ClassicNetwork} / VirtualNetworks/vnet1/Subnetze/subnet1</param>
        <param name="staticIP">Statische IP-Adresse. Erforderlich, wenn einen Redis-Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.</param>
        <param name="redisVersion">Die redis-Version.</param>
        <param name="provisioningState">Die redis-Instanz Bereitstellungsstatus.</param>
        <param name="hostName">Die redis-Hostnamen an.</param>
        <param name="port">Die redis-nicht-SSL-Port.</param>
        <param name="sslPort">Die redis-SSL-Port.</param>
        <param name="accessKeys">Die Schlüssel des Redis-Cache - nicht festgelegt werden, wenn dieses Objekt nicht die Antwort zu erstellen oder Aktualisieren des redis-cache</param>
        <param name="linkedServers">Liste von Verbindungsservern, die dem Cache zugeordnet</param>
        <param name="zones">Eine Liste der Verfügbarkeit Zonen, die angibt, in denen die Ressource stammen muss.</param>
        <summary>
            Initialisiert eine neue Instanz der RedisResource-Klasse.
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
            Ruft die Schlüssel des Redis-Cache - nicht festgelegt, wenn dieses Objekt nicht die Antwort zu erstellen ist oder Aktualisieren des redis-cache
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
            Ruft ab oder legt ihn fest, gibt Sie an, ob die nicht-Ssl-Redis-Server (6379) port aktiviert ist.
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
            Ruft die redis-Hostnamen an.
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
            Ruft die Liste von Verbindungsservern, die dem Cache zugeordnet
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
            Ruft die redis-nicht-SSL-Port.
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
            Ruft die redis-Instanz Bereitstellungsstatus.
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
            Ruft ab oder legt alle Redis-Einstellungen. Few possible keys: rdb-backup-enabled,rdb-storage-connection-string,rdb-backup-frequency,maxmemory-delta,maxmemory-policy,notify-keyspace-events,maxmemory-samples,slowlog-log-slower-than,slowlog-max-len,list-max-ziplist-entries,list-max-ziplist-value,hash-max-ziplist-entries,hash-max-ziplist-value,set-max-intset-entries,zset-max-ziplist-entries,zset-max-ziplist-value etc.
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
            Ruft die redis-Version.
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
            Ruft ab oder legt die Anzahl der Shards auf eine Premium-Cache-Cluster erstellt werden.
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
            Ruft ab oder legt die SKU des Redis-Caches zum Bereitstellen.
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
            Ruft die redis-SSL-Port.
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
            Ruft ab oder legt die statische IP-Adresse. Erforderlich, wenn einen Redis-Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.
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
            Ruft ab, oder legt Sie die vollständige Ressourcen-ID eines Subnetzes in einem virtuellen Netzwerk zum Bereitstellen des Redis-Caches in fest. Beispiel für das Format: / Subscriptions / {Subid} / ResourceGroups / {ResourceGroupName} / Microsoft. {Netzwerk | ClassicNetwork} / VirtualNetworks/vnet1/Subnetze/subnet1
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
            Ruft ab oder legt ein Wörterbuch von Mandanten Einstellungen
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
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
            Ruft ab oder legt ihn fest-Zonen eine Liste der Verfügbarkeit, die angibt, in denen die Ressource stammen muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>