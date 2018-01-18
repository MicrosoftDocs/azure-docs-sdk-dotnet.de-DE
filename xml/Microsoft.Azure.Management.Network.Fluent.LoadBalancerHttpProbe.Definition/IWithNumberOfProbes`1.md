<Type Name="IWithNumberOfProbes&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithNumberOfProbes&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNumberOfProbes&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNumberOfProbes`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithNumberOfProbes`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="17ada-101">Der übergeordnete Typ.</span><span class="sxs-lookup"><span data-stu-id="17ada-101">The parent type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="17ada-102">Die Phase der HTTP-Test Definition zu ermöglichen, geben die Anzahl der nicht erfolgreichen Tests aus, damit die Fehler ermittelt wird.</span><span class="sxs-lookup"><span data-stu-id="17ada-102">The stage of the HTTP probe definition allowing to specify the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNumberOfProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt; WithNumberOfProbes (int probes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach`1&lt;!ParentT&gt; WithNumberOfProbes(int32 probes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithNumberOfProbes`1.WithNumberOfProbes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNumberOfProbes (probes As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNumberOfProbes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithNumberOfProbes.WithNumberOfProbes probes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="probes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="probes"><span data-ttu-id="17ada-103">Die Anzahl der Tests.</span><span class="sxs-lookup"><span data-stu-id="17ada-103">Number of probes.</span></span></param>
        <summary>
            <span data-ttu-id="17ada-104">Gibt die Anzahl der fehlgeschlagenen Tests an, bevor Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="17ada-104">Specifies the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="17ada-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="17ada-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>