<Type Name="TaskCounts" FullName="Microsoft.Azure.Batch.TaskCounts">
  <TypeSignature Language="C#" Value="public class TaskCounts" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskCounts extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskCounts" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskCounts" />
  <TypeSignature Language="F#" Value="type TaskCounts = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="32764-101">Der Task zählt für einen Auftrag.</span><span class="sxs-lookup"><span data-stu-id="32764-101">The task counts for a job.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Active">
      <MemberSignature Language="C#" Value="public int Active { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Active" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Active" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Active As Integer" />
      <MemberSignature Language="F#" Value="member this.Active : int" Usage="Microsoft.Azure.Batch.TaskCounts.Active" />
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
            <span data-ttu-id="32764-102">Ruft die Anzahl der Aufgaben im aktiven Zustand.</span><span class="sxs-lookup"><span data-stu-id="32764-102">Gets the number of tasks in the active state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="public int Completed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Completed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Completed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Completed As Integer" />
      <MemberSignature Language="F#" Value="member this.Completed : int" Usage="Microsoft.Azure.Batch.TaskCounts.Completed" />
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
            <span data-ttu-id="32764-103">Ruft die Anzahl der Aufgaben in den abgeschlossenen Zustand versetzt.</span><span class="sxs-lookup"><span data-stu-id="32764-103">Gets the number of tasks in the completed state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="public int Failed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Failed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Failed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Failed As Integer" />
      <MemberSignature Language="F#" Value="member this.Failed : int" Usage="Microsoft.Azure.Batch.TaskCounts.Failed" />
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
            <span data-ttu-id="32764-104">Ruft die Anzahl der fehlgeschlagenen Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="32764-104">Gets the number of tasks which failed.</span></span> <span data-ttu-id="32764-105">Ein Task fehlschlägt, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Failure" ist.</span><span class="sxs-lookup"><span data-stu-id="32764-105">A task fails if its result (found in the executionInfo property) is 'failure'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="public int Running { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Running" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Running" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Running As Integer" />
      <MemberSignature Language="F#" Value="member this.Running : int" Usage="Microsoft.Azure.Batch.TaskCounts.Running" />
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
            <span data-ttu-id="32764-106">Ruft die Anzahl der Aufgaben in den Zustand ausgeführt werden oder vorbereiten.</span><span class="sxs-lookup"><span data-stu-id="32764-106">Gets the number of tasks in the running or preparing state.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Succeeded">
      <MemberSignature Language="C#" Value="public int Succeeded { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Succeeded" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.Succeeded" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Succeeded As Integer" />
      <MemberSignature Language="F#" Value="member this.Succeeded : int" Usage="Microsoft.Azure.Batch.TaskCounts.Succeeded" />
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
            <span data-ttu-id="32764-107">Ruft die Anzahl der Tasks erfolgreich ab.</span><span class="sxs-lookup"><span data-stu-id="32764-107">Gets the number of tasks which succeeded.</span></span> <span data-ttu-id="32764-108">Eine Aufgabe ist erfolgreich, wenn das Ergebnis (in der Eigenschaft ExecutionInfo gefunden) "Success".</span><span class="sxs-lookup"><span data-stu-id="32764-108">A task succeeds if its result (found in the executionInfo property) is 'success'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.TaskCountValidationStatus ValidationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Batch.Common.TaskCountValidationStatus ValidationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ValidationStatus As TaskCountValidationStatus" />
      <MemberSignature Language="F#" Value="member this.ValidationStatus : Microsoft.Azure.Batch.Common.TaskCountValidationStatus" Usage="Microsoft.Azure.Batch.TaskCounts.ValidationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskCountValidationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="32764-109">Ruft ab, ob die Aufgabe einfach überprüft wurden.</span><span class="sxs-lookup"><span data-stu-id="32764-109">Gets whether the task counts have been validated.</span></span> <span data-ttu-id="32764-110">Wenn die <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> nicht überprüfte, ist, und klicken Sie dann der Batch-Dienst nicht zum Überprüfen des Status für die Aufgabenzustände zählt wurde, wie Sie in der Liste Aufgaben-API können.</span><span class="sxs-lookup"><span data-stu-id="32764-110">If the <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> is unvalidated, then the Batch service has not been able to check state counts against the task states as reported in the List Tasks API.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="32764-111">Die <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> möglicherweise nicht überprüfte sein, wenn der Auftrag über 200.000 Aufgaben enthält.</span><span class="sxs-lookup"><span data-stu-id="32764-111">The <see cref="P:Microsoft.Azure.Batch.TaskCounts.ValidationStatus" /> may be unvalidated if the job contains more than 200,000 tasks.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>