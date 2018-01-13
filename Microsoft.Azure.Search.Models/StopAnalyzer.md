<Type Name="StopAnalyzer" FullName="Microsoft.Azure.Search.Models.StopAnalyzer">
  <TypeSignature Language="C#" Value="public class StopAnalyzer : Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StopAnalyzer extends Microsoft.Azure.Search.Models.Analyzer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.StopAnalyzer" />
  <TypeSignature Language="VB.NET" Value="Public Class StopAnalyzer&#xA;Inherits Analyzer" />
  <TypeSignature Language="F#" Value="type StopAnalyzer = class&#xA;    inherit Analyzer" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.Analyzer</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.StopAnalyzer")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Teilt Text am nicht Buchstaben; Die Kleinbuchstaben und Stoppwort token Filter angewendet werden. Diese Analyzer wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/core/StopAnalyzer.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopAnalyzer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.#ctor" />
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
            Initialisiert eine neue Instanz der StopAnalyzer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StopAnalyzer (string name, System.Collections.Generic.IList&lt;string&gt; stopwords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; stopwords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.#ctor(System.String,System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional stopwords As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.StopAnalyzer : string * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Search.Models.StopAnalyzer" Usage="new Microsoft.Azure.Search.Models.StopAnalyzer (name, stopwords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="stopwords" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Analyzers. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="stopwords">Eine Liste von Stoppwörtern.</param>
        <summary>
            Initialisiert eine neue Instanz der StopAnalyzer-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stopwords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Stopwords { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Stopwords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.StopAnalyzer.Stopwords" />
      <MemberSignature Language="VB.NET" Value="Public Property Stopwords As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Stopwords : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.StopAnalyzer.Stopwords" />
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
            Ruft ab oder legt eine Liste von Stoppwörtern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.StopAnalyzer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="stopAnalyzer.Validate " />
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