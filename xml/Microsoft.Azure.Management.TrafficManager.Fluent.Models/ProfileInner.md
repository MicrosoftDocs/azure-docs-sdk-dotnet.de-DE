<Type Name="ProfileInner" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner">
  <TypeSignature Language="C#" Value="public class ProfileInner : Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ProfileInner extends Microsoft.Azure.Management.ResourceManager.Fluent.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" />
  <TypeSignature Language="VB.NET" Value="Public Class ProfileInner&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type ProfileInner = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
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
            <span data-ttu-id="f16b9-101">Klasse, die eine Traffic Manager-Profil darstellt.</span><span class="sxs-lookup"><span data-stu-id="f16b9-101">Class representing a Traffic Manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProfileInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-102">Initialisiert eine neue Instanz der ProfileInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f16b9-102">Initializes a new instance of the ProfileInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ProfileInner (string location = null, string id = null, string name = null, string type = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string profileStatus = null, string trafficRoutingMethod = null, Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig dnsConfig = null, Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig monitorConfig = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; endpoints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string location, string id, string name, string type, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string profileStatus, string trafficRoutingMethod, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig dnsConfig, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig monitorConfig, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; endpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig,Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig * Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner" Usage="new Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner (location, id, name, type, tags, profileStatus, trafficRoutingMethod, dnsConfig, monitorConfig, endpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="profileStatus" Type="System.String" />
        <Parameter Name="trafficRoutingMethod" Type="System.String" />
        <Parameter Name="dnsConfig" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig" />
        <Parameter Name="monitorConfig" Type="Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig" />
        <Parameter Name="endpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;" />
      </Parameters>
      <Docs>
        <param name="location">To be added.</param>
        <param name="id">To be added.</param>
        <param name="name">To be added.</param>
        <param name="type">To be added.</param>
        <param name="tags">To be added.</param>
        <param name="profileStatus"><span data-ttu-id="f16b9-103">Ruft ab oder legt den Status der Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="f16b9-103">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="f16b9-104">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="f16b9-104">Possible values are 'Enabled' and 'Disabled'.</span></span></param>
        <param name="trafficRoutingMethod"><span data-ttu-id="f16b9-105">Ruft ab oder legt die datenverkehrrouting-Methode des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f16b9-105">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="f16b9-106">Mögliche Werte sind "Leistung", 'Weighted' oder 'Priority' an.</span><span class="sxs-lookup"><span data-stu-id="f16b9-106">Possible values are 'Performance', 'Weighted', or 'Priority'.</span></span></param>
        <param name="dnsConfig"><span data-ttu-id="f16b9-107">Ruft ab oder legt die DNS-Einstellungen des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f16b9-107">Gets or sets the DNS settings of the Traffic Manager profile.</span></span></param>
        <param name="monitorConfig"><span data-ttu-id="f16b9-108">Ruft ab oder legt die Einstellungen des Traffic Manager-Profils für die endpunktüberwachung.</span><span class="sxs-lookup"><span data-stu-id="f16b9-108">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span></param>
        <param name="endpoints"><span data-ttu-id="f16b9-109">Ruft ab oder legt die Liste der Endpunkte in Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="f16b9-109">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="f16b9-110">Initialisiert eine neue Instanz der ProfileInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="f16b9-110">Initializes a new instance of the ProfileInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig DnsConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig DnsConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.DnsConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsConfig As DnsConfig" />
      <MemberSignature Language="F#" Value="member this.DnsConfig : Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.DnsConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.Models.DnsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-111">Ruft ab oder legt die DNS-Einstellungen des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f16b9-111">Gets or sets the DNS settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As IList(Of EndpointInner)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.EndpointInner&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-112">Ruft ab oder legt die Liste der Endpunkte in Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="f16b9-112">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig MonitorConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig MonitorConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.MonitorConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitorConfig As MonitorConfig" />
      <MemberSignature Language="F#" Value="member this.MonitorConfig : Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.MonitorConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitorConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.Models.MonitorConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-113">Ruft ab oder legt die Einstellungen des Traffic Manager-Profils für die endpunktüberwachung.</span><span class="sxs-lookup"><span data-stu-id="f16b9-113">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileStatus">
      <MemberSignature Language="C#" Value="public string ProfileStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.ProfileStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.ProfileStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.profileStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-114">Ruft ab oder legt den Status der Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="f16b9-114">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="f16b9-115">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="f16b9-115">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public string TrafficRoutingMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficRoutingMethod As String" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.trafficRoutingMethod")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="f16b9-116">Ruft ab oder legt die datenverkehrrouting-Methode des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="f16b9-116">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="f16b9-117">Mögliche Werte sind "Leistung", 'Weighted' oder 'Priority' an.</span><span class="sxs-lookup"><span data-stu-id="f16b9-117">Possible values are 'Performance', 'Weighted', or 'Priority'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>