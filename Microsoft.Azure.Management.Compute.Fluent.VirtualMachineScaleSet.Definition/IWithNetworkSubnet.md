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
            Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht das Subnetz des virtuellen Netzwerks für die primäre Netzwerkkonfiguration an.
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
        <param name="network">Ein vorhandenes virtuelles Netzwerk.</param>
        <param name="subnetName">Der Subnetzname.</param>
        <summary>
            Ordnen Sie die primäre Netzwerkschnittstelle der virtuellen Computer in der Menge der Skalierung mit ein vorhandenen virtuellen Netzwerk-Subnetz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>