<Type Name="PipelineRun" FullName="Microsoft.Azure.Management.DataFactory.Models.PipelineRun">
  <TypeSignature Language="C#" Value="public class PipelineRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PipelineRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.PipelineRun" />
  <TypeSignature Language="VB.NET" Value="Public Class PipelineRun" />
  <TypeSignature Language="F#" Value="type PipelineRun = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Informationen zu einer Pipeline ausgeführt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der PipelineRun-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PipelineRun (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string runId = null, string pipelineName = null, System.Collections.Generic.IDictionary&lt;string,string&gt; parameters = null, Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy invokedBy = null, Nullable&lt;DateTime&gt; lastUpdated = null, Nullable&lt;DateTime&gt; runStart = null, Nullable&lt;DateTime&gt; runEnd = null, Nullable&lt;int&gt; durationInMs = null, string status = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string runId, string pipelineName, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; parameters, class Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy invokedBy, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastUpdated, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; runStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; runEnd, valuetype System.Nullable`1&lt;int32&gt; durationInMs, string status, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional runId As String = null, Optional pipelineName As String = null, Optional parameters As IDictionary(Of String, String) = null, Optional invokedBy As PipelineRunInvokedBy = null, Optional lastUpdated As Nullable(Of DateTime) = null, Optional runStart As Nullable(Of DateTime) = null, Optional runEnd As Nullable(Of DateTime) = null, Optional durationInMs As Nullable(Of Integer) = null, Optional status As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.PipelineRun : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * string * string -&gt; Microsoft.Azure.Management.DataFactory.Models.PipelineRun" Usage="new Microsoft.Azure.Management.DataFactory.Models.PipelineRun (additionalProperties, runId, pipelineName, parameters, invokedBy, lastUpdated, runStart, runEnd, durationInMs, status, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="runId" Type="System.String" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="parameters" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="invokedBy" Type="Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy" />
        <Parameter Name="lastUpdated" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="runStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="runEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="durationInMs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="runId">Der Bezeichner eines Testlaufs.</param>
        <param name="pipelineName">Der pipelinename.</param>
        <param name="parameters">Die Liste vollständig oder teilweise des Parameternamens führen-Wert-Paar in der Pipeline verwendet.</param>
        <param name="invokedBy">Führen Sie die Entität, die die Pipeline gestartet.</param>
        <param name="lastUpdated">Der letzten Aktualisierung Zeitstempel für die Pipeline im ISO8601-Format Ereignis ausführen.</param>
        <param name="runStart">Führen Sie die Startzeit für eine Pipeline im ISO8601-Format.</param>
        <param name="runEnd">Führen Sie die Endzeit einer Pipeline im ISO8601-Format.</param>
        <param name="durationInMs">Die Dauer einer Pipeline ausgeführt werden soll.</param>
        <param name="status">Der Status einer Pipeline ausgeführt werden soll.</param>
        <param name="message">Die Nachricht aus einer Pipeline ausgeführt werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der PipelineRun-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.AdditionalProperties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonExtensionData</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurationInMs">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DurationInMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DurationInMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.DurationInMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DurationInMs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DurationInMs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.DurationInMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durationInMs")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Dauer eines Testlaufs Pipeline ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokedBy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy InvokedBy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy InvokedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.InvokedBy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InvokedBy As PipelineRunInvokedBy" />
      <MemberSignature Language="F#" Value="member this.InvokedBy : Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.InvokedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="invokedBy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataFactory.Models.PipelineRunInvokedBy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Entität, die die Ausführung der Pipeline gestartet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastUpdated">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastUpdated { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastUpdated" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.LastUpdated" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdated As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastUpdated : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.LastUpdated" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastUpdated")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den zuletzt aktualisierten Zeitstempel für die Pipeline im ISO8601-Format Ereignis ausführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Nachricht aus einer Ausführung der Pipeline ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,string&gt; Parameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, string&gt; Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Parameters As IDictionary(Of String, String)" />
      <MemberSignature Language="F#" Value="member this.Parameters : System.Collections.Generic.IDictionary&lt;string, string&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den vollständigen oder teilweisen Auflistung der Parametername-Wert-Paar, führen Sie in der Pipeline verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.PipelineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den pipelinenamen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RunEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RunEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RunEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Endzeit einer Pipeline ausgeführt wird, im ISO8601-Format ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunId">
      <MemberSignature Language="C#" Value="public string RunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunId As String" />
      <MemberSignature Language="F#" Value="member this.RunId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Bezeichner eines Testlaufs.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; RunStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; RunStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.RunStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.RunStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit einer Pipeline ausgeführt wird, im ISO8601-Format ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.DataFactory.Models.PipelineRun.Status" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="status")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Status einer Ausführung der Pipeline ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>