<Type Name="EffectiveRoute" FullName="Microsoft.Azure.Management.Network.Models.EffectiveRoute">
  <TypeSignature Language="C#" Value="public class EffectiveRoute" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveRoute extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveRoute" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveRoute" />
  <TypeSignature Language="F#" Value="type EffectiveRoute = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a2e9d-101">Effektiven Route</span><span class="sxs-lookup"><span data-stu-id="a2e9d-101">Effective Route</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRoute ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRoute.#ctor" />
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
            <span data-ttu-id="a2e9d-102">Initialisiert eine neue Instanz der EffectiveRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-102">Initializes a new instance of the EffectiveRoute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveRoute (string name = null, string source = null, string state = null, System.Collections.Generic.IList&lt;string&gt; addressPrefix = null, System.Collections.Generic.IList&lt;string&gt; nextHopIpAddress = null, string nextHopType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string source, string state, class System.Collections.Generic.IList`1&lt;string&gt; addressPrefix, class System.Collections.Generic.IList`1&lt;string&gt; nextHopIpAddress, string nextHopType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveRoute.#ctor(System.String,System.String,System.String,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{System.String},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional source As String = null, Optional state As String = null, Optional addressPrefix As IList(Of String) = null, Optional nextHopIpAddress As IList(Of String) = null, Optional nextHopType As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveRoute : string * string * string * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;string&gt; * string -&gt; Microsoft.Azure.Management.Network.Models.EffectiveRoute" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveRoute (name, source, state, addressPrefix, nextHopIpAddress, nextHopType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="source" Type="System.String" />
        <Parameter Name="state" Type="System.String" />
        <Parameter Name="addressPrefix" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextHopIpAddress" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="nextHopType" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a2e9d-103">Der Name des Benutzers definiert Route.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-103">The name of the user defined route.</span></span> <span data-ttu-id="a2e9d-104">Dies ist optional.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-104">This is optional.</span></span></param>
        <param name="source"><span data-ttu-id="a2e9d-105">Der die Route erstellt hat.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-105">Who created the route.</span></span> <span data-ttu-id="a2e9d-106">Mögliche Werte sind: "Unbekannt", "User", "VirtualNetworkGateway" und "Default".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-106">Possible values are: 'Unknown', 'User', 'VirtualNetworkGateway', and 'Default'.</span></span> <span data-ttu-id="a2e9d-107">Folgende Werte sind möglich: "Unbekannt", "User", "VirtualNetworkGateway", "Default"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-107">Possible values include: 'Unknown', 'User', 'VirtualNetworkGateway', 'Default'</span></span></param>
        <param name="state"><span data-ttu-id="a2e9d-108">Der Wert der effektiven Route.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-108">The value of effective route.</span></span> <span data-ttu-id="a2e9d-109">Mögliche Werte sind: "Aktiv" und "Ungültig".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-109">Possible values are: 'Active' and 'Invalid'.</span></span> <span data-ttu-id="a2e9d-110">Folgende Werte sind möglich: "Aktiv", "Ungültig"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-110">Possible values include: 'Active', 'Invalid'</span></span></param>
        <param name="addressPrefix"><span data-ttu-id="a2e9d-111">Die Adresspräfixe für den effektiven Routen in CIDR-Notation.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-111">The address prefixes of the effective routes in CIDR notation.</span></span></param>
        <param name="nextHopIpAddress"><span data-ttu-id="a2e9d-112">Die IP-Adresse des nächsten Hops der effektiven Route.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-112">The IP address of the next hop of the effective route.</span></span></param>
        <param name="nextHopType"><span data-ttu-id="a2e9d-113">Der Azure-Hop-Typ, an den das Paket gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-113">The type of Azure hop the packet should be sent to.</span></span> <span data-ttu-id="a2e9d-114">Mögliche Werte sind: "VirtualNetworkGateway", "VnetLocal", "Internet", "" virtualappliance "und"None".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-114">Possible values are: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', and 'None'.</span></span> <span data-ttu-id="a2e9d-115">Folgende Werte sind möglich: "VirtualNetworkGateway", "VnetLocal", "Internet", "" virtualappliance "", "None"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-115">Possible values include: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', 'None'</span></span></param>
        <summary>
            <span data-ttu-id="a2e9d-116">Initialisiert eine neue Instanz der EffectiveRoute-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-116">Initializes a new instance of the EffectiveRoute class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefix">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AddressPrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.AddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefix As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AddressPrefix : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.AddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addressPrefix")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e9d-117">Ruft ab oder legt die Adresspräfixe, der den effektiven Routen in CIDR-Notation.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-117">Gets or sets the address prefixes of the effective routes in CIDR notation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.Name" />
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
            <span data-ttu-id="a2e9d-118">Ruft ab oder legt den Namen der benutzerdefinierten Route fest.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-118">Gets or sets the name of the user defined route.</span></span> <span data-ttu-id="a2e9d-119">Dies ist optional.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-119">This is optional.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e9d-120">Ruft ab oder legt die IP-Adresse des nächsten Hops der effektiven Route.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-120">Gets or sets the IP address of the next hop of the effective route.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e9d-121">Ruft ab oder legt den Typ des Azure-Hops, die das Paket gesendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-121">Gets or sets the type of Azure hop the packet should be sent to.</span></span>
            <span data-ttu-id="a2e9d-122">Mögliche Werte sind: "VirtualNetworkGateway", "VnetLocal", "Internet", "" virtualappliance "und"None".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-122">Possible values are: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', and 'None'.</span></span> <span data-ttu-id="a2e9d-123">Folgende Werte sind möglich: "VirtualNetworkGateway", "VnetLocal", "Internet", "" virtualappliance "", "None"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-123">Possible values include: 'VirtualNetworkGateway', 'VnetLocal', 'Internet', 'VirtualAppliance', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Source">
      <MemberSignature Language="C#" Value="public string Source { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Source" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.Source" />
      <MemberSignature Language="VB.NET" Value="Public Property Source As String" />
      <MemberSignature Language="F#" Value="member this.Source : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.Source" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="source")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e9d-124">Ruft ab oder legt ihn fest, der die Route erstellt hat.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-124">Gets or sets who created the route.</span></span> <span data-ttu-id="a2e9d-125">Mögliche Werte sind: "Unbekannt", "User", "VirtualNetworkGateway" und "Default".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-125">Possible values are: 'Unknown', 'User', 'VirtualNetworkGateway', and 'Default'.</span></span> <span data-ttu-id="a2e9d-126">Folgende Werte sind möglich: "Unbekannt", "User", "VirtualNetworkGateway", "Default"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-126">Possible values include: 'Unknown', 'User', 'VirtualNetworkGateway', 'Default'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveRoute.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveRoute.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="a2e9d-127">Ruft ab oder legt den Wert der effektiven Route.</span><span class="sxs-lookup"><span data-stu-id="a2e9d-127">Gets or sets the value of effective route.</span></span> <span data-ttu-id="a2e9d-128">Mögliche Werte sind: "Aktiv" und "Ungültig".</span><span class="sxs-lookup"><span data-stu-id="a2e9d-128">Possible values are: 'Active' and 'Invalid'.</span></span> <span data-ttu-id="a2e9d-129">Folgende Werte sind möglich: "Aktiv", "Ungültig"</span><span class="sxs-lookup"><span data-stu-id="a2e9d-129">Possible values include: 'Active', 'Invalid'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>