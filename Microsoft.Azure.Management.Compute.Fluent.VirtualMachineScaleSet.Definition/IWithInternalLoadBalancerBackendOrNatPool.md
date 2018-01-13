<Type Name="IWithInternalLoadBalancerBackendOrNatPool" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool">
  <TypeSignature Language="C#" Value="public interface IWithInternalLoadBalancerBackendOrNatPool : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInternalLoadBalancerBackendOrNatPool implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInternalLoadBalancerBackendOrNatPool&#xA;Implements IWithInternalInternalLoadBalancerNatPool" />
  <TypeSignature Language="F#" Value="type IWithInternalLoadBalancerBackendOrNatPool = interface&#xA;    interface IWithInternalInternalLoadBalancerNatPool&#xA;    interface IWithOS" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Phase der einer virtuellen Maschine Skalierung Gruppe Definition mit zuzuordnende Back-End-pools und/oder eingehende NAT-Pools mit den ausgewählten internen Lastenausgleich mit der primären Netzwerkschnittstelle der virtuellen Computer in der Menge der Skalierung.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryInternalLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool WithPrimaryInternalLoadBalancerBackends (params string[] backendNames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool WithPrimaryInternalLoadBalancerBackends(string[] backendNames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool.WithPrimaryInternalLoadBalancerBackends(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryInternalLoadBalancerBackends (ParamArray backendNames As String()) As IWithInternalInternalLoadBalancerNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryInternalLoadBalancerBackends : string[] -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool" Usage="iWithInternalLoadBalancerBackendOrNatPool.WithPrimaryInternalLoadBalancerBackends backendNames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalInternalLoadBalancerNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="backendNames" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="backendNames">Namen der vorhandenen Back-Ends in der ausgewählten Load Balancer.</param>
        <summary>
            Ordnet die angegebene Back-Ends des ausgewählten Load Balancers primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>