<Type Name="IWithInternalInternalLoadBalancerNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInternalInternalLoadBalancerNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInternalInternalLoadBalancerNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInternalInternalLoadBalancerNatPool&#xA;Implements IWithOS" />
  <TypeSignature Language="F#" Value="type IWithInternalInternalLoadBalancerNatPool = interface&#xA;    interface IWithOS" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f2fdc-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge Skalierung eingehenden NAT-Pools, von der ausgewählten internen Load Balancer zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f2fdc-101">The stage of the virtual machine scale set definition allowing to associate inbound NAT pools of the selected internal load balancer with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternalLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithPrimaryInternalLoadBalancerInboundNatPools (params string[] natPoolNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithPrimaryInternalLoadBalancerInboundNatPools(string[] natPoolNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternalLoadBalancerInboundNatPools (ParamArray natPoolNames As String()) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternalLoadBalancerInboundNatPools : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" Usage="iWithInternalInternalLoadBalancerNatPool.WithPrimaryInternalLoadBalancerInboundNatPools natPoolNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</ReturnType>
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
        <param name="natPoolNames"><span data-ttu-id="f2fdc-102">Eingehende NAT-Pool-Namen an.</span><span class="sxs-lookup"><span data-stu-id="f2fdc-102">Inbound NAT pool names.</span></span></param>
        <summary>
            <span data-ttu-id="f2fdc-103">Zuordnen von internen Load Balancer eingehende NAT-Pools mit der die primäre Netzwerkschnittstelle der Skala festlegen, virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="f2fdc-103">Associate internal load balancer inbound NAT pools with the the primary network interface of the scale set virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f2fdc-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="f2fdc-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>