<Type Name="OutputFileUploadCondition" FullName="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition">
  <TypeSignature Language="C#" Value="public enum OutputFileUploadCondition" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed OutputFileUploadCondition extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="d0f69-101">Definiert Werte für OutputFileUploadCondition an.</span><span class="sxs-lookup"><span data-stu-id="d0f69-101">Defines values for OutputFileUploadCondition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TaskCompletion">
      <MemberSignature Language="C#" Value="TaskCompletion" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition TaskCompletion = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskCompletion" />
      <MemberSignature Language="VB.NET" Value="TaskCompletion" />
      <MemberSignature Language="F#" Value="TaskCompletion = 2" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskCompletion" />
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
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0f69-102">Hochladen der Dateien an, nachdem der Task Prozess beendet wird, unabhängig davon, was der Exitcode war.</span><span class="sxs-lookup"><span data-stu-id="d0f69-102">Upload the file(s) after the task process exits, no matter what the exit code was.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskFailure">
      <MemberSignature Language="C#" Value="TaskFailure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition TaskFailure = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskFailure" />
      <MemberSignature Language="VB.NET" Value="TaskFailure" />
      <MemberSignature Language="F#" Value="TaskFailure = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskFailure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="taskfailure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0f69-103">Hochladen Sie die Dateien, nur, nachdem der Task-Prozess mit einem Exitcode ungleich Null beendet wird.</span><span class="sxs-lookup"><span data-stu-id="d0f69-103">Upload the file(s) only after the task process exits with a nonzero exit code.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TaskSuccess">
      <MemberSignature Language="C#" Value="TaskSuccess" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition TaskSuccess = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskSuccess" />
      <MemberSignature Language="VB.NET" Value="TaskSuccess" />
      <MemberSignature Language="F#" Value="TaskSuccess = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition.TaskSuccess" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="tasksuccess")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.OutputFileUploadCondition</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="d0f69-104">Hochladen der Dateien an, nur, nachdem der Task Prozess mit dem Exitcode 0 beendet wird.</span><span class="sxs-lookup"><span data-stu-id="d0f69-104">Upload the file(s) only after the task process exits with an exit code of 0.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>