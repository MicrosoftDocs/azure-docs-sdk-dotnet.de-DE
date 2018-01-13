<Type Name="MappingCharFilter" FullName="Microsoft.Azure.Search.Models.MappingCharFilter">
  <TypeSignature Language="C#" Value="public class MappingCharFilter : Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MappingCharFilter extends Microsoft.Azure.Search.Models.CharFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.MappingCharFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class MappingCharFilter&#xA;Inherits CharFilter" />
  <TypeSignature Language="F#" Value="type MappingCharFilter = class&#xA;    inherit CharFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.MappingCharFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein Zeichen-Filter, der Zuordnungen, die mit der Option Zuordnungen definiert gilt. Abgleich wird die gierigen (längste Musterabgleich an einem bestimmten Zeitpunkt Wins). Ersatz ist zulässig, die leere Zeichenfolge sein kann. Dieser Filter Zeichen wird mithilfe von Apache Lucene implementiert.
            <see href="https://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/charfilter/MappingCharFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MappingCharFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.#ctor" />
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
            Initialisiert eine neue Instanz der MappingCharFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MappingCharFilter (string name, System.Collections.Generic.IList&lt;string&gt; mappings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; mappings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, mappings As IList(Of String))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.MappingCharFilter : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.MappingCharFilter" Usage="new Microsoft.Azure.Search.Models.MappingCharFilter (name, mappings)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="mappings" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters Char. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="mappings">Eine Liste der Zuordnungen von das folgende Format: "eine =&gt;b" (alle Vorkommen des Zeichens "a" durch "b"-Zeichen ersetzt wird).</param>
        <summary>
            Initialisiert eine neue Instanz der MappingCharFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Mappings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Mappings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Mappings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.MappingCharFilter.Mappings" />
      <MemberSignature Language="VB.NET" Value="Public Property Mappings As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Mappings : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.MappingCharFilter.Mappings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mappings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Zuordnungen von das folgende Format: "eine =&amp;Gt; b" (alle Vorkommen des Zeichens "a" durch "b"-Zeichen ersetzt wird).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.MappingCharFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="mappingCharFilter.Validate " />
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