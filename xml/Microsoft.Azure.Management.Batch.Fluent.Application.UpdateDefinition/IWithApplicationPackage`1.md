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
    <typeparam name="ParentT"><span data-ttu-id="3171b-101">Die Phase des übergeordneten Elements Batch-Konto Definition wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="3171b-101">The stage of the parent Batch account definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="3171b-102">Die Phase der Erstellung eines Anwendungspakets Definition für eine Batch.</span><span class="sxs-lookup"><span data-stu-id="3171b-102">The stage of a Batch application definition allowing the creation of an application package.</span></span>
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
        <param name="version"><span data-ttu-id="3171b-103">Die Version der Anwendung.</span><span class="sxs-lookup"><span data-stu-id="3171b-103">The version of the application.</span></span></param>
        <summary>
            <span data-ttu-id="3171b-104">Erste Stufe neuen Anwendungspakets in Batch-Konto-Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="3171b-104">First stage to create new application package in Batch account application.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3171b-105">nächste Stufe auf die Anwendung zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="3171b-105">Next stage to create the application.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>