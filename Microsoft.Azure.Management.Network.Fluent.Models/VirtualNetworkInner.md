<Type Name="VirtualNetworkInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner">
  <TypeSignature Language="C#" Value="public class VirtualNetworkInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type VirtualNetworkInner = class&#xA;    inherit Resource" />
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
            Virtuelles Netzwerk-Ressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace addressSpace = null, Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions dhcpOptions = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; virtualNetworkPeerings = null, string resourceGuid = null, string provisioningState = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace addressSpace, class Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions dhcpOptions, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; subnets, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; virtualNetworkPeerings, string resourceGuid, string provisioningState, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace,Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner},System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner},System.String,System.String,System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace * Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; * string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner (location, id, name, type, tags, addressSpace, dhcpOptions, subnets, virtualNetworkPeerings, resourceGuid, provisioningState, etag)" />
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
        <Parameter Name="addressSpace" Type="Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace" />
        <Parameter Name="dhcpOptions" Type="Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions" />
        <Parameter Name="subnets" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;" />
        <Parameter Name="virtualNetworkPeerings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;" />
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
        <param name="addressSpace">Die AddressSpace, die ein Array von IP-Adressbereiche enthält, die von einem Subnetz verwendet werden kann.</param>
        <param name="dhcpOptions">Die DhcpOptions, die ein Array von DNS-Server im virtuellen Netzwerk bereitgestellten virtuellen Maschinen zur Verfügung.</param>
        <param name="subnets">Eine Liste von Subnetzen in einem virtuellen Netzwerk.</param>
        <param name="virtualNetworkPeerings">Eine Liste der kann in einem virtuellen Netzwerk.</param>
        <param name="resourceGuid">Die resourceguid für Eigenschaft der Ressource Virtuellenetzwerk.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der PublicIP-Ressource. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="etag">Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <summary>
            Initialisiert eine neue Instanz der VirtualNetworkInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace AddressSpace { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace AddressSpace" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.AddressSpace" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressSpace As AddressSpace" />
      <MemberSignature Language="F#" Value="member this.AddressSpace : Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.AddressSpace" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.addressSpace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der AddressSpace, die ein Array von IP-Adressbereiche enthält, die von einem Subnetz verwendet werden kann.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DhcpOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions DhcpOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions DhcpOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.DhcpOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DhcpOptions As DhcpOptions" />
      <MemberSignature Language="F#" Value="member this.DhcpOptions : Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.DhcpOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dhcpOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Models.DhcpOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der DhcpOptions, die ein Array von DNS-Server im virtuellen Netzwerk bereitgestellten virtuellen Maschinen zur Verfügung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Etag" />
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
            Ruft eine eindeutige Zeichenfolge ohne Schreibzugriff, die geändert werden, wenn die Ressource aktualisiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ProvisioningState" />
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
            Abrufen oder festlegen den Bereitstellungsstatus der PublicIP-Ressource.
            Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.ResourceGuid" />
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
            Ruft ab oder legt die Eigenschaft resourceguid für das Virtuellenetzwerk Ressource fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; Subnets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Subnets" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnets As IList(Of SubnetInner)" />
      <MemberSignature Language="F#" Value="member this.Subnets : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.Subnets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnets")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.SubnetInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Subnetzen in einem virtuellen Netzwerk.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualNetworkPeerings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; VirtualNetworkPeerings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; VirtualNetworkPeerings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.VirtualNetworkPeerings" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualNetworkPeerings As IList(Of VirtualNetworkPeeringInner)" />
      <MemberSignature Language="F#" Value="member this.VirtualNetworkPeerings : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkInner.VirtualNetworkPeerings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualNetworkPeerings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkPeeringInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der kann in einem virtuellen Netzwerk.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>