<Type Name="NGramTokenFilterV2" FullName="Microsoft.Azure.Search.Models.NGramTokenFilterV2">
  <TypeSignature Language="C#" Value="public class NGramTokenFilterV2 : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NGramTokenFilterV2 extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.NGramTokenFilterV2" />
  <TypeSignature Language="VB.NET" Value="Public Class NGramTokenFilterV2&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type NGramTokenFilterV2 = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.NGramTokenFilterV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="dce29-101">N-gramme richtet, der den angegebenen VM-Größe(n) wird generiert.</span><span class="sxs-lookup"><span data-stu-id="dce29-101">Generates n-grams of the given size(s).</span></span> <span data-ttu-id="dce29-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="dce29-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor" />
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
            <span data-ttu-id="dce29-103">Initialisiert eine neue Instanz der NGramTokenFilterV2-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dce29-103">Initializes a new instance of the NGramTokenFilterV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.NGramTokenFilterV2" Usage="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 (name, minGram, maxGram)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxGram" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="dce29-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="dce29-104">The name of the token filter.</span></span> <span data-ttu-id="dce29-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="dce29-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="minGram"><span data-ttu-id="dce29-106">Die Mindestlänge für die n-gramme.</span><span class="sxs-lookup"><span data-stu-id="dce29-106">The minimum n-gram length.</span></span> <span data-ttu-id="dce29-107">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="dce29-107">Default is 1.</span></span>
            <span data-ttu-id="dce29-108">Höchstwert beträgt 300.</span><span class="sxs-lookup"><span data-stu-id="dce29-108">Maximum is 300.</span></span> <span data-ttu-id="dce29-109">Kleiner als der Wert des MaxGram muss sein.</span><span class="sxs-lookup"><span data-stu-id="dce29-109">Must be less than the value of maxGram.</span></span></param>
        <param name="maxGram"><span data-ttu-id="dce29-110">Die maximale Länge von n-gramme.</span><span class="sxs-lookup"><span data-stu-id="dce29-110">The maximum n-gram length.</span></span> <span data-ttu-id="dce29-111">Standard ist 2.</span><span class="sxs-lookup"><span data-stu-id="dce29-111">Default is 2.</span></span>
            <span data-ttu-id="dce29-112">Höchstwert beträgt 300.</span><span class="sxs-lookup"><span data-stu-id="dce29-112">Maximum is 300.</span></span></param>
        <summary>
            <span data-ttu-id="dce29-113">Initialisiert eine neue Instanz der NGramTokenFilterV2-Klasse.</span><span class="sxs-lookup"><span data-stu-id="dce29-113">Initializes a new instance of the NGramTokenFilterV2 class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dce29-114">Ruft ab oder legt die maximale Länge von n-gramme.</span><span class="sxs-lookup"><span data-stu-id="dce29-114">Gets or sets the maximum n-gram length.</span></span> <span data-ttu-id="dce29-115">Standard ist 2.</span><span class="sxs-lookup"><span data-stu-id="dce29-115">Default is 2.</span></span> <span data-ttu-id="dce29-116">Maximal:</span><span class="sxs-lookup"><span data-stu-id="dce29-116">Maximum is</span></span>
            300.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="dce29-117">Ruft ab oder legt die minimale Länge von n-gramme.</span><span class="sxs-lookup"><span data-stu-id="dce29-117">Gets or sets the minimum n-gram length.</span></span> <span data-ttu-id="dce29-118">Der Standardwert ist 1.</span><span class="sxs-lookup"><span data-stu-id="dce29-118">Default is 1.</span></span> <span data-ttu-id="dce29-119">Maximal:</span><span class="sxs-lookup"><span data-stu-id="dce29-119">Maximum is</span></span>
            300. <span data-ttu-id="dce29-120">Kleiner als der Wert des MaxGram muss sein.</span><span class="sxs-lookup"><span data-stu-id="dce29-120">Must be less than the value of maxGram.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="nGramTokenFilterV2.Validate " />
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
            <span data-ttu-id="dce29-121">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="dce29-121">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="dce29-122">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="dce29-122">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>