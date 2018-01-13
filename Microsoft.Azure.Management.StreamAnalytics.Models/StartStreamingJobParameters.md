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
            Parameter für die Streaming-Auftrag starten zur Verfügung gestellt.
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
            Initialisiert eine neue Instanz der StartStreamingJobParameters-Klasse.
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
        <param name="outputStartMode">Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden beginnen mit einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben, oder starten aus dem Zeitpunkt des letzten Ereignisses-Ausgabe.
            Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """</param>
        <param name="outputStartTime">Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird. Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.</param>
        <summary>
            Initialisiert eine neue Instanz der StartStreamingJobParameters-Klasse.
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
            Ruft ab oder legt Wert kann "jobstarttime", "customtime" oder "lastoutputeventtime", um anzugeben, ob der Startpunkt des ausgabeereignisstreams gestartet werden soll, wenn der Auftrag gestartet wird, werden ausgehend von einem benutzerdefinierten Zeitstempel, der über die Eigenschaft "outputstarttime" angegeben oder ab dem letzten Ereignis Ausgabe starten. Folgende Werte sind möglich: "" jobstarttime ","customtime ""","lastoutputeventtime """
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
            Ruft ab oder legt ihn fest-Wert ist entweder ein ISO-8601-formatierter Zeitstempel, der den Anfangspunkt des ausgabeereignisstreams angibt, oder null, um anzugeben, dass der ausgabeereignisstream gestartet wird bei jedem der streamingauftrag gestartet wird. Diese Eigenschaft muss einen Wert aufweisen, wenn "outputstartmode" auf "customtime" festgelegt ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>