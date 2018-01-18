<Type Name="IWithOSDiskSettings" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings">
  <TypeSignature Language="C#" Value="public interface IWithOSDiskSettings" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithOSDiskSettings" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithOSDiskSettings" />
  <TypeSignature Language="F#" Value="type IWithOSDiskSettings = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="530c2-101">Die Phase der VM-Skalierungsgruppe festgelegt Definition, sodass Konfigurationen der Betriebssystem-Datenträger angeben.</span><span class="sxs-lookup"><span data-stu-id="530c2-101">The stage of a virtual machine scale set definition allowing to specify OS disk configurations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithOSDiskCaching">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOSDiskCaching (Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOSDiskCaching(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes cachingType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings.WithOSDiskCaching(Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskCaching (cachingType As CachingTypes) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskCaching : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskCaching cachingType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cachingType" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" />
      </Parameters>
      <Docs>
        <param name="cachingType"><span data-ttu-id="530c2-102">Der caching-Typ.</span><span class="sxs-lookup"><span data-stu-id="530c2-102">The caching type.</span></span></param>
        <summary>
            <span data-ttu-id="530c2-103">Gibt an, welche Zwischenspeichern für den Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="530c2-103">Specifies the caching type for the operating system disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="530c2-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="530c2-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithOSDiskName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOSDiskName (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate WithOSDiskName(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithOSDiskSettings.WithOSDiskName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithOSDiskName (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithOSDiskName : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate" Usage="iWithOSDiskSettings.WithOSDiskName name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="530c2-105">Der Name des Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="530c2-105">The OS disk name.</span></span></param>
        <summary>
            <span data-ttu-id="530c2-106">Gibt den Namen für den Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="530c2-106">Specifies the name for the OS disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="530c2-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="530c2-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>