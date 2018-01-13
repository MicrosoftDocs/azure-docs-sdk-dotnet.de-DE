<Type Name="JsonFormat" FullName="Microsoft.Azure.Management.DataFactory.Models.JsonFormat">
  <TypeSignature Language="C#" Value="public class JsonFormat : Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JsonFormat extends Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.JsonFormat" />
  <TypeSignature Language="VB.NET" Value="Public Class JsonFormat&#xA;Inherits DatasetStorageFormat" />
  <TypeSignature Language="F#" Value="type JsonFormat = class&#xA;    inherit DatasetStorageFormat" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.DatasetStorageFormat</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Daten im JSON-Format gespeichert.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JsonFormat-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JsonFormat (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object serializer = null, object deserializer = null, string filePattern = null, object nestingSeparator = null, object encodingName = null, object jsonNodeReference = null, object jsonPathDefinition = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object serializer, object deserializer, string filePattern, object nestingSeparator, object encodingName, object jsonNodeReference, object jsonPathDefinition) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.String,System.Object,System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional serializer As Object = null, Optional deserializer As Object = null, Optional filePattern As String = null, Optional nestingSeparator As Object = null, Optional encodingName As Object = null, Optional jsonNodeReference As Object = null, Optional jsonPathDefinition As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.JsonFormat : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * string * obj * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.JsonFormat" Usage="new Microsoft.Azure.Management.DataFactory.Models.JsonFormat (additionalProperties, serializer, deserializer, filePattern, nestingSeparator, encodingName, jsonNodeReference, jsonPathDefinition)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="serializer" Type="System.Object" />
        <Parameter Name="deserializer" Type="System.Object" />
        <Parameter Name="filePattern" Type="System.String" />
        <Parameter Name="nestingSeparator" Type="System.Object" />
        <Parameter Name="encodingName" Type="System.Object" />
        <Parameter Name="jsonNodeReference" Type="System.Object" />
        <Parameter Name="jsonPathDefinition" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="serializer">Das Serialisierungsprogramm. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="deserializer">Das Deserialisierungsprogramm. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="filePattern">Der JSON Dateimuster. Um spezifischere, werden die Möglichkeit, eine Auflistung von JSON-Objekten zu trennen. Der Standardwert ist "SetOfObjects". Es wird die Groß-/Kleinschreibung beachtet. Folgende Werte sind möglich: "SetOfObjects", "ArrayOfObjects"</param>
        <param name="nestingSeparator">Das Zeichen zum Trennen der Schachtelungsebenen verwendet. Standardwert ist "." (Punkt). Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="encodingName">Der Codepagename der bevorzugten Codierung. Wenn nicht angegeben ist, ist der Standardwert "Utf-8", es sei denn, einer anderen Codierung von Unicode-Byte-reihenfolgemarkierung (BOM) bezeichnet. Die vollständige Liste der unterstützten Werte finden Sie in der Spalte "Name" der Tabelle der Codierungen in den folgenden Verweis: https://go.microsoft.com/fwlink/?linkid=861078. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="jsonNodeReference">Die JSONPath des JSON-Array-Elements, vereinfacht werden. Beispiel: "$. ArrayPath". Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).</param>
        <param name="jsonPathDefinition">Die Definition der JSONPath für jede spaltenzuordnung mit einem benutzerdefinierten Spaltennamen zum Extrahieren von Daten aus JSON-Datei. Beginnen Sie für Felder unter Stammobjekt mit "$"; Starten Sie für Felder in das Array von JsonNodeReference Eigenschaft gewählt wird über das Arrayelement. Beispiel: {"Column1": "$. Column1Path","Column2":"Column2PathInArray"}. Typ: Objekt (oder Ausdruck mit ResultType-Objekt).</param>
        <summary>
            Initialisiert eine neue Instanz der JsonFormat-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EncodingName">
      <MemberSignature Language="C#" Value="public object EncodingName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object EncodingName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.EncodingName" />
      <MemberSignature Language="VB.NET" Value="Public Property EncodingName As Object" />
      <MemberSignature Language="F#" Value="member this.EncodingName : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.EncodingName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encodingName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Codepagename der bevorzugten Codierung. Wenn nicht angegeben ist, ist der Standardwert "Utf-8", es sei denn, einer anderen Codierung von Unicode-Byte-reihenfolgemarkierung (BOM) bezeichnet. Die vollständige Liste der unterstützten Werte finden Sie in der Spalte "Name" der Tabelle der Codierungen in den folgenden Verweis: https://go.microsoft.com/fwlink/?linkid=861078. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilePattern">
      <MemberSignature Language="C#" Value="public string FilePattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilePattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.FilePattern" />
      <MemberSignature Language="VB.NET" Value="Public Property FilePattern As String" />
      <MemberSignature Language="F#" Value="member this.FilePattern : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.FilePattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="filePattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Dateimuster von JSON. Um spezifischere, werden die Möglichkeit, eine Auflistung von JSON-Objekten zu trennen. Der Standardwert ist "SetOfObjects". Es wird die Groß-/Kleinschreibung beachtet. Folgende Werte sind möglich: "SetOfObjects", "ArrayOfObjects"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonNodeReference">
      <MemberSignature Language="C#" Value="public object JsonNodeReference { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JsonNodeReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonNodeReference" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonNodeReference As Object" />
      <MemberSignature Language="F#" Value="member this.JsonNodeReference : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonNodeReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jsonNodeReference")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der JSONPath des JSON-Array-Elements, vereinfacht werden. Beispiel: "$. ArrayPath". Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JsonPathDefinition">
      <MemberSignature Language="C#" Value="public object JsonPathDefinition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object JsonPathDefinition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonPathDefinition" />
      <MemberSignature Language="VB.NET" Value="Public Property JsonPathDefinition As Object" />
      <MemberSignature Language="F#" Value="member this.JsonPathDefinition : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.JsonPathDefinition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jsonPathDefinition")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die JSONPath-Definition für jede spaltenzuordnung mit einem benutzerdefinierten Spaltennamen zum Extrahieren von Daten aus JSON-Datei. Beginnen Sie für Felder unter Stammobjekt mit "$"; Starten Sie für Felder in das Array von JsonNodeReference Eigenschaft gewählt wird über das Arrayelement.
            Beispiel: {"Column1": "$. Column1Path","Column2":"Column2PathInArray"}. Typ: Objekt (oder Ausdruck mit ResultType-Objekt).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestingSeparator">
      <MemberSignature Language="C#" Value="public object NestingSeparator { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object NestingSeparator" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.JsonFormat.NestingSeparator" />
      <MemberSignature Language="VB.NET" Value="Public Property NestingSeparator As Object" />
      <MemberSignature Language="F#" Value="member this.NestingSeparator : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.JsonFormat.NestingSeparator" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nestingSeparator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Zeichen zum Trennen der Schachtelungsebenen verwendet. Standardwert ist "." (Punkt). Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>