<Type Name="OnTaskFailure" FullName="Microsoft.Azure.Batch.Common.OnTaskFailure">
  <TypeSignature Language="C#" Value="public enum OnTaskFailure" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OnTaskFailure extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OnTaskFailure" />
  <TypeSignature Language="VB.NET" Value="Public Enum OnTaskFailure" />
  <TypeSignature Language="F#" Value="type OnTaskFailure = " />
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
            <span data-ttu-id="da31f-101">Gibt eine Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.</span><span class="sxs-lookup"><span data-stu-id="da31f-101">Specifies an action the Batch service should take when any task in the job fails.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NoAction">
      <MemberSignature Language="C#" Value="NoAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnTaskFailure NoAction = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnTaskFailure.NoAction" />
      <MemberSignature Language="VB.NET" Value="NoAction" />
      <MemberSignature Language="F#" Value="NoAction = 0" Usage="Microsoft.Azure.Batch.Common.OnTaskFailure.NoAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnTaskFailure</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="da31f-102">Sie unternehmen nichts.</span><span class="sxs-lookup"><span data-stu-id="da31f-102">Do nothing.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PerformExitOptionsJobAction">
      <MemberSignature Language="C#" Value="PerformExitOptionsJobAction" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OnTaskFailure PerformExitOptionsJobAction = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OnTaskFailure.PerformExitOptionsJobAction" />
      <MemberSignature Language="VB.NET" Value="PerformExitOptionsJobAction" />
      <MemberSignature Language="F#" Value="PerformExitOptionsJobAction = 1" Usage="Microsoft.Azure.Batch.Common.OnTaskFailure.PerformExitOptionsJobAction" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OnTaskFailure</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="da31f-103">Führen Sie die Aktion, die die Aufgabe beenden-Bedingung in der Aufgabe zugeordneten <see cref="P:Microsoft.Azure.Batch.CloudTask.ExitConditions" /> Auflistung.</span><span class="sxs-lookup"><span data-stu-id="da31f-103">Take the action associated with the task exit condition in the task's <see cref="P:Microsoft.Azure.Batch.CloudTask.ExitConditions" /> collection.</span></span> <span data-ttu-id="da31f-104">(Dies kann immer noch keine Aktion ausgeführt wird, führen Wenn, was den Task angegeben ist.)</span><span class="sxs-lookup"><span data-stu-id="da31f-104">(This may still result in no action being taken, if that is what the task specifies.)</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>