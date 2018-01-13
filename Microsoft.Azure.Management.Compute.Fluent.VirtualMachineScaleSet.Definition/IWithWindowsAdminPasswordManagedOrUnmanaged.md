<Type Name="IWithWindowsAdminPasswordManagedOrUnmanaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminPasswordManagedOrUnmanaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminPasswordManagedOrUnmanaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Windows-VM-Skalierungsgruppe festgelegt Definition ermöglicht Benutzername des Administrators angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged WithAdminPassword (string adminPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged WithAdminPassword(string adminPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManagedOrUnmanaged.WithAdminPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminPassword (adminPassword As String) As IWithWindowsCreateManagedOrUnmanaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged" Usage="iWithWindowsAdminPasswordManagedOrUnmanaged.WithAdminPassword adminPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManagedOrUnmanaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminPassword">Das Kennwort des Administrators. Dadurch muss die Kriterien für das Kennwort des virtuellen Windows Azure-Computer befolgen.</param>
        <summary>
            Gibt das Administratorkennwort für den virtuellen Windows-Computer an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Phase, erstellt Windows-VM-Definition darstellt.</return>
      </Docs>
    </Member>
  </Members>
</Type>