<Type Name="IWithOSSnapshotFromImage" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage">
  <TypeSignature Language="C#" Value="public interface IWithOSSnapshotFromImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSSnapshotFromImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSSnapshotFromImage" />
  <TypeSignature Language="F#" Value="type IWithOSSnapshotFromImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8aee1-101">Die Phase der verwalteten Datenträger Definition ermöglicht ein Betriebssystemabbild Quelle auswählen.</span><span class="sxs-lookup"><span data-stu-id="8aee1-101">The stage of the managed disk definition allowing to choose a source operating system image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineCustomImage) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage" />
      </Parameters>
      <Docs>
        <param name="image"><span data-ttu-id="8aee1-102">Das Bild.</span><span class="sxs-lookup"><span data-stu-id="8aee1-102">The image.</span></span></param>
        <summary>
            <span data-ttu-id="8aee1-103">Gibt ein benutzerdefiniertes Bild, ein älteres Betriebssystem enthält.</span><span class="sxs-lookup"><span data-stu-id="8aee1-103">Specifies a custom image containing an operating system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8aee1-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8aee1-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage image) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (image As IVirtualMachineImage) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage image" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="image" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" />
      </Parameters>
      <Docs>
        <param name="image"><span data-ttu-id="8aee1-105">Das Bild.</span><span class="sxs-lookup"><span data-stu-id="8aee1-105">The image.</span></span></param>
        <summary>
            <span data-ttu-id="8aee1-106">Gibt ein Bild, ein älteres Betriebssystem enthält.</span><span class="sxs-lookup"><span data-stu-id="8aee1-106">Specifies an image containing an operating system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8aee1-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8aee1-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage (string imageId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate FromImage(string imageId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithOSSnapshotFromImage.FromImage(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromImage (imageId As String, osType As OperatingSystemTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromImage : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithOSSnapshotFromImage.FromImage (imageId, osType)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageId" Type="System.String" />
        <Parameter Name="osType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" />
      </Parameters>
      <Docs>
        <param name="imageId"><span data-ttu-id="8aee1-108">Image-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="8aee1-108">Image resource ID.</span></span></param>
        <param name="osType"><span data-ttu-id="8aee1-109">Betriebssystem-Typ.</span><span class="sxs-lookup"><span data-stu-id="8aee1-109">Operating system type.</span></span></param>
        <summary>
            <span data-ttu-id="8aee1-110">Gibt ein Bild, ein älteres Betriebssystem enthält.</span><span class="sxs-lookup"><span data-stu-id="8aee1-110">Specifies an image containing an operating system.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8aee1-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8aee1-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>