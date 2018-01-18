<Type Name="GatewayRoute" FullName="Microsoft.Azure.Management.Network.Models.GatewayRoute">
  <TypeSignature Language="C#" Value="public class GatewayRoute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GatewayRoute extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.GatewayRoute" />
  <TypeSignature Language="VB.NET" Value="Public Class GatewayRoute" />
  <TypeSignature Language="F#" Value="type GatewayRoute = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5aec8-101">Gateway-routing-details</span><span class="sxs-lookup"><span data-stu-id="5aec8-101">Gateway routing details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GatewayRoute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.GatewayRoute.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-102">Initialisiert eine neue Instanz der GatewayRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5aec8-102">Initializes a new instance of the GatewayRoute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GatewayRoute (string localAddress = null, string network = null, string nextHop = null, string sourcePeer = null, string origin = null, string asPath = null, Nullable&lt;int&gt; weight = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string localAddress, string network, string nextHop, string sourcePeer, string origin, string asPath, valuetype System.Nullable`1&lt;int32&gt; weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.GatewayRoute.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional localAddress As String = null, Optional network As String = null, Optional nextHop As String = null, Optional sourcePeer As String = null, Optional origin As String = null, Optional asPath As String = null, Optional weight As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.GatewayRoute : string * string * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Models.GatewayRoute" Usage="new Microsoft.Azure.Management.Network.Models.GatewayRoute (localAddress, network, nextHop, sourcePeer, origin, asPath, weight)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="localAddress" Type="System.String" />
        <Parameter Name="network" Type="System.String" />
        <Parameter Name="nextHop" Type="System.String" />
        <Parameter Name="sourcePeer" Type="System.String" />
        <Parameter Name="origin" Type="System.String" />
        <Parameter Name="asPath" Type="System.String" />
        <Parameter Name="weight" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="localAddress"><span data-ttu-id="5aec8-103">Die lokale Gatewayadresse</span><span class="sxs-lookup"><span data-stu-id="5aec8-103">The gateway's local address</span></span></param>
        <param name="network"><span data-ttu-id="5aec8-104">Das Routenpräfix Netzwerk</span><span class="sxs-lookup"><span data-stu-id="5aec8-104">The route's network prefix</span></span></param>
        <param name="nextHop"><span data-ttu-id="5aec8-105">Nächsten Hops der route</span><span class="sxs-lookup"><span data-stu-id="5aec8-105">The route's next hop</span></span></param>
        <param name="sourcePeer"><span data-ttu-id="5aec8-106">Der Peer wurde diese Route aus gelernt haben.</span><span class="sxs-lookup"><span data-stu-id="5aec8-106">The peer this route was learned from</span></span></param>
        <param name="origin"><span data-ttu-id="5aec8-107">Die Quelle wurde diese Route aus gelernt haben.</span><span class="sxs-lookup"><span data-stu-id="5aec8-107">The source this route was learned from</span></span></param>
        <param name="asPath"><span data-ttu-id="5aec8-108">ALS Folge der Pfad der route</span><span class="sxs-lookup"><span data-stu-id="5aec8-108">The route's AS path sequence</span></span></param>
        <param name="weight"><span data-ttu-id="5aec8-109">Die Route-Gewichtung</span><span class="sxs-lookup"><span data-stu-id="5aec8-109">The route's weight</span></span></param>
        <summary>
            <span data-ttu-id="5aec8-110">Initialisiert eine neue Instanz der GatewayRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5aec8-110">Initializes a new instance of the GatewayRoute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AsPath">
      <MemberSignature Language="C#" Value="public string AsPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AsPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.AsPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AsPath As String" />
      <MemberSignature Language="F#" Value="member this.AsPath : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.AsPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="asPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-111">Ruft der Route als Pfad Sequenz ab</span><span class="sxs-lookup"><span data-stu-id="5aec8-111">Gets the route's AS path sequence</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalAddress">
      <MemberSignature Language="C#" Value="public string LocalAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocalAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.LocalAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocalAddress As String" />
      <MemberSignature Language="F#" Value="member this.LocalAddress : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.LocalAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="localAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-112">Ruft die lokale Gatewayadresse</span><span class="sxs-lookup"><span data-stu-id="5aec8-112">Gets the gateway's local address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Network">
      <MemberSignature Language="C#" Value="public string Network { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Network" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.Network" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Network As String" />
      <MemberSignature Language="F#" Value="member this.Network : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.Network" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="network")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-113">Ruft das Routenpräfix Netzwerk ab</span><span class="sxs-lookup"><span data-stu-id="5aec8-113">Gets the route's network prefix</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHop">
      <MemberSignature Language="C#" Value="public string NextHop { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHop" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.NextHop" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NextHop As String" />
      <MemberSignature Language="F#" Value="member this.NextHop : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.NextHop" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHop")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-114">Ruft die nächsten Hops der Route ab</span><span class="sxs-lookup"><span data-stu-id="5aec8-114">Gets the route's next hop</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Origin">
      <MemberSignature Language="C#" Value="public string Origin { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Origin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.Origin" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Origin As String" />
      <MemberSignature Language="F#" Value="member this.Origin : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.Origin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="origin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-115">Ruft die Quelle, die, der diese Route aus gelernt wurde, ab</span><span class="sxs-lookup"><span data-stu-id="5aec8-115">Gets the source this route was learned from</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePeer">
      <MemberSignature Language="C#" Value="public string SourcePeer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePeer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.SourcePeer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourcePeer As String" />
      <MemberSignature Language="F#" Value="member this.SourcePeer : string" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.SourcePeer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourcePeer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-116">Ruft den Peer, die, dem diese Route aus gelernt wurde</span><span class="sxs-lookup"><span data-stu-id="5aec8-116">Gets the peer this route was learned from</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Weight">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Weight { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Weight" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.GatewayRoute.Weight" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Weight As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Weight : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Network.Models.GatewayRoute.Weight" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="weight")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5aec8-117">Ruft die Route-Gewichtung</span><span class="sxs-lookup"><span data-stu-id="5aec8-117">Gets the route's weight</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>