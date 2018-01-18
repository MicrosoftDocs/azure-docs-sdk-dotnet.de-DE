<Type Name="ComputeNodeDeallocationOption" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption">
  <TypeSignature Language="C#" Value="public enum ComputeNodeDeallocationOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeDeallocationOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9f6c7-101">Definiert Werte für ComputeNodeDeallocationOption an.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-101">Defines values for ComputeNodeDeallocationOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Requeue" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6c7-102">Beendet ausgeführte Prozesse von der Aufgabe und requeue Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-102">Terminate running task processes and requeue the tasks.</span></span> <span data-ttu-id="9f6c7-103">Die Tasks werden erneut ausgeführt, wenn ein Knoten verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-103">The tasks will run again when a node is available.</span></span> <span data-ttu-id="9f6c7-104">Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-104">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="RetainedData">
      <MemberSignature Language="C#" Value="RetainedData" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption RetainedData = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.RetainedData" />
      <MemberSignature Language="VB.NET" Value="RetainedData" />
      <MemberSignature Language="F#" Value="RetainedData = 3" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.RetainedData" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6c7-105">Ermöglichen Sie die aktuell ausgeführter Aufgaben abgeschlossen ist, und warten Sie, bis alle Aufgabe Beibehaltungsdauer abläuft.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-105">Allow currently running tasks to complete, then wait for all task data retention periods to expire.</span></span> <span data-ttu-id="9f6c7-106">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="9f6c7-107">Entfernen Sie Knoten, sobald die Aufbewahrungszeiträume aller Tasks abgelaufen sind.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-107">Remove nodes when all task retention periods have expired.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.TaskCompletion" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6c7-108">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-108">Allow currently running tasks to complete.</span></span> <span data-ttu-id="9f6c7-109">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-109">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="9f6c7-110">Entfernen Sie Knoten, sobald alle Aufgaben abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-110">Remove nodes when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption.Terminate" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeallocationOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="9f6c7-111">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-111">Terminate running tasks.</span></span> <span data-ttu-id="9f6c7-112">Mit FailureInfo gibt an, dass sie beendet wurden und nicht erneut ausgeführt werden, werden die Aufgaben abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-112">The tasks will be completed with failureInfo indicating that they were terminated, and will not run again.</span></span> <span data-ttu-id="9f6c7-113">Entfernen Sie Knoten, sobald Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="9f6c7-113">Remove nodes as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>