<Type Name="DependencyAction" FullName="Microsoft.Azure.Batch.Common.DependencyAction">
  <TypeSignature Language="C#" Value="public enum DependencyAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed DependencyAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.DependencyAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum DependencyAction" />
  <TypeSignature Language="F#" Value="type DependencyAction = " />
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
            Eine Aktion, die der Batch-Dienst für Aufgaben ausgeführt werden soll, die abhängig von der Aufgabe, die die Aktion angibt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Block">
      <MemberSignature Language="C#" Value="Block" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DependencyAction Block = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DependencyAction.Block" />
      <MemberSignature Language="VB.NET" Value="Block" />
      <MemberSignature Language="F#" Value="Block = 1" Usage="Microsoft.Azure.Batch.Common.DependencyAction.Block" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DependencyAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Die Abhängigkeit wird nicht erfüllt. Abhängige Aufgaben werden nicht berechtigt, die auszuführen. 
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Satisfy">
      <MemberSignature Language="C#" Value="Satisfy" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.DependencyAction Satisfy = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.DependencyAction.Satisfy" />
      <MemberSignature Language="VB.NET" Value="Satisfy" />
      <MemberSignature Language="F#" Value="Satisfy = 0" Usage="Microsoft.Azure.Batch.Common.DependencyAction.Satisfy" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.DependencyAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Die Abhängigkeit erfüllt wird. Nachdem alle Abhängigkeiten für eine abhängige Aufgabe erfüllt sind, kann der abhängige Task ausgeführt. 
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>