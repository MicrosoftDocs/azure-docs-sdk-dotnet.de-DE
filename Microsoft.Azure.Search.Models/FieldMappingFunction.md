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
            Stellt eine Funktion, die einen Wert aus einer Datenquelle vor der Indizierung transformiert.
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
            Initialisiert eine neue Instanz der FieldMappingFunction-Klasse.
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
        <param name="name">Der Name des der Zuordnungsfunktion Feld.</param>
        <param name="parameters">Ein Wörterbuch von Name/Wert-Paaren an die Funktion übergeben. Jeder Wert muss ein primitiver Typ sein.</param>
        <summary>
            Initialisiert eine neue Instanz der FieldMappingFunction-Klasse.
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
            Erstellt eine Funktion der Feld-Zuordnung, die Base64-Decodierung der Eingabezeichenfolge ausführt. Die Eingabe wird in eine URL-sichere Base64-codierte Zeichenfolge angenommen. 
            </summary>
        <returns>Eine neue Funktion der Feld-Zuordnung.</returns>
        <remarks>
            Beispiel-Anwendungsfall: Blob benutzerdefinierte Metadatenwerte müssen ASCII-codierte sein. Sie können die Base64-Codierung verwenden, um beliebige Unicode-Zeichenfolgen in benutzerdefinierten Blobmetadaten darzustellen. Um die Suche aussagekräftig zu gestalten, können Sie mit dieser Funktion die codierten Daten beim Auffüllen des Suchindexes wieder in „normale“ Zeichenfolgen umwandeln. 
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
            Erstellt eine Funktion der Feld-Zuordnung, die URL-sichere Base64-Codierung der Eingabezeichenfolge ausführt. Geht davon aus, dass die Eingabe mit UTF-8 codiert ist.
            </summary>
        <returns>Eine neue Funktion der Feld-Zuordnung.</returns>
        <remarks>
            Beispiel-Anwendungsfall: nur URL-sichere Zeichen stehen in einem Dokumentschlüssel Azure Search (da Kunden auf das Dokument mit der Suche-API, z. B. Adresse werden müssen). Wenn Ihre Daten URL-unsichere Zeichen enthalten und Sie damit ein Schlüsselfeld in Ihrem Suchindex auffüllen möchten, verwenden Sie diese Funktion. 
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
        <param name="delimiter">Eine Zeichenfolge, die als Trennzeichen verwendet werden soll, für die Aufteilung der Eingabezeichenfolge.</param>
        <param name="position">Eine ganze Zahl nullbasierte Position des Tokens auswählen, nachdem die Eingabezeichenfolge aufgeteilt wird.</param>
        <summary>
            Erstellt eine Funktion der Feld-Zuordnung, die ein Zeichenfolgenfeld mithilfe des angegebenen Trennzeichens unterteilt und wählt das Token der angegebenen Position in der resultierenden Teilung.
            </summary>
        <returns>Eine neue Funktion der Feld-Zuordnung.</returns>
        <remarks>
          <para>
            Beispielsweise ist die Eingabe Jane Doe, das Trennzeichen ist "" (Leerzeichen) und die Position ist 0, das Ergebnis ist, stellt Andrea; Wenn die Position 1 ist, ist das Ergebnis Doe an. Wenn die Position auf ein Token verweist, das nicht vorhanden ist, wird ein Fehler zurückgegeben.
            </para>
          <para>
            Anwendungsfall-Beispiel: Ihre Datenquelle enthält ein Feld PersonName, und es als zwei separate Felder für FirstName und LastName indiziert werden soll. Mit dieser Funktion können Sie die Eingabe mit dem Leerzeichen als Trennzeichen unterteilen.
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
            Erstellt eine Funktion der Feld-Zuordnung, die transformiert eine Zeichenfolge im Format als JSON-Array von Zeichenfolgen in ein Zeichenfolgenarray, das zum Auffüllen von einem Collection(EDM.String)-Feld im Index verwendet werden kann.
            </summary>
        <returns>Eine neue Funktion der Feld-Zuordnung.</returns>
        <remarks>
          <para>
            Wenn die Eingabezeichenfolge ist z. B. ["Rot", "Weißer", "blue"], und klicken Sie dann das Feld "Ziel" vom Typ Collection(Edm.String) mit drei Werte Rot, weiß und Blau aufgefüllt wird. Für Eingabewerte, die nicht als JSON-Zeichenfolgenarrays analysiert werden können, wird ein Fehler zurückgegeben.
            </para>
          <para>
            Beispiel-Anwendungsfall: Azure SQL-Datenbank verfügt nicht über ein integrierter Datentyp, der in Azure Search Collection(EDM.String)-Felder natürlich zugeordnet. Um Zeichenfolgen-Sammlungsfelder aufzufüllen, formatieren Sie Ihre Quelldaten als JSON-Zeichenfolgenarray, und verwenden Sie diese Funktion.
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
            Ruft ab oder legt den Namen der Funktion Zuordnung Feld fest.
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
            Ruft ab oder legt ein Wörterbuch von Name/Wert-Paaren an die Funktion übergeben. Jeder Wert muss ein primitiver Typ sein.
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
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>