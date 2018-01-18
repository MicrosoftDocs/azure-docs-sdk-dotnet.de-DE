<Type Name="Profile" FullName="Microsoft.Azure.Management.TrafficManager.Models.Profile">
  <TypeSignature Language="C#" Value="public class Profile : Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Profile extends Microsoft.Azure.Management.TrafficManager.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Models.Profile" />
  <TypeSignature Language="VB.NET" Value="Public Class Profile&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Profile = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.TrafficManager.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="8fef6-101">Klasse, die eine Traffic Manager-Profil darstellt.</span><span class="sxs-lookup"><span data-stu-id="8fef6-101">Class representing a Traffic Manager profile.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8fef6-102">Initialisiert eine neue Instanz der Profil-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fef6-102">Initializes a new instance of the Profile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Profile (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string profileStatus = null, string trafficRoutingMethod = null, Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig = null, Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string profileStatus, string trafficRoutingMethod, class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig dnsConfig, class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig monitorConfig, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; endpoints) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.Models.Profile.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.String,Microsoft.Azure.Management.TrafficManager.Models.DnsConfig,Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig,System.Collections.Generic.IList{Microsoft.Azure.Management.TrafficManager.Models.Endpoint})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.TrafficManager.Models.Profile : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * string * Microsoft.Azure.Management.TrafficManager.Models.DnsConfig * Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; -&gt; Microsoft.Azure.Management.TrafficManager.Models.Profile" Usage="new Microsoft.Azure.Management.TrafficManager.Models.Profile (id, name, type, location, tags, profileStatus, trafficRoutingMethod, dnsConfig, monitorConfig, endpoints)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="profileStatus" Type="System.String" />
        <Parameter Name="trafficRoutingMethod" Type="System.String" />
        <Parameter Name="dnsConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.DnsConfig" />
        <Parameter Name="monitorConfig" Type="Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig" />
        <Parameter Name="endpoints" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="8fef6-103">Ressourcen-Id</span><span class="sxs-lookup"><span data-stu-id="8fef6-103">Resource Id</span></span></param>
        <param name="name"><span data-ttu-id="8fef6-104">Ressourcenname</span><span class="sxs-lookup"><span data-stu-id="8fef6-104">Resource name</span></span></param>
        <param name="type"><span data-ttu-id="8fef6-105">Ressourcentyp</span><span class="sxs-lookup"><span data-stu-id="8fef6-105">Resource type</span></span></param>
        <param name="location"><span data-ttu-id="8fef6-106">Speicherort von Ressourcen</span><span class="sxs-lookup"><span data-stu-id="8fef6-106">Resource location</span></span></param>
        <param name="tags"><span data-ttu-id="8fef6-107">Ressourcentags</span><span class="sxs-lookup"><span data-stu-id="8fef6-107">Resource tags</span></span></param>
        <param name="profileStatus"><span data-ttu-id="8fef6-108">Ruft ab oder legt den Status der Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="8fef6-108">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="8fef6-109">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="8fef6-109">Possible values are 'Enabled' and 'Disabled'.</span></span></param>
        <param name="trafficRoutingMethod"><span data-ttu-id="8fef6-110">Ruft ab oder legt die datenverkehrrouting-Methode des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="8fef6-110">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="8fef6-111">Mögliche Werte sind "Leistung", 'Weighted', 'Priority' oder "Geografisch".</span><span class="sxs-lookup"><span data-stu-id="8fef6-111">Possible values are 'Performance', 'Weighted', 'Priority' or 'Geographic'.</span></span></param>
        <param name="dnsConfig"><span data-ttu-id="8fef6-112">Ruft ab oder legt die DNS-Einstellungen des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="8fef6-112">Gets or sets the DNS settings of the Traffic Manager profile.</span></span></param>
        <param name="monitorConfig"><span data-ttu-id="8fef6-113">Ruft ab oder legt die Einstellungen des Traffic Manager-Profils für die endpunktüberwachung.</span><span class="sxs-lookup"><span data-stu-id="8fef6-113">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span></param>
        <param name="endpoints"><span data-ttu-id="8fef6-114">Ruft ab oder legt die Liste der Endpunkte in Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="8fef6-114">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span></param>
        <summary>
            <span data-ttu-id="8fef6-115">Initialisiert eine neue Instanz der Profil-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8fef6-115">Initializes a new instance of the Profile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.DnsConfig DnsConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsConfig As DnsConfig" />
      <MemberSignature Language="F#" Value="member this.DnsConfig : Microsoft.Azure.Management.TrafficManager.Models.DnsConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.DnsConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.DnsConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8fef6-116">Ruft ab oder legt die DNS-Einstellungen des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="8fef6-116">Gets or sets the DNS settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Endpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; Endpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberSignature Language="VB.NET" Value="Public Property Endpoints As IList(Of Endpoint)" />
      <MemberSignature Language="F#" Value="member this.Endpoints : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt; with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.Endpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endpoints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.TrafficManager.Models.Endpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8fef6-117">Ruft ab oder legt die Liste der Endpunkte in Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="8fef6-117">Gets or sets the list of endpoints in the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig MonitorConfig" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberSignature Language="VB.NET" Value="Public Property MonitorConfig As MonitorConfig" />
      <MemberSignature Language="F#" Value="member this.MonitorConfig : Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.MonitorConfig" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.monitorConfig")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.MonitorConfig</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8fef6-118">Ruft ab oder legt die Einstellungen des Traffic Manager-Profils für die endpunktüberwachung.</span><span class="sxs-lookup"><span data-stu-id="8fef6-118">Gets or sets the endpoint monitoring settings of the Traffic Manager profile.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProfileStatus">
      <MemberSignature Language="C#" Value="public string ProfileStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProfileStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ProfileStatus As String" />
      <MemberSignature Language="F#" Value="member this.ProfileStatus : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.ProfileStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8fef6-119">Ruft ab oder legt den Status der Traffic Manager-Profil fest.</span><span class="sxs-lookup"><span data-stu-id="8fef6-119">Gets or sets the status of the Traffic Manager profile.</span></span>  <span data-ttu-id="8fef6-120">Mögliche Werte sind "Enabled" und "Deaktiviert".</span><span class="sxs-lookup"><span data-stu-id="8fef6-120">Possible values are 'Enabled' and 'Disabled'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public string TrafficRoutingMethod { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public Property TrafficRoutingMethod As String" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : string with get, set" Usage="Microsoft.Azure.Management.TrafficManager.Models.Profile.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="8fef6-121">Ruft ab oder legt die datenverkehrrouting-Methode des Traffic Manager-Profils.</span><span class="sxs-lookup"><span data-stu-id="8fef6-121">Gets or sets the traffic routing method of the Traffic Manager profile.</span></span>  <span data-ttu-id="8fef6-122">Mögliche Werte sind "Leistung", 'Weighted', 'Priority' oder "Geografisch".</span><span class="sxs-lookup"><span data-stu-id="8fef6-122">Possible values are 'Performance', 'Weighted', 'Priority' or 'Geographic'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>