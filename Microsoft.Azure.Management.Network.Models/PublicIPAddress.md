<Type Name="PublicIPAddress" FullName="Microsoft.Azure.Management.Network.Models.PublicIPAddress">
  <TypeSignature Language="C#" Value="public class PublicIPAddress : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PublicIPAddress extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.PublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Class PublicIPAddress&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type PublicIPAddress = class&#xA;    inherit Resource" />
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
            Öffentliche IP-Adressressource.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PublicIPAddress.#ctor" />
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
            Initialisiert eine neue Instanz der PublicIPAddress-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PublicIPAddress (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.Network.Models.PublicIPAddressSku sku = null, string publicIPAllocationMethod = null, string publicIPAddressVersion = null, Microsoft.Azure.Management.Network.Models.IPConfiguration ipConfiguration = null, Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings dnsSettings = null, string ipAddress = null, Nullable&lt;int&gt; idleTimeoutInMinutes = null, string resourceGuid = null, string provisioningState = null, string etag = null, System.Collections.Generic.IList&lt;string&gt; zones = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.Network.Models.PublicIPAddressSku sku, string publicIPAllocationMethod, string publicIPAddressVersion, class Microsoft.Azure.Management.Network.Models.IPConfiguration ipConfiguration, class Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings dnsSettings, string ipAddress, valuetype System.Nullable`1&lt;int32&gt; idleTimeoutInMinutes, string resourceGuid, string provisioningState, string etag, class System.Collections.Generic.IList`1&lt;string&gt; zones) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.PublicIPAddress.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.Network.Models.PublicIPAddressSku,System.String,System.String,Microsoft.Azure.Management.Network.Models.IPConfiguration,Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings,System.String,System.Nullable{System.Int32},System.String,System.String,System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.PublicIPAddress : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.Network.Models.PublicIPAddressSku * string * string * Microsoft.Azure.Management.Network.Models.IPConfiguration * Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings * string * Nullable&lt;int&gt; * string * string * string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Models.PublicIPAddress" Usage="new Microsoft.Azure.Management.Network.Models.PublicIPAddress (id, name, type, location, tags, sku, publicIPAllocationMethod, publicIPAddressVersion, ipConfiguration, dnsSettings, ipAddress, idleTimeoutInMinutes, resourceGuid, provisioningState, etag, zones)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddressSku" />
        <Parameter Name="publicIPAllocationMethod" Type="System.String" />
        <Parameter Name="publicIPAddressVersion" Type="System.String" />
        <Parameter Name="ipConfiguration" Type="Microsoft.Azure.Management.Network.Models.IPConfiguration" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings" />
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="idleTimeoutInMinutes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="resourceGuid" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="zones" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-ID</param>
        <param name="name">Name der Ressource.</param>
        <param name="type">Der Ressourcentyp.</param>
        <param name="location">Der Ressourcenspeicherort.</param>
        <param name="tags">Ressourcentags.</param>
        <param name="sku">Die öffentliche IP-Adresse-SKU.</param>
        <param name="publicIPAllocationMethod">Die öffentliche IP-Zuordnungsmethode. Mögliche Werte sind: "Static" und "Dynamic". Folgende Werte sind möglich: "Static", "Dynamic"</param>
        <param name="publicIPAddressVersion">Die öffentliche IP-Adressversion.
            Mögliche Werte sind: "IPv4" und "IPv6". Folgende Werte sind möglich: "IPv4", "IPv6"</param>
        <param name="ipConfiguration">Die IP-Konfiguration, die öffentliche IP-Adresse zugeordnet.</param>
        <param name="dnsSettings">Der FQDN des DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.</param>
        <param name="ipAddress">Die IP-Adresse der öffentlichen IP-Adressressource zugeordnet.</param>
        <param name="idleTimeoutInMinutes">Das Leerlauftimeout der öffentlichen IP-Adresse.</param>
        <param name="resourceGuid">Die Eigenschaft "Ressource" GUID der öffentlichen IP-Adressressource.</param>
        <param name="provisioningState">Der Bereitstellungsstatus der PublicIP-Ressource. Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".</param>
        <param name="etag">Eine eindeutige schreibgeschützte Zeichenfolge, die geändert werden, wenn die Ressource aktualisiert wird.</param>
        <param name="zones">Eine Liste der Verfügbarkeit von Zonen, die für die Ressource zugeordnete IP-Adresse angibt, muss stammen.</param>
        <summary>
            Initialisiert eine neue Instanz der PublicIPAddress-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As PublicIPAddressDnsSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddressDnsSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den FQDN des DNS-Datensatzes der öffentlichen IP-Adresse zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Etag" />
      <MemberSignature Language="VB.NET" Value="Public Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Etag" />
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
    <Member MemberName="IdleTimeoutInMinutes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IdleTimeoutInMinutes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IdleTimeoutInMinutes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IdleTimeoutInMinutes" />
      <MemberSignature Language="VB.NET" Value="Public Property IdleTimeoutInMinutes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IdleTimeoutInMinutes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IdleTimeoutInMinutes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.idleTimeoutInMinutes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Leerlauftimeout der öffentlichen IP-Adresse.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die IP-Adresse der öffentlichen IP-Adressressource zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.IPConfiguration IpConfiguration { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.IPConfiguration IpConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IpConfiguration As IPConfiguration" />
      <MemberSignature Language="F#" Value="member this.IpConfiguration : Microsoft.Azure.Management.Network.Models.IPConfiguration" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.IpConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.ipConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.IPConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die IP-Konfiguration, die die öffentliche IP-Adresse zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.ProvisioningState" />
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
            Abrufen oder festlegen den Bereitstellungsstatus der PublicIP-Ressource.
            Mögliche Werte sind: "Aktualisieren", "Löschen" und "Fehler".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAddressVersion">
      <MemberSignature Language="C#" Value="public string PublicIPAddressVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicIPAddressVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAddressVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAddressVersion As String" />
      <MemberSignature Language="F#" Value="member this.PublicIPAddressVersion : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAddressVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAddressVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version der öffentliche IP-Adresse. Mögliche Werte sind: "IPv4" und "IPv6". Folgende Werte sind möglich: "IPv4", "IPv6"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicIPAllocationMethod">
      <MemberSignature Language="C#" Value="public string PublicIPAllocationMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicIPAllocationMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAllocationMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicIPAllocationMethod As String" />
      <MemberSignature Language="F#" Value="member this.PublicIPAllocationMethod : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.PublicIPAllocationMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicIPAllocationMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die öffentliche IP-Zuordnungsmethode. Mögliche Werte sind: "Static" und "Dynamic". Folgende Werte sind möglich: "Static", "Dynamic"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGuid">
      <MemberSignature Language="C#" Value="public string ResourceGuid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGuid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.ResourceGuid" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGuid As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGuid : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.ResourceGuid" />
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
            Ruft ab oder legt die GUID-Eigenschaft, der die öffentliche IP-Adressressource "Ressource".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.PublicIPAddressSku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.PublicIPAddressSku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As PublicIPAddressSku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Network.Models.PublicIPAddressSku with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.PublicIPAddressSku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die öffentliche IP-Adresse SKU.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Zones">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Zones { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Zones" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.PublicIPAddress.Zones" />
      <MemberSignature Language="VB.NET" Value="Public Property Zones As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Zones : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.PublicIPAddress.Zones" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="zones")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder Festlegen einer Liste von Verfügbarkeit Zonen, die angibt, dass sich die IP-Adresse für die Ressource belegt stammen muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>