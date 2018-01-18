<Type Name="DistanceScoringFunction" FullName="Microsoft.Azure.Search.Models.DistanceScoringFunction">
  <TypeSignature Language="C#" Value="public class DistanceScoringFunction : Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DistanceScoringFunction extends Microsoft.Azure.Search.Models.ScoringFunction" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.DistanceScoringFunction" />
  <TypeSignature Language="VB.NET" Value="Public Class DistanceScoringFunction&#xA;Inherits ScoringFunction" />
  <TypeSignature Language="F#" Value="type DistanceScoringFunction = class&#xA;    inherit ScoringFunction" />
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
      <AttributeName>Newtonsoft.Json.JsonObject("distance")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="b97a6-101">Definiert eine Funktion, die Ergebnisse basierend auf den Abstand zwischen einem geografischen Ort steigert.</span><span class="sxs-lookup"><span data-stu-id="b97a6-101">Defines a function that boosts scores based on distance from a geographic location.</span></span>
            <see href="https://docs.microsoft.com/rest/api/searchservice/Add-scoring-profiles-to-a-search-index" /></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor" />
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
            <span data-ttu-id="b97a6-102">Initialisiert eine neue Instanz der DistanceScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b97a6-102">Initializes a new instance of the DistanceScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction (string fieldName, double boost, Microsoft.Azure.Search.Models.DistanceScoringParameters parameters, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, class Microsoft.Azure.Search.Models.DistanceScoringParameters parameters, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor(System.String,System.Double,Microsoft.Azure.Search.Models.DistanceScoringParameters,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, parameters As DistanceScoringParameters, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DistanceScoringFunction : string * double * Microsoft.Azure.Search.Models.DistanceScoringParameters * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.DistanceScoringFunction" Usage="new Microsoft.Azure.Search.Models.DistanceScoringFunction (fieldName, boost, parameters, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Search.Models.DistanceScoringParameters" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName"><span data-ttu-id="b97a6-103">Der Name des Felds als Eingabe für die Bewertungsfunktion verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="b97a6-103">The name of the field used as input to the scoring function.</span></span></param>
        <param name="boost"><span data-ttu-id="b97a6-104">Ein Multiplikator für die rohbewertung.</span><span class="sxs-lookup"><span data-stu-id="b97a6-104">A multiplier for the raw score.</span></span> <span data-ttu-id="b97a6-105">Muss eine positive Zahl sein nicht gleich 1.0.</span><span class="sxs-lookup"><span data-stu-id="b97a6-105">Must be a positive number not equal to 1.0.</span></span></param>
        <param name="parameters"><span data-ttu-id="b97a6-106">Parameterwerte für den Abstand Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="b97a6-106">Parameter values for the distance scoring function.</span></span></param>
        <param name="interpolation"><span data-ttu-id="b97a6-107">Ein Wert, der angibt, wie das Verstärkung über Dokument Bewertungen interpoliert werden wird. Der Standardwert ist "Linear".</span><span class="sxs-lookup"><span data-stu-id="b97a6-107">A value indicating how boosting will be interpolated across document scores; defaults to "Linear".</span></span> <span data-ttu-id="b97a6-108">Folgende Werte sind möglich: "linear", "konstant", "quadratische", "logarithmisch"</span><span class="sxs-lookup"><span data-stu-id="b97a6-108">Possible values include: 'linear', 'constant', 'quadratic', 'logarithmic'</span></span></param>
        <summary>
            <span data-ttu-id="b97a6-109">Initialisiert eine neue Instanz der DistanceScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b97a6-109">Initializes a new instance of the DistanceScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DistanceScoringFunction (string fieldName, double boost, string referencePointParameter, double boostingDistance, Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string fieldName, float64 boost, string referencePointParameter, float64 boostingDistance, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; interpolation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.#ctor(System.String,System.Double,System.String,System.Double,System.Nullable{Microsoft.Azure.Search.Models.ScoringFunctionInterpolation})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fieldName As String, boost As Double, referencePointParameter As String, boostingDistance As Double, Optional interpolation As Nullable(Of ScoringFunctionInterpolation) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.DistanceScoringFunction : string * double * string * double * Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt; -&gt; Microsoft.Azure.Search.Models.DistanceScoringFunction" Usage="new Microsoft.Azure.Search.Models.DistanceScoringFunction (fieldName, boost, referencePointParameter, boostingDistance, interpolation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fieldName" Type="System.String" />
        <Parameter Name="boost" Type="System.Double" />
        <Parameter Name="referencePointParameter" Type="System.String" />
        <Parameter Name="boostingDistance" Type="System.Double" />
        <Parameter Name="interpolation" Type="System.Nullable&lt;Microsoft.Azure.Search.Models.ScoringFunctionInterpolation&gt;" />
      </Parameters>
      <Docs>
        <param name="fieldName">To be added.</param>
        <param name="boost">To be added.</param>
        <param name="referencePointParameter">To be added.</param>
        <param name="boostingDistance">To be added.</param>
        <param name="interpolation">To be added.</param>
        <summary>
            <span data-ttu-id="b97a6-110">Initialisiert eine neue Instanz der DistanceScoringFunction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="b97a6-110">Initializes a new instance of the DistanceScoringFunction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Search.Models.DistanceScoringParameters Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Search.Models.DistanceScoringParameters Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.DistanceScoringFunction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As DistanceScoringParameters" />
      <MemberSignature Language="F#" Value="member this.Parameters : Microsoft.Azure.Search.Models.DistanceScoringParameters with get, set" Usage="Microsoft.Azure.Search.Models.DistanceScoringFunction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="distance")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Search.Models.DistanceScoringParameters</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="b97a6-111">Abrufen oder Festlegen der Parameterwerte für den Abstand Bewertungsfunktion.</span><span class="sxs-lookup"><span data-stu-id="b97a6-111">Gets or sets parameter values for the distance scoring function.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.DistanceScoringFunction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="distanceScoringFunction.Validate " />
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
            <span data-ttu-id="b97a6-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="b97a6-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="b97a6-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="b97a6-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>