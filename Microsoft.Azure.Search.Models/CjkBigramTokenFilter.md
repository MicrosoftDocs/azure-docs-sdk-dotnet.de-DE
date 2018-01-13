<Type Name="CjkBigramTokenFilter" FullName="Microsoft.Azure.Search.Models.CjkBigramTokenFilter">
  <TypeSignature Language="C#" Value="public class CjkBigramTokenFilter : Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CjkBigramTokenFilter extends Microsoft.Azure.Search.Models.TokenFilter" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.CjkBigramTokenFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class CjkBigramTokenFilter&#xA;Inherits TokenFilter" />
  <TypeSignature Language="F#" Value="type CjkBigramTokenFilter = class&#xA;    inherit TokenFilter" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("#Microsoft.Azure.Search.CjkBigramTokenFilter")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Formulare digramme CJK-Begriffe, die von StandardTokenizer generiert werden.
            Dieser Filter token wird mithilfe von Apache Lucene implementiert.
            <see href="http://lucene.apache.org/core/4_10_3/analyzers-common/org/apache/lucene/analysis/cjk/CJKBigramFilter.html" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor" />
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
            Initialisiert eine neue Instanz der CjkBigramTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CjkBigramTokenFilter (string name, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts = null, Nullable&lt;bool&gt; outputUnigrams = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; ignoreScripts, valuetype System.Nullable`1&lt;bool&gt; outputUnigrams) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts},System.Nullable{System.Boolean})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional ignoreScripts As IList(Of CjkBigramTokenFilterScripts) = null, Optional outputUnigrams As Nullable(Of Boolean) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; * Nullable&lt;bool&gt; -&gt; Microsoft.Azure.Search.Models.CjkBigramTokenFilter" Usage="new Microsoft.Azure.Search.Models.CjkBigramTokenFilter (name, ignoreScripts, outputUnigrams)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="ignoreScripts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;" />
        <Parameter Name="outputUnigrams" Type="System.Nullable&lt;System.Boolean&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Filters token. Es darf nur Buchstaben, Ziffern, Leerzeichen, Bindestriche oder Unterstriche enthalten, beginnen und enden mit alphanumerischen Zeichen enthalten und ist auf 128 Zeichen beschränkt.</param>
        <param name="ignoreScripts">Die Skripts, ignoriert werden sollen.</param>
        <param name="outputUnigrams">Ein Wert, der angibt, ob sowohl monogramme als auch digramme (falls "true") ausgegeben oder nur digramme (Wenn "false").
            Die Standardeinstellung ist "false".</param>
        <summary>
            Initialisiert eine neue Instanz der CjkBigramTokenFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IgnoreScripts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;valuetype Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; IgnoreScripts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberSignature Language="VB.NET" Value="Public Property IgnoreScripts As IList(Of CjkBigramTokenFilterScripts)" />
      <MemberSignature Language="F#" Value="member this.IgnoreScripts : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.IgnoreScripts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ignoreScripts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.CjkBigramTokenFilterScripts&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Skripts, ignoriert werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputUnigrams">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; OutputUnigrams { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; OutputUnigrams" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputUnigrams As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.OutputUnigrams : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Search.Models.CjkBigramTokenFilter.OutputUnigrams" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputUnigrams")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob sowohl monogramme als auch digramme (falls "true") ausgegeben oder nur digramme (Wenn "false"). Die Standardeinstellung ist "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.CjkBigramTokenFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="cjkBigramTokenFilter.Validate " />
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