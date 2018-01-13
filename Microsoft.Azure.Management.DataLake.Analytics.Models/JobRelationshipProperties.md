<Type Name="JobRelationshipProperties" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties">
  <TypeSignature Language="C#" Value="public class JobRelationshipProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobRelationshipProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class JobRelationshipProperties" />
  <TypeSignature Language="F#" Value="type JobRelationshipProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Auftrag Informationen Beziehungseigenschaften einschließlich Pipelineinformationen, Korrelationsinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRelationshipProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobRelationshipProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRelationshipProperties (Guid recurrenceId, Nullable&lt;Guid&gt; pipelineId = null, string pipelineName = null, string pipelineUri = null, Nullable&lt;Guid&gt; runId = null, string recurrenceName = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid recurrenceId, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; pipelineId, string pipelineName, string pipelineUri, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; runId, string recurrenceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.#ctor(System.Guid,System.Nullable{System.Guid},System.String,System.String,System.Nullable{System.Guid},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (recurrenceId As Guid, Optional pipelineId As Nullable(Of Guid) = null, Optional pipelineName As String = null, Optional pipelineUri As String = null, Optional runId As Nullable(Of Guid) = null, Optional recurrenceName As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties : Guid * Nullable&lt;Guid&gt; * string * string * Nullable&lt;Guid&gt; * string -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties (recurrenceId, pipelineId, pipelineName, pipelineUri, runId, recurrenceName)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceId" Type="System.Guid" />
        <Parameter Name="pipelineId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="pipelineName" Type="System.String" />
        <Parameter Name="pipelineUri" Type="System.String" />
        <Parameter Name="runId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="recurrenceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="recurrenceId">die Wiederholung Bezeichner (GUID) pro Aktivität/Skript ungeachtet der verwendeten Iterationen eindeutig. Dies ist etwas, um verschiedene Vorkommen des gleichen Auftrags miteinander zu verbinden.</param>
        <param name="pipelineId">die Beziehung Pipeline Auftragsbezeichner (eine GUID).</param>
        <param name="pipelineName">der angezeigte Name der Pipeline an Auftrag Beziehung, die nicht eindeutig sein muss.</param>
        <param name="pipelineUri">die Pipeline Uri eindeutig ist, Links zu der ursprungsdienst für die Pipeline.</param>
        <param name="runId">der führen Bezeichner (GUID) eindeutige Bezeichner der Iteration dieser Pipeline.</param>
        <param name="recurrenceName">der Name Wiederholung Benutzerfreundlicher Name für die Korrelation zwischen Aufträgen.</param>
        <summary>
            Initialisiert eine neue Instanz der JobRelationshipProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; PipelineId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; PipelineId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineId" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.PipelineId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Pipeline Auftrag beziehungsbezeichner (eine GUID).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineName">
      <MemberSignature Language="C#" Value="public string PipelineName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineName" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineName As String" />
      <MemberSignature Language="F#" Value="member this.PipelineName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den benutzerfreundlichen Namen der Pipeline an Auftrag Beziehung, der nicht eindeutig sein muss.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PipelineUri">
      <MemberSignature Language="C#" Value="public string PipelineUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PipelineUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineUri" />
      <MemberSignature Language="VB.NET" Value="Public Property PipelineUri As String" />
      <MemberSignature Language="F#" Value="member this.PipelineUri : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.PipelineUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pipelineUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Pipeline-Uri eindeutig ist, Links zu den ursprungsdienst für die Pipeline.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceId">
      <MemberSignature Language="C#" Value="public Guid RecurrenceId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid RecurrenceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RecurrenceId" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceId As Guid" />
      <MemberSignature Language="F#" Value="member this.RecurrenceId : Guid with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RecurrenceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Wiederholung (eine GUID), eindeutige ID pro Aktivität/Skript ungeachtet der verwendeten Iterationen. Dies ist etwas, um verschiedene Vorkommen des gleichen Auftrags miteinander zu verbinden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceName">
      <MemberSignature Language="C#" Value="public string RecurrenceName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecurrenceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RecurrenceName" />
      <MemberSignature Language="VB.NET" Value="Public Property RecurrenceName As String" />
      <MemberSignature Language="F#" Value="member this.RecurrenceName : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RecurrenceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recurrenceName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, die Wiederholung-Name, den benutzerfreundlichen Namen für die Korrelation zwischen Aufträgen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RunId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RunId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RunId" />
      <MemberSignature Language="VB.NET" Value="Public Property RunId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RunId : Nullable&lt;Guid&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.RunId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="runId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen den Ausführung Bezeichner (GUID) eindeutige Bezeichner der Iteration dieser Pipeline.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobRelationshipProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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