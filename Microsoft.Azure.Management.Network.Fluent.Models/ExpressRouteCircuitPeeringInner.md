<Type Name="ExpressRouteCircuitPeeringInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitPeeringInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitPeeringInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitPeeringInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeeringInner = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="1dc8f-101">In einer Ressource ExpressRouteCircuit Peering.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-101">Peering in an ExpressRouteCircuit resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeeringInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-102">Initialisiert eine neue Instanz der ExpressRouteCircuitPeeringInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-102">Initializes a new instance of the ExpressRouteCircuitPeeringInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeeringInner (string id = null, string peeringType = null, string state = null, Nullable&lt;int&gt; azureASN = null, Nullable&lt;int&gt; peerASN = null, string primaryPeerAddressPrefix = null, string secondaryPeerAddressPrefix = null, string primaryAzurePort = null, string secondaryAzurePort = null, string sharedKey = null, Nullable&lt;int&gt; vlanId = null, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig = null, Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner stats = null, string provisioningState = null, string gatewayManagerEtag = null, string lastModifiedBy = null, Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilter = null, Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string peeringType, string state, valuetype System.Nullable`1&lt;int32&gt; azureASN, valuetype System.Nullable`1&lt;int32&gt; peerASN, string primaryPeerAddressPrefix, string secondaryPeerAddressPrefix, string primaryAzurePort, string secondaryAzurePort, string sharedKey, valuetype System.Nullable`1&lt;int32&gt; vlanId, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig, class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner stats, string provisioningState, string gatewayManagerEtag, string lastModifiedBy, class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner routeFilter, class Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig,Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner,Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional peeringType As String = null, Optional state As String = null, Optional azureASN As Nullable(Of Integer) = null, Optional peerASN As Nullable(Of Integer) = null, Optional primaryPeerAddressPrefix As String = null, Optional secondaryPeerAddressPrefix As String = null, Optional primaryAzurePort As String = null, Optional secondaryAzurePort As String = null, Optional sharedKey As String = null, Optional vlanId As Nullable(Of Integer) = null, Optional microsoftPeeringConfig As ExpressRouteCircuitPeeringConfig = null, Optional stats As ExpressRouteCircuitStatsInner = null, Optional provisioningState As String = null, Optional gatewayManagerEtag As String = null, Optional lastModifiedBy As String = null, Optional routeFilter As RouteFilterInner = null, Optional ipv6PeeringConfig As Ipv6ExpressRouteCircuitPeeringConfig = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner : string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig * Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner * string * string * string * Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner * Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner (id, peeringType, state, azureASN, peerASN, primaryPeerAddressPrefix, secondaryPeerAddressPrefix, primaryAzurePort, secondaryAzurePort, sharedKey, vlanId, microsoftPeeringConfig, stats, provisioningState, gatewayManagerEtag, lastModifiedBy, routeFilter, ipv6PeeringConfig, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="peeringType" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="azureASN" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="peerASN" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="primaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="secondaryPeerAddressPrefix" Type="System.String" />
        <Parameter Name="primaryAzurePort" Type="System.String" />
        <Parameter Name="secondaryAzurePort" Type="System.String" />
        <Parameter Name="sharedKey" Type="System.String" />
        <Parameter Name="vlanId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="microsoftPeeringConfig" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="stats" Type="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="gatewayManagerEtag" Type="System.String" />
        <Parameter Name="lastModifiedBy" Type="System.String" />
        <Parameter Name="routeFilter" Type="Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner" />
        <Parameter Name="ipv6PeeringConfig" Type="Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="peeringType">To be added.</param>
        <param name="state">To be added.</param>
        <param name="azureASN">To be added.</param>
        <param name="peerASN">To be added.</param>
        <param name="primaryPeerAddressPrefix">To be added.</param>
        <param name="secondaryPeerAddressPrefix">To be added.</param>
        <param name="primaryAzurePort">To be added.</param>
        <param name="secondaryAzurePort">To be added.</param>
        <param name="sharedKey">To be added.</param>
        <param name="vlanId">To be added.</param>
        <param name="microsoftPeeringConfig">To be added.</param>
        <param name="stats">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="gatewayManagerEtag">To be added.</param>
        <param name="lastModifiedBy">To be added.</param>
        <param name="routeFilter">To be added.</param>
        <param name="ipv6PeeringConfig">To be added.</param>
        <param name="name">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AzureASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AzureASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.AzureASN" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AzureASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.AzureASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.azureASN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-103">Ruft ab oder legt die Azure-ASN.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-103">Gets or sets the Azure ASN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-104">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-104">Gets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayManagerEtag">
      <MemberSignature Language="C#" Value="public string GatewayManagerEtag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayManagerEtag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.GatewayManagerEtag" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayManagerEtag As String" />
      <MemberSignature Language="F#" Value="member this.GatewayManagerEtag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.GatewayManagerEtag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayManagerEtag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-105">Ruft ab oder legt das GatewayManager Etag fest.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-105">Gets or sets the GatewayManager Etag.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6PeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Ipv6PeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6PeeringConfig As Ipv6ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.Ipv6PeeringConfig : Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Ipv6PeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipv6PeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.Ipv6ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedBy">
      <MemberSignature Language="C#" Value="public string LastModifiedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastModifiedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.LastModifiedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModifiedBy As String" />
      <MemberSignature Language="F#" Value="member this.LastModifiedBy : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.LastModifiedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModifiedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-106">Ruft ab, ob der Anbieter oder der Kunde das peering geändert.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-106">Gets whether the provider or the customer last modified the peering.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftPeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.MicrosoftPeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftPeeringConfig As ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.MicrosoftPeeringConfig : Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.MicrosoftPeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftPeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-107">Abrufen oder festlegen die Microsoft-peering-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-107">Gets or sets the Microsoft peering configuration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-108">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-108">Gets name of the resource that is unique within a resource group.</span></span>
            <span data-ttu-id="1dc8f-109">Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-109">This name can be used to access the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeerASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PeerASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PeerASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PeerASN" />
      <MemberSignature Language="VB.NET" Value="Public Property PeerASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PeerASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PeerASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peerASN")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-110">Ruft ab oder legt den Peer-ASN.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-110">Gets or sets the peer ASN.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringType">
      <MemberSignature Language="C#" Value="public string PeeringType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PeeringType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PeeringType" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringType As String" />
      <MemberSignature Language="F#" Value="member this.PeeringType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PeeringType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peeringType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-111">Ruft ab oder legt die Peeringtyp.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-111">Gets or sets the PeeringType.</span></span> <span data-ttu-id="1dc8f-112">Mögliche Werte sind: "AzurePublicPeering", "AzurePrivatePeering" und "MicrosoftPeering".</span><span class="sxs-lookup"><span data-stu-id="1dc8f-112">Possible values are: 'AzurePublicPeering', 'AzurePrivatePeering', and 'MicrosoftPeering'.</span></span> <span data-ttu-id="1dc8f-113">Folgende Werte sind möglich: "AzurePublicPeering", "AzurePrivatePeering", "MicrosoftPeering"</span><span class="sxs-lookup"><span data-stu-id="1dc8f-113">Possible values include: 'AzurePublicPeering', 'AzurePrivatePeering', 'MicrosoftPeering'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAzurePort">
      <MemberSignature Language="C#" Value="public string PrimaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PrimaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PrimaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryAzurePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-114">Ruft ab oder legt den primären Anschluss.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-114">Gets or sets the primary port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string PrimaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PrimaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.PrimaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-115">Abrufen oder Festlegen der primären Adresspräfix.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-115">Gets or sets the primary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-116">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-116">Gets the provisioning state of the public IP resource.</span></span> <span data-ttu-id="1dc8f-117">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="1dc8f-117">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner RouteFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner RouteFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.RouteFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteFilter As RouteFilterInner" />
      <MemberSignature Language="F#" Value="member this.RouteFilter : Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.RouteFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.RouteFilterInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-118">Ruft ab oder legt den Verweis der RouteFilter Ressource.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-118">Gets or sets the reference of the RouteFilter resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryAzurePort">
      <MemberSignature Language="C#" Value="public string SecondaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SecondaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SecondaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryAzurePort")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-119">Abrufen oder festlegen den sekundären Port.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-119">Gets or sets the secondary port.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string SecondaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SecondaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SecondaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.secondaryPeerAddressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-120">Abrufen oder Festlegen der sekundären Adresspräfix.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-120">Gets or sets the secondary address prefix.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedKey">
      <MemberSignature Language="C#" Value="public string SharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.SharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sharedKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-121">Ruft ab oder legt den gemeinsam verwendeten Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-121">Gets or sets the shared key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-122">Ruft ab oder legt den Zustand des peering.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-122">Gets or sets the state of peering.</span></span> <span data-ttu-id="1dc8f-123">Mögliche Werte sind: "Disabled" und "Enabled".</span><span class="sxs-lookup"><span data-stu-id="1dc8f-123">Possible values are: 'Disabled' and 'Enabled'.</span></span> <span data-ttu-id="1dc8f-124">Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</span><span class="sxs-lookup"><span data-stu-id="1dc8f-124">Possible values include: 'Disabled', 'Enabled'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As ExpressRouteCircuitStatsInner" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitStatsInner</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-125">Statistiken ruft peering.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-125">Gets peering stats.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VlanId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VlanId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VlanId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.VlanId" />
      <MemberSignature Language="VB.NET" Value="Public Property VlanId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VlanId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.ExpressRouteCircuitPeeringInner.VlanId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vlanId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1dc8f-126">Ruft ab oder legt das VLAN ID.</span><span class="sxs-lookup"><span data-stu-id="1dc8f-126">Gets or sets the VLAN ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>