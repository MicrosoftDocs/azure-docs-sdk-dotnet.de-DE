<Type Name="ISupportsGettingById&lt;T&gt;" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface ISupportsGettingById&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsGettingById`1&lt;T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsGettingById(Of T)" />
  <TypeSignature Language="F#" Value="type ISupportsGettingById&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T">To be added.</typeparam>
    <summary>To be added.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetById">
      <MemberSignature Language="C#" Value="public T GetById (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T GetById(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetById(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetById (id As String) As T" />
      <MemberSignature Language="F#" Value="abstract member GetById : string -&gt; 'T" Usage="iSupportsGettingById.GetById id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">ID die Id der Ressource.</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>eine unveränderliche Darstellung der Ressource</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetByIdAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetByIdAsync (string id, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetByIdAsync(string id, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsGettingById`1.GetByIdAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetByIdAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T&gt;" Usage="iSupportsGettingById.GetByIdAsync (id, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="id">ID die Id der Ressource.</param>
        <param name="cancellationToken">das Abbruchtoken, das das cancellationToken</param>
        <summary>
            Ruft die Informationen zu einer Ressource von Azure auf Grundlage der Ressourcen-Id ab.
            </summary>
        <returns>eine unveränderliche Darstellung der Ressource</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>