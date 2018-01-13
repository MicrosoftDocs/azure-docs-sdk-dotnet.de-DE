<Type Name="IWithNumberOfProbes&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithNumberOfProbes&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNumberOfProbes&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNumberOfProbes`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithNumberOfProbes`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNumberOfProbes(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNumberOfProbes&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der übergeordnete Ressourcentyp.</typeparam>
    <summary>
            Die Phase des TCP-Prüfpunkt Definition ermöglicht die Anzahl der fehlgeschlagenen Tests angeben, bevor Fehler bestimmt wird.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNumberOfProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithNumberOfProbes (int probes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithNumberOfProbes(int32 probes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithNumberOfProbes`1.WithNumberOfProbes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNumberOfProbes (probes As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNumberOfProbes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNumberOfProbes.WithNumberOfProbes probes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="probes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="probes">Die Anzahl der Tests.</param>
        <summary>
            Gibt die Anzahl der fehlgeschlagenen Tests an, bevor Fehler bestimmt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>