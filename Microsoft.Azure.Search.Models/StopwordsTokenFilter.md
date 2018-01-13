<Type Name="StopwordsTokenFilter" FullName="Microsoft.Azure.Search.Models.StopwordsTokenFilter">
  <TypeSignature Language="C#" Value="public class StopwordsTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StopwordsTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StopwordsTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class StopwordsTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type StopwordsTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StopwordsTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Entfernt Stoppwörter einen token Stream heraus. Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor" />
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
            Initialisiert eine neue Instanz der StopwordsTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopwordsTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; stopwords = null, Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList = null, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; removeTrailingStopWords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; stopwords, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; stopwordsList, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; removeTrailingStopWords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{Microsoft.Azure.Search.Models.StopwordsList},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional stopwords As IList(Of String) = null, Optional stopwordsList As Nullable(Of StopwordsList) = null, Optional ignoreCase As Nullable(Of Boolean) = null, Optional removeTrailingStopWords As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StopwordsTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.StopwordsTokenFilter" Usage="new Microsoft.Azure.Search.Models.StopwordsTokenFilter (name, stopwords, stopwordsList, ignoreCase, removeTrailingStopWords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="stopwordsList" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="removeTrailingStopWords" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="stopwords">Die Liste von Stoppwörtern. Diese Eigenschaft und die Stoppwörter List-Eigenschaft können sowohl festgelegt werden.</param>
        <param name="stopwordsList">Eine vordefinierte Liste von Stoppwörtern verwenden.
            Diese Eigenschaft und die Stoppwörter-Eigenschaft können sowohl festgelegt werden.
            Standardmäßig ist Englisch. Folgende Werte sind möglich: "Arabische", "Armenisch", "Baskisch", "Portugiesisch (Brasilien)", "Bulgarisch", "Katalanisch", "Tschechische", "dänische", "Niederländisch", "english", "Finnisch", "Französisch", "Galizisch", "Deutsch", "griechischen", "Hindi", "Ungarisch", "Indonesisch", "Irisch", "Italienisch", " Lettisch ","Norwegisch","persischen"," Portugiesisch","Rumänisch","Russisch","Sorani","Spanische","Schwedisch","thai","Türkisch"</param>
        <param name="ignoreCase">Ein Wert, der angibt, ob Groß-und Kleinschreibung.
            Bei "true", werden alle Wörter zuerst in Kleinbuchstaben konvertiert. Die Standardeinstellung ist "false".</param>
        <param name="removeTrailingStopWords">Ein Wert, der angibt, ob den letzten Suchbegriff ignoriert werden sollen, wenn es sich um ein Stoppwort ist. Der Standardwert ist true.</param>
        <summary>
            Initialisiert eine neue Instanz der StopwordsTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.IgnoreCase" />
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
            Ruft ab oder legt einen Wert, der angibt, ob Groß-und Kleinschreibung. Bei "true", werden alle Wörter zuerst in Kleinbuchstaben konvertiert. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveTrailingStopWords">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; RemoveTrailingStopWords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; RemoveTrailingStopWords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberSignature Language="VB.NET" Value="Public Property RemoveTrailingStopWords As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.RemoveTrailingStopWords : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.RemoveTrailingStopWords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="removeTrailing")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob den letzten Suchbegriff ignoriert werden sollen, wenn es sich um ein Stoppwort ist. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.Stopwords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste mit Stoppwörtern fest. Diese Eigenschaft und die Stoppwörter List-Eigenschaft können sowohl festgelegt werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopwordsList">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.StopwordsList&gt; StopwordsList" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberSignature Language="VB.NET" Value="Public Property StopwordsList As Nullable(Of StopwordsList)" />
      <MemberSignature Language="F#" Value="member this.StopwordsList : Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopwordsTokenFilter.StopwordsList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stopwordsList")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.StopwordsList&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest eine vordefinierte Liste von Stoppwörtern verwenden. Diese Eigenschaft und die Stoppwörter-Eigenschaft können sowohl festgelegt werden. Standardmäßig ist Englisch.
            Folgende Werte sind möglich: "Arabische", "Armenisch", "Baskisch", "Portugiesisch (Brasilien)", "Bulgarisch", "Katalanisch", "Tschechische", "dänische", "Niederländisch", "english", "Finnisch", "Französisch", "Galizisch", "Deutsch", "griechischen", "Hindi", "Ungarisch", "Indonesisch", "Irisch", "Italienisch", " Lettisch ","Norwegisch","persischen"," Portugiesisch","Rumänisch","Russisch","Sorani","Spanische","Schwedisch","thai","Türkisch"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopwordsTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stopwordsTokenFilter.Validate " />
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