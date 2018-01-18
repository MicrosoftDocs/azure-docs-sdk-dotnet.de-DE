<Type Name="BgpServiceCommunity" FullName="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity">
  <TypeSignature Language="C#" Value="public class BgpServiceCommunity : Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BgpServiceCommunity extends Microsoft.Azure.Management.Network.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity" />
  <TypeSignature Language="VB.NET" Value="Public Class BgpServiceCommunity&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type BgpServiceCommunity = class&#xA;    inherit Resource" />
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
            <span data-ttu-id="bcccc-101">Community-Diensteigenschaften.</span><span class="sxs-lookup"><span data-stu-id="bcccc-101">Service Community Properties.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpServiceCommunity ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.#ctor" />
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
            <span data-ttu-id="bcccc-102">Initialisiert eine neue Instanz der BgpServiceCommunity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bcccc-102">Initializes a new instance of the BgpServiceCommunity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BgpServiceCommunity (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string serviceName = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; bgpCommunities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string serviceName, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; bgpCommunities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.BGPCommunity})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional name As String = null, Optional type As String = null, Optional location As String = null, Optional tags As IDictionary(Of String, String) = null, Optional serviceName As String = null, Optional bgpCommunities As IList(Of BGPCommunity) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.BgpServiceCommunity : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; -&gt; Microsoft.Azure.Management.Network.Models.BgpServiceCommunity" Usage="new Microsoft.Azure.Management.Network.Models.BgpServiceCommunity (id, name, type, location, tags, serviceName, bgpCommunities)" />
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
        <Parameter Name="serviceName" Type="System.String" />
        <Parameter Name="bgpCommunities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="bcccc-103">Ressourcen-ID</span><span class="sxs-lookup"><span data-stu-id="bcccc-103">Resource ID.</span></span></param>
        <param name="name"><span data-ttu-id="bcccc-104">Name der Ressource.</span><span class="sxs-lookup"><span data-stu-id="bcccc-104">Resource name.</span></span></param>
        <param name="type"><span data-ttu-id="bcccc-105">Der Ressourcentyp.</span><span class="sxs-lookup"><span data-stu-id="bcccc-105">Resource type.</span></span></param>
        <param name="location"><span data-ttu-id="bcccc-106">Der Ressourcenspeicherort.</span><span class="sxs-lookup"><span data-stu-id="bcccc-106">Resource location.</span></span></param>
        <param name="tags"><span data-ttu-id="bcccc-107">Ressourcentags.</span><span class="sxs-lookup"><span data-stu-id="bcccc-107">Resource tags.</span></span></param>
        <param name="serviceName"><span data-ttu-id="bcccc-108">Der Name des Bgp-Community.</span><span class="sxs-lookup"><span data-stu-id="bcccc-108">The name of the bgp community.</span></span> <span data-ttu-id="bcccc-109">z. B. Skype.</span><span class="sxs-lookup"><span data-stu-id="bcccc-109">e.g. Skype.</span></span></param>
        <param name="bgpCommunities"><span data-ttu-id="bcccc-110">Ruft eine Liste der Bgp-Communitys.</span><span class="sxs-lookup"><span data-stu-id="bcccc-110">Get a list of bgp communities.</span></span></param>
        <summary>
            <span data-ttu-id="bcccc-111">Initialisiert eine neue Instanz der BgpServiceCommunity-Klasse.</span><span class="sxs-lookup"><span data-stu-id="bcccc-111">Initializes a new instance of the BgpServiceCommunity class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BgpCommunities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; BgpCommunities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; BgpCommunities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.BgpCommunities" />
      <MemberSignature Language="VB.NET" Value="Public Property BgpCommunities As IList(Of BGPCommunity)" />
      <MemberSignature Language="F#" Value="member this.BgpCommunities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.BgpCommunities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.bgpCommunities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.BGPCommunity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcccc-112">Erhalten eine Liste der Bgp-Communitys, ruft ab oder legt ihn fest.</span><span class="sxs-lookup"><span data-stu-id="bcccc-112">Gets or sets get a list of bgp communities.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public string ServiceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceName : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.BgpServiceCommunity.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.serviceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="bcccc-113">Ruft ab oder legt den Namen der Bgp-Community.</span><span class="sxs-lookup"><span data-stu-id="bcccc-113">Gets or sets the name of the bgp community.</span></span> <span data-ttu-id="bcccc-114">z. B. Skype.</span><span class="sxs-lookup"><span data-stu-id="bcccc-114">e.g. Skype.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>