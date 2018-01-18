<Type Name="TaskInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskInformation">
  <TypeSignature Language="C#" Value="public class TaskInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskInformation" />
  <TypeSignature Language="F#" Value="type TaskInformation = class" />
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
            <span data-ttu-id="718bf-101">Informationen zu einer Aufgabe, die auf einem Serverknoten ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="718bf-101">Information about a task running on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.#ctor" />
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
            <span data-ttu-id="718bf-102">Initialisiert eine neue Instanz der Klasse TaskInformation an.</span><span class="sxs-lookup"><span data-stu-id="718bf-102">Initializes a new instance of the TaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskInformation (Microsoft.Azure.Batch.Protocol.Models.TaskState taskState, string taskUrl = null, string jobId = null, string taskId = null, Nullable&lt;int&gt; subtaskId = null, Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation executionInfo = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState taskState, string taskUrl, string jobId, string taskId, valuetype System.Nullable`1&lt;int32&gt; subtaskId, class Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation executionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.#ctor(Microsoft.Azure.Batch.Protocol.Models.TaskState,System.String,System.String,System.String,System.Nullable{System.Int32},Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskInformation : Microsoft.Azure.Batch.Protocol.Models.TaskState * string * string * string * Nullable&lt;int&gt; * Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskInformation (taskState, taskUrl, jobId, taskId, subtaskId, executionInfo)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskState" Type="Microsoft.Azure.Batch.Protocol.Models.TaskState" />
        <Parameter Name="taskUrl" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="taskId" Type="System.String" />
        <Parameter Name="subtaskId" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="executionInfo" Type="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation" />
      </Parameters>
      <Docs>
        <param name="taskState"><span data-ttu-id="718bf-103">Der aktuelle Status der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="718bf-103">The current state of the task.</span></span></param>
        <param name="taskUrl"><span data-ttu-id="718bf-104">Die URL der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="718bf-104">The URL of the task.</span></span></param>
        <param name="jobId"><span data-ttu-id="718bf-105">Die ID des Auftrags, zu dem die Aufgabe gehört.</span><span class="sxs-lookup"><span data-stu-id="718bf-105">The ID of the job to which the task belongs.</span></span></param>
        <param name="taskId"><span data-ttu-id="718bf-106">Die ID des Tasks.</span><span class="sxs-lookup"><span data-stu-id="718bf-106">The ID of the task.</span></span></param>
        <param name="subtaskId"><span data-ttu-id="718bf-107">Die ID der Teilvorgang, wenn die Aufgabe einen Vorgang mit mehreren Instanzen.</span><span class="sxs-lookup"><span data-stu-id="718bf-107">The ID of the subtask if the task is a multi-instance task.</span></span></param>
        <param name="executionInfo"><span data-ttu-id="718bf-108">Informationen zur Ausführung des Tasks.</span><span class="sxs-lookup"><span data-stu-id="718bf-108">Information about the execution of the task.</span></span></param>
        <summary>
            <span data-ttu-id="718bf-109">Initialisiert eine neue Instanz der Klasse TaskInformation an.</span><span class="sxs-lookup"><span data-stu-id="718bf-109">Initializes a new instance of the TaskInformation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecutionInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation ExecutionInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation ExecutionInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.ExecutionInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property ExecutionInfo As TaskExecutionInformation" />
      <MemberSignature Language="F#" Value="member this.ExecutionInfo : Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.ExecutionInfo" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskExecutionInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-110">Abrufen oder Festlegen von Informationen über die Ausführung des Tasks.</span><span class="sxs-lookup"><span data-stu-id="718bf-110">Gets or sets information about the execution of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobId">
      <MemberSignature Language="C#" Value="public string JobId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JobId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.JobId" />
      <MemberSignature Language="VB.NET" Value="Public Property JobId As String" />
      <MemberSignature Language="F#" Value="member this.JobId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.JobId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="jobId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-111">Ruft ab oder legt die ID des Auftrags, zu dem die Aufgabe gehört.</span><span class="sxs-lookup"><span data-stu-id="718bf-111">Gets or sets the ID of the job to which the task belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubtaskId">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SubtaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SubtaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.SubtaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubtaskId As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SubtaskId : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.SubtaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subtaskId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-112">Ruft ab oder legt die ID für die Unteraufgaben fest, wenn der Task eine Aufgabe mit mehreren Instanzen ist.</span><span class="sxs-lookup"><span data-stu-id="718bf-112">Gets or sets the ID of the subtask if the task is a multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskId">
      <MemberSignature Language="C#" Value="public string TaskId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskId" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskId As String" />
      <MemberSignature Language="F#" Value="member this.TaskId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-113">Ruft ab oder legt die ID des Vorgangs fest.</span><span class="sxs-lookup"><span data-stu-id="718bf-113">Gets or sets the ID of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskState TaskState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.TaskState TaskState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskState" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskState As TaskState" />
      <MemberSignature Language="F#" Value="member this.TaskState : Microsoft.Azure.Batch.Protocol.Models.TaskState with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-114">Ruft ab oder legt den aktuellen Status der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="718bf-114">Gets or sets the current state of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="718bf-115">Folgende Werte sind möglich: "aktiv", "vorbereitet", "wird ausgeführt", "abgeschlossen"</span><span class="sxs-lookup"><span data-stu-id="718bf-115">Possible values include: 'active', 'preparing', 'running', 'completed'</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskUrl">
      <MemberSignature Language="C#" Value="public string TaskUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskInformation.TaskUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="718bf-116">Ruft ab oder legt die URL der Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="718bf-116">Gets or sets the URL of the task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskInformation.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskInformation.Validate " />
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
            <span data-ttu-id="718bf-117">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="718bf-117">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="718bf-118">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="718bf-118">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>