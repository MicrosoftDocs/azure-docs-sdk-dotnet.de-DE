<Type Name="ISupportsGettingByParent&lt;T,ParentT,ManagerT&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent&lt;T,ParentT,ManagerT&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsGettingByParent&lt;T,ParentT,ManagerT&gt; where ParentT : IResource, IHasResourceGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsGettingByParent`3&lt;T, (class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup) ParentT, ManagerT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsGettingByParent(Of T, ParentT, ManagerT)" />
  <TypeSignature Language="F#" Value="type ISupportsGettingByParent&lt;'T, 'ParentT, 'ManagerT (requires 'ParentT :&gt; IResource and 'ParentT :&gt; IHasResourceGroup)&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
    <TypeParameter Name="ParentT">
      <Constraints>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
        <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="ManagerT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <typeparam name="ParentT">To be added.</typeparam>
    <typeparam name="ManagerT">To be added.</typeparam>
    <summary>
            Bietet Zugriff auf das Abrufen einer bestimmten Azure-Ressource, die basierend auf seinem Ressourcengruppe und übergeordneten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetByParent">
      <MemberSignature Language="C#" Value="public T GetByParent (ParentT parentResource, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByParent(!ParentT parentResource, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParent(`1,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByParent (parentResource As ParentT, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByParent : 'ParentT * string -&gt; 'T" Usage="iSupportsGettingByParent.GetByParent (parentResource, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="parentResource">die Instanz des übergeordneten Ressource.</param>
        <param name="name">der Name der Ressource.</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der Ressource.</return>
      </Docs>
    </Member>
    <Member MemberName="GetByParent">
      <MemberSignature Language="C#" Value="public T GetByParent (string resourceGroup, string parentName, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetByParent(string resourceGroup, string parentName, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParent(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByParent (resourceGroup As String, parentName As String, name As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetByParent : string * string * string -&gt; 'T" Usage="iSupportsGettingByParent.GetByParent (resourceGroup, parentName, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">der Name der Ressourcengruppe.</param>
        <param name="parentName">der Name der übergeordneten Ressource.</param>
        <param name="name">der Name der Ressource.</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der Ressource.</return>
      </Docs>
    </Member>
    <Member MemberName="GetByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByParentAsync (ParentT parentResource, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByParentAsync(!ParentT parentResource, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParentAsync(`1,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByParentAsync : 'ParentT * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingByParent.GetByParentAsync (parentResource, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="parentResource" Type="ParentT" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="parentResource">die Instanz des übergeordneten Ressource.</param>
        <param name="name">der Name der Ressource.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der Ressource.</return>
      </Docs>
    </Member>
    <Member MemberName="GetByParentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByParentAsync (string resourceGroup, string parentName, string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByParentAsync(string resourceGroup, string parentName, string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingByParent`3.GetByParentAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByParentAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingByParent.GetByParentAsync (resourceGroup, parentName, name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="parentName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroup">der Name der Ressourcengruppe.</param>
        <param name="parentName">der Name der übergeordneten Ressource.</param>
        <param name="name">der Name der Ressource.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine unveränderliche Darstellung der Ressource.</return>
      </Docs>
    </Member>
  </Members>
</Type>