<Type Name="IWithDataDiskSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource">
  <TypeSignature Language="C#" Value="public interface IWithDataDiskSource : Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromSnapshot, Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataDiskSource implements class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromSnapshot, class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataDiskSource&#xA;Implements IWithDataDiskFromDisk, IWithDataDiskFromSnapshot, IWithDataDiskFromVhd" />
  <TypeSignature Language="F#" Value="type IWithDataDiskSource = interface&#xA;    interface IWithDataDiskFromVhd&#xA;    interface IWithDataDiskFromDisk&#xA;    interface IWithDataDiskFromSnapshot" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromDisk</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromSnapshot</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskFromVhd</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e826b-101">Die Phase der verwalteten Datenträger Definition taktmonitoren-Datenquelle auswählen.</span><span class="sxs-lookup"><span data-stu-id="e826b-101">The stage of the managed disk definition allowing to choose data source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate WithSizeInGB (int sizeInGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate WithSizeInGB(int32 sizeInGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithDataDiskSource.WithSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSizeInGB (sizeInGB As Integer) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate" Usage="iWithDataDiskSource.WithSizeInGB sizeInGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Disk.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeInGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="sizeInGB"><span data-ttu-id="e826b-102">Die Größe des Datenträgers in GB.</span><span class="sxs-lookup"><span data-stu-id="e826b-102">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="e826b-103">Gibt die Größe des Datenträgers für einen leeren Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="e826b-103">Specifies the disk size for an empty disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e826b-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="e826b-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>