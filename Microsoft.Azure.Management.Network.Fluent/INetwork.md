<Type Name="INetwork" FullName="Microsoft.Azure.Management.Network.Fluent.INetwork">
  <TypeSignature Language="C#" Value="public interface INetwork : Microsoft.Azure.Management.Network.Fluent.INetworkBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetwork implements class Microsoft.Azure.Management.Network.Fluent.INetworkBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetwork&#xA;Implements IBeta, IGroupableResource(Of INetworkManager, VirtualNetworkInner), IHasInner(Of VirtualNetworkInner), IHasManager(Of INetworkManager), INetworkBeta, IRefreshable(Of INetwork), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type INetwork = interface&#xA;    interface IGroupableResource&lt;INetworkManager, VirtualNetworkInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;INetworkManager&gt;&#xA;    interface IHasInner&lt;VirtualNetworkInner&gt;&#xA;    interface IRefreshable&lt;INetwork&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface INetworkBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.INetworkBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager,Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Der Einstiegspunkt für Virtuellenetzwerk in Azure-Verwaltungs-API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddressSpaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; AddressSpaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; AddressSpaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetwork.AddressSpaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AddressSpaces As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AddressSpaces : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetwork.AddressSpaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Adressräume, die diesem virtuellen Netzwerk, in der CIDR-Notation zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsServerIPs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; DnsServerIPs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; DnsServerIPs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetwork.DnsServerIPs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsServerIPs As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DnsServerIPs : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetwork.DnsServerIPs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der DNS-Server IP-Adressen, die diesem virtuellen Netzwerk zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ISubnet&gt; Subnets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ISubnet&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetwork.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Subnets As IReadOnlyDictionary(Of String, ISubnet)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ISubnet&gt;" Usage="Microsoft.Azure.Management.Network.Fluent.INetwork.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ISubnet&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Subnetze des virtuellen Netzwerks als Karte indiziert Subnetz namentlich Beachten Sie, dass wenn ein virtuelles Netzwerk mit keine explizit definierten Subnetze erstellt wird, eine standardsubnetz automatisch mit dem Namen "subnet1" erstellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>