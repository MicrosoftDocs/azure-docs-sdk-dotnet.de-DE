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
            Kapselt die globalen Telemetrie-Konfiguration, die in der Regel aus deren ApplicationInsights.config-Datei geladen.
            </summary>
    <remarks>
            Alle <see cref="T:Microsoft.ApplicationInsights.DataContracts.TelemetryContext" /> Objekte initialisiert werden, mithilfe der <see cref="P:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration.Active" /> Telemetrie-Konfiguration, die von dieser Klasse bereitgestellten.
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
            Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.
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
        <param name="instrumentationKey">Instrumentierungsschlüssel bietet diese konfigurationsinstanz.</param>
        <summary>
            Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.
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
        <param name="instrumentationKey">Instrumentierungsschlüssel bietet diese konfigurationsinstanz.</param>
        <param name="channel">Der Telemetrie-Kanal, der mit dieser konfigurationsinstanz bereitstellen.</param>
        <summary>
            Initialisiert eine neue Instanz der TelemetryConfiguration-Klasse.
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
            Ruft den aktiven <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz aus deren ApplicationInsights.config-Datei geladen. Wenn die Konfigurationsdatei nicht vorhanden ist, wird die Instanz aktive Konfiguration mit minimalen Standardwerte, die zum Senden von Telemetriedaten an Application Insights benötigt initialisiert.
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
            Erstellt ein neues <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz aus deren ApplicationInsights.config-Datei geladen.
            Wenn die Konfigurationsdatei nicht vorhanden ist, wird die neue konfigurationsinstanz mit minimalen Standardwerte, die zum Senden von Telemetriedaten an Application Insights benötigt initialisiert.
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
        <param name="config">Eine serialisierte XML-Konfiguration.</param>
        <summary>
            Erstellt ein neues <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" /> Instanz geladen wird, aus der angegebenen Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Löst aus, wenn der Konfigurationswert, der null oder leer ist.</exception>
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
            Ruft ab oder legt einen Wert, der angibt, ob das Senden von Telemetriedaten an Application Insights deaktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Einstellungswert nachverfolgen deaktivieren wird standardmäßig von allen verwendet <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> Instanzen, die in der Anwendung erstellt. 
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
            Gibt die von der aktuellen Instanz der <see cref="T:Microsoft.ApplicationInsights.Extensibility.TelemetryConfiguration" />-Klasse verwendeten Ressourcen frei.
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
            Ruft ab, oder legt ihn fest die Instrumentation Standardschlüssel für die Anwendung.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser Schlüsselwert Instrumentation wird standardmäßig von allen verwendet <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> Instanzen, die in der Anwendung erstellt. Dieser Wert kann überschrieben werden, durch Festlegen der <see cref="P:Microsoft.ApplicationInsights.DataContracts.TelemetryContext.InstrumentationKey" /> Eigenschaft von der <see cref="P:Microsoft.ApplicationInsights.TelemetryClient.Context" />.
            </remarks>
        <exception cref="T:System.ArgumentNullException">Der neue Wert ist null.</exception>
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
            Abrufen oder festlegen den Telemetrie-Kanal.
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
            Ruft die Liste der <see cref="T:Microsoft.ApplicationInsights.Extensibility.ITelemetryInitializer" /> Objekte, die zusätzliche Informationen zur Telemetrie bereitzustellen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Telemetrie-Initialisierer Application Insights Telemetrie-Erfassung erweitern, indem Sie zusätzliche Informationen zu einzelnen Angabe <see cref="T:Microsoft.ApplicationInsights.Channel.ITelemetry" /> Elemente, wie z. B. <see cref="P:Microsoft.ApplicationInsights.Channel.ITelemetry.Timestamp" />. Ein <see cref="T:Microsoft.ApplicationInsights.TelemetryClient" /> ruft Telemetrie Initialisierer jedes Mal <see cref="M:Microsoft.ApplicationInsights.TelemetryClient.Track(Microsoft.ApplicationInsights.Channel.ITelemetry)" /> -Methode aufgerufen wird.
            Die Standardliste der Telemetrie-Initialisierer wird von Application Insights NuGet-Pakete bereitgestellt und aus der ApplicationInsights.config-Datei befindet sich im Verzeichnis Anwendung geladen. 
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
            Ruft die TelemetryProcessorChainBuilder erstellen und Auffüllen TelemetryProcessors in der TelemetryConfiguration kann.
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
            Ruft eine schreibgeschützte Auflistung von TelemetryProcessors ab.
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