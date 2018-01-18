<Type Name="LocalNetworkGatewayInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner">
  <TypeSignature Language="C#" Value="public class LocalNetworkGatewayInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LocalNetworkGatewayInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner" />
  <TypeSignature Language="VB.NET" Value="Public Class LocalNetworkGatewayInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type LocalNetworkGatewayInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.ResourceManager.Fluent.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="5d93a-101">Eine allgemeine Klasse für allgemeine Ressourceninformationen</span><span class="sxs-lookup"><span data-stu-id="5d93a-101">A common class for general resource information</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalNetworkGatewayInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5d93a-102">Initialisiert eine neue Instanz der LocalNetworkGatewayInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5d93a-102">Initializes a new instance of the LocalNetworkGatewayInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LocalNetworkGatewayInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace localNetworkAddressSpace = null, string gatewayIpAddress = null, Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings bgpSettings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace localNetworkAddressSpace, string gatewayIpAddress, class Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings bgpSettings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace,System.String,Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings,System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace * string * Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner (location, id, name, type, tags, localNetworkAddressSpace, gatewayIpAddress, bgpSettings, resourceGuid, provisioningState, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="localNetworkAddressSpace" Type="Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace" />
        <Parameter Name="gatewayIpAddress" Type="System.String" />
        <Parameter Name="bgpSettings" Type="Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="localNetworkAddressSpace">To be added.</param>
        <param name="gatewayIpAddress">To be added.</param>
        <param name="bgpSettings">To be added.</param>
        <param name="resourceGuid">To be added.</param>
        <param name="provisioningState">To be added.</param>
        <param name="etag">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings BgpSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings BgpSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.BgpSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpSettings As BgpSettings" />
      <MemberSignature Language="F#" Value="member this.BgpSettings : Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.BgpSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.BgpSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d93a-103">Abrufen oder Festlegen des Gateways des lokalen Netzwerks BGP sprechender Benutzer Einstellungen.</span><span class="sxs-lookup"><span data-stu-id="5d93a-103">Gets or sets local network gateway's BGP speaker settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.Etag" />
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
            <span data-ttu-id="5d93a-104">Ruft ab oder legt eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="5d93a-104">Gets or sets a unique read-only string that changes whenever the resource is updated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewayIpAddress">
      <MemberSignature Language="C#" Value="public string GatewayIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewayIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.GatewayIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property GatewayIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.GatewayIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.GatewayIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.gatewayIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d93a-105">Ruft ab oder legt die IP-Adresse des lokalen Netzwerkgateways.</span><span class="sxs-lookup"><span data-stu-id="5d93a-105">Gets or sets IP address of local network gateway.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocalNetworkAddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace LocalNetworkAddressSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace LocalNetworkAddressSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.LocalNetworkAddressSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property LocalNetworkAddressSpace As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.LocalNetworkAddressSpace : Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.LocalNetworkAddressSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.localNetworkAddressSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5d93a-106">Abrufen oder Festlegen der Adressraum des lokalen Netzwerks Standort.</span><span class="sxs-lookup"><span data-stu-id="5d93a-106">Gets or sets local network site address space.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.ProvisioningState" />
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
            <span data-ttu-id="5d93a-107">Ruft den Bereitstellungsstatus der Gatewayverbindung Ressource ab.</span><span class="sxs-lookup"><span data-stu-id="5d93a-107">Gets the provisioning state of the LocalNetworkGateway resource.</span></span>
            <span data-ttu-id="5d93a-108">Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</span><span class="sxs-lookup"><span data-stu-id="5d93a-108">Possible values are: 'Updating', 'Deleting', and 'Failed'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.LocalNetworkGatewayInner.ResourceGuid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="5d93a-109">Abrufen oder Festlegen der Ressourcen-GUID-Eigenschaft der Ressource Gatewayverbindung.</span><span class="sxs-lookup"><span data-stu-id="5d93a-109">Gets or sets the resource GUID property of the LocalNetworkGateway resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>