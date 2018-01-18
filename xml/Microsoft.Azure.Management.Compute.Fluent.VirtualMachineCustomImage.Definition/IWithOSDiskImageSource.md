<Type Name="IWithOSDiskImageSource" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskImageSource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskImageSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskImageSource" />
  <TypeSignature Language="F#" Value="type IWithOSDiskImageSource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0a5a-101">Die Phase der Image-Definition ermöglicht ein OS-Quelle und ein Betriebssystem-Status für das Betriebssystemabbild auswählen.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-101">The stage of the image definition allowing to choose an OS source and an OS state for the OS image.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceManagedDisk As IDisk, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromDisk (sourceManagedDisk, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDisk"><span data-ttu-id="c0a5a-102">Verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-102">Source managed disk.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-103">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-103">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-104">Gibt an, die Linux verwalteten Quelldatenträger für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-104">Specifies the Linux source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk (string sourceManagedDiskId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromDisk(string sourceManagedDiskId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromDisk(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromDisk (sourceManagedDiskId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromDisk : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromDisk (sourceManagedDiskId, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="c0a5a-106">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-106">Source managed disk resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-107">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-107">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-108">Gibt an, die Linux verwalteten Quelldatenträger für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-108">Specifies the Linux source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshot As ISnapshot, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromSnapshot (sourceSnapshot, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><span data-ttu-id="c0a5a-110">Quelle Snapshot-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-110">Source snapshot resource.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-111">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-111">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-112">Gibt die Momentaufnahme des Linux-Quelle für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-112">Specifies the Linux source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-113">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot (string sourceSnapshotId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromSnapshot(string sourceSnapshotId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromSnapshot(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromSnapshot (sourceSnapshotId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromSnapshot : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromSnapshot (sourceSnapshotId, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="c0a5a-114">Momentaufnahme der quellressource-ID.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-114">Source snapshot resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-115">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-115">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-116">Gibt die Momentaufnahme des Linux-Quelle für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-116">Specifies the Linux source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-117">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-117">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithLinuxFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromVhd (string sourceVhdUrl, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithLinuxFromVhd(string sourceVhdUrl, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithLinuxFromVhd(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLinuxFromVhd (sourceVhdUrl As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithLinuxFromVhd : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithLinuxFromVhd (sourceVhdUrl, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="c0a5a-118">Quell-Linux-virtuelle Festplatte-URL.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-118">Source Linux virtual hard disk URL.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-119">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-119">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-120">Gibt an, die Linux Quelle systemeigenen VHD für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-120">Specifies the Linux source native VHD for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-121">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-121">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceManagedDisk, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceManagedDisk As IDisk, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromDisk (sourceManagedDisk, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceManagedDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDisk"><span data-ttu-id="c0a5a-122">Verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-122">Source managed disk.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-123">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-123">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-124">Gibt den verwalteten Windows Quelle-Datenträger für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-124">Specifies the Windows source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-125">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-125">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk (string sourceManagedDiskId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromDisk(string sourceManagedDiskId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromDisk(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceManagedDiskId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromDisk (sourceManagedDiskId, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceManagedDiskId"><span data-ttu-id="c0a5a-126">Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-126">Source managed disk resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-127">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-127">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-128">Gibt den verwalteten Windows Quelle-Datenträger für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-128">Specifies the Windows source managed disk for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-129">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-129">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshot As ISnapshot, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromSnapshot (sourceSnapshot, osState)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><span data-ttu-id="c0a5a-130">Quelle Snapshot-Ressource.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-130">Source snapshot resource.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-131">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-131">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-132">Gibt die Windows-Quell-Momentaufnahme für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-132">Specifies the Windows source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-133">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-133">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot (string sourceSnapshotId, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromSnapshot(string sourceSnapshotId, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromSnapshot(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshotId As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromSnapshot (sourceSnapshotId, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="c0a5a-134">Momentaufnahme der quellressource-ID.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-134">Source snapshot resource ID.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-135">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-135">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-136">Gibt die Windows-Quell-Momentaufnahme für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-136">Specifies the Windows source snapshot for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-137">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-137">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromVhd (string sourceVhdUrl, Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings WithWindowsFromVhd(string sourceVhdUrl, valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes osState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithOSDiskImageSource.WithWindowsFromVhd(System.String,Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromVhd (sourceVhdUrl As String, osState As OperatingSystemStateTypes) As IWithCreateAndDataDiskImageOSDiskSettings" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromVhd : string * Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreateAndDataDiskImageOSDiskSettings" Usage="iWithOSDiskImageSource.WithWindowsFromVhd (sourceVhdUrl, osState)" />
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
        <Parameter Name="osState" Type="Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemStateTypes" />
      </Parameters>
      <Docs>
        <param name="sourceVhdUrl"><span data-ttu-id="c0a5a-138">Quelle Windows VHD-URL.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-138">Source Windows virtual hard disk URL.</span></span></param>
        <param name="osState"><span data-ttu-id="c0a5a-139">Betriebssystem – Status.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-139">Operating system state.</span></span></param>
        <summary>
            <span data-ttu-id="c0a5a-140">Gibt an, die Windows Quelle systemeigenen VHD für die Datenträger-Image.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-140">Specifies the Windows source native VHD for the OS disk image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0a5a-141">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c0a5a-141">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>