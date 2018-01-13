<Type Name="TagScoringFunction" FullName="Microsoft.Azure.Search.Models.TagScoringFunction">
  <TypeSignature Language="C#" Value="public class TagScoringFunction : Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TagScoringFunction extends Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.TagScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class TagScoringFunction&#xA;Inherits ScoringFunction" />
  <TypeSignature Language="F#" Value="type TagScoringFunction = class&#xA;    inherit ScoringFunction" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Search.Models.ScoringFunction</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("tag")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Definiert eine Funktion, die steigert die Bewertungen von Dokumenten mit Zeichenfolgenwerten, die einer angegebenen Liste von RFID-Transponder an.
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringFunction.#ctor" />
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
            Initialisiert eine neue Instanz der TagScoringFunction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagScoringFunction (string fieldName, double boost, Microsoft.Azure.Search.Models.TagScoringParameters parameters, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, class Microsoft.Azure.Search.Models.TagScoringParameters parameters, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringFunction.#ctor(System.String,System.Double,Microsoft.Azure.Search.Models.TagScoringParameters,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, parameters As TagScoringParameters, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TagScoringFunction : string * double * Microsoft.Azure.Search.Models.TagScoringParameters * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.TagScoringFunction" Usage="new Microsoft.Azure.Search.Models.TagScoringFunction (fieldName, boost, parameters, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.TagScoringParameters" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">Der Name des Felds als Eingabe für die Bewertungsfunktion verwendet werden soll.</param>
        <param name="boost">Ein Multiplikator für die rohbewertung. Muss eine positive Zahl sein nicht gleich 1.0.</param>
        <param name="parameters">Parameterwerte für das Tag Bewertungsfunktion.</param>
        <param name="interpolation">Ein Wert, der angibt, wie das Verstärkung über Dokument Bewertungen interpoliert werden wird. Der Standardwert ist "Linear". Folgende Werte sind möglich: "linear", "konstant", "quadratische", "logarithmisch"</param>
        <summary>
            Initialisiert eine neue Instanz der TagScoringFunction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TagScoringFunction (string fieldName, double boost, string tagsParameter, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, string tagsParameter, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringFunction.#ctor(System.String,System.Double,System.String,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, tagsParameter As String, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.TagScoringFunction : string * double * string * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.TagScoringFunction" Usage="new Microsoft.Azure.Search.Models.TagScoringFunction (fieldName, boost, tagsParameter, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="tagsParameter" Type="System.String" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">To be added.</param>
        <param name="boost">To be added.</param>
        <param name="tagsParameter">To be added.</param>
        <param name="interpolation">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der TagScoringFunction-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.TagScoringParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.TagScoringParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.TagScoringFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As TagScoringParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.TagScoringParameters with get, set" Usage="Microsoft.Azure.Search.Models.TagScoringFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="tag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.TagScoringParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen von Parameterwerten für das Tag Bewertungsfunktion.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.TagScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="tagScoringFunction.Validate " />
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