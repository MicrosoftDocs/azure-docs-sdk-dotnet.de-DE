<Type Name="CommonGramTokenFilter" FullName="Microsoft.Azure.Search.Models.CommonGramTokenFilter">
  <TypeSignature Language="C#" Value="public class CommonGramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CommonGramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CommonGramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CommonGramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type CommonGramTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CommonGramTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="935f7-101">Erstellen Sie digramme für häufig auftretende Begriffe beim indizieren.</span><span class="sxs-lookup"><span data-stu-id="935f7-101">Construct bigrams for frequently occurring terms while indexing.</span></span> <span data-ttu-id="935f7-102">Einzelne Ausdrücke sind, weiterhin mit digramme Überlagerung indiziert.</span><span class="sxs-lookup"><span data-stu-id="935f7-102">Single terms are still indexed too, with bigrams overlaid.</span></span> <span data-ttu-id="935f7-103">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="935f7-103">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/commongrams/CommonGramsFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommonGramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.#ctor" />
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
            <span data-ttu-id="935f7-104">Initialisiert eine neue Instanz der CommonGramTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="935f7-104">Initializes a new instance of the CommonGramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CommonGramTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; commonWords, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; useQueryMode = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; commonWords, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; useQueryMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, commonWords As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null, Optional useQueryMode As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CommonGramTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.CommonGramTokenFilter" Usage="new Microsoft.Azure.Search.Models.CommonGramTokenFilter (name, commonWords, ignoreCase, useQueryMode)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="commonWords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="useQueryMode" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="935f7-105">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="935f7-105">The name of the token filter.</span></span> <span data-ttu-id="935f7-106">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="935f7-106">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="commonWords"><span data-ttu-id="935f7-107">Der Satz von häufigen Wörtern durchsucht.</span><span class="sxs-lookup"><span data-stu-id="935f7-107">The set of common words.</span></span></param>
        <param name="ignoreCase"><span data-ttu-id="935f7-108">Ein Wert, der angibt, ob häufig auftretender Wörter, die übereinstimmende Groß-/Kleinschreibung beachtet werden.</span><span class="sxs-lookup"><span data-stu-id="935f7-108">A value indicating whether common words matching will be case insensitive.</span></span> <span data-ttu-id="935f7-109">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="935f7-109">Default is false.</span></span></param>
        <param name="useQueryMode"><span data-ttu-id="935f7-110">Ein Wert, der angibt, ob das token Filter im Abfragemodus ist.</span><span class="sxs-lookup"><span data-stu-id="935f7-110">A value that indicates whether the token filter is in query mode.</span></span> <span data-ttu-id="935f7-111">Im Abfragemodus können token Filter digramme generiert und entfernt dann häufig auftretender Wörter und einzelne Ausdrücke, gefolgt von einem allgemeinen Wort.</span><span class="sxs-lookup"><span data-stu-id="935f7-111">When in query mode, the token filter generates bigrams and then removes common words and single terms followed by a common word.</span></span> <span data-ttu-id="935f7-112">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="935f7-112">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="935f7-113">Initialisiert eine neue Instanz der CommonGramTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="935f7-113">Initializes a new instance of the CommonGramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonWords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; CommonWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; CommonWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.CommonWords" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonWords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.CommonWords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.CommonWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonWords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="935f7-114">Ruft ab oder legt sie fest häufig auftretender Wörter.</span><span class="sxs-lookup"><span data-stu-id="935f7-114">Gets or sets the set of common words.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.IgnoreCase" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreCase")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="935f7-115">Ruft ab oder legt einen Wert, der angibt, ob häufig auftretender Wörter, die übereinstimmende Groß-/Kleinschreibung beachtet werden.</span><span class="sxs-lookup"><span data-stu-id="935f7-115">Gets or sets a value indicating whether common words matching will be case insensitive.</span></span> <span data-ttu-id="935f7-116">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="935f7-116">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UseQueryMode">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UseQueryMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UseQueryMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CommonGramTokenFilter.UseQueryMode" />
      <MemberSignature Language="VB.NET" Value="Public Property UseQueryMode As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UseQueryMode : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CommonGramTokenFilter.UseQueryMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queryMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="935f7-117">Ruft ab oder legt einen Wert, der angibt, ob das token Filter im Abfragemodus ist.</span><span class="sxs-lookup"><span data-stu-id="935f7-117">Gets or sets a value that indicates whether the token filter is in query mode.</span></span> <span data-ttu-id="935f7-118">Im Abfragemodus können token Filter digramme generiert und entfernt dann häufig auftretender Wörter und einzelne Ausdrücke, gefolgt von einem allgemeinen Wort.</span><span class="sxs-lookup"><span data-stu-id="935f7-118">When in query mode, the token filter generates bigrams and then removes common words and single terms followed by a common word.</span></span> <span data-ttu-id="935f7-119">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="935f7-119">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CommonGramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="commonGramTokenFilter.Validate " />
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
            <span data-ttu-id="935f7-120">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="935f7-120">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="935f7-121">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="935f7-121">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>