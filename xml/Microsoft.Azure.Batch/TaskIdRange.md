<Type Name="TaskIdRange" FullName="Microsoft.Azure.Batch.TaskIdRange">
  <TypeSignature Language="C#" Value="public class TaskIdRange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskIdRange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskIdRange" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskIdRange" />
  <TypeSignature Language="F#" Value="type TaskIdRange = class&#xA;    interface ITransportObjectProvider&lt;TaskIdRange&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="4b95c-101">Einen Bereich von Aufgaben-Ids, die eine <see cref="T:Microsoft.Azure.Batch.CloudTask" /> abhängig.</span><span class="sxs-lookup"><span data-stu-id="4b95c-101">A range of task ids that a <see cref="T:Microsoft.Azure.Batch.CloudTask" /> depends on.</span></span> <span data-ttu-id="4b95c-102">Alle Aufgaben-Ids im Bereich müssen erfolgreich abgeschlossen, bevor der abhängige Task geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="4b95c-102">All tasks with ids in the range must complete successfully before the dependent task can be scheduled.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskIdRange (int start, int end);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskIdRange.#ctor(System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (start As Integer, end As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskIdRange : int * int -&gt; Microsoft.Azure.Batch.TaskIdRange" Usage="new Microsoft.Azure.Batch.TaskIdRange (start, end)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="4b95c-103">Der erste Task-Id im Bereich.</span><span class="sxs-lookup"><span data-stu-id="4b95c-103">The first task id in the range.</span></span></param>
        <param name="end"><span data-ttu-id="4b95c-104">Die letzte Task-Id im Bereich.</span><span class="sxs-lookup"><span data-stu-id="4b95c-104">The last task id in the range.</span></span></param>
        <summary>
            <span data-ttu-id="4b95c-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.TaskIdRange" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="4b95c-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskIdRange" /> class.</span></span>
            </summary>
        <remarks>
            <span data-ttu-id="4b95c-106">Bereiche sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="4b95c-106">Ranges are inclusive.</span></span> <span data-ttu-id="4b95c-107">Z. B. wenn eine Aufgabe sich nach einem Bereich mit 8 Start und Ende 10 richtet dann tasks "8", muss "9" und "10" abschließen, bevor die Aufgabe geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="4b95c-107">For example, if a task depends on a range with Start 8 and End 10, then tasks "8", "9" and "10" must complete before the task can be scheduled.</span></span>
            </remarks>
        <exception cref="T:System.ArgumentOutOfRangeException">
          <span data-ttu-id="4b95c-108"><paramref name="start" /> oder <paramref name="end" /> ist ein negativer Wert.</span><span class="sxs-lookup"><span data-stu-id="4b95c-108"><paramref name="start" /> or <paramref name="end" /> is negative.</span></span></exception>
        <exception cref="T:System.ArgumentException">
          <span data-ttu-id="4b95c-109"><paramref name="end" /> ist kleiner als <paramref name="start" />.</span><span class="sxs-lookup"><span data-stu-id="4b95c-109"><paramref name="end" /> is less than <paramref name="start" />.</span></span></exception>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.TaskIdRange.End" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b95c-110">Ruft den letzten Task-Id in den Bereich ab.</span><span class="sxs-lookup"><span data-stu-id="4b95c-110">Gets the last task id in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4b95c-111">Bereiche sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="4b95c-111">Ranges are inclusive.</span></span> <span data-ttu-id="4b95c-112">Z. B. wenn ein Task auf einen Bereich mit der End-12 abhängig ist, muss dann Aufgabe "12" abschließen, bevor die Aufgabe geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="4b95c-112">For example, if a task depends on a range with End 12, then task "12" must complete before the task can be scheduled.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.TaskIdRange.Start" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4b95c-113">Ruft den ersten Task-Id in den Bereich ab.</span><span class="sxs-lookup"><span data-stu-id="4b95c-113">Gets the first task id in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="4b95c-114">Bereiche sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="4b95c-114">Ranges are inclusive.</span></span> <span data-ttu-id="4b95c-115">Z. B. wenn ein Task auf einen Bereich mit 8 Starten abhängig ist, muss dann Aufgabe "8" abschließen, bevor die Aufgabe geplant werden kann.</span><span class="sxs-lookup"><span data-stu-id="4b95c-115">For example, if a task depends on a range with Start 8, then task "8" must complete before the task can be scheduled.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>