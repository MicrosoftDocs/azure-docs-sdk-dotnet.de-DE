<Type Name="ScoringProfile" FullName="Microsoft.Azure.Search.Models.ScoringProfile">
  <TypeSignature Language="C#" Value="public class ScoringProfile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ScoringProfile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.ScoringProfile" />
  <TypeSignature Language="VB.NET" Value="Public Class ScoringProfile" />
  <TypeSignature Language="F#" Value="type ScoringProfile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Definiert Parameter für einen Azure Search-Index, die in Suchabfragen Bewertung beeinflussen.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.#ctor" />
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
            Initialisiert eine neue Instanz der ScoringProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ScoringProfile (string name, Microsoft.Azure.Search.Models.TextWeights textWeights = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; functions = null, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; functionAggregation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, class Microsoft.Azure.Search.Models.TextWeights textWeights, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringFunction&gt; functions, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; functionAggregation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.#ctor(System.String,Microsoft.Azure.Search.Models.TextWeights,System.Collections.Generic.IList{Microsoft.Azure.Search.Models.ScoringFunction},System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionAggregation})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.ScoringProfile : string * Microsoft.Azure.Search.Models.TextWeights * System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; -&gt; Microsoft.Azure.Search.Models.ScoringProfile" Usage="new Microsoft.Azure.Search.Models.ScoringProfile (name, textWeights, functions, functionAggregation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="textWeights" Type="Microsoft.Azure.Search.Models.TextWeights" />
        <Parameter Name="functions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt;" />
        <Parameter Name="functionAggregation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt;" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des Bewertungsprofils.</param>
        <param name="textWeights">Parameter, die zur Verbesserung der Bewertung anhand von Übereinstimmungen von Text in bestimmten Indexfeldern ab.</param>
        <param name="functions">Die Auflistung von Funktionen, die die Bewertung von Dokumenten zu beeinflussen.</param>
        <param name="functionAggregation">Ein Wert, der angibt, wie die Ergebnisse der einzelnen Funktionen zur entfernungsbewertung kombiniert werden sollen.
            Der Standardwert ist "Summe". Ignoriert, wenn keine Funktionen zur entfernungsbewertung vorhanden sind.
            Folgende Werte sind möglich: "Sum", "Mittelwert", "minimum", "maximum", "FirstMatching"</param>
        <summary>
            Initialisiert eine neue Instanz der ScoringProfile-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FunctionAggregation">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; FunctionAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; FunctionAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.FunctionAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property FunctionAggregation As Nullable(Of ScoringFunctionAggregation)" />
      <MemberSignature Language="F#" Value="member this.FunctionAggregation : Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.FunctionAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="functionAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionAggregation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, wie die Ergebnisse der einzelnen Funktionen zur entfernungsbewertung kombiniert werden sollen. Der Standardwert ist "Summe". Ignoriert, wenn keine Funktionen zur entfernungsbewertung vorhanden sind. Folgende Werte sind möglich: "Sum", "Mittelwert", "minimum", "maximum", "FirstMatching"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; Functions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Search.Models.ScoringFunction&gt; Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.Functions" />
      <MemberSignature Language="VB.NET" Value="Public Property Functions As IList(Of ScoringFunction)" />
      <MemberSignature Language="F#" Value="member this.Functions : System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt; with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="functions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Search.Models.ScoringFunction&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Auflistung der Funktionen, die die Bewertung von Dokumenten zu beeinflussen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Bewertungsprofils.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TextWeights">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TextWeights TextWeights { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TextWeights TextWeights" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.ScoringProfile.TextWeights" />
      <MemberSignature Language="VB.NET" Value="Public Property TextWeights As TextWeights" />
      <MemberSignature Language="F#" Value="member this.TextWeights : Microsoft.Azure.Search.Models.TextWeights with get, set" Usage="Microsoft.Azure.Search.Models.ScoringProfile.TextWeights" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="text")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TextWeights</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Parameter dieser Boost Bewertung, die basierend auf Übereinstimmungen von Text in bestimmten Indexfeldern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.ScoringProfile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="scoringProfile.Validate " />
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