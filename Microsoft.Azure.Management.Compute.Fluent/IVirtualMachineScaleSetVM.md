<Type Name="IVirtualMachineScaleSetVM" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetVM : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetVM implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetVM&#xA;Implements IChildResource(Of IVirtualMachineScaleSet), IHasInner(Of VirtualMachineScaleSetVMInner), IHasParent(Of IVirtualMachineScaleSet), IRefreshable(Of IVirtualMachineScaleSetVM), IResource" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetVM = interface&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IChildResource&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IHasParent&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IRefreshable&lt;IVirtualMachineScaleSetVM&gt;&#xA;    interface IHasInner&lt;VirtualMachineScaleSetVMInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetVMInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung der Instanz eines virtuellen Computers in einer Azure VM-Skalierungsgruppe festgelegt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AdministratorUserName">
      <MemberSignature Language="C#" Value="public string AdministratorUserName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AdministratorUserName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AdministratorUserName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdministratorUserName As String" />
      <MemberSignature Language="F#" Value="member this.AdministratorUserName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AdministratorUserName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Benutzers Admin ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySetId">
      <MemberSignature Language="C#" Value="public string AvailabilitySetId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AvailabilitySetId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AvailabilitySetId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySetId As String" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySetId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.AvailabilitySetId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ressource, die ID der verfügbarkeitsgruppe festgelegt, dass diese virtuelle Computerinstanz gehört.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnosticEnabled">
      <MemberSignature Language="C#" Value="public bool BootDiagnosticEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool BootDiagnosticEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BootDiagnosticEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.BootDiagnosticEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn es sich bei der Diagnose Start aktiviert ist, andernfalls false.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BootDiagnosticStorageAccountUri">
      <MemberSignature Language="C#" Value="public string BootDiagnosticStorageAccountUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BootDiagnosticStorageAccountUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticStorageAccountUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BootDiagnosticStorageAccountUri As String" />
      <MemberSignature Language="F#" Value="member this.BootDiagnosticStorageAccountUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.BootDiagnosticStorageAccountUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den URI mit dem Speicherkonto über das Speichern von Boot-Diagnoseprotokolls ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerName">
      <MemberSignature Language="C#" Value="public string ComputerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ComputerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputerName As String" />
      <MemberSignature Language="F#" Value="member this.ComputerName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ComputerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Computernamen des VM-Instanz mit dem VM Scale Set-Präfix ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt; DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineDataDisk)" />
      <MemberSignature Language="F#" Value="member this.DataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die verwaltete Daten-Datenträger, die zugeordneten VM-Instanz, durch LUN indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public void Deallocate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Deallocate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Deallocate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deallocate ()" />
      <MemberSignature Language="F#" Value="abstract member Deallocate : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Deallocate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Die virtuelle Computerinstanz heruntergefahren, und die zugeordneten Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeallocateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeallocateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DeallocateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.DeallocateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Die virtuelle Computerinstanz heruntergefahren, und die zugeordneten Ressourcen frei.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Die Observable-Objekt für die Deallocate-Aktion.</return>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Delete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete ()" />
      <MemberSignature Language="F#" Value="abstract member Delete : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Delete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Löscht die VM-Instanz.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.DeleteAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Löscht die VM-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Die Observable-Objekt für die Löschaktion.</return>
      </Docs>
    </Member>
    <Member MemberName="DiagnosticsProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile DiagnosticsProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DiagnosticsProfile As DiagnosticsProfile" />
      <MemberSignature Language="F#" Value="member this.DiagnosticsProfile : Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.DiagnosticsProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.DiagnosticsProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Profil "Diagnose" der virtuellen Computerinstanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IReadOnlyDictionary(Of String, IVirtualMachineScaleSetVMInstanceExtension)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMInstanceExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die VM-Instanz, die nach Namen indiziert zugeordneten Erweiterungen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterface (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterface(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetNetworkInterface(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkInterface (name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkInterface : string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSetVM.GetNetworkInterface name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der Netzwerkschnittstelle.</param>
        <summary>
            Ruft eine Netzwerkschnittstelle, die dieser Instanz der virtuellen Maschine zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Netzwerkschnittstelle.</return>
      </Docs>
    </Member>
    <Member MemberName="GetOSCustomImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage GetOSCustomImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage GetOSCustomImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetOSCustomImage" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOSCustomImage () As IVirtualMachineCustomImage" />
      <MemberSignature Language="F#" Value="abstract member GetOSCustomImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage" Usage="iVirtualMachineScaleSetVM.GetOSCustomImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineCustomImage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Des benutzerdefinierten Images, dem das Betriebssystem des virtuellen Computers Instanz basiert, Null werden zurückgegeben, andernfalls.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetOSPlatformImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetOSPlatformImage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage GetOSPlatformImage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.GetOSPlatformImage" />
      <MemberSignature Language="VB.NET" Value="Public Function GetOSPlatformImage () As IVirtualMachineImage" />
      <MemberSignature Language="F#" Value="abstract member GetOSPlatformImage : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage" Usage="iVirtualMachineScaleSetVM.GetOSPlatformImage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImage</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Die Plattform-Images, die das Betriebssystem des virtuellen Computers Instanz basiert, Null werden zurückgegeben, andernfalls.
            </return>
      </Docs>
    </Member>
    <Member MemberName="InstanceId">
      <MemberSignature Language="C#" Value="public string InstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string InstanceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceId As String" />
      <MemberSignature Language="F#" Value="member this.InstanceId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Instanz-ID, die mit dieser Instanz der virtuellen Maschine zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView InstanceView" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceView" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property InstanceView As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="member this.InstanceView : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.InstanceView" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Instanzansicht eines virtuellen Computerinstanz ab.
            Zum Abrufen der letzten Verwendung der Instanz anzeigen <code>refreshInstanceView()</code>.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLatestScaleSetUpdateApplied">
      <MemberSignature Language="C#" Value="public bool IsLatestScaleSetUpdateApplied { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLatestScaleSetUpdateApplied" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLatestScaleSetUpdateApplied" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLatestScaleSetUpdateApplied As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLatestScaleSetUpdateApplied : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLatestScaleSetUpdateApplied" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn die aktuelle Skalierung Modell festgelegt, die Änderungen auf die virtuelle Computerinstanz angewendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsLinuxPasswordAuthenticationEnabled">
      <MemberSignature Language="C#" Value="public bool IsLinuxPasswordAuthenticationEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsLinuxPasswordAuthenticationEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLinuxPasswordAuthenticationEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsLinuxPasswordAuthenticationEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsLinuxPasswordAuthenticationEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsLinuxPasswordAuthenticationEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn diese einem virtuellen Linux-Computer und Kennwort-basierte Anmeldung aktiviert, andernfalls false ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedDiskEnabled">
      <MemberSignature Language="C#" Value="public bool IsManagedDiskEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManagedDiskEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsManagedDiskEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManagedDiskEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManagedDiskEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsManagedDiskEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn verwaltete Datenträger für den Datenträger des virtuellen Computers (Betriebssystem, Data) verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnCustomImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnCustomImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnCustomImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnCustomImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnCustomImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnCustomImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnCustomImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn das Betriebssystem der virtuellen Computerinstanz benutzerdefiniertes Image basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnPlatformImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnPlatformImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnPlatformImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnPlatformImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnPlatformImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnPlatformImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnPlatformImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn das Betriebssystem der virtuellen Computerinstanz Plattformimage basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsOSBasedOnStoredImage">
      <MemberSignature Language="C#" Value="public bool IsOSBasedOnStoredImage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsOSBasedOnStoredImage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnStoredImage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsOSBasedOnStoredImage As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsOSBasedOnStoredImage : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsOSBasedOnStoredImage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn das Betriebssystem der virtuellen Computerinstanz gespeichertes Bild basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWindowsAutoUpdateEnabled">
      <MemberSignature Language="C#" Value="public bool IsWindowsAutoUpdateEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWindowsAutoUpdateEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsAutoUpdateEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWindowsAutoUpdateEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWindowsAutoUpdateEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsAutoUpdateEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn dies ein Windows-VM ist und automatische Updates aktiviert andernfalls auf "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsWindowsVMAgentProvisioned">
      <MemberSignature Language="C#" Value="public bool IsWindowsVMAgentProvisioned { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsWindowsVMAgentProvisioned" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsVMAgentProvisioned" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsWindowsVMAgentProvisioned As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsWindowsVMAgentProvisioned : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.IsWindowsVMAgentProvisioned" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn dies ein Windows-VM und VM-Agent bereitgestellt wurde, andernfalls false wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ListNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfaces () As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfaces : unit -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSetVM.ListNetworkInterfaces " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die Netzwerkschnittstellen, die dieser Instanz der virtuellen Maschine zugeordnet wird.</return>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaceIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NetworkInterfaceIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NetworkInterfaceIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.NetworkInterfaceIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkInterfaceIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaceIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.NetworkInterfaceIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Ressourcen-ID der Netzwerkschnittstelle, die die virtuelle Computerinstanz zugeordnet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskCachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskCachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.OSDiskCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskCachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zwischenspeichern des Betriebssystem-Datenträgers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskId">
      <MemberSignature Language="C#" Value="public string OSDiskId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskId As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ressourcen-ID des verwalteten Datenträgers BS-Datenträger sichern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskName">
      <MemberSignature Language="C#" Value="public string OSDiskName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskName As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen des Betriebssystem-Datenträgers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskSizeInGB">
      <MemberSignature Language="C#" Value="public int OSDiskSizeInGB { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 OSDiskSizeInGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskSizeInGB" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskSizeInGB As Integer" />
      <MemberSignature Language="F#" Value="member this.OSDiskSizeInGB : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSDiskSizeInGB" />
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
            Ruft die Größe des Betriebssystem-Datenträgers ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile OSProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSProfile As OSProfile" />
      <MemberSignature Language="F#" Value="member this.OSProfile : Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OSProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Gastbetriebssystem-Profil einer VM-Instanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Betriebssystems.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSUnmanagedDiskVhdUri">
      <MemberSignature Language="C#" Value="public string OSUnmanagedDiskVhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSUnmanagedDiskVhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSUnmanagedDiskVhdUri As String" />
      <MemberSignature Language="F#" Value="member this.OSUnmanagedDiskVhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.OSUnmanagedDiskVhdUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Betriebssystem-Datenträger VHD-URI ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformImageReference">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference PlatformImageReference { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference PlatformImageReference" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PlatformImageReference" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlatformImageReference As ImageReference" />
      <MemberSignature Language="F#" Value="member this.PlatformImageReference : Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PlatformImageReference" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.ImageReference</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Verweis auf das Plattformimage, dass das Betriebssystem des virtuellen Computers Instanz basiert, wird Null zurückgegeben, wenn ein benutzerdefiniertes Image des Betriebssystems basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public void PowerOff ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PowerOff() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerOff" />
      <MemberSignature Language="VB.NET" Value="Public Sub PowerOff ()" />
      <MemberSignature Language="F#" Value="abstract member PowerOff : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.PowerOff " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beendet die VM-Instanz.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PowerOffAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PowerOffAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerOffAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.PowerOffAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Beendet die VM-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Die Observable-Objekt für die Aktion zum Herunterfahren.</return>
      </Docs>
    </Member>
    <Member MemberName="PowerState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.PowerState PowerState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PowerState As PowerState" />
      <MemberSignature Language="F#" Value="member this.PowerState : Microsoft.Azure.Management.Compute.Fluent.PowerState" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PowerState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.PowerState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Energiezustand des VM-Instanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryNetworkInterfaceId">
      <MemberSignature Language="C#" Value="public string PrimaryNetworkInterfaceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryNetworkInterfaceId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PrimaryNetworkInterfaceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryNetworkInterfaceId As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryNetworkInterfaceId : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.PrimaryNetworkInterfaceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ressourcen-ID des primären Netzwerkschnittstellen zugeordneten VM-Instanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshInstanceView">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView RefreshInstanceView() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.RefreshInstanceView" />
      <MemberSignature Language="VB.NET" Value="Public Function RefreshInstanceView () As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="abstract member RefreshInstanceView : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView" Usage="iVirtualMachineScaleSetVM.RefreshInstanceView " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Aktualisiert die Instanzansicht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Instanzansicht.</return>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reimage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Reimage" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage ()" />
      <MemberSignature Language="F#" Value="abstract member Reimage : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Reimage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Aktualisiert die Version des installierten Betriebssystems in der VM-Instanz.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.ReimageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.ReimageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Aktualisiert die Version des installierten Betriebssystems in der VM-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Die Observable-Objekt für die reimaging-Aktion.</return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die virtuelle Computerinstanz neu.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet die virtuelle Computerinstanz neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Um den Neustartvorgang Observable-Objekt.</return>
      </Docs>
    </Member>
    <Member MemberName="Size">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes Size" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Size" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Size As VirtualMachineSizeTypes" />
      <MemberSignature Language="F#" Value="member this.Size : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Size" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineSizeTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Größe des virtuellen Computers-Instanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.Sku Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As Sku" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.Models.Sku" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.Sku</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SKU Dies ist der virtuellen Computerinstanz SKU, die während des Erstellens der übergeordneten VM-Skalierungsgruppe verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iVirtualMachineScaleSetVM.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet die VM-Instanz.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSetVM.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet die VM-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Um die Startaktion Observable-Objekt.</return>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageProfile As StorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.StorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Speicherprofil der VM-Instanz ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoredImageUnmanagedVhdUri">
      <MemberSignature Language="C#" Value="public string StoredImageUnmanagedVhdUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StoredImageUnmanagedVhdUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StoredImageUnmanagedVhdUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoredImageUnmanagedVhdUri As String" />
      <MemberSignature Language="F#" Value="member this.StoredImageUnmanagedVhdUri : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.StoredImageUnmanagedVhdUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab die VHD-URI des benutzerdefinierten Images, dass das Betriebssystem des virtuellen Computers Instanz basiert, wird Null zurückgegeben, wenn das Betriebssystem auf Plattformimage basiert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnmanagedDataDisks">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;int,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;int32, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt; UnmanagedDataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.UnmanagedDataDisks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UnmanagedDataDisks As IReadOnlyDictionary(Of Integer, IVirtualMachineUnmanagedDataDisk)" />
      <MemberSignature Language="F#" Value="member this.UnmanagedDataDisks : System.Collections.Generic.IReadOnlyDictionary&lt;int, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.UnmanagedDataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.Int32,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineUnmanagedDataDisk&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die nicht verwaltete Daten-Datenträger, die zugeordneten VM-Instanz, durch LUN indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WindowsTimeZone">
      <MemberSignature Language="C#" Value="public string WindowsTimeZone { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string WindowsTimeZone" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.WindowsTimeZone" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WindowsTimeZone As String" />
      <MemberSignature Language="F#" Value="member this.WindowsTimeZone : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVM.WindowsTimeZone" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Zeitzone des virtuellen Computers Windows ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>