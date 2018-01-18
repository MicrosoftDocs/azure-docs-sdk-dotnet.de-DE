<Type Name="IWithLinuxRootUsernameManaged" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged">
  <TypeSignature Language="C#" Value="public interface IWithLinuxRootUsernameManaged" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLinuxRootUsernameManaged" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLinuxRootUsernameManaged" />
  <TypeSignature Language="F#" Value="type IWithLinuxRootUsernameManaged = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="126ec-101">Die Phase der Linux-VM-Skalierungsgruppe festgelegt Definition ermöglicht SSH-Root-Benutzernamen angeben.</span><span class="sxs-lookup"><span data-stu-id="126ec-101">The stage of the Linux virtual machine scale set definition allowing to specify SSH root user name.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRootUsername">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged WithRootUsername (string rootUserName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged WithRootUsername(string rootUserName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootUsernameManaged.WithRootUsername(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRootUsername (rootUserName As String) As IWithLinuxRootPasswordOrPublicKeyManaged" />
      <MemberSignature Language="F#" Value="abstract member WithRootUsername : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged" Usage="iWithLinuxRootUsernameManaged.WithRootUsername rootUserName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithLinuxRootPasswordOrPublicKeyManaged</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="rootUserName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="rootUserName"><span data-ttu-id="126ec-102">Ein Stamm-Benutzername, befolgen die erforderlichen Benennungskonventionen für Linux-Benutzernamen.</span><span class="sxs-lookup"><span data-stu-id="126ec-102">A root user name following the required naming conventions for Linux user names.</span></span></param>
        <summary>
            <span data-ttu-id="126ec-103">Gibt die SSH-Root-Benutzername für den virtuellen Linux-Computer an.</span><span class="sxs-lookup"><span data-stu-id="126ec-103">Specifies the SSH root user name for the Linux virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="126ec-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="126ec-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>