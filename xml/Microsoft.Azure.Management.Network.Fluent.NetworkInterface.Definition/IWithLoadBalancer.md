<Type Name="IWithLoadBalancer" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d20ed-101">Die Phase der Definition des Netzwerk-Schnittstelle ermöglicht es einem Lastenausgleichsmodul zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="d20ed-101">The stage of the network interface definition allowing to associate it with a load balancer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="d20ed-102">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="d20ed-102">An existing load balancer.</span></span></param>
        <param name="backendName"><span data-ttu-id="d20ed-103">Der Name der ein vorhandenes Back-End auf, die den load Balancer.</span><span class="sxs-lookup"><span data-stu-id="d20ed-103">The name of an existing backend on that load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="d20ed-104">Ordnet ein Back-End für einen vorhandenen Load Balancer der Netzwerkschnittstelle primäre IP-Konfiguration zu.</span><span class="sxs-lookup"><span data-stu-id="d20ed-104">Associates the network interface's primary IP configuration with a backend of an existing load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d20ed-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d20ed-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithLoadBalancer.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="d20ed-106">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="d20ed-106">An existing load balancer.</span></span></param>
        <param name="inboundNatRuleName"><span data-ttu-id="d20ed-107">Der Name einer vorhandenen eingehende NAT-Regel auf dem ausgewählten Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="d20ed-107">The name of an existing inbound NAT rule on the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="d20ed-108">Ordnet eine NAT-Regel für einen vorhandenen Load Balancer der Netzwerkschnittstelle primäre IP-Konfiguration zu.</span><span class="sxs-lookup"><span data-stu-id="d20ed-108">Associates the network interface's primary IP configuration with an inbound NAT rule of an existing load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d20ed-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d20ed-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>