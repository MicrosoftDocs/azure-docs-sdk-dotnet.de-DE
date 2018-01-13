<Type Name="ICloneVolumeOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations">
  <TypeSignature Language="C#" Value="public interface ICloneVolumeOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICloneVolumeOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICloneVolumeOperations" />
  <TypeSignature Language="F#" Value="type ICloneVolumeOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1c1a5-101">Alle Vorgänge im Zusammenhang mit CloneVolume (http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx für Weitere Informationen siehe)</span><span class="sxs-lookup"><span data-stu-id="1c1a5-101">All Operations related to CloneVolume  (see http://msdn.microsoft.com/en-us/library/azure/FILLTHISPART.aspx for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (string sourceDeviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(string sourceDeviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest triggerCloneRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.ICloneVolumeOperations.TriggerAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member TriggerAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="iCloneVolumeOperations.TriggerAsync (sourceDeviceId, triggerCloneRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDeviceId" Type="System.String" />
        <Parameter Name="triggerCloneRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.TriggerCloneRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="sourceDeviceId">
            <span data-ttu-id="1c1a5-102">Der Bezeichner für das Quellgerät aus der Klon wird ausgelöst werden soll</span><span class="sxs-lookup"><span data-stu-id="1c1a5-102">The identifier of the source device from which clone is to be triggered</span></span>
            </param>
        <param name="triggerCloneRequest">
            <span data-ttu-id="1c1a5-103">Die Parameter für den Klonvorgang erforderlich</span><span class="sxs-lookup"><span data-stu-id="1c1a5-103">The parameters required for clone operation</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="1c1a5-104">Der benutzerdefinierte Client verwenden, muss Anforderungsheader</span><span class="sxs-lookup"><span data-stu-id="1c1a5-104">The Custom Request Headers which client must use</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="1c1a5-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="1c1a5-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="1c1a5-106">Klonen einer backup-Element.</span><span class="sxs-lookup"><span data-stu-id="1c1a5-106">Clone a backup element.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="1c1a5-107">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="1c1a5-107">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>