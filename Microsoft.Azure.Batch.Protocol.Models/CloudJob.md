<Type Name="CloudJob" FullName="Microsoft.Azure.Batch.Protocol.Models.CloudJob">
  <TypeSignature Language="C#" Value="public class CloudJob" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudJob extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.CloudJob" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudJob" />
  <TypeSignature Language="F#" Value="type CloudJob = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Ein Azure Batch-Auftrag.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJob ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CloudJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudJob (string id = null, string displayName = null, Nullable&lt;bool&gt; usesTaskDependencies = null, string url = null, string eTag = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, Nullable&lt;int&gt; priority = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask = null, Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask = null, Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings = null, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation executionInfo = null, Microsoft.Azure.Batch.Protocol.Models.JobStatistics stats = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string displayName, valuetype System.Nullable`1&lt;bool&gt; usesTaskDependencies, string url, string eTag, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, valuetype System.Nullable`1&lt;int32&gt; priority, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask jobManagerTask, class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask jobPreparationTask, class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask jobReleaseTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; commonEnvironmentSettings, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; onTaskFailure, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation executionInfo, class Microsoft.Azure.Batch.Protocol.Models.JobStatistics stats) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.#ctor(System.String,System.String,System.Nullable{System.Boolean},System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.JobState},System.Nullable{System.DateTime},System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.JobManagerTask,Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask,Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting},Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem},Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation,Microsoft.Azure.Batch.Protocol.Models.JobStatistics)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.CloudJob : string * string * Nullable&lt;bool&gt; * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.JobManagerTask * Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask * Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; * Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation * Microsoft.Azure.Batch.Protocol.Models.JobStatistics -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJob" Usage="new Microsoft.Azure.Batch.Protocol.Models.CloudJob (id, displayName, usesTaskDependencies, url, eTag, lastModified, creationTime, state, stateTransitionTime, previousState, previousStateTransitionTime, priority, constraints, jobManagerTask, jobPreparationTask, jobReleaseTask, commonEnvironmentSettings, poolInfo, onAllTasksComplete, onTaskFailure, metadata, executionInfo, stats)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="usesTaskDependencies" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="eTag" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="jobManagerTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobManagerTask" />
        <Parameter Name="jobPreparationTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask" />
        <Parameter Name="jobReleaseTask" Type="Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask" />
        <Parameter Name="commonEnvironmentSettings" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="onTaskFailure" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation" />
        <Parameter Name="stats" Type="Microsoft.Azure.Batch.Protocol.Models.JobStatistics" />
      </Parameters>
      <Docs>
        <param name="id">Eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.</param>
        <param name="displayName">Der Anzeigename für den Auftrag.</param>
        <param name="usesTaskDependencies">Gibt an, ob Aufgaben im Auftrag Abhängigkeiten untereinander definieren können. Der Standardwert ist false.</param>
        <param name="url">Die URL des Auftrags.</param>
        <param name="eTag">Das ETag des Auftrags.</param>
        <param name="lastModified">Der letzten Änderung des Auftrags.</param>
        <param name="creationTime">Der Zeitpunkt der Erstellung des Auftrags.</param>
        <param name="state">Der aktuelle Status des Auftrags.</param>
        <param name="stateTransitionTime">Der Zeitpunkt, zu dem der Auftrag seinem aktuellen Status erlangt hat.</param>
        <param name="previousState">Der vorherige Status des Auftrags.</param>
        <param name="previousStateTransitionTime">Der Zeitpunkt, an dem der Auftrag den vorherigen Zustand angenommen hat.</param>
        <param name="priority">Die Priorität des Auftrags.</param>
        <param name="constraints">Die ausführungseinschränkungen für den Auftrag.</param>
        <param name="jobManagerTask">Die Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.</param>
        <param name="jobPreparationTask">Der Auftrag zur Vorbereitung-Task.</param>
        <param name="jobReleaseTask">Der Task Auftrag freigeben.</param>
        <param name="commonEnvironmentSettings">Die Liste der allgemeinen umgebungsvariableneinstellungen. Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.</param>
        <param name="poolInfo">Die pooleinstellungen, die dem Auftrag zugeordnet.</param>
        <param name="onAllTasksComplete">Sollte der Batch-Dienst Maßnahmen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</param>
        <param name="onTaskFailure">Sollte der Batch-Dienst Maßnahmen, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</param>
        <param name="metadata">Eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.</param>
        <param name="executionInfo">Die Ausführungsinformationen für den Auftrag.</param>
        <param name="stats">Statistiken zum Ressourceneinsatz während der gesamten Lebensdauer des Auftrags.</param>
        <summary>
            Initialisiert eine neue Instanz der CloudJob-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonEnvironmentSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; CommonEnvironmentSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.CommonEnvironmentSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonEnvironmentSettings As IList(Of EnvironmentSetting)" />
      <MemberSignature Language="F#" Value="member this.CommonEnvironmentSettings : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.CommonEnvironmentSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="commonEnvironmentSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.EnvironmentSetting&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der allgemeinen umgebungsvariableneinstellungen.
            Diese Umgebungsvariablen sind für alle Aufgaben im Auftrag (einschließlich der Auftrags-Manager "," Auftrag zur Vorbereitung "und" Auftrag Version Aufgaben) festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Einzelne Vorgänge können eine umgebungseinstellung, die hier angegebene durch Angabe der gleiche Name der Einstellung mit einem anderen Wert überschreiben.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ausführungseinschränkungen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt der Erstellung des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.ETag" />
      <MemberSignature Language="VB.NET" Value="Public Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="eTag")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das ETag des Auftrags fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist eine nicht transparente Zeichenfolge. Sie können es verwenden, um zu ermitteln, ob zwischen den Anforderungen der Auftrag geändert wurde. Insbesondere können werden übergeben das ETag beim Aktualisieren eines Auftrags, um anzugeben, dass die Änderungen wirksam werden soll, nur dann, wenn keine andere Person auf der Auftrag in der Zwischenzeit geändert wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As JobExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.ExecutionInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="executionInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Ausführungsinformationen für den Auftrag.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt eine Zeichenfolge, die den Auftrag im Konto eindeutig identifiziert.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die ID ist unter Beibehaltung von Groß-/Kleinschreibung und Groß-/Kleinschreibung (d. h., Sie verfügen nicht zwei IDs innerhalb eines Kontos, die sich nur in Groß-bzw. Kleinschreibung unterscheiden).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobManagerTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobManagerTask JobManagerTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobManagerTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobManagerTask As JobManagerTask" />
      <MemberSignature Language="F#" Value="member this.JobManagerTask : Microsoft.Azure.Batch.Protocol.Models.JobManagerTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobManagerTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobManagerTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobManagerTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Details einer Auftrags-Manager-Aufgabe gestartet werden, wenn der Auftrag gestartet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobPreparationTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask JobPreparationTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobPreparationTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobPreparationTask As JobPreparationTask" />
      <MemberSignature Language="F#" Value="member this.JobPreparationTask : Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobPreparationTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobPreparationTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Übernimmt oder bestimmt die Vorbereitung des Auftrags-Aufgabe.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Auftrag zur Vorbereitung Aufgabe ist eine spezielle Aufgabe führen Sie auf jedem Knoten vor allen anderen Aufgaben des Auftrags.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="JobReleaseTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask JobReleaseTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobReleaseTask" />
      <MemberSignature Language="VB.NET" Value="Public Property JobReleaseTask As JobReleaseTask" />
      <MemberSignature Language="F#" Value="member this.JobReleaseTask : Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.JobReleaseTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobReleaseTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobReleaseTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Version des Auftrags fest.
            </summary>
        <value>To be added.</value>
        <remarks>
            Die Auftrags-Release-Aufgabe ist eine spezielle Aufgabe, die am Ende des Auftrags ausgeführt werden, auf jedem Knoten, die von allen anderen Aufgaben des Auftrags ausgeführt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Zeitpunkt der letzten Änderung des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist der letzten Ausführung bei der der Auftrag Level-Daten, z. B. der Status des Auftrags "oder" Priorität ", geändert wurde. Es ist nicht auf Aufgabenebene Änderungen, z. B. das Hinzufügen, neue Aufgaben oder Aufgaben, die statusänderung abwägen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von Name / Wert-Paaren, die dem Auftrag als Metadaten zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>
            Der Batch-Dienst weist keine Bedeutung zu Metadaten; Es ist ausschließlich für die Verwendung von Benutzercode.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion der Batch-Dienst ausgeführt werden sollen, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.
            </summary>
        <value>To be added.</value>
        <remarks>
            "NoAction" - Unternehmen Sie nichts. Der Auftrag bleibt aktiv, es sei denn, beendet oder anderweitig deaktiviert. TerminateJob - Auftrags zu beenden. Der Auftrag TerminateReason wird auf "AllTasksComplete" festgelegt. Der Standardwert ist "NoAction". Folgende Werte sind möglich: 'NoAction', 'TerminateJob'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTaskFailure">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; OnTaskFailure" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnTaskFailure" />
      <MemberSignature Language="VB.NET" Value="Public Property OnTaskFailure As Nullable(Of OnTaskFailure)" />
      <MemberSignature Language="F#" Value="member this.OnTaskFailure : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.OnTaskFailure" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onTaskFailure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnTaskFailure&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.
            </summary>
        <value>To be added.</value>
        <remarks>
            Eine Aufgabe wird als mit fehlerhaften If hat eine FailureInfo. Ein FailureInfo wird festgelegt, wenn die Aufgabe mit einem Exitcode ungleich 0 (null) abgeschlossen ist, nachdem die Wiederholungsanzahl für schwellenwertbenachrichtigungen oder wenn Fehler beim Starten der Aufgabe aufgetreten ist, z. B. aufgrund einer Ressourcendatei herunterladen Fehler.
            "NoAction" - Unternehmen Sie nichts. PerformExitOptionsJobAction - führen Sie die Aktion, die die Aufgabe beenden-Bedingung in der abhängigkeitsauflistung ExitConditions zugeordnet. (Dies kann immer noch keine Aktion ausgeführt wird, führen Wenn, was den Task angegeben ist.) Der Standardwert ist "NoAction". Folgende Werte sind möglich: 'NoAction', 'PerformExitOptionsJobAction'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die pooleinstellungen, die dem Auftrag zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den vorherigen Status des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nicht festgelegt werden, wenn der Auftrag seinen anfänglichen aktiven Status hat.
            Folgende Werte sind möglich: "aktiv", "deaktivieren", "deaktiviert", "aktivieren", "Beenden", "abgeschlossen", "löschen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an der der Auftrag den vorherigen Zustand angenommen hat.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nicht festgelegt werden, wenn der Auftrag seinen anfänglichen aktiven Status hat.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Priorität des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Priority-Werte reichen von-1000 bis 1000,-1000 wird die niedrigste Priorität und 1000 die höchste Priorität. Der Standardwert ist 0.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Status des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "aktiv", "deaktivieren", "deaktiviert", "aktivieren", "Beenden", "abgeschlossen", "löschen"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der der Auftrag seinem aktuellen Status erlangt hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stats">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobStatistics Stats { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobStatistics Stats" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Stats" />
      <MemberSignature Language="VB.NET" Value="Public Property Stats As JobStatistics" />
      <MemberSignature Language="F#" Value="member this.Stats : Microsoft.Azure.Batch.Protocol.Models.JobStatistics with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Stats" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stats")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt ressourcennutzungsstatistiken für die gesamte Lebensdauer des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsesTaskDependencies">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; UsesTaskDependencies { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; UsesTaskDependencies" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.CloudJob.UsesTaskDependencies" />
      <MemberSignature Language="VB.NET" Value="Public Property UsesTaskDependencies As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.UsesTaskDependencies : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.CloudJob.UsesTaskDependencies" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="usesTaskDependencies")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, ob die Aufgaben im Auftrag Abhängigkeiten untereinander definieren können. Der Standardwert ist false.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.CloudJob.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudJob.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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