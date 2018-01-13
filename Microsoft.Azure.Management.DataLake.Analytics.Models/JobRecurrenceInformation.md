<Type Name="JobRecurrenceInformation" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation">
  <TypeSignature Language="C#" Value="public class JobRecurrenceInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobRecurrenceInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobRecurrenceInformation" />
  <TypeSignature Language="F#" Value="type JobRecurrenceInformation = class" />
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
            <span data-ttu-id="95bec-101">Wiederholung Auftragsinformationen für einen bestimmten Wiederholung.</span><span class="sxs-lookup"><span data-stu-id="95bec-101">Recurrence job information for a specific recurrence.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRecurrenceInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="95bec-102">Initialisiert eine neue Instanz der JobRecurrenceInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95bec-102">Initializes a new instance of the JobRecurrenceInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobRecurrenceInformation (Nullable&lt;Guid&gt; recurrenceId = null, string recurrenceName = null, Nullable&lt;int&gt; numJobsFailed = null, Nullable&lt;int&gt; numJobsCanceled = null, Nullable&lt;int&gt; numJobsSucceeded = null, Nullable&lt;double&gt; auHoursFailed = null, Nullable&lt;double&gt; auHoursCanceled = null, Nullable&lt;double&gt; auHoursSucceeded = null, Nullable&lt;DateTimeOffset&gt; lastSubmitTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.Guid&gt; recurrenceId, string recurrenceName, valuetype System.Nullable`1&lt;int32&gt; numJobsFailed, valuetype System.Nullable`1&lt;int32&gt; numJobsCanceled, valuetype System.Nullable`1&lt;int32&gt; numJobsSucceeded, valuetype System.Nullable`1&lt;float64&gt; auHoursFailed, valuetype System.Nullable`1&lt;float64&gt; auHoursCanceled, valuetype System.Nullable`1&lt;float64&gt; auHoursSucceeded, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; lastSubmitTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.#ctor(System.Nullable{System.Guid},System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Int32},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.Double},System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional recurrenceId As Nullable(Of Guid) = null, Optional recurrenceName As String = null, Optional numJobsFailed As Nullable(Of Integer) = null, Optional numJobsCanceled As Nullable(Of Integer) = null, Optional numJobsSucceeded As Nullable(Of Integer) = null, Optional auHoursFailed As Nullable(Of Double) = null, Optional auHoursCanceled As Nullable(Of Double) = null, Optional auHoursSucceeded As Nullable(Of Double) = null, Optional lastSubmitTime As Nullable(Of DateTimeOffset) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation : Nullable&lt;Guid&gt; * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation (recurrenceId, recurrenceName, numJobsFailed, numJobsCanceled, numJobsSucceeded, auHoursFailed, auHoursCanceled, auHoursSucceeded, lastSubmitTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="recurrenceId" Type="System.Nullable&lt;System.Guid&gt;" />
        <Parameter Name="recurrenceName" Type="System.String" />
        <Parameter Name="numJobsFailed" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsCanceled" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="numJobsSucceeded" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="auHoursFailed" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursCanceled" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="auHoursSucceeded" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="lastSubmitTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="recurrenceId"><span data-ttu-id="95bec-103">die Wiederholung Bezeichner (GUID) pro Aktivität/Skript ungeachtet der verwendeten Iterationen eindeutig.</span><span class="sxs-lookup"><span data-stu-id="95bec-103">the recurrence identifier (a GUID), unique per activity/script, regardless of iterations.</span></span> <span data-ttu-id="95bec-104">Dies ist etwas, um verschiedene Vorkommen des gleichen Auftrags miteinander zu verbinden.</span><span class="sxs-lookup"><span data-stu-id="95bec-104">This is something to link different occurrences of the same job together.</span></span></param>
        <param name="recurrenceName"><span data-ttu-id="95bec-105">der Name Wiederholung Benutzerfreundlicher Name für die Korrelation zwischen Aufträgen.</span><span class="sxs-lookup"><span data-stu-id="95bec-105">the recurrence name, user friendly name for the correlation between jobs.</span></span></param>
        <param name="numJobsFailed"><span data-ttu-id="95bec-106">die Anzahl der Aufträge in dieser Serie, die fehlgeschlagen sind.</span><span class="sxs-lookup"><span data-stu-id="95bec-106">the number of jobs in this recurrence that have failed.</span></span></param>
        <param name="numJobsCanceled"><span data-ttu-id="95bec-107">die Anzahl der Aufträge in dieser Serie, die abgebrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="95bec-107">the number of jobs in this recurrence that have been canceled.</span></span></param>
        <param name="numJobsSucceeded"><span data-ttu-id="95bec-108">die Anzahl der Aufträge in dieser Serie, die erfolgreich ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="95bec-108">the number of jobs in this recurrence that have succeeded.</span></span></param>
        <param name="auHoursFailed"><span data-ttu-id="95bec-109">die Anzahl der Auftrag Ausführung Stunden mit der fehlerhaften Aufträge.</span><span class="sxs-lookup"><span data-stu-id="95bec-109">the number of job execution hours that resulted in failed jobs.</span></span></param>
        <param name="auHoursCanceled"><span data-ttu-id="95bec-110">die Anzahl der Auftrag Ausführung Stunden, die in den abgebrochenen Aufträge geführt haben.</span><span class="sxs-lookup"><span data-stu-id="95bec-110">the number of job execution hours that resulted in canceled jobs.</span></span></param>
        <param name="auHoursSucceeded"><span data-ttu-id="95bec-111">die Anzahl der Auftrag Ausführung Stunden, die in erfolgreich abgeschlossenen Aufträgen geführt haben.</span><span class="sxs-lookup"><span data-stu-id="95bec-111">the number of job execution hours that resulted in successful jobs.</span></span></param>
        <param name="lastSubmitTime"><span data-ttu-id="95bec-112">Zeitpunkt der letzten wurde ein Auftrag in dieser Serie übermittelt.</span><span class="sxs-lookup"><span data-stu-id="95bec-112">the last time a job in this recurrence was submitted.</span></span></param>
        <summary>
            <span data-ttu-id="95bec-113">Initialisiert eine neue Instanz der JobRecurrenceInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="95bec-113">Initializes a new instance of the JobRecurrenceInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursCanceled As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursCanceled : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-114">Ruft die Anzahl der Auftrag Ausführung Stunden, die in den abgebrochenen Aufträge geführt haben.</span><span class="sxs-lookup"><span data-stu-id="95bec-114">Gets the number of job execution hours that resulted in canceled jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursFailed As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursFailed : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-115">Ruft die Anzahl der Auftrag Ausführung Stunden mit der fehlerhaften Aufträge.</span><span class="sxs-lookup"><span data-stu-id="95bec-115">Gets the number of job execution hours that resulted in failed jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuHoursSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; AuHoursSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; AuHoursSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AuHoursSucceeded As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.AuHoursSucceeded : Nullable&lt;double&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.AuHoursSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="auHoursSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-116">Ruft die Anzahl der Auftrag Ausführung Stunden, die in erfolgreich abgeschlossenen Aufträgen geführt haben.</span><span class="sxs-lookup"><span data-stu-id="95bec-116">Gets the number of job execution hours that resulted in successful jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastSubmitTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; LastSubmitTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; LastSubmitTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.LastSubmitTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastSubmitTime As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.LastSubmitTime : Nullable&lt;DateTimeOffset&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.LastSubmitTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastSubmitTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-117">Ruft ab der letzten Ausführung ein Auftrags in dieser Serie übermittelt wurde.</span><span class="sxs-lookup"><span data-stu-id="95bec-117">Gets the last time a job in this recurrence was submitted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsCanceled">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsCanceled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsCanceled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsCanceled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsCanceled As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsCanceled : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsCanceled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsCanceled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-118">Ruft die Anzahl der Aufträge in dieser Serie, die abgebrochen wurden.</span><span class="sxs-lookup"><span data-stu-id="95bec-118">Gets the number of jobs in this recurrence that have been canceled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsFailed">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsFailed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsFailed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsFailed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsFailed As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsFailed : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsFailed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsFailed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-119">Ruft die Anzahl der Aufträge in dieser Serie, die fehlgeschlagen sind.</span><span class="sxs-lookup"><span data-stu-id="95bec-119">Gets the number of jobs in this recurrence that have failed.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumJobsSucceeded">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumJobsSucceeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumJobsSucceeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsSucceeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumJobsSucceeded As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumJobsSucceeded : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.NumJobsSucceeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="numJobsSucceeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-120">Ruft die Anzahl der Aufträge in dieser Serie, die erfolgreich ausgeführt wurden.</span><span class="sxs-lookup"><span data-stu-id="95bec-120">Gets the number of jobs in this recurrence that have succeeded.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceId">
      <MemberSignature Language="C#" Value="public Nullable&lt;Guid&gt; RecurrenceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Guid&gt; RecurrenceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecurrenceId As Nullable(Of Guid)" />
      <MemberSignature Language="F#" Value="member this.RecurrenceId : Nullable&lt;Guid&gt;" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceId" />
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
        <ReturnType>System.Nullable&lt;System.Guid&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="95bec-121">Ruft den Bezeichner Wiederholung (eine GUID), jede Aktivität/Skript ungeachtet der verwendeten Iterationen eindeutig.</span><span class="sxs-lookup"><span data-stu-id="95bec-121">Gets the recurrence identifier (a GUID), unique per activity/script, regardless of iterations.</span></span> <span data-ttu-id="95bec-122">Dies ist etwas, um verschiedene Vorkommen des gleichen Auftrags miteinander zu verbinden.</span><span class="sxs-lookup"><span data-stu-id="95bec-122">This is something to link different occurrences of the same job together.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RecurrenceName">
      <MemberSignature Language="C#" Value="public string RecurrenceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RecurrenceName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RecurrenceName As String" />
      <MemberSignature Language="F#" Value="member this.RecurrenceName : string" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.JobRecurrenceInformation.RecurrenceName" />
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
            <span data-ttu-id="95bec-123">Ruft die Wiederholung Name, den benutzerfreundlichen Namen für die Korrelation zwischen Aufträgen ab.</span><span class="sxs-lookup"><span data-stu-id="95bec-123">Gets the recurrence name, user friendly name for the correlation between jobs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>