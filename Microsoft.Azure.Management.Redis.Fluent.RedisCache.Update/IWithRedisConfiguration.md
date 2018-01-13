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
            Ein Redis-Cache aktualisieren lässt Redis-Konfiguration geändert werden.
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
            Bereinigt alle Konfigurationseinstellungen, die auf die Redis-Cache festgelegt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
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
        <param name="key">Die redis-Konfigurationsname.</param>
        <summary>
            Entfernt den angegebenen Redis-Cache-Konfigurationseinstellung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
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
        <param name="redisConfiguration">Konfiguration des Redis-Cache als Karte nach Namen indiziert.</param>
        <summary>
            Alle Redis-Einstellungen. Einige möglichen Schlüssel: Rdb-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, der Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
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
        <param name="key">Die redis-Konfigurationsname.</param>
        <param name="value">Die redis-Konfigurationswert.</param>
        <summary>
            Gibt die Redis-Einstellung.
            der RDB-Sicherung aktiviert, der Rdb-Speicher-Verbindungszeichenfolge, Rdb--sicherungshäufigkeit, Maxmemory-Delta, Maxmemory-Richtlinie, benachrichtigen-Keyspace-Ereignisse, Maxmemory-Samples Slowlog-Protokoll langsamer-als, Slowlog-Max-Len-Max-Ziplist-Listeneinträge,-Max-Ziplist-Wert aus der Liste, Hash-Max-Ziplist-Einträge, Hash-Max-Ziplist-Value festzulegen - max-Intset-Einträgen, Zset-Ziplist maximaleinträge und Zset-Max-Ziplist-Value usw.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>