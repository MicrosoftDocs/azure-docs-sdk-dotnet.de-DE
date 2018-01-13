<Type Name="IWithApplicationPackage&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithApplicationPackage&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithApplicationPackage`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithApplicationPackage(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithApplicationPackage&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase des übergeordneten Elements Batch-Konto Definition wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der Erstellung eines Anwendungspakets Definition für eine Batch.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineNewApplicationPackage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt; DefineNewApplicationPackage (string version);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; DefineNewApplicationPackage(string version) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithApplicationPackage`1.DefineNewApplicationPackage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNewApplicationPackage (version As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member DefineNewApplicationPackage : string -&gt; Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithApplicationPackage.DefineNewApplicationPackage version" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Fluent.Application.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="version" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="version">Die Version der Anwendung.</param>
        <summary>
            Erste Stufe neuen Anwendungspakets in Batch-Konto-Anwendung erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>nächste Stufe auf die Anwendung zu erstellen.</return>
      </Docs>
    </Member>
  </Members>
</Type>