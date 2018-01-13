<Type Name="MigrationOperation" FullName="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation">
  <TypeSignature Language="C#" Value="public enum MigrationOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed MigrationOperation extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation" />
  <TypeSignature Language="VB.NET" Value="Public Enum MigrationOperation" />
  <TypeSignature Language="F#" Value="type MigrationOperation = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            Migration Vorgang stellt, die verschiedene für eine importierte volumecontainer zulässiges Vorgang bestätigen
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Commit">
      <MemberSignature Language="C#" Value="Commit" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Commit = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Commit" />
      <MemberSignature Language="VB.NET" Value="Commit" />
      <MemberSignature Language="F#" Value="Commit = 1" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Commit" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            Commit verknüpft den volumecontainer auf dem Zielgerät dauerhaft
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            Stellt einen Vorgang kein dar
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Rollback">
      <MemberSignature Language="C#" Value="Rollback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation Rollback = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Rollback" />
      <MemberSignature Language="VB.NET" Value="Rollback" />
      <MemberSignature Language="F#" Value="Rollback = 2" Usage="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation.Rollback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationOperation</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            Rollback bereinigt die Änderungen, die durch die Migration abgeschlossen und die Volume-Container in einen Zustand vor der Migration zurückgesetzt
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>