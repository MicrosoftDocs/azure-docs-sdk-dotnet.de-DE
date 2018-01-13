<Type Name="IWithBackendHttpConfiguration&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendHttpConfiguration&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendHttpConfiguration`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendHttpConfiguration(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackendHttpConfiguration&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition ermöglicht, die an die Back-End-HTTP-Einstellungen-Konfiguration, um die Weiterleitungsregel mit zuzuordnen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendHttpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpConfiguration (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpConfiguration(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1.ToBackendHttpConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpConfiguration (name As String) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpConfiguration : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpConfiguration name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name einer Back-End-HTTP-Einstellungen-Konfiguration.</param>
        <summary>
            Ordnet die angegebene Back-End-HTTP-Einstellungen für Konfiguration dieser Anforderung Routingregel.
            Wenn die Back-End-Konfiguration noch nicht vorhanden ist, muss er in den optionalen Teil der Gateway Anwendungsdefinition mit defineBackendHttpConfiguration(...) definiert werden. Die Weiterleitungsregel Anfrage verweist er nur anhand des Namens auf.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt; ToBackendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress`1&lt;!ParentT&gt; ToBackendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendHttpConfiguration`1.ToBackendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendHttpPort (portNumber As Integer) As IWithBackendOrAddress(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;'ParentT&gt;" Usage="iWithBackendHttpConfiguration.ToBackendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.Definition.IWithBackendOrAddress&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">Die Nummer des Ports für eine neue Konfiguration der Back-End-HTTP-Einstellungen.</param>
        <summary>
            Erstellt eine Back-End-HTTP-Einstellungen-Konfiguration für die angegebene Back-End-Port und das HTTP-Protokoll, und ordnet diese Anforderung Routingregel.
            Ein automatisch generierter Name wird für den neu erstellten Konfiguration verwendet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>