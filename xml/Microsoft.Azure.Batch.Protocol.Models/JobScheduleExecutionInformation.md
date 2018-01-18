<Type Name="JobScheduleExecutionInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation">
  <TypeSignature Language="C#" Value="public class JobScheduleExecutionInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobScheduleExecutionInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class JobScheduleExecutionInformation" />
  <TypeSignature Language="F#" Value="type JobScheduleExecutionInformation = class" />
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
            <span data-ttu-id="73d43-101">Enthält Informationen zu den Aufträgen, die Waren und wird unter einem Auftragszeitplan ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="73d43-101">Contains information about jobs that have been and will be run under a job schedule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleExecutionInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.#ctor" />
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
            <span data-ttu-id="73d43-102">Initialisiert eine neue Instanz der JobScheduleExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73d43-102">Initializes a new instance of the JobScheduleExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobScheduleExecutionInformation (Nullable&lt;DateTime&gt; nextRunTime = null, Microsoft.Azure.Batch.Protocol.Models.RecentJob recentJob = null, Nullable&lt;DateTime&gt; endTime = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; nextRunTime, class Microsoft.Azure.Batch.Protocol.Models.RecentJob recentJob, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; endTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.#ctor(System.Nullable{System.DateTime},Microsoft.Azure.Batch.Protocol.Models.RecentJob,System.Nullable{System.DateTime})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation : Nullable&lt;DateTime&gt; * Microsoft.Azure.Batch.Protocol.Models.RecentJob * Nullable&lt;DateTime&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation (nextRunTime, recentJob, endTime)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nextRunTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="recentJob" Type="Microsoft.Azure.Batch.Protocol.Models.RecentJob" />
        <Parameter Name="endTime" Type="System.Nullable&lt;System.DateTime&gt;" />
      </Parameters>
      <Docs>
        <param name="nextRunTime"><span data-ttu-id="73d43-103">Das nächste Mal an dem ein Auftrag unter diesem Plan erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="73d43-103">The next time at which a job will be created under this schedule.</span></span></param>
        <param name="recentJob"><span data-ttu-id="73d43-104">Informationen zu den aktuellen Auftrag unter der Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="73d43-104">Information about the most recent job under the job schedule.</span></span></param>
        <param name="endTime"><span data-ttu-id="73d43-105">Der Zeitpunkt, zu dem der Zeitplan beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="73d43-105">The time at which the schedule ended.</span></span></param>
        <summary>
            <span data-ttu-id="73d43-106">Initialisiert eine neue Instanz der JobScheduleExecutionInformation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="73d43-106">Initializes a new instance of the JobScheduleExecutionInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; EndTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; EndTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.EndTime" />
      <MemberSignature Language="VB.NET" Value="Public Property EndTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.EndTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.EndTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="endTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d43-107">Ruft ab oder legt die Zeit, zu dem der Zeitplan beendet wurde.</span><span class="sxs-lookup"><span data-stu-id="73d43-107">Gets or sets the time at which the schedule ended.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="73d43-108">Diese Eigenschaft wird festgelegt, nur dann, wenn der Zeitplan für Aufträge in den abgeschlossenen Zustand versetzt wird.</span><span class="sxs-lookup"><span data-stu-id="73d43-108">This property is set only if the job schedule is in the completed state.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NextRunTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; NextRunTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; NextRunTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.NextRunTime" />
      <MemberSignature Language="VB.NET" Value="Public Property NextRunTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.NextRunTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.NextRunTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nextRunTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d43-109">Ruft ab oder legt das nächste Mal an dem ein Auftrag unter diesem Plan erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="73d43-109">Gets or sets the next time at which a job will be created under this schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="73d43-110">Diese Eigenschaft ist nur sinnvoll, wenn der Zeitplan im aktiven Zustand ist, wenn die Zeit, um eingeht.</span><span class="sxs-lookup"><span data-stu-id="73d43-110">This property is meaningful only if the schedule is in the active state when the time comes around.</span></span> <span data-ttu-id="73d43-111">Z. B. wenn der Zeitplan deaktiviert ist, wird kein Auftrag auf NextRunTime-Objekt erstellt werden, wenn der Auftrag vorher aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="73d43-111">For example, if the schedule is disabled, no job will be created at nextRunTime unless the job is enabled before then.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RecentJob">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.RecentJob RecentJob { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.RecentJob RecentJob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.RecentJob" />
      <MemberSignature Language="VB.NET" Value="Public Property RecentJob As RecentJob" />
      <MemberSignature Language="F#" Value="member this.RecentJob : Microsoft.Azure.Batch.Protocol.Models.RecentJob with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExecutionInformation.RecentJob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="recentJob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.RecentJob</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="73d43-112">Ruft ab oder legt Informationen zum neuesten Auftrag unter der Auftragszeitplan.</span><span class="sxs-lookup"><span data-stu-id="73d43-112">Gets or sets information about the most recent job under the job schedule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="73d43-113">Diese Eigenschaft ist nur vorhanden, wenn mindestens ein Auftrag unter dem Zeitplan ausgeführt wurde.</span><span class="sxs-lookup"><span data-stu-id="73d43-113">This property is present only if the at least one job has run under the schedule.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>