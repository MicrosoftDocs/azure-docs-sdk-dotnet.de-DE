<Type Name="IWithSku" FullName="Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku">
  <TypeSignature Language="C#" Value="public interface IWithSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSku" />
  <TypeSignature Language="F#" Value="type IWithSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition einer Redis-Cache ermöglicht die Sku festgelegt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBasicSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithBasicSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithBasicSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithBasicSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBasicSku () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithBasicSku : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithSku.WithBasicSku " />
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
            Gibt die grundlegende Sku des Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithBasicSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithBasicSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithBasicSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithBasicSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBasicSku (capacity As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithBasicSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithSku.WithBasicSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity">Gibt an, welche Größe der Redis-Cache für grundlegende Sku mit C-Familie (0, 1, 2, 3, 4, 5, 6) bereitstellen.</param>
        <summary>
            Gibt die grundlegende Sku des Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPremiumSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPremiumSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithPremiumSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumSku () As IWithPremiumSkuCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumSku : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithSku.WithPremiumSku " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt die Premium-Sku des Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPremiumSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPremiumSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate WithPremiumSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithPremiumSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPremiumSku (capacity As Integer) As IWithPremiumSkuCreate" />
      <MemberSignature Language="F#" Value="abstract member WithPremiumSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate" Usage="iWithSku.WithPremiumSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithPremiumSkuCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity">Gibt an, welche Größe der Redis-Cache für Standard-Sku mit P-Familie (1, 2, 3, 4) bereitstellen.</param>
        <summary>
            Gibt die Premium-Sku des Redis-Cache.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStandardSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStandardSku() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithStandardSku" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : unit -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithSku.WithStandardSku " />
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
            Gibt die Standard-Sku des Redis-Caches.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStandardSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStandardSku (int capacity);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate WithStandardSku(int32 capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithSku.WithStandardSku(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStandardSku (capacity As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithStandardSku : int -&gt; Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate" Usage="iWithSku.WithStandardSku capacity" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Redis.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Redis.Fluent.RedisCache.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="capacity" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="capacity">Gibt an, welche Größe der Redis-Cache für Standard-Sku mit C-Familie (0, 1, 2, 3, 4, 5, 6) bereitstellen.</param>
        <summary>
            Gibt die Standard-Sku des Redis-Caches.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Redis-Cache-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>