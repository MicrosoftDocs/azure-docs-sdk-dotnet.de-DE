<Type Name="IWithLinuxCreateUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxCreateUnmanaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxCreateUnmanaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCapacity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithComputerNamePrefix, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCustomData, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxCreateUnmanaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachineScaleSet), IDefinitionWithTags(Of IWithCreate), IWithUnmanagedCreate" />
  <TypeSignature Language="F#" Value="type IWithLinuxCreateUnmanaged = interface&#xA;    interface IWithUnmanagedCreate&#xA;    interface IWithUnmanagedDataDisk&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IIndexable&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithComputerNamePrefix&#xA;    interface IWithCapacity&#xA;    interface IWithUpgradePolicy&#xA;    interface IWithOverProvision&#xA;    interface IWithStorageAccount&#xA;    interface IWithCustomData&#xA;    interface IWithExtension&#xA;    interface IWithManagedServiceIdentity&#xA;    interface IBeta&#xA;    interface IWithBootDiagnostics&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUnmanagedCreate</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="11f9b-101">Festlegen des Status von einem Linux-VM-Skalierungsgruppe Definition enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden, sondern auch für andere optionalen Einstellungen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="11f9b-101">The stage of a Linux virtual machine scale set definition which contains all the minimum required inputs for the resource to be created, but also allows for any other optional settings to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged" Usage="iWithLinuxCreateUnmanaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxCreateUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey"><span data-ttu-id="11f9b-102">eine öffentliche SSH-Schlüssel in das PEM-Format.</span><span class="sxs-lookup"><span data-stu-id="11f9b-102">An SSH public key in the PEM format.</span></span></param>
        <summary>
            <span data-ttu-id="11f9b-103">Gibt den öffentlichen SSH-Schlüssel an.</span><span class="sxs-lookup"><span data-stu-id="11f9b-103">Specifies the SSH public key.</span></span>
            <span data-ttu-id="11f9b-104">Jeder Aufruf dieser Methode hinzugefügt die Liste der öffentliche Schlüssel des virtuellen Computers den angegebenen öffentlichen Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="11f9b-104">Each call to this method adds the given public key to the list of VM's public keys.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="11f9b-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="11f9b-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>