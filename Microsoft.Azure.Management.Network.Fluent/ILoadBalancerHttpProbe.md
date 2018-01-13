<Type Name="ILoadBalancerHttpProbe" FullName="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe">
  <TypeSignature Language="C#" Value="public interface ILoadBalancerHttpProbe : Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ILoadBalancerHttpProbe implements class Microsoft.Azure.Management.Network.Fluent.IHasLoadBalancingRules, class Microsoft.Azure.Management.Network.Fluent.IHasPort, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ProbeInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe" />
  <TypeSignature Language="VB.NET" Value="Public Interface ILoadBalancerHttpProbe&#xA;Implements IChildResource(Of ILoadBalancer), IHasInner(Of ProbeInner), IHasParent(Of ILoadBalancer), IHasProtocol(Of ProbeProtocol), ILoadBalancerProbe" />
  <TypeSignature Language="F#" Value="type ILoadBalancerHttpProbe = interface&#xA;    interface ILoadBalancerProbe&#xA;    interface IHasInner&lt;ProbeInner&gt;&#xA;    interface IChildResource&lt;ILoadBalancer&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ILoadBalancer&gt;&#xA;    interface IHasLoadBalancingRules&#xA;    interface IHasProtocol&lt;ProbeProtocol&gt;&#xA;    interface IHasPort" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ProbeProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ILoadBalancerProbe</InterfaceName>
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
            Eine unveränderliche clientseitige Darstellung der Prüfpunkts für eine HTTP-Lastenausgleich.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="RequestPath">
      <MemberSignature Language="C#" Value="public string RequestPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RequestPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe.RequestPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RequestPath As String" />
      <MemberSignature Language="F#" Value="member this.RequestPath : string" Usage="Microsoft.Azure.Management.Network.Fluent.ILoadBalancerHttpProbe.RequestPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Pfad der HTTP-Anforderung für den HTTP-Test aufrufen, um den Status zu überprüfen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>