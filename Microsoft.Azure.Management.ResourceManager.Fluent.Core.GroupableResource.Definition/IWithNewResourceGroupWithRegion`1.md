<Type Name="IWithNewResourceGroupWithRegion&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewResourceGroupWithRegion&lt;T&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewResourceGroupWithRegion`1&lt;T&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewResourceGroupWithRegion(Of T)&#xA;Implements IWithCreatableResourceGroup(Of T)" />
  <TypeSignature Language="F#" Value="type IWithNewResourceGroupWithRegion&lt;'T&gt; = interface&#xA;    interface IWithCreatableResourceGroup&lt;'T&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithCreatableResourceGroup&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T">die nächste Phase der Ressourcendefinition</typeparam>
    <summary>
            Einer Ressourcendefinition, sodass eine neue Ressourcengruppe in einer anderen Region erstellt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public T WithNewResourceGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithNewResourceGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1.WithNewResourceGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'T" Usage="iWithNewResourceGroupWithRegion.WithNewResourceGroup region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region">Region der Region, in denen Ressourcengruppe erstellt werden muss</param>
        <summary>
            Fügen Sie die Ressource in eine neue Ressourcengruppe wird erstellt.
            Die Gruppe wird am gleichen Speicherort wie die Ressource erstellt werden.
            Den Namen der Gruppe wird automatisch von den Namen der Ressource abgeleitet.
            </summary>
        <returns>die nächste Phase der Ressourcendefinition</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithNewResourceGroup">
      <MemberSignature Language="C#" Value="public T WithNewResourceGroup (string name, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T WithNewResourceGroup(string name, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.GroupableResource.Definition.IWithNewResourceGroupWithRegion`1.WithNewResourceGroup(System.String,Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member WithNewResourceGroup : string * Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; 'T" Usage="iWithNewResourceGroupWithRegion.WithNewResourceGroup (name, region)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der neuen Gruppe</param>
        <param name="region">Region der Region, in denen Ressourcengruppe erstellt werden muss</param>
        <summary>
            Fügen Sie die Ressource in eine neue Ressourcengruppe wird erstellt.
            Die Gruppe wird am gleichen Speicherort wie die Ressource erstellt werden.
            </summary>
        <returns>die nächste Phase der Ressourcendefinition</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>