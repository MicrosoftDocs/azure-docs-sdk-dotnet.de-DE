<Type Name="JobInformationBasic" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic">
  <TypeSignature Language="C#" Value="public class JobInformationBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInformationBasic extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInformationBasic" />
  <TypeSignature Language="F#" Value="type JobInformationBasic = class" />
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
            Die allgemeine Data Lake Analytics-Auftrag Informationseigenschaften.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformationBasic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobInformationBasic-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformationBasic (string name, Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Nullable&lt;Guid&gt; jobId = null, string submitter = null, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, Nullable&lt;DateTimeOffset&gt; submitTime = null, Nullable&lt;DateTimeOffset&gt; startTime = null, Nullable&lt;DateTimeOffset&gt; endTime = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result = null, string logFolder = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; jobId, string submitter, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; submitTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result, string logFolder, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.#ctor(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult},System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As JobType, Optional jobId As Nullable(Of Guid) = null, Optional submitter As String = null, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional submitTime As Nullable(Of DateTimeOffset) = null, Optional startTime As Nullable(Of DateTimeOffset) = null, Optional endTime As Nullable(Of DateTimeOffset) = null, Optional state As Nullable(Of JobState) = null, Optional result As Nullable(Of JobResult) = null, Optional logFolder As String = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic : string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic (name, type, jobId, submitter, degreeOfParallelism, priority, submitTime, startTime, endTime, state, result, logFolder, logFilePatterns, related)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="jobId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="submitter" Type="System.String" />
        <Parameter Name="degreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="submitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="startTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt;" />
        <Parameter Name="result" Type="System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt;" />
        <Parameter Name="logFolder" Type="System.String" />
        <Parameter Name="logFilePatterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="related" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
      </Parameters>
      <Docs>
        <param name="name">der angezeigte Name des Auftrags.</param>
        <param name="type">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"</param>
        <param name="jobId">der Auftrag eindeutige Bezeichner (eine GUID).</param>
        <param name="submitter">der Benutzer oder das Konto, das der Auftrag übermittelt.</param>
        <param name="degreeOfParallelism">der Grad der Parallelität für diesen Auftrag verwendet. Wenn Set auf kleiner als 0 1 standardmäßig generiert, muss größer als 0 (null) sein.</param>
        <param name="priority">die Priority-Wert für den aktuellen Auftrag.
            Niedrigere Nummern haben eine höhere Priorität. Standardmäßig verfügt ein Auftrag eine Priorität von 1000. Dies muss größer als 0 sein.</param>
        <param name="submitTime">der Zeitpunkt, zu der Auftrag an den Dienst übermittelt wurde.</param>
        <param name="startTime">Die Startzeit des Auftrags.</param>
        <param name="endTime">Die Ausführungszeit des Auftrags.</param>
        <param name="state">der Status des Auftrags. Wenn der Auftrag im Status "beendet" ist, finden Sie in Ergebnis und ErrorMessage, Weitere Informationen. Folgende Werte sind möglich: "Akzeptiert", "Kompilieren", "Beendet", "New", "Queued", "Wird ausgeführt", "Planung", "starten", "Angehalten", "WaitingForCapacity"</param>
        <param name="result">Das Ergebnis der Ausführung eines Auftrags oder das aktuelle Ergebnis des ausgeführten Auftrags. Folgende Werte sind möglich: "None", "Succeeded", "Abgebrochen", "Fehler"</param>
        <param name="logFolder">die Protokoll-Ordnerpfad in folgendem Format verwendet: Adl: / /&lt;AccountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/.</param>
        <param name="logFilePatterns">die Liste der Dateinamenmuster Protokoll, in der LogFolder gefunden. "*" ist das einzige übereinstimmenden Zeichen zulässig. Beispiel für das Format: JobExecution*.log oder *MeinProtokoll*".txt"</param>
        <param name="related">die wiederholte Auftrag Informationen Beziehungseigenschaften.</param>
        <summary>
            Initialisiert eine neue Instanz der JobInformationBasic-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.DegreeOfParallelism" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="degreeOfParallelism")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Grad an Parallelität für diesen Auftrag verwendet. Wenn Set auf kleiner als 0 1 standardmäßig generiert, muss größer als 0 (null) sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; EndTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausführungszeit des Auftrags ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; JobId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.JobId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.JobId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Auftrag eindeutige Bezeichner (eine GUID) ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFilePatterns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; LogFilePatterns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; LogFilePatterns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.LogFilePatterns" />
      <MemberSignature Language="VB.NET" Value="Public Property LogFilePatterns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.LogFilePatterns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.LogFilePatterns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logFilePatterns")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Dateinamenmuster Protokoll, in der LogFolder gefunden. "*" ist das einzige übereinstimmenden Zeichen zulässig. Beispiel für das Format: JobExecution*.log oder *MeinProtokoll*".txt"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFolder">
      <MemberSignature Language="C#" Value="public string LogFolder { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LogFolder" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.LogFolder" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LogFolder As String" />
      <MemberSignature Language="F#" Value="member this.LogFolder : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.LogFolder" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="logFolder")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Protokoll-Ordnerpfad in folgendem Format verwendet: Adl: / /&amp;Lt; AccountName&amp;gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Anzeigenamen des Auftrags.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
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
            Ruft ab oder legt den Prioritätswert für den aktuellen Auftrag. Niedrigere Nummern haben eine höhere Priorität. Standardmäßig verfügt ein Auftrag eine Priorität von 1000.
            Dies muss größer als 0 sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Related">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Related" />
      <MemberSignature Language="VB.NET" Value="Public Property Related As JobRelationshipProperties" />
      <MemberSignature Language="F#" Value="member this.Related : Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Related" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="related")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des periodischen Auftrags Beziehungseigenschaften-Informationen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; Result" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As Nullable(Of JobResult)" />
      <MemberSignature Language="F#" Value="member this.Result : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="result")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ergebnis der Ausführung des Auftrags oder das aktuelle Ergebnis von der aktuell ausgeführten Auftrag ab. Folgende Werte sind möglich: "None", "Succeeded", "Abgebrochen", "Fehler"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.StartTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="startTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Startzeit des Auftrags ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As Nullable(Of JobState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Auftragsstatus ab. Wenn der Auftrag im Status "beendet" ist, finden Sie in Ergebnis und ErrorMessage, Weitere Informationen. Folgende Werte sind möglich: "Akzeptiert", "Kompilieren", "Beendet", "New", "Queued", "Wird ausgeführt", "Planung", "starten", "Angehalten", "WaitingForCapacity"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Submitter">
      <MemberSignature Language="C#" Value="public string Submitter { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Submitter" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Submitter" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Submitter As String" />
      <MemberSignature Language="F#" Value="member this.Submitter : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Submitter" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="submitter")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Benutzer oder das Konto, das der Auftrag übermittelt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; SubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; SubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.SubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.SubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.SubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="submitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeit ab, die der Auftrag an den Dienst übermittelt wurde.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobType Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As JobType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobInformationBasic.Validate " />
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