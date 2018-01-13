<Type Name="ILoadBalancerProbe" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe">
  <TypeSignature Language="C#" Value="public interface ILoadBalancerProbe : Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, Microsoft.Azure.Management.Network.Fluent.IHasPort, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancerProbe implements class Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, class Microsoft.Azure.Management.Network.Fluent.IHasPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancerProbe&#xA;Implements IChildResource(Of ILoadBalancer), IHasInner(Of ProbeInner), IHasLoadBalancingRules, IHasParent(Of ILoadBalancer), IHasPort, IHasProtocol(Of ProbeProtocol)" />
  <TypeSignature Language="F#" Value="type ILoadBalancerProbe = interface&#xA;    interface IHasInner&lt;ProbeInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;&#xA;    interface IHasLoadBalancingRules&#xA;    interface IHasProtocol&lt;ProbeProtocol&gt;&#xA;    interface IHasPort" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPort</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="f73c9-101">Eine unveränderliche clientseitige Darstellung einer Prüfpunkt mit Lastenausgleich.</span><span class="sxs-lookup"><span data-stu-id="f73c9-101">An immutable client-side representation of a load balancing probe.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="f73c9-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="f73c9-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public int IntervalInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IntervalInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : int" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe.IntervalInSeconds" />
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
            <span data-ttu-id="f73c9-103">Ruft die Anzahl der Sekunden zwischen den Tests.</span><span class="sxs-lookup"><span data-stu-id="f73c9-103">Gets number of seconds between probes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfProbes">
      <MemberSignature Language="C#" Value="public int NumberOfProbes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfProbes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe.NumberOfProbes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfProbes As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfProbes : int" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe.NumberOfProbes" />
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
            <span data-ttu-id="f73c9-104">Ruft die Anzahl der fehlgeschlagenen Tests vor dem Knoten wird bestimmt, fehlerhaft sein.</span><span class="sxs-lookup"><span data-stu-id="f73c9-104">Gets number of failed probes before the node is determined to be unhealthy.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>