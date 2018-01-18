<Type Name="SnowballTokenFilter" FullName="Microsoft.Azure.Search.Models.SnowballTokenFilter">
  <TypeSignature Language="C#" Value="public class SnowballTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SnowballTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SnowballTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SnowballTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type SnowballTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SnowballTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="032a0-101">Ein Filter, der Wörter, wobei eine wortstammerkennung Snowball generierte resultiert.</span><span class="sxs-lookup"><span data-stu-id="032a0-101">A filter that stems words using a Snowball-generated stemmer.</span></span> <span data-ttu-id="032a0-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="032a0-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/snowball/SnowballFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnowballTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.#ctor" />
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
            <span data-ttu-id="032a0-103">Initialisiert eine neue Instanz der SnowballTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="032a0-103">Initializes a new instance of the SnowballTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SnowballTokenFilter (string name, Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage language);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.#ctor(System.String,Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, language As SnowballTokenFilterLanguage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SnowballTokenFilter : string * Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage -&gt; Microsoft.Azure.Search.Models.SnowballTokenFilter" Usage="new Microsoft.Azure.Search.Models.SnowballTokenFilter (name, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="language" Type="Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="032a0-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="032a0-104">The name of the token filter.</span></span> <span data-ttu-id="032a0-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="032a0-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="language"><span data-ttu-id="032a0-106">Die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="032a0-106">The language to use.</span></span> <span data-ttu-id="032a0-107">Folgende Werte sind möglich: "Armenisch", "Baskisch", "Katalanisch", "dänische", "Niederländisch", "english", "Finnisch", "Französisch", "Deutsch", "german2", "Ungarisch", "Italienisch", "Kp", "Lovins',"Norwegisch","Porter","Portugiesisch","Rumänisch","Russisch","Spanisch"," Schwedisch ","Türkisch"</span><span class="sxs-lookup"><span data-stu-id="032a0-107">Possible values include: 'armenian', 'basque', 'catalan', 'danish', 'dutch', 'english', 'finnish', 'french', 'german', 'german2', 'hungarian', 'italian', 'kp', 'lovins', 'norwegian', 'porter', 'portuguese', 'romanian', 'russian', 'spanish', 'swedish', 'turkish'</span></span></param>
        <summary>
            <span data-ttu-id="032a0-108">Initialisiert eine neue Instanz der SnowballTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="032a0-108">Initializes a new instance of the SnowballTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SnowballTokenFilter.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As SnowballTokenFilterLanguage" />
      <MemberSignature Language="F#" Value="member this.Language : Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage with get, set" Usage="Microsoft.Azure.Search.Models.SnowballTokenFilter.Language" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="language")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.SnowballTokenFilterLanguage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="032a0-109">Ruft ab oder legt die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="032a0-109">Gets or sets the language to use.</span></span> <span data-ttu-id="032a0-110">Folgende Werte sind möglich: "Armenisch", "Baskisch", "Katalanisch", "dänische", "Niederländisch", "english", "Finnisch", "Französisch", "Deutsch", "german2", "Ungarisch", "Italienisch", "Kp", "Lovins',"Norwegisch","Porter","Portugiesisch","Rumänisch","Russisch","Spanisch"," Schwedisch ","Türkisch"</span><span class="sxs-lookup"><span data-stu-id="032a0-110">Possible values include: 'armenian', 'basque', 'catalan', 'danish', 'dutch', 'english', 'finnish', 'french', 'german', 'german2', 'hungarian', 'italian', 'kp', 'lovins', 'norwegian', 'porter', 'portuguese', 'romanian', 'russian', 'spanish', 'swedish', 'turkish'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SnowballTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="snowballTokenFilter.Validate " />
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
            <span data-ttu-id="032a0-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="032a0-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="032a0-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="032a0-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>