<Type Name="FreshnessScoringFunction" FullName="Microsoft.Azure.Search.Models.FreshnessScoringFunction">
  <TypeSignature Language="C#" Value="public class FreshnessScoringFunction : Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FreshnessScoringFunction extends Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.FreshnessScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class FreshnessScoringFunction&#xA;Inherits ScoringFunction" />
  <TypeSignature Language="F#" Value="type FreshnessScoringFunction = class&#xA;    inherit ScoringFunction" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("freshness")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="cfdf4-101">Definiert eine Funktion, die Ergebnisse basierend auf dem Wert, der einen Datums-/ Uhrzeitfeld steigert.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-101">Defines a function that boosts scores based on the value of a date-time field.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FreshnessScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringFunction.#ctor" />
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
            <span data-ttu-id="cfdf4-102">Initialisiert eine neue Instanz der FreshnessScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-102">Initializes a new instance of the FreshnessScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FreshnessScoringFunction (string fieldName, double boost, Microsoft.Azure.Search.Models.FreshnessScoringParameters parameters, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, class Microsoft.Azure.Search.Models.FreshnessScoringParameters parameters, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringFunction.#ctor(System.String,System.Double,Microsoft.Azure.Search.Models.FreshnessScoringParameters,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, parameters As FreshnessScoringParameters, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FreshnessScoringFunction : string * double * Microsoft.Azure.Search.Models.FreshnessScoringParameters * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.FreshnessScoringFunction" Usage="new Microsoft.Azure.Search.Models.FreshnessScoringFunction (fieldName, boost, parameters, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.FreshnessScoringParameters" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName"><span data-ttu-id="cfdf4-103">Der Name des Felds als Eingabe für die Bewertungsfunktion verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-103">The name of the field used as input to the scoring function.</span></span></param>
        <param name="boost"><span data-ttu-id="cfdf4-104">Ein Multiplikator für die rohbewertung.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-104">A multiplier for the raw score.</span></span> <span data-ttu-id="cfdf4-105">Muss eine positive Zahl sein nicht gleich 1.0.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-105">Must be a positive number not equal to 1.0.</span></span></param>
        <param name="parameters"><span data-ttu-id="cfdf4-106">Parameterwerte für die Aktualität Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-106">Parameter values for the freshness scoring function.</span></span></param>
        <param name="interpolation"><span data-ttu-id="cfdf4-107">Ein Wert, der angibt, wie das Verstärkung über Dokument Bewertungen interpoliert werden wird. Der Standardwert ist "Linear".</span><span class="sxs-lookup"><span data-stu-id="cfdf4-107">A value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="cfdf4-108">Folgende Werte sind möglich: "linear", "konstant", "quadratische", "logarithmisch"</span><span class="sxs-lookup"><span data-stu-id="cfdf4-108">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span></param>
        <summary>
            <span data-ttu-id="cfdf4-109">Initialisiert eine neue Instanz der FreshnessScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-109">Initializes a new instance of the FreshnessScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FreshnessScoringFunction (string fieldName, double boost, TimeSpan boostingDuration, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, valuetype System.TimeSpan boostingDuration, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringFunction.#ctor(System.String,System.Double,System.TimeSpan,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, boostingDuration As TimeSpan, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.FreshnessScoringFunction : string * double * TimeSpan * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.FreshnessScoringFunction" Usage="new Microsoft.Azure.Search.Models.FreshnessScoringFunction (fieldName, boost, boostingDuration, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="boostingDuration" Type="System.TimeSpan" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">To be added.</param>
        <param name="boost">To be added.</param>
        <param name="boostingDuration">To be added.</param>
        <param name="interpolation">To be added.</param>
        <summary>
            <span data-ttu-id="cfdf4-110">Initialisiert eine neue Instanz der FreshnessScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-110">Initializes a new instance of the FreshnessScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.FreshnessScoringParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.FreshnessScoringParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.FreshnessScoringFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As FreshnessScoringParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.FreshnessScoringParameters with get, set" Usage="Microsoft.Azure.Search.Models.FreshnessScoringFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="freshness")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.FreshnessScoringParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="cfdf4-111">Abrufen oder Festlegen der Parameterwerte für die Aktualität Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-111">Gets or sets parameter values for the freshness scoring function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.FreshnessScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="freshnessScoringFunction.Validate " />
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
            <span data-ttu-id="cfdf4-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="cfdf4-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="cfdf4-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="cfdf4-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>