<Type Name="IWithMiddleName&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithMiddleName&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithMiddleName&lt;ParentT&gt; : Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMiddleName`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithMiddleName`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMiddleName(Of ParentT)&#xA;Implements IWithLastName(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithMiddleName&lt;'ParentT&gt; = interface&#xA;    interface IWithLastName&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="decba-101">Die Phase der Definition des übergeordneten wieder nach dem Anfügen.</span><span class="sxs-lookup"><span data-stu-id="decba-101">The stage of the parent definition to return to after attaching.</span></span></typeparam>
    <summary>
            <span data-ttu-id="decba-102">Die Phase der Kontakt Definition ermöglicht Vornamen festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="decba-102">The stage of contact definition allowing middle name to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMiddleName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName&lt;ParentT&gt; WithMiddleName (string middleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName`1&lt;!ParentT&gt; WithMiddleName(string middleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithMiddleName`1.WithMiddleName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMiddleName (middleName As String) As IWithLastName(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMiddleName : string -&gt; Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName&lt;'ParentT&gt;" Usage="iWithMiddleName.WithMiddleName middleName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DomainContact.Definition.IWithLastName&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="middleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="middleName"><span data-ttu-id="decba-103">Der zweite Vorname.</span><span class="sxs-lookup"><span data-stu-id="decba-103">The middle name.</span></span></param>
        <summary>
            <span data-ttu-id="decba-104">Gibt den Vornamen an.</span><span class="sxs-lookup"><span data-stu-id="decba-104">Specifies the middle name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="decba-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="decba-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>