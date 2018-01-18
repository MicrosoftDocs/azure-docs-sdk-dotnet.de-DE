<Type Name="ComputeNodeReimageOption" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeReimageOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeReimageOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="131e3-101">Definiert Werte für ComputeNodeReimageOption an.</span><span class="sxs-lookup"><span data-stu-id="131e3-101">Defines values for ComputeNodeReimageOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="requeue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="131e3-102">Beendet ausgeführte Prozesse von der Aufgabe und requeue Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="131e3-102">Terminate running task processes and requeue the tasks.</span></span> <span data-ttu-id="131e3-103">Die Tasks werden erneut ausgeführt, wenn ein Knoten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="131e3-103">The tasks will run again when a node is available.</span></span> <span data-ttu-id="131e3-104">Stellen Sie den Knoten als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="131e3-104">Reimage the node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.RetainedData" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="retaineddata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="131e3-105">Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft.</span><span class="sxs-lookup"><span data-stu-id="131e3-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="131e3-106">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="131e3-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="131e3-107">Ein reimaging Ausführen des Knotens, wenn die Aufbewahrungsdauer für alle Tasks abgelaufen sind.</span><span class="sxs-lookup"><span data-stu-id="131e3-107">Reimage the node when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="taskcompletion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="131e3-108">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="131e3-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="131e3-109">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="131e3-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="131e3-110">Stellen Sie den Knoten aus, wenn alle Aufgaben abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="131e3-110">Reimage the node when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="terminate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="131e3-111">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="131e3-111">Terminate running tasks.</span></span> <span data-ttu-id="131e3-112">Mit FailureInfo gibt an, dass sie beendet wurden und nicht erneut ausgeführt werden, werden die Aufgaben abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="131e3-112">The tasks will be completed with failureInfo indicating that they were terminated, and will not run again.</span></span> <span data-ttu-id="131e3-113">Stellen Sie den Knoten als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="131e3-113">Reimage the node as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>