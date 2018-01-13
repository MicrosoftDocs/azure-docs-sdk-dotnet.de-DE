<Type Name="FieldMappingFunction" FullName="Microsoft.Azure.Search.Models.FieldMappingFunction">
  <TypeSignature Language="C#" Value="public class FieldMappingFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FieldMappingFunction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FieldMappingFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class FieldMappingFunction" />
  <TypeSignature Language="F#" Value="type FieldMappingFunction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c3554-101">Stellt eine Funktion, die einen Wert aus einer Datenquelle vor der Indizierung transformiert.</span><span class="sxs-lookup"><span data-stu-id="c3554-101">Represents a function that transforms a value from a data source before indexing.</span></span>
            <see href="https://docs.microsoft.com/azure/search/search-indexer-field-mappings" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMappingFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.#ctor" />
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
            <span data-ttu-id="c3554-102">Initialisiert eine neue Instanz der FieldMappingFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3554-102">Initializes a new instance of the FieldMappingFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FieldMappingFunction (string name, System.Collections.Generic.IDictionary&lt;string,object&gt; parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.#ctor(System.String,System.Collections.Generic.IDictionary{System.String,System.Object})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional parameters As IDictionary(Of String, Object) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FieldMappingFunction : string * System.Collections.Generic.IDictionary&lt;string, obj&gt; -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="new Microsoft.Azure.Search.Models.FieldMappingFunction (name, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="c3554-103">Der Name des der Zuordnungsfunktion Feld.</span><span class="sxs-lookup"><span data-stu-id="c3554-103">The name of the field mapping function.</span></span></param>
        <param name="parameters"><span data-ttu-id="c3554-104">Ein Wörterbuch von Name/Wert-Paaren an die Funktion übergeben.</span><span class="sxs-lookup"><span data-stu-id="c3554-104">A dictionary of parameter name/value pairs to pass to the function.</span></span> <span data-ttu-id="c3554-105">Jeder Wert muss ein primitiver Typ sein.</span><span class="sxs-lookup"><span data-stu-id="c3554-105">Each value must be of a primitive type.</span></span></param>
        <summary>
            <span data-ttu-id="c3554-106">Initialisiert eine neue Instanz der FieldMappingFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c3554-106">Initializes a new instance of the FieldMappingFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64Decode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction Base64Decode ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction Base64Decode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Decode" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Base64Decode () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member Base64Decode : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Decode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3554-107">Erstellt eine Funktion der Feld-Zuordnung, die Base64-Decodierung der Eingabezeichenfolge ausführt.</span><span class="sxs-lookup"><span data-stu-id="c3554-107">Creates a field mapping function that performs Base64 decoding of the input string.</span></span> <span data-ttu-id="c3554-108">Die Eingabe wird in eine URL-sichere Base64-codierte Zeichenfolge angenommen.</span><span class="sxs-lookup"><span data-stu-id="c3554-108">The input is assumed to a URL-safe Base64-encoded string.</span></span> 
            </summary>
        <returns><span data-ttu-id="c3554-109">Eine neue Funktion der Feld-Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="c3554-109">A new field mapping function.</span></span></returns>
        <remarks>
            <span data-ttu-id="c3554-110">Beispiel-Anwendungsfall: Blob benutzerdefinierte Metadatenwerte müssen ASCII-codierte sein.</span><span class="sxs-lookup"><span data-stu-id="c3554-110">Sample use case: Blob custom metadata values must be ASCII-encoded.</span></span> <span data-ttu-id="c3554-111">Sie können die Base64-Codierung verwenden, um beliebige Unicode-Zeichenfolgen in benutzerdefinierten Blobmetadaten darzustellen.</span><span class="sxs-lookup"><span data-stu-id="c3554-111">You can use Base64 encoding to represent arbitrary Unicode strings in blob custom metadata.</span></span> <span data-ttu-id="c3554-112">Um die Suche aussagekräftig zu gestalten, können Sie mit dieser Funktion die codierten Daten beim Auffüllen des Suchindexes wieder in „normale“ Zeichenfolgen umwandeln.</span><span class="sxs-lookup"><span data-stu-id="c3554-112">However, to make search meaningful, you can use this function to turn the encoded data back into "regular" strings when populating your search index.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Base64Encode">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction Base64Encode ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction Base64Encode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Encode" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Base64Encode () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member Base64Encode : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Base64Encode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3554-113">Erstellt eine Funktion der Feld-Zuordnung, die URL-sichere Base64-Codierung der Eingabezeichenfolge ausführt.</span><span class="sxs-lookup"><span data-stu-id="c3554-113">Creates a field mapping function that performs URL-safe Base64 encoding of the input string.</span></span> <span data-ttu-id="c3554-114">Geht davon aus, dass die Eingabe mit UTF-8 codiert ist.</span><span class="sxs-lookup"><span data-stu-id="c3554-114">Assumes that the input is UTF-8 encoded.</span></span>
            </summary>
        <returns><span data-ttu-id="c3554-115">Eine neue Funktion der Feld-Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="c3554-115">A new field mapping function.</span></span></returns>
        <remarks>
            <span data-ttu-id="c3554-116">Beispiel-Anwendungsfall: nur URL-sichere Zeichen stehen in einem Dokumentschlüssel Azure Search (da Kunden auf das Dokument mit der Suche-API, z. B. Adresse werden müssen).</span><span class="sxs-lookup"><span data-stu-id="c3554-116">Sample use case: Only URL-safe characters can appear in an Azure Search document key (because customers must be able to address the document using the Lookup API, for example).</span></span> <span data-ttu-id="c3554-117">Wenn Ihre Daten URL-unsichere Zeichen enthalten und Sie damit ein Schlüsselfeld in Ihrem Suchindex auffüllen möchten, verwenden Sie diese Funktion.</span><span class="sxs-lookup"><span data-stu-id="c3554-117">If your data contains URL-unsafe characters and you want to use it to populate a key field in your search index, use this function.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExtractTokenAtPosition">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction ExtractTokenAtPosition (string delimiter, int position);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction ExtractTokenAtPosition(string delimiter, int32 position) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.ExtractTokenAtPosition(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ExtractTokenAtPosition (delimiter As String, position As Integer) As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member ExtractTokenAtPosition : string * int -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.ExtractTokenAtPosition (delimiter, position)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="delimiter" Type="System.String" />
        <Parameter Name="position" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="delimiter"><span data-ttu-id="c3554-118">Eine Zeichenfolge, die als Trennzeichen verwendet werden soll, für die Aufteilung der Eingabezeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="c3554-118">A string to use as the separator when splitting the input string.</span></span></param>
        <param name="position"><span data-ttu-id="c3554-119">Eine ganze Zahl nullbasierte Position des Tokens auswählen, nachdem die Eingabezeichenfolge aufgeteilt wird.</span><span class="sxs-lookup"><span data-stu-id="c3554-119">An integer zero-based position of the token to pick after the input string is split.</span></span></param>
        <summary>
            <span data-ttu-id="c3554-120">Erstellt eine Funktion der Feld-Zuordnung, die ein Zeichenfolgenfeld mithilfe des angegebenen Trennzeichens unterteilt und wählt das Token der angegebenen Position in der resultierenden Teilung.</span><span class="sxs-lookup"><span data-stu-id="c3554-120">Creates a field mapping function that splits a string field using the specified delimiter, and picks the token at the specified position in the resulting split.</span></span>
            </summary>
        <returns><span data-ttu-id="c3554-121">Eine neue Funktion der Feld-Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="c3554-121">A new field mapping function.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c3554-122">Beispielsweise ist die Eingabe Jane Doe, das Trennzeichen ist "" (Leerzeichen) und die Position ist 0, das Ergebnis ist, stellt Andrea; Wenn die Position 1 ist, ist das Ergebnis Doe an.</span><span class="sxs-lookup"><span data-stu-id="c3554-122">For example, if the input is Jane Doe, the delimiter is " " (space) and the position is 0, the result is Jane; if the position is 1, the result is Doe.</span></span> <span data-ttu-id="c3554-123">Wenn die Position auf ein Token verweist, das nicht vorhanden ist, wird ein Fehler zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c3554-123">If the position refers to a token that doesn't exist, an error will be returned.</span></span>
            </para>
          <para>
            <span data-ttu-id="c3554-124">Anwendungsfall-Beispiel: Ihre Datenquelle enthält ein Feld PersonName, und es als zwei separate Felder für FirstName und LastName indiziert werden soll.</span><span class="sxs-lookup"><span data-stu-id="c3554-124">Sample use case: Your data source contains a PersonName field, and you want to index it as two separate FirstName and LastName fields.</span></span> <span data-ttu-id="c3554-125">Mit dieser Funktion können Sie die Eingabe mit dem Leerzeichen als Trennzeichen unterteilen.</span><span class="sxs-lookup"><span data-stu-id="c3554-125">You can use this function to split the input using the space character as the delimiter.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonArrayToStringCollection">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Search.Models.FieldMappingFunction JsonArrayToStringCollection ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Search.Models.FieldMappingFunction JsonArrayToStringCollection() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.JsonArrayToStringCollection" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function JsonArrayToStringCollection () As FieldMappingFunction" />
      <MemberSignature Language="F#" Value="static member JsonArrayToStringCollection : unit -&gt; Microsoft.Azure.Search.Models.FieldMappingFunction" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.JsonArrayToStringCollection " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FieldMappingFunction</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c3554-126">Erstellt eine Funktion der Feld-Zuordnung, die transformiert eine Zeichenfolge im Format als JSON-Array von Zeichenfolgen in ein Zeichenfolgenarray, das zum Auffüllen von einem Collection(EDM.String)-Feld im Index verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="c3554-126">Creates a field mapping function that transforms a string formatted as a JSON array of strings into a string array that can be used to populate a Collection(Edm.String) field in the index.</span></span>
            </summary>
        <returns><span data-ttu-id="c3554-127">Eine neue Funktion der Feld-Zuordnung.</span><span class="sxs-lookup"><span data-stu-id="c3554-127">A new field mapping function.</span></span></returns>
        <remarks>
          <para>
            <span data-ttu-id="c3554-128">Wenn die Eingabezeichenfolge ist z. B. ["Rot", "Weißer", "blue"], und klicken Sie dann das Feld "Ziel" vom Typ Collection(Edm.String) mit drei Werte Rot, weiß und Blau aufgefüllt wird.</span><span class="sxs-lookup"><span data-stu-id="c3554-128">For example, if the input string is ["red", "white", "blue"], then the target field of type Collection(Edm.String) will be populated with the three values red, white and blue.</span></span> <span data-ttu-id="c3554-129">Für Eingabewerte, die nicht als JSON-Zeichenfolgenarrays analysiert werden können, wird ein Fehler zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="c3554-129">For input values that cannot be parsed as JSON string arrays, an error will be returned.</span></span>
            </para>
          <para>
            <span data-ttu-id="c3554-130">Beispiel-Anwendungsfall: Azure SQL-Datenbank verfügt nicht über ein integrierter Datentyp, der in Azure Search Collection(EDM.String)-Felder natürlich zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="c3554-130">Sample use case: Azure SQL database doesn't have a built-in data type that naturally maps to Collection(Edm.String) fields in Azure Search.</span></span> <span data-ttu-id="c3554-131">Um Zeichenfolgen-Sammlungsfelder aufzufüllen, formatieren Sie Ihre Quelldaten als JSON-Zeichenfolgenarray, und verwenden Sie diese Funktion.</span><span class="sxs-lookup"><span data-stu-id="c3554-131">To populate string collection fields, format your source data as a JSON string array and use this function.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMappingFunction.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="c3554-132">Ruft ab oder legt den Namen der Funktion Zuordnung Feld fest.</span><span class="sxs-lookup"><span data-stu-id="c3554-132">Gets or sets the name of the field mapping function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FieldMappingFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Search.Models.FieldMappingFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c3554-133">Ruft ab oder legt ein Wörterbuch von Name/Wert-Paaren an die Funktion übergeben.</span><span class="sxs-lookup"><span data-stu-id="c3554-133">Gets or sets a dictionary of parameter name/value pairs to pass to the function.</span></span> <span data-ttu-id="c3554-134">Jeder Wert muss ein primitiver Typ sein.</span><span class="sxs-lookup"><span data-stu-id="c3554-134">Each value must be of a primitive type.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FieldMappingFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fieldMappingFunction.Validate " />
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
            <span data-ttu-id="c3554-135">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="c3554-135">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="c3554-136">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="c3554-136">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>