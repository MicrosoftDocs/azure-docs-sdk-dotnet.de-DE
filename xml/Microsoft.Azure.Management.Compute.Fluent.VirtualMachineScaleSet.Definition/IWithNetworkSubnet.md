<Type Name="IWithNetworkSubnet" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithNetworkSubnet">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithNetworkSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSubnet" />
  <TypeSignature Language="F#" Value="type IWithNetworkSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2b6d6-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht das Subnetz des virtuellen Netzwerks für die primäre Netzwerkkonfiguration an.</span><span class="sxs-lookup"><span data-stu-id="2b6d6-101">The stage of a virtual machine scale set definition allowing to specify the virtual network subnet for the primary network configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetworkSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer WithExistingPrimaryNetworkSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer WithExistingPrimaryNetworkSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithNetworkSubnet.WithExistingPrimaryNetworkSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetworkSubnet (network As INetwork, subnetName As String) As IWithPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetworkSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer" Usage="iWithNetworkSubnet.WithExistingPrimaryNetworkSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithPrimaryInternetFacingLoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="2b6d6-102">Ein vorhandenes virtuelles Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="2b6d6-102">An existing virtual network.</span></span></param>
        <param name="subnetName"><span data-ttu-id="2b6d6-103">Der Subnetzname.</span><span class="sxs-lookup"><span data-stu-id="2b6d6-103">The subnet name.</span></span></param>
        <summary>
            <span data-ttu-id="2b6d6-104">Ordnen Sie die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skalierung mit ein vorhandenen virtuellen Netzwerk-Subnetz.</span><span class="sxs-lookup"><span data-stu-id="2b6d6-104">Associate an existing virtual network subnet with the primary network interface of the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2b6d6-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2b6d6-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>