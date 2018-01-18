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
            <span data-ttu-id="a577d-101">Der erweiterte Data Lake Analytics-Auftrag Informationseigenschaften zurückgegeben, wenn Sie einen bestimmten Auftrag abrufen.</span><span class="sxs-lookup"><span data-stu-id="a577d-101">The extended Data Lake Analytics job information properties returned when retrieving a specific job.</span></span>
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
            <span data-ttu-id="a577d-102">Initialisiert eine neue Instanz der JobInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a577d-102">Initializes a new instance of the JobInformation class.</span></span>
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
        <param name="name"><span data-ttu-id="a577d-103">der angezeigte Name des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-103">the friendly name of the job.</span></span></param>
        <param name="type"><span data-ttu-id="a577d-104">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).</span><span class="sxs-lookup"><span data-stu-id="a577d-104">the job type of the current job (Hive or USql).</span></span>
            <span data-ttu-id="a577d-105">Folgende Werte sind möglich: "USql", "Struktur"</span><span class="sxs-lookup"><span data-stu-id="a577d-105">Possible values include: 'USql', 'Hive'</span></span></param>
        <param name="properties"><span data-ttu-id="a577d-106">die spezifischen Eigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-106">the job specific properties.</span></span></param>
        <param name="jobId"><span data-ttu-id="a577d-107">der Auftrag eindeutige Bezeichner (eine GUID).</span><span class="sxs-lookup"><span data-stu-id="a577d-107">the job's unique identifier (a GUID).</span></span></param>
        <param name="submitter"><span data-ttu-id="a577d-108">der Benutzer oder das Konto, das der Auftrag übermittelt.</span><span class="sxs-lookup"><span data-stu-id="a577d-108">the user or account that submitted the job.</span></span></param>
        <param name="degreeOfParallelism"><span data-ttu-id="a577d-109">der Grad der Parallelität für diesen Auftrag verwendet.</span><span class="sxs-lookup"><span data-stu-id="a577d-109">the degree of parallelism used for this job.</span></span> <span data-ttu-id="a577d-110">Wenn Set auf kleiner als 0 1 standardmäßig generiert, muss größer als 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="a577d-110">This must be greater than 0, if set to less than 0 it will default to 1.</span></span></param>
        <param name="priority"><span data-ttu-id="a577d-111">die Priority-Wert für den aktuellen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="a577d-111">the priority value for the current job.</span></span>
            <span data-ttu-id="a577d-112">Niedrigere Nummern haben eine höhere Priorität.</span><span class="sxs-lookup"><span data-stu-id="a577d-112">Lower numbers have a higher priority.</span></span> <span data-ttu-id="a577d-113">Standardmäßig verfügt ein Auftrag eine Priorität von 1000.</span><span class="sxs-lookup"><span data-stu-id="a577d-113">By default, a job has a priority of 1000.</span></span> <span data-ttu-id="a577d-114">Dies muss größer als 0 sein.</span><span class="sxs-lookup"><span data-stu-id="a577d-114">This must be greater than 0.</span></span></param>
        <param name="submitTime"><span data-ttu-id="a577d-115">der Zeitpunkt, zu der Auftrag an den Dienst übermittelt wurde.</span><span class="sxs-lookup"><span data-stu-id="a577d-115">the time the job was submitted to the service.</span></span></param>
        <param name="startTime"><span data-ttu-id="a577d-116">Die Startzeit des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-116">the start time of the job.</span></span></param>
        <param name="endTime"><span data-ttu-id="a577d-117">Die Ausführungszeit des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-117">the completion time of the job.</span></span></param>
        <param name="state"><span data-ttu-id="a577d-118">der Status des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-118">the job state.</span></span> <span data-ttu-id="a577d-119">Wenn der Auftrag im Status "beendet" ist, finden Sie in Ergebnis und ErrorMessage, Weitere Informationen.</span><span class="sxs-lookup"><span data-stu-id="a577d-119">When the job is in the Ended state, refer to Result and ErrorMessage for details.</span></span> <span data-ttu-id="a577d-120">Folgende Werte sind möglich: "Akzeptiert", "Kompilieren", "Beendet", "New", "Queued", "Wird ausgeführt", "Planung", "starten", "Angehalten", "WaitingForCapacity"</span><span class="sxs-lookup"><span data-stu-id="a577d-120">Possible values include: 'Accepted', 'Compiling', 'Ended', 'New', 'Queued', 'Running', 'Scheduling', 'Starting', 'Paused', 'WaitingForCapacity'</span></span></param>
        <param name="result"><span data-ttu-id="a577d-121">Das Ergebnis der Ausführung eines Auftrags oder das aktuelle Ergebnis des ausgeführten Auftrags.</span><span class="sxs-lookup"><span data-stu-id="a577d-121">the result of job execution or the current result of the running job.</span></span> <span data-ttu-id="a577d-122">Folgende Werte sind möglich: "None", "Succeeded", "Abgebrochen", "Fehler"</span><span class="sxs-lookup"><span data-stu-id="a577d-122">Possible values include: 'None', 'Succeeded', 'Cancelled', 'Failed'</span></span></param>
        <param name="logFolder"><span data-ttu-id="a577d-123">die Protokoll-Ordnerpfad in folgendem Format verwendet: Adl: / /&lt;AccountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/.</span><span class="sxs-lookup"><span data-stu-id="a577d-123">the log folder path to use in the following format: adl://&lt;accountName&gt;.azuredatalakestore.net/system/jobservice/jobs/Usql/2016/03/13/17/18/5fe51957-93bc-4de0-8ddc-c5a4753b068b/logs/.</span></span></param>
        <param name="logFilePatterns"><span data-ttu-id="a577d-124">die Liste der Dateinamenmuster Protokoll, in der LogFolder gefunden.</span><span class="sxs-lookup"><span data-stu-id="a577d-124">the list of log file name patterns to find in the logFolder.</span></span> <span data-ttu-id="a577d-125">"*" ist das einzige übereinstimmenden Zeichen zulässig. Beispiel für das Format: JobExecution*.log oder *MeinProtokoll*".txt"</span><span class="sxs-lookup"><span data-stu-id="a577d-125">'*' is the only matching character allowed. Example format: jobExecution*.log or *mylog*.txt</span></span></param>
        <param name="related"><span data-ttu-id="a577d-126">die wiederholte Auftrag Informationen Beziehungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a577d-126">the recurring job relationship information properties.</span></span></param>
        <param name="errorMessage"><span data-ttu-id="a577d-127">Details der Fehlermeldung für den Auftrag, wenn der Auftrag ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="a577d-127">the error message details for the job, if the job failed.</span></span></param>
        <param name="stateAuditRecords"><span data-ttu-id="a577d-128">der Status des Auftrags Überwachungsdatensätze, gibt an, wann verschiedene Vorgänge zu diesem Auftrag ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="a577d-128">the job state audit records, indicating when various operations have been performed on this job.</span></span></param>
        <summary>
            <span data-ttu-id="a577d-129">Initialisiert eine neue Instanz der JobInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="a577d-129">Initializes a new instance of the JobInformation class.</span></span>
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
            <span data-ttu-id="a577d-130">Ruft den Fehler Nachrichtendetails für den Auftrag, wenn der Auftrag ist fehlgeschlagen.</span><span class="sxs-lookup"><span data-stu-id="a577d-130">Gets the error message details for the job, if the job failed.</span></span>
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
            <span data-ttu-id="a577d-131">Abrufen oder Festlegen des Auftrags spezifische Eigenschaften.</span><span class="sxs-lookup"><span data-stu-id="a577d-131">Gets or sets the job specific properties.</span></span>
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
            <span data-ttu-id="a577d-132">Ruft den Auftrag ab, das Zustand Audit-Datensätze, der angibt, wenn verschiedene Vorgänge zu diesem Auftrag ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="a577d-132">Gets the job state audit records, indicating when various operations have been performed on this job.</span></span>
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
            <span data-ttu-id="a577d-133">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="a577d-133">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="a577d-134">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="a577d-134">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>