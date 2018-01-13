<Type Name="SynonymTokenFilter" FullName="Microsoft.Azure.Search.Models.SynonymTokenFilter">
  <TypeSignature Language="C#" Value="public class SynonymTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SynonymTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.SynonymTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class SynonymTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type SynonymTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.SynonymTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Entspricht einem oder mehreren Wörtern Synonyme in einem token Datenstrom. Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/synonym/SynonymFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor" />
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
            Initialisiert eine neue Instanz der SynonymTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SynonymTokenFilter (string name, System.Collections.Generic.IList&lt;string&gt; synonyms, Nullable&lt;bool&gt; ignoreCase = null, Nullable&lt;bool&gt; expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;string&gt; synonyms, valuetype System.Nullable`1&lt;bool&gt; ignoreCase, valuetype System.Nullable`1&lt;bool&gt; expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.#ctor(System.String,System.Collections.Generic.IList{System.String},System.Nullable{System.Boolean},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, synonyms As IList(Of String), Optional ignoreCase As Nullable(Of Boolean) = null, Optional expand As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.SynonymTokenFilter : string * System.Collections.Generic.IList&lt;string&gt; * Nullable&lt;bool&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.SynonymTokenFilter" Usage="new Microsoft.Azure.Search.Models.SynonymTokenFilter (name, synonyms, ignoreCase, expand)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="synonyms" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="ignoreCase" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="expand" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="synonyms">Eine Liste von Synonymen in einem der beiden Formate: 1. unglaubliche, unglaublichen, fabulous =&gt; erstaunlich - alle Begriffe auf der linken Seite des =&gt; Symbol ersetzt werden alle Bedingungen auf der rechten Seite ist; 2. unglaubliche, unglaublichen, fabulous, erstaunliche - durch Trennzeichen getrennte Liste von Wörtern entspricht. Legen Sie die Expand-Option zu ändern, wie diese Liste interpretiert wird.</param>
        <param name="ignoreCase">Ein Wert, der angibt, ob case-fold Eingabe für den Abgleich. Die Standardeinstellung ist "false".</param>
        <param name="expand">Ein Wert, der angibt, ob alle Wörter in der Liste von Synonymen (Wenn =&gt; Notation wird nicht verwendet) miteinander zugeordnet wird. Bei "true", alle Wörter in der Liste von Synonymen (Wenn =&gt; Notation wird nicht verwendet) miteinander zugeordnet wird. In der folgenden Liste: unglaubliche, unglaublichen, fabulous, erstaunlich entspricht: unglaubliche, unglaublichen, fabulous, erstaunlich =&gt; unglaubliche, unglaublichen, fabulous, erstaunlich. Wenn "false" in der folgenden Liste: unglaubliche, unglaublichen, fabulous, erstaunlich werden entspricht: unglaubliche, unglaublichen, fabulous, erstaunlich =&gt; unglaubliche.
            Der Standardwert ist true.</param>
        <summary>
            Initialisiert eine neue Instanz der SynonymTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expand">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Expand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Expand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberSignature Language="VB.NET" Value="Public Property Expand As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Expand : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Expand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob alle Wörter in der Liste der Synonyme fest (Wenn =&amp;Gt; Notation wird nicht verwendet) miteinander zugeordnet wird. Bei "true", alle Wörter in der Liste von Synonymen (Wenn =&amp;Gt; Notation wird nicht verwendet) miteinander zugeordnet wird. In der folgenden Liste: unglaubliche, unglaublichen, fabulous, erstaunlich entspricht: unglaubliche, unglaublichen, fabulous, erstaunlich =&amp;Gt; unglaubliche, unglaublichen, fabulous, erstaunlich. Wenn "false" in der folgenden Liste: unglaubliche, unglaublichen, fabulous, erstaunlich werden entspricht: unglaubliche, unglaublichen, fabulous, erstaunlich =&amp;Gt; unglaubliche.
            Der Standardwert ist true.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreCase">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IgnoreCase { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IgnoreCase" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreCase As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IgnoreCase : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.IgnoreCase" />
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
            Ermittelt oder definiert einen Wert, der angibt, ob das case-fold Eingabe für den Abgleich. Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Synonyms">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; Synonyms { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; Synonyms" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberSignature Language="VB.NET" Value="Public Property Synonyms As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.Synonyms : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Search.Models.SynonymTokenFilter.Synonyms" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="synonyms")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Synonymen in einem der beiden Formate: 1.
            unglaubliche, unglaublichen, fabulous =&amp;Gt; erstaunliche - alle Begriffe auf der linken Seite des =&amp;Gt; alle Begriffe auf der rechten Seite ist; Symbol ersetzt werden 2. unglaubliche, unglaublichen, fabulous, erstaunliche - durch Trennzeichen getrennte Liste von Wörtern entspricht. Legen Sie die Expand-Option zu ändern, wie diese Liste interpretiert wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.SynonymTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="synonymTokenFilter.Validate " />
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