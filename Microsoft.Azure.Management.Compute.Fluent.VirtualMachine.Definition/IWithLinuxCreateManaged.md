<Type Name="IWithLinuxCreateManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxCreateManaged : Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxCreateManaged implements class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilityZone, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithBootDiagnostics, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithExtension, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedCreate, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedDataDisk, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithManagedServiceIdentity, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOSDiskSettings, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPlan, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithStorageAccount, class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithVMSize, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxCreateManaged&#xA;Implements IBeta, ICreatable(Of IVirtualMachine), IDefinitionWithTags(Of IWithCreate), IWithFromImageCreateOptionsManaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxCreateManaged = interface&#xA;    interface IWithFromImageCreateOptionsManaged&#xA;    interface IWithManagedCreate&#xA;    interface IWithManagedDataDisk&#xA;    interface IWithAvailabilityZone&#xA;    interface IBeta&#xA;    interface IWithCreate&#xA;    interface ICreatable&lt;IVirtualMachine&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;&#xA;    interface IWithOSDiskSettings&#xA;    interface IWithVMSize&#xA;    interface IWithStorageAccount&#xA;    interface IWithAvailabilitySet&#xA;    interface IWithSecondaryNetworkInterface&#xA;    interface IWithExtension&#xA;    interface IWithPlan&#xA;    interface IWithBootDiagnostics&#xA;    interface IWithManagedServiceIdentity" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithFromImageCreateOptionsManaged</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Phase der Definition eines Linux-VM enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden, sondern auch für andere optionalen Einstellungen angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSsh">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithSsh (string publicKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged WithSsh(string publicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged.WithSsh(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSsh (publicKey As String) As IWithLinuxCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithSsh : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged" Usage="iWithLinuxCreateManaged.WithSsh publicKey" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithLinuxCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="publicKey">der öffentliche SSH-Schlüssel im PEM-Format.</param>
        <summary>
            Gibt den öffentlichen SSH-Schlüssel an.
            Jeder Aufruf dieser Methode hinzugefügt die Liste der öffentliche Schlüssel des virtuellen Computers den angegebenen öffentlichen Schlüssel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, die erstellbaren Linux-VM-Definition darstellt.</return>
      </Docs>
    </Member>
  </Members>
</Type>