<Type Name="TaskDependencies" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies">
  <TypeSignature Language="C#" Value="public class TaskDependencies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskDependencies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskDependencies" />
  <TypeSignature Language="F#" Value="type TaskDependencies = class" />
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
            <span data-ttu-id="e13a7-101">Gibt alle Abhängigkeiten von einer Aufgabe an.</span><span class="sxs-lookup"><span data-stu-id="e13a7-101">Specifies any dependencies of a task.</span></span> <span data-ttu-id="e13a7-102">Jede Aufgabe, die explizit angegeben wird oder innerhalb einer Abhängigkeit Bereich abgeschlossen werden muss, bevor der abhängige Task geplant wird.</span><span class="sxs-lookup"><span data-stu-id="e13a7-102">Any task that is explicitly specified or within a dependency range must complete before the dependant task will be scheduled.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.#ctor" />
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
            <span data-ttu-id="e13a7-103">Initialisiert eine neue Instanz der Klasse TaskDependencies an.</span><span class="sxs-lookup"><span data-stu-id="e13a7-103">Initializes a new instance of the TaskDependencies class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskDependencies (System.Collections.Generic.IList&lt;string&gt; taskIds = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; taskIdRanges = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; taskIds, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; taskIdRanges) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.#ctor(System.Collections.Generic.IList{System.String},System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.TaskIdRange})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional taskIds As IList(Of String) = null, Optional taskIdRanges As IList(Of TaskIdRange) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskDependencies : System.Collections.Generic.IList&lt;string&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskDependencies" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskDependencies (taskIds, taskIdRanges)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="taskIds" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="taskIdRanges" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt;" />
      </Parameters>
      <Docs>
        <param name="taskIds"><span data-ttu-id="e13a7-104">Die Liste der Aufgaben-IDs, die von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="e13a7-104">The list of task IDs that this task depends on.</span></span> <span data-ttu-id="e13a7-105">Alle Aufgaben in dieser Liste müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="e13a7-105">All tasks in this list must complete successfully before the dependent task can be scheduled.</span></span></param>
        <param name="taskIdRanges"><span data-ttu-id="e13a7-106">Die Liste der Task-ID-Bereiche, denen von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="e13a7-106">The list of task ID ranges that this task depends on.</span></span> <span data-ttu-id="e13a7-107">Alle Aufgaben in allen Bereichen müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="e13a7-107">All tasks in all ranges must complete successfully before the dependent task can be scheduled.</span></span></param>
        <summary>
            <span data-ttu-id="e13a7-108">Initialisiert eine neue Instanz der Klasse TaskDependencies an.</span><span class="sxs-lookup"><span data-stu-id="e13a7-108">Initializes a new instance of the TaskDependencies class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIdRanges">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; TaskIdRanges { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; TaskIdRanges" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIdRanges" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskIdRanges As IList(Of TaskIdRange)" />
      <MemberSignature Language="F#" Value="member this.TaskIdRanges : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIdRanges" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskIdRanges")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.TaskIdRange&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e13a7-109">Ruft ab oder legt die Liste der Task-ID-Bereiche, denen von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="e13a7-109">Gets or sets the list of task ID ranges that this task depends on.</span></span>
            <span data-ttu-id="e13a7-110">Alle Aufgaben in allen Bereichen müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="e13a7-110">All tasks in all ranges must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; TaskIds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; TaskIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIds" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskIds As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.TaskIds : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskDependencies.TaskIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskIds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e13a7-111">Ruft ab oder legt die Liste der Aufgaben-IDs, die von dieser Aufgabe abhängig ist.</span><span class="sxs-lookup"><span data-stu-id="e13a7-111">Gets or sets the list of task IDs that this task depends on.</span></span> <span data-ttu-id="e13a7-112">Alle Aufgaben in dieser Liste müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="e13a7-112">All tasks in this list must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="e13a7-113">Die Auflistung TaskIds ist auf 64000 Zeichen total (d. h. die Gesamtlänge des aller Aufgaben-IDs) beschränkt.</span><span class="sxs-lookup"><span data-stu-id="e13a7-113">The taskIds collection is limited to 64000 characters total (i.e. the combined length of all task IDs).</span></span> <span data-ttu-id="e13a7-114">Wenn die Auflistung TaskIds die maximale Länge überschreitet, schlägt die Aufgabe hinzufügen-Anforderung mit dem Fehlercode TaskDependencyListTooLong fehl.</span><span class="sxs-lookup"><span data-stu-id="e13a7-114">If the taskIds collection exceeds the maximum length, the Add Task request fails with error code TaskDependencyListTooLong.</span></span> <span data-ttu-id="e13a7-115">In diesem Fall erwägen Sie stattdessen mithilfe von Task-ID-Bereiche.</span><span class="sxs-lookup"><span data-stu-id="e13a7-115">In this case consider using task ID ranges instead.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>