<Type Name="PatternReplaceCharFilter" FullName="Microsoft.Azure.Search.Models.PatternReplaceCharFilter">
  <TypeSignature Language="C#" Value="public class PatternReplaceCharFilter : Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternReplaceCharFilter extends Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternReplaceCharFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternReplaceCharFilter&#xA;Inherits CharFilter" />
  <TypeSignature Language="F#" Value="type PatternReplaceCharFilter = class&#xA;    inherit CharFilter" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.CharFilter</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternReplaceCharFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein Zeichen-Filter, der Zeichen in der Eingabezeichenfolge ersetzt. Er verwendet einen regulären Ausdruck zur Identifizierung von Zeichensequenzen erhalten bleiben und einem Ersetzungsmuster zum Identifizieren von Zeichen ersetzen. Beispielsweise Muster zugewiesen Eingabetext "aa-bb-aa-bb", "(aa)\s+(bb)", und ersetzen "$1#$ 2", "aa #bb aa #bb" ergeben würde. Dieser Filter Zeichen wird mithilfe von Apache Lucene implementiert.
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternReplaceCharFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceCharFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceCharFilter.#ctor" />
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
            Initialisiert eine neue Instanz der PatternReplaceCharFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternReplaceCharFilter (string name, string pattern, string replacement);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string pattern, string replacement) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceCharFilter.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, pattern As String, replacement As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternReplaceCharFilter : string * string * string -&gt; Microsoft.Azure.Search.Models.PatternReplaceCharFilter" Usage="new Microsoft.Azure.Search.Models.PatternReplaceCharFilter (name, pattern, replacement)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="pattern" Type="System.String" />
        <Parameter Name="replacement" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters Char. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="pattern">Das Muster eines regulären Ausdrucks.</param>
        <param name="replacement">Der Ersetzungstext.</param>
        <summary>
            Initialisiert eine neue Instanz der PatternReplaceCharFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pattern">
      <MemberSignature Language="C#" Value="public string Pattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Pattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceCharFilter.Pattern" />
      <MemberSignature Language="VB.NET" Value="Public Property Pattern As String" />
      <MemberSignature Language="F#" Value="member this.Pattern : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceCharFilter.Pattern" />
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
            Ruft ab, oder legt ihn fest Muster eines regulären Ausdrucks.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Replacement">
      <MemberSignature Language="C#" Value="public string Replacement { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Replacement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternReplaceCharFilter.Replacement" />
      <MemberSignature Language="VB.NET" Value="Public Property Replacement As String" />
      <MemberSignature Language="F#" Value="member this.Replacement : string with get, set" Usage="Microsoft.Azure.Search.Models.PatternReplaceCharFilter.Replacement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="replacement")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Ersetzungstext.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternReplaceCharFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternReplaceCharFilter.Validate " />
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