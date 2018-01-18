<Type Name="ComputeNodeReimageOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeReimageOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeReimageOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeReimageOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeReimageOption = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="94746-101">Gibt an, wann die Serverknoten reimaging durchführen und was mit den derzeit ausgeführten Tasks geschehen.</span><span class="sxs-lookup"><span data-stu-id="94746-101">Specifies when to reimage the compute node and what to do with currently running tasks.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="94746-102">Beenden Sie derzeit ausgeführte Tasks, und sie requeue.</span><span class="sxs-lookup"><span data-stu-id="94746-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="94746-103">Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="94746-103">The tasks will run again when the job is enabled.</span></span> <span data-ttu-id="94746-104">Stellen Sie Serverknoten als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="94746-104">Reimage the compute node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="94746-105">Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft.</span><span class="sxs-lookup"><span data-stu-id="94746-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="94746-106">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="94746-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="94746-107">Ein reimaging ausführen Sie den Compute-Knoten, wenn die Aufbewahrungsdauer für alle Tasks abgelaufen sind.</span><span class="sxs-lookup"><span data-stu-id="94746-107">Reimage the compute node when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="94746-108">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="94746-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="94746-109">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="94746-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="94746-110">Ein reimaging ausführen Sie den Computeknoten, wenn alle Aufgaben abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="94746-110">Reimage the compute node when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeReimageOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeReimageOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="94746-111">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="94746-111">Terminate running tasks.</span></span> <span data-ttu-id="94746-112">Die Tasks werden nicht erneut ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="94746-112">The tasks will not run again.</span></span> <span data-ttu-id="94746-113">Stellen Sie Serverknoten als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="94746-113">Reimage the compute node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>