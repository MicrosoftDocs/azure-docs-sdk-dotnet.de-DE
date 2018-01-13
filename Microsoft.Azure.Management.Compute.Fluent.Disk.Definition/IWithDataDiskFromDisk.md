<Type Name="IWithDataDiskFromDisk" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk">
  <TypeSignature Language="C#" Value="public interface IWithDataDiskFromDisk" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataDiskFromDisk" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataDiskFromDisk" />
  <TypeSignature Language="F#" Value="type IWithDataDiskFromDisk = interface" />
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
    <Member MemberName="FromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk managedDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk managedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk.FromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromDisk (managedDisk As IDisk) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member FromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithDataDiskFromDisk.FromDisk managedDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="managedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="managedDisk">Verwaltete Quelldatenträger.</param>
        <summary>
            Gibt verwaltete Daten Quelldatenträger an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="FromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromDisk (string managedDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize FromDisk(string managedDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk.FromDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromDisk (managedDiskId As String) As IWithCreateAndSize" />
      <MemberSignature Language="F#" Value="abstract member FromDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize" Usage="iWithDataDiskFromDisk.FromDisk managedDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreateAndSize</ReturnType>
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