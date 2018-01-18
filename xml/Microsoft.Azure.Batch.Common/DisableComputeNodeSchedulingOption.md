<Type Name="DisableComputeNodeSchedulingOption" FullName="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption">
  <TypeSignature Language="C#" Value="public enum DisableComputeNodeSchedulingOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DisableComputeNodeSchedulingOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption" />
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
  <Docs>
    <summary>
            <span data-ttu-id="26612-101">Gibt an, was mit den derzeit ausgeführten Aufgaben werden beim Deaktivieren der aufgabenplanung auf dem Computeknoten.</span><span class="sxs-lookup"><span data-stu-id="26612-101">Specifies what to do with currently running tasks when disable task scheduling on the compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Requeue">
      <MemberSignature Language="C#" Value="Requeue" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption Requeue = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />
      <MemberSignature Language="VB.NET" Value="Requeue" />
      <MemberSignature Language="F#" Value="Requeue = 0" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Requeue" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="26612-102">Beenden Sie derzeit ausgeführte Tasks, und sie requeue.</span><span class="sxs-lookup"><span data-stu-id="26612-102">Terminate running tasks and requeue them.</span></span> <span data-ttu-id="26612-103">Die Tasks werden erneut ausgeführt, sobald der Auftrag aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="26612-103">The tasks will run again when the job is enabled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="26612-104">Ermöglichen Sie die derzeit ausgeführten Tasks ab.</span><span class="sxs-lookup"><span data-stu-id="26612-104">Allow currently running tasks to complete.</span></span> <span data-ttu-id="26612-105">Planen Sie beim Warten keine neuen Tasks.</span><span class="sxs-lookup"><span data-stu-id="26612-105">Schedule no new tasks while waiting.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="Terminate" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption Terminate = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Terminate" />
      <MemberSignature Language="VB.NET" Value="Terminate" />
      <MemberSignature Language="F#" Value="Terminate = 1" Usage="Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption.Terminate" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DisableComputeNodeSchedulingOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="26612-106">Ausführen von Aufgaben zu beenden.</span><span class="sxs-lookup"><span data-stu-id="26612-106">Terminate running tasks.</span></span> <span data-ttu-id="26612-107">Die Tasks werden nicht erneut ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="26612-107">The tasks will not run again.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>