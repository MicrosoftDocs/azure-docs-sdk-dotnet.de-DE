<Type Name="ExpressRouteCircuitPeering" FullName="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering">
  <TypeSignature Language="C#" Value="public class ExpressRouteCircuitPeering : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExpressRouteCircuitPeering extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" />
  <TypeSignature Language="VB.NET" Value="Public Class ExpressRouteCircuitPeering&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type ExpressRouteCircuitPeering = class&#xA;    inherit SubResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.SubResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            In einer Ressource ExpressRouteCircuit Peering.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeering ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.#ctor" />
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
            Initialisiert eine neue Instanz der ExpressRouteCircuitPeering-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExpressRouteCircuitPeering (string id = null, string peeringType = null, string state = null, Nullable&lt;int&gt; azureASN = null, Nullable&lt;int&gt; peerASN = null, string primaryPeerAddressPrefix = null, string secondaryPeerAddressPrefix = null, string primaryAzurePort = null, string secondaryAzurePort = null, string sharedKey = null, Nullable&lt;int&gt; vlanId = null, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig = null, Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats stats = null, string provisioningState = null, string gatewayManagerEtag = null, string lastModifiedBy = null, Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter = null, Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string peeringType, string state, valuetype System.Nullable`1&lt;int32&gt; azureASN, valuetype System.Nullable`1&lt;int32&gt; peerASN, string primaryPeerAddressPrefix, string secondaryPeerAddressPrefix, string primaryAzurePort, string secondaryAzurePort, string sharedKey, valuetype System.Nullable`1&lt;int32&gt; vlanId, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig microsoftPeeringConfig, class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats stats, string provisioningState, string gatewayManagerEtag, string lastModifiedBy, class Microsoft.Azure.Management.Network.Models.RouteFilter routeFilter, class Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig ipv6PeeringConfig, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.#ctor(System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig,Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats,System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.RouteFilter,Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering : string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * string * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig * Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats * string * string * string * Microsoft.Azure.Management.Network.Models.RouteFilter * Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig * string * string -&gt; Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering" Usage="new Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering (id, peeringType, state, azureASN, peerASN, primaryPeerAddressPrefix, secondaryPeerAddressPrefix, primaryAzurePort, secondaryAzurePort, sharedKey, vlanId, microsoftPeeringConfig, stats, provisioningState, gatewayManagerEtag, lastModifiedBy, routeFilter, ipv6PeeringConfig, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
        <Parameter Name="microsoftPeeringConfig" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="stats" Type="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="gatewayManagerEtag" Type="System.String" />
        <Parameter Name="lastModifiedBy" Type="System.String" />
        <Parameter Name="routeFilter" Type="Microsoft.Azure.Management.Network.Models.RouteFilter" />
        <Parameter Name="ipv6PeeringConfig" Type="Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="peeringType">Der Peeringtyp. Mögliche Werte sind: "AzurePublicPeering", "AzurePrivatePeering" und "MicrosoftPeering". Folgende Werte sind möglich: "AzurePublicPeering", "AzurePrivatePeering", "MicrosoftPeering"</param>
        <param name="state">Der Status des peering. Mögliche Werte sind: "Disabled" und "Enabled". Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"</param>
        <param name="azureASN">Die Azure ASN.</param>
        <param name="peerASN">Die Peer-ASN.</param>
        <param name="primaryPeerAddressPrefix">Das Präfix für die primäre Adresse.</param>
        <param name="secondaryPeerAddressPrefix">Das sekundäre Adresspräfix.</param>
        <param name="primaryAzurePort">Der primäre Port.</param>
        <param name="secondaryAzurePort">Der sekundäre Port.</param>
        <param name="sharedKey">Den gemeinsam verwendeten Schlüssel.</param>
        <param name="vlanId">Die VLAN-ID.</param>
        <param name="microsoftPeeringConfig">Die Microsoft-peering-Konfiguration.</param>
        <param name="stats">Statistiken ruft peering.</param>
        <param name="provisioningState">Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="gatewayManagerEtag">Das GatewayManager Etag.</param>
        <param name="lastModifiedBy">Ruft ab, ob der Anbieter oder der Kunde das peering geändert.</param>
        <param name="routeFilter">Der Verweis der RouteFilter Ressource.</param>
        <param name="ipv6PeeringConfig">Die IPv6-peering-Konfiguration.</param>
        <param name="name">Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der ExpressRouteCircuitPeering-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AzureASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; AzureASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; AzureASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.AzureASN" />
      <MemberSignature Language="VB.NET" Value="Public Property AzureASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.AzureASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.AzureASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt die Azure-ASN.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayManagerEtag">
      <MemberSignature Language="C#" Value="public string GatewayManagerEtag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayManagerEtag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.GatewayManagerEtag" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayManagerEtag As String" />
      <MemberSignature Language="F#" Value="member this.GatewayManagerEtag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.GatewayManagerEtag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt das GatewayManager Etag fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Ipv6PeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig Ipv6PeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Ipv6PeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property Ipv6PeeringConfig As Ipv6ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.Ipv6PeeringConfig : Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Ipv6PeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipv6PeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Ipv6ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IPv6-peering-Konfiguration fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedBy">
      <MemberSignature Language="C#" Value="public string LastModifiedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LastModifiedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.LastModifiedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModifiedBy As String" />
      <MemberSignature Language="F#" Value="member this.LastModifiedBy : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.LastModifiedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab, ob der Anbieter oder der Kunde das peering geändert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicrosoftPeeringConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig MicrosoftPeeringConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.MicrosoftPeeringConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MicrosoftPeeringConfig As ExpressRouteCircuitPeeringConfig" />
      <MemberSignature Language="F#" Value="member this.MicrosoftPeeringConfig : Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.MicrosoftPeeringConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.microsoftPeeringConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeeringConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die Microsoft-peering-Konfiguration.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft die Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist.
            Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeerASN">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; PeerASN { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; PeerASN" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeerASN" />
      <MemberSignature Language="VB.NET" Value="Public Property PeerASN As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.PeerASN : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeerASN" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Peer-ASN.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringType">
      <MemberSignature Language="C#" Value="public string PeeringType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PeeringType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeeringType" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringType As String" />
      <MemberSignature Language="F#" Value="member this.PeeringType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PeeringType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt die Peeringtyp. Mögliche Werte sind: "AzurePublicPeering", "AzurePrivatePeering" und "MicrosoftPeering". Folgende Werte sind möglich: "AzurePublicPeering", "AzurePrivatePeering", "MicrosoftPeering"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAzurePort">
      <MemberSignature Language="C#" Value="public string PrimaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den primären Anschluss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string PrimaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.PrimaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Abrufen oder Festlegen der primären Adresspräfix.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft den Bereitstellungsstatus der öffentlichen IP-Ressource ab. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteFilter">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.RouteFilter RouteFilter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.RouteFilter" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteFilter As RouteFilter" />
      <MemberSignature Language="F#" Value="member this.RouteFilter : Microsoft.Azure.Management.Network.Models.RouteFilter with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.RouteFilter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.routeFilter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.RouteFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der RouteFilter Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryAzurePort">
      <MemberSignature Language="C#" Value="public string SecondaryAzurePort { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryAzurePort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryAzurePort" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryAzurePort As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryAzurePort : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryAzurePort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Abrufen oder festlegen den sekundären Port.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryPeerAddressPrefix">
      <MemberSignature Language="C#" Value="public string SecondaryPeerAddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryPeerAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryPeerAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryPeerAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryPeerAddressPrefix : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SecondaryPeerAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Abrufen oder Festlegen der sekundären Adresspräfix.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharedKey">
      <MemberSignature Language="C#" Value="public string SharedKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SharedKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SharedKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SharedKey As String" />
      <MemberSignature Language="F#" Value="member this.SharedKey : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.SharedKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den gemeinsam verwendeten Schlüssel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Zustand des peering. Mögliche Werte sind: "Disabled" und "Enabled". Folgende Werte sind möglich: "Deaktiviert", "Aktiviert"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As ExpressRouteCircuitStats" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitStats</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Statistiken ruft peering.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VlanId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VlanId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VlanId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.VlanId" />
      <MemberSignature Language="VB.NET" Value="Public Property VlanId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VlanId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.ExpressRouteCircuitPeering.VlanId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt das VLAN ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>