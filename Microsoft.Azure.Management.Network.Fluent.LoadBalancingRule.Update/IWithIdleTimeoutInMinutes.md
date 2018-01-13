<Type Name="IWithIdleTimeoutInMinutes" FullName="Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes">
  <TypeSignature Language="C#" Value="public interface IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIdleTimeoutInMinutes" />
  <TypeSignature Language="F#" Value="type IWithIdleTimeoutInMinutes = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="42ce4-101">Die Phase des Lastenausgleichs Regel Update festlegen, dass das Verbindungstimeout für Verbindungen im Leerlauf zu ändern.</span><span class="sxs-lookup"><span data-stu-id="42ce4-101">The stage of a load balancing rule update allowing to modify the connection timeout for idle connections.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate WithIdleTimeoutInMinutes (int minutes);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate WithIdleTimeoutInMinutes(int32 minutes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IWithIdleTimeoutInMinutes.WithIdleTimeoutInMinutes(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIdleTimeoutInMinutes (minutes As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIdleTimeoutInMinutes : int -&gt; Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate" Usage="iWithIdleTimeoutInMinutes.WithIdleTimeoutInMinutes minutes" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.LoadBalancingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="minutes" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="minutes"><span data-ttu-id="42ce4-102">Die gewünschte Anzahl von Minuten.</span><span class="sxs-lookup"><span data-stu-id="42ce4-102">The desired number of minutes.</span></span></param>
        <summary>
            <span data-ttu-id="42ce4-103">Gibt die Anzahl von Minuten, bevor eine Verbindung im Leerlauf geschlossen wird.</span><span class="sxs-lookup"><span data-stu-id="42ce4-103">Specifies the number of minutes before an idle connection is closed.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="42ce4-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="42ce4-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>