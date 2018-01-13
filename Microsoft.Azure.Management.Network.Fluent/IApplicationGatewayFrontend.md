<Type Name="IApplicationGatewayFrontend" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayFrontend : Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayFrontend implements class Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress, class Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayFrontend&#xA;Implements IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayFrontendIPConfigurationInner), IHasParent(Of IApplicationGateway), IHasPrivateIPAddress, IHasPublicIPAddress, IHasSubnet" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayFrontend = interface&#xA;    interface IHasInner&lt;ApplicationGatewayFrontendIPConfigurationInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasPrivateIPAddress&#xA;    interface IHasSubnet&#xA;    interface IHasPublicIPAddress" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPrivateIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasPublicIPAddress</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayFrontendIPConfigurationInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasSubnet</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung eines einer Anwendung Gateway Front-Ends.
            </summary>
    <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="GetSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ISubnet GetSubnet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.GetSubnet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSubnet () As ISubnet" />
      <MemberSignature Language="F#" Value="abstract member GetSubnet : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ISubnet" Usage="iApplicationGatewayFrontend.GetSubnet " />
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
        <return>Das zugeordnete Subnetz.</return>
      </Docs>
    </Member>
    <Member MemberName="IsPrivate">
      <MemberSignature Language="C#" Value="public bool IsPrivate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPrivate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPrivate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPrivate As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPrivate : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPrivate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true" ist, dass die Front-End-Zugriff über eine private IP-Adresse ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPublic">
      <MemberSignature Language="C#" Value="public bool IsPublic { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPublic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPublic" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPublic As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPublic : bool" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayFrontend.IsPublic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn der Front-End-Zugriff über eine öffentliche IP-Adresse, die andernfalls "false" ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>