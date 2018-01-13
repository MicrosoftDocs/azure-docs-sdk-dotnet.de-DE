<Type Name="NetworkInterfaceIPConfiguration" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceIPConfiguration : Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceIPConfiguration extends Microsoft.Azure.Management.Network.Models.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceIPConfiguration&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceIPConfiguration = class&#xA;    inherit SubResource" />
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
            IP-Konfiguration in eine Netzwerkschnittstelle.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceIPConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.#ctor" />
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
            Initialisiert eine neue Instanz der NetworkInterfaceIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceIPConfiguration (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; applicationGatewayBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; loadBalancerBackendAddressPools = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; loadBalancerInboundNatRules = null, string privateIPAddress = null, string privateIPAllocationMethod = null, string privateIPAddressVersion = null, Microsoft.Azure.Management.Network.Models.Subnet subnet = null, Nullable&lt;bool&gt; primary = null, Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; applicationSecurityGroups = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; applicationGatewayBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; loadBalancerBackendAddressPools, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; loadBalancerInboundNatRules, string privateIPAddress, string privateIPAllocationMethod, string privateIPAddressVersion, class Microsoft.Azure.Management.Network.Models.Subnet subnet, valuetype System.Nullable`1&lt;bool&gt; primary, class Microsoft.Azure.Management.Network.Models.PublicIPAddress publicIPAddress, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; applicationSecurityGroups, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BackendAddressPool},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.InboundNatRule},System.String,System.String,System.String,Microsoft.Azure.Management.Network.Models.Subnet,System.Nullable{System.Boolean},Microsoft.Azure.Management.Network.Models.PublicIPAddress,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; * string * string * string * Microsoft.Azure.Management.Network.Models.Subnet * Nullable&lt;bool&gt; * Microsoft.Azure.Management.Network.Models.PublicIPAddress * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration (id, applicationGatewayBackendAddressPools, loadBalancerBackendAddressPools, loadBalancerInboundNatRules, privateIPAddress, privateIPAllocationMethod, privateIPAddressVersion, subnet, primary, publicIPAddress, applicationSecurityGroups, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="applicationGatewayBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;" />
        <Parameter Name="loadBalancerBackendAddressPools" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;" />
        <Parameter Name="loadBalancerInboundNatRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;" />
        <Parameter Name="privateIPAddress" Type="System.String" />
        <Parameter Name="privateIPAllocationMethod" Type="System.String" />
        <Parameter Name="privateIPAddressVersion" Type="System.String" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Models.Subnet" />
        <Parameter Name="primary" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
        <Parameter Name="applicationSecurityGroups" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="applicationGatewayBackendAddressPools">Der Verweis ApplicationGatewayBackendAddressPool Ressource.</param>
        <param name="loadBalancerBackendAddressPools">Der Verweis LoadBalancerBackendAddressPool Ressource.</param>
        <param name="loadBalancerInboundNatRules">Eine Liste von Verweisen auf LoadBalancerInboundNatRules.</param>
        <param name="privateIPAddress">Private IP-Adresse der IP-Konfiguration.</param>
        <param name="privateIPAllocationMethod">Definiert, wie eine private IP-Adresse zugewiesen wird. Mögliche Werte sind: "Static" und "Dynamic".
            Folgende Werte sind möglich: "Static", "Dynamic"</param>
        <param name="privateIPAddressVersion">Von Api-Version 2016-03-30 darstellt oder höher, er, ob die spezifische IP-Konfiguration IPv4 oder IPv6 ist. Standardmäßig wird als IPv4 verwendet.
            Mögliche Werte sind: "IPv4" und "IPv6". Folgende Werte sind möglich: "IPv4", "IPv6"</param>
        <param name="subnet">Subnetz gebunden, um die IP-Konfiguration.</param>
        <param name="primary">Ruft ab, ob dies eine primäre Kundenadresse auf der Netzwerkschnittstelle ist.</param>
        <param name="publicIPAddress">Öffentliche IP-Adresse, die an die IP-Konfiguration gebunden werden.</param>
        <param name="applicationSecurityGroups">Anwendung Sicherheitsgruppen, in denen die IP-Konfiguration enthalten ist.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der IP-Konfiguration der Netzwerkschnittstelle. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="name">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der NetworkInterfaceIPConfiguration-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationGatewayBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; ApplicationGatewayBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationGatewayBackendAddressPools As IList(Of ApplicationGatewayBackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.ApplicationGatewayBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationGatewayBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationGatewayBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationGatewayBackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der ApplicationGatewayBackendAddressPool Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationSecurityGroups">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ApplicationSecurityGroups { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; ApplicationSecurityGroups" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationSecurityGroups" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationSecurityGroups As IList(Of ApplicationSecurityGroup)" />
      <MemberSignature Language="F#" Value="member this.ApplicationSecurityGroups : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ApplicationSecurityGroups" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationSecurityGroups")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.ApplicationSecurityGroup&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Anwendung Sicherheitsgruppen, die in denen die IP-Konfiguration enthalten ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Etag" />
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
            Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerBackendAddressPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; LoadBalancerBackendAddressPools { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; LoadBalancerBackendAddressPools" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerBackendAddressPools As IList(Of BackendAddressPool)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerBackendAddressPools : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerBackendAddressPools" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerBackendAddressPools")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BackendAddressPool&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis der LoadBalancerBackendAddressPool Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadBalancerInboundNatRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; LoadBalancerInboundNatRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; LoadBalancerInboundNatRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerInboundNatRules" />
      <MemberSignature Language="VB.NET" Value="Public Property LoadBalancerInboundNatRules As IList(Of InboundNatRule)" />
      <MemberSignature Language="F#" Value="member this.LoadBalancerInboundNatRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.LoadBalancerInboundNatRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.loadBalancerInboundNatRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.InboundNatRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Verweisen auf LoadBalancerInboundNatRules.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Name" />
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
            Ruft ab oder legt den Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Primary">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Primary { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Primary" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Primary" />
      <MemberSignature Language="VB.NET" Value="Public Property Primary As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Primary : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Primary" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.primary")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, ob dies eine primäre Kundenadresse auf der Netzwerkschnittstelle ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddress">
      <MemberSignature Language="C#" Value="public string PrivateIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt die private IP-Adresse der IP-Konfiguration fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PrivateIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-Api-Version 2016-03-30 verfügbar oder höher, stellt, ob die spezifische IP-Konfiguration IPv4 oder IPv6 ist dar.
            Standardmäßig wird als IPv4 verwendet.  Mögliche Werte sind: "IPv4" und "IPv6".
            Folgende Werte sind möglich: "IPv4", "IPv6"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrivateIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PrivateIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrivateIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PrivateIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PrivateIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PrivateIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.privateIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest definiert, wie eine private IP-Adresse zugewiesen wird. Mögliche Werte sind: "Static" und "Dynamic". Folgende Werte sind möglich: "Static", "Dynamic"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.ProvisioningState" />
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
            Ruft ab oder legt den Bereitstellungsstatus der IP-Konfiguration der Netzwerkschnittstelle. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddress PublicIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddress As PublicIPAddress" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddress : Microsoft.Azure.Management.Network.Models.PublicIPAddress with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.PublicIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddress</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest öffentliche IP-Adresse der IP-Konfiguration gebunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.Subnet Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.Subnet Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As Subnet" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Models.Subnet with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceIPConfiguration.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.Subnet</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Subnetz, die an die IP-Konfiguration gebunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>