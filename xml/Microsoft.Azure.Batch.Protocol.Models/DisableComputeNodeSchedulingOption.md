<Type Name="DisableComputeNodeSchedulingOption" FullName="Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption">
  <TypeSignature Language="C#" Value="public enum DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableComputeNodeSchedulingOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="F#" Value="type DisableComputeNodeSchedulingOption = " />
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
            <span data-ttu-id="797c7-101">Definiert Werte für DisableComputeNodeSchedulingOption an.</span><span class="sxs-lookup"><span data-stu-id="797c7-101">Defines values for DisableComputeNodeSchedulingOption.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.Requeue" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="797c7-102">Beendet ausgeführte Prozesse von der Aufgabe und requeue Aufgaben.</span><span class="sxs-lookup"><span data-stu-id="797c7-102">Terminate running task processes and requeue the tasks.</span></span> <span data-ttu-id="797c7-103">Die Aufgaben möglicherweise erneut ausführen, für andere Serverknoten oder beim aufgabenplanung auf diesem Knoten erneut aktiviert werden wird.</span><span class="sxs-lookup"><span data-stu-id="797c7-103">The tasks may run again on other compute nodes, or when task scheduling is re-enabled on this node.</span></span> <span data-ttu-id="797c7-104">Geben Sie die offline-Status, als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="797c7-104">Enter offline state as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.TaskCompletion" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="797c7-105">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="797c7-105">Allow currently running tasks to complete.</span></span> <span data-ttu-id="797c7-106">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="797c7-106">Schedule no new tasks while waiting.</span></span> <span data-ttu-id="797c7-107">Geben Sie die offline-Status, wenn alle Aufgaben abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="797c7-107">Enter offline state when all tasks have completed.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption.Terminate" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="797c7-108">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="797c7-108">Terminate running tasks.</span></span> <span data-ttu-id="797c7-109">Mit FailureInfo gibt an, dass sie beendet wurden und nicht erneut ausgeführt werden, werden die Aufgaben abgeschlossen werden.</span><span class="sxs-lookup"><span data-stu-id="797c7-109">The tasks will be completed with failureInfo indicating that they were terminated, and will not run again.</span></span> <span data-ttu-id="797c7-110">Geben Sie die offline-Status, als Tasks abgeschlossen wurden.</span><span class="sxs-lookup"><span data-stu-id="797c7-110">Enter offline state as soon as tasks have been terminated.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>