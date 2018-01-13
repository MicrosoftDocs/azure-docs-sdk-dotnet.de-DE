<Type Name="ISupportsBeginDeletingByName" FullName="Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName">
  <TypeSignature Language="C#" Value="public interface ISupportsBeginDeletingByName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISupportsBeginDeletingByName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISupportsBeginDeletingByName" />
  <TypeSignature Language="F#" Value="type ISupportsBeginDeletingByName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Bietet Zugriff auf die beim Löschen einer Ressource von Azure, die Ressourcen-ID identifiziert wird
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginDeleteByName">
      <MemberSignature Language="C#" Value="public void BeginDeleteByName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void BeginDeleteByName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName.BeginDeleteByName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub BeginDeleteByName (name As String)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteByName : string -&gt; unit" Usage="iSupportsBeginDeletingByName.BeginDeleteByName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">der Name der Ressource löschen</param>
        <summary>
            Startet beim Löschen einer Ressource von Azure, mit dem Ressourcennamen identifiziert wird. Die Ressource verbleibt, bis get() gibt Null zurück.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteByNameAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task BeginDeleteByNameAsync (string name, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task BeginDeleteByNameAsync(string name, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsBeginDeletingByName.BeginDeleteByNameAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteByNameAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iSupportsBeginDeletingByName.BeginDeleteByNameAsync (name, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">der Name der Ressource löschen</param>
        <param name="cancellationToken">das Abbruchtoken, das das cancellationToken</param>
        <summary>
            Startet beim Löschen einer Ressource von Azure, mit dem Ressourcennamen identifiziert wird. Die Ressource verbleibt, bis get() gibt Null zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Eine "await" können Aufgabe für den asynchronen Vorgang.</return>
      </Docs>
    </Member>
  </Members>
</Type>