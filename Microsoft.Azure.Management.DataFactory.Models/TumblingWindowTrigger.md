<Type Name="TumblingWindowTrigger" FullName="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger">
  <TypeSignature Language="C#" Value="public class TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TumblingWindowTrigger extends Microsoft.Azure.Management.DataFactory.Models.Trigger" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class TumblingWindowTrigger&#xA;Inherits Trigger" />
  <TypeSignature Language="F#" Value="type TumblingWindowTrigger = class&#xA;    inherit Trigger" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.Trigger</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Trigger, der Pipeline plant ausgeführt wird, für alle festen Intervall-Zeitfenstern über eine Startzeit ohne Lücken und unterstützt auch Abgleich-Szenarien (wenn es sich um eine Startzeit in der Vergangenheit liegt).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TumblingWindowTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TumblingWindowTrigger (Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string description = null, string runtimeState = null, string frequency = null, Nullable&lt;int&gt; interval = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, object delay = null, Nullable&lt;int&gt; maxConcurrency = null, Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference pipeline, class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string description, string runtimeState, string frequency, valuetype System.Nullable`1&lt;int32&gt; interval, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, object delay, valuetype System.Nullable`1&lt;int32&gt; maxConcurrency, class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy retryPolicy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.#ctor(Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference,System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Object,System.Nullable{System.Int32},Microsoft.Azure.Management.DataFactory.Models.RetryPolicy)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference * System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * Nullable&lt;int&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * obj * Nullable&lt;int&gt; * Microsoft.Azure.Management.DataFactory.Models.RetryPolicy -&gt; Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger" Usage="new Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger (pipeline, additionalProperties, description, runtimeState, frequency, interval, startTime, endTime, delay, maxConcurrency, retryPolicy)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="pipeline" Type="Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference" />
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="description" Type="System.String" />
        <Parameter Name="runtimeState" Type="System.String" />
        <Parameter Name="frequency" Type="System.String" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="delay" Type="System.Object" />
        <Parameter Name="maxConcurrency" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="retryPolicy" Type="Microsoft.Azure.Management.DataFactory.Models.RetryPolicy" />
      </Parameters>
      <Docs>
        <param name="pipeline">Die Pipeline für die Testläufe erstellt werden, wenn ein Ereignis für Fenster der Trigger ausgelöst wird, die bereit ist.</param>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="description">Beschreibung des Triggers.</param>
        <param name="runtimeState">Gibt an, ob Trigger oder nicht ausgeführt wird.
            Aktualisiert, wenn der Start/Stopp-APIs für den Trigger aufgerufen werden. Folgende Werte sind möglich: "Gestartet", "Angehalten", "Disabled"</param>
        <param name="frequency">Die Häufigkeit des Windows-Zeit. Folgende Werte sind möglich: 'Minute', 'Hour'</param>
        <param name="interval">Das Intervall der Zeit Windows. Das Mindestintervall zulässig beträgt 15 Minuten.</param>
        <param name="startTime">Die Startzeit für den Zeitraum für den Trigger, in dem Ereignisse ausgelöst werden, für Windows, die bereit sind.
            UTC-Zeit wird derzeit unterstützt.</param>
        <param name="endTime">Die Endzeit für den Zeitraum für den Trigger, in dem Ereignisse ausgelöst werden, für Windows, die bereit sind.
            UTC-Zeit wird derzeit unterstützt.</param>
        <param name="delay">Gibt an, wie lange der Trigger überfällig wartet vor dem Auslösen neu ausführen. Noch keine alter fensterstart- und Endzeiten. Der Standardwert ist 0. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).</param>
        <param name="maxConcurrency">Die maximale Anzahl von parallelen Zeitfenstern (bereit für die Ausführung), die für die ein neues ausführendes ausgelöst wird.</param>
        <param name="retryPolicy">Wiederholen Sie die Richtlinie, die für die Ausführung des fehlerhaften Pipeline angewendet werden.</param>
        <summary>
            Initialisiert eine neue Instanz der TumblingWindowTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delay">
      <MemberSignature Language="C#" Value="public object Delay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Delay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberSignature Language="VB.NET" Value="Public Property Delay As Object" />
      <MemberSignature Language="F#" Value="member this.Delay : obj with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Delay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.delay")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, wie lange der Trigger überfällig wartet vor dem Auslösen neu ausführen. Noch keine alter fensterstart- und Endzeiten. Der Standardwert ist 0. Typ: Zeichenfolge (oder Ausdruck mit ResultType-Zeichenfolge), Muster: ((\d+)\.)? () :(60| \d\d) ([0-5][0-9])): () 60 | ([0-5][0-9])).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Endzeit für den Zeitraum für den Trigger, in dem Ereignisse ausgelöst werden, für Windows, die bereit sind. UTC-Zeit wird derzeit unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Frequency">
      <MemberSignature Language="C#" Value="public string Frequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Frequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberSignature Language="VB.NET" Value="Public Property Frequency As String" />
      <MemberSignature Language="F#" Value="member this.Frequency : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Frequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.frequency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Häufigkeit des Windows-Zeit. Folgende Werte sind möglich: 'Minute', 'Hour'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Intervall der Zeit Windows fest. Das Mindestintervall zulässig beträgt 15 Minuten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxConcurrency">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxConcurrency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxConcurrency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxConcurrency As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxConcurrency : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.MaxConcurrency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.maxConcurrency")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von parallelen Zeitfenstern (für die Ausführung bereit) für die ein neues ausführendes ausgelöst wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Pipeline">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference Pipeline" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberSignature Language="VB.NET" Value="Public Property Pipeline As TriggerPipelineReference" />
      <MemberSignature Language="F#" Value="member this.Pipeline : Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Pipeline" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipeline")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.TriggerPipelineReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Pipeline für die Testläufe erstellt werden, wenn ein Ereignis für Fenster der Trigger ausgelöst wird, die bereit ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.RetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As RetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Management.DataFactory.Models.RetryPolicy with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.retryPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.RetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest wiederholungsrichtlinie, die für die Ausführung des fehlerhaften Pipeline angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="typeProperties.startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Startzeit für den Zeitraum für den Trigger, in dem Ereignisse ausgelöst werden, für Windows, die bereit sind. UTC-Zeit wird derzeit unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.TumblingWindowTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="tumblingWindowTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
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