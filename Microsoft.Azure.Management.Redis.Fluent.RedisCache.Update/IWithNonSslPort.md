<Type Name="IWithNonSslPort" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort">
  <TypeSignature Language="C#" Value="public interface IWithNonSslPort" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNonSslPort" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNonSslPort" />
  <TypeSignature Language="F#" Value="type IWithNonSslPort = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein Redis-Cache aktualisieren lässt nicht SSL-Port aktiviert bzw. deaktiviert werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNonSslPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithNonSslPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithNonSslPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort.WithNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNonSslPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNonSslPort : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithNonSslPort.WithNonSslPort " />
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
            Ermöglicht nicht-Ssl-Redis-Server-port (6379).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNonSslPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutNonSslPort ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate WithoutNonSslPort() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IWithNonSslPort.WithoutNonSslPort" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNonSslPort () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNonSslPort : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Update.IUpdate" Usage="iWithNonSslPort.WithoutNonSslPort " />
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
            Deaktiviert-nicht-Ssl-Redis-Server-port (6379).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Redis-Cache aktualisieren.</return>
      </Docs>
    </Member>
  </Members>
</Type>