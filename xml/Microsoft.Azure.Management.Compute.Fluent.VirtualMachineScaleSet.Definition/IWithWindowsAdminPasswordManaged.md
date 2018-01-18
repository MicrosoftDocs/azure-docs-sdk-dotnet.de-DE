<Type Name="IWithWindowsAdminPasswordManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManaged">
  <TypeSignature Language="C#" Value="public interface IWithWindowsAdminPasswordManaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsAdminPasswordManaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsAdminPasswordManaged" />
  <TypeSignature Language="F#" Value="type IWithWindowsAdminPasswordManaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c370d-101">Die Phase der Windows-VM-Skalierungsgruppe festgelegt Definition ermöglicht Benutzername des Administrators angeben.</span><span class="sxs-lookup"><span data-stu-id="c370d-101">The stage of the Windows virtual machine scale set definition allowing to specify administrator user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAdminPassword">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithAdminPassword (string adminPassword);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged WithAdminPassword(string adminPassword) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsAdminPasswordManaged.WithAdminPassword(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAdminPassword (adminPassword As String) As IWithWindowsCreateManaged" />
      <MemberSignature Language="F#" Value="abstract member WithAdminPassword : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged" Usage="iWithWindowsAdminPasswordManaged.WithAdminPassword adminPassword" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithWindowsCreateManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="adminPassword" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="adminPassword"><span data-ttu-id="c370d-102">Das Kennwort des Administrators.</span><span class="sxs-lookup"><span data-stu-id="c370d-102">The administrator password.</span></span> <span data-ttu-id="c370d-103">Dadurch muss die Kriterien für das Kennwort des virtuellen Windows Azure-Computer befolgen.</span><span class="sxs-lookup"><span data-stu-id="c370d-103">This must follow the criteria for Azure Windows VM password.</span></span></param>
        <summary>
            <span data-ttu-id="c370d-104">Gibt das Administratorkennwort für den virtuellen Windows-Computer an.</span><span class="sxs-lookup"><span data-stu-id="c370d-104">Specifies the administrator password for the Windows virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c370d-105">Die Phase, erstellt Windows-VM-Definition darstellt.</span><span class="sxs-lookup"><span data-stu-id="c370d-105">The stage representing creatable Windows VM definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>