<Type Name="CjkBigramTokenFilter" FullName="Microsoft.Azure.Search.Models.CjkBigramTokenFilter">
  <TypeSignature Language="C#" Value="public class CjkBigramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CjkBigramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CjkBigramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CjkBigramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type CjkBigramTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CjkBigramTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="e0c54-101">Formulare digramme CJK-Begriffe, die von StandardTokenizer generiert werden.</span><span class="sxs-lookup"><span data-stu-id="e0c54-101">Forms bigrams of CJK terms that are generated from StandardTokenizer.</span></span>
            <span data-ttu-id="e0c54-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="e0c54-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKBigramFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor" />
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
            <span data-ttu-id="e0c54-103">Initialisiert eine neue Instanz der CjkBigramTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0c54-103">Initializes a new instance of the CjkBigramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts = null, Nullable&lt;bool&gt; outputUnigrams = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts, valuetype System.Nullable`1&lt;bool&gt; outputUnigrams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional ignoreScripts As IList(Of CjkBigramTokenFilterScripts) = null, Optional outputUnigrams As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.CjkBigramTokenFilter" Usage="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter (name, ignoreScripts, outputUnigrams)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ignoreScripts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;" />
        <Parameter Name="outputUnigrams" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="e0c54-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="e0c54-104">The name of the token filter.</span></span> <span data-ttu-id="e0c54-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="e0c54-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="ignoreScripts"><span data-ttu-id="e0c54-106">Die Skripts, ignoriert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e0c54-106">The scripts to ignore.</span></span></param>
        <param name="outputUnigrams"><span data-ttu-id="e0c54-107">Ein Wert, der angibt, ob sowohl monogramme als auch digramme (falls "true") ausgegeben oder nur digramme (Wenn "false").</span><span class="sxs-lookup"><span data-stu-id="e0c54-107">A value indicating whether to output both unigrams and bigrams (if true), or just bigrams (if false).</span></span>
            <span data-ttu-id="e0c54-108">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="e0c54-108">Default is false.</span></span></param>
        <summary>
            <span data-ttu-id="e0c54-109">Initialisiert eine neue Instanz der CjkBigramTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e0c54-109">Initializes a new instance of the CjkBigramTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreScripts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreScripts As IList(Of CjkBigramTokenFilterScripts)" />
      <MemberSignature Language="F#" Value="member this.IgnoreScripts : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreScripts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0c54-110">Ruft ab oder legt die Skripts, ignoriert werden sollen.</span><span class="sxs-lookup"><span data-stu-id="e0c54-110">Gets or sets the scripts to ignore.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUnigrams">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OutputUnigrams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OutputUnigrams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUnigrams As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OutputUnigrams : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputUnigrams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e0c54-111">Ruft ab oder legt einen Wert, der angibt, ob sowohl monogramme als auch digramme (falls "true") ausgegeben oder nur digramme (Wenn "false").</span><span class="sxs-lookup"><span data-stu-id="e0c54-111">Gets or sets a value indicating whether to output both unigrams and bigrams (if true), or just bigrams (if false).</span></span> <span data-ttu-id="e0c54-112">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="e0c54-112">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="cjkBigramTokenFilter.Validate " />
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
            <span data-ttu-id="e0c54-113">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="e0c54-113">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="e0c54-114">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="e0c54-114">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>