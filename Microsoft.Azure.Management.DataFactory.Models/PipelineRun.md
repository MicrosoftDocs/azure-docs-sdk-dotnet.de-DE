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
            <span data-ttu-id="03e3f-101">Informationen zu einer Pipeline ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="03e3f-101">Information about a pipeline run.</span></span>
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
            <span data-ttu-id="03e3f-102">Initialisiert eine neue Instanz der PipelineRun-Klasse.</span><span class="sxs-lookup"><span data-stu-id="03e3f-102">Initializes a new instance of the PipelineRun class.</span></span>
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
        <param name="additionalProperties"><span data-ttu-id="03e3f-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="03e3f-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="runId"><span data-ttu-id="03e3f-104">Der Bezeichner eines Testlaufs.</span><span class="sxs-lookup"><span data-stu-id="03e3f-104">Identifier of a run.</span></span></param>
        <param name="pipelineName"><span data-ttu-id="03e3f-105">Der pipelinename.</span><span class="sxs-lookup"><span data-stu-id="03e3f-105">The pipeline name.</span></span></param>
        <param name="parameters"><span data-ttu-id="03e3f-106">Die Liste vollständig oder teilweise des Parameternamens führen-Wert-Paar in der Pipeline verwendet.</span><span class="sxs-lookup"><span data-stu-id="03e3f-106">The full or partial list of parameter name, value pair used in the pipeline run.</span></span></param>
        <param name="invokedBy"><span data-ttu-id="03e3f-107">Führen Sie die Entität, die die Pipeline gestartet.</span><span class="sxs-lookup"><span data-stu-id="03e3f-107">Entity that started the pipeline run.</span></span></param>
        <param name="lastUpdated"><span data-ttu-id="03e3f-108">Der letzten Aktualisierung Zeitstempel für die Pipeline im ISO8601-Format Ereignis ausführen.</span><span class="sxs-lookup"><span data-stu-id="03e3f-108">The last updated timestamp for the pipeline run event in ISO8601 format.</span></span></param>
        <param name="runStart"><span data-ttu-id="03e3f-109">Führen Sie die Startzeit für eine Pipeline im ISO8601-Format.</span><span class="sxs-lookup"><span data-stu-id="03e3f-109">The start time of a pipeline run in ISO8601 format.</span></span></param>
        <param name="runEnd"><span data-ttu-id="03e3f-110">Führen Sie die Endzeit einer Pipeline im ISO8601-Format.</span><span class="sxs-lookup"><span data-stu-id="03e3f-110">The end time of a pipeline run in ISO8601 format.</span></span></param>
        <param name="durationInMs"><span data-ttu-id="03e3f-111">Die Dauer einer Pipeline ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="03e3f-111">The duration of a pipeline run.</span></span></param>
        <param name="status"><span data-ttu-id="03e3f-112">Der Status einer Pipeline ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="03e3f-112">The status of a pipeline run.</span></span></param>
        <param name="message"><span data-ttu-id="03e3f-113">Die Nachricht aus einer Pipeline ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="03e3f-113">The message from a pipeline run.</span></span></param>
        <summary>
            <span data-ttu-id="03e3f-114">Initialisiert eine neue Instanz der PipelineRun-Klasse.</span><span class="sxs-lookup"><span data-stu-id="03e3f-114">Initializes a new instance of the PipelineRun class.</span></span>
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
            <span data-ttu-id="03e3f-115">Ruft ab oder legt ihn fest, die nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="03e3f-115">Gets or sets unmatched properties from the message are deserialized this collection</span></span>
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
            <span data-ttu-id="03e3f-116">Ruft die Dauer eines Testlaufs Pipeline ab.</span><span class="sxs-lookup"><span data-stu-id="03e3f-116">Gets the duration of a pipeline run.</span></span>
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
            <span data-ttu-id="03e3f-117">Ruft die Entität, die die Ausführung der Pipeline gestartet.</span><span class="sxs-lookup"><span data-stu-id="03e3f-117">Gets entity that started the pipeline run.</span></span>
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
            <span data-ttu-id="03e3f-118">Ruft den zuletzt aktualisierten Zeitstempel für die Pipeline im ISO8601-Format Ereignis ausführen.</span><span class="sxs-lookup"><span data-stu-id="03e3f-118">Gets the last updated timestamp for the pipeline run event in ISO8601 format.</span></span>
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
            <span data-ttu-id="03e3f-119">Ruft die Nachricht aus einer Ausführung der Pipeline ab.</span><span class="sxs-lookup"><span data-stu-id="03e3f-119">Gets the message from a pipeline run.</span></span>
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
            <span data-ttu-id="03e3f-120">Ruft den vollständigen oder teilweisen Auflistung der Parametername-Wert-Paar, führen Sie in der Pipeline verwendet.</span><span class="sxs-lookup"><span data-stu-id="03e3f-120">Gets the full or partial list of parameter name, value pair used in the pipeline run.</span></span>
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
            <span data-ttu-id="03e3f-121">Ruft den pipelinenamen.</span><span class="sxs-lookup"><span data-stu-id="03e3f-121">Gets the pipeline name.</span></span>
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
            <span data-ttu-id="03e3f-122">Ruft die Endzeit einer Pipeline ausgeführt wird, im ISO8601-Format ab.</span><span class="sxs-lookup"><span data-stu-id="03e3f-122">Gets the end time of a pipeline run in ISO8601 format.</span></span>
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
            <span data-ttu-id="03e3f-123">Ruft den Bezeichner eines Testlaufs.</span><span class="sxs-lookup"><span data-stu-id="03e3f-123">Gets identifier of a run.</span></span>
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
            <span data-ttu-id="03e3f-124">Ruft die Startzeit einer Pipeline ausgeführt wird, im ISO8601-Format ab.</span><span class="sxs-lookup"><span data-stu-id="03e3f-124">Gets the start time of a pipeline run in ISO8601 format.</span></span>
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
            <span data-ttu-id="03e3f-125">Ruft den Status einer Ausführung der Pipeline ab.</span><span class="sxs-lookup"><span data-stu-id="03e3f-125">Gets the status of a pipeline run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>