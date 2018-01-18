<Type Name="IWithNumberOfProbes" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithNumberOfProbes">
  <TypeSignature Language="C#" Value="public interface IWithNumberOfProbes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNumberOfProbes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithNumberOfProbes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNumberOfProbes" />
  <TypeSignature Language="F#" Value="type IWithNumberOfProbes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1cf56-101">Die Phase der HTTP-Test Update ermöglichen so ändern Sie die Anzahl der fehlgeschlagenen Tests vor dem Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="1cf56-101">The stage of the HTTP probe update allowing to modify the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNumberOfProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate WithNumberOfProbes (int probes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate WithNumberOfProbes(int32 probes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IWithNumberOfProbes.WithNumberOfProbes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNumberOfProbes (probes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNumberOfProbes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate" Usage="iWithNumberOfProbes.WithNumberOfProbes probes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerHttpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="probes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="probes"><span data-ttu-id="1cf56-102">Die Anzahl der Tests.</span><span class="sxs-lookup"><span data-stu-id="1cf56-102">Number of probes.</span></span></param>
        <summary>
            <span data-ttu-id="1cf56-103">Gibt die Anzahl der fehlgeschlagenen Tests an, bevor Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="1cf56-103">Specifies the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1cf56-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="1cf56-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>