<Type Name="Response" FullName="Microsoft.Azure.Management.Monitor.Models.Response">
  <TypeSignature Language="C#" Value="public class Response" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Response extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.Models.Response" />
  <TypeSignature Language="VB.NET" Value="Public Class Response" />
  <TypeSignature Language="F#" Value="type Response = class" />
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
            Die Antwort auf eine Abfrage Metriken.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Response ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.#ctor" />
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
            Initialisiert eine neue Instanz der Klasse Antwort.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Response (string timespan, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; value, Nullable&lt;double&gt; cost = null, Nullable&lt;TimeSpan&gt; interval = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string timespan, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.Metric&gt; value, valuetype System.Nullable`1&lt;float64&gt; cost, valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; interval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Monitor.Models.Metric},System.Nullable{System.Double},System.Nullable{System.TimeSpan})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (timespan As String, value As IList(Of Metric), Optional cost As Nullable(Of Double) = null, Optional interval As Nullable(Of TimeSpan) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Monitor.Models.Response : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; * Nullable&lt;double&gt; * Nullable&lt;TimeSpan&gt; -&gt; Microsoft.Azure.Management.Monitor.Models.Response" Usage="new Microsoft.Azure.Management.Monitor.Models.Response (timespan, value, cost, interval)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="timespan" Type="System.String" />
        <Parameter Name="value" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt;" />
        <Parameter Name="cost" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="interval" Type="System.Nullable&lt;System.TimeSpan&gt;" />
      </Parameters>
      <Docs>
        <param name="timespan">Die Zeitspanne, für die die Daten abgerufen wurde. Der Wert besteht aus zwei Datatimes verkettet, getrennt durch "/".  Dies kann in der Zukunft angepasst und vom ursprünglich angeforderten zurückgegeben werden.</param>
        <param name="value">der Wert der Auflistung.</param>
        <param name="cost">Der ganzzahlige Wert, der die Kosten der Abfrage, für die Groß-/Kleinschreibung Daten darstellt.</param>
        <param name="interval">Das Intervall (Fenstergröße) für dem Metrikdaten in zurückgegeben wurde.  Dies kann in der Zukunft angepasst und vom ursprünglich angeforderten zurückgegeben werden.  Dies ist nicht vorhanden, wenn Metadaten angefordert wurde.</param>
        <summary>
            Initialisiert eine neue Instanz der Klasse Antwort.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Cost">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Cost { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Cost" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Cost" />
      <MemberSignature Language="VB.NET" Value="Public Property Cost As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Cost : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Cost" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cost")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den ganzzahligen Wert, der die Kosten der Abfrage, für die Groß-/Kleinschreibung Daten darstellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Interval">
      <MemberSignature Language="C#" Value="public Nullable&lt;TimeSpan&gt; Interval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.TimeSpan&gt; Interval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Interval" />
      <MemberSignature Language="VB.NET" Value="Public Property Interval As Nullable(Of TimeSpan)" />
      <MemberSignature Language="F#" Value="member this.Interval : Nullable&lt;TimeSpan&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Interval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="interval")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.TimeSpan&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Intervall (Fenstergröße) für dem Metrikdaten in zurückgegeben wurde.  Dies kann in der Zukunft angepasst und vom ursprünglich angeforderten zurückgegeben werden.  Dies ist nicht vorhanden, wenn Metadaten angefordert wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timespan">
      <MemberSignature Language="C#" Value="public string Timespan { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Timespan" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Timespan" />
      <MemberSignature Language="VB.NET" Value="Public Property Timespan As String" />
      <MemberSignature Language="F#" Value="member this.Timespan : string with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Timespan" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="timespan")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitraum, für den die Daten abgerufen wurde. Der Wert besteht aus zwei Datatimes verkettet, getrennt durch "/".
            Dies kann in der Zukunft angepasst und vom ursprünglich angeforderten zurückgegeben werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.Models.Response.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="response.Validate " />
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
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; Value { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Monitor.Models.Metric&gt; Value" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Monitor.Models.Response.Value" />
      <MemberSignature Language="VB.NET" Value="Public Property Value As IList(Of Metric)" />
      <MemberSignature Language="F#" Value="member this.Value : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt; with get, set" Usage="Microsoft.Azure.Management.Monitor.Models.Response.Value" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="value")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Monitor.Models.Metric&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert der Auflistung.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>