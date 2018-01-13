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
            Gibt eine Aktion, die der Batch-Dienst ausführen sollten, wenn jede Aufgabe im Auftrag ein Fehler auftritt.
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
            Sie unternehmen nichts.
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
            Führen Sie die Aktion, die die Aufgabe beenden-Bedingung in der Aufgabe zugeordneten <see cref="P:Microsoft.Azure.Batch.CloudTask.ExitConditions" /> Auflistung. (Dies kann immer noch keine Aktion ausgeführt wird, führen Wenn, was den Task angegeben ist.)
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>