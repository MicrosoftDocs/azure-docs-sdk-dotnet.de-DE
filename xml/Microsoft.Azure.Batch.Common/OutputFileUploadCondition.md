<Type Name="OutputFileUploadCondition" FullName="Microsoft.Azure.Batch.Common.OutputFileUploadCondition">
  <TypeSignature Language="C#" Value="public enum OutputFileUploadCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OutputFileUploadCondition extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.OutputFileUploadCondition" />
  <TypeSignature Language="VB.NET" Value="Public Enum OutputFileUploadCondition" />
  <TypeSignature Language="F#" Value="type OutputFileUploadCondition = " />
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
            <span data-ttu-id="60bef-101">Die Bedingungen, unter denen eine Aufgabe Datei(en) Ausgabe des, hochgeladen werden soll.</span><span class="sxs-lookup"><span data-stu-id="60bef-101">The conditions under which a task's output file(s) should be uploaded.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OutputFileUploadCondition TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskCompletion" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="60bef-102">Hochladen der Dateien an, nachdem der Task Prozess beendet wird, unabhängig davon, was der Exitcode war.</span><span class="sxs-lookup"><span data-stu-id="60bef-102">Upload the file(s) after the task process exits, no matter what the exit code was.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskFailure">
      <MemberSignature Language="C#" Value="TaskFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OutputFileUploadCondition TaskFailure = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskFailure" />
      <MemberSignature Language="VB.NET" Value="TaskFailure" />
      <MemberSignature Language="F#" Value="TaskFailure = 1" Usage="Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="60bef-103">Hochladen Sie die Dateien, nur, nachdem der Task-Prozess mit einem Exitcode ungleich Null beendet wird.</span><span class="sxs-lookup"><span data-stu-id="60bef-103">Upload the file(s) only after the task process exits with a nonzero exit code.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskSuccess">
      <MemberSignature Language="C#" Value="TaskSuccess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.OutputFileUploadCondition TaskSuccess = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskSuccess" />
      <MemberSignature Language="VB.NET" Value="TaskSuccess" />
      <MemberSignature Language="F#" Value="TaskSuccess = 0" Usage="Microsoft.Azure.Batch.Common.OutputFileUploadCondition.TaskSuccess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="60bef-104">Hochladen der Dateien an, nur, nachdem der Task Prozess mit dem Exitcode 0 beendet wird.</span><span class="sxs-lookup"><span data-stu-id="60bef-104">Upload the file(s) only after the task process exits with an exit code of 0.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>