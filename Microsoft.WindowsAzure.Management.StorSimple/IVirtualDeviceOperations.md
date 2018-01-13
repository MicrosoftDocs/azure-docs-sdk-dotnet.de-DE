<Type Name="IVirtualDeviceOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations">
  <TypeSignature Language="C#" Value="public interface IVirtualDeviceOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualDeviceOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualDeviceOperations" />
  <TypeSignature Language="F#" Value="type IVirtualDeviceOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3ea8f-101">Alle Vorgänge im Zusammenhang mit virtuellen Geräts</span><span class="sxs-lookup"><span data-stu-id="3ea8f-101">All Operations related to Virtual Device</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="iVirtualDeviceOperations.CreateAsync (virtualDeviceProvisioningInfo, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="virtualDeviceProvisioningInfo">
            <span data-ttu-id="3ea8f-102">Das virtuelle Gerät Bereitstellung Info.</span><span class="sxs-lookup"><span data-stu-id="3ea8f-102">The Virtual device provisioning info.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="3ea8f-103">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="3ea8f-103">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3ea8f-104">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3ea8f-104">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3ea8f-105">Die virtuelles Gerät erstellen</span><span class="sxs-lookup"><span data-stu-id="3ea8f-105">The Create Virtual Device</span></span>
            </summary>
        <returns>
            <span data-ttu-id="3ea8f-106">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="3ea8f-106">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>