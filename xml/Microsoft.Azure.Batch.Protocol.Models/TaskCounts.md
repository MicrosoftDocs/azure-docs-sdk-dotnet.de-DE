<Type Name="TaskCounts" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskCounts">
  <TypeSignature Language="C#" Value="public class TaskCounts" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskCounts extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskCounts" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskCounts" />
  <TypeSignature Language="F#" Value="type TaskCounts = class" />
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
            <span data-ttu-id="54ca3-101">Der Task zählt für einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="54ca3-101">The task counts for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskCounts ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.#ctor" />
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
            <span data-ttu-id="54ca3-102">Initialisiert eine neue Instanz der TaskCounts-Klasse.</span><span class="sxs-lookup"><span data-stu-id="54ca3-102">Initializes a new instance of the TaskCounts class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskCounts (int active, int running, int completed, int succeeded, int failed, Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus validationStatus);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 active, int32 running, int32 completed, int32 succeeded, int32 failed, valuetype Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus validationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.#ctor(System.Int32,System.Int32,System.Int32,System.Int32,System.Int32,Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (active As Integer, running As Integer, completed As Integer, succeeded As Integer, failed As Integer, validationStatus As TaskCountValidationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskCounts : int * int * int * int * int * Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskCounts" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskCounts (active, running, completed, succeeded, failed, validationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="active" Type="System.Int32" />
        <Parameter Name="running" Type="System.Int32" />
        <Parameter Name="completed" Type="System.Int32" />
        <Parameter Name="succeeded" Type="System.Int32" />
        <Parameter Name="failed" Type="System.Int32" />
        <Parameter Name="validationStatus" Type="Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus" />
      </Parameters>
      <Docs>
        <param name="active"><span data-ttu-id="54ca3-103">Die Anzahl der Aufgaben im aktiven Zustand.</span><span class="sxs-lookup"><span data-stu-id="54ca3-103">The number of tasks in the active state.</span></span></param>
        <param name="running"><span data-ttu-id="54ca3-104">Die Anzahl der Aufgaben im Zustand ausgeführt werden oder vorbereiten.</span><span class="sxs-lookup"><span data-stu-id="54ca3-104">The number of tasks in the running or preparing state.</span></span></param>
        <param name="completed"><span data-ttu-id="54ca3-105">Die Anzahl der Aufgaben in den abgeschlossenen Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="54ca3-105">The number of tasks in the completed state.</span></span></param>
        <param name="succeeded"><span data-ttu-id="54ca3-106">Die Anzahl der Aufgaben, die erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="54ca3-106">The number of tasks which succeeded.</span></span> <span data-ttu-id="54ca3-107">Eine Aufgabe ist erfolgreich, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Success".</span><span class="sxs-lookup"><span data-stu-id="54ca3-107">A task succeeds if its result (found in the executionInfo property) is 'success'.</span></span></param>
        <param name="failed"><span data-ttu-id="54ca3-108">Die Anzahl der fehlgeschlagenen Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="54ca3-108">The number of tasks which failed.</span></span> <span data-ttu-id="54ca3-109">Ein Task fehlschlägt, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Failure" ist.</span><span class="sxs-lookup"><span data-stu-id="54ca3-109">A task fails if its result (found in the executionInfo property) is 'failure'.</span></span></param>
        <param name="validationStatus"><span data-ttu-id="54ca3-110">Ob der Task zählt wurden überprüft.</span><span class="sxs-lookup"><span data-stu-id="54ca3-110">Whether the task counts have been validated.</span></span></param>
        <summary>
            <span data-ttu-id="54ca3-111">Initialisiert eine neue Instanz der TaskCounts-Klasse.</span><span class="sxs-lookup"><span data-stu-id="54ca3-111">Initializes a new instance of the TaskCounts class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public int Active { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Active" />
      <MemberSignature Language="VB.NET" Value="Public Property Active As Integer" />
      <MemberSignature Language="F#" Value="member this.Active : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Active" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="active")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-112">Ruft ab oder legt die Anzahl der Aufgaben im aktiven Zustand.</span><span class="sxs-lookup"><span data-stu-id="54ca3-112">Gets or sets the number of tasks in the active state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="public int Completed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Completed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Completed" />
      <MemberSignature Language="VB.NET" Value="Public Property Completed As Integer" />
      <MemberSignature Language="F#" Value="member this.Completed : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Completed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-113">Ruft ab oder legt die Anzahl der Aufgaben in den abgeschlossenen Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="54ca3-113">Gets or sets the number of tasks in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="public int Failed { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Failed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Failed" />
      <MemberSignature Language="VB.NET" Value="Public Property Failed As Integer" />
      <MemberSignature Language="F#" Value="member this.Failed : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Failed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="failed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-114">Ruft ab oder legt die Anzahl der fehlgeschlagenen Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="54ca3-114">Gets or sets the number of tasks which failed.</span></span> <span data-ttu-id="54ca3-115">Ein Task fehlschlägt, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Failure" ist.</span><span class="sxs-lookup"><span data-stu-id="54ca3-115">A task fails if its result (found in the executionInfo property) is 'failure'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="public int Running { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Running" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Running" />
      <MemberSignature Language="VB.NET" Value="Public Property Running As Integer" />
      <MemberSignature Language="F#" Value="member this.Running : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Running" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-116">Ruft ab oder legt die Anzahl der Aufgaben in den Zustand ausgeführt werden oder vorbereiten.</span><span class="sxs-lookup"><span data-stu-id="54ca3-116">Gets or sets the number of tasks in the running or preparing state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="public int Succeeded { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Succeeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Public Property Succeeded As Integer" />
      <MemberSignature Language="F#" Value="member this.Succeeded : int with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Succeeded" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="succeeded")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-117">Ruft ab oder legt die Anzahl der Aufgaben, die erfolgreich war.</span><span class="sxs-lookup"><span data-stu-id="54ca3-117">Gets or sets the number of tasks which succeeded.</span></span> <span data-ttu-id="54ca3-118">Eine Aufgabe ist erfolgreich, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Success".</span><span class="sxs-lookup"><span data-stu-id="54ca3-118">A task succeeds if its result (found in the executionInfo property) is 'success'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskCounts.Validate " />
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
            <span data-ttu-id="54ca3-119">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="54ca3-119">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="54ca3-120">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="54ca3-120">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ValidationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus ValidationStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus ValidationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskCounts.ValidationStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property ValidationStatus As TaskCountValidationStatus" />
      <MemberSignature Language="F#" Value="member this.ValidationStatus : Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskCounts.ValidationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="validationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="54ca3-121">Ruft ab oder legt fest, ob die Aufgabe einfach überprüft wurden.</span><span class="sxs-lookup"><span data-stu-id="54ca3-121">Gets or sets whether the task counts have been validated.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="54ca3-122">Folgende Werte sind möglich: "überprüft", "nicht überprüfte"</span><span class="sxs-lookup"><span data-stu-id="54ca3-122">Possible values include: 'validated', 'unvalidated'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>