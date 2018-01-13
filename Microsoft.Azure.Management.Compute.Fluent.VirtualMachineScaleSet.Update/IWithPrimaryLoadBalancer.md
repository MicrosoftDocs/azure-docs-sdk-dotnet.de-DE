<Type Name="IWithPrimaryLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryLoadBalancer : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryLoadBalancer implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryLoadBalancer&#xA;Implements IAppliable(Of IVirtualMachineScaleSet), IBeta, IUpdateWithTags(Of IWithApply), IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryLoadBalancer = interface&#xA;    interface IWithPrimaryInternalLoadBalancer&#xA;    interface IWithApply&#xA;    interface IAppliable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IWithApply&gt;&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithSku&#xA;    interface IWithCapacity&#xA;    interface IWithExtension&#xA;    interface IWithoutPrimaryLoadBalancer&#xA;    interface IWithoutPrimaryLoadBalancerBackend&#xA;    interface IWithoutPrimaryLoadBalancerNatPool&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithAvailabilityZone" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancer</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Phase der VM-Skalierungsgruppe festgelegt Update ermöglichen Lastenausgleich für die primäre Netzwerkschnittstelle Scale Set virtuellen Computer an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool WithExistingPrimaryInternetFacingLoadBalancer (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool WithExistingPrimaryInternetFacingLoadBalancer(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer.WithExistingPrimaryInternetFacingLoadBalancer(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryInternetFacingLoadBalancer (loadBalancer As ILoadBalancer) As IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryInternetFacingLoadBalancer : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool" Usage="iWithPrimaryLoadBalancer.WithExistingPrimaryInternetFacingLoadBalancer loadBalancer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternetFacingLoadBalancerBackendOrNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">Der primäre Internetzugriff Load Balancer.</param>
        <summary>
            Gibt das Lastenausgleichsmodul als Lastenausgleichsmodul Internetzugriff für die virtuellen Computer in der Menge der Skala verwendet werden.
            Dadurch wird der aktuelle Internetzugriff Load-Balancer zugeordneten virtuellen Computer in der Skala festlegen (sofern vorhanden) ersetzt.
            Standardmäßig ist die Back-End- und eingehenden NAT-Pool des Lastenausgleichs primäre Netzwerkschnittstelle der virtuellen Computer zugeordnet, bis ein Teil davon in den nächsten Schritten ausgewählt ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>