<Type Name="IWithLoadBalancingRule" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule">
  <TypeSignature Language="C#" Value="public interface IWithLoadBalancingRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLoadBalancingRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLoadBalancingRule" />
  <TypeSignature Language="F#" Value="type IWithLoadBalancingRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="39327-101">Die Stufe des Load Balancers aktualisieren, sodass hinzufügen, entfernen oder Ändern von Load balancer-Regeln.</span><span class="sxs-lookup"><span data-stu-id="39327-101">The stage of the load balancer update allowing to add, remove or modify load balancing rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt; DefineLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.DefineLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineLoadBalancingRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;" Usage="iWithLoadBalancingRule.DefineLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="39327-102">Der Name des der lastenausgleichsregel.</span><span class="sxs-lookup"><span data-stu-id="39327-102">The name of the load balancing rule.</span></span></param>
        <summary>
            <span data-ttu-id="39327-103">Beginn der Definition einer neuen lastenausgleichsregel zum Lastenausgleich hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="39327-103">Begins the definition of a new load balancing rule to add to the load balancer.</span></span>
            <span data-ttu-id="39327-104">Die Definition muss mit einem Aufruf von LoadBalancerTcpProbe.DefinitionStages.WithAttach.attach() abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="39327-104">The definition must be completed with a call to  LoadBalancerTcpProbe.DefinitionStages.WithAttach.attach().</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="39327-105">Die erste Stufe der neue Regeldefinition für den Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="39327-105">The first stage of the new load balancing rule definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate UpdateLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.UpdateLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate" Usage="iWithLoadBalancingRule.UpdateLoadBalancingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="39327-106">Der Name der lastenausgleichsregel zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="39327-106">The name of the load balancing rule to update.</span></span></param>
        <summary>
            <span data-ttu-id="39327-107">Startet die Beschreibung des ein Update für eine vorhandene lastenausgleichsregel für dieses Lastenausgleichsmodul.</span><span class="sxs-lookup"><span data-stu-id="39327-107">Begins the description of an update to an existing load balancing rule on this load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="39327-108">Die erste Phase des Load balancing Regel Updates.</span><span class="sxs-lookup"><span data-stu-id="39327-108">The first stage of the load balancing rule update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLoadBalancingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate WithoutLoadBalancingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IWithLoadBalancingRule.WithoutLoadBalancingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLoadBalancingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLoadBalancingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancer.Update.IUpdate" Usage="iWithLoadBalancingRule.WithoutLoadBalancingRule name" />
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
        <param name="name"><span data-ttu-id="39327-109">Der Name des zu entfernenden Regel Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="39327-109">The name of the load balancing rule to remove.</span></span></param>
        <summary>
            <span data-ttu-id="39327-110">Entfernt die angegebene lastenausgleichsregel aus dem Lastenausgleich, falls vorhanden.</span><span class="sxs-lookup"><span data-stu-id="39327-110">Removes the specified load balancing rule from the load balancer, if present.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="39327-111">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="39327-111">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>