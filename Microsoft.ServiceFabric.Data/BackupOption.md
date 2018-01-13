<Type Name="BackupOption" FullName="Microsoft.ServiceFabric.Data.BackupOption">
  <TypeSignature Language="C#" Value="public enum BackupOption" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed BackupOption extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.BackupOption" />
  <TypeSignature Language="VB.NET" Value="Public Enum BackupOption" />
  <TypeSignature Language="F#" Value="type BackupOption = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="53f89-101">Gibt die Art der Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="53f89-101">Indicates the kind of the backup.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Full">
      <MemberSignature Language="C#" Value="Full" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.BackupOption Full = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupOption.Full" />
      <MemberSignature Language="VB.NET" Value="Full" />
      <MemberSignature Language="F#" Value="Full = 0" Usage="Microsoft.ServiceFabric.Data.BackupOption.Full" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="53f89-102">Eine vollständige Sicherung alle Zustände, die von verwaltet die <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span><span class="sxs-lookup"><span data-stu-id="53f89-102">A full backup of all state managed by the <see cref="T:Microsoft.ServiceFabric.Data.IReliableStateManager" />.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Incremental">
      <MemberSignature Language="C#" Value="Incremental" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Data.BackupOption Incremental = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Data.BackupOption.Incremental" />
      <MemberSignature Language="VB.NET" Value="Incremental" />
      <MemberSignature Language="F#" Value="Incremental = 1" Usage="Microsoft.ServiceFabric.Data.BackupOption.Incremental" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.BackupOption</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="53f89-103">Inkrementelle Sicherung des Replikats.</span><span class="sxs-lookup"><span data-stu-id="53f89-103">Incremental backup of the replica.</span></span> <span data-ttu-id="53f89-104">d. h. nur die Änderungen seit die letzten vollständige oder inkrementelle Sicherung gesichert werden.</span><span class="sxs-lookup"><span data-stu-id="53f89-104">i.e. only the changes since the last full or incremental backup will be backed up.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>