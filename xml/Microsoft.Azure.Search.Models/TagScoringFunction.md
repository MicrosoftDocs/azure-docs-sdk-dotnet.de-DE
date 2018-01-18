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
            <span data-ttu-id="08a4f-101">Definiert eine Funktion, die steigert die Bewertungen von Dokumenten mit Zeichenfolgenwerten, die einer angegebenen Liste von RFID-Transponder an.</span><span class="sxs-lookup"><span data-stu-id="08a4f-101">Defines a function that boosts scores of documents with string values matching a given list of tags.</span></span>
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
            <span data-ttu-id="08a4f-102">Initialisiert eine neue Instanz der TagScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08a4f-102">Initializes a new instance of the TagScoringFunction class.</span></span>
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
        <param name="fieldName"><span data-ttu-id="08a4f-103">Der Name des Felds als Eingabe für die Bewertungsfunktion verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="08a4f-103">The name of the field used as input to the scoring function.</span></span></param>
        <param name="boost"><span data-ttu-id="08a4f-104">Ein Multiplikator für die rohbewertung.</span><span class="sxs-lookup"><span data-stu-id="08a4f-104">A multiplier for the raw score.</span></span> <span data-ttu-id="08a4f-105">Muss eine positive Zahl sein nicht gleich 1.0.</span><span class="sxs-lookup"><span data-stu-id="08a4f-105">Must be a positive number not equal to 1.0.</span></span></param>
        <param name="parameters"><span data-ttu-id="08a4f-106">Parameterwerte für das Tag Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="08a4f-106">Parameter values for the tag scoring function.</span></span></param>
        <param name="interpolation"><span data-ttu-id="08a4f-107">Ein Wert, der angibt, wie das Verstärkung über Dokument Bewertungen interpoliert werden wird. Der Standardwert ist "Linear".</span><span class="sxs-lookup"><span data-stu-id="08a4f-107">A value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="08a4f-108">Folgende Werte sind möglich: "linear", "konstant", "quadratische", "logarithmisch"</span><span class="sxs-lookup"><span data-stu-id="08a4f-108">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span></param>
        <summary>
            <span data-ttu-id="08a4f-109">Initialisiert eine neue Instanz der TagScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08a4f-109">Initializes a new instance of the TagScoringFunction class.</span></span>
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
            <span data-ttu-id="08a4f-110">Initialisiert eine neue Instanz der TagScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="08a4f-110">Initializes a new instance of the TagScoringFunction class.</span></span>
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
            <span data-ttu-id="08a4f-111">Abrufen oder Festlegen von Parameterwerten für das Tag Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="08a4f-111">Gets or sets parameter values for the tag scoring function.</span></span>
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
            <span data-ttu-id="08a4f-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="08a4f-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="08a4f-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="08a4f-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>