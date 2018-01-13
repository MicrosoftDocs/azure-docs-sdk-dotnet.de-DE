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
    <typeparam name="ParentT"><span data-ttu-id="d7fd1-101">Der übergeordnete Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="d7fd1-101">The parent resource type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="d7fd1-102">Die Phase des TCP-Prüfpunkt Definition ermöglicht die Anzahl der fehlgeschlagenen Tests angeben, bevor Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="d7fd1-102">The stage of the TCP probe definition allowing to specify the number of unsuccessful probes before failure is determined.</span></span>
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
        <param name="probes"><span data-ttu-id="d7fd1-103">Die Anzahl der Tests.</span><span class="sxs-lookup"><span data-stu-id="d7fd1-103">Number of probes.</span></span></param>
        <summary>
            <span data-ttu-id="d7fd1-104">Gibt die Anzahl der fehlgeschlagenen Tests an, bevor Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="d7fd1-104">Specifies the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7fd1-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d7fd1-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>