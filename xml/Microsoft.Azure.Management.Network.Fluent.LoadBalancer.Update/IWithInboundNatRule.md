<Type Name="IWithInboundNatRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule">
  <TypeSignature Language="C#" Value="public interface IWithInboundNatRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithInboundNatRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithInboundNatRule" />
  <TypeSignature Language="F#" Value="type IWithInboundNatRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="20b73-101">Die Phase eines Lastenausgleichs aktualisieren definieren, entfernen oder bearbeiten die NAT-Eingangsregeln ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="20b73-101">The stage of a load balancer update allowing to define, remove or edit inbound NAT rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.DefineInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineInboundNatRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithInboundNatRule.DefineInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="20b73-102">Der Name für die eingehende NAT-Regel.</span><span class="sxs-lookup"><span data-stu-id="20b73-102">The name for the inbound NAT rule.</span></span></param>
        <summary>
            <span data-ttu-id="20b73-103">Beginn der Definition einer neuen NAT-Eingangsregel.</span><span class="sxs-lookup"><span data-stu-id="20b73-103">Begins the definition of a new inbound NAT rule.</span></span>
            <span data-ttu-id="20b73-104">Die Definition muss mit einem Aufruf von LoadBalancerInboundNatRule.UpdateDefinitionStages.WithAttach.attach() abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="20b73-104">The definition must be completed with a call to  LoadBalancerInboundNatRule.UpdateDefinitionStages.WithAttach.attach().</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="20b73-105">Die erste Phase des der neuen Regel für eingehende NAT Definition.</span><span class="sxs-lookup"><span data-stu-id="20b73-105">The first stage of the new inbound NAT rule definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate UpdateInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.UpdateInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate" Usage="iWithInboundNatRule.UpdateInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="20b73-106">Der Name der eingehenden NAT-Regel aktualisiert.</span><span class="sxs-lookup"><span data-stu-id="20b73-106">The name of the inbound NAT rule to update.</span></span></param>
        <summary>
            <span data-ttu-id="20b73-107">Startet die Beschreibung der Aktualisierung einer vorhandenen eingehenden NAT-Regel an.</span><span class="sxs-lookup"><span data-stu-id="20b73-107">Begins the description of an update to an existing inbound NAT rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="20b73-108">Die erste Phase des eingehenden NAT-Regel-Updates.</span><span class="sxs-lookup"><span data-stu-id="20b73-108">The first stage of the inbound NAT rule update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutInboundNatRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutInboundNatRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithInboundNatRule.WithoutInboundNatRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutInboundNatRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutInboundNatRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithInboundNatRule.WithoutInboundNatRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="20b73-109">Der Name einer vorhandenen eingehenden NAT-Regel für dieses Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="20b73-109">The name of an existing inbound NAT rule on this load balancer.</span></span></param>
        <summary>
            <span data-ttu-id="20b73-110">Entfernt die angegebene NAT-Eingangsregel aus dem Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="20b73-110">Removes the specified inbound NAT rule from the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="20b73-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="20b73-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>