<Type Name="IWithSku" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku">
  <TypeSignature Language="C#" Value="public interface IWithSku" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSku" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSku" />
  <TypeSignature Language="F#" Value="type IWithSku = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="80d28-101">Die Phase der VM-Skalierungsgruppe festgelegt Update ermöglicht die SKU für die virtuellen Computer in der Menge der Skalierung ändern.</span><span class="sxs-lookup"><span data-stu-id="80d28-101">The stage of a virtual machine scale set update allowing to change the SKU for the virtual machines in the scale set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithSku (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku sku);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithSku(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku sku) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku.WithSku(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSku (sku As IVirtualMachineScaleSetSku) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithSku : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithSku.WithSku sku" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sku" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku" />
      </Parameters>
      <Docs>
        <param name="sku"><span data-ttu-id="80d28-102">Eine SKU aus der Liste der verfügbaren Größen für die virtuellen Computer in dieser Skala festgelegt.</span><span class="sxs-lookup"><span data-stu-id="80d28-102">A SKU from the list of available sizes for the virtual machines in this scale set.</span></span></param>
        <summary>
            <span data-ttu-id="80d28-103">Gibt die SKU für den virtuellen Computern in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="80d28-103">Specifies the SKU for the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="80d28-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="80d28-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithSku (Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes skuType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithSku(class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes skuType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithSku.WithSku(Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSku (skuType As VirtualMachineScaleSetSkuTypes) As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithSku : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithSku.WithSku skuType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="skuType" Type="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes" />
      </Parameters>
      <Docs>
        <param name="skuType"><span data-ttu-id="80d28-105">Die SKU-Typs.</span><span class="sxs-lookup"><span data-stu-id="80d28-105">The SKU type.</span></span></param>
        <summary>
            <span data-ttu-id="80d28-106">Gibt die SKU für den virtuellen Computern in der Menge der Skala an.</span><span class="sxs-lookup"><span data-stu-id="80d28-106">Specifies the SKU for the virtual machines in the scale set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="80d28-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="80d28-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>