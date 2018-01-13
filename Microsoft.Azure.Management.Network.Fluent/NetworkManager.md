<Type Name="NetworkManager" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkManager">
  <TypeSignature Language="C#" Value="public class NetworkManager : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, Microsoft.Azure.Management.Network.Fluent.INetworkManager, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkManager extends Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt; implements class Microsoft.Azure.Management.Network.Fluent.INetworkManager, class Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManagerBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkManager" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkManager&#xA;Inherits Manager(Of INetworkManagementClient)&#xA;Implements IBeta, IHasInner(Of INetworkManagementClient), IManager(Of INetworkManagementClient), INetworkManager" />
  <TypeSignature Language="F#" Value="type NetworkManager = class&#xA;    inherit Manager&lt;INetworkManagementClient&gt;&#xA;    interface INetworkManager&#xA;    interface INetworkManagerBeta&#xA;    interface IBeta&#xA;    interface IManager&lt;INetworkManagementClient&gt;&#xA;    interface IHasInner&lt;INetworkManagementClient&gt;&#xA;    interface IManagerBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Manager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;</BaseTypeName>
    <BaseTypeArguments>
      <BaseTypeArgument TypeParamName="!0">Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient</BaseTypeArgument>
    </BaseTypeArguments>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.INetworkManager</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManagementClient&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="1cdac-101">Einstiegspunkt für einen Azure-Netzwerk-Management.</span><span class="sxs-lookup"><span data-stu-id="1cdac-101">Entry point to Azure networking management.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IApplicationGateways ApplicationGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.ApplicationGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationGateways As IApplicationGateways" />
      <MemberSignature Language="F#" Value="member this.ApplicationGateways : Microsoft.Azure.Management.Network.Fluent.IApplicationGateways" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.ApplicationGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.ApplicationGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IApplicationGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-102">Einstiegspunkt für einen Gateway-anwendungsverwaltung.</span><span class="sxs-lookup"><span data-stu-id="1cdac-102">Entry point to application gateway management.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1cdac-103">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.)</span><span class="sxs-lookup"><span data-stu-id="1cdac-103">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Fluent.INetworkManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Fluent.INetworkManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials credentials, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Authenticate (credentials As AzureCredentials, subscriptionId As String) As INetworkManager" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials * string -&gt; Microsoft.Azure.Management.Network.Fluent.INetworkManager" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.Authenticate (credentials, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Authentication.AzureCredentials" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="credentials"><span data-ttu-id="1cdac-104">die zu verwendenden Anmeldeinformationen</span><span class="sxs-lookup"><span data-stu-id="1cdac-104">the credentials to use</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="1cdac-105">die Abonnement-UUID</span><span class="sxs-lookup"><span data-stu-id="1cdac-105">the subscription UUID</span></span></param>
        <summary>
            <span data-ttu-id="1cdac-106">Erstellt eine Instanz des NetworkManager, die Speicher Ressource Management-API-Einstiegspunkte verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="1cdac-106">Creates an instance of NetworkManager that exposes storage resource management API entry points.</span></span>
            </summary>
        <returns><span data-ttu-id="1cdac-107">die NetworkManager</span><span class="sxs-lookup"><span data-stu-id="1cdac-107">the NetworkManager</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authenticate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Fluent.INetworkManager Authenticate (Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Fluent.INetworkManager Authenticate(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient restClient, string subscriptionId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManager.Authenticate(Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient,System.String)" />
      <MemberSignature Language="F#" Value="static member Authenticate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient * string -&gt; Microsoft.Azure.Management.Network.Fluent.INetworkManager" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.Authenticate (restClient, subscriptionId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.RestClient" />
        <Parameter Name="subscriptionId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="restClient"><span data-ttu-id="1cdac-108">die RestClient für API-Aufrufe verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1cdac-108">the RestClient to be used for API calls.</span></span></param>
        <param name="subscriptionId"><span data-ttu-id="1cdac-109">die Abonnement-UUID</span><span class="sxs-lookup"><span data-stu-id="1cdac-109">the subscription UUID</span></span></param>
        <summary>
            <span data-ttu-id="1cdac-110">Erstellt eine Instanz des NetworkManager, die Speicher Ressource Management-API-Einstiegspunkte verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="1cdac-110">Creates an instance of NetworkManager that exposes storage resource management API entry points.</span></span>
            </summary>
        <returns><span data-ttu-id="1cdac-111">die NetworkManager</span><span class="sxs-lookup"><span data-stu-id="1cdac-111">the NetworkManager</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Configure">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Network.Fluent.NetworkManager.IConfigurable Configure ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Network.Fluent.NetworkManager/IConfigurable Configure() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkManager.Configure" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Configure () As NetworkManager.IConfigurable" />
      <MemberSignature Language="F#" Value="static member Configure : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkManager.IConfigurable" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.Configure " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkManager+IConfigurable</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-112">Abrufen einer konfigurierbaren her, die zum Erstellen von NetworkManager mit optionale Konfiguration verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="1cdac-112">Get a Configurable instance that can be used to create NetworkManager with optional configuration.</span></span>
            </summary>
        <returns><span data-ttu-id="1cdac-113">die Instanz, sodass Konfigurationen</span><span class="sxs-lookup"><span data-stu-id="1cdac-113">the instance allowing configurations</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpressRouteCircuits">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits ExpressRouteCircuits { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits ExpressRouteCircuits" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.ExpressRouteCircuits" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpressRouteCircuits As IExpressRouteCircuits" />
      <MemberSignature Language="F#" Value="member this.ExpressRouteCircuits : Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.ExpressRouteCircuits" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta.ExpressRouteCircuits</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IExpressRouteCircuits</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancers LoadBalancers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.LoadBalancers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LoadBalancers As ILoadBalancers" />
      <MemberSignature Language="F#" Value="member this.LoadBalancers : Microsoft.Azure.Management.Network.Fluent.ILoadBalancers" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.LoadBalancers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.LoadBalancers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-114">Gibt Einstiegspunkt zur Verwaltung des Lastenausgleichsmoduls laden</span><span class="sxs-lookup"><span data-stu-id="1cdac-114">returns entry point to load balancer management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="1cdac-115">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.)</span><span class="sxs-lookup"><span data-stu-id="1cdac-115">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.)</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways LocalNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways LocalNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.LocalNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalNetworkGateways As ILocalNetworkGateways" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkGateways : Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.LocalNetworkGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta.LocalNetworkGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILocalNetworkGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaces As INetworkInterfaces" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkInterfaces</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkInterfaces</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-116">Einstiegspunkt für einen netzwerkverwaltung-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="1cdac-116">Entry point to network interface management.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Networks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworks Networks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworks Networks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.Networks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Networks As INetworks" />
      <MemberSignature Language="F#" Value="member this.Networks : Microsoft.Azure.Management.Network.Fluent.INetworks" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.Networks" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.Networks</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-117">Einstiegspunkt zu des virtuellen Netzwerks zurückkehren</span><span class="sxs-lookup"><span data-stu-id="1cdac-117">return entry point to virtual network management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkSecurityGroups">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups NetworkSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkSecurityGroups As INetworkSecurityGroups" />
      <MemberSignature Language="F#" Value="member this.NetworkSecurityGroups : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkSecurityGroups" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.NetworkSecurityGroups</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroups</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-118">Einstiegspunkt zur Verwaltung von Sicherheitsgruppen Netzwerk zurückzukehren</span><span class="sxs-lookup"><span data-stu-id="1cdac-118">return entry point to network security group management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkWatchers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetworkWatchers NetworkWatchers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.INetworkWatchers NetworkWatchers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkWatchers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkWatchers As INetworkWatchers" />
      <MemberSignature Language="F#" Value="member this.NetworkWatchers : Microsoft.Azure.Management.Network.Fluent.INetworkWatchers" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.NetworkWatchers" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta.NetworkWatchers</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetworkWatchers</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddresses">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses PublicIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.PublicIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicIPAddresses As IPublicIPAddresses" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddresses : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.PublicIPAddresses" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.PublicIPAddresses</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IPublicIPAddresses</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-119">Kehren Sie zur öffentlichen IP-Adressverwaltung Einstiegspunkt zurück</span><span class="sxs-lookup"><span data-stu-id="1cdac-119">return entry point to public IP address management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTables">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IRouteTables RouteTables { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IRouteTables RouteTables" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.RouteTables" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RouteTables As IRouteTables" />
      <MemberSignature Language="F#" Value="member this.RouteTables : Microsoft.Azure.Management.Network.Fluent.IRouteTables" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.RouteTables" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManager.RouteTables</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IRouteTables</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1cdac-120">Zurückgeben der Einstiegspunkt zur Tabelle Management weiterleiten</span><span class="sxs-lookup"><span data-stu-id="1cdac-120">return entry point to route table management</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkGateways">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways VirtualNetworkGateways { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways VirtualNetworkGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.NetworkManager.VirtualNetworkGateways" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkGateways As IVirtualNetworkGateways" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkGateways : Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways" Usage="Microsoft.Azure.Management.Network.Fluent.NetworkManager.VirtualNetworkGateways" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Management.Network.Fluent.INetworkManagerBeta.VirtualNetworkGateways</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualNetworkGateways</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>