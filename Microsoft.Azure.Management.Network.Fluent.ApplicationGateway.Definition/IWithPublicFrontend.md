<Type Name="IWithPublicFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicFrontend">
  <TypeSignature Language="C#" Value="public interface IWithPublicFrontend : Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicIPAddress, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPublicFrontend implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicIPAddress, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPublicFrontend&#xA;Implements IWithExistingPublicIPAddress(Of IWithCreate), IWithNewPublicIPAddressNoDnsLabel(Of IWithCreate), IWithPublicIPAddress, IWithPublicIPAddressNoDnsLabel(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithPublicFrontend = interface&#xA;    interface IWithPublicIPAddress&#xA;    interface IWithPublicIPAddressNoDnsLabel&lt;IWithCreate&gt;&#xA;    interface IWithExistingPublicIPAddress&lt;IWithCreate&gt;&#xA;    interface IWithNewPublicIPAddressNoDnsLabel&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithExistingPublicIPAddress&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithNewPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Definition.IWithPublicIPAddressNoDnsLabel&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="606d3-101">Die Phase der Definition einer Anwendung-Gateway ermöglicht, um eine oder mehrere öffentliche oder Internetzugriff, Front-Ends zu definieren.</span><span class="sxs-lookup"><span data-stu-id="606d3-101">The stage of an application gateway definition allowing to define one or more public, or Internet-facing, frontends.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithoutPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithoutPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithPublicFrontend.WithoutPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPublicFrontend () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithPublicFrontend.WithoutPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="606d3-102">Gibt an, dass das Anwendungsgateway Internetzugriff nicht sein sollte.</span><span class="sxs-lookup"><span data-stu-id="606d3-102">Specifies that the application gateway should not be Internet-facing.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="606d3-103">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="606d3-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>