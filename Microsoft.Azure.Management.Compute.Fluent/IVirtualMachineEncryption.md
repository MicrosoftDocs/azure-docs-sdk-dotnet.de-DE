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
            Verschlüsselung für virtuellen Computer verbundene Operationen.
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
        <param name="volumeType">Der Volumetyp um Verschlüsselung zu deaktivieren.</param>
        <summary>
            Deaktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Aktuellen Verschlüsselungsstatus.</return>
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
        <param name="volumeType">Der Volumetyp um Verschlüsselung zu deaktivieren.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Deaktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt, der aktuelle Status von Volumes Entschlüsselung ausgibt.</return>
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
        <param name="encryptionSettings">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für Linux-VM-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Aktuellen Verschlüsselungsstatus.</return>
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
        <param name="encryptionSettings">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für Windows-VM-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Aktuellen Verschlüsselungsstatus.</return>
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
        <param name="keyVaultId">Ressourcen-ID des schlüsseltresors, die Datenträger-Verschlüsselungsschlüssel zu speichern.</param>
        <param name="aadClientId">Client-ID einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</param>
        <param name="aadSecret">Der geheime Clientschlüssel, der AadClientId entspricht.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Aktuellen Status von Volumes Entschlüsselung.</return>
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
        <param name="encryptionSettings">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für Linux-VM-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</return>
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
        <param name="encryptionSettings">Einstellungen für die Verschlüsselung für den virtuellen Windows-Computer.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für Windows-VM-Datenträger.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</return>
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
        <param name="keyVaultId">Ressourcen-ID des schlüsseltresors, die Datenträger-Verschlüsselungsschlüssel zu speichern.</param>
        <param name="aadClientId">Client-ID einer AAD-Anwendung die Berechtigung für den schlüsseltresor hat.</param>
        <param name="aadSecret">Der geheime Clientschlüssel, der AadClientId entspricht.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktivieren Sie die Verschlüsselung für die Datenträger der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt, die aktuellen Verschlüsselungsstatus ausgibt.</return>
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
        <return>Aktuellen Status von Volumes Entschlüsselung.</return>
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
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt, der aktuelle Status von Volumes Entschlüsselung ausgibt.</return>
      </Docs>
    </Member>
  </Members>
</Type>