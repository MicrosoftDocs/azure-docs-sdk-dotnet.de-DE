<Type Name="IWithPrimaryInternalLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternalLoadBalancerNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternalLoadBalancerNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerBackend, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternalLoadBalancerNatPool&#xA;Implements IAppliable(Of IVirtualMachineScaleSet), IBeta, IUpdateWithTags(Of IWithApply), IWithApply" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternalLoadBalancerNatPool = interface&#xA;    interface IWithApply&#xA;    interface IAppliable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IWithApply&gt;&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithSku&#xA;    interface IWithCapacity&#xA;    interface IWithExtension&#xA;    interface IWithoutPrimaryLoadBalancer&#xA;    interface IWithoutPrimaryLoadBalancerBackend&#xA;    interface IWithoutPrimaryLoadBalancerNatPool&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithAvailabilityZone" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</InterfaceName>
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
            Die Phase der VM-Skalierungsgruppe festgelegt Update ermöglicht, die primären Netzwerkschnittstelle der virtuellen Computer in der Menge Skalierung eingehenden NAT-Pools, von der ausgewählten internen Load Balancer zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternalLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithPrimaryInternalLoadBalancerInboundNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithPrimaryInternalLoadBalancerInboundNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternalLoadBalancerInboundNatPools (ParamArray natPoolNames As String()) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternalLoadBalancerInboundNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithPrimaryInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="natPoolNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="natPoolNames">Die Namen der vorhandenen eingehenden NAT-Pools in der ausgewählten Load Balancer.</param>
        <summary>
            Ordnet der angegebenen internen Lastenausgleich eingehende NAT-Pools mit der die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>