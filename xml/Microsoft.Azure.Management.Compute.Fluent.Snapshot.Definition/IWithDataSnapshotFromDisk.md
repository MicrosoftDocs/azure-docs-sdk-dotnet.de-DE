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
            <span data-ttu-id="3adb7-101">Die Stufe der verwalteten Datenträger Definition ermöglicht verwalteten Datenträger, die Daten auswählen.</span><span class="sxs-lookup"><span data-stu-id="3adb7-101">The stage of the managed disk definition allowing to choose managed disk containing data.</span></span>
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
        <param name="managedDisk"><span data-ttu-id="3adb7-102">Eine verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="3adb7-102">A source managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="3adb7-103">Gibt verwaltete Daten Quelldatenträger an.</span><span class="sxs-lookup"><span data-stu-id="3adb7-103">Specifies the source data managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3adb7-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3adb7-104">The next stage of the definition.</span></span></return>
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
        <param name="managedDiskId"><span data-ttu-id="3adb7-105">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="3adb7-105">Source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="3adb7-106">Gibt die ID des verwalteten Quelldatenträger für Daten.</span><span class="sxs-lookup"><span data-stu-id="3adb7-106">Specifies the ID of source data managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3adb7-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3adb7-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>