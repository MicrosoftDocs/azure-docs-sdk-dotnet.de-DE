<Type Name="MetricTrigger" FullName="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger">
  <TypeSignature Language="C#" Value="public class MetricTrigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricTrigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricTrigger" />
  <TypeSignature Language="F#" Value="type MetricTrigger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der Trigger, der zu einer skalierungsaktion führt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricTrigger (string metricName, string metricResourceUri, TimeSpan timeGrain, Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, TimeSpan timeWindow, Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, double threshold);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string metricName, string metricResourceUri, valuetype System.TimeSpan timeGrain, valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType statistic, valuetype System.TimeSpan timeWindow, valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType timeAggregation, valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType operatorProperty, float64 threshold) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.#ctor(System.String,System.String,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType,System.TimeSpan,Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType,Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType,System.Double)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (metricName As String, metricResourceUri As String, timeGrain As TimeSpan, statistic As MetricStatisticType, timeWindow As TimeSpan, timeAggregation As TimeAggregationType, operatorProperty As ComparisonOperationType, threshold As Double)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger : string * string * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType * TimeSpan * Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType * Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType * double -&gt; Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger" Usage="new Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger (metricName, metricResourceUri, timeGrain, statistic, timeWindow, timeAggregation, operatorProperty, threshold)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="metricName" Type="System.String" />
        <Parameter Name="metricResourceUri" Type="System.String" />
        <Parameter Name="timeGrain" Type="System.TimeSpan" />
        <Parameter Name="statistic" Type="Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType" />
        <Parameter Name="timeWindow" Type="System.TimeSpan" />
        <Parameter Name="timeAggregation" Type="Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType" />
        <Parameter Name="operatorProperty" Type="Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType" />
        <Parameter Name="threshold" Type="System.Double" />
      </Parameters>
      <Docs>
        <param name="metricName">Der Name der Metrik, die definiert, was die Regel überwacht.</param>
        <param name="metricResourceUri">Der Ressourcenbezeichner der Ressource die Regel überwacht.</param>
        <param name="timeGrain">die Granularität der Metriken, die Regel überwacht. Einen der vordefinierten Werte muss von den metrikdefinitionen für die Metrik zurückgegeben werden. Muss zwischen 12 Stunden und 1 Minute betragen.</param>
        <param name="statistic">der Metrik Statistiktyp. Wie die Metriken aus mehreren Instanzen kombiniert werden. Folgende Werte sind möglich: 'Average', 'Min', 'Max', 'Sum'</param>
        <param name="timeWindow">die Zeitspanne, in dem Instanzdaten gesammelt werden. Dieser Wert muss größer als die Verzögerung bei der metrikerfassung, werden die von Ressource zu Ressource unterschiedlich sein können. Muss zwischen 12 Stunden und 5 Minuten liegen.</param>
        <param name="timeAggregation">Zeit Aggregationstyp. Legt fest, wie die erfassten Daten im Zeitverlauf kombiniert werden sollen. Der Standardwert ist "Average". Folgende Werte sind möglich: "Durchschnitt", "Minimum", "Maximum", "Total", "Count"</param>
        <param name="operatorProperty">der Operator, mit dem die metrischen Daten und der Schwellenwert verglichen. Folgende Werte sind möglich: "Equals", "Ungleich", "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"</param>
        <param name="threshold">der Schwellenwert der Metrik, die die skalierungsaktion auslöst.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricTrigger-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricName">
      <MemberSignature Language="C#" Value="public string MetricName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricName As String" />
      <MemberSignature Language="F#" Value="member this.MetricName : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Metrik, die definiert, was die Regel überwacht.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricResourceUri">
      <MemberSignature Language="C#" Value="public string MetricResourceUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MetricResourceUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricResourceUri As String" />
      <MemberSignature Language="F#" Value="member this.MetricResourceUri : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.MetricResourceUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricResourceUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt überwacht der Ressourcenbezeichner der Ressource die Regel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatorProperty">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType OperatorProperty" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberSignature Language="VB.NET" Value="Public Property OperatorProperty As ComparisonOperationType" />
      <MemberSignature Language="F#" Value="member this.OperatorProperty : Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.OperatorProperty" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="operator")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.ComparisonOperationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Operator, der verwendet wird, um die metrischen Daten und der Schwellenwert verglichen. Folgende Werte sind möglich: "Equals", "Ungleich", "GreaterThan", "GreaterThanOrEqual", "LessThan", "LessThanOrEqual"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Statistic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType Statistic" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberSignature Language="VB.NET" Value="Public Property Statistic As MetricStatisticType" />
      <MemberSignature Language="F#" Value="member this.Statistic : Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Statistic" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="statistic")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.MetricStatisticType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Metrik Statistiktyp. Wie die Metriken aus mehreren Instanzen kombiniert werden. Folgende Werte sind möglich: 'Average', 'Min', 'Max', 'Sum'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Threshold">
      <MemberSignature Language="C#" Value="public double Threshold { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float64 Threshold" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberSignature Language="VB.NET" Value="Public Property Threshold As Double" />
      <MemberSignature Language="F#" Value="member this.Threshold : double with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Threshold" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="threshold")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Double</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Schwellenwert der Metrik, die die skalierungsaktion auslöst.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeAggregation">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType TimeAggregation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeAggregation As TimeAggregationType" />
      <MemberSignature Language="F#" Value="member this.TimeAggregation : Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeAggregation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeAggregation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Management.Models.TimeAggregationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest Zeit Aggregation. Legt fest, wie die erfassten Daten im Zeitverlauf kombiniert werden sollen. Der Standardwert ist "Average".
            Folgende Werte sind möglich: "Durchschnitt", "Minimum", "Maximum", "Total", "Count"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public TimeSpan TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt überwacht die Granularität der Metriken der Regel. Einen der vordefinierten Werte muss von den metrikdefinitionen für die Metrik zurückgegeben werden. Muss zwischen 12 Stunden und 1 Minute betragen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeWindow">
      <MemberSignature Language="C#" Value="public TimeSpan TimeWindow { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan TimeWindow" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeWindow As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.TimeWindow : TimeSpan with get, set" Usage="Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.TimeWindow" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeWindow")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitspanne, in dem Instanzdaten gesammelt werden.
            Dieser Wert muss größer als die Verzögerung bei der metrikerfassung, werden die von Ressource zu Ressource unterschiedlich sein können. Muss zwischen 12 Stunden und 5 Minuten liegen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Management.Models.MetricTrigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricTrigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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