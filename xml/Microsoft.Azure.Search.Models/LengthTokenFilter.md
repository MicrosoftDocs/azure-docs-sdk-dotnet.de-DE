<Type Name="LengthTokenFilter" FullName="Microsoft.Azure.Search.Models.LengthTokenFilter">
  <TypeSignature Language="C#" Value="public class LengthTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LengthTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.LengthTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class LengthTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type LengthTokenFilter = class&#xA;    inherit TokenFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.TokenFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.LengthTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="102ba-101">Entfernt ein Wort, die zu lang oder zu kurz sind.</span><span class="sxs-lookup"><span data-stu-id="102ba-101">Removes words that are too long or too short.</span></span> <span data-ttu-id="102ba-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="102ba-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/LengthFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LengthTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LengthTokenFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="102ba-103">Initialisiert eine neue Instanz der LengthTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="102ba-103">Initializes a new instance of the LengthTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LengthTokenFilter (string name, Nullable&lt;int&gt; min = null, Nullable&lt;int&gt; max = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; min, valuetype System.Nullable`1&lt;int32&gt; max) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LengthTokenFilter.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional min As Nullable(Of Integer) = null, Optional max As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.LengthTokenFilter : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.LengthTokenFilter" Usage="new Microsoft.Azure.Search.Models.LengthTokenFilter (name, min, max)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="min" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="max" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="102ba-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="102ba-104">The name of the token filter.</span></span> <span data-ttu-id="102ba-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="102ba-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="min"><span data-ttu-id="102ba-106">Die minimale Länge in Zeichen.</span><span class="sxs-lookup"><span data-stu-id="102ba-106">The minimum length in characters.</span></span> <span data-ttu-id="102ba-107">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="102ba-107">Default is 0.</span></span>
            <span data-ttu-id="102ba-108">Höchstwert beträgt 300.</span><span class="sxs-lookup"><span data-stu-id="102ba-108">Maximum is 300.</span></span> <span data-ttu-id="102ba-109">Kleiner als der Wert des Max muss sein.</span><span class="sxs-lookup"><span data-stu-id="102ba-109">Must be less than the value of max.</span></span></param>
        <param name="max"><span data-ttu-id="102ba-110">Die maximale Länge in Zeichen.</span><span class="sxs-lookup"><span data-stu-id="102ba-110">The maximum length in characters.</span></span> <span data-ttu-id="102ba-111">Standard- und ist 300.</span><span class="sxs-lookup"><span data-stu-id="102ba-111">Default and maximum is 300.</span></span></param>
        <summary>
            <span data-ttu-id="102ba-112">Initialisiert eine neue Instanz der LengthTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="102ba-112">Initializes a new instance of the LengthTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Max { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LengthTokenFilter.Max" />
      <MemberSignature Language="VB.NET" Value="Public Property Max As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Max : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LengthTokenFilter.Max" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="max")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="102ba-113">Ruft ab oder legt die maximale Länge in Zeichen.</span><span class="sxs-lookup"><span data-stu-id="102ba-113">Gets or sets the maximum length in characters.</span></span> <span data-ttu-id="102ba-114">Standard- und ist 300.</span><span class="sxs-lookup"><span data-stu-id="102ba-114">Default and maximum is 300.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Min { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.LengthTokenFilter.Min" />
      <MemberSignature Language="VB.NET" Value="Public Property Min As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Min : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.LengthTokenFilter.Min" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="min")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="102ba-115">Ruft ab oder legt die minimale Länge in Zeichen.</span><span class="sxs-lookup"><span data-stu-id="102ba-115">Gets or sets the minimum length in characters.</span></span> <span data-ttu-id="102ba-116">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="102ba-116">Default is 0.</span></span>
            <span data-ttu-id="102ba-117">Höchstwert beträgt 300.</span><span class="sxs-lookup"><span data-stu-id="102ba-117">Maximum is 300.</span></span> <span data-ttu-id="102ba-118">Kleiner als der Wert des Max muss sein.</span><span class="sxs-lookup"><span data-stu-id="102ba-118">Must be less than the value of max.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.LengthTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="lengthTokenFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="102ba-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="102ba-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="102ba-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="102ba-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>