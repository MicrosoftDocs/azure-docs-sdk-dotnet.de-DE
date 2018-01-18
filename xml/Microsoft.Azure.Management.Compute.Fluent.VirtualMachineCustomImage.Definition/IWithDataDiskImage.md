<Type Name="IWithDataDiskImage" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage">
  <TypeSignature Language="C#" Value="public interface IWithDataDiskImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataDiskImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataDiskImage" />
  <TypeSignature Language="F#" Value="type IWithDataDiskImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4c743-101">Die Phase der bilddefinition ermöglicht ein hinzuzufügende Datenträger Image.</span><span class="sxs-lookup"><span data-stu-id="4c743-101">The stage of an image definition allowing to add a data disk image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineDataDiskImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt; DefineDataDiskImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt; DefineDataDiskImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.DefineDataDiskImage" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineDataDiskImage () As IBlank(Of IWithCreateAndDataDiskImageOSDiskSettings)" />
      <MemberSignature Language="F#" Value="abstract member DefineDataDiskImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt;" Usage="iWithDataDiskImage.DefineDataDiskImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.CustomImageDataDisk.Definition.IBlank&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4c743-102">Ruft ab, beginnt die Definition eines neuen Daten-Datenträger-Image auf dem Abbild hinzugefügt werden.</span><span class="sxs-lookup"><span data-stu-id="4c743-102">Gets Begins the definition of a new data disk image to add to the image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromManagedDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromManagedDisk (string sourceManagedDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromManagedDisk(string sourceManagedDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromManagedDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromManagedDisk (sourceManagedDiskId As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromManagedDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromManagedDisk sourceManagedDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="4c743-103">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="4c743-103">Source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="4c743-104">Fügt einen Daten-Datenträger-Image mit einem vorhandenen verwalteten Datenträger als Quelle an.</span><span class="sxs-lookup"><span data-stu-id="4c743-104">Adds a data disk image with an existing managed disk as the source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4c743-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="4c743-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromSnapshot (sourceSnapshotId As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="4c743-106">Momentaufnahme der quellressource-ID.</span><span class="sxs-lookup"><span data-stu-id="4c743-106">Source snapshot resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="4c743-107">Fügt einen Daten-Datenträger-Image mit einer vorhandenen Momentaufnahme als Quelle an.</span><span class="sxs-lookup"><span data-stu-id="4c743-107">Adds a data disk image with an existing snapshot as the source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4c743-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="4c743-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskImageFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromVhd (string sourceVhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithDataDiskImageFromVhd(string sourceVhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithDataDiskImage.WithDataDiskImageFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskImageFromVhd (sourceVhdUrl As String) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskImageFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithDataDiskImage.WithDataDiskImageFromVhd sourceVhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceVhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="4c743-109">Virtuelle Festplatte-Quell-URL.</span><span class="sxs-lookup"><span data-stu-id="4c743-109">Source virtual hard disk URL.</span></span></param>
        <summary>
            <span data-ttu-id="4c743-110">Fügt einen Daten-Datenträger-Image mit einer virtuellen Festplatte als Quelle an.</span><span class="sxs-lookup"><span data-stu-id="4c743-110">Adds a data disk image with a virtual hard disk as the source.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4c743-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="4c743-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>