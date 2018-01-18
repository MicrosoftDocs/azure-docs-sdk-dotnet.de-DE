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
            <span data-ttu-id="8a127-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht, einen internen Lastenausgleich für die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="8a127-101">The stage of a virtual machine scale set definition allowing to specify an internal load balancer for the primary network interface of the virtual machines in the scale set.</span></span>
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
        <param name="loadBalancer"><span data-ttu-id="8a127-102">Einen vorhandenen internen Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="8a127-102">An existing internal load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="8a127-103">Gibt den internen Lastenausgleich, die an die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skala, deren Back-Ends und/oder NAT-Pools zugewiesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="8a127-103">Specifies the internal load balancer whose backends and/or NAT pools can be assigned to the primary network interface of the virtual machines in the scale set.</span></span>
            <span data-ttu-id="8a127-104">Standardmäßig ist die Back-Ends und eingehenden NAT-Pools des Lastenausgleichs der virtuellen Computer in der Menge Skalierung der primären Netzwerkschnittstelle zugeordnet, bis Teil davon in den nächsten Schritten ausgewählt ist.</span><span class="sxs-lookup"><span data-stu-id="8a127-104">By default all the backends and inbound NAT pools of the load balancer will be associated with the primary network interface of the virtual machines in the scale set, unless subset of them is selected in the next stages.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8a127-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8a127-105">The next stage of the definition.</span></span></return>
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
            <span data-ttu-id="8a127-106">Gibt an, dass keine internen Load Balancer primäre Netzwerkschnittstellen der virtuellen Computer in der Skalierungsgruppe zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8a127-106">Specifies that no internal load balancer should be associated with the primary network interfaces of the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8a127-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8a127-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>