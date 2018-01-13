<Type Name="VirtualDeviceOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualDeviceOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualDeviceOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualDeviceOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9cc90-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="9cc90-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Create(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.Create (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9cc90-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span><span class="sxs-lookup"><span data-stu-id="9cc90-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span></span>
            </param>
        <param name="virtualDeviceProvisioningInfo">
            <span data-ttu-id="9cc90-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9cc90-103">Required.</span></span> <span data-ttu-id="9cc90-104">Das virtuelle Gerät Bereitstellung Info.</span><span class="sxs-lookup"><span data-stu-id="9cc90-104">The Virtual device provisioning info.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9cc90-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9cc90-105">Required.</span></span> <span data-ttu-id="9cc90-106">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9cc90-106">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9cc90-107">Die virtuelles Gerät erstellen</span><span class="sxs-lookup"><span data-stu-id="9cc90-107">The Create Virtual Device</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9cc90-108">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9cc90-108">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo virtualDeviceProvisioningInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.VirtualDeviceOperationsExtensions.CreateAsync (operations, virtualDeviceProvisioningInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations" RefType="this" />
        <Parameter Name="virtualDeviceProvisioningInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.VirtualDeviceProvisioningInfo" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9cc90-109">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span><span class="sxs-lookup"><span data-stu-id="9cc90-109">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IVirtualDeviceOperations.</span></span>
            </param>
        <param name="virtualDeviceProvisioningInfo">
            <span data-ttu-id="9cc90-110">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9cc90-110">Required.</span></span> <span data-ttu-id="9cc90-111">Das virtuelle Gerät Bereitstellung Info.</span><span class="sxs-lookup"><span data-stu-id="9cc90-111">The Virtual device provisioning info.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="9cc90-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="9cc90-112">Required.</span></span> <span data-ttu-id="9cc90-113">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="9cc90-113">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9cc90-114">Die virtuelles Gerät erstellen</span><span class="sxs-lookup"><span data-stu-id="9cc90-114">The Create Virtual Device</span></span>
            </summary>
        <returns>
            <span data-ttu-id="9cc90-115">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="9cc90-115">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>