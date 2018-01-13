<Type Name="StreamingJob" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob">
  <TypeSignature Language="C#" Value="public class StreamingJob : Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StreamingJob extends Microsoft.Azure.Management.StreamAnalytics.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" />
  <TypeSignature Language="VB.NET" Value="Public Class StreamingJob&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type StreamingJob = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Ein Streamng-Auftragsobjekt, enthält alle Informationen, die die benannte streamingauftrag zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StreamingJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StreamingJob (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku = null, string jobId = null, string provisioningState = null, string jobState = null, string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null, Nullable&lt;DateTime&gt; lastOutputEventTime = null, string eventsOutOfOrderPolicy = null, string outputErrorPolicy = null, Nullable&lt;int&gt; eventsOutOfOrderMaxDelayInSeconds = null, Nullable&lt;int&gt; eventsLateArrivalMaxDelayInSeconds = null, string dataLocale = null, string compatibilityLevel = null, Nullable&lt;DateTime&gt; createdDate = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs = null, Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions = null, string etag = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, class Microsoft.Azure.Management.StreamAnalytics.Models.Sku sku, string jobId, string provisioningState, string jobState, string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastOutputEventTime, string eventsOutOfOrderPolicy, string outputErrorPolicy, valuetype System.Nullable`1&lt;int32&gt; eventsOutOfOrderMaxDelayInSeconds, valuetype System.Nullable`1&lt;int32&gt; eventsLateArrivalMaxDelayInSeconds, string dataLocale, string compatibilityLevel, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; createdDate, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; inputs, class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation transformation, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; outputs, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; functions, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.StreamAnalytics.Models.Sku,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String,System.String,System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Input},Microsoft.Azure.Management.StreamAnalytics.Models.Transformation,System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Output},System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.Function},System.String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Sku * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string * string * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; * Microsoft.Azure.Management.StreamAnalytics.Models.Transformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; * string -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob (id, name, type, location, tags, sku, jobId, provisioningState, jobState, outputStartMode, outputStartTime, lastOutputEventTime, eventsOutOfOrderPolicy, outputErrorPolicy, eventsOutOfOrderMaxDelayInSeconds, eventsLateArrivalMaxDelayInSeconds, dataLocale, compatibilityLevel, createdDate, inputs, transformation, outputs, functions, etag)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="sku" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Sku" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="provisioningState" Type="System.String" />
        <Parameter Name="jobState" Type="System.String" />
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="lastOutputEventTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="eventsOutOfOrderPolicy" Type="System.String" />
        <Parameter Name="outputErrorPolicy" Type="System.String" />
        <Parameter Name="eventsOutOfOrderMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="eventsLateArrivalMaxDelayInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dataLocale" Type="System.String" />
        <Parameter Name="compatibilityLevel" Type="System.String" />
        <Parameter Name="createdDate" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="inputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;" />
        <Parameter Name="transformation" Type="Microsoft.Azure.Management.StreamAnalytics.Models.Transformation" />
        <Parameter Name="outputs" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;" />
        <Parameter Name="functions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">Ressourcen-Id</param>
        <param name="name">Ressourcenname</param>
        <param name="type">Ressourcentyp</param>
        <param name="location">Der Ressourcenspeicherort. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="tags">Ressourcentags</param>
        <param name="sku">Beschreibt die SKU des streamingauftrags an. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="jobId">Eine GUID, die den streamingauftrag eindeutig identifiziert.
            Diese GUID wird bei der Erstellung des streamingauftrags generiert.</param>
        <param name="provisioningState">Beschreibt den Bereitstellungsstatus des streamingauftrags an.</param>
        <param name="jobState">Beschreibt den Status des streamingauftrags.</param>
        <param name="outputStartMode">Diese Eigenschaft sollte nur verwendet werden, wenn es gewünscht wird, dass der Auftrag sofort nach dem Erstellen gestartet werden. Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden beginnen mit einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben, oder starten aus dem Zeitpunkt des letzten Ereignisses-Ausgabe. Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """</param>
        <param name="outputStartTime">Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird. Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.</param>
        <param name="lastOutputEventTime">Der Wert ist entweder ein ISO-8601-formatierte Zeitstempel, der angibt, der letzte Ausgabe Ereigniszeit des Auftrags oder streaming Null gibt an, dass noch keine Ausgabe erzeugt wurde. Im Falle von mehreren Ausgaben oder mehrere Datenströme zeigt dies den letzten Wert in diesem Satz an.</param>
        <param name="eventsOutOfOrderPolicy">Gibt an, die Richtlinie auf Ereignisse angewendet, die in den eingabeereignisdatenstrom in falscher Reihenfolge ankommen.
            Folgende Werte sind möglich: 'Anpassen', 'Drop'</param>
        <param name="outputErrorPolicy">Gibt an, die Richtlinie auf Ereignisse angewendet, die an die Ausgabe eingehen und nicht in den externen Speicher aufgrund eines fehlerhaften (fehlende Spaltenwerte, Spaltenwerte falschen Typ oder die Größe) geschrieben werden. Folgende Werte sind möglich: 'Beenden', 'Drop'</param>
        <param name="eventsOutOfOrderMaxDelayInSeconds">Die maximale tolerierbar Verzögerung in Sekunden, in dem Ereignisse außerhalb der Reihenfolge, in Reihenfolge wieder angepasst werden kann.</param>
        <param name="eventsLateArrivalMaxDelayInSeconds">Die maximale tolerierbar Verzögerung in Sekunden, in dem Ereignisse spät ankommen eingeschlossen werden können.  Der unterstützte Bereich ist 1, um 1814399 (20.23:59:59 Tage) und-1 wird verwendet, um die Wartezeit unbegrenzt angeben. Wenn die Eigenschaft nicht vorhanden ist, wird er interpretiert, einen Wert von-1 ist.</param>
        <param name="dataLocale">Das Gebietsschema der Daten von Stream Analytics-Auftrag. Wert muss der Name einer unterstützten .NET Kultur aus der Gruppe https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. sein.
            Der Standardwert ist "En-US", falls keiner angegeben.</param>
        <param name="compatibilityLevel">Steuert bestimmte Laufzeitverhaltens des streamingauftrags an. Folgende Werte sind möglich: "1.0"</param>
        <param name="createdDate">Wert ist, dass die ISO-8601-Format UTC-Zeitstempel, der angibt, wann der streamingauftrag erstellt wurde.</param>
        <param name="inputs">Eine Liste der eine oder mehrere Eingaben für den streamingauftrag. Die Name-Eigenschaft für jede Eingabe ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelnen Eingabe verwenden.</param>
        <param name="transformation">Gibt an, die Abfrage und die Anzahl der streamingeinheiten, die für den streamingauftrag verwendet. Die Name-Eigenschaft der Transformation ist erforderlich, wenn diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden.
            Sie müssen die PATCH-API verfügbar für die einzelnen zwischengespeicherten verwenden.</param>
        <param name="outputs">Eine Liste der eine oder mehrere Ausgaben für die streaming-Auftrags. Die Name-Eigenschaft für jede Ausgabe ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelne Ausgabe verwenden.</param>
        <param name="functions">Eine Liste der eine oder mehrere Funktionen für die streaming-Auftrags. Die Name-Eigenschaft für jede Funktion ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelnen Transformation verwenden.</param>
        <param name="etag">Das aktuelle Entitätstag für die streaming-Auftrags.
            Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der StreamingJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CompatibilityLevel">
      <MemberSignature Language="C#" Value="public string CompatibilityLevel { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CompatibilityLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberSignature Language="VB.NET" Value="Public Property CompatibilityLevel As String" />
      <MemberSignature Language="F#" Value="member this.CompatibilityLevel : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CompatibilityLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.compatibilityLevel")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Steuerelemente bestimmte Laufzeitverhalten des streaming-Auftrags. Folgende Werte sind möglich: "1.0"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedDate">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreatedDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreatedDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedDate As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreatedDate : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.CreatedDate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.createdDate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft-Wert ist ein ISO-8601-Format UTC-Zeitstempel, der angibt, wann der streamingauftrag erstellt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataLocale">
      <MemberSignature Language="C#" Value="public string DataLocale { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DataLocale" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberSignature Language="VB.NET" Value="Public Property DataLocale As String" />
      <MemberSignature Language="F#" Value="member this.DataLocale : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.DataLocale" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataLocale")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Gebietsschema der Daten von Stream Analytics-Auftrag fest. Wert muss der Name einer unterstützten .NET Kultur aus der Gruppe https://msdn.microsoft.com/en-us/library/system.globalization.culturetypes(v=vs.110).aspx. sein.
            Der Standardwert ist "En-US", falls keiner angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Etag">
      <MemberSignature Language="C#" Value="public string Etag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Etag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Etag As String" />
      <MemberSignature Language="F#" Value="member this.Etag : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Etag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.etag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das aktuelle Entitätstag für den streamingauftrag an. Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob die Ressource zwischen Anforderungen geändert hat. Sie können es auch in der If-Match- oder If-None-Match-Header für Schreibvorgänge auf vollständige Parallelität verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsLateArrivalMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsLateArrivalMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsLateArrivalMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsLateArrivalMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsLateArrivalMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsLateArrivalMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale tolerierbar Verzögerung in Sekunden, in dem Ereignisse spät ankommen berücksichtigt werden.  Der unterstützte Bereich ist 1, um 1814399 (20.23:59:59 Tage) und-1 wird verwendet, um die Wartezeit unbegrenzt angeben. Wenn die Eigenschaft nicht vorhanden ist, wird er interpretiert, einen Wert von-1 ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderMaxDelayInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; EventsOutOfOrderMaxDelayInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderMaxDelayInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderMaxDelayInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderMaxDelayInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderMaxDelayInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale tolerierbar Verzögerung in Sekunden, in dem Ereignisse außerhalb der Reihenfolge angepasst werden wieder in der Reihenfolge befinden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventsOutOfOrderPolicy">
      <MemberSignature Language="C#" Value="public string EventsOutOfOrderPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EventsOutOfOrderPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property EventsOutOfOrderPolicy As String" />
      <MemberSignature Language="F#" Value="member this.EventsOutOfOrderPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.EventsOutOfOrderPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.eventsOutOfOrderPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an die Richtlinie auf Ereignisse angewendet, die in den eingabeereignisdatenstrom in falscher Reihenfolge ankommen, ruft ab oder legt ihn fest. Folgende Werte sind möglich: 'Anpassen', 'Drop'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Functions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; Functions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberSignature Language="VB.NET" Value="Public Property Functions As IList(Of Function)" />
      <MemberSignature Language="F#" Value="member this.Functions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Functions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.functions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Function&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der eine oder mehrere Funktionen für die streaming-Auftrags.
            Die Name-Eigenschaft für jede Funktion ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelnen Transformation verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Inputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; Inputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Inputs As IList(Of Input)" />
      <MemberSignature Language="F#" Value="member this.Inputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Inputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.inputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Input&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der eine oder mehrere Eingaben für den streamingauftrag. Die Name-Eigenschaft für jede Eingabe ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelnen Eingabe verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine GUID ab, die den streamingauftrag eindeutig identifiziert. Diese GUID wird bei der Erstellung des streamingauftrags generiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobState">
      <MemberSignature Language="C#" Value="public string JobState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobState As String" />
      <MemberSignature Language="F#" Value="member this.JobState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.JobState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.jobState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft beschreibt den Status des streamingauftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastOutputEventTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastOutputEventTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastOutputEventTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastOutputEventTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastOutputEventTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.LastOutputEventTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastOutputEventTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Wert ist entweder ein ISO-8601-formatierte Zeitstempel, der angibt, der letzte Ausgabe Ereigniszeit des Auftrags oder streaming Null gibt an, dass noch keine Ausgabe erzeugt wurde. Im Falle von mehreren Ausgaben oder mehrere Datenströme zeigt dies den letzten Wert in diesem Satz an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputErrorPolicy">
      <MemberSignature Language="C#" Value="public string OutputErrorPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputErrorPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputErrorPolicy As String" />
      <MemberSignature Language="F#" Value="member this.OutputErrorPolicy : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputErrorPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputErrorPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an die Richtlinie auf Ereignisse angewendet, die an die Ausgabe eingehen und kann nicht geschrieben werden, auf dem externen Speichermedium aufgrund eines fehlerhaften (fehlende Spaltenwerte, Spaltenwerte falschen Typ oder die Größe), ruft ab oder legt ihn fest. Folgende Werte sind möglich: 'Beenden', 'Drop'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Outputs">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; Outputs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberSignature Language="VB.NET" Value="Public Property Outputs As IList(Of Output)" />
      <MemberSignature Language="F#" Value="member this.Outputs : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Outputs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.Output&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der eine oder mehrere Ausgaben für die streaming-Auftrags.
            Die Name-Eigenschaft für jede Ausgabe ist erforderlich, wenn Sie diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelne Ausgabe verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die diese Eigenschaft sollte nur verwendet werden, wenn es gewünscht wird, dass der Auftrag sofort nach dem Erstellen gestartet werden. Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden beginnen mit einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben, oder starten aus dem Zeitpunkt des letzten Ereignisses-Ausgabe. Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest-Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird. Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft beschreibt den Bereitstellungsstatus des streamingauftrags an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberSignature Language="VB.NET" Value="Public Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.StreamAnalytics.Models.Sku with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sku")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt beschreibt die SKU des streaming-Auftrags. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Transformation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StreamAnalytics.Models.Transformation Transformation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberSignature Language="VB.NET" Value="Public Property Transformation As Transformation" />
      <MemberSignature Language="F#" Value="member this.Transformation : Microsoft.Azure.Management.StreamAnalytics.Models.Transformation with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StreamingJob.Transformation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.transformation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StreamAnalytics.Models.Transformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, die Abfrage und die Anzahl der streamingeinheiten, die für den streamingauftrag verwendet. Die Name-Eigenschaft der Transformation ist erforderlich, wenn diese Eigenschaft in einer PUT-Anforderung angeben. Diese Eigenschaft kann nicht über eine PATCH-Vorgang geändert werden. Sie müssen die PATCH-API verfügbar für die einzelnen zwischengespeicherten verwenden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>