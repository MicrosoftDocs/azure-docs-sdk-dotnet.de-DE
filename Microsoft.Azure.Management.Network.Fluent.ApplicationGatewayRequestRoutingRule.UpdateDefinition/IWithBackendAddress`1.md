<Type Name="IWithBackendAddress&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithBackendAddress&lt;ParentT&gt; : Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta&lt;ParentT&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithBackendAddress`1&lt;ParentT&gt; implements class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta`1&lt;!ParentT&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithBackendAddress(Of ParentT)&#xA;Implements IBeta, IWithBackendAddressBeta(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithBackendAddress&lt;'ParentT&gt; = interface&#xA;    interface IWithBackendAddressBeta&lt;'ParentT&gt;&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressBeta&lt;ParentT&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ParentT">Die Phase der Anwendungsdefinition Gateway wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Phase der ein vorhandenes Anwendungsgateway anfordern routing Regeldefinition ermöglicht dem Back-End verwendet, die für diese Anforderung Routingregel eine Adresse hinzu.
            Ein neues Back-End wird erstellt werden, wenn keine noch mit dieser Regel zugeordnet ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ToBackendFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1.ToBackendFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendFqdn (fqdn As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">Einen vollständig qualifizierten Domänennamen ein.</param>
        <summary>
            Die Back-End-mit dieser Regel verbundenen hinzugefügt FQDN (vollständig qualifizierter Domänenname).
            Wenn keine Back-End-mit dieser Regel zugeordnet wurde, noch ein weiteres mit einem automatisch generierten Namen erstellt werden.
            Dieser Aufruf kann in einer Sequenz verwendet werden, um mehrere FQDNs hinzuzufügen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="ToBackendIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt; ToBackendIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach`1&lt;!ParentT&gt; ToBackendIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddress`1.ToBackendIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ToBackendIPAddress (ipAddress As String) As IWithBackendAddressOrAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member ToBackendIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;'ParentT&gt;" Usage="iWithBackendAddress.ToBackendIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayRequestRoutingRule.UpdateDefinition.IWithBackendAddressOrAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">Eine IP-Adresse.</param>
        <summary>
            Die mit dieser Regel verbundenen Back-End-hinzugefügt IP-Adresse.
            Wenn keine Back-End-mit dieser Regel zugeordnet wurde, noch ein weiteres mit einem automatisch generierten Namen erstellt werden.
            Dieser Aufruf kann in einer Sequenz verwendet werden, mehrere IP-Adressen hinzu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>