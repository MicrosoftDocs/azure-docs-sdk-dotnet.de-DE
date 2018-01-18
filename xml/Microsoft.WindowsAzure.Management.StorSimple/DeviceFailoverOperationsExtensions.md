<Type Name="DeviceFailoverOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceFailoverOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceFailoverOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceFailoverOperationsExtensions = class" />
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
            <span data-ttu-id="f41d6-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="f41d6-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListDCGroups">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse ListDCGroups(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroups : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroups (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f41d6-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span><span class="sxs-lookup"><span data-stu-id="f41d6-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="f41d6-103">Optional.</span><span class="sxs-lookup"><span data-stu-id="f41d6-103">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f41d6-104">Optional.</span><span class="sxs-lookup"><span data-stu-id="f41d6-104">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f41d6-105">Stellt die Antwort-Modell für DataContainerGroups Get-Aufruf dar</span><span class="sxs-lookup"><span data-stu-id="f41d6-105">Represents the response model for DataContainerGroups Get call</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListDCGroupsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt; ListDCGroupsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListDCGroupsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.ListDCGroupsAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DataContainerGroupsGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f41d6-106">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span><span class="sxs-lookup"><span data-stu-id="f41d6-106">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="f41d6-107">Optional.</span><span class="sxs-lookup"><span data-stu-id="f41d6-107">Optional.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f41d6-108">Optional.</span><span class="sxs-lookup"><span data-stu-id="f41d6-108">Optional.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="f41d6-109">Stellt die Antwort-Modell für DataContainerGroups Get-Aufruf dar</span><span class="sxs-lookup"><span data-stu-id="f41d6-109">Represents the response model for DataContainerGroups Get call</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trigger">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse Trigger(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Trigger : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.Trigger (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f41d6-110">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span><span class="sxs-lookup"><span data-stu-id="f41d6-110">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="f41d6-111">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-111">Required.</span></span> <span data-ttu-id="f41d6-112">Die Geräte-ID.</span><span class="sxs-lookup"><span data-stu-id="f41d6-112">The device identifier</span></span>
            </param>
        <param name="drRequest">
            <span data-ttu-id="f41d6-113">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-113">Required.</span></span> <span data-ttu-id="f41d6-114">Die Details der Anforderung des Geräts-Failover.</span><span class="sxs-lookup"><span data-stu-id="f41d6-114">The details of the device failover request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f41d6-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-115">Required.</span></span> <span data-ttu-id="f41d6-116">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f41d6-116">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f41d6-117">Gerätefailover auslösen.</span><span class="sxs-lookup"><span data-stu-id="f41d6-117">Trigger device failover.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f41d6-118">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="f41d6-118">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TriggerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt; TriggerAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest drRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member TriggerAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceFailoverOperationsExtensions.TriggerAsync (operations, deviceId, drRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.JobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="drRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceFailoverRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="f41d6-119">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span><span class="sxs-lookup"><span data-stu-id="f41d6-119">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceFailoverOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="f41d6-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-120">Required.</span></span> <span data-ttu-id="f41d6-121">Die Geräte-ID.</span><span class="sxs-lookup"><span data-stu-id="f41d6-121">The device identifier</span></span>
            </param>
        <param name="drRequest">
            <span data-ttu-id="f41d6-122">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-122">Required.</span></span> <span data-ttu-id="f41d6-123">Die Details der Anforderung des Geräts-Failover.</span><span class="sxs-lookup"><span data-stu-id="f41d6-123">The details of the device failover request.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="f41d6-124">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="f41d6-124">Required.</span></span> <span data-ttu-id="f41d6-125">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="f41d6-125">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="f41d6-126">Gerätefailover auslösen.</span><span class="sxs-lookup"><span data-stu-id="f41d6-126">Trigger device failover.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="f41d6-127">Dies ist die Antwort-Auftrag für alle Geräte Auftrag verknüpften Aufrufe</span><span class="sxs-lookup"><span data-stu-id="f41d6-127">This is the Job Response for all Device Job Related Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>