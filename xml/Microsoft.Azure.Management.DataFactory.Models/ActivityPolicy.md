<Type Name="ActivityPolicy" FullName="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy">
  <TypeSignature Language="C#" Value="public class ActivityPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityPolicy" />
  <TypeSignature Language="F#" Value="type ActivityPolicy = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2477a-101">Die Ausführungsrichtlinie für eine Aktivität.</span><span class="sxs-lookup"><span data-stu-id="2477a-101">Execution policy for an activity.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityPolicy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2477a-102">Initialisiert eine neue Instanz der ActivityPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2477a-102">Initializes a new instance of the ActivityPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityPolicy (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, object timeout = null, object retry = null, Nullable&lt;int&gt; retryIntervalInSeconds = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, object timeout, object retry, valuetype System.Nullable`1&lt;int32&gt; retryIntervalInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.Object,System.Object,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional timeout As Object = null, Optional retry As Object = null, Optional retryIntervalInSeconds As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy : System.Collections.Generic.IDictionary&lt;string, obj&gt; * obj * obj * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy" Usage="new Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy (additionalProperties, timeout, retry, retryIntervalInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="timeout" Type="System.Object" />
        <Parameter Name="retry" Type="System.Object" />
        <Parameter Name="retryIntervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="2477a-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="2477a-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="timeout"><span data-ttu-id="2477a-104">Gibt das Zeitlimit für die Ausführung der Aktivität an.</span><span class="sxs-lookup"><span data-stu-id="2477a-104">Specifies the timeout for the activity to run.</span></span> <span data-ttu-id="2477a-105">Der Standardtimeout beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="2477a-105">The default timeout is 7 days.</span></span> <span data-ttu-id="2477a-106">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="2477a-106">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span></param>
        <param name="retry"><span data-ttu-id="2477a-107">Maximale Wiederholungsversuche gewöhnliche.</span><span class="sxs-lookup"><span data-stu-id="2477a-107">Maximum ordinary retry attempts.</span></span> <span data-ttu-id="2477a-108">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="2477a-108">Default is 0.</span></span>
            <span data-ttu-id="2477a-109">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimale:</span><span class="sxs-lookup"><span data-stu-id="2477a-109">Type: integer (or Expression with resultType integer), minimum:</span></span>
            0.</param>
        <param name="retryIntervalInSeconds"><span data-ttu-id="2477a-110">Intervall zwischen den Wiederholungsversuchen beim Senden (in Sekunden).</span><span class="sxs-lookup"><span data-stu-id="2477a-110">Interval between each retry attempt (in seconds).</span></span> <span data-ttu-id="2477a-111">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="2477a-111">The default is 30 sec.</span></span></param>
        <summary>
            <span data-ttu-id="2477a-112">Initialisiert eine neue Instanz der ActivityPolicy-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2477a-112">Initializes a new instance of the ActivityPolicy class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2477a-113">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="2477a-113">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="public object Retry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Retry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.Retry" />
      <MemberSignature Language="VB.NET" Value="Public Property Retry As Object" />
      <MemberSignature Language="F#" Value="member this.Retry : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.Retry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2477a-114">Ruft ab, oder legt ihn fest normale maximale Anzahl von Wiederholungsversuchen.</span><span class="sxs-lookup"><span data-stu-id="2477a-114">Gets or sets maximum ordinary retry attempts.</span></span> <span data-ttu-id="2477a-115">Der Standardwert ist 0.</span><span class="sxs-lookup"><span data-stu-id="2477a-115">Default is 0.</span></span> <span data-ttu-id="2477a-116">Typ: ganze Zahl (oder Ausdrücke mit ganzzahligen ResultType-Element), minimum: 0.</span><span class="sxs-lookup"><span data-stu-id="2477a-116">Type: integer (or Expression with resultType integer), minimum: 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryIntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; RetryIntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; RetryIntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.RetryIntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryIntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.RetryIntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.RetryIntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="retryIntervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2477a-117">Ruft ab oder legt das Intervall zwischen den Wiederholungsversuchen beim Senden (in Sekunden) fest.</span><span class="sxs-lookup"><span data-stu-id="2477a-117">Gets or sets interval between each retry attempt (in seconds).</span></span> <span data-ttu-id="2477a-118">Der Standardwert ist 30 Sekunden.</span><span class="sxs-lookup"><span data-stu-id="2477a-118">The default is 30 sec.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public object Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As Object" />
      <MemberSignature Language="F#" Value="member this.Timeout : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeout")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2477a-119">Ruft ab oder legt gibt das Timeout für die Aktivität ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2477a-119">Gets or sets specifies the timeout for the activity to run.</span></span> <span data-ttu-id="2477a-120">Der Standardtimeout beträgt 7 Tage.</span><span class="sxs-lookup"><span data-stu-id="2477a-120">The default timeout is 7 days.</span></span> <span data-ttu-id="2477a-121">Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</span><span class="sxs-lookup"><span data-stu-id="2477a-121">Type: string (or Expression with resultType string), pattern: ((\d+)\.)?(\d\d):(60|([0-5][0-9])):(60|([0-5][0-9])).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityPolicy.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="activityPolicy.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2477a-122">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2477a-122">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2477a-123">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2477a-123">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>