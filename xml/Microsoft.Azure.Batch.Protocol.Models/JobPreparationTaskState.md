<Type Name="JobPreparationTaskState" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState">
  <TypeSignature Language="C#" Value="public enum JobPreparationTaskState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed JobPreparationTaskState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState" />
  <TypeSignature Language="VB.NET" Value="Public Enum JobPreparationTaskState" />
  <TypeSignature Language="F#" Value="type JobPreparationTaskState = " />
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
            <span data-ttu-id="0f1be-101">Definiert Werte für JobPreparationTaskState an.</span><span class="sxs-lookup"><span data-stu-id="0f1be-101">Defines values for JobPreparationTaskState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Completed">
      <MemberSignature Language="C#" Value="Completed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState Completed = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState.Completed" />
      <MemberSignature Language="VB.NET" Value="Completed" />
      <MemberSignature Language="F#" Value="Completed = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState.Completed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="completed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f1be-102">Der Task wurde mit Exitcode 0 (null) beendet oder der Task Wiederholungslimit verbraucht hat, oder der Batch-Dienst konnte die Aufgabe aufgrund Vorbereitung Taskfehler (z. B. Fehler beim Herunterladen von Ressourcen-Datei) zu starten.</span><span class="sxs-lookup"><span data-stu-id="0f1be-102">The task has exited with exit code 0, or the task has exhausted its retry limit, or the Batch service was unable to start the task due to task preparation errors (such as resource file download failures).</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Running">
      <MemberSignature Language="C#" Value="Running" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState Running = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState.Running" />
      <MemberSignature Language="VB.NET" Value="Running" />
      <MemberSignature Language="F#" Value="Running = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState.Running" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="running")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobPreparationTaskState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="0f1be-103">Der Task wird gerade ausgeführt (einschließlich Wiederholung).</span><span class="sxs-lookup"><span data-stu-id="0f1be-103">The task is currently running (including retrying).</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>