<Type Name="IWithLoadBalancer" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="ac50a-101">Die Phase von der Netzwerkschnittstelle IP-Konfiguration zulassen, geben Sie das Lastenausgleichsmodul für diese IP-Konfiguration mit zuordnen.</span><span class="sxs-lookup"><span data-stu-id="ac50a-101">The stage of the network interface's IP configuration allowing to specify the load balancer to associate this IP configuration with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLoadBalancerBackend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerBackend (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerBackend(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string backendName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithExistingLoadBalancerBackend(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerBackend (loadBalancer As ILoadBalancer, backendName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerBackend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithExistingLoadBalancerBackend (loadBalancer, backendName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="backendName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="ac50a-102">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="ac50a-102">An existing load balancer.</span></span></param>
        <param name="backendName"><span data-ttu-id="ac50a-103">Der Name der ein vorhandenes Back-End auf, die den load Balancer.</span><span class="sxs-lookup"><span data-stu-id="ac50a-103">The name of an existing backend on that load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="ac50a-104">Gibt das Lastenausgleichsmodul für diese IP-Konfiguration mit zuordnen.</span><span class="sxs-lookup"><span data-stu-id="ac50a-104">Specifies the load balancer to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac50a-105">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="ac50a-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingLoadBalancerInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerInboundNatRule (Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithExistingLoadBalancerInboundNatRule(class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer loadBalancer, string inboundNatRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithExistingLoadBalancerInboundNatRule(Microsoft.Azure.Management.Network.Fluent.ILoadBalancer,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLoadBalancerInboundNatRule (loadBalancer As ILoadBalancer, inboundNatRuleName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLoadBalancerInboundNatRule : Microsoft.Azure.Management.Network.Fluent.ILoadBalancer * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithExistingLoadBalancerInboundNatRule (loadBalancer, inboundNatRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="loadBalancer" Type="Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" />
        <Parameter Name="inboundNatRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="loadBalancer"><span data-ttu-id="ac50a-106">Einen vorhandenen Load Balancer.</span><span class="sxs-lookup"><span data-stu-id="ac50a-106">An existing load balancer.</span></span></param>
        <param name="inboundNatRuleName"><span data-ttu-id="ac50a-107">Der Name einer vorhandenen eingehende NAT-Regel auf dem ausgewählten Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="ac50a-107">The name of an existing inbound NAT rule on the selected load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="ac50a-108">Gibt an, der Load Balancer NAT-Eingangsregel, um diese IP-Konfiguration mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="ac50a-108">Specifies the load balancer inbound NAT rule to associate this IP configuration with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac50a-109">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="ac50a-109">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithoutLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancerBackends () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancerBackends : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithoutLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac50a-110">Entfernt alle bestehenden Verknüpfungen mit Load Balancer-Back-Ends.</span><span class="sxs-lookup"><span data-stu-id="ac50a-110">Removes all the existing associations with load balancer backends.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac50a-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="ac50a-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancerInboundNatRules">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerInboundNatRules ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate WithoutLoadBalancerInboundNatRules() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IWithLoadBalancer.WithoutLoadBalancerInboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancerInboundNatRules () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancerInboundNatRules : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate" Usage="iWithLoadBalancer.WithoutLoadBalancerInboundNatRules " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="ac50a-112">Entfernt alle vorhandenen Zuordnungen mit Lastenausgleich für den eingehenden NAT-Regeln.</span><span class="sxs-lookup"><span data-stu-id="ac50a-112">Removes all the existing associations with load balancer inbound NAT rules.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ac50a-113">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="ac50a-113">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>