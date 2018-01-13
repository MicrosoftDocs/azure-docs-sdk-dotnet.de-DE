<Type Name="TelemetryClient" FullName="Microsoft.ApplicationInsights.TelemetryClient">
  <TypeSignature Language="C#" Value="public sealed class TelemetryClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.TelemetryClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryClient" />
  <TypeSignature Language="F#" Value="type TelemetryClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
    <AssemblyVersion>2.3.0.0</AssemblyVersion>
    <AssemblyVersion>2.5.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="a20df-101">Senden von Ereignissen, Metriken und andere Telemetrie an Application Insights-Dienst.</span><span class="sxs-lookup"><span data-stu-id="a20df-101">Send events, metrics and other telemetry to the Application Insights service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryClient ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.#ctor" />
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
            <span data-ttu-id="a20df-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a20df-102">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> class.</span></span> <span data-ttu-id="a20df-103">Senden Sie Telemetrie mit der aktiven Konfiguration in der Regel über deren ApplicationInsights.config geladen.</span><span class="sxs-lookup"><span data-stu-id="a20df-103">Send telemetry with the active configuration, usually loaded from ApplicationInsights.config.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryClient (Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.#ctor(Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As TelemetryConfiguration)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.TelemetryClient : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration -&gt; Microsoft.ApplicationInsights.TelemetryClient" Usage="new Microsoft.ApplicationInsights.TelemetryClient configuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
      </Parameters>
      <Docs>
        <param name="configuration">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a20df-104">Initializes a new instance of the <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> class.</span></span> <span data-ttu-id="a20df-105">Senden Sie Telemetrie mit dem angegebenen <paramref name="configuration" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-105">Send telemetry with the specified <paramref name="configuration" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="a20df-106">Die <paramref name="configuration" /> ist null.</span><span class="sxs-lookup"><span data-stu-id="a20df-106">The <paramref name="configuration" /> is null.</span></span></exception>
        <exception cref="T:System.ArgumentException"><span data-ttu-id="a20df-107">Die <paramref name="configuration" /> enthält keinen Telemetrie-Kanal.</span><span class="sxs-lookup"><span data-stu-id="a20df-107">The <paramref name="configuration" /> does not contain a telemetry channel.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="Context">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.DataContracts.TelemetryContext Context" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Context As TelemetryContext" />
      <MemberSignature Language="F#" Value="member this.Context : Microsoft.ApplicationInsights.DataContracts.TelemetryContext" Usage="Microsoft.ApplicationInsights.TelemetryClient.Context" />
      <MemberType>Property</MemberType>
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
            <span data-ttu-id="a20df-108">Ruft den aktuellen Kontext, der verwendet wird, um Telemetriedaten zu erweitern, die Sie senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-108">Gets the current context that will be used to augment telemetry you send.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Flush">
      <MemberSignature Language="C#" Value="public void Flush ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Flush() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Flush" />
      <MemberSignature Language="VB.NET" Value="Public Sub Flush ()" />
      <MemberSignature Language="F#" Value="member this.Flush : unit -&gt; unit" Usage="telemetryClient.Flush " />
      <MemberType>Method</MemberType>
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
            <span data-ttu-id="a20df-109">Leert den Puffer im Arbeitsspeicher.</span><span class="sxs-lookup"><span data-stu-id="a20df-109">Flushes the in-memory buffer.</span></span> 
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="public void Initialize (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Initialize(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Initialize(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Initialize (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="member this.Initialize : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="telemetryClient.Initialize telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="a20df-110">Telemetrie-Element initialisiert werden.</span><span class="sxs-lookup"><span data-stu-id="a20df-110">Telemetry item to initialize.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-111">Diese Methode ist eine interne Teil Application Insights-Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="a20df-111">This method is an internal part of Application Insights infrastructure.</span></span> <span data-ttu-id="a20df-112">Rufen Sie nicht.</span><span class="sxs-lookup"><span data-stu-id="a20df-112">Do not call.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstrumentationKey">
      <MemberSignature Language="C#" Value="public string InstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.TelemetryClient.InstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property InstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.InstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.TelemetryClient.InstrumentationKey" />
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
            <span data-ttu-id="a20df-113">Ruft ab oder legt den Instrumentation Standardschlüssel für alle <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Objekte in diesem protokolliert <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-113">Gets or sets the default instrumentation key for all <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> objects logged in this <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance bool IsEnabled() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public Function IsEnabled () As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : unit -&gt; bool" Usage="telemetryClient.IsEnabled " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="a20df-114">Überprüfen Sie, um festzustellen, ob die Überwachung aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="a20df-114">Check to determine if the tracking is enabled.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Track">
      <MemberSignature Language="C#" Value="public void Track (Microsoft.ApplicationInsights.Channel.ITelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Track(class Microsoft.ApplicationInsights.Channel.ITelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Track (telemetry As ITelemetry)" />
      <MemberSignature Language="F#" Value="member this.Track : Microsoft.ApplicationInsights.Channel.ITelemetry -&gt; unit" Usage="telemetryClient.Track telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.Channel.ITelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-115">Diese Methode ist eine interne Teil Application Insights-Infrastruktur.</span><span class="sxs-lookup"><span data-stu-id="a20df-115">This method is an internal part of Application Insights infrastructure.</span></span> <span data-ttu-id="a20df-116">Rufen Sie nicht.</span><span class="sxs-lookup"><span data-stu-id="a20df-116">Do not call.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackAvailability">
      <MemberSignature Language="C#" Value="public void TrackAvailability (Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackAvailability(class Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackAvailability (telemetry As AvailabilityTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackAvailability : Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry -&gt; unit" Usage="telemetryClient.TrackAvailability telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-117">Informationen über die Verfügbarkeit einer Anwendung zu senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-117">Send information about availability of an application.</span></span>
            <span data-ttu-id="a20df-118">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry" /> Instanz für jeden Aufruf an<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry)" /></span><span class="sxs-lookup"><span data-stu-id="a20df-118">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(Microsoft.ApplicationInsights.DataContracts.AvailabilityTelemetry)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackAvailability">
      <MemberSignature Language="C#" Value="public void TrackAvailability (string name, DateTimeOffset timeStamp, TimeSpan duration, string runLocation, bool success, string message = null, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackAvailability(string name, valuetype System.DateTimeOffset timeStamp, valuetype System.TimeSpan duration, string runLocation, bool success, string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackAvailability(System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackAvailability (name As String, timeStamp As DateTimeOffset, duration As TimeSpan, runLocation As String, success As Boolean, Optional message As String = null, Optional properties As IDictionary(Of String, String) = null, Optional metrics As IDictionary(Of String, Double) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackAvailability : string * DateTimeOffset * TimeSpan * string * bool * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackAvailability (name, timeStamp, duration, runLocation, success, message, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="timeStamp" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="runLocation" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a20df-119">Verfügbarkeit Testnamen an.</span><span class="sxs-lookup"><span data-stu-id="a20df-119">Availability test name.</span></span></param>
        <param name="timeStamp"><span data-ttu-id="a20df-120">Der Zeitpunkt, wenn die Verfügbarkeit aufgezeichnet wurden.</span><span class="sxs-lookup"><span data-stu-id="a20df-120">The time when the availability was captured.</span></span></param>
        <param name="duration"><span data-ttu-id="a20df-121">Die Zeit für die Verfügbarkeit Test ausführen.</span><span class="sxs-lookup"><span data-stu-id="a20df-121">The time taken for the availability test to run.</span></span></param>
        <param name="runLocation"><span data-ttu-id="a20df-122">Der Name des Speicherorts, von der Verfügbarkeit-Test ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-122">Name of the location the availability test was run from.</span></span></param>
        <param name="success"><span data-ttu-id="a20df-123">"True", wenn die Verfügbarkeit Test erfolgreich ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-123">True if the availability test ran successfully.</span></span></param>
        <param name="message"><span data-ttu-id="a20df-124">Die Fehlermeldung auf Verfügbarkeit Testlauf-Fehler.</span><span class="sxs-lookup"><span data-stu-id="a20df-124">Error message on availability test run failure.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-125">Mit dem Namen Zeichenfolgenwerte, die Sie verwenden können, zu klassifizieren und suchen Sie für diese Verfügbarkeit Telemetrie.</span><span class="sxs-lookup"><span data-stu-id="a20df-125">Named string values you can use to classify and search for this availability telemetry.</span></span></param>
        <param name="metrics"><span data-ttu-id="a20df-126">Weitere Werte, die diese Verfügbarkeit Telemetrie zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="a20df-126">Additional values associated with this availability telemetry.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-127">Informationen über die Verfügbarkeit einer Anwendung zu senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-127">Send information about availability of an application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(class Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (telemetry As DependencyTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry -&gt; unit" Usage="telemetryClient.TrackDependency telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-128">Informationen zur externen Abhängigkeit Aufruf in der Anwendung zu senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-128">Send information about external dependency call in the application.</span></span>
            <span data-ttu-id="a20df-129">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> Instanz für jeden Aufruf an<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry)" /></span><span class="sxs-lookup"><span data-stu-id="a20df-129">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(Microsoft.ApplicationInsights.DataContracts.DependencyTelemetry)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (string dependencyName, string commandName, DateTimeOffset startTime, TimeSpan duration, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(string dependencyName, string commandName, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (dependencyName As String, commandName As String, startTime As DateTimeOffset, duration As TimeSpan, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : string * string * DateTimeOffset * TimeSpan * bool -&gt; unit" Usage="telemetryClient.TrackDependency (dependencyName, commandName, startTime, duration, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="commandName" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dependencyName"><span data-ttu-id="a20df-130">Name der externen Abhängigkeit.</span><span class="sxs-lookup"><span data-stu-id="a20df-130">External dependency name.</span></span></param>
        <param name="commandName"><span data-ttu-id="a20df-131">Befehlsname Abhängigkeit-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="a20df-131">Dependency call command name.</span></span></param>
        <param name="startTime"><span data-ttu-id="a20df-132">Der Zeitpunkt, wenn die Abhängigkeit aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-132">The time when the dependency was called.</span></span></param>
        <param name="duration"><span data-ttu-id="a20df-133">Die Zeitdauer von externen Abhängigkeit für den Aufruf zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="a20df-133">The time taken by the external dependency to handle the call.</span></span></param>
        <param name="success"><span data-ttu-id="a20df-134">"True", wenn der Aufruf Abhängigkeit erfolgreich behandelt wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-134">True if the dependency call was handled successfully.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-135">Informationen zur externen Abhängigkeit Aufruf in der Anwendung zu senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-135">Send information about external dependency call in the application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackDependency">
      <MemberSignature Language="C#" Value="public void TrackDependency (string dependencyTypeName, string target, string dependencyName, string data, DateTimeOffset startTime, TimeSpan duration, string resultCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackDependency(string dependencyTypeName, string target, string dependencyName, string data, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string resultCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackDependency(System.String,System.String,System.String,System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackDependency (dependencyTypeName As String, target As String, dependencyName As String, data As String, startTime As DateTimeOffset, duration As TimeSpan, resultCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackDependency : string * string * string * string * DateTimeOffset * TimeSpan * string * bool -&gt; unit" Usage="telemetryClient.TrackDependency (dependencyTypeName, target, dependencyName, data, startTime, duration, resultCode, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dependencyTypeName" Type="System.String" />
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="dependencyName" Type="System.String" />
        <Parameter Name="data" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="resultCode" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="dependencyTypeName"><span data-ttu-id="a20df-136">Typ der externen Abhängigkeit.</span><span class="sxs-lookup"><span data-stu-id="a20df-136">External dependency type.</span></span></param>
        <param name="target"><span data-ttu-id="a20df-137">Externe Abhängigkeit-Ziel.</span><span class="sxs-lookup"><span data-stu-id="a20df-137">External dependency target.</span></span></param>
        <param name="dependencyName"><span data-ttu-id="a20df-138">Name der externen Abhängigkeit.</span><span class="sxs-lookup"><span data-stu-id="a20df-138">External dependency name.</span></span></param>
        <param name="data"><span data-ttu-id="a20df-139">Befehlsname Abhängigkeit-Aufruf.</span><span class="sxs-lookup"><span data-stu-id="a20df-139">Dependency call command name.</span></span></param>
        <param name="startTime"><span data-ttu-id="a20df-140">Der Zeitpunkt, wenn die Abhängigkeit aufgerufen wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-140">The time when the dependency was called.</span></span></param>
        <param name="duration"><span data-ttu-id="a20df-141">Die Zeitdauer von externen Abhängigkeit für den Aufruf zu behandeln.</span><span class="sxs-lookup"><span data-stu-id="a20df-141">The time taken by the external dependency to handle the call.</span></span></param>
        <param name="resultCode"><span data-ttu-id="a20df-142">Ergebniscode eines Abhängigkeit Aufruf ausführen.</span><span class="sxs-lookup"><span data-stu-id="a20df-142">Result code of dependency call execution.</span></span></param>
        <param name="success"><span data-ttu-id="a20df-143">"True", wenn der Aufruf Abhängigkeit erfolgreich behandelt wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-143">True if the dependency call was handled successfully.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-144">Informationen zur externen Abhängigkeit Aufruf in der Anwendung zu senden.</span><span class="sxs-lookup"><span data-stu-id="a20df-144">Send information about external dependency call in the application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackEvent">
      <MemberSignature Language="C#" Value="public void TrackEvent (Microsoft.ApplicationInsights.DataContracts.EventTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackEvent(class Microsoft.ApplicationInsights.DataContracts.EventTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(Microsoft.ApplicationInsights.DataContracts.EventTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackEvent (telemetry As EventTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackEvent : Microsoft.ApplicationInsights.DataContracts.EventTelemetry -&gt; unit" Usage="telemetryClient.TrackEvent telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.EventTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="a20df-145">Ein Ereignisprotokoll-Element.</span><span class="sxs-lookup"><span data-stu-id="a20df-145">An event log item.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-146">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> für unter "Diagnose suchen und Aggregationen im Explorer Metriken" anzeigen.</span><span class="sxs-lookup"><span data-stu-id="a20df-146">Send an <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> for display in Diagnostic Search and aggregation in Metrics Explorer.</span></span>
            <span data-ttu-id="a20df-147">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> Instanz für jeden Aufruf von <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(Microsoft.ApplicationInsights.DataContracts.EventTelemetry)" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-147">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(Microsoft.ApplicationInsights.DataContracts.EventTelemetry)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackEvent">
      <MemberSignature Language="C#" Value="public void TrackEvent (string eventName, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackEvent(string eventName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackEvent(System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackEvent (eventName As String, Optional properties As IDictionary(Of String, String) = null, Optional metrics As IDictionary(Of String, Double) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackEvent : string * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackEvent (eventName, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="eventName" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="eventName"><span data-ttu-id="a20df-148">Ein Name für das Ereignis.</span><span class="sxs-lookup"><span data-stu-id="a20df-148">A name for the event.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-149">Mit dem Namen Zeichenfolgenwerte, die Sie zum Suchen und Klassifizieren von Ereignissen verwenden können.</span><span class="sxs-lookup"><span data-stu-id="a20df-149">Named string values you can use to search and classify events.</span></span></param>
        <param name="metrics"><span data-ttu-id="a20df-150">Messungen, die dem Ereignis zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="a20df-150">Measurements associated with this event.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-151">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> für unter "Diagnose suchen und Aggregationen im Explorer Metriken" anzeigen.</span><span class="sxs-lookup"><span data-stu-id="a20df-151">Send an <see cref="T:Microsoft.ApplicationInsights.DataContracts.EventTelemetry" /> for display in Diagnostic Search and aggregation in Metrics Explorer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackException">
      <MemberSignature Language="C#" Value="public void TrackException (Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackException(class Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackException (telemetry As ExceptionTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackException : Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry -&gt; unit" Usage="telemetryClient.TrackException telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-152">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> für die Anzeige in der Diagnose Suche.</span><span class="sxs-lookup"><span data-stu-id="a20df-152">Send an <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> for display in Diagnostic Search.</span></span>
            <span data-ttu-id="a20df-153">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> Instanz für jeden Aufruf an<see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry)" /></span><span class="sxs-lookup"><span data-stu-id="a20df-153">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry)" /></span></span></summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackException">
      <MemberSignature Language="C#" Value="public void TrackException (Exception exception, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null, System.Collections.Generic.IDictionary&lt;string,double&gt; metrics = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackException(class System.Exception exception, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties, class System.Collections.Generic.IDictionary`2&lt;string, float64&gt; metrics) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackException(System.Exception,System.Collections.Generic.IDictionary{System.String,System.String},System.Collections.Generic.IDictionary{System.String,System.Double})" />
      <MemberSignature Language="F#" Value="member this.TrackException : Exception * System.Collections.Generic.IDictionary&lt;string, string&gt; * System.Collections.Generic.IDictionary&lt;string, double&gt; -&gt; unit" Usage="telemetryClient.TrackException (exception, properties, metrics)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="metrics" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="exception"><span data-ttu-id="a20df-154">Die zu protokollierende Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="a20df-154">The exception to log.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-155">Mit dem Namen Zeichenfolgenwerte, die Sie verwenden können, zu klassifizieren und suchen Sie für diese Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="a20df-155">Named string values you can use to classify and search for this exception.</span></span></param>
        <param name="metrics"><span data-ttu-id="a20df-156">Weitere Werte, die dieser Ausnahme zugeordnet werden.</span><span class="sxs-lookup"><span data-stu-id="a20df-156">Additional values associated with this exception.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-157">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> für die Anzeige in der Diagnose Suche.</span><span class="sxs-lookup"><span data-stu-id="a20df-157">Send an <see cref="T:Microsoft.ApplicationInsights.DataContracts.ExceptionTelemetry" /> for display in Diagnostic Search.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackMetric">
      <MemberSignature Language="C#" Value="public void TrackMetric (Microsoft.ApplicationInsights.DataContracts.MetricTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackMetric(class Microsoft.ApplicationInsights.DataContracts.MetricTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(Microsoft.ApplicationInsights.DataContracts.MetricTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackMetric (telemetry As MetricTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackMetric : Microsoft.ApplicationInsights.DataContracts.MetricTelemetry -&gt; unit" Usage="telemetryClient.TrackMetric telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-158">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> zum Darstellen von aggregierter metrischer Daten.</span><span class="sxs-lookup"><span data-stu-id="a20df-158">Send a <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> for representing aggregated metric data.</span></span>
            <span data-ttu-id="a20df-159">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> Instanz für jeden Aufruf von <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(Microsoft.ApplicationInsights.DataContracts.MetricTelemetry)" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-159">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(Microsoft.ApplicationInsights.DataContracts.MetricTelemetry)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackMetric">
      <MemberSignature Language="C#" Value="public void TrackMetric (string name, double value, System.Collections.Generic.IDictionary&lt;string,string&gt; properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackMetric(string name, float64 value, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackMetric(System.String,System.Double,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackMetric (name As String, value As Double, Optional properties As IDictionary(Of String, String) = null)" />
      <MemberSignature Language="F#" Value="member this.TrackMetric : string * double * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackMetric (name, value, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Double" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a20df-160">Der metrikname.</span><span class="sxs-lookup"><span data-stu-id="a20df-160">Metric name.</span></span></param>
        <param name="value"><span data-ttu-id="a20df-161">Metrischer Wert.</span><span class="sxs-lookup"><span data-stu-id="a20df-161">Metric value.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-162">Mit dem Namen Zeichenfolgenwerte, die Sie verwenden können, zu klassifizieren und Metriken zu filtern.</span><span class="sxs-lookup"><span data-stu-id="a20df-162">Named string values you can use to classify and filter metrics.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-163">Senden einer <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> für die Aggregation im Explorer Metrik.</span><span class="sxs-lookup"><span data-stu-id="a20df-163">Send a <see cref="T:Microsoft.ApplicationInsights.DataContracts.MetricTelemetry" /> for aggregation in Metric Explorer.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackPageView">
      <MemberSignature Language="C#" Value="public void TrackPageView (Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackPageView(class Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackPageView (telemetry As PageViewTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackPageView : Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry -&gt; unit" Usage="telemetryClient.TrackPageView telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-164">Senden Sie Informationen über die Seite in der Anwendung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a20df-164">Send information about the page viewed in the application.</span></span>
            <span data-ttu-id="a20df-165">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry" /> Instanz für jeden Aufruf von <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry)" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-165">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(Microsoft.ApplicationInsights.DataContracts.PageViewTelemetry)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackPageView">
      <MemberSignature Language="C#" Value="public void TrackPageView (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackPageView(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackPageView(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackPageView (name As String)" />
      <MemberSignature Language="F#" Value="member this.TrackPageView : string -&gt; unit" Usage="telemetryClient.TrackPageView name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a20df-166">Der Name der Seite.</span><span class="sxs-lookup"><span data-stu-id="a20df-166">Name of the page.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-167">Senden Sie Informationen über die Seite in der Anwendung angezeigt.</span><span class="sxs-lookup"><span data-stu-id="a20df-167">Send information about the page viewed in the application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackRequest">
      <MemberSignature Language="C#" Value="public void TrackRequest (Microsoft.ApplicationInsights.DataContracts.RequestTelemetry request);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackRequest(class Microsoft.ApplicationInsights.DataContracts.RequestTelemetry request) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackRequest (request As RequestTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackRequest : Microsoft.ApplicationInsights.DataContracts.RequestTelemetry -&gt; unit" Usage="telemetryClient.TrackRequest request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" />
      </Parameters>
      <Docs>
        <param name="request">To be added.</param>
        <summary>
            <span data-ttu-id="a20df-168">Senden Sie Informationen über eine Anforderung, die von der Anwendung behandelt.</span><span class="sxs-lookup"><span data-stu-id="a20df-168">Send information about a request handled by the application.</span></span>
            <span data-ttu-id="a20df-169">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> Instanz für jeden Aufruf von <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-169">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.RequestTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(Microsoft.ApplicationInsights.DataContracts.RequestTelemetry)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackRequest">
      <MemberSignature Language="C#" Value="public void TrackRequest (string name, DateTimeOffset startTime, TimeSpan duration, string responseCode, bool success);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackRequest(string name, valuetype System.DateTimeOffset startTime, valuetype System.TimeSpan duration, string responseCode, bool success) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackRequest(System.String,System.DateTimeOffset,System.TimeSpan,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackRequest (name As String, startTime As DateTimeOffset, duration As TimeSpan, responseCode As String, success As Boolean)" />
      <MemberSignature Language="F#" Value="member this.TrackRequest : string * DateTimeOffset * TimeSpan * string * bool -&gt; unit" Usage="telemetryClient.TrackRequest (name, startTime, duration, responseCode, success)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="startTime" Type="System.DateTimeOffset" />
        <Parameter Name="duration" Type="System.TimeSpan" />
        <Parameter Name="responseCode" Type="System.String" />
        <Parameter Name="success" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="a20df-170">Der Anforderungsname.</span><span class="sxs-lookup"><span data-stu-id="a20df-170">The request name.</span></span></param>
        <param name="startTime"><span data-ttu-id="a20df-171">Der Zeitpunkt, wenn die Seite angefordert wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-171">The time when the page was requested.</span></span></param>
        <param name="duration"><span data-ttu-id="a20df-172">Die Zeit, die von der Anwendung zur Verarbeitung der Anforderung.</span><span class="sxs-lookup"><span data-stu-id="a20df-172">The time taken by the application to handle the request.</span></span></param>
        <param name="responseCode"><span data-ttu-id="a20df-173">Der Statuscode der Antwort.</span><span class="sxs-lookup"><span data-stu-id="a20df-173">The response status code.</span></span></param>
        <param name="success"><span data-ttu-id="a20df-174">"True", wenn die Anforderung erfolgreich, von der Anwendung verarbeitet wurde.</span><span class="sxs-lookup"><span data-stu-id="a20df-174">True if the request was handled successfully by the application.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-175">Senden Sie Informationen über eine Anforderung, die von der Anwendung behandelt.</span><span class="sxs-lookup"><span data-stu-id="a20df-175">Send information about a request handled by the application.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (Microsoft.ApplicationInsights.DataContracts.TraceTelemetry telemetry);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(class Microsoft.ApplicationInsights.DataContracts.TraceTelemetry telemetry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(Microsoft.ApplicationInsights.DataContracts.TraceTelemetry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (telemetry As TraceTelemetry)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : Microsoft.ApplicationInsights.DataContracts.TraceTelemetry -&gt; unit" Usage="telemetryClient.TrackTrace telemetry" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="telemetry" Type="Microsoft.ApplicationInsights.DataContracts.TraceTelemetry" />
      </Parameters>
      <Docs>
        <param name="telemetry"><span data-ttu-id="a20df-176">Die Nachricht mit der optionalen Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a20df-176">Message with optional properties.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-177">Senden Sie eine Ablaufverfolgungsmeldung für die Anzeige in der Diagnose Suche an.</span><span class="sxs-lookup"><span data-stu-id="a20df-177">Send a trace message for display in Diagnostic Search.</span></span>
            <span data-ttu-id="a20df-178">Erstellen Sie eine Separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.TraceTelemetry" /> Instanz für jeden Aufruf von <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(Microsoft.ApplicationInsights.DataContracts.TraceTelemetry)" />.</span><span class="sxs-lookup"><span data-stu-id="a20df-178">Create a separate <see cref="T:Microsoft.ApplicationInsights.DataContracts.TraceTelemetry" /> instance for each call to <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(Microsoft.ApplicationInsights.DataContracts.TraceTelemetry)" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (message As String)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string -&gt; unit" Usage="telemetryClient.TrackTrace message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="a20df-179">Anzuzeigende Meldung.</span><span class="sxs-lookup"><span data-stu-id="a20df-179">Message to display.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-180">Senden Sie eine Ablaufverfolgungsmeldung für die Anzeige in der Diagnose Suche an.</span><span class="sxs-lookup"><span data-stu-id="a20df-180">Send a trace message for display in Diagnostic Search.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, valuetype Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,Microsoft.ApplicationInsights.DataContracts.SeverityLevel)" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * Microsoft.ApplicationInsights.DataContracts.SeverityLevel -&gt; unit" Usage="telemetryClient.TrackTrace (message, severityLevel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="severityLevel" Type="Microsoft.ApplicationInsights.DataContracts.SeverityLevel" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="a20df-181">Anzuzeigende Meldung.</span><span class="sxs-lookup"><span data-stu-id="a20df-181">Message to display.</span></span></param>
        <param name="severityLevel"><span data-ttu-id="a20df-182">Schweregrad der Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="a20df-182">Trace severity level.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-183">Senden Sie eine Ablaufverfolgungsmeldung für die Anzeige in der Diagnose Suche an.</span><span class="sxs-lookup"><span data-stu-id="a20df-183">Send a trace message for display in Diagnostic Search.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub TrackTrace (message As String, properties As IDictionary(Of String, String))" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackTrace (message, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="a20df-184">Anzuzeigende Meldung.</span><span class="sxs-lookup"><span data-stu-id="a20df-184">Message to display.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-185">Mit dem Namen Zeichenfolgenwerte, die Sie zum Suchen und Klassifizieren von Ereignissen verwenden können.</span><span class="sxs-lookup"><span data-stu-id="a20df-185">Named string values you can use to search and classify events.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-186">Senden Sie eine Ablaufverfolgungsmeldung für die Anzeige in der Diagnose Suche an.</span><span class="sxs-lookup"><span data-stu-id="a20df-186">Send a trace message for display in Diagnostic Search.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrackTrace">
      <MemberSignature Language="C#" Value="public void TrackTrace (string message, Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel, System.Collections.Generic.IDictionary&lt;string,string&gt; properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void TrackTrace(string message, valuetype Microsoft.ApplicationInsights.DataContracts.SeverityLevel severityLevel, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.TelemetryClient.TrackTrace(System.String,Microsoft.ApplicationInsights.DataContracts.SeverityLevel,System.Collections.Generic.IDictionary{System.String,System.String})" />
      <MemberSignature Language="F#" Value="member this.TrackTrace : string * Microsoft.ApplicationInsights.DataContracts.SeverityLevel * System.Collections.Generic.IDictionary&lt;string, string&gt; -&gt; unit" Usage="telemetryClient.TrackTrace (message, severityLevel, properties)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="severityLevel" Type="Microsoft.ApplicationInsights.DataContracts.SeverityLevel" />
        <Parameter Name="properties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="message"><span data-ttu-id="a20df-187">Anzuzeigende Meldung.</span><span class="sxs-lookup"><span data-stu-id="a20df-187">Message to display.</span></span></param>
        <param name="severityLevel"><span data-ttu-id="a20df-188">Schweregrad der Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="a20df-188">Trace severity level.</span></span></param>
        <param name="properties"><span data-ttu-id="a20df-189">Mit dem Namen Zeichenfolgenwerte, die Sie zum Suchen und Klassifizieren von Ereignissen verwenden können.</span><span class="sxs-lookup"><span data-stu-id="a20df-189">Named string values you can use to search and classify events.</span></span></param>
        <summary>
            <span data-ttu-id="a20df-190">Senden Sie eine Ablaufverfolgungsmeldung für die Anzeige in der Diagnose Suche an.</span><span class="sxs-lookup"><span data-stu-id="a20df-190">Send a trace message for display in Diagnostic Search.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>