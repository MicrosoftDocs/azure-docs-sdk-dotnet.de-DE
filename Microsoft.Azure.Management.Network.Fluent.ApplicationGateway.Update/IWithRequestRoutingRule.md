<Type Name="IWithRequestRoutingRule" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule">
  <TypeSignature Language="C#" Value="public interface IWithRequestRoutingRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRequestRoutingRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRequestRoutingRule" />
  <TypeSignature Language="F#" Value="type IWithRequestRoutingRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase von einer Anwendung Gateway Update ermöglicht Routingregeln Anforderung ändern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt; DefineRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.DefineRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineRequestRoutingRule (name As String) As IBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" Usage="iWithRequestRoutingRule.DefineRequestRoutingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IBlank&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Ein eindeutiger Name für die Weiterleitungsregel Anfrage.</param>
        <summary>
            Beginn der Definition einer Anforderung Routingregel für dieses Anwendungsgateway an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Stufe der die Weiterleitungsregel Anfrage.</return>
      </Docs>
    </Member>
    <Member MemberName="UpdateRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate UpdateRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate UpdateRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.UpdateRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateRequestRoutingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member UpdateRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Update.IUpdate" Usage="iWithRequestRoutingRule.UpdateRequestRoutingRule name" />
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
        <param name="name">Der Name eines vorhandenen anfordern Routingregel.</param>
        <summary>
            Startet das Update von einer Anforderung Routingregel an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die erste Phase einer Anforderung routing Regel aktualisieren oder Null, wenn die angeforderte Regel nicht vorhanden ist.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutRequestRoutingRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutRequestRoutingRule (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithoutRequestRoutingRule(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithRequestRoutingRule.WithoutRequestRoutingRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutRequestRoutingRule (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutRequestRoutingRule : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithRequestRoutingRule.WithoutRequestRoutingRule name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der die Anforderung Routingregel zu entfernen.</param>
        <summary>
            Entfernt eine Routingregel für die Anforderung über das Anwendungsgateway.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>