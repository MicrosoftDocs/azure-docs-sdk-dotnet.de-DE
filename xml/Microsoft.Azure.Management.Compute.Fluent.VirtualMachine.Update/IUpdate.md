<Type Name="IUpdate" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate">
  <TypeSignature Language="C#" Value="public interface IUpdate : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithBootDiagnostics, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedServiceIdentity, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface, Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IUpdate implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IUpdate&#xA;Implements IAppliable(Of IVirtualMachine), IBeta, IUpdateWithTags(Of IUpdate), IWithBootDiagnostics, IWithExtension, IWithManagedDataDisk, IWithManagedServiceIdentity, IWithSecondaryNetworkInterface, IWithUnmanagedDataDisk" />
  <TypeSignature Language="F#" Value="type IUpdate = interface&#xA;    interface IAppliable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IUpdateWithTags&lt;IUpdate&gt;&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithBootDiagnostics</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithExtension</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedDataDisk</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithManagedServiceIdentity</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithUnmanagedDataDisk</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Update.IUpdateWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IAppliable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="cc1c6-101">Die Vorlage für eine Update-Vorgang mit den Einstellungen aus, die geändert werden können.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-101">The template for an update operation, containing all the settings that can be modified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataDiskDefaultCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithDataDiskDefaultCachingType (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithDataDiskDefaultCachingType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithDataDiskDefaultCachingType(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultCachingType (cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithDataDiskDefaultCachingType cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="cc1c6-102">ein Zwischenspeichern Typ.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-102">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-103">Gibt die standardmäßige caching-Typ für die verwaltete Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-103">Specifies the default caching type for the managed data disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithDataDiskDefaultStorageAccountType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithDataDiskDefaultStorageAccountType (Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithDataDiskDefaultStorageAccountType(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes storageAccountType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithDataDiskDefaultStorageAccountType(Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataDiskDefaultStorageAccountType (storageAccountType As StorageAccountTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDataDiskDefaultStorageAccountType : Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithDataDiskDefaultStorageAccountType storageAccountType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="storageAccountType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.StorageAccountTypes" />
      </Parameters>
      <Docs>
        <param name="storageAccountType"><span data-ttu-id="cc1c6-105">Ein Speicher-Kontotyp.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-105">A storage account type.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-106">Gibt einen Speicher-Kontotyp an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-106">Specifies a storage account type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithOSDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskCaching (cachingType As CachingTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithOSDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="cc1c6-108">ein Zwischenspeichern Typ.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-108">A caching type.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-109">Gibt an, welche Zwischenspeichern für den Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-109">Specifies the caching type for the OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-110">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-110">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskEncryptionSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskEncryptionSettings (Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskEncryptionSettings(class Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings settings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithOSDiskEncryptionSettings(Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskEncryptionSettings (settings As DiskEncryptionSettings) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskEncryptionSettings : Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithOSDiskEncryptionSettings settings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="settings" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskEncryptionSettings" />
      </Parameters>
      <Docs>
        <param name="settings"><span data-ttu-id="cc1c6-111">die verschlüsselungseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-111">The encryption settings.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-112">Gibt die Einstellungen für die Verschlüsselung für den Betriebssystem-Datenträger an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-112">Specifies the encryption settings for the OS Disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-113">Die Phase, die erstellbaren Update der VM darstellt.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-113">The stage representing creatable VM update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskSizeInGB (int size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithOSDiskSizeInGB(int32 size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithOSDiskSizeInGB(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskSizeInGB (size As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskSizeInGB : int -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithOSDiskSizeInGB size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="size"><span data-ttu-id="cc1c6-114">eine Größe des Datenträgers.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-114">A disk size.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-115">Gibt die Größe des Betriebssystem-Datenträgers in GB an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-115">Specifies the size of the OS disk in GB.</span></span>
            <span data-ttu-id="cc1c6-116">Nur nicht verwaltete Datenträger möglicherweise als Teil einer VM-Update angepasst.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-116">Only unmanaged disks may be resized as part of a VM update.</span></span> <span data-ttu-id="cc1c6-117">Verwalteter Datenträger müssen separat mit verwalteten Datenträger-API geändert werden.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-117">Managed disks must be resized separately, using managed disk API.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-118">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-118">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithSize (Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithSize(class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithSize(Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (size As VirtualMachineSizeTypes) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithSize size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes" />
      </Parameters>
      <Docs>
        <param name="size"><span data-ttu-id="cc1c6-119">Eine Größe aus der Liste der verfügbaren Größen für die virtuelle Maschine.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-119">A size from the list of available sizes for the virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-120">Gibt eine neue Größe für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-120">Specifies a new size for the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-121">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-121">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithSize (string sizeName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithSize(string sizeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate.WithSize(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (sizeName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iUpdate.WithSize sizeName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sizeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sizeName"><span data-ttu-id="cc1c6-122">Der Name einer Größe für den virtuellen Computer als Text.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-122">The name of a size for the virtual machine as text.</span></span></param>
        <summary>
            <span data-ttu-id="cc1c6-123">Gibt eine neue Größe für den virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-123">Specifies a new size for the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="cc1c6-124">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="cc1c6-124">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>