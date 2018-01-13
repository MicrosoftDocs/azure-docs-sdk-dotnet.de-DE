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
            Die Phase der ein vorhandenes Anwendungsgateway request routing Regel zum Update gewähren an die Back-End-HTTP-Einstellungen-Konfiguration, um die Weiterleitungsregel mit zuzuordnen.
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
        <param name="name">Der Name einer Back-End-HTTP-Einstellungen-Konfiguration.</param>
        <summary>
            Ordnet die angegebene Back-End-HTTP-Einstellungen für Konfiguration dieser Anforderung Routingregel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>