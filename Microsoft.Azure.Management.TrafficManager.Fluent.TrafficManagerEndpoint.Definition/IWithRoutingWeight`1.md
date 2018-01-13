<Type Name="IWithRoutingWeight&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingWeight&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingWeight`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingWeight(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRoutingWeight&lt;'ParentT&gt; = interface" />
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
            Die Phase der Traffic Manager Endpunktdefinition ermöglicht die Gewichtung Endpunkt angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingWeight">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; WithRoutingWeight (int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; WithRoutingWeight(int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingWeight`1.WithRoutingWeight(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingWeight (weight As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingWeight : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingWeight.WithRoutingWeight weight" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="weight">Die Endpunkt-Gewichtung.</param>
        <summary>
            Gibt die Gewichtung für den Endpunkt, der verwendet wird, wenn das übergeordnete-Profil mit gewichteten Routingmethode TrafficRoutingMethod.WEIGHTED konfiguriert ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>