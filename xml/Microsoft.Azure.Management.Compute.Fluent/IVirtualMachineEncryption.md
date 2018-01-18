<Type Name="IVirtualMachineEncryption" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineEncryption" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineEncryption" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineEncryption" />
  <TypeSignature Language="F#" Value="type IVirtualMachineEncryption = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e3cdb-101">Verschlüsselung für virtuellen Computer verbundene Operationen.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-101">Virtual machine encryption related operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Disable (Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Disable(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.Disable(Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType)" />
      <MemberSignature Language="VB.NET" Value="Public Function Disable (volumeType As DiskVolumeType) As IDiskVolumeEncryptionMonitor" />
      <MemberSignature Language="F#" Value="abstract member Disable : Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType -&gt; Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" Usage="iVirtualMachineEncryption.Disable volumeType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="volumeType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType" />
      </Parameters>
      <Docs>
        <param name="volumeType"><span data-ttu-id="e3cdb-102">Der Volumetyp um Verschlüsselung zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-102">Volume type to disable encryption.</span></span></param>
        <summary>
            <span data-ttu-id="e3cdb-103">Deaktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-103">Disable encryption for virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e3cdb-104">Aktuellen Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-104">Current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; DisableAsync (Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; DisableAsync(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType volumeType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.DisableAsync(Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DisableAsync : Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iVirtualMachineEncryption.DisableAsync (volumeType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="volumeType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.DiskVolumeType" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="volumeType"><span data-ttu-id="e3cdb-105">Der Volumetyp um Verschlüsselung zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-105">Volume type to disable encryption.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="e3cdb-106">Deaktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-106">Disable encryption for virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e3cdb-107">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3cdb-107">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="e3cdb-108">Observable-Objekt, der aktuelle Status von Volumes Entschlüsselung ausgibt.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-108">Observable that emits current volume decryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable (Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration encryptionSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable(class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration encryptionSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.Enable(Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enable (encryptionSettings As LinuxVMDiskEncryptionConfiguration) As IDiskVolumeEncryptionMonitor" />
      <MemberSignature Language="F#" Value="abstract member Enable : Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration -&gt; Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" Usage="iVirtualMachineEncryption.Enable encryptionSettings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" />
      </Parameters>
      <Docs>
        <param name="encryptionSettings"><span data-ttu-id="e3cdb-109">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-109">Encryption settings for windows virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="e3cdb-110">Aktivieren Sie die Verschlüsselung für Linux-VM-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-110">Enable encryption for Linux virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e3cdb-111">Aktuellen Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-111">Current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable (Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration encryptionSettings);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable(class Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration encryptionSettings) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.Enable(Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enable (encryptionSettings As WindowsVMDiskEncryptionConfiguration) As IDiskVolumeEncryptionMonitor" />
      <MemberSignature Language="F#" Value="abstract member Enable : Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration -&gt; Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" Usage="iVirtualMachineEncryption.Enable encryptionSettings" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration" />
      </Parameters>
      <Docs>
        <param name="encryptionSettings"><span data-ttu-id="e3cdb-112">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-112">Encryption settings for windows virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="e3cdb-113">Aktivieren Sie die Verschlüsselung für Windows-VM-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-113">Enable encryption for Windows virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e3cdb-114">Aktuellen Verschlüsselungsstatus.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-114">Current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable (string keyVaultId, string aadClientId, string aadSecret);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor Enable(string keyVaultId, string aadClientId, string aadSecret) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.Enable(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Enable (keyVaultId As String, aadClientId As String, aadSecret As String) As IDiskVolumeEncryptionMonitor" />
      <MemberSignature Language="F#" Value="abstract member Enable : string * string * string -&gt; Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" Usage="iVirtualMachineEncryption.Enable (keyVaultId, aadClientId, aadSecret)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="aadClientId" Type="System.String" />
        <Parameter Name="aadSecret" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="keyVaultId"><span data-ttu-id="e3cdb-115">Ressourcen-ID des schlüsseltresors, die Datenträger-Verschlüsselungsschlüssel zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-115">Resource ID of the key vault to store the disk encryption key.</span></span></param>
        <param name="aadClientId"><span data-ttu-id="e3cdb-116">Client-ID einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-116">Client ID of an AAD application which has permission to the key vault.</span></span></param>
        <param name="aadSecret"><span data-ttu-id="e3cdb-117">Der geheime Clientschlüssel, der AadClientId entspricht.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-117">Client secret corresponding to the aadClientId.</span></span></param>
        <summary>
            <span data-ttu-id="e3cdb-118">Aktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-118">Enable encryption for virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e3cdb-119">Aktuellen Status von Volumes Entschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-119">Current volume decryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync (Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration encryptionSettings, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync(class Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration encryptionSettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.EnableAsync(Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAsync : Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iVirtualMachineEncryption.EnableAsync (encryptionSettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.LinuxVMDiskEncryptionConfiguration" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encryptionSettings"><span data-ttu-id="e3cdb-120">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-120">Encryption settings for windows virtual machine.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="e3cdb-121">Aktivieren Sie die Verschlüsselung für Linux-VM-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-121">Enable encryption for Linux virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e3cdb-122">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3cdb-122">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="e3cdb-123">Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-123">Observable that emits current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync (Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration encryptionSettings, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync(class Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration encryptionSettings, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.EnableAsync(Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAsync : Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iVirtualMachineEncryption.EnableAsync (encryptionSettings, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="encryptionSettings" Type="Microsoft.Azure.Management.Compute.Fluent.WindowsVMDiskEncryptionConfiguration" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="encryptionSettings"><span data-ttu-id="e3cdb-124">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-124">Encryption settings for windows virtual machine.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="e3cdb-125">Aktivieren Sie die Verschlüsselung für Windows-VM-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-125">Enable encryption for Windows virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e3cdb-126">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3cdb-126">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="e3cdb-127">Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-127">Observable that emits current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync (string keyVaultId, string aadClientId, string aadSecret, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; EnableAsync(string keyVaultId, string aadClientId, string aadSecret, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.EnableAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member EnableAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iVirtualMachineEncryption.EnableAsync (keyVaultId, aadClientId, aadSecret, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="keyVaultId" Type="System.String" />
        <Parameter Name="aadClientId" Type="System.String" />
        <Parameter Name="aadSecret" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="keyVaultId"><span data-ttu-id="e3cdb-128">Ressourcen-ID des schlüsseltresors, die Datenträger-Verschlüsselungsschlüssel zu speichern.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-128">Resource ID of the key vault to store the disk encryption key.</span></span></param>
        <param name="aadClientId"><span data-ttu-id="e3cdb-129">Client-ID einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-129">Client ID of an AAD application which has permission to the key vault.</span></span></param>
        <param name="aadSecret"><span data-ttu-id="e3cdb-130">Der geheime Clientschlüssel, der AadClientId entspricht.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-130">Client secret corresponding to the aadClientId.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="e3cdb-131">Aktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-131">Enable encryption for virtual machine disks.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e3cdb-132">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3cdb-132">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="e3cdb-133">Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-133">Observable that emits current volume encryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetMonitor">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor GetMonitor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor GetMonitor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.GetMonitor" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMonitor () As IDiskVolumeEncryptionMonitor" />
      <MemberSignature Language="F#" Value="abstract member GetMonitor : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor" Usage="iVirtualMachineEncryption.GetMonitor " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e3cdb-134">Aktuellen Status von Volumes Entschlüsselung.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-134">Current volume decryption status.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetMonitorAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; GetMonitorAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt; GetMonitorAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineEncryption.GetMonitorAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMonitorAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;" Usage="iVirtualMachineEncryption.GetMonitorAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Fluent.IDiskVolumeEncryptionMonitor&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="e3cdb-135">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e3cdb-135">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
        <return><span data-ttu-id="e3cdb-136">Observable-Objekt, der aktuelle Status von Volumes Entschlüsselung ausgibt.</span><span class="sxs-lookup"><span data-stu-id="e3cdb-136">Observable that emits current volume decryption status.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>