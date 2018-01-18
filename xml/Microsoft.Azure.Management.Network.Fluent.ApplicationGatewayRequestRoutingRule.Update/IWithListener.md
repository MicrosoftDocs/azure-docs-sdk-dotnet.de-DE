<Type Name="IWithListener" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener">
  <TypeSignature Language="C#" Value="public interface IWithListener" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithListener" />
  <TypeSignature Language="F#" Value="type IWithListener = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="da88c-101">Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regel Update taktmonitoren Geben Sie einen vorhandenen Listener um die Weiterleitungsregel mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="da88c-101">The stage of an application gateway request routing rule update allowing to specify an existing listener to associate the routing rule with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromListener">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate FromListener(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithListener.FromListener(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromListener (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member FromListener : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithListener.FromListener name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="da88c-102">Der Name eines Listeners zu verweisen.</span><span class="sxs-lookup"><span data-stu-id="da88c-102">The name of a listener to reference.</span></span></param>
        <summary>
            <span data-ttu-id="da88c-103">Ordnet die Weiterleitungsregel Anfrage einen vorhandenen Front-End-Listener.</span><span class="sxs-lookup"><span data-stu-id="da88c-103">Associates the request routing rule with an existing frontend listener.</span></span>
            <span data-ttu-id="da88c-104">Beachten Sie, ein bestimmter Listener von nicht mehr als eine Anforderung Routingregel zu einem Zeitpunkt verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="da88c-104">Also, note that a given listener can be used by no more than one request routing rule at a time.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="da88c-105">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="da88c-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>