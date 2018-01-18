<Type Name="OnAllTasksComplete" FullName="Microsoft.Azure.Batch.Common.OnAllTasksComplete">
  <TypeSignature Language="C#" Value="public enum OnAllTasksComplete" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OnAllTasksComplete extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OnAllTasksComplete" />
  <TypeSignature Language="VB.NET" Value="Public Enum OnAllTasksComplete" />
  <TypeSignature Language="F#" Value="type OnAllTasksComplete = " />
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
            <span data-ttu-id="fcf1b-101">Gibt eine Aktion, die der Batch-Dienst ausführen sollten, wenn alle Aufgaben im Auftrag in den Zustand abgeschlossen sind.</span><span class="sxs-lookup"><span data-stu-id="fcf1b-101">Specifies an action the Batch service should take when all tasks in the job are in the completed state.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoAction">
      <MemberSignature Language="C#" Value="NoAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete NoAction = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnAllTasksComplete.NoAction" />
      <MemberSignature Language="VB.NET" Value="NoAction" />
      <MemberSignature Language="F#" Value="NoAction = 0" Usage="Microsoft.Azure.Batch.Common.OnAllTasksComplete.NoAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnAllTasksComplete</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcf1b-102">Sie unternehmen nichts.</span><span class="sxs-lookup"><span data-stu-id="fcf1b-102">Do nothing.</span></span> <span data-ttu-id="fcf1b-103">Der Auftrag bleibt aktiv, es sei denn, beendet oder anderweitig deaktiviert.</span><span class="sxs-lookup"><span data-stu-id="fcf1b-103">The job remains active unless terminated or disabled by some other means.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TerminateJob">
      <MemberSignature Language="C#" Value="TerminateJob" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnAllTasksComplete TerminateJob = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnAllTasksComplete.TerminateJob" />
      <MemberSignature Language="VB.NET" Value="TerminateJob" />
      <MemberSignature Language="F#" Value="TerminateJob = 1" Usage="Microsoft.Azure.Batch.Common.OnAllTasksComplete.TerminateJob" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnAllTasksComplete</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="fcf1b-104">Beenden Sie den Auftrag.</span><span class="sxs-lookup"><span data-stu-id="fcf1b-104">Terminate the job.</span></span> <span data-ttu-id="fcf1b-105">Des Auftrags <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" /> auf "AllTasksComplete" festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="fcf1b-105">The job's <see cref="P:Microsoft.Azure.Batch.JobExecutionInformation.TerminateReason" /> is set to "AllTasksComplete".</span></span> 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>