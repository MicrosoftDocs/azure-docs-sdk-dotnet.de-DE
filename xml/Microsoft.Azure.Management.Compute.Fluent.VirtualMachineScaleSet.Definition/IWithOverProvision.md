<Type Name="IWithOverProvision" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision">
  <TypeSignature Language="C#" Value="public interface IWithOverProvision" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOverProvision" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOverProvision" />
  <TypeSignature Language="F#" Value="type IWithOverProvision = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1d456-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition an, ob virtuelle Computer in der Menge Skalierung bereitstellen können.</span><span class="sxs-lookup"><span data-stu-id="1d456-101">The stage of a virtual machine scale set definition allowing to specify whether or not to over-provision virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutOverProvisioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithoutOverProvisioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithoutOverProvisioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithoutOverProvisioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutOverProvisioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithoutOverProvisioning : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithoutOverProvisioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1d456-102">Bereitstellung von virtuellen Maschinen deaktiviert zu stark an.</span><span class="sxs-lookup"><span data-stu-id="1d456-102">Disables over-provisioning of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1d456-103">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1d456-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOverProvision">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvision (bool enabled);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvision(bool enabled) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithOverProvision(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOverProvision (enabled As Boolean) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOverProvision : bool -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithOverProvision enabled" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="enabled" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="enabled">
            <span data-ttu-id="1d456-104">"True" festgelegt, wenn Over-0provisioning von virtuellen Computern in der Skala zu aktivieren, andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="1d456-104">True if enabling over-0provisioning of virtual machines in the scale set, otherwise false.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1d456-105">Aktiviert oder deaktiviert wird, zu stark Bereitstellung virtueller Maschinen in der Menge der Skala.</span><span class="sxs-lookup"><span data-stu-id="1d456-105">Enables or disables over-provisioning of virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1d456-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1d456-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOverProvisioning">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvisioning ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOverProvisioning() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOverProvision.WithOverProvisioning" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOverProvisioning () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOverProvisioning : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOverProvision.WithOverProvisioning " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1d456-107">Bereitstellung von virtuellen Computern aktiviert zu stark an.</span><span class="sxs-lookup"><span data-stu-id="1d456-107">Enables over-provisioning of virtual machines.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1d456-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1d456-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>