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
            Eine Definition der Redis-Cache mit ausreichenden Eingaben zum Erstellen eines neuen Redis-Caches in der Cloud, aber das Verfügbarmachen von zusätzlichen optionalen Eingaben an.
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
            Ermöglicht nicht-Ssl-Redis-Server-port (6379).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
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
        <param name="redisConfiguration">Konfiguration des Redis-Cache als Karte nach Namen indiziert.</param>
        <summary>
            Alle Redis-Einstellungen. Einige möglichen Schlüssel: Rdb-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, der Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
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
        <param name="key">Die redis-Konfigurationsname.</param>
        <param name="value">Die redis-Konfigurationswert.</param>
        <summary>
            Gibt die Redis-Einstellung.
            der RDB-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
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
        <param name="staticIP">der statische IP-Wert festgelegt.</param>
        <summary>
            Legt die Redis-Cache: statische IP-Adresse fest. Erforderlich, wenn Sie einen Redis Cache in einem vorhandenen virtuellen Azure-Netzwerk bereitstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
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
        <param name="network">die Instanz des Netzwerk-Objekts.</param>
        <param name="subnetName">Der Name des Subnetzes.</param>
        <summary>
            Weist das angegebene Subnetz für diese Instanz des Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>