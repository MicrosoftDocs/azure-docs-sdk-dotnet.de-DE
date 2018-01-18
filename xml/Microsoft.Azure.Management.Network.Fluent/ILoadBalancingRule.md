<Type Name="ILoadBalancingRule" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule">
  <TypeSignature Language="C#" Value="public interface ILoadBalancingRule : Microsoft.Azure.Management.Network.Fluent.IHasBackendPort, Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP, Microsoft.Azure.Management.Network.Fluent.IHasFrontend, Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancingRule implements class Microsoft.Azure.Management.Network.Fluent.IHasBackendPort, class Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP, class Microsoft.Azure.Management.Network.Fluent.IHasFrontend, class Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancingRule&#xA;Implements IChildResource(Of ILoadBalancer), IHasBackendPort, IHasFloatingIP, IHasFrontend, IHasFrontendPort, IHasInner(Of LoadBalancingRuleInner), IHasParent(Of ILoadBalancer), IHasProtocol(Of TransportProtocol)" />
  <TypeSignature Language="F#" Value="type ILoadBalancingRule = interface&#xA;    interface IHasInner&lt;LoadBalancingRuleInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;&#xA;    interface IHasBackendPort&#xA;    interface IHasFrontend&#xA;    interface IHasFloatingIP&#xA;    interface IHasProtocol&lt;TransportProtocol&gt;&#xA;    interface IHasFrontendPort" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasBackendPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFloatingIP</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFrontend</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasFrontendPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.TransportProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.LoadBalancingRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="84427-101">Eine unveränderliche clientseitige Darstellung von einer HTTP-lastenausgleichsregel.</span><span class="sxs-lookup"><span data-stu-id="84427-101">An immutable client-side representation of an HTTP load balancing rule.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="84427-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="84427-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Backend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend Backend { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend Backend" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.Backend" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Backend As ILoadBalancerBackend" />
      <MemberSignature Language="F#" Value="member this.Backend : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.Backend" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84427-103">Ruft das Back-End der lastenausgleichsregel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="84427-103">Gets the backend associated with the load balancing rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public int IdleTimeoutInMinutes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IdleTimeoutInMinutes As Integer" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : int" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84427-104">Ruft die Anzahl von Minuten, bevor eine inaktive Verbindung geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="84427-104">Gets the number of minutes before an inactive connection is closed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadDistribution">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.LoadDistribution LoadDistribution { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.LoadDistribution LoadDistribution" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.LoadDistribution" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadDistribution As LoadDistribution" />
      <MemberSignature Language="F#" Value="member this.LoadDistribution : Microsoft.Azure.Management.Network.Fluent.Models.LoadDistribution" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.LoadDistribution" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.LoadDistribution</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84427-105">Ruft die Methode der lastenverteilung ab.</span><span class="sxs-lookup"><span data-stu-id="84427-105">Gets the method of load distribution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Probe">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe Probe { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe Probe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.Probe" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Probe As ILoadBalancerProbe" />
      <MemberSignature Language="F#" Value="member this.Probe : Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancingRule.Probe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="84427-106">Ruft die Überprüfung der lastenausgleichsregel zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="84427-106">Gets the probe associated with the load balancing rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>