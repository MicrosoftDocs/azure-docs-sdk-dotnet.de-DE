<Type Name="IWithDataSnapshotFromDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromDisk">
  <TypeSignature Language="C#" Value="public interface IWithDataSnapshotFromDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataSnapshotFromDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataSnapshotFromDisk" />
  <TypeSignature Language="F#" Value="type IWithDataSnapshotFromDisk = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der verwalteten Datenträger Definition ermöglicht verwalteten Datenträger, die Daten auswählen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk managedDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromDisk.WithDataFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataFromDisk (managedDisk As IDisk) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromDisk.WithDataFromDisk managedDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="managedDisk">Eine verwaltete Quelldatenträger.</param>
        <summary>
            Gibt verwaltete Daten Quelldatenträger an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithDataFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromDisk (string managedDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromDisk(string managedDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromDisk.WithDataFromDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataFromDisk (managedDiskId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataFromDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromDisk.WithDataFromDisk managedDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="managedDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="managedDiskId">Quelle verwaltet, Datenträger-Ressourcen-ID.</param>
        <summary>
            Gibt die ID des verwalteten Quelldatenträger für Daten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>