<Type Name="PhoneticTokenFilter" FullName="Microsoft.Azure.Search.Models.PhoneticTokenFilter">
  <TypeSignature Language="C#" Value="public class PhoneticTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PhoneticTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PhoneticTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PhoneticTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PhoneticTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PhoneticTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Erstellen von Tokens für phonetischen entspricht. Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-phonetic/org/apache/lucene/analysis/phonetic/package-tree.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor" />
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
            Initialisiert eine neue Instanz der PhoneticTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PhoneticTokenFilter (string name, Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder = null, Nullable&lt;bool&gt; replaceOriginalTokens = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; encoder, valuetype System.Nullable`1&lt;bool&gt; replaceOriginalTokens) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.#ctor(System.String,System.Nullable{Microsoft.Azure.Search.Models.PhoneticEncoder},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional encoder As Nullable(Of PhoneticEncoder) = null, Optional replaceOriginalTokens As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PhoneticTokenFilter : string * Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.PhoneticTokenFilter" Usage="new Microsoft.Azure.Search.Models.PhoneticTokenFilter (name, encoder, replaceOriginalTokens)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="encoder" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;" />
        <Parameter Name="replaceOriginalTokens" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="encoder">Der phonetischen Encoder verwenden. Der Standardwert ist "Metaphone". Folgende Werte sind möglich: "Metaphone", "DoubleMetaphone", "Soundex", "RefinedSoundex", "caverphone1", "caverphone2", "Köln", "Nysiis", "KoelnerPhonetik", "HaasePhonetik", "BeiderMorse"</param>
        <param name="replaceOriginalTokens">Ein Wert, der angibt, ob die ursprünglichen Token codierte Token ersetzt werden soll. Wenn "false" werden codierte Token als Synonyme hinzugefügt. Der Standardwert ist true.</param>
        <summary>
            Initialisiert eine neue Instanz der PhoneticTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoder">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.PhoneticEncoder&gt; Encoder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoder As Nullable(Of PhoneticEncoder)" />
      <MemberSignature Language="F#" Value="member this.Encoder : Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.Encoder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoder")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.PhoneticEncoder&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den phonetischen Encoder verwenden. Der Standardwert ist "Metaphone".
            Folgende Werte sind möglich: "Metaphone", "DoubleMetaphone", "Soundex", "RefinedSoundex", "caverphone1", "caverphone2", "Köln", "Nysiis", "KoelnerPhonetik", "HaasePhonetik", "BeiderMorse"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceOriginalTokens">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; ReplaceOriginalTokens { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; ReplaceOriginalTokens" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberSignature Language="VB.NET" Value="Public Property ReplaceOriginalTokens As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.ReplaceOriginalTokens : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PhoneticTokenFilter.ReplaceOriginalTokens" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replace")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die ursprünglichen Token codierte Token ersetzt werden soll. Wenn "false" werden codierte Token als Synonyme hinzugefügt. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PhoneticTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="phoneticTokenFilter.Validate " />
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