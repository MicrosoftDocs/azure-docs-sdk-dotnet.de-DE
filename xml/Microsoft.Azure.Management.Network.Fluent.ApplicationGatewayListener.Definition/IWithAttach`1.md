<Type Name="IWithAttach&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAttach&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication&lt;ParentT&gt;, Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAttach`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAttach(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithHostName(Of IWithAttach(Of IWithCreate)), IWithHostName(Of ParentT), IWithProtocol(Of ParentT), IWithServerNameIndication(Of IWithAttach(Of IWithCreate)), IWithServerNameIndication(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAttach&lt;'ParentT&gt; = interface&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithProtocol&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;'ParentT&gt;&#xA;    interface IWithHostName&lt;IWithAttach&lt;IWithCreate&gt;&gt;&#xA;    interface IWithServerNameIndication&lt;'ParentT&gt;&#xA;    interface IWithServerNameIndication&lt;IWithAttach&lt;IWithCreate&gt;&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithHostName&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithProtocol&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithServerNameIndication&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasHostName.Definition.IWithHostName&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasServerNameIndication.Definition.IWithServerNameIndication&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayListener.Definition.IWithAttach&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="3cabc-101">Die Phase der Definition des übergeordneten Anwendung Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="3cabc-101">The stage of the parent application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="3cabc-102">Der abschließenden Phase einer Anwendung Gateway HTTP-Listener.</span><span class="sxs-lookup"><span data-stu-id="3cabc-102">The final stage of an application gateway HTTP listener.</span></span>
            <span data-ttu-id="3cabc-103">Zu diesem Zeitpunkt alle verbleibenden Einstellungen an optionalen können angegeben werden, oder die Definition der Definition des übergeordneten-Anwendung Gateway mit WithAttach.attach() angefügt werden kann.</span><span class="sxs-lookup"><span data-stu-id="3cabc-103">At this stage, any remaining optional settings can be specified, or the definition can be attached to the parent application gateway definition using  WithAttach.attach().</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members />
</Type>