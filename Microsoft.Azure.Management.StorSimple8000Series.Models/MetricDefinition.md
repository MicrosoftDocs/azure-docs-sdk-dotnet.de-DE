<Type Name="MetricDefinition" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition">
  <TypeSignature Language="C#" Value="public class MetricDefinition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricDefinition extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricDefinition" />
  <TypeSignature Language="F#" Value="type MetricDefinition = class" />
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
            Überwachung der metrischen Definition.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der MetricDefinition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricDefinition (Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregationType = null, string resourceId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; metricAvailabilities = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions = null, string category = null, string type = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName name, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; unit, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; primaryAggregationType, string resourceId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; metricAvailabilities, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; dimensions, string category, string type) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit},System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType},System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity},System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As MetricName = null, Optional unit As Nullable(Of MetricUnit) = null, Optional primaryAggregationType As Nullable(Of MetricAggregationType) = null, Optional resourceId As String = null, Optional metricAvailabilities As IList(Of MetricAvailablity) = null, Optional dimensions As IList(Of MetricDimension) = null, Optional category As String = null, Optional type As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; * string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition (name, unit, primaryAggregationType, resourceId, metricAvailabilities, dimensions, category, type)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName" />
        <Parameter Name="unit" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt;" />
        <Parameter Name="primaryAggregationType" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;" />
        <Parameter Name="resourceId" Type="System.String" />
        <Parameter Name="metricAvailabilities" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt;" />
        <Parameter Name="dimensions" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt;" />
        <Parameter Name="category" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der metrikname.</param>
        <param name="unit">Die Metrik Einheit. Folgende Werte sind möglich: 'Bytes', 'BytesPerSecond', 'Count', "CountPerSecond", "Prozent", "Sekunden"</param>
        <param name="primaryAggregationType">Die Metrik Aggregationstyp.
            Folgende Werte sind möglich: "Durchschnitt", "Letzte", "Maximum", "Minimum", 'None', 'Total'</param>
        <param name="resourceId">Die metrikquelle-ID.</param>
        <param name="metricAvailabilities">Die verfügbaren Metrik Granularitäten ermittelt.</param>
        <param name="dimensions">Die verfügbaren Metriken-Dimensionen.</param>
        <param name="category">Die Kategorie der Metrik.</param>
        <param name="type">Der Typ der metrischen Definition.</param>
        <summary>
            Initialisiert eine neue Instanz der MetricDefinition-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Category">
      <MemberSignature Language="C#" Value="public string Category { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Category" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Category" />
      <MemberSignature Language="VB.NET" Value="Public Property Category As String" />
      <MemberSignature Language="F#" Value="member this.Category : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Category" />
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
            Ruft ab oder legt die Kategorie der Metrik.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dimensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; Dimensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Dimensions" />
      <MemberSignature Language="VB.NET" Value="Public Property Dimensions As IList(Of MetricDimension)" />
      <MemberSignature Language="F#" Value="member this.Dimensions : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Dimensions" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDimension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die verfügbaren Metriken-Dimensionen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MetricAvailabilities">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; MetricAvailabilities { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; MetricAvailabilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.MetricAvailabilities" />
      <MemberSignature Language="VB.NET" Value="Public Property MetricAvailabilities As IList(Of MetricAvailablity)" />
      <MemberSignature Language="F#" Value="member this.MetricAvailabilities : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.MetricAvailabilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metricAvailabilities")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAvailablity&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die verfügbaren Metrik Granularität der.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As MetricName" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Name" />
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
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.MetricName</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den metrischen Namen fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryAggregationType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregationType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; PrimaryAggregationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryAggregationType As Nullable(Of MetricAggregationType)" />
      <MemberSignature Language="F#" Value="member this.PrimaryAggregationType : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.PrimaryAggregationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="primaryAggregationType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricAggregationType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Metrik Aggregationstyp. Folgende Werte sind möglich: "Durchschnitt", "Letzte", "Maximum", "Minimum", 'None', 'Total'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceId">
      <MemberSignature Language="C#" Value="public string ResourceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.ResourceId" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceId As String" />
      <MemberSignature Language="F#" Value="member this.ResourceId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.ResourceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die metrikquelle-ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ anhand der metrischen Definition fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Nullable(Of MetricUnit)" />
      <MemberSignature Language="F#" Value="member this.Unit : Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricUnit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, Metrik. Folgende Werte sind möglich: 'Bytes', 'BytesPerSecond', 'Count', "CountPerSecond", "Prozent", "Sekunden"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>