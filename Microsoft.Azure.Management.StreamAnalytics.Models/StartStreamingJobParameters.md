<Type Name="StartStreamingJobParameters" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters">
  <TypeSignature Language="C#" Value="public class StartStreamingJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StartStreamingJobParameters extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class StartStreamingJobParameters" />
  <TypeSignature Language="F#" Value="type StartStreamingJobParameters = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3a169-101">Parameter für die Streaming-Auftrag starten zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="3a169-101">Parameters supplied to the Start Streaming Job operation.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3a169-102">Initialisiert eine neue Instanz der StartStreamingJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a169-102">Initializes a new instance of the StartStreamingJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StartStreamingJobParameters (string outputStartMode = null, Nullable&lt;DateTime&gt; outputStartTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string outputStartMode, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; outputStartTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.#ctor(System.String,System.Nullable{System.DateTime})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional outputStartMode As String = null, Optional outputStartTime As Nullable(Of DateTime) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters : string * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters (outputStartMode, outputStartTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="outputStartMode" Type="System.String" />
        <Parameter Name="outputStartTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="outputStartMode"><span data-ttu-id="3a169-103">Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden beginnen mit einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben, oder starten aus dem Zeitpunkt des letzten Ereignisses-Ausgabe.</span><span class="sxs-lookup"><span data-stu-id="3a169-103">Value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span>
            <span data-ttu-id="3a169-104">Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """</span><span class="sxs-lookup"><span data-stu-id="3a169-104">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span></param>
        <param name="outputStartTime"><span data-ttu-id="3a169-105">Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="3a169-105">Value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="3a169-106">Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="3a169-106">This property must have a value if outputStartMode is set to CustomTime.</span></span></param>
        <summary>
            <span data-ttu-id="3a169-107">Initialisiert eine neue Instanz der StartStreamingJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3a169-107">Initializes a new instance of the StartStreamingJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartMode">
      <MemberSignature Language="C#" Value="public string OutputStartMode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OutputStartMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartMode As String" />
      <MemberSignature Language="F#" Value="member this.OutputStartMode : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartMode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a169-108">Ruft ab oder legt Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden ausgehend von einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben oder ab dem letzten Ereignis Ausgabe starten.</span><span class="sxs-lookup"><span data-stu-id="3a169-108">Gets or sets value may be JobStartTime, CustomTime, or LastOutputEventTime to indicate whether the starting point of the output event stream should start whenever the job is started, start at a custom user time stamp specified via the outputStartTime property, or start from the last event output time.</span></span> <span data-ttu-id="3a169-109">Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """</span><span class="sxs-lookup"><span data-stu-id="3a169-109">Possible values include: 'JobStartTime', 'CustomTime', 'LastOutputEventTime'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutputStartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; OutputStartTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; OutputStartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberSignature Language="VB.NET" Value="Public Property OutputStartTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.OutputStartTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.StartStreamingJobParameters.OutputStartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="outputStartTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3a169-110">Ruft ab oder legt ihn fest-Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird.</span><span class="sxs-lookup"><span data-stu-id="3a169-110">Gets or sets value is either an ISO-8601 formatted time stamp that indicates the starting point of the output event stream, or null to indicate that the output event stream will start whenever the streaming job is started.</span></span> <span data-ttu-id="3a169-111">Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="3a169-111">This property must have a value if outputStartMode is set to CustomTime.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>