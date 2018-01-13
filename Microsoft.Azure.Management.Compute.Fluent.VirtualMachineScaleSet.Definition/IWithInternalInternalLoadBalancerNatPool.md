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
            Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge Skalierung eingehenden NAT-Pools, von der ausgewählten internen Load Balancer zugeordnet werden soll.
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
        <param name="natPoolNames">Eingehende NAT-Pool-Namen an.</param>
        <summary>
            Zuordnen von internen Load Balancer eingehende NAT-Pools mit der die primäre Netzwerkschnittstelle der Skala festlegen, virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>