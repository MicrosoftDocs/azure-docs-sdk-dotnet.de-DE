<Type Name="NextHopResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner">
  <TypeSignature Language="C#" Value="public class NextHopResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NextHopResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class NextHopResultInner" />
  <TypeSignature Language="F#" Value="type NextHopResultInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12be8-101">Die Informationen zum nächsten Hop von den angegebenen virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="12be8-101">The information about next hop from the specified VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="12be8-102">Initialisiert eine neue Instanz der NextHopResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12be8-102">Initializes a new instance of the NextHopResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NextHopResultInner (string nextHopType = null, string nextHopIpAddress = null, string routeTableId = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string nextHopType, string nextHopIpAddress, string routeTableId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional nextHopType As String = null, Optional nextHopIpAddress As String = null, Optional routeTableId As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner : string * string * string -&gt; Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner (nextHopType, nextHopIpAddress, routeTableId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextHopType" Type="System.String" />
        <Parameter Name="nextHopIpAddress" Type="System.String" />
        <Parameter Name="routeTableId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nextHopType"><span data-ttu-id="12be8-103">Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="12be8-103">Next hop type.</span></span> <span data-ttu-id="12be8-104">Folgende Werte sind möglich: "Internet", "virtualappliance" "", "VirtualNetworkGateway", "VnetLocal", "HyperNetGateway", "None"</span><span class="sxs-lookup"><span data-stu-id="12be8-104">Possible values include: 'Internet', 'VirtualAppliance', 'VirtualNetworkGateway', 'VnetLocal', 'HyperNetGateway', 'None'</span></span></param>
        <param name="nextHopIpAddress"><span data-ttu-id="12be8-105">IP-Adresse des nächsten Abschnitts</span><span class="sxs-lookup"><span data-stu-id="12be8-105">Next hop IP Address</span></span></param>
        <param name="routeTableId"><span data-ttu-id="12be8-106">Der Ressourcenbezeichner für die Routentabelle verknüpft sind, mit der Route, die zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="12be8-106">The resource identifier for the route table associated with the route being returned.</span></span> <span data-ttu-id="12be8-107">Wenn die Route, die zurückgegeben wird nicht für jeden Benutzer, Routen erstellt wird, wird dieses Feld die Zeichenfolge 'System Route' sein.</span><span class="sxs-lookup"><span data-stu-id="12be8-107">If the route being returned does not correspond to any user created routes then this field will be the string 'System Route'.</span></span></param>
        <summary>
            <span data-ttu-id="12be8-108">Initialisiert eine neue Instanz der NextHopResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="12be8-108">Initializes a new instance of the NextHopResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopIpAddress">
      <MemberSignature Language="C#" Value="public string NextHopIpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopIpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopIpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopIpAddress As String" />
      <MemberSignature Language="F#" Value="member this.NextHopIpAddress : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopIpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextHopIpAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12be8-109">Ruft ab oder legt die nächsten Hop IP-Adresse</span><span class="sxs-lookup"><span data-stu-id="12be8-109">Gets or sets next hop IP Address</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NextHopType">
      <MemberSignature Language="C#" Value="public string NextHopType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NextHopType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopType" />
      <MemberSignature Language="VB.NET" Value="Public Property NextHopType As String" />
      <MemberSignature Language="F#" Value="member this.NextHopType : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.NextHopType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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
            <span data-ttu-id="12be8-110">Ruft ab oder legt der Typ des nächsten Hops.</span><span class="sxs-lookup"><span data-stu-id="12be8-110">Gets or sets next hop type.</span></span> <span data-ttu-id="12be8-111">Folgende Werte sind möglich: "Internet", "virtualappliance" "", "VirtualNetworkGateway", "VnetLocal", "HyperNetGateway", "None"</span><span class="sxs-lookup"><span data-stu-id="12be8-111">Possible values include: 'Internet', 'VirtualAppliance', 'VirtualNetworkGateway', 'VnetLocal', 'HyperNetGateway', 'None'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RouteTableId">
      <MemberSignature Language="C#" Value="public string RouteTableId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RouteTableId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.RouteTableId" />
      <MemberSignature Language="VB.NET" Value="Public Property RouteTableId As String" />
      <MemberSignature Language="F#" Value="member this.RouteTableId : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.NextHopResultInner.RouteTableId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="routeTableId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="12be8-112">Abrufen oder festlegen den Ressourcenbezeichner für die Routentabelle verknüpft sind, mit der Route, die zurückgegeben wird.</span><span class="sxs-lookup"><span data-stu-id="12be8-112">Gets or sets the resource identifier for the route table associated with the route being returned.</span></span> <span data-ttu-id="12be8-113">Wenn die Route, die zurückgegeben wird nicht für jeden Benutzer, Routen erstellt wird, wird dieses Feld die Zeichenfolge 'System Route' sein.</span><span class="sxs-lookup"><span data-stu-id="12be8-113">If the route being returned does not correspond to any user created routes then this field will be the string 'System Route'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>