<Type Name="Metric" FullName="Microsoft.Azure.Management.Monitor.Models.Metric">
  <TypeSignature Language="C#" Value="public class Metric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Metric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.Metric" />
  <TypeSignature Language="VB.NET" Value="Public Class Metric" />
  <TypeSignature Language="F#" Value="type Metric = class" />
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
            Die Ergebnisdaten einer Abfrage.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.#ctor" />
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
            Initialisiert eine neue Instanz der Metrik-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Metric (string id, string type, Microsoft.Azure.Management.Monitor.Models.LocalizableString name, Microsoft.Azure.Management.Monitor.Models.Unit unit, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; timeseries);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string type, class Microsoft.Azure.Management.Monitor.Models.LocalizableString name, valuetype Microsoft.Azure.Management.Monitor.Models.Unit unit, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; timeseries) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.#ctor(System.String,System.String,Microsoft.Azure.Management.Monitor.Models.LocalizableString,Microsoft.Azure.Management.Monitor.Models.Unit,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.Metric : string * string * Microsoft.Azure.Management.Monitor.Models.LocalizableString * Microsoft.Azure.Management.Monitor.Models.Unit * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Metric" Usage="new Microsoft.Azure.Management.Monitor.Models.Metric (id, type, name, unit, timeseries)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="name" Type="Microsoft.Azure.Management.Monitor.Models.LocalizableString" />
        <Parameter Name="unit" Type="Microsoft.Azure.Management.Monitor.Models.Unit" />
        <Parameter Name="timeseries" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt;" />
      </Parameters>
      <Docs>
        <param name="id">die Metrik-Id.</param>
        <param name="type">der Ressourcentyp der Metrik Ressource.</param>
        <param name="name">der Name und der Anzeigename der Metrik, d. h. es ist in lokalisierbare Zeichenfolge.</param>
        <param name="unit">Die Einheit der Metrik. Folgende Werte sind möglich: 'Count', 'Bytes', "Sekunden", "CountPerSecond", "BytesPerSecond", "Prozent", "Millisekunden", "ByteSeconds", "Unspecified"</param>
        <param name="timeseries">die Zeitreihe zurückgegeben, wenn eine Datenabfrage ausgeführt wird.</param>
        <summary>
            Initialisiert eine neue Instanz der Metrik-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die metrische-Id.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.LocalizableString Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Monitor.Models.LocalizableString Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As LocalizableString" />
      <MemberSignature Language="F#" Value="member this.Name : Microsoft.Azure.Management.Monitor.Models.LocalizableString with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.LocalizableString</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt sie fest, der Name und der Anzeigename der Metrik, d. h. es ist in lokalisierbare Zeichenfolge.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeseries">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; Timeseries { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; Timeseries" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Timeseries" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeseries As IList(Of TimeSeriesElement)" />
      <MemberSignature Language="F#" Value="member this.Timeseries : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Timeseries" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timeseries")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.TimeSeriesElement&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeitreihe beim Ausführen einer Datenabfrage zurückgegeben wird ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public string Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As String" />
      <MemberSignature Language="F#" Value="member this.Type : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
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
            Ruft ab oder legt den Ressourcentyp des der metrikressourcen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Monitor.Models.Unit Unit { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Monitor.Models.Unit Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Metric.Unit" />
      <MemberSignature Language="VB.NET" Value="Public Property Unit As Unit" />
      <MemberSignature Language="F#" Value="member this.Unit : Microsoft.Azure.Management.Monitor.Models.Unit with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Metric.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Monitor.Models.Unit</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, der Metrik. Folgende Werte sind möglich: 'Count', 'Bytes', "Sekunden", "CountPerSecond", "BytesPerSecond", "Prozent", "Millisekunden", "ByteSeconds", "Unspecified"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Metric.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="metric.Validate " />
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