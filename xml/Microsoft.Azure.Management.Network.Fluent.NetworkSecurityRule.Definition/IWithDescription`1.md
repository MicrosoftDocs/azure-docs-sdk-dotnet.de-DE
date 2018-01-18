<Type Name="IWithDescription&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDescription&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDescription`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDescription(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDescription&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="4b0a4-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="4b0a4-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="4b0a4-102">Die Phase der Regel der Definition des Netzwerks können die Beschreibung angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="4b0a4-102">The stage of the network rule definition allowing the description to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt; WithDescription (string description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithDescription(string description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithDescription`1.WithDescription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDescription (description As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDescription : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDescription.WithDescription description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="description"><span data-ttu-id="4b0a4-103">Die Beschreibung dieser Regel zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="4b0a4-103">The text description to associate with this security rule.</span></span></param>
        <summary>
            <span data-ttu-id="4b0a4-104">Gibt eine Beschreibung für diese Sicherheitsregel zur.</span><span class="sxs-lookup"><span data-stu-id="4b0a4-104">Specifies a description for this security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4b0a4-105">Die nächste Stufe.</span><span class="sxs-lookup"><span data-stu-id="4b0a4-105">The next stage.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>