<Type Name="ComputeNodeFillType" FullName="Microsoft.Azure.Batch.Common.ComputeNodeFillType">
  <TypeSignature Language="C#" Value="public enum ComputeNodeFillType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ComputeNodeFillType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ComputeNodeFillType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ComputeNodeFillType" />
  <TypeSignature Language="F#" Value="type ComputeNodeFillType = " />
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
            Gibt an, wie Aufgaben auf Serverknoten verteilt werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Pack">
      <MemberSignature Language="C#" Value="Pack" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeFillType Pack = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeFillType.Pack" />
      <MemberSignature Language="VB.NET" Value="Pack" />
      <MemberSignature Language="F#" Value="Pack = 1" Usage="Microsoft.Azure.Batch.Common.ComputeNodeFillType.Pack" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Wie viele Aufgaben wie möglich (MaxTasksPerNode) sollte auf jeden Knoten im Pool zugewiesen werden, bevor alle Aufgaben auf den nächsten Knoten im Pool zugewiesen sind.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Spread">
      <MemberSignature Language="C#" Value="Spread" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ComputeNodeFillType Spread = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ComputeNodeFillType.Spread" />
      <MemberSignature Language="VB.NET" Value="Spread" />
      <MemberSignature Language="F#" Value="Spread = 0" Usage="Microsoft.Azure.Batch.Common.ComputeNodeFillType.Spread" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ComputeNodeFillType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Aufgaben sollten gleichmäßig allen Knoten im Pool zugewiesen werden.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>