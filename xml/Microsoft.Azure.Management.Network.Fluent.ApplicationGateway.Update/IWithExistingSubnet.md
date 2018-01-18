<Type Name="IWithExistingSubnet" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet">
  <TypeSignature Language="C#" Value="public interface IWithExistingSubnet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithExistingSubnet implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet`1&lt;class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithExistingSubnet&#xA;Implements IWithSubnet(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IWithExistingSubnet = interface&#xA;    interface IWithSubnet&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.HasSubnet.Update.IWithSubnet&lt;Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4e6f5-101">Die Phase der eine Anwendung Gateway Update festlegen, dass das Subnetz angeben wird das app-Gateway seine private IP-Adresse aus abrufen.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-101">The stage of an application gateway update allowing to specify the subnet the app gateway is getting its private IP address from.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.ISubnet subnet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.ISubnet subnet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.ISubnet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (subnet As ISubnet) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.ISubnet -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet subnet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Fluent.ISubnet" />
      </Parameters>
      <Docs>
        <param name="subnet"><span data-ttu-id="4e6f5-102">Einem vorhandenen Subnetz.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-102">An existing subnet.</span></span></param>
        <summary>
            <span data-ttu-id="4e6f5-103">Gibt an, dass das Subnetz das Anwendungsgateway ruft seine private IP-Adresse aus ab.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-103">Specifies the subnet the application gateway gets its private IP address from.</span></span>
            <span data-ttu-id="4e6f5-104">Dadurch wird eine neue IP-Konfiguration erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-104">This will create a new IP configuration, if it does not already exist.</span></span>
            <span data-ttu-id="4e6f5-105">Private (intern) Front-Ends, wird wenn alle aktiviert haben, konfiguriert werden ebenfalls dieses Subnetz verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-105">Private (internal) frontends, if any have been enabled, will be configured to use this subnet as well.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4e6f5-106">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-106">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet (Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate WithExistingSubnet(class Microsoft.Azure.Management.Network.Fluent.INetwork network, string subnetName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IWithExistingSubnet.WithExistingSubnet(Microsoft.Azure.Management.Network.Fluent.INetwork,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSubnet (network As INetwork, subnetName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSubnet : Microsoft.Azure.Management.Network.Fluent.INetwork * string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate" Usage="iWithExistingSubnet.WithExistingSubnet (network, subnetName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
        <Parameter Name="subnetName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="network"><span data-ttu-id="4e6f5-107">Das virtuelle Netzwerk-Subnetz gehört.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-107">The virtual network the subnet is part of.</span></span></param>
        <param name="subnetName"><span data-ttu-id="4e6f5-108">Der Name eines Subnetzes innerhalb des ausgewählten Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-108">The name of a subnet within the selected network.</span></span></param>
        <summary>
            <span data-ttu-id="4e6f5-109">Gibt an, dass das Subnetz das Anwendungsgateway ruft seine private IP-Adresse aus ab.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-109">Specifies the subnet the application gateway gets its private IP address from.</span></span>
            <span data-ttu-id="4e6f5-110">Dadurch wird eine neue IP-Konfiguration erstellt, wenn sie nicht bereits vorhanden ist.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-110">This will create a new IP configuration, if it does not already exist.</span></span>
            <span data-ttu-id="4e6f5-111">Private (intern) Front-Ends, wird wenn alle aktiviert haben, konfiguriert werden ebenfalls dieses Subnetz verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-111">Private (internal) frontends, if any have been enabled, will be configured to use this subnet as well.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4e6f5-112">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="4e6f5-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>