<Type Name="DeviceJobOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class DeviceJobOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit DeviceJobOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module DeviceJobOperationsExtensions" />
  <TypeSignature Language="F#" Value="type DeviceJobOperationsExtensions = class" />
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
            <span data-ttu-id="7ef55-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="7ef55-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse BeginUpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-103">Required.</span></span> <span data-ttu-id="7ef55-104">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="7ef55-104">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-105">Required.</span></span> <span data-ttu-id="7ef55-106">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="7ef55-106">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="7ef55-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-107">Required.</span></span> <span data-ttu-id="7ef55-108">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="7ef55-108">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-109">Required.</span></span> <span data-ttu-id="7ef55-110">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-110">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef55-111">Beginnen Sie die asynchrone Aufgabe, um einen Auftrag Gerät zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7ef55-111">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7ef55-112">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7ef55-112">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.BeginUpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-113">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-113">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-114">Required.</span></span> <span data-ttu-id="7ef55-115">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="7ef55-115">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-116">Required.</span></span> <span data-ttu-id="7ef55-117">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="7ef55-117">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="7ef55-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-118">Required.</span></span> <span data-ttu-id="7ef55-119">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="7ef55-119">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-120">Required.</span></span> <span data-ttu-id="7ef55-121">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-121">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef55-122">Beginnen Sie die asynchrone Aufgabe, um einen Auftrag Gerät zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7ef55-122">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7ef55-123">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7ef55-123">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.Get (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-124">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-124">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-125">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-125">Optional.</span></span> <span data-ttu-id="7ef55-126">Geräte-Id des Geräts von Aufträgen</span><span class="sxs-lookup"><span data-stu-id="7ef55-126">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="7ef55-127">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-127">Optional.</span></span> <span data-ttu-id="7ef55-128">Typ des deviceJob</span><span class="sxs-lookup"><span data-stu-id="7ef55-128">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="7ef55-129">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-129">Optional.</span></span> <span data-ttu-id="7ef55-130">Status des Auftrags</span><span class="sxs-lookup"><span data-stu-id="7ef55-130">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-131">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-131">Optional.</span></span> <span data-ttu-id="7ef55-132">ID des Auftrags</span><span class="sxs-lookup"><span data-stu-id="7ef55-132">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="7ef55-133">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-133">Optional.</span></span> <span data-ttu-id="7ef55-134">Startzeit des Auftrags, im ISO 8601-Format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="7ef55-134">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="7ef55-135">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-135">Optional.</span></span> <span data-ttu-id="7ef55-136">Endzeit der Auftrag, der im ISO 8601-format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="7ef55-136">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="7ef55-137">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-137">Required.</span></span> <span data-ttu-id="7ef55-138">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="7ef55-138">Pagination parameter.</span></span> <span data-ttu-id="7ef55-139">Die Anzahl der zu überspringenden Einträge, d. h. der Index des ersten Eintrags zurückgegeben werden</span><span class="sxs-lookup"><span data-stu-id="7ef55-139">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="7ef55-140">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-140">Required.</span></span> <span data-ttu-id="7ef55-141">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="7ef55-141">Pagination parameter.</span></span> <span data-ttu-id="7ef55-142">Die Anzahl von Einträgen zurückgegeben wird, nachdem die 'Skip' Anzahl von Einträgen übersprungen wird</span><span class="sxs-lookup"><span data-stu-id="7ef55-142">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-143">Required.</span></span> <span data-ttu-id="7ef55-144">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-144">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7ef55-145">Antwort-Modell abrufen Abfrage für einen Auftrag Gerät</span><span class="sxs-lookup"><span data-stu-id="7ef55-145">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.GetAsync (operations, deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-146">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-146">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-147">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-147">Optional.</span></span> <span data-ttu-id="7ef55-148">Geräte-Id des Geräts von Aufträgen</span><span class="sxs-lookup"><span data-stu-id="7ef55-148">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="7ef55-149">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-149">Optional.</span></span> <span data-ttu-id="7ef55-150">Typ des deviceJob</span><span class="sxs-lookup"><span data-stu-id="7ef55-150">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="7ef55-151">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-151">Optional.</span></span> <span data-ttu-id="7ef55-152">Status des Auftrags</span><span class="sxs-lookup"><span data-stu-id="7ef55-152">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-153">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-153">Optional.</span></span> <span data-ttu-id="7ef55-154">ID des Auftrags</span><span class="sxs-lookup"><span data-stu-id="7ef55-154">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="7ef55-155">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-155">Optional.</span></span> <span data-ttu-id="7ef55-156">Startzeit des Auftrags, im ISO 8601-Format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="7ef55-156">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="7ef55-157">Optional.</span><span class="sxs-lookup"><span data-stu-id="7ef55-157">Optional.</span></span> <span data-ttu-id="7ef55-158">Endzeit der Auftrag, der im ISO 8601-format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="7ef55-158">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="7ef55-159">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-159">Required.</span></span> <span data-ttu-id="7ef55-160">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="7ef55-160">Pagination parameter.</span></span> <span data-ttu-id="7ef55-161">Die Anzahl der zu überspringenden Einträge, d. h. der Index des ersten Eintrags zurückgegeben werden</span><span class="sxs-lookup"><span data-stu-id="7ef55-161">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="7ef55-162">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-162">Required.</span></span> <span data-ttu-id="7ef55-163">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="7ef55-163">Pagination parameter.</span></span> <span data-ttu-id="7ef55-164">Die Anzahl von Einträgen zurückgegeben wird, nachdem die 'Skip' Anzahl von Einträgen übersprungen wird</span><span class="sxs-lookup"><span data-stu-id="7ef55-164">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-165">Required.</span></span> <span data-ttu-id="7ef55-166">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7ef55-167">Antwort-Modell abrufen Abfrage für einen Auftrag Gerät</span><span class="sxs-lookup"><span data-stu-id="7ef55-167">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJob">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDeviceJob(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJob : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJob (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-168">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-169">Required.</span></span> <span data-ttu-id="7ef55-170">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="7ef55-170">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-171">Required.</span></span> <span data-ttu-id="7ef55-172">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="7ef55-172">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="7ef55-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-173">Required.</span></span> <span data-ttu-id="7ef55-174">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="7ef55-174">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-175">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-175">Required.</span></span> <span data-ttu-id="7ef55-176">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-176">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef55-177">Aktualisieren eines Auftrags Gerät</span><span class="sxs-lookup"><span data-stu-id="7ef55-177">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7ef55-178">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7ef55-178">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (this Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(class Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations operations, string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync(Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDeviceJobAsync : Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.DeviceJobOperationsExtensions.UpdateDeviceJobAsync (operations, deviceId, jobId, updateRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7ef55-179">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span><span class="sxs-lookup"><span data-stu-id="7ef55-179">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7ef55-180">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-180">Required.</span></span> <span data-ttu-id="7ef55-181">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="7ef55-181">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="7ef55-182">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-182">Required.</span></span> <span data-ttu-id="7ef55-183">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="7ef55-183">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="7ef55-184">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-184">Required.</span></span> <span data-ttu-id="7ef55-185">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="7ef55-185">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7ef55-186">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7ef55-186">Required.</span></span> <span data-ttu-id="7ef55-187">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7ef55-187">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7ef55-188">Aktualisieren eines Auftrags Gerät</span><span class="sxs-lookup"><span data-stu-id="7ef55-188">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7ef55-189">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7ef55-189">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>