<Type Name="PatternTokenizer" FullName="Microsoft.Azure.Search.Models.PatternTokenizer">
  <TypeSignature Language="C#" Value="public class PatternTokenizer : Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternTokenizer extends Microsoft.Azure.Search.Models.Tokenizer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternTokenizer" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternTokenizer&#xA;Inherits Tokenizer" />
  <TypeSignature Language="F#" Value="type PatternTokenizer = class&#xA;    inherit Tokenizer" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternTokenizer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Tokenizer, der Regex-Mustervergleich verwendet, um unterschiedliche Token zu erstellen. Diese Tokenizer wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternTokenizer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor" />
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
            Initialisiert eine neue Instanz der PatternTokenizer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternTokenizer (string name, string pattern = null, Microsoft.Azure.Search.Models.RegexFlags flags = null, Nullable&lt;int&gt; group = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, class Microsoft.Azure.Search.Models.RegexFlags flags, valuetype System.Nullable`1&lt;int32&gt; group) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.#ctor(System.String,System.String,Microsoft.Azure.Search.Models.RegexFlags,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional pattern As String = null, Optional flags As RegexFlags = null, Optional group As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternTokenizer : string * string * Microsoft.Azure.Search.Models.RegexFlags * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.PatternTokenizer" Usage="new Microsoft.Azure.Search.Models.PatternTokenizer (name, pattern, flags, group)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="flags" Type="Microsoft.Azure.Search.Models.RegexFlags" />
        <Parameter Name="group" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des tokenizers. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="pattern">Muster eines regulären Ausdrucks mit token-Trennzeichen übereinstimmen. Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.</param>
        <param name="flags">Flags für reguläre Ausdrücke.</param>
        <param name="group">Die nullbasierte Ordnungszahl der entsprechenden Gruppe im Muster regulären Ausdrucks, in Token zu extrahieren. Verwenden Sie-1. wenn das gesamte Muster zu verwenden, um die Eingabe in Tokens, unabhängig von der übereinstimmenden Gruppen aufgeteilt werden sollen. Standard ist-1.</param>
        <summary>
            Initialisiert eine neue Instanz der PatternTokenizer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flags">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.RegexFlags Flags { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.RegexFlags Flags" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberSignature Language="VB.NET" Value="Public Property Flags As RegexFlags" />
      <MemberSignature Language="F#" Value="member this.Flags : Microsoft.Azure.Search.Models.RegexFlags with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Flags" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="flags")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.RegexFlags</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert Flags für reguläre Ausdrücke.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Group">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Group { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Group" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberSignature Language="VB.NET" Value="Public Property Group As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Group : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Group" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="group")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die nullbasierte Ordnungszahl der entsprechenden Gruppe im Muster regulären Ausdrucks, in Token zu extrahieren. Verwenden Sie-1. wenn das gesamte Muster zu verwenden, um die Eingabe in Tokens, unabhängig von der übereinstimmenden Gruppen aufgeteilt werden sollen. Standard ist-1.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternTokenizer.Pattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert ein Muster eines regulären Ausdrucks token-Trennzeichen übereinstimmen. Standard ist ein Ausdruck, der ein oder mehrere Leerzeichen übereinstimmt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternTokenizer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternTokenizer.Validate " />
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