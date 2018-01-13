<Type Name="AddTaskResultStatus" FullName="Microsoft.Azure.Batch.AddTaskResultStatus">
  <TypeSignature Language="C#" Value="public enum AddTaskResultStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed AddTaskResultStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.AddTaskResultStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum AddTaskResultStatus" />
  <TypeSignature Language="F#" Value="type AddTaskResultStatus = " />
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
            Verwendet von <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionResultHandler" /> zum Klassifizieren einer <see cref="T:Microsoft.Azure.Batch.AddTaskResult" /> als erfolgreich oder erfordern eine Wiederholung.
            </summary>
    <remarks>AddTaskResultStatus wird nicht verwendet, um einen Fehler ohne wiederholungsmöglichkeit des. sollte ein Ergebnis Handler auslösen <see cref="T:Microsoft.Azure.Batch.AddTaskCollectionTerminatedException" /> für diesen.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Retry">
      <MemberSignature Language="C#" Value="Retry" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.AddTaskResultStatus Retry = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.AddTaskResultStatus.Retry" />
      <MemberSignature Language="VB.NET" Value="Retry" />
      <MemberSignature Language="F#" Value="Retry = 1" Usage="Microsoft.Azure.Batch.AddTaskResultStatus.Retry" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Klassifiziert das Ergebnis ist, dass eine Wiederholung erfordert.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Success">
      <MemberSignature Language="C#" Value="Success" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.AddTaskResultStatus Success = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.AddTaskResultStatus.Success" />
      <MemberSignature Language="VB.NET" Value="Success" />
      <MemberSignature Language="F#" Value="Success = 0" Usage="Microsoft.Azure.Batch.AddTaskResultStatus.Success" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AddTaskResultStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Klassifiziert das Ergebnis als Erfolg.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>