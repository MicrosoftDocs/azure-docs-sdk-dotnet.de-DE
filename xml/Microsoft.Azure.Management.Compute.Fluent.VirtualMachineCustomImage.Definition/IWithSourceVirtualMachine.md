<Type Name="IWithSourceVirtualMachine" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine">
  <TypeSignature Language="C#" Value="public interface IWithSourceVirtualMachine" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSourceVirtualMachine" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSourceVirtualMachine" />
  <TypeSignature Language="F#" Value="type IWithSourceVirtualMachine = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83ee8-101">Die Phase der Image-Definition, die virtuelle Quellmaschine auswählen können.</span><span class="sxs-lookup"><span data-stu-id="83ee8-101">The stage of the image definition allowing to choose source virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FromVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine (Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine virtualMachine);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine(class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine virtualMachine) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine.FromVirtualMachine(Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVirtualMachine (virtualMachine As IVirtualMachine) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromVirtualMachine : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate" Usage="iWithSourceVirtualMachine.FromVirtualMachine virtualMachine" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachine" Type="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachine" />
      </Parameters>
      <Docs>
        <param name="virtualMachine"><span data-ttu-id="83ee8-102">Virtuelle Quellmaschine.</span><span class="sxs-lookup"><span data-stu-id="83ee8-102">Source virtual machine.</span></span></param>
        <summary>
            <span data-ttu-id="83ee8-103">Die Quellen für OS-Abbild und Daten von Datenträgerimages dieses Bilds Datenträger verwendet des virtuellen Computers Betriebssystem und die Datenträger.</span><span class="sxs-lookup"><span data-stu-id="83ee8-103">Uses the virtual machine's OS and data disks as the sources for OS disk image and data disk images of this image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="83ee8-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="83ee8-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="FromVirtualMachine">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine (string virtualMachineId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate FromVirtualMachine(string virtualMachineId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithSourceVirtualMachine.FromVirtualMachine(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function FromVirtualMachine (virtualMachineId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member FromVirtualMachine : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate" Usage="iWithSourceVirtualMachine.FromVirtualMachine virtualMachineId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineCustomImage.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachineId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineId"><span data-ttu-id="83ee8-105">Quelle VM-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="83ee8-105">Source virtual machine resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="83ee8-106">Betriebssystem-Datenträger und Datenträger des virtuellen Computers verwendet als Quelle für Betriebssystem-Datenträger-Image und Daten von Datenträgerimages dieses Bilds.</span><span class="sxs-lookup"><span data-stu-id="83ee8-106">Uses the virtual machine's OS disk and data disks as the source for OS disk image and data disk images of this image.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="83ee8-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="83ee8-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>