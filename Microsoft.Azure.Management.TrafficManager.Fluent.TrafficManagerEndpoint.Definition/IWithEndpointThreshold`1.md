<Type Name="IWithEndpointThreshold&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithEndpointThreshold&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithEndpointThreshold&lt;ParentT&gt; : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithGeographicLocation&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight&lt;ParentT&gt;, Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithTrafficDisabled&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndpointThreshold`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithGeographicLocation`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithTrafficDisabled`1&lt;!ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithEndpointThreshold`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndpointThreshold(Of ParentT)&#xA;Implements IInDefinition(Of ParentT), IWithAttach(Of ParentT), IWithGeographicLocation(Of ParentT), IWithRoutingPriority(Of ParentT), IWithRoutingWeight(Of ParentT), IWithTrafficDisabled(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithEndpointThreshold&lt;'ParentT&gt; = interface&#xA;    interface IWithAttach&lt;'ParentT&gt;&#xA;    interface IInDefinition&lt;'ParentT&gt;&#xA;    interface IWithRoutingWeight&lt;'ParentT&gt;&#xA;    interface IWithRoutingPriority&lt;'ParentT&gt;&#xA;    interface IWithGeographicLocation&lt;'ParentT&gt;&#xA;    interface IWithTrafficDisabled&lt;'ParentT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ChildResource.Definition.IInDefinition&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithGeographicLocation&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithTrafficDisabled&lt;ParentT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp der WithAttach.attach().</typeparam>
    <summary>
            Die Phase der geschachtelten Traffic Manager-Profil Endpunktdefinition taktmonitoren Geben Sie die minimale Endpunkte zum online in geschachtelten Profils, das beachtet werden als nicht heruntergestuft werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMinimumEndpointsToEnableTraffic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; WithMinimumEndpointsToEnableTraffic (int count);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; WithMinimumEndpointsToEnableTraffic(int32 count) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithEndpointThreshold`1.WithMinimumEndpointsToEnableTraffic(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMinimumEndpointsToEnableTraffic (count As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMinimumEndpointsToEnableTraffic : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithEndpointThreshold.WithMinimumEndpointsToEnableTraffic count" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="count" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="count">Die Anzahl der Endpunkte.</param>
        <summary>
            Gibt die minimale Anzahl von Endpunkten für online sein, damit die verschachtelten Profil fehlerfrei angesehen werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>