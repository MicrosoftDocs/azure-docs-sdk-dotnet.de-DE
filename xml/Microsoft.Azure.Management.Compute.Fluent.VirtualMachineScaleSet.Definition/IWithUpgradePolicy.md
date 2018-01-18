<Type Name="IWithUpgradePolicy" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy">
  <TypeSignature Language="C#" Value="public interface IWithUpgradePolicy" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithUpgradePolicy" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithUpgradePolicy" />
  <TypeSignature Language="F#" Value="type IWithUpgradePolicy = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="81adf-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition ermöglicht die Upgraderichtlinie angeben.</span><span class="sxs-lookup"><span data-stu-id="81adf-101">The stage of a virtual machine scale set definition allowing to specify the upgrade policy.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithUpgradeMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithUpgradeMode (Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode upgradeMode);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithUpgradeMode(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode upgradeMode) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithUpgradePolicy.WithUpgradeMode(Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode)" />
      <MemberSignature Language="F#" Value="abstract member WithUpgradeMode : Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithUpgradePolicy.WithUpgradeMode upgradeMode" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="upgradeMode" Type="Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode" />
      </Parameters>
      <Docs>
        <param name="upgradeMode"><span data-ttu-id="81adf-102">Ein Upgraderichtlinie-Modus.</span><span class="sxs-lookup"><span data-stu-id="81adf-102">An upgrade policy mode.</span></span></param>
        <summary>
            <span data-ttu-id="81adf-103">Gibt an, dass die VM-Skalierungsgruppe Upgraderichtlinie Modus festgelegt.</span><span class="sxs-lookup"><span data-stu-id="81adf-103">Specifies the virtual machine scale set upgrade policy mode.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="81adf-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="81adf-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>