<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAvailabilityZone&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAttach`1&lt;!ParentT&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAvailabilityZone`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IBeta, IInDefinitionAlt(Of ParentT), IWithAvailabilityZone(Of ParentT), IWithPrivateIPAddress(Of IWithAttach(Of ParentT))" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinitionAlt&lt;'ParentT&gt;&#xA;    interface IWithPrivateIPAddress&lt;IWithAttach&lt;'ParentT&gt;&gt;&#xA;    interface IWithAvailabilityZone&lt;'ParentT&gt;&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPrivateIPAddress.Definition.IWithPrivateIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAttach&lt;ParentT&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.LoadBalancerPrivateFrontend.Definition.IWithAvailabilityZone&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResourceActions.IInDefinitionAlt&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp der WithAttach.attach().</typeparam>
    <summary>
            Der abschließenden Phase eine private Front-End-Definition.
            Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder die Front-End-Definition an den übergeordneten Load Balancer-Definition mit WithAttach.attach() angefügt werden kann.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>