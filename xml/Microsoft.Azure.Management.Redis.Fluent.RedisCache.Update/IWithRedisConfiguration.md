<Type Name="IWithRedisConfiguration" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithRedisConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRedisConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRedisConfiguration" />
  <TypeSignature Language="F#" Value="type IWithRedisConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="b33a5-101">Ein Redis-Cache aktualisieren lässt Redis-Konfiguration geändert werden.</span><span class="sxs-lookup"><span data-stu-id="b33a5-101">A Redis Cache update allowing Redis configuration to be modified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithoutRedisConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRedisConfiguration () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRedisConfiguration : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithoutRedisConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="b33a5-102">Bereinigt alle Konfigurationseinstellungen, die auf die Redis-Cache festgelegt wird.</span><span class="sxs-lookup"><span data-stu-id="b33a5-102">Cleans all the configuration settings being set on Redis Cache.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b33a5-103">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b33a5-103">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutRedisConfiguration(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithoutRedisConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRedisConfiguration (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRedisConfiguration : string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithoutRedisConfiguration key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="b33a5-104">Die redis-Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="b33a5-104">Redis configuration name.</span></span></param>
        <summary>
            <span data-ttu-id="b33a5-105">Entfernt den angegebenen Redis-Cache-Konfigurationseinstellung.</span><span class="sxs-lookup"><span data-stu-id="b33a5-105">Removes specified Redis Cache configuration setting.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b33a5-106">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b33a5-106">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration (System.Collections.Generic.IDictionary&lt;string,string&gt; redisConfiguration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration(class System.Collections.Generic.IDictionary`2&lt;string, string&gt; redisConfiguration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithRedisConfiguration(System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (redisConfiguration As IDictionary(Of String, String)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithRedisConfiguration redisConfiguration" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="redisConfiguration" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="redisConfiguration"><span data-ttu-id="b33a5-107">Konfiguration des Redis-Cache als Karte nach Namen indiziert.</span><span class="sxs-lookup"><span data-stu-id="b33a5-107">Configuration of Redis Cache as a map indexed by configuration name.</span></span></param>
        <summary>
            <span data-ttu-id="b33a5-108">Alle Redis-Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="b33a5-108">All Redis Settings.</span></span> <span data-ttu-id="b33a5-109">Einige möglichen Schlüssel: Rdb-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, der Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.</span><span class="sxs-lookup"><span data-stu-id="b33a5-109">Few possible keys: rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b33a5-110">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b33a5-110">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithRedisConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithRedisConfiguration(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithRedisConfiguration.WithRedisConfiguration(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRedisConfiguration (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithRedisConfiguration : string * string -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithRedisConfiguration.WithRedisConfiguration (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key"><span data-ttu-id="b33a5-111">Die redis-Konfigurationsname.</span><span class="sxs-lookup"><span data-stu-id="b33a5-111">Redis configuration name.</span></span></param>
        <param name="value"><span data-ttu-id="b33a5-112">Die redis-Konfigurationswert.</span><span class="sxs-lookup"><span data-stu-id="b33a5-112">Redis configuration value.</span></span></param>
        <summary>
            <span data-ttu-id="b33a5-113">Gibt die Redis-Einstellung.</span><span class="sxs-lookup"><span data-stu-id="b33a5-113">Specifies Redis Setting.</span></span>
            <span data-ttu-id="b33a5-114">der RDB-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.</span><span class="sxs-lookup"><span data-stu-id="b33a5-114">rdb-backup-enabled, rdb-storage-connection-string, rdb-backup-frequency, maxmemory-delta, maxmemory-policy, notify-keyspace-events, maxmemory-samples, slowlog-log-slower-than, slowlog-max-len, list-max-ziplist-entries, list-max-ziplist-value, hash-max-ziplist-entries, hash-max-ziplist-value, set -max-intset-entries, zset-max-ziplist-entries, zset-max-ziplist-value etc.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="b33a5-115">die nächste Phase des Redis-Cache aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="b33a5-115">The next stage of Redis Cache update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>