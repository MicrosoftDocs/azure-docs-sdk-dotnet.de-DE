<Type Name="IWithBackendHttpConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfiguration" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a50b3-101">Die Phase der ein vorhandenes Anwendungsgateway request routing Regel zum Update gewähren an die Back-End-HTTP-Einstellungen-Konfiguration, um die Weiterleitungsregel mit zuzuordnen.</span><span class="sxs-lookup"><span data-stu-id="a50b3-101">The stage of an application gateway request routing rule update allowing to specify the backend HTTP settings configuration to associate the routing rule with.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IWithBackendHttpConfiguration.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
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
        <param name="name"><span data-ttu-id="a50b3-102">Der Name einer Back-End-HTTP-Einstellungen-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="a50b3-102">The name of a backend HTTP settings configuration.</span></span></param>
        <summary>
            <span data-ttu-id="a50b3-103">Ordnet die angegebene Back-End-HTTP-Einstellungen für Konfiguration dieser Anforderung Routingregel.</span><span class="sxs-lookup"><span data-stu-id="a50b3-103">Associates the specified backend HTTP settings configuration with this request routing rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a50b3-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="a50b3-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>