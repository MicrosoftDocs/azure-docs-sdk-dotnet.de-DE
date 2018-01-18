<Type Name="TaskExecutionResult" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult">
  <TypeSignature Language="C#" Value="public enum TaskExecutionResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed TaskExecutionResult extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult" />
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
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="2af7a-101">Definiert Werte für TaskExecutionResult an.</span><span class="sxs-lookup"><span data-stu-id="2af7a-101">Defines values for TaskExecutionResult.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failure">
      <MemberSignature Language="C#" Value="Failure" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult Failure = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult.Failure" />
      <MemberSignature Language="VB.NET" Value="Failure" />
      <MemberSignature Language="F#" Value="Failure = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult.Failure" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="failure")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af7a-102">Während der Verarbeitung des Vorgangs ein Fehler aufgetreten ist.</span><span class="sxs-lookup"><span data-stu-id="2af7a-102">There was an error during processing of the task.</span></span> <span data-ttu-id="2af7a-103">Der Fehler möglicherweise aufgetreten, bevor der Task Prozess gestartet wurde, während der Prozess der Aufgabe ausgeführt wurde, oder nachdem der Task Prozess beendet.</span><span class="sxs-lookup"><span data-stu-id="2af7a-103">The failure may have occurred before the task process was launched, while the task process was executing, or after the task process exited.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="success")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.TaskExecutionResult</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="2af7a-104">Der Task wurde erfolgreich ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="2af7a-104">The task ran successfully.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>