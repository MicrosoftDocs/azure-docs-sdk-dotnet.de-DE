<Type Name="ComputeNodeDeallocationOption" FullName="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeDeallocationOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="F#" Value="type ComputeNodeDeallocationOption = " />
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
            <span data-ttu-id="539fd-101">Gibt an, wie behandelt Aufgaben bereits ausgeführt wird und wenn ressourcenaufwändig Knoten möglicherweise aus dem Pool entfernt werden, wenn Verkleinerung des Pools.</span><span class="sxs-lookup"><span data-stu-id="539fd-101">Specifies how to handle tasks already running, and when the nodes running them may be removed from the pool, if the pool size is decreasing.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="539fd-102">Beenden Sie derzeit ausgeführte Tasks, und sie requeue.</span><span class="sxs-lookup"><span data-stu-id="539fd-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="539fd-103">Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="539fd-103">The tasks will run again when the job is enabled.</span></span> <span data-ttu-id="539fd-104">Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="539fd-104">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="539fd-105">Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft.</span><span class="sxs-lookup"><span data-stu-id="539fd-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="539fd-106">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="539fd-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="539fd-107">Entfernen Sie Knoten, sobald die Aufbewahrungszeiträume aller Tasks abgelaufen sind.</span><span class="sxs-lookup"><span data-stu-id="539fd-107">Remove nodes when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="539fd-108">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="539fd-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="539fd-109">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="539fd-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="539fd-110">Entfernen Sie Knoten, sobald alle Aufgaben abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="539fd-110">Remove nodes when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="539fd-111">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="539fd-111">Terminate running tasks.</span></span> <span data-ttu-id="539fd-112">Die Tasks werden nicht erneut ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="539fd-112">The tasks will not run again.</span></span> <span data-ttu-id="539fd-113">Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="539fd-113">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>