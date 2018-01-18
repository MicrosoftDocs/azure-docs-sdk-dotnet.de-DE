<Type Name="IWithNumberOfProbes" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithNumberOfProbes">
  <TypeSignature Language="C#" Value="public interface IWithNumberOfProbes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNumberOfProbes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithNumberOfProbes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNumberOfProbes" />
  <TypeSignature Language="F#" Value="type IWithNumberOfProbes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="27d98-101">Die Phase des TCP-Prüfpunkt Update festlegen, dass um die Anzahl der fehlgeschlagenen Tests zu ändern, bevor der Fehler festgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="27d98-101">The stage of the TCP probe update allowing to modify the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNumberOfProbes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate WithNumberOfProbes (int probes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate WithNumberOfProbes(int32 probes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IWithNumberOfProbes.WithNumberOfProbes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNumberOfProbes (probes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNumberOfProbes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate" Usage="iWithNumberOfProbes.WithNumberOfProbes probes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerTcpProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="probes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="probes"><span data-ttu-id="27d98-102">Die Anzahl der Tests.</span><span class="sxs-lookup"><span data-stu-id="27d98-102">Number of probes.</span></span></param>
        <summary>
            <span data-ttu-id="27d98-103">Gibt die Anzahl der fehlgeschlagenen Tests an, bevor Fehler bestimmt wird.</span><span class="sxs-lookup"><span data-stu-id="27d98-103">Specifies the number of unsuccessful probes before failure is determined.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="27d98-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="27d98-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>