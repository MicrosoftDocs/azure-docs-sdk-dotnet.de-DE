<Type Name="MicrosoftLanguageTokenizer" FullName="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer">
  <TypeSignature Language="C#" Value="public class MicrosoftLanguageTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MicrosoftLanguageTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class MicrosoftLanguageTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type MicrosoftLanguageTokenizer = class&#xA;    inherit Tokenizer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Tokenizer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MicrosoftLanguageTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Teilt Text mit sprachspezifische Regeln an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.#ctor" />
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
            Initialisiert eine neue Instanz der MicrosoftLanguageTokenizer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftLanguageTokenizer (string name, Nullable&lt;int&gt; maxTokenLength = null, Nullable&lt;bool&gt; isSearchTokenizer = null, Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; language = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; maxTokenLength, valuetype System.Nullable`1&lt;bool&gt; isSearchTokenizer, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; language) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional maxTokenLength As Nullable(Of Integer) = null, Optional isSearchTokenizer As Nullable(Of Boolean) = null, Optional language As Nullable(Of MicrosoftTokenizerLanguage) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer : string * Nullable&lt;int&gt; * Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; -&gt; Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer" Usage="new Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer (name, maxTokenLength, isSearchTokenizer, language)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="maxTokenLength" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="isSearchTokenizer" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="language" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des tokenizers. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="maxTokenLength">Die maximale Tokenlänge. Token, die die maximale Länge überschreiten, werden geteilt. Maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen. Token, die länger als 300 Zeichen werden zuerst in Token Länge 300 aufteilen, und anschließend wird jede diese Token aufgeteilt basierend auf den max-token-Länge. Standardwert ist
            255.</param>
        <param name="isSearchTokenizer">Ein Wert, der angibt, wie der Tokenizer verwendet wird. Legen Sie auf "true" Wenn verwendet, als die Suche Tokenizer, auf "false" festgelegt werden, wenn als der Volltextindizierung Tokenizer verwendet. Die Standardeinstellung ist "false".</param>
        <param name="language">Die zu verwendende Sprache. Die Standardeinstellung ist Englisch.
            Folgende Werte sind möglich: "Bangla", "Bulgarisch", "Katalanisch", "ChineseSimplified", "ChineseTraditional", "Kroatisch", "Tschechische", "dänische", "Niederländisch", "english", "Französisch", "Deutsch", "Griechisch", "Gujarati", "Hindi", "Isländisch", "Indonesisch", "Italienisch", " Japanisch ","Kannada","koreanische","Malaiische","Malayalam","Marathi","NorwegianBokmaal","Polnisch","Portugiesisch","PortugueseBrazilian","punjabi","Rumänisch","Russisch","SerbianCyrillic","SerbianLatin","Slowenisch","Spanisch","Schwedisch","Tamil" , Telugu "-", "thai", "Ukrainische", "Urdu", "Vietnamesisch"</param>
        <summary>
            Initialisiert eine neue Instanz der MicrosoftLanguageTokenizer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsSearchTokenizer">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsSearchTokenizer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsSearchTokenizer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.IsSearchTokenizer" />
      <MemberSignature Language="VB.NET" Value="Public Property IsSearchTokenizer As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsSearchTokenizer : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.IsSearchTokenizer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isSearchTokenizer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, wie der Tokenizer verwendet wird. Legen Sie auf "true" Wenn verwendet, als die Suche Tokenizer, auf "false" festgelegt werden, wenn als der Volltextindizierung Tokenizer verwendet. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Language">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; Language { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; Language" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Language" />
      <MemberSignature Language="VB.NET" Value="Public Property Language As Nullable(Of MicrosoftTokenizerLanguage)" />
      <MemberSignature Language="F#" Value="member this.Language : Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Language" />
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
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.MicrosoftTokenizerLanguage&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die zu verwendende Sprache. Die Standardeinstellung ist Englisch. Folgende Werte sind möglich: "Bangla", "Bulgarisch", "Katalanisch", "ChineseSimplified", "ChineseTraditional", "Kroatisch", "Tschechische", "dänische", "Niederländisch", "english", "Französisch", "Deutsch", "Griechisch", "Gujarati", "Hindi", "Isländisch", "Indonesisch", "Italienisch", " Japanisch ","Kannada","koreanische","Malaiische","Malayalam","Marathi","NorwegianBokmaal","Polnisch","Portugiesisch","PortugueseBrazilian","punjabi","Rumänisch","Russisch","SerbianCyrillic","SerbianLatin","Slowenisch","Spanisch","Schwedisch","Tamil" , Telugu "-", "thai", "Ukrainische", "Urdu", "Vietnamesisch"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTokenLength">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTokenLength { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTokenLength" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.MaxTokenLength" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTokenLength As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTokenLength : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.MaxTokenLength" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxTokenLength")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Tokenlänge. Token, die die maximale Länge überschreiten, werden geteilt. Maximale Tokenlänge, die verwendet werden kann, beträgt 300 Zeichen. Token, die länger als 300 Zeichen werden zuerst in Token Länge 300 aufteilen, und anschließend wird jede diese Token aufgeteilt basierend auf den max-token-Länge. Standardwert ist 255.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MicrosoftLanguageTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="microsoftLanguageTokenizer.Validate " />
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