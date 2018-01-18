<Type Name="IWithLoadBalancer&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="7b61d-101">Der Rückgabetyp des endgültigen Attachable.attach().</span><span class="sxs-lookup"><span data-stu-id="7b61d-101">The return type of the final  Attachable.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="7b61d-102">Die Stufe der Netzwerk-IP-Konfiguration Schnittstellendefinition an das Lastenausgleichsmodul für diese IP-Konfiguration mit zuordnen können.</span><span class="sxs-lookup"><span data-stu-id="7b61d-102">The stage of the network interface IP configuration definition allowing to specify the load balancer to associate this IP configuration with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt; WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="7b61d-103">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="7b61d-103">An existing load balancer.</span></span></param>
        <param name="backendName"><span data-ttu-id="7b61d-104">Der Name der ein vorhandenes Back-End auf, die den load Balancer.</span><span class="sxs-lookup"><span data-stu-id="7b61d-104">The name of an existing backend on that load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="7b61d-105">Gibt die Load Balancer Back-End-um diese IP-Konfiguration mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="7b61d-105">Specifies the load balancer backend to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7b61d-106">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="7b61d-106">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt; WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithLoadBalancer`1.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="7b61d-107">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="7b61d-107">An existing load balancer.</span></span></param>
        <param name="inboundNatRuleName"><span data-ttu-id="7b61d-108">Der Name einer vorhandenen eingehende NAT-Regel auf dem ausgewählten Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="7b61d-108">The name of an existing inbound NAT rule on the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="7b61d-109">Gibt an, der Load Balancer NAT-Eingangsregel, um diese IP-Konfiguration mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="7b61d-109">Specifies the load balancer inbound NAT rule to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="7b61d-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="7b61d-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>