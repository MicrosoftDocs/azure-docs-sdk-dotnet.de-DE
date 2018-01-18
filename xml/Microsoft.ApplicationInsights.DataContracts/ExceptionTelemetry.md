<Type Name="ExceptionTelemetry" FullName="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry">
  <TypeSignature Language="C#" Value="public sealed class ExceptionTelemetry : Microsoft.ApplicationInsights.Channel.ITelemetry, Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, Microsoft.ApplicationInsights.DataContracts.ISupportProperties, Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ExceptionTelemetry extends System.Object implements class Microsoft.ApplicationInsights.Channel.ITelemetry, class Microsoft.ApplicationInsights.DataContracts.ISupportMetrics, class Microsoft.ApplicationInsights.DataContracts.ISupportProperties, class Microsoft.ApplicationInsights.DataContracts.ISupportSampling" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ExceptionTelemetry&#xA;Implements ISupportMetrics, ISupportProperties, ISupportSampling, ITelemetry" />
  <TypeSignature Language="F#" Value="type ExceptionTelemetry = class&#xA;    interface ITelemetry&#xA;    interface ISupportProperties&#xA;    interface ISupportSampling&#xA;    interface ISupportMetrics" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.Channel.ITelemetry</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportMetrics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportProperties</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.ApplicationInsights.DataContracts.ISupportSampling</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="0027b-101">Ein Typ, der Telemetrie zum Nachverfolgen von Ausnahmen verwendet.</span><span class="sxs-lookup"><span data-stu-id="0027b-101">Telemetry type used to track exceptions.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionTelemetry ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0027b-102">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> Klasse mit leeren Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="0027b-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> class with empty properties.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExceptionTelemetry (Exception exception);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Exception exception) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.#ctor(System.Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry : Exception -&gt; Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" Usage="new Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry exception" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="0027b-103">Die Ausnahmeinstanz.</span><span class="sxs-lookup"><span data-stu-id="0027b-103">Exception instance.</span></span></param>
        <summary>
            <span data-ttu-id="0027b-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> Klasse mit leeren Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="0027b-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> class with empty properties.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Context" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Context</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.TelemetryContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-105">Ruft das aktuelle Element der Telemetrie zugeordneten Kontext.</span><span class="sxs-lookup"><span data-stu-id="0027b-105">Gets the context associated with the current telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeepClone">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ApplicationInsights.Channel.ITelemetry DeepClone() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.DeepClone" />
      <MemberSignature Language="VB.NET" Value="Public Function DeepClone () As ITelemetry" />
      <MemberSignature Language="F#" Value="abstract member DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry&#xA;override this.DeepClone : unit -&gt; Microsoft.ApplicationInsights.Channel.ITelemetry" Usage="exceptionTelemetry.DeepClone " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.DeepClone</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetry</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Exception" />
      <MemberSignature Language="VB.NET" Value="Public Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-106">Ruft ab oder legt die ursprüngliche Ausnahme, die von diesem nachverfolgt <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />.</span><span class="sxs-lookup"><span data-stu-id="0027b-106">Gets or sets the original exception tracked by this <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HandledAt">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt HandledAt { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt HandledAt" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.HandledAt" />
      <MemberSignature Language="VB.NET" Value="Public Property HandledAt As ExceptionHandledAt" />
      <MemberSignature Language="F#" Value="member this.HandledAt : Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.HandledAt" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use custom properties to report exception handling layer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.DataContracts.ExceptionHandledAt</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-107">Ruft ab oder legt, die der Wert angegeben, in dem die Ausnahme behandelt wurde.</span><span class="sxs-lookup"><span data-stu-id="0027b-107">Gets or sets the value indicated where the exception was handled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Message" />
      <MemberSignature Language="VB.NET" Value="Public Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-108">Ruft ab, oder legt Sie ExceptionTelemetry fest.</span><span class="sxs-lookup"><span data-stu-id="0027b-108">Gets or sets ExceptionTelemetry message.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metrics">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,double&gt; Metrics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; Metrics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Metrics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Metrics As IDictionary(Of String, Double)" />
      <MemberSignature Language="F#" Value="member this.Metrics : System.Collections.Generic.IDictionary&lt;string, double&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Metrics" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportMetrics.Metrics</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-109">Ruft ein Wörterbuch der Anwendung definierte Ausnahme Metriken ab.</span><span class="sxs-lookup"><span data-stu-id="0027b-109">Gets a dictionary of application-defined exception metrics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize">
      <MemberSignature Language="C#" Value="void ITelemetry.Sanitize ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance void Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Microsoft#ApplicationInsights#Channel#ITelemetry#Sanitize" />
      <MemberSignature Language="VB.NET" Value="Sub Sanitize () Implements ITelemetry.Sanitize" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.ApplicationInsights.Channel.ITelemetry.Sanitize</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0027b-110">Bereinigt die Eigenschaften, die auf Einschränkungen basieren.</span><span class="sxs-lookup"><span data-stu-id="0027b-110">Sanitizes the properties based on constraints.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage">
      <MemberSignature Language="C#" Value="Nullable&lt;double&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Microsoft#ApplicationInsights#DataContracts#ISupportSampling#SamplingPercentage" />
      <MemberSignature Language="VB.NET" Value=" Property SamplingPercentage As Nullable(Of Double) Implements ISupportSampling.SamplingPercentage" />
      <MemberSignature Language="F#" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportSampling.SamplingPercentage</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-111">Ruft ab, oder legt ihn fest Datenstichproben Prozentwert (zwischen 0 und 100).</span><span class="sxs-lookup"><span data-stu-id="0027b-111">Gets or sets data sampling percentage (between 0 and 100).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProblemId">
      <MemberSignature Language="C#" Value="public string ProblemId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProblemId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.ProblemId" />
      <MemberSignature Language="VB.NET" Value="Public Property ProblemId As String" />
      <MemberSignature Language="F#" Value="member this.ProblemId : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.ProblemId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Properties { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Properties" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Properties As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Properties : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Properties" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.DataContracts.ISupportProperties.Properties</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-112">Ruft ein Wörterbuch von anwendungsdefinierten Eigenschaftennamen und Werten, die zusätzliche Informationen über diese Ausnahme ab.</span><span class="sxs-lookup"><span data-stu-id="0027b-112">Gets a dictionary of application-defined property names and values providing additional information about this exception.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sequence">
      <MemberSignature Language="C#" Value="public string Sequence { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Sequence" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Sequence" />
      <MemberSignature Language="VB.NET" Value="Public Property Sequence As String" />
      <MemberSignature Language="F#" Value="member this.Sequence : string with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Sequence" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Sequence</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-113">Ruft ab oder legt den Wert an, der absolute Reihenfolge der Telemetrie-Elements definiert.</span><span class="sxs-lookup"><span data-stu-id="0027b-113">Gets or sets the value that defines absolute order of the telemetry item.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetParsedStack">
      <MemberSignature Language="C#" Value="public void SetParsedStack (System.Diagnostics.StackFrame[] frames);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetParsedStack(class System.Diagnostics.StackFrame[] frames) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.SetParsedStack(System.Diagnostics.StackFrame[])" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetParsedStack (frames As StackFrame())" />
      <MemberSignature Language="F#" Value="member this.SetParsedStack : System.Diagnostics.StackFrame[] -&gt; unit" Usage="exceptionTelemetry.SetParsedStack frames" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="frames" Type="System.Diagnostics.StackFrame[]" />
      </Parameters>
      <Docs>
        <param name="frames">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SeverityLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.ApplicationInsights.DataContracts.SeverityLevel&gt; SeverityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.ApplicationInsights.DataContracts.SeverityLevel&gt; SeverityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.SeverityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property SeverityLevel As Nullable(Of SeverityLevel)" />
      <MemberSignature Language="F#" Value="member this.SeverityLevel : Nullable&lt;Microsoft.ApplicationInsights.DataContracts.SeverityLevel&gt; with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.SeverityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.ApplicationInsights.DataContracts.SeverityLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-114">Abrufen oder Festlegen der Schweregrad der Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="0027b-114">Gets or sets Exception severity level.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTimeOffset Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTimeOffset Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTimeOffset" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTimeOffset with get, set" Usage="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry.Timestamp" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTimeOffset</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0027b-115">Ruft ab oder legt Datum und Uhrzeit, wann Telemetrie aufgezeichnet wurde.</span><span class="sxs-lookup"><span data-stu-id="0027b-115">Gets or sets date and time when telemetry was recorded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>