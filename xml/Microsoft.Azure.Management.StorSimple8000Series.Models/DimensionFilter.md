<Type Name="DimensionFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter">
  <TypeSignature Language="C#" Value="public class DimensionFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DimensionFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class DimensionFilter" />
  <TypeSignature Language="F#" Value="type DimensionFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="93896-101">Der Dimensionsfilter für die.</span><span class="sxs-lookup"><span data-stu-id="93896-101">The dimension filter.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DimensionFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="93896-102">Initialisiert eine neue Instanz der Klasse DimensionFilter an.</span><span class="sxs-lookup"><span data-stu-id="93896-102">Initializes a new instance of the DimensionFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DimensionFilter (string name = null, string values = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string values) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional values As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter : string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter (name, values)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="values" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="93896-103">Gibt den Namen der Dimension an.</span><span class="sxs-lookup"><span data-stu-id="93896-103">Specifies the dimension name.</span></span> <span data-ttu-id="93896-104">Z. B. Clusternetzwerkschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="93896-104">E.g., NetworkInterface.</span></span> <span data-ttu-id="93896-105">Gültige Werte sind diejenigen, die im Aufruf der ListMetricDefinitions in das Feld "Dimensionen" angegeben.</span><span class="sxs-lookup"><span data-stu-id="93896-105">Valid values are the ones specified in the field "dimensions" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="93896-106">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="93896-106">Only 'Equality' operator is supported for this property.</span></span></param>
        <param name="values"><span data-ttu-id="93896-107">Gibt den Dimensionswert.</span><span class="sxs-lookup"><span data-stu-id="93896-107">Specifies the dimension value.</span></span> <span data-ttu-id="93896-108">Z. B. Data0.</span><span class="sxs-lookup"><span data-stu-id="93896-108">E.g., Data0.</span></span>
            <span data-ttu-id="93896-109">Gültige Werte sind diejenigen, die in das Feld "Dimensionen" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="93896-109">Valid values are the ones returned in the field "dimensions" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="93896-110">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="93896-110">Only 'Equality' operator is supported for this property.</span></span></param>
        <summary>
            <span data-ttu-id="93896-111">Initialisiert eine neue Instanz der Klasse DimensionFilter an.</span><span class="sxs-lookup"><span data-stu-id="93896-111">Initializes a new instance of the DimensionFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
            <span data-ttu-id="93896-112">Ruft ab oder legt gibt den Namen der Dimension an.</span><span class="sxs-lookup"><span data-stu-id="93896-112">Gets or sets specifies the dimension name.</span></span> <span data-ttu-id="93896-113">Z. B. Clusternetzwerkschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="93896-113">E.g., NetworkInterface.</span></span>
            <span data-ttu-id="93896-114">Gültige Werte sind diejenigen, die im Aufruf der ListMetricDefinitions in das Feld "Dimensionen" angegeben.</span><span class="sxs-lookup"><span data-stu-id="93896-114">Valid values are the ones specified in the field "dimensions" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="93896-115">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="93896-115">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Values">
      <MemberSignature Language="C#" Value="public string Values { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Values" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Values" />
      <MemberSignature Language="VB.NET" Value="Public Property Values As String" />
      <MemberSignature Language="F#" Value="member this.Values : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter.Values" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="values")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="93896-116">Ruft ab oder legt gibt den Dimensionswert an.</span><span class="sxs-lookup"><span data-stu-id="93896-116">Gets or sets specifies the dimension value.</span></span> <span data-ttu-id="93896-117">Z. B. Data0.</span><span class="sxs-lookup"><span data-stu-id="93896-117">E.g., Data0.</span></span> <span data-ttu-id="93896-118">Gültige Werte sind diejenigen, die in das Feld "Dimensionen" im Aufruf ListMetricDefinitions zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="93896-118">Valid values are the ones returned in the field "dimensions" in the ListMetricDefinitions call.</span></span> <span data-ttu-id="93896-119">Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</span><span class="sxs-lookup"><span data-stu-id="93896-119">Only 'Equality' operator is supported for this property.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>