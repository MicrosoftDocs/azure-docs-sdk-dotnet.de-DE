<Type Name="ActivityRun" FullName="Microsoft.Azure.Management.DataFactory.Models.ActivityRun">
  <TypeSignature Language="C#" Value="public class ActivityRun" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ActivityRun extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.ActivityRun" />
  <TypeSignature Language="VB.NET" Value="Public Class ActivityRun" />
  <TypeSignature Language="F#" Value="type ActivityRun = class" />
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
            Informationen zu einer Aktivität, die in einer Pipeline ausgeführt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityRun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.#ctor" />
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
            Initialisiert eine neue Instanz der ActivityRun-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ActivityRun (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string pipelineName = null, string pipelineRunId = null, string activityName = null, string activityType = null, string activityRunId = null, string linkedServiceName = null, string status = null, Nullable&lt;DateTime&gt; activityRunStart = null, Nullable&lt;DateTime&gt; activityRunEnd = null, Nullable&lt;int&gt; durationInMs = null, object input = null, object output = null, object error = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string pipelineName, string pipelineRunId, string activityName, string activityType, string activityRunId, string linkedServiceName, string status, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; activityRunStart, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; activityRunEnd, valuetype System.Nullable`1&lt;int32&gt; durationInMs, object input, object output, object error) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{System.Int32},System.Object,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional pipelineName As String = null, Optional pipelineRunId As String = null, Optional activityName As String = null, Optional activityType As String = null, Optional activityRunId As String = null, Optional linkedServiceName As String = null, Optional status As String = null, Optional activityRunStart As Nullable(Of DateTime) = null, Optional activityRunEnd As Nullable(Of DateTime) = null, Optional durationInMs As Nullable(Of Integer) = null, Optional input As Object = null, Optional output As Object = null, Optional error As Object = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.ActivityRun : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string * string * string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * obj * obj * obj -&gt; Microsoft.Azure.Management.DataFactory.Models.ActivityRun" Usage="new Microsoft.Azure.Management.DataFactory.Models.ActivityRun (additionalProperties, pipelineName, pipelineRunId, activityName, activityType, activityRunId, linkedServiceName, status, activityRunStart, activityRunEnd, durationInMs, input, output, error)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipelineRunId" Type="System.String" />
        <Parameter Name="activityName" Type="System.String" />
        <Parameter Name="activityType" Type="System.String" />
        <Parameter Name="activityRunId" Type="System.String" />
        <Parameter Name="linkedServiceName" Type="System.String" />
        <Parameter Name="status" Type="System.String" />
        <Parameter Name="activityRunStart" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="activityRunEnd" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="durationInMs" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="input" Type="System.Object" />
        <Parameter Name="output" Type="System.Object" />
        <Parameter Name="error" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="additionalProperties">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</param>
        <param name="pipelineName">Der Name der Pipeline.</param>
        <param name="pipelineRunId">Führen Sie die Id der Pipeline.</param>
        <param name="activityName">Der Name der Aktivität.</param>
        <param name="activityType">Der Typ der Aktivität.</param>
        <param name="activityRunId">Führen Sie die Id der Aktivität.</param>
        <param name="linkedServiceName">Der Name des Diensts Compute verknüpft.</param>
        <param name="status">Führen Sie der Status der Aktivität.</param>
        <param name="activityRunStart">Die Startzeit der Aktivität im Format "ISO 8601" ausführen.</param>
        <param name="activityRunEnd">Die Endzeit der Aktivität im Format "ISO 8601" ausführen.</param>
        <param name="durationInMs">Führen Sie die Dauer der Aktivität.</param>
        <param name="input">Die Eingabe für die Aktivität.</param>
        <param name="output">Die Ausgabe für die Aktivität definiert.</param>
        <param name="error">Der Fehler, wenn alle von der Aktivität ausgeführt.</param>
        <summary>
            Initialisiert eine neue Instanz der ActivityRun-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityName">
      <MemberSignature Language="C#" Value="public string ActivityName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityName As String" />
      <MemberSignature Language="F#" Value="member this.ActivityName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityRunEnd">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ActivityRunEnd { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ActivityRunEnd" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunEnd" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityRunEnd As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ActivityRunEnd : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunEnd" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityRunEnd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Endzeit der Aktivität im Format "ISO 8601" ausführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityRunId">
      <MemberSignature Language="C#" Value="public string ActivityRunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityRunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityRunId As String" />
      <MemberSignature Language="F#" Value="member this.ActivityRunId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityRunId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Id der ausführenden Aktivität.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityRunStart">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ActivityRunStart { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ActivityRunStart" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunStart" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityRunStart As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ActivityRunStart : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityRunStart" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityRunStart")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit der Aktivität im Format "ISO 8601" ausführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ActivityType">
      <MemberSignature Language="C#" Value="public string ActivityType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ActivityType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ActivityType As String" />
      <MemberSignature Language="F#" Value="member this.ActivityType : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.ActivityType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="activityType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ der Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AdditionalProperties">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IDictionary&lt;string,object&gt; AdditionalProperties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IDictionary`2&lt;string, object&gt; AdditionalProperties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.AdditionalProperties" />
      <MemberSignature Language="VB.NET" Value="Public Property AdditionalProperties As IDictionary(Of String, Object)" />
      <MemberSignature Language="F#" Value="member this.AdditionalProperties : System.Collections.Generic.IDictionary&lt;string, obj&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.AdditionalProperties" />
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.DurationInMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DurationInMs As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DurationInMs : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.DurationInMs" />
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
            Ruft die Dauer der Ausführung der Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public object Error { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Error" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Error" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Error As Object" />
      <MemberSignature Language="F#" Value="member this.Error : obj" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Error" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="error")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Fehler ab, wenn alle von der Aktivität ausgeführt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Input">
      <MemberSignature Language="C#" Value="public object Input { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Input" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Input" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Input As Object" />
      <MemberSignature Language="F#" Value="member this.Input : obj" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Input" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="input")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Eingabe für die Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinkedServiceName">
      <MemberSignature Language="C#" Value="public string LinkedServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinkedServiceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.LinkedServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinkedServiceName As String" />
      <MemberSignature Language="F#" Value="member this.LinkedServiceName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.LinkedServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="linkedServiceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Diensts Compute verknüpft.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Output">
      <MemberSignature Language="C#" Value="public object Output { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance object Output" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Output" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Output As Object" />
      <MemberSignature Language="F#" Value="member this.Output : obj" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Output" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="output")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausgabe für die Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.PipelineName" />
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
            Ruft den Namen der Pipeline ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineRunId">
      <MemberSignature Language="C#" Value="public string PipelineRunId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineRunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.PipelineRunId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PipelineRunId As String" />
      <MemberSignature Language="F#" Value="member this.PipelineRunId : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.PipelineRunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineRunId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Id der Pipeline Ausführung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Status">
      <MemberSignature Language="C#" Value="public string Status { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Status" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Status" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Status As String" />
      <MemberSignature Language="F#" Value="member this.Status : string" Usage="Microsoft.Azure.Management.DataFactory.Models.ActivityRun.Status" />
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
            Ruft den Status der Ausführung der Aktivität ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>