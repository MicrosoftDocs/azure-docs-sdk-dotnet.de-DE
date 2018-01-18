<Type Name="NetworkFeatures" FullName="Microsoft.Azure.Management.WebSites.Models.NetworkFeatures">
  <TypeSignature Language="C#" Value="public class NetworkFeatures : Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkFeatures extends Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkFeatures&#xA;Inherits ProxyOnlyResource" />
  <TypeSignature Language="F#" Value="type NetworkFeatures = class&#xA;    inherit ProxyOnlyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.WebSites.Models.Resource</BaseTypeName>
    <BaseTypeName FrameworkAlternate="azure-dotnet">Microsoft.Azure.Management.WebSites.Models.ProxyOnlyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="30c99-101">Umfassende Ansicht der Netzwerkfunktionen für eine app (gegenwärtig VNET-Integration und Hybridverbindungen).</span><span class="sxs-lookup"><span data-stu-id="30c99-101">Full view of network features for an app (presently VNET integration and Hybrid Connections).</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkFeatures ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="30c99-102">Initialisiert eine neue Instanz der NetworkFeatures-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30c99-102">Initializes a new instance of the NetworkFeatures class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkFeatures (string id = null, string name = null, string kind = null, string type = null, string virtualNetworkName = null, Microsoft.Azure.Management.WebSites.Models.VnetInfo virtualNetworkConnection = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt; hybridConnections = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; hybridConnectionsV2 = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string kind, string type, string virtualNetworkName, class Microsoft.Azure.Management.WebSites.Models.VnetInfo virtualNetworkConnection, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt; hybridConnections, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; hybridConnectionsV2) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.#ctor(System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.WebSites.Models.VnetInfo,System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.HybridConnection})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional kind As String = null, Optional type As String = null, Optional virtualNetworkName As String = null, Optional virtualNetworkConnection As VnetInfo = null, Optional hybridConnections As IList(Of RelayServiceConnectionEntity) = null, Optional hybridConnectionsV2 As IList(Of HybridConnection) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.NetworkFeatures : string * string * string * string * string * Microsoft.Azure.Management.WebSites.Models.VnetInfo * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.NetworkFeatures" Usage="new Microsoft.Azure.Management.WebSites.Models.NetworkFeatures (id, name, kind, type, virtualNetworkName, virtualNetworkConnection, hybridConnections, hybridConnectionsV2)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="kind" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="virtualNetworkName" Type="System.String" />
        <Parameter Name="virtualNetworkConnection" Type="Microsoft.Azure.Management.WebSites.Models.VnetInfo" />
        <Parameter Name="hybridConnections" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt;" />
        <Parameter Name="hybridConnectionsV2" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="30c99-103">Ressourcen-Id.</span><span class="sxs-lookup"><span data-stu-id="30c99-103">Resource Id.</span></span></param>
        <param name="name"><span data-ttu-id="30c99-104">Ressourcenname.</span><span class="sxs-lookup"><span data-stu-id="30c99-104">Resource Name.</span></span></param>
        <param name="kind"><span data-ttu-id="30c99-105">Die Art der Ressource.</span><span class="sxs-lookup"><span data-stu-id="30c99-105">Kind of resource.</span></span></param>
        <param name="type"><span data-ttu-id="30c99-106">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="30c99-106">Resource type.</span></span></param>
        <param name="virtualNetworkName"><span data-ttu-id="30c99-107">Der Name des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="30c99-107">The Virtual Network name.</span></span></param>
        <param name="virtualNetworkConnection"><span data-ttu-id="30c99-108">Die Zusammenfassungsansicht des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="30c99-108">The Virtual Network summary view.</span></span></param>
        <param name="hybridConnections"><span data-ttu-id="30c99-109">Die Zusammenfassungsansicht Hybridverbindungen.</span><span class="sxs-lookup"><span data-stu-id="30c99-109">The Hybrid Connections summary view.</span></span></param>
        <param name="hybridConnectionsV2"><span data-ttu-id="30c99-110">Der Hybrid Connection V2 (Service Bus) anzeigen.</span><span class="sxs-lookup"><span data-stu-id="30c99-110">The Hybrid Connection V2 (Service Bus) view.</span></span></param>
        <summary>
            <span data-ttu-id="30c99-111">Initialisiert eine neue Instanz der NetworkFeatures-Klasse.</span><span class="sxs-lookup"><span data-stu-id="30c99-111">Initializes a new instance of the NetworkFeatures class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridConnections">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt; HybridConnections { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt; HybridConnections" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.HybridConnections" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HybridConnections As IList(Of RelayServiceConnectionEntity)" />
      <MemberSignature Language="F#" Value="member this.HybridConnections : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.HybridConnections" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hybridConnections")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.RelayServiceConnectionEntity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c99-112">Ruft die Zusammenfassungsansicht der Hybridverbindungen ab.</span><span class="sxs-lookup"><span data-stu-id="30c99-112">Gets the Hybrid Connections summary view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HybridConnectionsV2">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; HybridConnectionsV2 { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt; HybridConnectionsV2" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.HybridConnectionsV2" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HybridConnectionsV2 As IList(Of HybridConnection)" />
      <MemberSignature Language="F#" Value="member this.HybridConnectionsV2 : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.HybridConnectionsV2" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.hybridConnectionsV2")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.HybridConnection&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c99-113">Ruft den Hybrid Connection V2 (Servicebus) anzeigen.</span><span class="sxs-lookup"><span data-stu-id="30c99-113">Gets the Hybrid Connection V2 (Service Bus) view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkConnection">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.VnetInfo VirtualNetworkConnection { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.VnetInfo VirtualNetworkConnection" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.VirtualNetworkConnection" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkConnection As VnetInfo" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkConnection : Microsoft.Azure.Management.WebSites.Models.VnetInfo" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.VirtualNetworkConnection" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkConnection")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.VnetInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c99-114">Ruft die Zusammenfassungsansicht des virtuellen Netzwerks ab.</span><span class="sxs-lookup"><span data-stu-id="30c99-114">Gets the Virtual Network summary view.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkName">
      <MemberSignature Language="C#" Value="public string VirtualNetworkName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VirtualNetworkName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.VirtualNetworkName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualNetworkName As String" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkName : string" Usage="Microsoft.Azure.Management.WebSites.Models.NetworkFeatures.VirtualNetworkName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="30c99-115">Ruft den Namen des virtuellen Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="30c99-115">Gets the Virtual Network name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>