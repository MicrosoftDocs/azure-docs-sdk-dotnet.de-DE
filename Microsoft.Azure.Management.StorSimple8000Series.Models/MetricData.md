<Type Name="MetricData" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData">
  <TypeSignature Language="C#" Value="public class MetricData" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricData extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricData" />
  <TypeSignature Language="F#" Value="type MetricData = class" />
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
            Die metrischen Daten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricData ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricData-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricData (Nullable&lt;DateTime&gt; timeStamp = null, Nullable&lt;double&gt; sum = null, Nullable&lt;int&gt; count = null, Nullable&lt;double&gt; average = null, Nullable&lt;double&gt; minimum = null, Nullable&lt;double&gt; maximum = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; timeStamp, valuetype System.Nullable`1&lt;float64&gt; sum, valuetype System.Nullable`1&lt;int32&gt; count, valuetype System.Nullable`1&lt;float64&gt; average, valuetype System.Nullable`1&lt;float64&gt; minimum, valuetype System.Nullable`1&lt;float64&gt; maximum) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional timeStamp As Nullable(Of DateTime) = null, Optional sum As Nullable(Of Double) = null, Optional count As Nullable(Of Integer) = null, Optional average As Nullable(Of Double) = null, Optional minimum As Nullable(Of Double) = null, Optional maximum As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData : Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData (timeStamp, sum, count, average, minimum, maximum)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timeStamp" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="average" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="minimum" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="maximum" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="timeStamp">Der Zeitstempel des ausgewählten Metriken.</param>
        <param name="sum">Die Summe aller Beispiele mit dem Zeitstempel am.</param>
        <param name="count">Die Anzahl der mit dem Zeitstempel am alle Beispiele.</param>
        <param name="average">Der Durchschnitt aller Beispiele mit dem Zeitstempel am.</param>
        <param name="minimum">Das Minimum aller Beispiele mit dem Zeitstempel am.</param>
        <param name="maximum">Der Maximalwert aller Beispiele mit dem Zeitstempel am.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricData-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Average { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Average" />
      <MemberSignature Language="VB.NET" Value="Public Property Average As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Average : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="average")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Durchschnitt aller Beispiele mit dem Zeitstempel am.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl aller Beispiele mit dem Zeitstempel am.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Maximum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Maximum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Maximum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Maximum" />
      <MemberSignature Language="VB.NET" Value="Public Property Maximum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Maximum : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Maximum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maximum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Maximum aller Beispiele mit dem Zeitstempel am.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Minimum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Minimum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Minimum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Minimum" />
      <MemberSignature Language="VB.NET" Value="Public Property Minimum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Minimum : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Minimum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="minimum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Minimum aller Beispiele mit dem Zeitstempel am.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sum">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Sum { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Sum" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Sum" />
      <MemberSignature Language="VB.NET" Value="Public Property Sum As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Sum : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.Sum" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sum")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Summe aller Beispiele mit dem Zeitstempel am.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeStamp">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; TimeStamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; TimeStamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.TimeStamp" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeStamp As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.TimeStamp : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricData.TimeStamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeStamp")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitstempel des Metrikdaten.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>