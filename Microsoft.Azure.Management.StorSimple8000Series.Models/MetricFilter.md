<Type Name="MetricFilter" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter">
  <TypeSignature Language="C#" Value="public class MetricFilter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricFilter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricFilter" />
  <TypeSignature Language="F#" Value="type MetricFilter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die OData-Filter für Metriken verwendet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricFilter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricFilter (string category, Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter name = null, Nullable&lt;DateTime&gt; startTime = null, Nullable&lt;DateTime&gt; endTime = null, string timeGrain = null, Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter dimensions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string category, class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter name, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime, string timeGrain, class Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter dimensions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (category As String, Optional name As MetricNameFilter = null, Optional startTime As Nullable(Of DateTime) = null, Optional endTime As Nullable(Of DateTime) = null, Optional timeGrain As String = null, Optional dimensions As DimensionFilter = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter : string * Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter (category, name, startTime, endTime, timeGrain, dimensions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="timeGrain" Type="System.String" />
        <Parameter Name="dimensions" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter" />
      </Parameters>
      <Docs>
        <param name="category">Gibt die Kategorie der Metriken gefiltert werden sollen. Z. B. "CapacityUtilization". Gültige Werte sind diejenigen, die als das Feld "Kategorie" im Aufruf ListMetricDefinitions zurückgegeben.
            Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="name">Gibt den metrischen Namensfilter angeben des Namens der Metrik auf gefiltert werden sollen. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="startTime">Gibt die Startzeit des Zeitraums, der abgefragt werden. Nur 'Größer als oder gleich'-Operator wird für diese Eigenschaft unterstützt.</param>
        <param name="endTime">Gibt die Endzeit des Zeitraums, der abgefragt werden. Nur 'Less Than Or Equal To'-Operator wird für diese Eigenschaft unterstützt.</param>
        <param name="timeGrain">Gibt die Zeitgranularität der zurückzugebenden Metriken an. Z. B. "P1D". Gültige Werte sind diejenigen, die als das Feld "TimeGrain" im Aufruf ListMetricDefinitions zurückgegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <param name="dimensions">Gibt die Quelle (Dimension) der abzurufenden gefiltert werden. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricFilter-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Category" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="category")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Kategorie der Metriken gefiltert werden sollen.
            Z. B. "CapacityUtilization". Gültige Werte sind diejenigen, die als das Feld "Kategorie" im Aufruf ListMetricDefinitions zurückgegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As DimensionFilter" />
      <MemberSignature Language="F#" Value="member this.Dimensions : Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Dimensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dimensions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.DimensionFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an der Quelle (Dimension) der abzurufenden gefiltert werden, ruft ab oder legt ihn fest. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Endzeit des Zeitraums, der abgefragt werden. Nur 'Less Than Or Equal To'-Operator wird für diese Eigenschaft unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricNameFilter" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MetricNameFilter</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt an, der metrikname Filter angeben des Namens der Metrik auf gefiltert werden sollen. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Startzeit des Zeitraums, der abgefragt werden. Nur 'Größer als oder gleich'-Operator wird für diese Eigenschaft unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeGrain">
      <MemberSignature Language="C#" Value="public string TimeGrain { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeGrain" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.TimeGrain" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeGrain As String" />
      <MemberSignature Language="F#" Value="member this.TimeGrain : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.TimeGrain" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeGrain")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt die Zeitgranularität der zurückzugebenden Metriken an. Z. B. "P1D". Gültige Werte sind diejenigen, die als das Feld "TimeGrain" im Aufruf ListMetricDefinitions zurückgegeben. Für diese Eigenschaft wird nur "Gleichheitsoperator" unterstützt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metricFilter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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