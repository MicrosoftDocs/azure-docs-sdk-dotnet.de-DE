<Type Name="StemmerTokenFilter" FullName="Microsoft.Azure.Search.Models.StemmerTokenFilter">
  <TypeSignature Language="C#" Value="public class StemmerTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StemmerTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StemmerTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StemmerTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StemmerTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StemmerTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="4e455-101">Bestimmte wortstammerkennung Sprachfilter.</span><span class="sxs-lookup"><span data-stu-id="4e455-101">Language specific stemming filter.</span></span> <span data-ttu-id="4e455-102">Dieser Filter token wird mithilfe von Apache Lucene implementiert.</span><span class="sxs-lookup"><span data-stu-id="4e455-102">This token filter is implemented using Apache Lucene.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Custom-analyzers-in-Azure-Search#TokenFilters" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.#ctor" />
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
            <span data-ttu-id="4e455-103">Initialisiert eine neue Instanz der StemmerTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4e455-103">Initializes a new instance of the StemmerTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StemmerTokenFilter (string name, Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage language);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.#ctor(System.String,Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, language As StemmerTokenFilterLanguage)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StemmerTokenFilter : string * Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage -&gt; Microsoft.Azure.Search.Models.StemmerTokenFilter" Usage="new Microsoft.Azure.Search.Models.StemmerTokenFilter (name, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="language" Type="Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="4e455-104">Der Name des Filters token.</span><span class="sxs-lookup"><span data-stu-id="4e455-104">The name of the token filter.</span></span> <span data-ttu-id="4e455-105">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="4e455-105">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="language"><span data-ttu-id="4e455-106">Die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="4e455-106">The language to use.</span></span> <span data-ttu-id="4e455-107">Folgende Werte sind möglich: "Arabische", "Armenisch", "Baskisch", "Portugiesisch (Brasilien)", "Bulgarisch", "Katalanisch", "Tschechische", "dänische", "Niederländisch", "DutchKp", "english", "LightEnglish", "MinimalEnglish", "PossessiveEnglish", "porter2", "Lovins", "Finnisch", "LightFinnish" , "Französisch", "LightFrench", "MinimalFrench", "Galizisch", "MinimalGalician", "Deutsch", "german2", "LightGerman", "MinimalGerman", "griechischen", "Hindi", "Ungarisch", "LightHungarian", 'indonesische', "Irland", "Italienisch", "LightItalian", "Sorani", " Lettisch ","Norwegisch","LightNorwegian","MinimalNorwegian","LightNynorsk","MinimalNynorsk"," Portugiesisch","LightPortuguese","MinimalPortuguese","PortugueseRslp","Rumänisch","Russisch","LightRussian","Spanische","LightSpanish"," Schwedisch ","LightSwedish","Türkisch"</span><span class="sxs-lookup"><span data-stu-id="4e455-107">Possible values include: 'arabic', 'armenian', 'basque', 'brazilian', 'bulgarian', 'catalan', 'czech', 'danish', 'dutch', 'dutchKp', 'english', 'lightEnglish', 'minimalEnglish', 'possessiveEnglish', 'porter2', 'lovins', 'finnish', 'lightFinnish', 'french', 'lightFrench', 'minimalFrench', 'galician', 'minimalGalician', 'german', 'german2', 'lightGerman', 'minimalGerman', 'greek', 'hindi', 'hungarian', 'lightHungarian', 'indonesian', 'irish', 'italian', 'lightItalian', 'sorani', 'latvian', 'norwegian', 'lightNorwegian', 'minimalNorwegian', 'lightNynorsk', 'minimalNynorsk', 'portuguese', 'lightPortuguese', 'minimalPortuguese', 'portugueseRslp', 'romanian', 'russian', 'lightRussian', 'spanish', 'lightSpanish', 'swedish', 'lightSwedish', 'turkish'</span></span></param>
        <summary>
            <span data-ttu-id="4e455-108">Initialisiert eine neue Instanz der StemmerTokenFilter-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4e455-108">Initializes a new instance of the StemmerTokenFilter class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StemmerTokenFilter.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As StemmerTokenFilterLanguage" />
      <MemberSignature Language="F#" Value="member this.Language : Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage with get, set" Usage="Microsoft.Azure.Search.Models.StemmerTokenFilter.Language" />
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
        <ReturnType>Microsoft.Azure.Search.Models.StemmerTokenFilterLanguage</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e455-109">Ruft ab oder legt die zu verwendende Sprache.</span><span class="sxs-lookup"><span data-stu-id="4e455-109">Gets or sets the language to use.</span></span> <span data-ttu-id="4e455-110">Folgende Werte sind möglich: "Arabische", "Armenisch", "Baskisch", "Portugiesisch (Brasilien)", "Bulgarisch", "Katalanisch", "Tschechische", "dänische", "Niederländisch", "DutchKp", "english", "LightEnglish", "MinimalEnglish", "PossessiveEnglish", "porter2", "Lovins", "Finnisch", "LightFinnish" , "Französisch", "LightFrench", "MinimalFrench", "Galizisch", "MinimalGalician", "Deutsch", "german2", "LightGerman", "MinimalGerman", "griechischen", "Hindi", "Ungarisch", "LightHungarian", 'indonesische', "Irland", "Italienisch", "LightItalian", "Sorani", " Lettisch ","Norwegisch","LightNorwegian","MinimalNorwegian","LightNynorsk","MinimalNynorsk"," Portugiesisch","LightPortuguese","MinimalPortuguese","PortugueseRslp","Rumänisch","Russisch","LightRussian","Spanische","LightSpanish"," Schwedisch ","LightSwedish","Türkisch"</span><span class="sxs-lookup"><span data-stu-id="4e455-110">Possible values include: 'arabic', 'armenian', 'basque', 'brazilian', 'bulgarian', 'catalan', 'czech', 'danish', 'dutch', 'dutchKp', 'english', 'lightEnglish', 'minimalEnglish', 'possessiveEnglish', 'porter2', 'lovins', 'finnish', 'lightFinnish', 'french', 'lightFrench', 'minimalFrench', 'galician', 'minimalGalician', 'german', 'german2', 'lightGerman', 'minimalGerman', 'greek', 'hindi', 'hungarian', 'lightHungarian', 'indonesian', 'irish', 'italian', 'lightItalian', 'sorani', 'latvian', 'norwegian', 'lightNorwegian', 'minimalNorwegian', 'lightNynorsk', 'minimalNynorsk', 'portuguese', 'lightPortuguese', 'minimalPortuguese', 'portugueseRslp', 'romanian', 'russian', 'lightRussian', 'spanish', 'lightSpanish', 'swedish', 'lightSwedish', 'turkish'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StemmerTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stemmerTokenFilter.Validate " />
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
            <span data-ttu-id="4e455-111">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="4e455-111">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="4e455-112">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="4e455-112">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>