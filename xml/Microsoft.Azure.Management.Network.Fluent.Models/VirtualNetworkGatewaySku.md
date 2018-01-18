<Type Name="VirtualNetworkGatewaySku" FullName="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku">
  <TypeSignature Language="C#" Value="public class VirtualNetworkGatewaySku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VirtualNetworkGatewaySku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku" />
  <TypeSignature Language="VB.NET" Value="Public Class VirtualNetworkGatewaySku" />
  <TypeSignature Language="F#" Value="type VirtualNetworkGatewaySku = class" />
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
            <span data-ttu-id="d7624-101">VirtualNetworkGatewaySku-details</span><span class="sxs-lookup"><span data-stu-id="d7624-101">VirtualNetworkGatewaySku details</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewaySku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7624-102">Initialisiert eine neue Instanz der VirtualNetworkGatewaySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d7624-102">Initializes a new instance of the VirtualNetworkGatewaySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VirtualNetworkGatewaySku (string name = null, string tier = null, Nullable&lt;int&gt; capacity = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, valuetype System.Nullable`1&lt;int32&gt; capacity) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.#ctor(System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional tier As String = null, Optional capacity As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku : string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku (name, tier, capacity)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7624-103">Gateway-SKU-Name.</span><span class="sxs-lookup"><span data-stu-id="d7624-103">Gateway SKU name.</span></span> <span data-ttu-id="d7624-104">Mögliche Werte sind: 'Basic', 'HighPerformance', 'Standard' und 'UltraPerformance'.</span><span class="sxs-lookup"><span data-stu-id="d7624-104">Possible values are: 'Basic', 'HighPerformance','Standard', and 'UltraPerformance'.</span></span> <span data-ttu-id="d7624-105">Folgende Werte sind möglich: "Basic", "HighPerformance", "Standard", "UltraPerformance"</span><span class="sxs-lookup"><span data-stu-id="d7624-105">Possible values include: 'Basic', 'HighPerformance', 'Standard', 'UltraPerformance'</span></span></param>
        <param name="tier"><span data-ttu-id="d7624-106">Gateway-SKU-Tarif.</span><span class="sxs-lookup"><span data-stu-id="d7624-106">Gateway SKU tier.</span></span> <span data-ttu-id="d7624-107">Mögliche Werte sind: 'Basic', 'HighPerformance', 'Standard' und 'UltraPerformance'.</span><span class="sxs-lookup"><span data-stu-id="d7624-107">Possible values are: 'Basic', 'HighPerformance','Standard', and 'UltraPerformance'.</span></span> <span data-ttu-id="d7624-108">Folgende Werte sind möglich: "Basic", "HighPerformance", "Standard", "UltraPerformance"</span><span class="sxs-lookup"><span data-stu-id="d7624-108">Possible values include: 'Basic', 'HighPerformance', 'Standard', 'UltraPerformance'</span></span></param>
        <param name="capacity"><span data-ttu-id="d7624-109">Die Kapazität.</span><span class="sxs-lookup"><span data-stu-id="d7624-109">The capacity.</span></span></param>
        <summary>
            <span data-ttu-id="d7624-110">Initialisiert eine neue Instanz der VirtualNetworkGatewaySku-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d7624-110">Initializes a new instance of the VirtualNetworkGatewaySku class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7624-111">Ruft ab oder legt die Kapazität fest.</span><span class="sxs-lookup"><span data-stu-id="d7624-111">Gets or sets the capacity.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Name" />
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
            <span data-ttu-id="d7624-112">Ruft ab, oder legt ihn fest Gateway-SKU-Name.</span><span class="sxs-lookup"><span data-stu-id="d7624-112">Gets or sets gateway SKU name.</span></span> <span data-ttu-id="d7624-113">Mögliche Werte sind: 'Basic', 'HighPerformance', 'Standard' und 'UltraPerformance'.</span><span class="sxs-lookup"><span data-stu-id="d7624-113">Possible values are: 'Basic', 'HighPerformance','Standard', and 'UltraPerformance'.</span></span> <span data-ttu-id="d7624-114">Folgende Werte sind möglich: "Basic", "HighPerformance", "Standard", "UltraPerformance"</span><span class="sxs-lookup"><span data-stu-id="d7624-114">Possible values include: 'Basic', 'HighPerformance', 'Standard', 'UltraPerformance'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.VirtualNetworkGatewaySku.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tier")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d7624-115">Ruft ab, oder legt ihn fest Gateway-SKU-Tarif.</span><span class="sxs-lookup"><span data-stu-id="d7624-115">Gets or sets gateway SKU tier.</span></span> <span data-ttu-id="d7624-116">Mögliche Werte sind: 'Basic', 'HighPerformance', 'Standard' und 'UltraPerformance'.</span><span class="sxs-lookup"><span data-stu-id="d7624-116">Possible values are: 'Basic', 'HighPerformance','Standard', and 'UltraPerformance'.</span></span> <span data-ttu-id="d7624-117">Folgende Werte sind möglich: "Basic", "HighPerformance", "Standard", "UltraPerformance"</span><span class="sxs-lookup"><span data-stu-id="d7624-117">Possible values include: 'Basic', 'HighPerformance', 'Standard', 'UltraPerformance'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>