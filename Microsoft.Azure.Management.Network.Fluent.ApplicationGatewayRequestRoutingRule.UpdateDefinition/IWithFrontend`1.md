<Type Name="IWithFrontend&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontend&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontend`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontend(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontend&lt;'ParentT&gt; = interface" />
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
            Die Phase der ein vorhandenes Anwendungsgateway request routing an das Front-End für die Regel angewendet, sodass Regeldefinition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromPrivateFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; FromPrivateFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; FromPrivateFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1.FromPrivateFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPrivateFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPrivateFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPrivateFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Aktiviert die Regel an, das Anwendungsgateway private (intern) Front-End.
            Wenn die private Front-End-IP-Konfiguration noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt.
            Das Anwendungsgateway kein Subnetz für die private Front-End angegeben, wird eine, wenn ein bestimmtes Subnetz angegeben wird, in der Anwendung Gatewaydefinition optionalen Einstellungen, die mit withExistingSubnet(...) automatisch erstellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="FromPublicFrontend">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt; FromPublicFrontend ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1&lt;!ParentT&gt; FromPublicFrontend() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontend`1.FromPublicFrontend" />
      <MemberSignature Language="VB.NET" Value="Public Function FromPublicFrontend () As IWithFrontendPort(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromPublicFrontend : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;'ParentT&gt;" Usage="iWithFrontend.FromPublicFrontend " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Aktiviert die Regel, die für das Anwendungsgateway öffentlichen (Internetverbindung) Front-End-gelten.
            Wenn die öffentliche Front-End-IP-Konfiguration noch nicht vorhanden ist, wird er unter einem automatisch generierten Namen erstellt.
            Verfügt das Anwendungsgateway keine öffentliche IP-Adresse für die öffentliche Front-End angegeben, wird eine automatisch erstellt, es sei denn, eine bestimmte öffentliche IP-Adresse angegeben wird, in der Anwendung Gatewaydefinition optionalen Einstellungen, die mit withExistingPublicIPAddress(...) oder withNewPublicIPAddress(...).
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>