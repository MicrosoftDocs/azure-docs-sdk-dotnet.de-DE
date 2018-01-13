<Type Name="IWithSourceTrafficRegion&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegion&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSourceTrafficRegion&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceTrafficRegion`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegion`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceTrafficRegion(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSourceTrafficRegion&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp der WithAttach.attach().</typeparam>
    <summary>
            Die Phase der Traffic Manager Endpunktdefinition ermöglicht, den Speicherort des externen Endpunkts an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromRegion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; FromRegion (Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; FromRegion(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region region) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithSourceTrafficRegion`1.FromRegion(Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region)" />
      <MemberSignature Language="F#" Value="abstract member FromRegion : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithSourceTrafficRegion.FromRegion region" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="region" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" />
      </Parameters>
      <Docs>
        <param name="region">Der Speicherort.</param>
        <summary>
            Gibt den Speicherort des Endpunkts, der verwendet wird, wenn das übergeordnete Profil Leistung Routingmethode TrafficRoutingMethod.PERFORMANCE konfiguriert ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>