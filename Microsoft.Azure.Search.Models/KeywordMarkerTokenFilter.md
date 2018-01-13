<Type Name="KeywordMarkerTokenFilter" FullName="Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter">
  <TypeSignature Language="C#" Value="public class KeywordMarkerTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KeywordMarkerTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class KeywordMarkerTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type KeywordMarkerTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.KeywordMarkerTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="87153-101">Markiert die Begriffe als Schlüsselwörter.</span><span class="sxs-lookup"><span data-stu-id="87153-101">Marks terms as keywords.</span></span> <span data-ttu-id="87153-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="87153-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/miscellaneous/KeywordMarkerFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordMarkerTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.#ctor" />
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
            <span data-ttu-id="87153-103">Initialisiert eine neue Instanz der KeywordMarkerTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87153-103">Initializes a new instance of the KeywordMarkerTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KeywordMarkerTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; keywords, Nullable&lt;bool&gt; ignoreCase = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; keywords, valuetype System.Nullable`1&lt;bool&gt; ignoreCase) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, keywords As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter" Usage="new Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter (name, keywords, ignoreCase)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="keywords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="87153-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="87153-104">The name of the token filter.</span></span> <span data-ttu-id="87153-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="87153-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="keywords"><span data-ttu-id="87153-106">Eine Liste von Wörtern, die als Schlüsselwörter zu markieren.</span><span class="sxs-lookup"><span data-stu-id="87153-106">A list of words to mark as keywords.</span></span></param>
        <param name="ignoreCase"><span data-ttu-id="87153-107">Ein Wert, der angibt, ob Groß-und Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="87153-107">A value indicating whether to ignore case.</span></span>
            <span data-ttu-id="87153-108">Bei "true", werden alle Wörter zuerst in Kleinbuchstaben konvertiert.</span><span class="sxs-lookup"><span data-stu-id="87153-108">If true, all words are converted to lower case first.</span></span> <span data-ttu-id="87153-109">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="87153-109">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="87153-110">Initialisiert eine neue Instanz der KeywordMarkerTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87153-110">Initializes a new instance of the KeywordMarkerTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.IgnoreCase" />
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
            <span data-ttu-id="87153-111">Ruft ab oder legt einen Wert, der angibt, ob Groß-und Kleinschreibung.</span><span class="sxs-lookup"><span data-stu-id="87153-111">Gets or sets a value indicating whether to ignore case.</span></span> <span data-ttu-id="87153-112">Bei "true", werden alle Wörter zuerst in Kleinbuchstaben konvertiert.</span><span class="sxs-lookup"><span data-stu-id="87153-112">If true, all words are converted to lower case first.</span></span> <span data-ttu-id="87153-113">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="87153-113">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keywords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Keywords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Keywords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.Keywords" />
      <MemberSignature Language="VB.NET" Value="Public Property Keywords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Keywords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.Keywords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keywords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87153-114">Ruft ab oder legt eine Liste von Wörtern, die als Schlüsselwörter zu markieren.</span><span class="sxs-lookup"><span data-stu-id="87153-114">Gets or sets a list of words to mark as keywords.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.KeywordMarkerTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="keywordMarkerTokenFilter.Validate " />
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
            <span data-ttu-id="87153-115">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="87153-115">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="87153-116">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="87153-116">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>