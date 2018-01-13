<Type Name="NGramTokenFilterV2" FullName="Microsoft.Azure.Search.Models.NGramTokenFilterV2">
  <TypeSignature Language="C#" Value="public class NGramTokenFilterV2 : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NGramTokenFilterV2 extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.NGramTokenFilterV2" />
  <TypeSignature Language="VB.NET" Value="Public Class NGramTokenFilterV2&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type NGramTokenFilterV2 = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.NGramTokenFilterV2")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            N-gramme richtet, der den angegebenen VM-Größe(n) wird generiert. Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/ngram/NGramTokenFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor" />
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
            Initialisiert eine neue Instanz der NGramTokenFilterV2-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NGramTokenFilterV2 (string name, Nullable&lt;int&gt; minGram = null, Nullable&lt;int&gt; maxGram = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;int32&gt; minGram, valuetype System.Nullable`1&lt;int32&gt; maxGram) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.#ctor(System.String,System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional minGram As Nullable(Of Integer) = null, Optional maxGram As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 : string * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Search.Models.NGramTokenFilterV2" Usage="new Microsoft.Azure.Search.Models.NGramTokenFilterV2 (name, minGram, maxGram)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="minGram" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxGram" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="minGram">Die Mindestlänge für die n-gramme. Der Standardwert ist 1.
            Höchstwert beträgt 300. Kleiner als der Wert des MaxGram muss sein.</param>
        <param name="maxGram">Die maximale Länge von n-gramme. Standard ist 2.
            Höchstwert beträgt 300.</param>
        <summary>
            Initialisiert eine neue Instanz der NGramTokenFilterV2-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MaxGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Länge von n-gramme. Standard ist 2. Maximal:
            300.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MinGram">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MinGram { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MinGram" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
      <MemberSignature Language="VB.NET" Value="Public Property MinGram As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MinGram : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Search.Models.NGramTokenFilterV2.MinGram" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minGram")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die minimale Länge von n-gramme. Der Standardwert ist 1. Maximal:
            300. Kleiner als der Wert des MaxGram muss sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.NGramTokenFilterV2.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="nGramTokenFilterV2.Validate " />
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