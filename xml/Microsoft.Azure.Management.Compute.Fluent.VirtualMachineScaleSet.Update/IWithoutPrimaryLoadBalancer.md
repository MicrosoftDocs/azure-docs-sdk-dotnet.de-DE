<Type Name="IWithoutPrimaryLoadBalancer" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer">
  <TypeSignature Language="C#" Value="public interface IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithoutPrimaryLoadBalancer" />
  <TypeSignature Language="F#" Value="type IWithoutPrimaryLoadBalancer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c712f-101">Die Phase der VM-Skalierungsgruppe festgelegt Update festlegen, dass um der öffentliche und interne Load Balancer aus der Konfiguration der primären Netzwerkschnittstellen zu entfernen.</span><span class="sxs-lookup"><span data-stu-id="c712f-101">The stage of a virtual machine scale set update allowing to remove the public and internal load balancer from the primary network interface configuration.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer.WithoutPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternalLoadBalancer () As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancer.WithoutPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c712f-102">Entfernt die Zuordnung zwischen den internen Lastenausgleich und die Konfiguration der primären Netzwerkschnittstelle an.</span><span class="sxs-lookup"><span data-stu-id="c712f-102">Removes the association between the internal load balancer and the primary network interface configuration.</span></span>
            <span data-ttu-id="c712f-103">Dadurch wird die Zuordnung zwischen der primären Netzwerkschnittstellenkonfiguration und alle Back-Ends und eingehenden NAT-Pools im Lastenausgleich entfernt.</span><span class="sxs-lookup"><span data-stu-id="c712f-103">This removes the association between primary network interface configuration and all the backends and inbound NAT pools in the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c712f-104">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="c712f-104">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply WithoutPrimaryInternetFacingLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithoutPrimaryLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryInternetFacingLoadBalancer () As IWithApply" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryInternetFacingLoadBalancer : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply" Usage="iWithoutPrimaryLoadBalancer.WithoutPrimaryInternetFacingLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithApply</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c712f-105">Entfernt die Zuordnung zwischen der Load-Balancer Internetzugriff und die Konfiguration der primären Netzwerkschnittstelle an.</span><span class="sxs-lookup"><span data-stu-id="c712f-105">Removes the association between the Internet-facing load balancer and the primary network interface configuration.</span></span>
            <span data-ttu-id="c712f-106">Dadurch wird die Zuordnung zwischen der primären Netzwerkschnittstellenkonfiguration und alle Back-Ends und eingehenden NAT-Pools im Lastenausgleich entfernt.</span><span class="sxs-lookup"><span data-stu-id="c712f-106">This removes the association between primary network interface configuration and all the backends and inbound NAT pools in the load balancer.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c712f-107">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="c712f-107">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>