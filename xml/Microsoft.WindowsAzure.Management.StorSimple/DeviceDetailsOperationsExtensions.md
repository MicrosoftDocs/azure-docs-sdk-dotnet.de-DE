<Type Name="DeviceDetailsOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceDetailsOperationsExtensions = class" />
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
            <span data-ttu-id="97871-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="97871-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="97871-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-103">Required.</span></span> <span data-ttu-id="97871-104">Aktualisierte DeviceDetails.</span><span class="sxs-lookup"><span data-stu-id="97871-104">Updated DeviceDetails.</span></span> <span data-ttu-id="97871-105">Enthält die entsprechenden "DeviceID"</span><span class="sxs-lookup"><span data-stu-id="97871-105">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-106">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-106">Required.</span></span> <span data-ttu-id="97871-107">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-107">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="97871-108">Vorgang zum Aktualisieren von Gerätedetails entsprechend den Angaben von DeviceDetails zu starten.</span><span class="sxs-lookup"><span data-stu-id="97871-108">Begin task for updating device details as specified by deviceDetails.</span></span> <span data-ttu-id="97871-109">Der Task kann Klicken Sie dann auf den Abschluss mithilfe der zurückgegebenen Aufgabeninformationen nachverfolgt werden</span><span class="sxs-lookup"><span data-stu-id="97871-109">The task can then be tracked for completion using returned task information</span></span>
            </summary>
        <returns>
            <span data-ttu-id="97871-110">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="97871-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.BeginUpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-111">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="97871-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-112">Required.</span></span> <span data-ttu-id="97871-113">Aktualisierte DeviceDetails.</span><span class="sxs-lookup"><span data-stu-id="97871-113">Updated DeviceDetails.</span></span> <span data-ttu-id="97871-114">Enthält die entsprechenden "DeviceID"</span><span class="sxs-lookup"><span data-stu-id="97871-114">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-115">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-115">Required.</span></span> <span data-ttu-id="97871-116">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-116">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="97871-117">Vorgang zum Aktualisieren von Gerätedetails entsprechend den Angaben von DeviceDetails zu starten.</span><span class="sxs-lookup"><span data-stu-id="97871-117">Begin task for updating device details as specified by deviceDetails.</span></span> <span data-ttu-id="97871-118">Der Task kann Klicken Sie dann auf den Abschluss mithilfe der zurückgegebenen Aufgabeninformationen nachverfolgt werden</span><span class="sxs-lookup"><span data-stu-id="97871-118">The task can then be tracked for completion using returned task information</span></span>
            </summary>
        <returns>
            <span data-ttu-id="97871-119">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="97871-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.Get (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-120">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="97871-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-121">Required.</span></span> <span data-ttu-id="97871-122">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="97871-122">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-123">Required.</span></span> <span data-ttu-id="97871-124">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-124">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="97871-125">Das Antwort-Modell für die Gerätedetails.</span><span class="sxs-lookup"><span data-stu-id="97871-125">The response model for device details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.GetAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-126">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-126">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="97871-127">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-127">Required.</span></span> <span data-ttu-id="97871-128">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="97871-128">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-129">Required.</span></span> <span data-ttu-id="97871-130">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-130">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="97871-131">Das Antwort-Modell für die Gerätedetails.</span><span class="sxs-lookup"><span data-stu-id="97871-131">The response model for device details.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetails">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceDetails(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetails : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetails (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-132">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-132">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="97871-133">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-133">Required.</span></span> <span data-ttu-id="97871-134">Aktualisierte DeviceDetails.</span><span class="sxs-lookup"><span data-stu-id="97871-134">Updated DeviceDetails.</span></span> <span data-ttu-id="97871-135">Enthält die entsprechenden "DeviceID"</span><span class="sxs-lookup"><span data-stu-id="97871-135">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-136">Required.</span></span> <span data-ttu-id="97871-137">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-137">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="97871-138">Gerätedetails entsprechend den Angaben von DeviceDetails aktualisieren</span><span class="sxs-lookup"><span data-stu-id="97871-138">Update device details as specified by deviceDetails</span></span>
            </summary>
        <returns>
            <span data-ttu-id="97871-139">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="97871-139">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceDetailsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceDetailsAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest deviceDetails, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceDetailsAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceDetailsOperationsExtensions.UpdateDeviceDetailsAsync (operations, deviceDetails, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations" RefType="this" />
        <Parameter Name="deviceDetails" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.DeviceDetailsRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="97871-140">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span><span class="sxs-lookup"><span data-stu-id="97871-140">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceDetailsOperations.</span></span>
            </param>
        <param name="deviceDetails">
            <span data-ttu-id="97871-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-141">Required.</span></span> <span data-ttu-id="97871-142">Aktualisierte DeviceDetails.</span><span class="sxs-lookup"><span data-stu-id="97871-142">Updated DeviceDetails.</span></span> <span data-ttu-id="97871-143">Enthält die entsprechenden "DeviceID"</span><span class="sxs-lookup"><span data-stu-id="97871-143">Contains the corresponding DeviceId</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="97871-144">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="97871-144">Required.</span></span> <span data-ttu-id="97871-145">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="97871-145">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="97871-146">Gerätedetails entsprechend den Angaben von DeviceDetails aktualisieren</span><span class="sxs-lookup"><span data-stu-id="97871-146">Update device details as specified by deviceDetails</span></span>
            </summary>
        <returns>
            <span data-ttu-id="97871-147">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="97871-147">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>