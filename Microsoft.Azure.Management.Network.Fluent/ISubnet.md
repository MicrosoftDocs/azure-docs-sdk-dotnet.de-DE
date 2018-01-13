<Type Name="ISubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ISubnet">
  <TypeSignature Language="C#" Value="public interface ISubnet : Microsoft.Azure.Management.Network.Fluent.ISubnetBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISubnet implements class Microsoft.Azure.Management.Network.Fluent.ISubnetBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ISubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISubnet&#xA;Implements IBeta, IChildResource(Of INetwork), IHasInner(Of SubnetInner), IHasParent(Of INetwork), ISubnetBeta" />
  <TypeSignature Language="F#" Value="type ISubnet = interface&#xA;    interface IHasInner&lt;SubnetInner&gt;&#xA;    interface IChildResource&lt;INetwork&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;INetwork&gt;&#xA;    interface ISubnetBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.ISubnetBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung eines Subnetzes eines virtuellen Netzwerks.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public string AddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ISubnet.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : string" Usage="Microsoft.Azure.Management.Network.Fluent.ISubnet.AddressPrefix" />
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
            Ruft das Adresspräfix Speicherplatz in CIDR-Notation, die dieses Subnetz zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkInterfaceIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt; GetNetworkInterfaceIPConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.ISet`1&lt;class Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt; GetNetworkInterfaceIPConfigurations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ISubnet.GetNetworkInterfaceIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkInterfaceIPConfigurations () As ISet(Of INicIPConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkInterfaceIPConfigurations : unit -&gt; System.Collections.Generic.ISet&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt;" Usage="iSubnet.GetNetworkInterfaceIPConfigurations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use  Subnet.ListNetworkInterfaceIPConfigurations() instead.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Netzwerk-Schnittstelle IP-Konfigurationen, die dieses Subnetz Hinweis zugeordnet sind, dass dieser Aufruf führen kann, in mehreren Aufrufen an Azure abzurufenden alle referenzierten Schnittstellen jedes Mal, wenn er aufgerufen wird.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup GetNetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup GetNetworkSecurityGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ISubnet.GetNetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkSecurityGroup () As INetworkSecurityGroup" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkSecurityGroup : unit -&gt; Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" Usage="iSubnet.GetNetworkSecurityGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Die Netzwerksicherheitsgruppe, die dieses Subnetz zugeordnet wird, wenn alle Beachten Sie, dass diese Methode in einem Aufruf in jeder Azure führt es Zeit wird aufgerufen.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteTable GetRouteTable ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IRouteTable GetRouteTable() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ISubnet.GetRouteTable" />
      <MemberSignature Language="VB.NET" Value="Public Function GetRouteTable () As IRouteTable" />
      <MemberSignature Language="F#" Value="abstract member GetRouteTable : unit -&gt; Microsoft.Azure.Management.Network.Fluent.IRouteTable" Usage="iSubnet.GetRouteTable " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteTable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Die Routingtabelle dieses Subnetz zugeordnet wird, wenn alle Beachten Sie, dass diese Methode in einem Aufruf in jeder Azure führt es Zeit wird aufgerufen.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfaceIPConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt; ListNetworkInterfaceIPConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyCollection`1&lt;class Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt; ListNetworkInterfaceIPConfigurations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ISubnet.ListNetworkInterfaceIPConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfaceIPConfigurations () As IReadOnlyCollection(Of INicIPConfiguration)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfaceIPConfigurations : unit -&gt; System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt;" Usage="iSubnet.ListNetworkInterfaceIPConfigurations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyCollection&lt;Microsoft.Azure.Management.Network.Fluent.INicIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIPConfigurationCount">
      <MemberSignature Language="C#" Value="public int NetworkInterfaceIPConfigurationCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NetworkInterfaceIPConfigurationCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ISubnet.NetworkInterfaceIPConfigurationCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIPConfigurationCount As Integer" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIPConfigurationCount : int" Usage="Microsoft.Azure.Management.Network.Fluent.ISubnet.NetworkInterfaceIPConfigurationCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Netzwerk-Schnittstelle IP-Konfigurationen dieses Subnetz zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroupId">
      <MemberSignature Language="C#" Value="public string NetworkSecurityGroupId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NetworkSecurityGroupId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ISubnet.NetworkSecurityGroupId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroupId As String" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroupId : string" Usage="Microsoft.Azure.Management.Network.Fluent.ISubnet.NetworkSecurityGroupId" />
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
            Ruft die Ressourcen-ID für dieses Subnetz zugeordneten Netzwerksicherheitsgruppe ab, sofern vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTableId">
      <MemberSignature Language="C#" Value="public string RouteTableId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteTableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.ISubnet.RouteTableId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteTableId As String" />
      <MemberSignature Language="F#" Value="member this.RouteTableId : string" Usage="Microsoft.Azure.Management.Network.Fluent.ISubnet.RouteTableId" />
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
            Ruft die Ressourcen-ID der diesem Subnetz zugeordnet Routentabelle ab, sofern vorhanden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>