<Type Name="ElevationLevel" FullName="Microsoft.Azure.Batch.Common.ElevationLevel">
  <TypeSignature Language="C#" Value="public enum ElevationLevel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ElevationLevel extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Common.ElevationLevel" />
  <TypeSignature Language="VB.NET" Value="Public Enum ElevationLevel" />
  <TypeSignature Language="F#" Value="type ElevationLevel = " />
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
            Die Erhöhung der Rechte Ebene des Benutzerkontos ein, die von der Batch-Dienst verwendet, um eine Aufgabe auszuführen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Admin">
      <MemberSignature Language="C#" Value="Admin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ElevationLevel Admin = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ElevationLevel.Admin" />
      <MemberSignature Language="VB.NET" Value="Admin" />
      <MemberSignature Language="F#" Value="Admin = 1" Usage="Microsoft.Azure.Batch.Common.ElevationLevel.Admin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Der Benutzer verfügt über erhöhte Zugriffsberechtigungen und arbeitet mit vollständigen Administratorberechtigungen.
            </summary>
      </Docs>
    </Member>
    <Member MemberName="NonAdmin">
      <MemberSignature Language="C#" Value="NonAdmin" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Common.ElevationLevel NonAdmin = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />
      <MemberSignature Language="VB.NET" Value="NonAdmin" />
      <MemberSignature Language="F#" Value="NonAdmin = 0" Usage="Microsoft.Azure.Batch.Common.ElevationLevel.NonAdmin" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.ElevationLevel</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Der Benutzer hat die standard-Zugriffsberechtigungen.
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>