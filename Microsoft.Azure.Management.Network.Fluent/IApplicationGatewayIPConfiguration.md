<Type Name="IApplicationGatewayIPConfiguration" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayIPConfiguration : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayIPConfiguration implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayIPConfiguration&#xA;Implements IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayIPConfigurationInner), IHasParent(Of IApplicationGateway)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayIPConfiguration = interface&#xA;    interface IHasInner&lt;ApplicationGatewayIPConfigurationInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayIPConfigurationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung einer Anwendung Gateway-IP-Konfiguration.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.GetSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubnet () As ISubnet" />
      <MemberSignature Language="F#" Value="abstract member GetSubnet : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ISubnet" Usage="iApplicationGatewayIPConfiguration.GetSubnet " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ISubnet</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Das Subnetz, in dem das Anwendungsgateway Hinweis befindet, führt dies in einen separaten Aufruf von Azure.
            </return>
      </Docs>
    </Member>
    <Member MemberName="NetworkId">
      <MemberSignature Language="C#" Value="public string NetworkId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetworkId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.NetworkId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkId As String" />
      <MemberSignature Language="F#" Value="member this.NetworkId : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.NetworkId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ressourcen-ID des virtuellen Netzwerks, in dem das Anwendungsgateway befindet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetName">
      <MemberSignature Language="C#" Value="public string SubnetName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.SubnetName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubnetName As String" />
      <MemberSignature Language="F#" Value="member this.SubnetName : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayIPConfiguration.SubnetName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Subnetzes, in dem das Anwendungsgateway befindet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>