<Type Name="CustomAnalyzer" FullName="Microsoft.Azure.Search.Models.CustomAnalyzer">
  <TypeSignature Language="C#" Value="public class CustomAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CustomAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CustomAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class CustomAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type CustomAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CustomAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="153a6-101">Können Sie die Kontrolle über den Prozess der Konvertierung von Text in indizierbaren/durchsuchbaren Token nutzen.</span><span class="sxs-lookup"><span data-stu-id="153a6-101">Allows you to take control over the process of converting text into indexable/searchable tokens.</span></span> <span data-ttu-id="153a6-102">Es ist eine benutzerdefinierte Konfiguration besteht aus einer einzelnen vordefinierten Tokenizer und ein oder mehrere Filter.</span><span class="sxs-lookup"><span data-stu-id="153a6-102">It's a user-defined configuration consisting of a single predefined tokenizer and one or more filters.</span></span>
            <span data-ttu-id="153a6-103">Der Tokenizer ist verantwortlich für Zerlegen von Text in Token und die Filter für das Ändern von Tokens ausgegeben, die für den Tokenizer.</span><span class="sxs-lookup"><span data-stu-id="153a6-103">The tokenizer is responsible for breaking text into tokens, and the filters for modifying tokens emitted by the tokenizer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor" />
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
            <span data-ttu-id="153a6-104">Initialisiert eine neue Instanz der CustomAnalyzer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="153a6-104">Initializes a new instance of the CustomAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CustomAnalyzer (string name, Microsoft.Azure.Search.Models.TokenizerName tokenizer, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.TokenizerName tokenizer, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; tokenFilters, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; charFilters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.#ctor(System.String,Microsoft.Azure.Search.Models.TokenizerName,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.TokenFilterName},System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CharFilterName})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, tokenizer As TokenizerName, Optional tokenFilters As IList(Of TokenFilterName) = null, Optional charFilters As IList(Of CharFilterName) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CustomAnalyzer : string * Microsoft.Azure.Search.Models.TokenizerName * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; -&gt; Microsoft.Azure.Search.Models.CustomAnalyzer" Usage="new Microsoft.Azure.Search.Models.CustomAnalyzer (name, tokenizer, tokenFilters, charFilters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="tokenizer" Type="Microsoft.Azure.Search.Models.TokenizerName" />
        <Parameter Name="tokenFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;" />
        <Parameter Name="charFilters" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="153a6-105">Der Name des Analyzers.</span><span class="sxs-lookup"><span data-stu-id="153a6-105">The name of the analyzer.</span></span> <span data-ttu-id="153a6-106">Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</span><span class="sxs-lookup"><span data-stu-id="153a6-106">It must only contain letters, digits, spaces, dashes or underscores, can only start and end with alphanumeric characters, and is limited to 128 characters.</span></span></param>
        <param name="tokenizer"><span data-ttu-id="153a6-107">Der Name des tokenizers zum Dividieren von fortlaufenden Textbereich in eine Folge von Token, wie einen Satz in Wörter unterteilt.</span><span class="sxs-lookup"><span data-stu-id="153a6-107">The name of the tokenizer to use to divide continuous text into a sequence of tokens, such as breaking a sentence into words.</span></span></param>
        <param name="tokenFilters"><span data-ttu-id="153a6-108">Eine Liste von token filtern, die zum herausfiltern oder ändern die Token, die durch einen Tokenizer verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="153a6-108">A list of token filters used to filter out or modify the tokens generated by a tokenizer.</span></span> <span data-ttu-id="153a6-109">Sie können beispielsweise einen Filter für Kleinbuchstaben angeben, mit dem alle Zeichen in Kleinbuchstaben konvertiert werden.</span><span class="sxs-lookup"><span data-stu-id="153a6-109">For example, you can specify a lowercase filter that converts all characters to lowercase.</span></span> <span data-ttu-id="153a6-110">Die Filter werden in der Reihenfolge ausgeführt, in denen sie aufgelistet sind.</span><span class="sxs-lookup"><span data-stu-id="153a6-110">The filters are run in the order in which they are listed.</span></span></param>
        <param name="charFilters"><span data-ttu-id="153a6-111">Eine Liste von Zeichen Filter verwendet, um Eingabetext vorzubereiten, bevor die Verarbeitung durch den Tokenizer.</span><span class="sxs-lookup"><span data-stu-id="153a6-111">A list of character filters used to prepare input text before it is processed by the tokenizer.</span></span> <span data-ttu-id="153a6-112">Sie können z. B. bestimmte Zeichen oder Symbole ersetzen.</span><span class="sxs-lookup"><span data-stu-id="153a6-112">For instance, they can replace certain characters or symbols.</span></span> <span data-ttu-id="153a6-113">Die Filter werden in der Reihenfolge ausgeführt, in denen sie aufgelistet sind.</span><span class="sxs-lookup"><span data-stu-id="153a6-113">The filters are run in the order in which they are listed.</span></span></param>
        <summary>
            <span data-ttu-id="153a6-114">Initialisiert eine neue Instanz der CustomAnalyzer-Klasse.</span><span class="sxs-lookup"><span data-stu-id="153a6-114">Initializes a new instance of the CustomAnalyzer class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CharFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.CharFilterName&gt; CharFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property CharFilters As IList(Of CharFilterName)" />
      <MemberSignature Language="F#" Value="member this.CharFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.CharFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="charFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CharFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="153a6-115">Ruft ab oder legt eine Liste von Zeichen Filtern verwendet, um Eingabetext vorzubereiten, bevor die Verarbeitung durch den Tokenizer.</span><span class="sxs-lookup"><span data-stu-id="153a6-115">Gets or sets a list of character filters used to prepare input text before it is processed by the tokenizer.</span></span> <span data-ttu-id="153a6-116">Sie können z. B. bestimmte Zeichen oder Symbole ersetzen.</span><span class="sxs-lookup"><span data-stu-id="153a6-116">For instance, they can replace certain characters or symbols.</span></span> <span data-ttu-id="153a6-117">Die Filter werden in der Reihenfolge ausgeführt, in denen sie aufgelistet sind.</span><span class="sxs-lookup"><span data-stu-id="153a6-117">The filters are run in the order in which they are listed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TokenFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.TokenFilterName&gt; TokenFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberSignature Language="VB.NET" Value="Public Property TokenFilters As IList(Of TokenFilterName)" />
      <MemberSignature Language="F#" Value="member this.TokenFilters : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.TokenFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenFilters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.TokenFilterName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="153a6-118">Ruft ab oder legt eine Liste von token filtern, die zum herausfiltern oder ändern die Token, die durch einen Tokenizer verwendet.</span><span class="sxs-lookup"><span data-stu-id="153a6-118">Gets or sets a list of token filters used to filter out or modify the tokens generated by a tokenizer.</span></span> <span data-ttu-id="153a6-119">Sie können beispielsweise einen Filter für Kleinbuchstaben angeben, mit dem alle Zeichen in Kleinbuchstaben konvertiert werden.</span><span class="sxs-lookup"><span data-stu-id="153a6-119">For example, you can specify a lowercase filter that converts all characters to lowercase.</span></span> <span data-ttu-id="153a6-120">Die Filter werden in der Reihenfolge ausgeführt, in denen sie aufgelistet sind.</span><span class="sxs-lookup"><span data-stu-id="153a6-120">The filters are run in the order in which they are listed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Tokenizer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TokenizerName Tokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TokenizerName Tokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property Tokenizer As TokenizerName" />
      <MemberSignature Language="F#" Value="member this.Tokenizer : Microsoft.Azure.Search.Models.TokenizerName with get, set" Usage="Microsoft.Azure.Search.Models.CustomAnalyzer.Tokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TokenizerName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="153a6-121">Ruft ab oder legt den Namen des tokenizers zum Dividieren von fortlaufenden Textbereich in eine Folge von Token, wie einen Satz in Wörter unterteilt.</span><span class="sxs-lookup"><span data-stu-id="153a6-121">Gets or sets the name of the tokenizer to use to divide continuous text into a sequence of tokens, such as breaking a sentence into words.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CustomAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="customAnalyzer.Validate " />
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
            <span data-ttu-id="153a6-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="153a6-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="153a6-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="153a6-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>