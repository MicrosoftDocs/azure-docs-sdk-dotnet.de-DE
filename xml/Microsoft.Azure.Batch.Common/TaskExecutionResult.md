<Type Name="TaskExecutionResult" FullName="Microsoft.Azure.Batch.Common.TaskExecutionResult">
  <TypeSignature Language="C#" Value="public enum TaskExecutionResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskExecutionResult extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.TaskExecutionResult" />
  <TypeSignature Language="VB.NET" Value="Public Enum TaskExecutionResult" />
  <TypeSignature Language="F#" Value="type TaskExecutionResult = " />
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
            <span data-ttu-id="6523f-101">Das Ergebnis der Taskausführung.</span><span class="sxs-lookup"><span data-stu-id="6523f-101">The result of task execution.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failure">
      <MemberSignature Language="C#" Value="Failure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult Failure = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />
      <MemberSignature Language="VB.NET" Value="Failure" />
      <MemberSignature Language="F#" Value="Failure = 1" Usage="Microsoft.Azure.Batch.Common.TaskExecutionResult.Failure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskExecutionResult</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6523f-102">Während der Verarbeitung des Vorgangs ein Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="6523f-102">There was an error during processing of the task.</span></span> <span data-ttu-id="6523f-103">Der Fehler möglicherweise aufgetreten, bevor der Task Prozess gestartet wurde, während der Prozess der Aufgabe ausgeführt wurde, oder nachdem der Task Prozess beendet.</span><span class="sxs-lookup"><span data-stu-id="6523f-103">The failure may have occurred before the task process was launched, while the task process was executing, or after the task process exited.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.TaskExecutionResult Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.TaskExecutionResult.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.Batch.Common.TaskExecutionResult.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.TaskExecutionResult</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6523f-104">Der Task wurde erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="6523f-104">The task ran successfully.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>