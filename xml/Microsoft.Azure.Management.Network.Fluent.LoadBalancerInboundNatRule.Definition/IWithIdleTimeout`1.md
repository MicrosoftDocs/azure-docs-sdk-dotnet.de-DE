<Type Name="IWithIdleTimeout&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeout&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeout`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeout(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeout&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="52c72-101">Der übergeordnete Load Balancer-Typ.</span><span class="sxs-lookup"><span data-stu-id="52c72-101">The parent load balancer type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="52c72-102">Die Phase einer eingehenden NAT-Regeldefinition ermöglicht das Timeout der Verbindung im Leerlauf für diese eingehende NAT-Regel an.</span><span class="sxs-lookup"><span data-stu-id="52c72-102">The stage of an inbound NAT rule definition allowing to specify the idle connection timeout for this inbound NAT rule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;ParentT&gt; WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach`1&lt;!ParentT&gt; WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithIdleTimeout`1.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithIdleTimeout.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancerInboundNatRule.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes"><span data-ttu-id="52c72-103">Eine Anzahl von Minuten.</span><span class="sxs-lookup"><span data-stu-id="52c72-103">A number of minutes.</span></span></param>
        <summary>
            <span data-ttu-id="52c72-104">Gibt das Timeout der Verbindung im Leerlauf in Minuten an.</span><span class="sxs-lookup"><span data-stu-id="52c72-104">Specifies the idle connection timeout in minutes.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="52c72-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="52c72-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>