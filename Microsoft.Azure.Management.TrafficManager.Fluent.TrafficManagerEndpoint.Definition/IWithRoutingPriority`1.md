<Type Name="IWithRoutingPriority&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRoutingPriority&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRoutingPriority`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRoutingPriority(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRoutingPriority&lt;'ParentT&gt; = interface" />
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
            Die Phase der Traffic Manager Endpunktdefinition ermöglicht die endpunktpriorität angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRoutingPriority">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt; WithRoutingPriority (int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach`1&lt;!ParentT&gt; WithRoutingPriority(int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithRoutingPriority`1.WithRoutingPriority(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRoutingPriority (priority As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRoutingPriority : int -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRoutingPriority.WithRoutingPriority priority" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerEndpoint.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="priority">Die endpunktpriorität.</param>
        <summary>
            Gibt die Priorität für den Endpunkt, der verwendet wird, wenn das übergeordnete-Profil mit Priorität Routingmethode TrafficRoutingMethod.PRIORITY konfiguriert ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>