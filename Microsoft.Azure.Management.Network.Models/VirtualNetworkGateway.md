<Type Name="VirtualNetworkGateway" FullName="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGateway : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGateway extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGateway&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGateway = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Network.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Eine allgemeine Klasse für allgemeine Ressourceninformationen
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor" />
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
            Initialisiert eine neue Instanz der VirtualNetworkGateway-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGateway (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations = null, string gatewayType = null, string vpnType = null, Nullable&lt;bool&gt; enableBgp = null, Nullable&lt;bool&gt; activeActive = null, Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite = null, Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku = null, Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration = null, Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; ipConfigurations, string gatewayType, string vpnType, valuetype System.Nullable`1&lt;bool&gt; enableBgp, valuetype System.Nullable`1&lt;bool&gt; activeActive, class Microsoft.Azure.Management.Network.Models.SubResource gatewayDefaultSite, class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku sku, class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration vpnClientConfiguration, class Microsoft.Azure.Management.Network.Models.BgpSettings bgpSettings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration},System.String,System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku,Microsoft.Azure.Management.Network.Models.VpnClientConfiguration,Microsoft.Azure.Management.Network.Models.BgpSettings,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; * string * string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku * Microsoft.Azure.Management.Network.Models.VpnClientConfiguration * Microsoft.Azure.Management.Network.Models.BgpSettings * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway" Usage="new Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway (id, name, type, location, tags, ipConfigurations, gatewayType, vpnType, enableBgp, activeActive, gatewayDefaultSite, sku, vpnClientConfiguration, bgpSettings, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="ipConfigurations" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;" />
        <Parameter Name="gatewayType" Type="System.String" />
        <Parameter Name="vpnType" Type="System.String" />
        <Parameter Name="enableBgp" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="activeActive" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="gatewayDefaultSite" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku" />
        <Parameter Name="vpnClientConfiguration" Type="Microsoft.Azure.Management.Network.Models.VpnClientConfiguration" />
        <Parameter Name="bgpSettings" Type="Microsoft.Azure.Management.Network.Models.BgpSettings" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="ipConfigurations">IP-Konfigurationen für das Gateway des virtuellen Netzwerks.</param>
        <param name="gatewayType">Der Typ des diesem Gateway des virtuellen Netzwerks.
            Mögliche Werte sind: "Vpn" und "ExpressRoute". Folgende Werte sind möglich: "Vpn", "ExpressRoute"</param>
        <param name="vpnType">Der Typ des diesem Gateway des virtuellen Netzwerks.
            Mögliche Werte sind: "PolicyBased" und "Als routebased festgelegt". Folgende Werte sind möglich: "PolicyBased", "Als routebased festgelegt"</param>
        <param name="enableBgp">Gibt an, ob BGP für dieses virtuelle Netzwerkgateway oder nicht aktiviert ist.</param>
        <param name="activeActive">ActiveActive-flag</param>
        <param name="gatewayDefaultSite">Der Verweis der Gatewayverbindung Ressource, die Website im lokalen Netzwerk mit Standardrouten darstellt. Zuweisen von Null-Wert im Falle vorhandene Standardeinstellung entfernen.</param>
        <param name="sku">Der Verweis der VirtualNetworkGatewaySku Ressource die SKU für das virtuelle Netzwerkgateway ausgewählt dar.</param>
        <param name="vpnClientConfiguration">Der Verweis der VpnClientConfiguration Ressource die P2S VpnClient Konfigurationen dar.</param>
        <param name="bgpSettings">Virtuelles Netzwerk-Gateway-BGP-sprechender Benutzer-Einstellungen.</param>
        <param name="resourceGuid">Die GUID-Eigenschaft der Ressource VirtualNetworkGateway-Ressource.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der VirtualNetworkGateway Ressource. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="etag">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkGateway-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActiveActive">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ActiveActive { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ActiveActive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberSignature Language="VB.NET" Value="Public Property ActiveActive As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ActiveActive : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ActiveActive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.activeActive")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab bzw. legt ActiveActive-Flag fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.BgpSettings BgpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpSettings As BgpSettings" />
      <MemberSignature Language="F#" Value="member this.BgpSettings : Microsoft.Azure.Management.Network.Models.BgpSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.BgpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.BgpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Gateways des virtuellen Netzwerks BGP sprechender Benutzer Einstellungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableBgp">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; EnableBgp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; EnableBgp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberSignature Language="VB.NET" Value="Public Property EnableBgp As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.EnableBgp : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.EnableBgp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.enableBgp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob BGP für dieses virtuelle Netzwerkgateway aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Etag" />
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
    <Member MemberName="GatewayDefaultSite">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource GatewayDefaultSite" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayDefaultSite As SubResource" />
      <MemberSignature Language="F#" Value="member this.GatewayDefaultSite : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayDefaultSite" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayDefaultSite")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der Gatewayverbindung Ressource, die Website im lokalen Netzwerk mit Standardrouten darstellt. Zuweisen von Null-Wert im Falle vorhandene Standardeinstellung entfernen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayType">
      <MemberSignature Language="C#" Value="public string GatewayType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayType As String" />
      <MemberSignature Language="F#" Value="member this.GatewayType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.GatewayType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ dieses Gateway des virtuellen Netzwerks fest. Mögliche Werte sind: "Vpn" und "ExpressRoute". Folgende Werte sind möglich: "Vpn", "ExpressRoute"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfigurations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; IpConfigurations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Property IpConfigurations As IList(Of VirtualNetworkGatewayIPConfiguration)" />
      <MemberSignature Language="F#" Value="member this.IpConfigurations : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.IpConfigurations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfigurations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewayIPConfiguration&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der IP-Konfigurationen für das Gateway des virtuellen Netzwerks.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ProvisioningState" />
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
            Ruft den Bereitstellungsstatus der VirtualNetworkGateway Ressource ab.
            Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resourceGuid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die GUID-Eigenschaft der Ressource VirtualNetworkGateway "Ressource" ".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As VirtualNetworkGatewaySku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VirtualNetworkGatewaySku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der VirtualNetworkGatewaySku Ressource die SKU für das virtuelle Netzwerkgateway ausgewählt dar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnClientConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.VpnClientConfiguration VpnClientConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnClientConfiguration As VpnClientConfiguration" />
      <MemberSignature Language="F#" Value="member this.VpnClientConfiguration : Microsoft.Azure.Management.Network.Models.VpnClientConfiguration with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnClientConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnClientConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.VpnClientConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der VpnClientConfiguration Ressource die P2S VpnClient Konfigurationen dar.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VpnType">
      <MemberSignature Language="C#" Value="public string VpnType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VpnType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberSignature Language="VB.NET" Value="Public Property VpnType As String" />
      <MemberSignature Language="F#" Value="member this.VpnType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.VirtualNetworkGateway.VpnType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vpnType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ dieses Gateway des virtuellen Netzwerks fest. Mögliche Werte sind: "PolicyBased" und "Als routebased festgelegt". Folgende Werte sind möglich: "PolicyBased", "Als routebased festgelegt"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>