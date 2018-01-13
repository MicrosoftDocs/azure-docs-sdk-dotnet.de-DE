<Type Name="IWithFrontendPort&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithFrontendPort&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFrontendPort`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFrontendPort(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithFrontendPort&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="88166-101">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="88166-101">The stage of the application gateway definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="88166-102">Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition, die zum Erstellen eines Listeners zuordnen und Front-End für eine bestimmte Portnummer und Protokoll ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="88166-102">The stage of an application gateway request routing rule definition allowing to create an associate listener and frontend for a specific port number and protocol.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromFrontendHttpPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;ParentT&gt; FromFrontendHttpPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect`1&lt;!ParentT&gt; FromFrontendHttpPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1.FromFrontendHttpPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromFrontendHttpPort (portNumber As Integer) As IWithBackendHttpConfigOrRedirect(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromFrontendHttpPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;'ParentT&gt;" Usage="iWithFrontendPort.FromFrontendHttpPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendHttpConfigOrRedirect&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FromFrontendHttpsPort">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;ParentT&gt; FromFrontendHttpsPort (int portNumber);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate`1&lt;!ParentT&gt; FromFrontendHttpsPort(int32 portNumber) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithFrontendPort`1.FromFrontendHttpsPort(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromFrontendHttpsPort (portNumber As Integer) As IWithSslCertificate(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromFrontendHttpsPort : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;'ParentT&gt;" Usage="iWithFrontendPort.FromFrontendHttpsPort portNumber" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithSslCertificate&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="portNumber" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="portNumber"><span data-ttu-id="88166-103">Die Nummer des Ports, zu überwachen.</span><span class="sxs-lookup"><span data-stu-id="88166-103">The port number to listen to.</span></span></param>
        <summary>
            <span data-ttu-id="88166-104">Ordnet einen neuen Listener für die angegebene Portnummer und das HTTPS-Protokoll mit dieser Regel.</span><span class="sxs-lookup"><span data-stu-id="88166-104">Associates a new listener for the specified port number and the HTTPS protocol with this rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="88166-105">Die nächste Phase der Definition oder Null, wenn die angegebene Portnummer bereits für ein anderes Protokoll verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="88166-105">The next stage of the definition, or null if the specified port number is already used for a different protocol.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>