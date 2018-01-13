<Type Name="PatternCaptureTokenFilter" FullName="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter">
  <TypeSignature Language="C#" Value="public class PatternCaptureTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PatternCaptureTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class PatternCaptureTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type PatternCaptureTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.PatternCaptureTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Java-Regexes wird für die Ausgabe von mehrere Token - eines für jede Erfassungsgruppe im ein oder mehrere Muster verwendet. Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/pattern/PatternCaptureGroupTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternCaptureTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.#ctor" />
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
            Initialisiert eine neue Instanz der PatternCaptureTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PatternCaptureTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; patterns, Nullable&lt;bool&gt; preserveOriginal = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; patterns, valuetype System.Nullable`1&lt;bool&gt; preserveOriginal) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, patterns As IList(Of String), Optional preserveOriginal As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.PatternCaptureTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.PatternCaptureTokenFilter" Usage="new Microsoft.Azure.Search.Models.PatternCaptureTokenFilter (name, patterns, preserveOriginal)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="patterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="preserveOriginal" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="patterns">Eine Liste von Mustern jedes Token verglichen werden soll.</param>
        <param name="preserveOriginal">Ein Wert, der angibt, ob die ursprünglichen Token zurück, auch wenn eines der Muster entspricht. Der Standardwert ist true.</param>
        <summary>
            Initialisiert eine neue Instanz der PatternCaptureTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patterns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Patterns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Patterns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Patterns" />
      <MemberSignature Language="VB.NET" Value="Public Property Patterns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Patterns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Patterns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="patterns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Mustern für die Überprüfung jedes Token Übereinstimmungen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreserveOriginal">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; PreserveOriginal { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; PreserveOriginal" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.PreserveOriginal" />
      <MemberSignature Language="VB.NET" Value="Public Property PreserveOriginal As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.PreserveOriginal : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.PreserveOriginal" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="preserveOriginal")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die ursprünglichen Token zurück, auch wenn eines der Muster entspricht. Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.PatternCaptureTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="patternCaptureTokenFilter.Validate " />
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