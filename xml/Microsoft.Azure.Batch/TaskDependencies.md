<Type Name="TaskDependencies" FullName="Microsoft.Azure.Batch.TaskDependencies">
  <TypeSignature Language="C#" Value="public class TaskDependencies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDependencies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskDependencies" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDependencies" />
  <TypeSignature Language="F#" Value="type TaskDependencies = class&#xA;    interface ITransportObjectProvider&lt;TaskDependencies&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="01d41-101">Gibt alle Abhängigkeiten von einer Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="01d41-101">Specifies any dependencies of a task.</span></span> <span data-ttu-id="01d41-102">Jede Aufgabe, die explizit angegeben wird oder innerhalb einer Abhängigkeit Bereich abgeschlossen werden muss, bevor der abhängige Task geplant wird.</span><span class="sxs-lookup"><span data-stu-id="01d41-102">Any task that is explicitly specified or within a dependency range must complete before the dependant task will be scheduled.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies (System.Collections.Generic.IEnumerable&lt;string&gt; taskIds, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IEnumerable`1&lt;string&gt; taskIds, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; taskIdRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.#ctor(System.Collections.Generic.IEnumerable{System.String},System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.TaskIdRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (taskIds As IEnumerable(Of String), taskIdRanges As IEnumerable(Of TaskIdRange))" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskDependencies : seq&lt;string&gt; * seq&lt;Microsoft.Azure.Batch.TaskIdRange&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="new Microsoft.Azure.Batch.TaskDependencies (taskIds, taskIdRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskIds" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
        <Parameter Name="taskIdRanges" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" />
      </Parameters>
      <Docs>
        <param name="taskIds"><span data-ttu-id="01d41-103">Die Liste der Aufgaben-Ids, die abgeschlossen werden muss, bevor diese Aufgabe geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="01d41-103">The list of task ids that must complete before this task can be scheduled.</span></span> <span data-ttu-id="01d41-104">NULL wird als eine leere Liste behandelt.</span><span class="sxs-lookup"><span data-stu-id="01d41-104">null is treated as an empty list.</span></span></param>
        <param name="taskIdRanges"><span data-ttu-id="01d41-105">Die Liste der Task-Bereiche, die abgeschlossen werden muss, bevor diese Aufgabe geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="01d41-105">The list of task ranges that must complete before this task can be scheduled.</span></span> <span data-ttu-id="01d41-106">NULL wird als eine leere Liste behandelt.</span><span class="sxs-lookup"><span data-stu-id="01d41-106">null is treated as an empty list.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-107">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.TaskDependencies" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="01d41-107">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> class.</span></span>
            </summary>
        <remarks><span data-ttu-id="01d41-108">Dieser Konstruktor stellt die allgemeinste Methode zum Initialisieren eines TaskDependencies-Objekts.</span><span class="sxs-lookup"><span data-stu-id="01d41-108">This constructor provides the most general way of initializing a TaskDependencies object.</span></span>
            <span data-ttu-id="01d41-109">In der Praxis werden die meisten Abhängigkeiten auf eine einzelne Aufgabe, eine Liste der Aufgaben-Ids oder einem einzelnen Bereich von Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="01d41-109">In practice, most dependencies are on a single task, a list of task ids, or a single range of tasks.</span></span> <span data-ttu-id="01d41-110">Sie können diese Abhängigkeiten deutlich mit Ausdrücken <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />, und <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" /> Methoden.</span><span class="sxs-lookup"><span data-stu-id="01d41-110">You can express these dependencies more clearly using <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />, <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />, and <see cref="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" /> methods.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="OnId">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnId (string id);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnId(string id) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnId (id As String) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnId : string -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnId id" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="01d41-111">Die Aufgabe, die von abhängig sind.</span><span class="sxs-lookup"><span data-stu-id="01d41-111">The task to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-112">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine einzelne Aufgabe darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-112">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a single task.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-113">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine einzelne Aufgabe darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-113">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a single task.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIdRange">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIdRange(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIdRange(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIdRange (start As Integer, end As Integer) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIdRange (start, end)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="01d41-114">Der erste Task-Id im Bereich von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-114">The first task id in the range to depend on.</span></span></param>
        <param name="end"><span data-ttu-id="01d41-115">Die letzte Task-Id im Bereich von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-115">The last task id in the range to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-116">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf einen Bereich von Aufgaben-Ids darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-116">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a range of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-117">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von den angegebenen Bereich von Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-117">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified range of tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (System.Collections.Generic.IEnumerable&lt;string&gt; ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(class System.Collections.Generic.IEnumerable`1&lt;string&gt; ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.Collections.Generic.IEnumerable{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ids As IEnumerable(Of String)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : seq&lt;string&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.Collections.Generic.IEnumerable&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="01d41-118">Die Aufgaben von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-118">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-119">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste der Aufgaben-Ids darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-119">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-120">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-120">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnIds">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnIds (params string[] ids);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnIds(string[] ids) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnIds(System.String[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnIds (ParamArray ids As String()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnIds : string[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnIds ids" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ids" Type="System.String[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="ids"><span data-ttu-id="01d41-121">Die Aufgaben von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-121">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-122">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste der Aufgaben-Ids darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-122">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of task ids.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-123">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-123">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (params Microsoft.Azure.Batch.CloudTask[] tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class Microsoft.Azure.Batch.CloudTask[] tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(Microsoft.Azure.Batch.CloudTask[])" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (ParamArray tasks As CloudTask()) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : Microsoft.Azure.Batch.CloudTask[] -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="Microsoft.Azure.Batch.CloudTask[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="tasks"><span data-ttu-id="01d41-124">Die Aufgaben von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-124">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-125">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste von Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-125">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of tasks.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-126">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-126">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnTasks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.TaskDependencies OnTasks (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt; tasks);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.TaskDependencies OnTasks(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.CloudTask&gt; tasks) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskDependencies.OnTasks(System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.CloudTask})" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OnTasks (tasks As IEnumerable(Of CloudTask)) As TaskDependencies" />
      <MemberSignature Language="F#" Value="static member OnTasks : seq&lt;Microsoft.Azure.Batch.CloudTask&gt; -&gt; Microsoft.Azure.Batch.TaskDependencies" Usage="Microsoft.Azure.Batch.TaskDependencies.OnTasks tasks" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskDependencies</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tasks" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.CloudTask&gt;" />
      </Parameters>
      <Docs>
        <param name="tasks"><span data-ttu-id="01d41-127">Die Aufgaben von abhängen.</span><span class="sxs-lookup"><span data-stu-id="01d41-127">The tasks to depend on.</span></span></param>
        <summary>
            <span data-ttu-id="01d41-128">Ruft eine <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit auf eine Liste von Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-128">Gets a <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on a list of tasks.</span></span>
            </summary>
        <returns><span data-ttu-id="01d41-129">Ein <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> , die Abhängigkeit von der angegebenen Aufgaben darstellt.</span><span class="sxs-lookup"><span data-stu-id="01d41-129">A <see cref="T:Microsoft.Azure.Batch.TaskDependencies" /> representing dependency on the specified tasks.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.TaskIdRange&gt; TaskIdRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIdRanges As IReadOnlyList(Of TaskIdRange)" />
      <MemberSignature Language="F#" Value="member this.TaskIdRanges : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIdRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.TaskIdRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01d41-130">Ruft die Liste der Aufgaben-IDs, die von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="01d41-130">Gets the list of task IDs that this task depends on.</span></span> <span data-ttu-id="01d41-131">Alle Aufgaben in dieser Liste müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="01d41-131">All tasks in this list must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; TaskIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; TaskIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TaskIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TaskIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Batch.TaskDependencies.TaskIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="01d41-132">Ruft die Liste der Task-ID-Bereiche, denen von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="01d41-132">Gets the list of task ID ranges that this task depends on.</span></span> <span data-ttu-id="01d41-133">Alle Aufgaben in allen Bereichen müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="01d41-133">All tasks in all ranges must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>