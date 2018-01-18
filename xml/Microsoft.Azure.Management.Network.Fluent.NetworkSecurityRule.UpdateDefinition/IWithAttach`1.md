<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInUpdate(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInUpdate&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Update.IInUpdate&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="465ec-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="465ec-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="465ec-102">Der abschließenden Phase Sicherheitsgruppen-Regeldefinition.</span><span class="sxs-lookup"><span data-stu-id="465ec-102">The final stage of the security rule definition.</span></span>
            <span data-ttu-id="465ec-103">Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder Sicherheitsgruppen-Regeldefinition an die übergeordnete netzwerksicherheitsgruppen-Definition mit WithAttach.attach() angefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="465ec-103">At this stage, any remaining optional settings can be specified, or the security rule definition can be attached to the parent network security group definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDescription">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithDescription (string descrtiption);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithDescription(string descrtiption) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1.WithDescription(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDescription (descrtiption As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDescription : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithDescription descrtiption" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="descrtiption" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="descrtiption"><span data-ttu-id="465ec-104">Eine textbeschreibung der Sicherheitsregel zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="465ec-104">A text description to associate with the security rule.</span></span></param>
        <summary>
            <span data-ttu-id="465ec-105">Gibt eine Beschreibung für diese Sicherheitsregel zur.</span><span class="sxs-lookup"><span data-stu-id="465ec-105">Specifies a description for this security rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="465ec-106">Die nächste Stufe.</span><span class="sxs-lookup"><span data-stu-id="465ec-106">The next stage.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach`1.WithPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPriority : int -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAttach.WithPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkSecurityRule.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority"><span data-ttu-id="465ec-107">Die Prioritätsnummer im Bereich von 100 auf 4096.</span><span class="sxs-lookup"><span data-stu-id="465ec-107">The priority number in the range 100 to 4096.</span></span></param>
        <summary>
            <span data-ttu-id="465ec-108">Gibt die Priorität zuweisen von dieser Regel.</span><span class="sxs-lookup"><span data-stu-id="465ec-108">Specifies the priority to assign to this rule.</span></span>
            <span data-ttu-id="465ec-109">In der Reihenfolge ihrer Priorität zugewiesen werden Sicherheitsregeln angewendet.</span><span class="sxs-lookup"><span data-stu-id="465ec-109">Security rules are applied in the order of their assigned priority.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="465ec-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="465ec-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>