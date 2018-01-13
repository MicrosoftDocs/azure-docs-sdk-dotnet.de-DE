<Type Name="IWithPrimaryInternalLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryInternalLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithPrimaryInternalLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht, einen internen Lastenausgleich für die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool WithExistingPrimaryInternalLoadBalancer (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool WithExistingPrimaryInternalLoadBalancer(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer.WithExistingPrimaryInternalLoadBalancer(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryInternalLoadBalancer (loadBalancer As ILoadBalancer) As IWithInternalLoadBalancerBackendOrNatPool" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryInternalLoadBalancer : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool" Usage="iWithPrimaryInternalLoadBalancer.WithExistingPrimaryInternalLoadBalancer loadBalancer" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithInternalLoadBalancerBackendOrNatPool</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
      </Parameters>
      <Docs>
        <param name="loadBalancer">Einen vorhandenen internen Lastenausgleich.</param>
        <summary>
            Gibt den internen Lastenausgleich, die an die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala, deren Back-Ends und/oder NAT-Pools zugewiesen werden kann.
            Standardmäßig ist die Back-Ends und eingehenden NAT-Pools des Lastenausgleichs der virtuellen Computer in der Menge Skalierung der primären Netzwerkschnittstelle zugeordnet, bis Teil davon in den nächsten Schritten ausgewählt ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithoutPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS WithoutPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternalLoadBalancer.WithoutPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancer () As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS" Usage="iWithPrimaryInternalLoadBalancer.WithoutPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass keine internen Load Balancer primäre Netzwerkschnittstellen der virtuellen Computer in der Skalierungsgruppe zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>