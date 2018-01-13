<Type Name="ConfigureDeviceRequest" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest">
  <TypeSignature Language="C#" Value="public class ConfigureDeviceRequest : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ConfigureDeviceRequest extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ConfigureDeviceRequest&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type ConfigureDeviceRequest = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="bbf5a-101">Die obligatorischen Gerät konfigurationsanforderung.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-101">The mandatory device configuration request.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigureDeviceRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-102">Initialisiert eine neue Instanz der ConfigureDeviceRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-102">Initializes a new instance of the ConfigureDeviceRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ConfigureDeviceRequest (string friendlyName, string currentDeviceName, string timeZone, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings dnsSettings = null, Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings networkInterfaceData0Settings = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string friendlyName, string currentDeviceName, string timeZone, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, class Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings dnsSettings, class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings networkInterfaceData0Settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings,Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest : string * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings * Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest (friendlyName, currentDeviceName, timeZone, id, name, type, kind, dnsSettings, networkInterfaceData0Settings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="friendlyName" Type="System.String" />
        <Parameter Name="currentDeviceName" Type="System.String" />
        <Parameter Name="timeZone" Type="System.String" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="dnsSettings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings" />
        <Parameter Name="networkInterfaceData0Settings" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings" />
      </Parameters>
      <Docs>
        <param name="friendlyName"><span data-ttu-id="bbf5a-103">Der Anzeigename für das Gerät.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-103">The friendly name for the device.</span></span></param>
        <param name="currentDeviceName"><span data-ttu-id="bbf5a-104">Der aktuelle Name des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-104">The current name of the device.</span></span></param>
        <param name="timeZone"><span data-ttu-id="bbf5a-105">Die Zeitzone des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-105">The device time zone.</span></span> <span data-ttu-id="bbf5a-106">Für z. B.: "Pacific Standard Time"</span><span class="sxs-lookup"><span data-stu-id="bbf5a-106">For eg: "Pacific Standard Time"</span></span></param>
        <param name="id"><span data-ttu-id="bbf5a-107">Die Pfad-ID, die das Objekt eindeutig identifiziert.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-107">The path ID that uniquely identifies the object.</span></span></param>
        <param name="name"><span data-ttu-id="bbf5a-108">Der Name des Objekts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-108">The name of the object.</span></span></param>
        <param name="type"><span data-ttu-id="bbf5a-109">Der hierarchische Typ des Objekts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-109">The hierarchical type of the object.</span></span></param>
        <param name="kind"><span data-ttu-id="bbf5a-110">Die Art des Objekts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-110">The Kind of the object.</span></span> <span data-ttu-id="bbf5a-111">Derzeit wird nur Series8000 wird unterstützt.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-111">Currently only Series8000 is supported.</span></span> <span data-ttu-id="bbf5a-112">Folgende Werte sind möglich: "Series8000"</span><span class="sxs-lookup"><span data-stu-id="bbf5a-112">Possible values include: 'Series8000'</span></span></param>
        <param name="dnsSettings"><span data-ttu-id="bbf5a-113">Der sekundäre DNS-Einstellungen des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-113">The secondary DNS Settings of the device.</span></span></param>
        <param name="networkInterfaceData0Settings"><span data-ttu-id="bbf5a-114">Die "Data 0" Karte netzwerkschnittstelleneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-114">The 'Data 0' network interface card settings.</span></span></param>
        <summary>
            <span data-ttu-id="bbf5a-115">Initialisiert eine neue Instanz der ConfigureDeviceRequest-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-115">Initializes a new instance of the ConfigureDeviceRequest class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDeviceName">
      <MemberSignature Language="C#" Value="public string CurrentDeviceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentDeviceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.CurrentDeviceName" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentDeviceName As String" />
      <MemberSignature Language="F#" Value="member this.CurrentDeviceName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.CurrentDeviceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDeviceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-116">Ruft ab oder legt den aktuellen Namen des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-116">Gets or sets the current name of the device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings DnsSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings DnsSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.DnsSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property DnsSettings As SecondaryDNSSettings" />
      <MemberSignature Language="F#" Value="member this.DnsSettings : Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.DnsSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dnsSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SecondaryDNSSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-117">Abrufen oder Festlegen der sekundäre DNS-Einstellungen des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-117">Gets or sets the secondary DNS Settings of the device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.FriendlyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.friendlyName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-118">Ruft ab oder legt den Anzeigenamen für das Gerät.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-118">Gets or sets the friendly name for the device.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceData0Settings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings NetworkInterfaceData0Settings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings NetworkInterfaceData0Settings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.NetworkInterfaceData0Settings" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaceData0Settings As NetworkInterfaceData0Settings" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceData0Settings : Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.NetworkInterfaceData0Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkInterfaceData0Settings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.NetworkInterfaceData0Settings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-119">Ruft ab oder legt die "Data 0" Karte netzwerkschnittstelleneinstellungen.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-119">Gets or sets the 'Data 0' network interface card settings.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeZone">
      <MemberSignature Language="C#" Value="public string TimeZone { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.TimeZone" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeZone As String" />
      <MemberSignature Language="F#" Value="member this.TimeZone : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.TimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeZone")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-120">Ruft ab oder legt die Zeitzone des Geräts.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-120">Gets or sets the device time zone.</span></span> <span data-ttu-id="bbf5a-121">Für z. B.: "Pacific Standard Time"</span><span class="sxs-lookup"><span data-stu-id="bbf5a-121">For eg: "Pacific Standard Time"</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.ConfigureDeviceRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="configureDeviceRequest.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="bbf5a-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="bbf5a-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="bbf5a-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="bbf5a-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>