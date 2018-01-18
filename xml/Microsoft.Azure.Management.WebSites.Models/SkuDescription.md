<Type Name="SkuDescription" FullName="Microsoft.Azure.Management.WebSites.Models.SkuDescription">
  <TypeSignature Language="C#" Value="public class SkuDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SkuDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.SkuDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class SkuDescription" />
  <TypeSignature Language="F#" Value="type SkuDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c4d31-101">Beschreibung von einer SKU für eine skalierbare Ressource.</span><span class="sxs-lookup"><span data-stu-id="c4d31-101">Description of a SKU for a scalable resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-102">Initialisiert eine neue Instanz der SkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4d31-102">Initializes a new instance of the SkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SkuDescription (string name = null, string tier = null, string size = null, string family = null, Nullable&lt;int&gt; capacity = null, Microsoft.Azure.Management.WebSites.Models.SkuCapacity skuCapacity = null, System.Collections.Generic.IList&lt;string&gt; locations = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; capabilities = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string tier, string size, string family, valuetype System.Nullable`1&lt;int32&gt; capacity, class Microsoft.Azure.Management.WebSites.Models.SkuCapacity skuCapacity, class System.Collections.Generic.IList`1&lt;string&gt; locations, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt; capabilities) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.SkuDescription.#ctor(System.String,System.String,System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Management.WebSites.Models.SkuCapacity,System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Management.WebSites.Models.Capability})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.SkuDescription : string * string * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Management.WebSites.Models.SkuCapacity * System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; -&gt; Microsoft.Azure.Management.WebSites.Models.SkuDescription" Usage="new Microsoft.Azure.Management.WebSites.Models.SkuDescription (name, tier, size, family, capacity, skuCapacity, locations, capabilities)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tier" Type="System.String" />
        <Parameter Name="size" Type="System.String" />
        <Parameter Name="family" Type="System.String" />
        <Parameter Name="capacity" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="skuCapacity" Type="Microsoft.Azure.Management.WebSites.Models.SkuCapacity" />
        <Parameter Name="locations" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="capabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c4d31-103">Der Name der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-103">Name of the resource SKU.</span></span></param>
        <param name="tier"><span data-ttu-id="c4d31-104">Die Dienstebene der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-104">Service tier of the resource SKU.</span></span></param>
        <param name="size"><span data-ttu-id="c4d31-105">Größenbezeichner der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-105">Size specifier of the resource SKU.</span></span></param>
        <param name="family"><span data-ttu-id="c4d31-106">Familie Code für die SKU-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c4d31-106">Family code of the resource SKU.</span></span></param>
        <param name="capacity"><span data-ttu-id="c4d31-107">Aktuelle Anzahl der Instanzen, die auf die Ressource zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="c4d31-107">Current number of instances assigned to the resource.</span></span></param>
        <param name="skuCapacity"><span data-ttu-id="c4d31-108">Min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-108">Min, max, and default scale values of the SKU.</span></span></param>
        <param name="locations"><span data-ttu-id="c4d31-109">Die Speicherorte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-109">Locations of the SKU.</span></span></param>
        <param name="capabilities"><span data-ttu-id="c4d31-110">Funktionen von der SKU, z. B. Traffic Manager aktiviert ist?</span><span class="sxs-lookup"><span data-stu-id="c4d31-110">Capabilities of the SKU, e.g., is traffic manager enabled?</span></span></param>
        <summary>
            <span data-ttu-id="c4d31-111">Initialisiert eine neue Instanz der SkuDescription-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c4d31-111">Initializes a new instance of the SkuDescription class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; Capabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.WebSites.Models.Capability&gt; Capabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Capabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property Capabilities As IList(Of Capability)" />
      <MemberSignature Language="F#" Value="member this.Capabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Capabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="capabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.WebSites.Models.Capability&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-112">Ruft ab oder legt Funktionen der SKU, z. B., ist Traffic Manager aktiviert?</span><span class="sxs-lookup"><span data-stu-id="c4d31-112">Gets or sets capabilities of the SKU, e.g., is traffic manager enabled?</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Capacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public Property Capacity As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Capacity : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4d31-113">Ruft ab oder legt die aktuelle Anzahl der Instanzen, die auf die Ressource zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="c4d31-113">Gets or sets current number of instances assigned to the resource.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Family">
      <MemberSignature Language="C#" Value="public string Family { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Family" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Family" />
      <MemberSignature Language="VB.NET" Value="Public Property Family As String" />
      <MemberSignature Language="F#" Value="member this.Family : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Family" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="family")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-114">Ruft ab, oder legt ihn fest Familie Code für die SKU-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c4d31-114">Gets or sets family code of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Locations">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Locations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Locations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Locations" />
      <MemberSignature Language="VB.NET" Value="Public Property Locations As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Locations : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Locations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-115">Ruft ab oder legt die Speicherorte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-115">Gets or sets locations of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4d31-116">Ruft ab oder legt den Namen der Ressource SKU fest.</span><span class="sxs-lookup"><span data-stu-id="c4d31-116">Gets or sets name of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public string Size { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Size" />
      <MemberSignature Language="VB.NET" Value="Public Property Size As String" />
      <MemberSignature Language="F#" Value="member this.Size : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="size")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-117">Ruft ab, oder legt ihn fest Größenbezeichner der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-117">Gets or sets size specifier of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SkuCapacity">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.WebSites.Models.SkuCapacity SkuCapacity { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.WebSites.Models.SkuCapacity SkuCapacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.SkuCapacity" />
      <MemberSignature Language="VB.NET" Value="Public Property SkuCapacity As SkuCapacity" />
      <MemberSignature Language="F#" Value="member this.SkuCapacity : Microsoft.Azure.Management.WebSites.Models.SkuCapacity with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.SkuCapacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="skuCapacity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.WebSites.Models.SkuCapacity</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c4d31-118">Ruft ab, oder legt sie fest, min, Max und Skalierung Standardwerte der SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-118">Gets or sets min, max, and default scale values of the SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tier">
      <MemberSignature Language="C#" Value="public string Tier { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Tier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.SkuDescription.Tier" />
      <MemberSignature Language="VB.NET" Value="Public Property Tier As String" />
      <MemberSignature Language="F#" Value="member this.Tier : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.SkuDescription.Tier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c4d31-119">Ruft ab, oder legt ihn fest-Dienstebene der Ressource SKU.</span><span class="sxs-lookup"><span data-stu-id="c4d31-119">Gets or sets service tier of the resource SKU.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>