<Type Name="TelemetryConfiguration" FullName="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration">
  <TypeSignature Language="C#" Value="public sealed class TelemetryConfiguration : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TelemetryConfiguration extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TelemetryConfiguration&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TelemetryConfiguration = class&#xA;    interface IDisposable" />
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
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="36e11-101">Kapselt die globalen Telemetrie-Konfiguration, die in der Regel aus deren ApplicationInsights.config-Datei geladen.</span><span class="sxs-lookup"><span data-stu-id="36e11-101">Encapsulates the global telemetry configuration typically loaded from the ApplicationInsights.config file.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="36e11-102">Alle <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> Objekte initialisiert werden, mithilfe der <see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" /> Telemetrie-Konfiguration, die von dieser Klasse bereitgestellten.</span><span class="sxs-lookup"><span data-stu-id="36e11-102">All <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> objects are initialized using the <see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" /> telemetry configuration provided by this class.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
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
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36e11-103">Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="36e11-103">Initializes a new instance of the TelemetryConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration (string instrumentationKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string instrumentationKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instrumentationKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration : string -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration instrumentationKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instrumentationKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instrumentationKey"><span data-ttu-id="36e11-104">Instrumentierungsschlüssel bietet diese konfigurationsinstanz.</span><span class="sxs-lookup"><span data-stu-id="36e11-104">The instrumentation key this configuration instance will provide.</span></span></param>
        <summary>
            <span data-ttu-id="36e11-105">Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="36e11-105">Initializes a new instance of the TelemetryConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TelemetryConfiguration (string instrumentationKey, Microsoft.ApplicationInsights.Channel.ITelemetryChannel channel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string instrumentationKey, class Microsoft.ApplicationInsights.Channel.ITelemetryChannel channel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.#ctor(System.String,Microsoft.ApplicationInsights.Channel.ITelemetryChannel)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (instrumentationKey As String, channel As ITelemetryChannel)" />
      <MemberSignature Language="F#" Value="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration : string * Microsoft.ApplicationInsights.Channel.ITelemetryChannel -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="new Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration (instrumentationKey, channel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="instrumentationKey" Type="System.String" />
        <Parameter Name="channel" Type="Microsoft.ApplicationInsights.Channel.ITelemetryChannel" />
      </Parameters>
      <Docs>
        <param name="instrumentationKey"><span data-ttu-id="36e11-106">Instrumentierungsschlüssel bietet diese konfigurationsinstanz.</span><span class="sxs-lookup"><span data-stu-id="36e11-106">The instrumentation key this configuration instance will provide.</span></span></param>
        <param name="channel"><span data-ttu-id="36e11-107">Der Telemetrie-Kanal, der mit dieser konfigurationsinstanz bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="36e11-107">The telemetry channel to provide with this configuration instance.</span></span></param>
        <summary>
            <span data-ttu-id="36e11-108">Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.</span><span class="sxs-lookup"><span data-stu-id="36e11-108">Initializes a new instance of the TelemetryConfiguration class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration Active { get; }" />
      <MemberSignature Language="ILAsm" Value=".property class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Property Active As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="member this.Active : Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-109">Ruft den aktiven <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz aus deren ApplicationInsights.config-Datei geladen.</span><span class="sxs-lookup"><span data-stu-id="36e11-109">Gets the active <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> instance loaded from the ApplicationInsights.config file.</span></span> <span data-ttu-id="36e11-110">Wenn die Konfigurationsdatei nicht vorhanden ist, wird die Instanz aktive Konfiguration mit minimalen Standardwerte, die zum Senden von Telemetriedaten an Application Insights benötigt initialisiert.</span><span class="sxs-lookup"><span data-stu-id="36e11-110">If the configuration file does not exist, the active configuration instance is initialized with minimum defaults needed to send telemetry to Application Insights.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateDefault ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateDefault() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateDefault" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateDefault () As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="static member CreateDefault : unit -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateDefault " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="36e11-111">Erstellt ein neues <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz aus deren ApplicationInsights.config-Datei geladen.</span><span class="sxs-lookup"><span data-stu-id="36e11-111">Creates a new <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> instance loaded from the ApplicationInsights.config file.</span></span>
            <span data-ttu-id="36e11-112">Wenn die Konfigurationsdatei nicht vorhanden ist, wird die neue konfigurationsinstanz mit minimalen Standardwerte, die zum Senden von Telemetriedaten an Application Insights benötigt initialisiert.</span><span class="sxs-lookup"><span data-stu-id="36e11-112">If the configuration file does not exist, the new configuration instance is initialized with minimum defaults needed to send telemetry to Application Insights.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConfiguration">
      <MemberSignature Language="C#" Value="public static Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateFromConfiguration (string config);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration CreateFromConfiguration(string config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateFromConfiguration(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConfiguration (config As String) As TelemetryConfiguration" />
      <MemberSignature Language="F#" Value="static member CreateFromConfiguration : string -&gt; Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.CreateFromConfiguration config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="config"><span data-ttu-id="36e11-113">Eine serialisierte XML-Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="36e11-113">An xml serialized configuration.</span></span></param>
        <summary>
            <span data-ttu-id="36e11-114">Erstellt ein neues <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz geladen wird, aus der angegebenen Konfiguration.</span><span class="sxs-lookup"><span data-stu-id="36e11-114">Creates a new <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> instance loaded from the specified configuration.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="36e11-115">Löst aus, wenn der Konfigurationswert, der null oder leer ist.</span><span class="sxs-lookup"><span data-stu-id="36e11-115">Throws if the config value is null or empty.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="DefaultTelemetrySink">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.TelemetrySink DefaultTelemetrySink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.TelemetrySink DefaultTelemetrySink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DefaultTelemetrySink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultTelemetrySink As TelemetrySink" />
      <MemberSignature Language="F#" Value="member this.DefaultTelemetrySink : Microsoft.ApplicationInsights.Extensibility.TelemetrySink" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DefaultTelemetrySink" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.TelemetrySink</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableTelemetry">
      <MemberSignature Language="C#" Value="public bool DisableTelemetry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool DisableTelemetry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DisableTelemetry" />
      <MemberSignature Language="VB.NET" Value="Public Property DisableTelemetry As Boolean" />
      <MemberSignature Language="F#" Value="member this.DisableTelemetry : bool with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.DisableTelemetry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-116">Ruft ab oder legt einen Wert, der angibt, ob das Senden von Telemetriedaten an Application Insights deaktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="36e11-116">Gets or sets a value indicating whether sending of telemetry to Application Insights is disabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36e11-117">Dieser Einstellungswert nachverfolgen deaktivieren wird standardmäßig von allen verwendet <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> Instanzen, die in der Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="36e11-117">This disable tracking setting value is used by default by all <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> instances created in the application.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="telemetryConfiguration.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
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
            <span data-ttu-id="36e11-118">Gibt die von der aktuellen Instanz der <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />-Klasse verwendeten Ressourcen frei.</span><span class="sxs-lookup"><span data-stu-id="36e11-118">Releases resources used by the current instance of the <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstrumentationKey">
      <MemberSignature Language="C#" Value="public string InstrumentationKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstrumentationKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.InstrumentationKey" />
      <MemberSignature Language="VB.NET" Value="Public Property InstrumentationKey As String" />
      <MemberSignature Language="F#" Value="member this.InstrumentationKey : string with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.InstrumentationKey" />
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
            <span data-ttu-id="36e11-119">Ruft ab, oder legt ihn fest die Instrumentation Standardschlüssel für die Anwendung.</span><span class="sxs-lookup"><span data-stu-id="36e11-119">Gets or sets the default instrumentation key for the application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36e11-120">Dieser Schlüsselwert Instrumentation wird standardmäßig von allen verwendet <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> Instanzen, die in der Anwendung erstellt.</span><span class="sxs-lookup"><span data-stu-id="36e11-120">This instrumentation key value is used by default by all <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> instances created in the application.</span></span> <span data-ttu-id="36e11-121">Dieser Wert kann überschrieben werden, durch Festlegen der <see cref="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" /> Eigenschaft von der <see cref="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />.</span><span class="sxs-lookup"><span data-stu-id="36e11-121">This value can be overwritten by setting the <see cref="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" /> property of the <see cref="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentNullException"><span data-ttu-id="36e11-122">Der neue Wert ist null.</span><span class="sxs-lookup"><span data-stu-id="36e11-122">The new value is null.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="TelemetryChannel">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Channel.ITelemetryChannel TelemetryChannel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Channel.ITelemetryChannel TelemetryChannel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryChannel" />
      <MemberSignature Language="VB.NET" Value="Public Property TelemetryChannel As ITelemetryChannel" />
      <MemberSignature Language="F#" Value="member this.TelemetryChannel : Microsoft.ApplicationInsights.Channel.ITelemetryChannel with get, set" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryChannel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Channel.ITelemetryChannel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-123">Abrufen oder festlegen den Telemetrie-Kanal.</span><span class="sxs-lookup"><span data-stu-id="36e11-123">Gets or sets the telemetry channel.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryInitializers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt; TelemetryInitializers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt; TelemetryInitializers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryInitializers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryInitializers As IList(Of ITelemetryInitializer)" />
      <MemberSignature Language="F#" Value="member this.TelemetryInitializers : System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryInitializers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-124">Ruft die Liste der <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" /> Objekte, die zusätzliche Informationen zur Telemetrie bereitzustellen.</span><span class="sxs-lookup"><span data-stu-id="36e11-124">Gets the list of <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" /> objects that supply additional information about telemetry.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="36e11-125">Telemetrie-Initialisierer Application Insights Telemetrie-Erfassung erweitern, indem Sie zusätzliche Informationen zu einzelnen Angabe <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Elemente, wie z. B. <see cref="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />.</span><span class="sxs-lookup"><span data-stu-id="36e11-125">Telemetry initializers extend Application Insights telemetry collection by supplying additional information about individual <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> items, such as <see cref="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />.</span></span> <span data-ttu-id="36e11-126">Ein <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> ruft Telemetrie Initialisierer jedes Mal <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" /> -Methode aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="36e11-126">A <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> invokes telemetry initializers each time <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" /> method is called.</span></span>
            <span data-ttu-id="36e11-127">Die Standardliste der Telemetrie-Initialisierer wird von Application Insights NuGet-Pakete bereitgestellt und aus der ApplicationInsights.config-Datei befindet sich im Verzeichnis Anwendung geladen.</span><span class="sxs-lookup"><span data-stu-id="36e11-127">The default list of telemetry initializers is provided by the Application Insights NuGet packages and loaded from the ApplicationInsights.config file located in the application directory.</span></span> 
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryProcessorChainBuilder">
      <MemberSignature Language="C#" Value="public Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder TelemetryProcessorChainBuilder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder TelemetryProcessorChainBuilder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessorChainBuilder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryProcessorChainBuilder As TelemetryProcessorChainBuilder" />
      <MemberSignature Language="F#" Value="member this.TelemetryProcessorChainBuilder : Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessorChainBuilder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ApplicationInsights.Extensibility.Implementation.TelemetryProcessorChainBuilder</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-128">Ruft die TelemetryProcessorChainBuilder erstellen und Auffüllen TelemetryProcessors in der TelemetryConfiguration kann.</span><span class="sxs-lookup"><span data-stu-id="36e11-128">Gets the TelemetryProcessorChainBuilder which can build and populate TelemetryProcessors in the TelemetryConfiguration.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetryProcessors">
      <MemberSignature Language="C#" Value="public System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; TelemetryProcessors { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.ObjectModel.ReadOnlyCollection`1&lt;class Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt; TelemetryProcessors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessors" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetryProcessors As ReadOnlyCollection(Of ITelemetryProcessor)" />
      <MemberSignature Language="F#" Value="member this.TelemetryProcessors : System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetryProcessors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.3.0.0</AssemblyVersion>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.ObjectModel.ReadOnlyCollection&lt;Microsoft.ApplicationInsights.Extensibility.ITelemetryProcessor&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="36e11-129">Ruft eine schreibgeschützte Auflistung von TelemetryProcessors ab.</span><span class="sxs-lookup"><span data-stu-id="36e11-129">Gets a readonly collection of TelemetryProcessors.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TelemetrySinks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt; TelemetrySinks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt; TelemetrySinks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetrySinks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TelemetrySinks As IList(Of TelemetrySink)" />
      <MemberSignature Language="F#" Value="member this.TelemetrySinks : System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt;" Usage="Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.TelemetrySinks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ApplicationInsights</AssemblyName>
        <AssemblyVersion>2.5.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.ApplicationInsights.Extensibility.TelemetrySink&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>