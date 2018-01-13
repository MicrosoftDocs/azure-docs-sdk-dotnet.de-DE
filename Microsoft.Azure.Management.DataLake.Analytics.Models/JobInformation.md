<Type Name="JobInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation">
  <TypeSignature Language="C#" Value="public class JobInformation : Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobInformation extends Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobInformation&#xA;Inherits JobInformationBasic" />
  <TypeSignature Language="F#" Value="type JobInformation = class&#xA;    inherit JobInformationBasic" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformationBasic</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Der erweiterte Data Lake Analytics-Auftrag Informationseigenschaften zurückgegeben, wenn Sie einen bestimmten Auftrag abrufen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der JobInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobInformation (string name, Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, Nullable&lt;Guid&gt; jobId = null, string submitter = null, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, Nullable&lt;DateTimeOffset&gt; submitTime = null, Nullable&lt;DateTimeOffset&gt; startTime = null, Nullable&lt;DateTimeOffset&gt; endTime = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state = null, Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result = null, string logFolder = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties properties, valuetype System.Nullable`1&lt;valuetype System.Guid&gt; jobId, string submitter, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; submitTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; startTime, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; endTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; state, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; result, string logFolder, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; errorMessage, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; stateAuditRecords) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.#ctor(System.String,Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties,System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{System.DateTimeOffset},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobState},System.Nullable{Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult},System.String,System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties,System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, type As JobType, properties As JobProperties, Optional jobId As Nullable(Of Guid) = null, Optional submitter As String = null, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional submitTime As Nullable(Of DateTimeOffset) = null, Optional startTime As Nullable(Of DateTimeOffset) = null, Optional endTime As Nullable(Of DateTimeOffset) = null, Optional state As Nullable(Of JobState) = null, Optional result As Nullable(Of JobResult) = null, Optional logFolder As String = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null, Optional errorMessage As IList(Of JobErrorDetails) = null, Optional stateAuditRecords As IList(Of JobStateAuditRecord) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation : string * Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties * Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;DateTimeOffset&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobState&gt; * Nullable&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobResult&gt; * string * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation (name, type, properties, jobId, submitter, degreeOfParallelism, priority, submitTime, startTime, endTime, state, result, logFolder, logFilePatterns, related, errorMessage, stateAuditRecords)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties" />
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
        <Parameter Name="errorMessage" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" />
        <Parameter Name="stateAuditRecords" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" />
      </Parameters>
      <Docs>
        <param name="name">der angezeigte Name des Auftrags.</param>
        <param name="type">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).
            Folgende Werte sind möglich: "USql", "Struktur"</param>
        <param name="properties">die spezifischen Eigenschaften des Auftrags.</param>
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
        <param name="errorMessage">Details der Fehlermeldung für den Auftrag, wenn der Auftrag ist fehlgeschlagen.</param>
        <param name="stateAuditRecords">der Status des Auftrags Überwachungsdatensätze, gibt an, wann verschiedene Vorgänge zu diesem Auftrag ausgeführt wurden.</param>
        <summary>
            Initialisiert eine neue Instanz der JobInformation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorMessage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt; ErrorMessage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorMessage As IList(Of JobErrorDetails)" />
      <MemberSignature Language="F#" Value="member this.ErrorMessage : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.ErrorMessage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="errorMessage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobErrorDetails&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Fehler Nachrichtendetails für den Auftrag, wenn der Auftrag ist fehlgeschlagen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As JobProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Analytics.Models.JobProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen des Auftrags spezifische Eigenschaften.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StateAuditRecords">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt; StateAuditRecords" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StateAuditRecords As IList(Of JobStateAuditRecord)" />
      <MemberSignature Language="F#" Value="member this.StateAuditRecords : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.StateAuditRecords" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateAuditRecords")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.JobStateAuditRecord&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Auftrag ab, das Zustand Audit-Datensätze, der angibt, wenn verschiedene Vorgänge zu diesem Auftrag ausgeführt wurden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="jobInformation.Validate " />
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