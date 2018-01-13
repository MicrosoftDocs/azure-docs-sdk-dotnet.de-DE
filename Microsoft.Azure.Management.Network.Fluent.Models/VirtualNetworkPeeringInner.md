<Type Name="VirtualNetworkPeeringInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner">
  <TypeSignature Language="C#" Value="public class VirtualNetworkPeeringInner : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkPeeringInner extends Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkPeeringInner&#xA;Inherits SubResource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkPeeringInner = class&#xA;    inherit SubResource" />
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
            Kann in einem virtuellen Netzwerk-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkPeeringInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkPeeringInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkPeeringInner (string id = null, Nullable&lt;bool&gt; allowVirtualNetworkAccess = null, Nullable&lt;bool&gt; allowForwardedTraffic = null, Nullable&lt;bool&gt; allowGatewayTransit = null, Nullable&lt;bool&gt; useRemoteGateways = null, Microsoft.Azure.Management.ResourceManager.Fluent.SubResource remoteVirtualNetwork = null, string peeringState = null, string provisioningState = null, string name = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, valuetype System.Nullable`1&lt;bool&gt; allowVirtualNetworkAccess, valuetype System.Nullable`1&lt;bool&gt; allowForwardedTraffic, valuetype System.Nullable`1&lt;bool&gt; allowGatewayTransit, valuetype System.Nullable`1&lt;bool&gt; useRemoteGateways, class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource remoteVirtualNetwork, string peeringState, string provisioningState, string name, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},System.Nullable{System.Boolean},Microsoft.Azure.Management.ResourceManager.Fluent.SubResource,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional allowVirtualNetworkAccess As Nullable(Of Boolean) = null, Optional allowForwardedTraffic As Nullable(Of Boolean) = null, Optional allowGatewayTransit As Nullable(Of Boolean) = null, Optional useRemoteGateways As Nullable(Of Boolean) = null, Optional remoteVirtualNetwork As SubResource = null, Optional peeringState As String = null, Optional provisioningState As String = null, Optional name As String = null, Optional etag As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner : string * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; * Microsoft.Azure.Management.ResourceManager.Fluent.SubResource * string * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner (id, allowVirtualNetworkAccess, allowForwardedTraffic, allowGatewayTransit, useRemoteGateways, remoteVirtualNetwork, peeringState, provisioningState, name, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="allowVirtualNetworkAccess" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="allowForwardedTraffic" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="allowGatewayTransit" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="useRemoteGateways" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="remoteVirtualNetwork" Type="Microsoft.Azure.Management.ResourceManager.Fluent.SubResource" />
        <Parameter Name="peeringState" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">To be added.</param>
        <param name="allowVirtualNetworkAccess">Gibt an, ob die virtuellen Computer in der verknüpften virtuellen netzwerkraums auf alle virtuellen Computer im lokalen virtuellen netzwerkraums zugreifen werden würde.</param>
        <param name="allowForwardedTraffic">Gibt an, ob der weitergeleitete Datenverkehr aus den virtuellen Computern in das virtuelle Remotenetzwerk zugelassen/nicht zugelassen werden.</param>
        <param name="allowGatewayTransit">Wenn Gateway Links in remote virtuellen Netzwerken verwendet werden kann, Verknüpfen mit diesem virtuellen Netzwerk.</param>
        <param name="useRemoteGateways">Wenn der remote-Gateways auf diesem virtuellen Netzwerk verwendet werden können. Wenn das Flag festgelegt ist, auf "true", und AllowGatewayTransit auf remotepeering ist ebenfalls "true", virtuelles Netzwerk-Gateways des virtuellen Remotenetzwerk für während der Übertragung. Nur ein peering möglich, dass dieses Kennzeichen auf "true" festgelegt wird. Dieses Flag kann nicht festgelegt werden, wenn das virtuelles Netzwerk bereits ein Gateway.</param>
        <param name="remoteVirtualNetwork">Der Verweis für das virtuelle Netzwerk.</param>
        <param name="peeringState">Der Status des virtuellen Netzwerks peering. Mögliche Werte sind "Initiiert", "Verbunden" und "Getrennt". Folgende Werte sind möglich: "Initiiert", "Verbunden", "getrennt"</param>
        <param name="provisioningState">Der Bereitstellungsstatus der Ressource.</param>
        <param name="name">Der Name der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkPeeringInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowForwardedTraffic">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowForwardedTraffic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowForwardedTraffic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowForwardedTraffic" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowForwardedTraffic As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowForwardedTraffic : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowForwardedTraffic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowForwardedTraffic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, ob der weitergeleitete Datenverkehr aus den virtuellen Computern in das virtuelle Remotenetzwerk zugelassen/nicht zugelassen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowGatewayTransit">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowGatewayTransit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowGatewayTransit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowGatewayTransit" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowGatewayTransit As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowGatewayTransit : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowGatewayTransit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowGatewayTransit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Gateway-Links in remote virtuelle Netzwerke verwendet werden kann, um mit diesem virtuellen Netzwerk zu verknüpfen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowVirtualNetworkAccess">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; AllowVirtualNetworkAccess { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; AllowVirtualNetworkAccess" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowVirtualNetworkAccess" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowVirtualNetworkAccess As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.AllowVirtualNetworkAccess : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.AllowVirtualNetworkAccess" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allowVirtualNetworkAccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die virtuellen Computer in der verknüpften virtuellen netzwerkraums wäre auf alle virtuellen Computer im lokalen virtuellen netzwerkraums zugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.Etag" />
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
            Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.Name" />
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
            Ruft ab oder legt den Namen der Ressource, die innerhalb einer Ressourcengruppe eindeutig ist. Dieser Name kann verwendet werden, auf die Ressource zuzugreifen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PeeringState">
      <MemberSignature Language="C#" Value="public string PeeringState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PeeringState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.PeeringState" />
      <MemberSignature Language="VB.NET" Value="Public Property PeeringState As String" />
      <MemberSignature Language="F#" Value="member this.PeeringState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.PeeringState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.peeringState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Status des virtuellen Netzwerks peering fest. Mögliche Werte sind "Initiiert", "Verbunden" und "Getrennt". Folgende Werte sind möglich: "Initiiert", "Verbunden", "getrennt"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.ProvisioningState" />
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
            Ruft ab oder legt den Bereitstellungsstatus der Ressource.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteVirtualNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.SubResource RemoteVirtualNetwork { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.SubResource RemoteVirtualNetwork" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.RemoteVirtualNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoteVirtualNetwork As SubResource" />
      <MemberSignature Language="F#" Value="member this.RemoteVirtualNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.RemoteVirtualNetwork" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.remoteVirtualNetwork")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Verweis in das virtuelle Netzwerk.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseRemoteGateways">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseRemoteGateways { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseRemoteGateways" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.UseRemoteGateways" />
      <MemberSignature Language="VB.NET" Value="Public Property UseRemoteGateways As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseRemoteGateways : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner.UseRemoteGateways" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.useRemoteGateways")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, wenn der remote-Gateways auf diesem virtuellen Netzwerk verwendet werden können. Wenn das Flag festgelegt ist, auf "true", und AllowGatewayTransit auf remotepeering ist ebenfalls "true", virtuelles Netzwerk-Gateways des virtuellen Remotenetzwerk für während der Übertragung. Nur ein peering möglich, dass dieses Kennzeichen auf "true" festgelegt wird. Dieses Flag kann nicht festgelegt werden, wenn das virtuelles Netzwerk bereits ein Gateway.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>