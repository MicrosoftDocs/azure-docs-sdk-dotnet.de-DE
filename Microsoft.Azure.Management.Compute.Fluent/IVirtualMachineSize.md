<Type Name="IVirtualMachineSize" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineSize : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineSize implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineSize&#xA;Implements IHasName" />
  <TypeSignature Language="F#" Value="type IVirtualMachineSize = interface&#xA;    interface IHasName" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="03289-101">Ein Typ, die Größe des virtuellen Computers verfügbar für ein Abonnement in einer Region darstellt.</span><span class="sxs-lookup"><span data-stu-id="03289-101">A type representing virtual machine size available for a subscription in a region.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="MaxDataDiskCount">
      <MemberSignature Language="C#" Value="public int MaxDataDiskCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxDataDiskCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.MaxDataDiskCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxDataDiskCount As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxDataDiskCount : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.MaxDataDiskCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03289-102">Ruft die maximale Anzahl von Datenträgern, die von einer VM-Größe zulässig.</span><span class="sxs-lookup"><span data-stu-id="03289-102">Gets the maximum number of data disks allowed by a VM size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MemoryInMB">
      <MemberSignature Language="C#" Value="public int MemoryInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MemoryInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.MemoryInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MemoryInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.MemoryInMB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.MemoryInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03289-103">Ruft die Größe des Arbeitsspeichers unterstützt, die Größe des virtuellen Computers ab.</span><span class="sxs-lookup"><span data-stu-id="03289-103">Gets the memory size supported by the VM size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfCores">
      <MemberSignature Language="C#" Value="public int NumberOfCores { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfCores" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.NumberOfCores" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfCores As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfCores : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.NumberOfCores" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03289-104">Ruft die Anzahl der Kerne, die von der Größe des virtuellen Computers unterstützt.</span><span class="sxs-lookup"><span data-stu-id="03289-104">Gets the number of cores supported by the VM size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskSizeInMB">
      <MemberSignature Language="C#" Value="public int OSDiskSizeInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OSDiskSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.OSDiskSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskSizeInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.OSDiskSizeInMB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.OSDiskSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03289-105">Ruft die Größe des virtuellen Computers zulässig Datenträgergröße des Betriebssystems ab.</span><span class="sxs-lookup"><span data-stu-id="03289-105">Gets the OS disk size allowed by the VM size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceDiskSizeInMB">
      <MemberSignature Language="C#" Value="public int ResourceDiskSizeInMB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ResourceDiskSizeInMB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.ResourceDiskSizeInMB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceDiskSizeInMB As Integer" />
      <MemberSignature Language="F#" Value="member this.ResourceDiskSizeInMB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSize.ResourceDiskSizeInMB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="03289-106">Ruft die Größe des virtuellen Computers zulässig Ressource Datenträgergröße ab.</span><span class="sxs-lookup"><span data-stu-id="03289-106">Gets the resource disk size allowed by the VM size.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>