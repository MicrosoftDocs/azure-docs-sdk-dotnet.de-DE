<Type Name="IWithImageSource&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithImageSource&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithImageSource`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithImageSource(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithImageSource&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="9a245-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="9a245-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9a245-102">Die Phase der Image-Definition ermöglicht die Quelle der Daten auf Datenträger Image.</span><span class="sxs-lookup"><span data-stu-id="9a245-102">The stage of the image definition allowing to choose the source of the data disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; FromManagedDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; FromManagedDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1.FromManagedDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromManagedDisk (sourceManagedDisk As IDisk) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromManagedDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageSource.FromManagedDisk sourceManagedDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDisk"><span data-ttu-id="9a245-103">Verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="9a245-103">Source managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="9a245-104">Gibt verwaltete Quelldatenträger für der Daten-Datenträger-Imagedatei an.</span><span class="sxs-lookup"><span data-stu-id="9a245-104">Specifies the source managed disk for the data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a245-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a245-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; FromManagedDisk (string sourceManagedDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; FromManagedDisk(string sourceManagedDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1.FromManagedDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromManagedDisk (sourceManagedDiskId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromManagedDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageSource.FromManagedDisk sourceManagedDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="9a245-106">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="9a245-106">Source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="9a245-107">Gibt verwaltete Quelldatenträger für der Daten-Datenträger-Imagedatei an.</span><span class="sxs-lookup"><span data-stu-id="9a245-107">Specifies the source managed disk for the data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a245-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a245-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; FromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; FromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1.FromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromSnapshot (sourceSnapshotId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageSource.FromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="9a245-109">Momentaufnahme der quellressource-ID.</span><span class="sxs-lookup"><span data-stu-id="9a245-109">Source snapshot resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="9a245-110">Gibt die Quellmomentaufnahme für die Datenträger-Imagedatei Daten.</span><span class="sxs-lookup"><span data-stu-id="9a245-110">Specifies the source snapshot for the data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a245-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a245-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt; FromVhd (string sourceVhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach`1&lt;!ParentT&gt; FromVhd(string sourceVhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithImageSource`1.FromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVhd (sourceVhdUrl As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member FromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithImageSource.FromVhd sourceVhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceVhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="9a245-112">Virtuelle Festplatte-Quell-URL.</span><span class="sxs-lookup"><span data-stu-id="9a245-112">Source virtual hard disk URL.</span></span></param>
        <summary>
            <span data-ttu-id="9a245-113">Gibt die Quelle VHD für das Daten-Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="9a245-113">Specifies the source VHD for the data disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="9a245-114">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="9a245-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>