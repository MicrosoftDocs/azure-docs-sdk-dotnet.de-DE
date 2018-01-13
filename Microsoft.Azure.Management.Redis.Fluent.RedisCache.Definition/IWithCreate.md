<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of IRedisCache), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;IRedisCache&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Redis.Fluent.IRedisCache&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="ac8c1-101">Eine Definition der Redis-Cache mit ausreichenden Eingaben zum Erstellen eines neuen Redis-Caches in der Cloud, aber das Verfügbarmachen von zusätzlichen optionalen Eingaben an.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-101">A Redis Cache definition with sufficient inputs to create a new Redis Cache in the cloud, but exposing additional optional inputs to specify.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNonSslPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithNonSslPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNonSslPort () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNonSslPort : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithNonSslPort " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac8c1-102">Ermöglicht nicht-Ssl-Redis-Server-port (6379).</span><span class="sxs-lookup"><span data-stu-id="ac8c1-102">Enables non-ssl Redis server port (6379).</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac8c1-103">die nächste Phase der Redis-Cache-Definition.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-103">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (redisConfiguration As IDictionary(Of String, String)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration redisConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="redisConfiguration"><span data-ttu-id="ac8c1-104">Konfiguration des Redis-Cache als Karte nach Namen indiziert.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-104">Configuration of Redis Cache as a map indexed by configuration name.</span></span></param>
        <summary>
            <span data-ttu-id="ac8c1-105">Alle Redis-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-105">All Redis Settings.</span></span> <span data-ttu-id="ac8c1-106">Einige möglichen Schlüssel: Rdb-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, der Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-106">Few possible keys: rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac8c1-107">die nächste Phase der Redis-Cache-Definition.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-107">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithRedisConfiguration(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithRedisConfiguration(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (key As String, value As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithRedisConfiguration (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="ac8c1-108">Die redis-Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-108">Redis configuration name.</span></span></param>
        <param name="value"><span data-ttu-id="ac8c1-109">Die redis-Konfigurationswert.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-109">Redis configuration value.</span></span></param>
        <summary>
            <span data-ttu-id="ac8c1-110">Gibt die Redis-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-110">Specifies Redis Setting.</span></span>
            <span data-ttu-id="ac8c1-111">der RDB-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-111">rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac8c1-112">die nächste Phase der Redis-Cache-Definition.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-112">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP (string staticIP);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStaticIP(string staticIP) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithStaticIP(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP (staticIP As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithStaticIP staticIP" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticIP" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticIP"><span data-ttu-id="ac8c1-113">der statische IP-Wert festgelegt.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-113">The static IP value to set.</span></span></param>
        <summary>
            <span data-ttu-id="ac8c1-114">Legt die Redis-Cache: statische IP-Adresse fest.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-114">Sets Redis Cache static IP.</span></span> <span data-ttu-id="ac8c1-115">Erforderlich, wenn Sie einen Redis Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-115">Required when deploying a Redis Cache inside an existing Azure Virtual Network.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac8c1-116">die nächste Phase der Redis-Cache-Definition.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-116">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet (Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithSubnet(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate.WithSubnet(Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (network As IHasId, subnetName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithCreate.WithSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="ac8c1-117">die Instanz des Netzwerk-Objekts.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-117">Instance of Network object.</span></span></param>
        <param name="subnetName"><span data-ttu-id="ac8c1-118">Der Name des Subnetzes.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-118">The name of the subnet.</span></span></param>
        <summary>
            <span data-ttu-id="ac8c1-119">Weist das angegebene Subnetz für diese Instanz des Redis-Cache.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-119">Assigns the specified subnet to this instance of Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac8c1-120">die nächste Phase der Redis-Cache-Definition.</span><span class="sxs-lookup"><span data-stu-id="ac8c1-120">The next stage of Redis Cache definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>