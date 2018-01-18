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
            <span data-ttu-id="be8bf-101">Die Stufe der verwalteten Datenträger Definition ermöglicht verwalteten Datenträger, die Daten auswählen.</span><span class="sxs-lookup"><span data-stu-id="be8bf-101">The stage of the managed disk definition allowing to choose managed disk containing data.</span></span>
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
        <param name="managedDisk"><span data-ttu-id="be8bf-102">Verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="be8bf-102">Source managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="be8bf-103">Gibt verwaltete Daten Quelldatenträger an.</span><span class="sxs-lookup"><span data-stu-id="be8bf-103">Specifies the source data managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="be8bf-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="be8bf-104">The next stage of the definition.</span></span></return>
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
        <param name="managedDiskId"><span data-ttu-id="be8bf-105">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="be8bf-105">Source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="be8bf-106">Gibt die ID des verwalteten Quelldatenträger für Daten.</span><span class="sxs-lookup"><span data-stu-id="be8bf-106">Specifies the ID of source data managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="be8bf-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="be8bf-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>