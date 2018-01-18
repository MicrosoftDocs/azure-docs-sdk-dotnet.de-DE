<Type Name="IWithDiskSettings&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskSettings&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDiskSettings&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDiskSettings`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskSettings`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDiskSettings(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDiskSettings&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="2a2ea-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="2a2ea-102">Die Stufe der Daten Datenträger Image Definition ermöglicht Konfigurationen für den Datenträger angeben, wenn es aus der gleichen Datenträger-Imagedatei Daten erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-102">The stage of data disk image definition allowing to specify configurations for the data disk when it is created from the same data disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; WithDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; WithDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskSettings`1.WithDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDiskCaching (cachingType As CachingTypes) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDiskSettings.WithDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="2a2ea-103">der Datenträger, die caching-Typ.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-103">The disk caching type.</span></span></param>
        <summary>
            <span data-ttu-id="2a2ea-104">Gibt an, welche caching für Datenträger.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-104">Specifies the caching type for data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2a2ea-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDiskSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; WithDiskSizeInGB (int diskSizeGB);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; WithDiskSizeInGB(int32 diskSizeGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithDiskSettings`1.WithDiskSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDiskSizeInGB (diskSizeGB As Integer) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDiskSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithDiskSettings.WithDiskSizeInGB diskSizeGB" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="diskSizeGB" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="diskSizeGB"><span data-ttu-id="2a2ea-106">Die Größe des Datenträgers in GB.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-106">The disk size in GB.</span></span></param>
        <summary>
            <span data-ttu-id="2a2ea-107">Gibt die Größe in GB für Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-107">Specifies the size in GB for data disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="2a2ea-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="2a2ea-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>