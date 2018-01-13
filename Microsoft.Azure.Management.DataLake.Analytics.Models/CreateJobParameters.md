<Type Name="CreateJobParameters" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters">
  <TypeSignature Language="C#" Value="public class CreateJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreateJobParameters extends Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" />
  <TypeSignature Language="VB.NET" Value="Public Class CreateJobParameters&#xA;Inherits BaseJobParameters" />
  <TypeSignature Language="F#" Value="type CreateJobParameters = class&#xA;    inherit BaseJobParameters" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataLake.Analytics.Models.BaseJobParameters</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2bef6-101">Die Parameter verwendet, um einen neuen Data Lake Analytics-Auftrag zu senden.</span><span class="sxs-lookup"><span data-stu-id="2bef6-101">The parameters used to submit a new Data Lake Analytics job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateJobParameters ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2bef6-102">Initialisiert eine neue Instanz der CreateJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2bef6-102">Initializes a new instance of the CreateJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreateJobParameters (Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name, Nullable&lt;int&gt; degreeOfParallelism = null, Nullable&lt;int&gt; priority = null, System.Collections.Generic.IList&lt;string&gt; logFilePatterns = null, Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.DataLake.Analytics.Models.JobType type, class Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties properties, string name, valuetype System.Nullable`1&lt;int32&gt; degreeOfParallelism, valuetype System.Nullable`1&lt;int32&gt; priority, class System.Collections.Generic.IList`1&lt;string&gt; logFilePatterns, class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties related) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.#ctor(Microsoft.Azure.Management.DataLake.Analytics.Models.JobType,Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (type As JobType, properties As CreateJobProperties, name As String, Optional degreeOfParallelism As Nullable(Of Integer) = null, Optional priority As Nullable(Of Integer) = null, Optional logFilePatterns As IList(Of String) = null, Optional related As JobRelationshipProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters : Microsoft.Azure.Management.DataLake.Analytics.Models.JobType * Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters (type, properties, name, degreeOfParallelism, priority, logFilePatterns, related)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobType" />
        <Parameter Name="properties" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobProperties" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="degreeOfParallelism" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="logFilePatterns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="related" Type="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="2bef6-103">Der Auftragstyp des aktuellen Auftrags (Hive oder USql).</span><span class="sxs-lookup"><span data-stu-id="2bef6-103">the job type of the current job (Hive or USql).</span></span>
            <span data-ttu-id="2bef6-104">Folgende Werte sind möglich: "USql", "Struktur"</span><span class="sxs-lookup"><span data-stu-id="2bef6-104">Possible values include: 'USql', 'Hive'</span></span></param>
        <param name="properties"><span data-ttu-id="2bef6-105">die spezifischen Eigenschaften des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="2bef6-105">the job specific properties.</span></span></param>
        <param name="name"><span data-ttu-id="2bef6-106">der angezeigte Name des Auftrags zu übermitteln.</span><span class="sxs-lookup"><span data-stu-id="2bef6-106">the friendly name of the job to submit.</span></span></param>
        <param name="degreeOfParallelism"><span data-ttu-id="2bef6-107">der Grad der Parallelität für diesen Auftrag verwenden.</span><span class="sxs-lookup"><span data-stu-id="2bef6-107">the degree of parallelism to use for this job.</span></span> <span data-ttu-id="2bef6-108">Wenn Set auf kleiner als 0 1 standardmäßig generiert, muss größer als 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="2bef6-108">This must be greater than 0, if set to less than 0 it will default to 1.</span></span></param>
        <param name="priority"><span data-ttu-id="2bef6-109">der Priority-Wert, der für den aktuellen Auftrag verwendet.</span><span class="sxs-lookup"><span data-stu-id="2bef6-109">the priority value to use for the current job.</span></span> <span data-ttu-id="2bef6-110">Niedrigere Nummern haben eine höhere Priorität.</span><span class="sxs-lookup"><span data-stu-id="2bef6-110">Lower numbers have a higher priority.</span></span> <span data-ttu-id="2bef6-111">Standardmäßig verfügt ein Auftrag eine Priorität von 1000.</span><span class="sxs-lookup"><span data-stu-id="2bef6-111">By default, a job has a priority of 1000.</span></span> <span data-ttu-id="2bef6-112">Dies muss größer als 0 sein.</span><span class="sxs-lookup"><span data-stu-id="2bef6-112">This must be greater than 0.</span></span></param>
        <param name="logFilePatterns"><span data-ttu-id="2bef6-113">die Liste der Dateinamenmuster Protokoll, in der LogFolder gefunden.</span><span class="sxs-lookup"><span data-stu-id="2bef6-113">the list of log file name patterns to find in the logFolder.</span></span> <span data-ttu-id="2bef6-114">"*" ist das einzige übereinstimmenden Zeichen zulässig. Beispiel für das Format: JobExecution*.log oder *MeinProtokoll*".txt"</span><span class="sxs-lookup"><span data-stu-id="2bef6-114">'*' is the only matching character allowed. Example format: jobExecution*.log or *mylog*.txt</span></span></param>
        <param name="related"><span data-ttu-id="2bef6-115">die wiederholte Auftrag Informationen Beziehungseigenschaften.</span><span class="sxs-lookup"><span data-stu-id="2bef6-115">the recurring job relationship information properties.</span></span></param>
        <summary>
            <span data-ttu-id="2bef6-116">Initialisiert eine neue Instanz der CreateJobParameters-Klasse.</span><span class="sxs-lookup"><span data-stu-id="2bef6-116">Initializes a new instance of the CreateJobParameters class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DegreeOfParallelism">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DegreeOfParallelism { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DegreeOfParallelism" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.DegreeOfParallelism" />
      <MemberSignature Language="VB.NET" Value="Public Property DegreeOfParallelism As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DegreeOfParallelism : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.DegreeOfParallelism" />
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
            <span data-ttu-id="2bef6-117">Ruft ab oder legt den Grad an Parallelität für diesen Auftrag verwenden.</span><span class="sxs-lookup"><span data-stu-id="2bef6-117">Gets or sets the degree of parallelism to use for this job.</span></span> <span data-ttu-id="2bef6-118">Wenn Set auf kleiner als 0 1 standardmäßig generiert, muss größer als 0 (null) sein.</span><span class="sxs-lookup"><span data-stu-id="2bef6-118">This must be greater than 0, if set to less than 0 it will default to 1.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LogFilePatterns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; LogFilePatterns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; LogFilePatterns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.LogFilePatterns" />
      <MemberSignature Language="VB.NET" Value="Public Property LogFilePatterns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.LogFilePatterns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.LogFilePatterns" />
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
            <span data-ttu-id="2bef6-119">Ruft ab oder legt die Liste der Dateinamenmuster Protokoll, in der LogFolder gefunden.</span><span class="sxs-lookup"><span data-stu-id="2bef6-119">Gets or sets the list of log file name patterns to find in the logFolder.</span></span> <span data-ttu-id="2bef6-120">"*" ist das einzige übereinstimmenden Zeichen zulässig. Beispiel für das Format: JobExecution*.log oder *MeinProtokoll*".txt"</span><span class="sxs-lookup"><span data-stu-id="2bef6-120">'*' is the only matching character allowed. Example format: jobExecution*.log or *mylog*.txt</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Name" />
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
            <span data-ttu-id="2bef6-121">Ruft ab oder legt den Anzeigenamen des Auftrags zum Übermitteln von.</span><span class="sxs-lookup"><span data-stu-id="2bef6-121">Gets or sets the friendly name of the job to submit.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Priority" />
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
            <span data-ttu-id="2bef6-122">Ruft ab oder legt den Priority-Wert, der für den aktuellen Auftrag verwendet.</span><span class="sxs-lookup"><span data-stu-id="2bef6-122">Gets or sets the priority value to use for the current job.</span></span> <span data-ttu-id="2bef6-123">Niedrigere Nummern haben eine höhere Priorität.</span><span class="sxs-lookup"><span data-stu-id="2bef6-123">Lower numbers have a higher priority.</span></span> <span data-ttu-id="2bef6-124">Standardmäßig verfügt ein Auftrag Priorität</span><span class="sxs-lookup"><span data-stu-id="2bef6-124">By default, a job has a priority of</span></span>
            1000. <span data-ttu-id="2bef6-125">Dies muss größer als 0 sein.</span><span class="sxs-lookup"><span data-stu-id="2bef6-125">This must be greater than 0.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Related">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties Related" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Related" />
      <MemberSignature Language="VB.NET" Value="Public Property Related As JobRelationshipProperties" />
      <MemberSignature Language="F#" Value="member this.Related : Microsoft.Azure.Management.DataLake.Analytics.Models.JobRelationshipProperties with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Related" />
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
            <span data-ttu-id="2bef6-126">Abrufen oder Festlegen des periodischen Auftrags Beziehungseigenschaften-Informationen.</span><span class="sxs-lookup"><span data-stu-id="2bef6-126">Gets or sets the recurring job relationship information properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.CreateJobParameters.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="createJobParameters.Validate " />
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
            <span data-ttu-id="2bef6-127">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="2bef6-127">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="2bef6-128">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="2bef6-128">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>