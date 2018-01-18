<Type Name="IWithPriority&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithPriority&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPriority`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPriority(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithPriority&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="bd185-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="bd185-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="bd185-102">Die Phase der Regel der Definition des Netzwerks können die Priorität kann angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="bd185-102">The stage of the network rule definition allowing the priority to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt; WithPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithPriority`1.WithPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPriority : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithPriority.WithPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="bd185-103">Die Prioritätsnummer im Bereich von 100 auf 4096.</span><span class="sxs-lookup"><span data-stu-id="bd185-103">The priority number in the range 100 to 4096.</span></span></param>
        <summary>
            <span data-ttu-id="bd185-104">Gibt die Priorität zuweisen von dieser Regel.</span><span class="sxs-lookup"><span data-stu-id="bd185-104">Specifies the priority to assign to this rule.</span></span>
            <span data-ttu-id="bd185-105">In der Reihenfolge ihrer Priorität zugewiesen werden Sicherheitsregeln angewendet.</span><span class="sxs-lookup"><span data-stu-id="bd185-105">Security rules are applied in the order of their assigned priority.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bd185-106">Die nächste Stufe.</span><span class="sxs-lookup"><span data-stu-id="bd185-106">The next stage.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>