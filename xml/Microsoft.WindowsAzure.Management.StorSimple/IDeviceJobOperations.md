<Type Name="IDeviceJobOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations">
  <TypeSignature Language="C#" Value="public interface IDeviceJobOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDeviceJobOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDeviceJobOperations" />
  <TypeSignature Language="F#" Value="type IDeviceJobOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="067a7-101">Alle Vorgänge im Zusammenhang mit Aufträgen Gerät</span><span class="sxs-lookup"><span data-stu-id="067a7-101">All Operations related to Device Jobs</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt; BeginUpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.BeginUpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;" Usage="iDeviceJobOperations.BeginUpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GuidTaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="067a7-102">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="067a7-102">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="067a7-103">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="067a7-103">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="067a7-104">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="067a7-104">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="067a7-105">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="067a7-105">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="067a7-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="067a7-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="067a7-107">Beginnen Sie die asynchrone Aufgabe, um einen Auftrag Gerät zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="067a7-107">Begin async task to update a device job.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="067a7-108">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="067a7-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync (string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int skip, int top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt; GetAsync(string deviceId, string jobType, string jobStatus, string jobId, string startTime, string endTime, int32 skip, int32 top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.GetAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.Int32,System.Int32,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * string * string * string * int * int * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;" Usage="iDeviceJobOperations.GetAsync (deviceId, jobType, jobStatus, jobId, startTime, endTime, skip, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetDeviceJobResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobType" Type="System.String" />
        <Parameter Name="jobStatus" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.Int32" />
        <Parameter Name="top" Type="System.Int32" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="067a7-109">Geräte-Id des Geräts von Aufträgen</span><span class="sxs-lookup"><span data-stu-id="067a7-109">Device id of device of jobs</span></span>
            </param>
        <param name="jobType">
            <span data-ttu-id="067a7-110">Typ des deviceJob</span><span class="sxs-lookup"><span data-stu-id="067a7-110">Type of deviceJob</span></span>
            </param>
        <param name="jobStatus">
            <span data-ttu-id="067a7-111">Status des Auftrags</span><span class="sxs-lookup"><span data-stu-id="067a7-111">Status of job</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="067a7-112">ID des Auftrags</span><span class="sxs-lookup"><span data-stu-id="067a7-112">Id of job</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="067a7-113">Startzeit des Auftrags, im ISO 8601-Format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="067a7-113">Job start time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="067a7-114">Endzeit der Auftrag, der im ISO 8601-format "Yyyy'-'MM'-'dd ' t' HH': 'mm':'ss '</span><span class="sxs-lookup"><span data-stu-id="067a7-114">Job end time, in ISO 8601 format 'yyyy'-'MM'-'dd'T'HH':'mm':'ss'</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="067a7-115">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="067a7-115">Pagination parameter.</span></span> <span data-ttu-id="067a7-116">Die Anzahl der zu überspringenden Einträge, d. h. der Index des ersten Eintrags zurückgegeben werden</span><span class="sxs-lookup"><span data-stu-id="067a7-116">The number of entries to skip, i.e. index of the first entry to be returned</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="067a7-117">Paginierung-Parameter.</span><span class="sxs-lookup"><span data-stu-id="067a7-117">Pagination parameter.</span></span> <span data-ttu-id="067a7-118">Die Anzahl von Einträgen zurückgegeben wird, nachdem die 'Skip' Anzahl von Einträgen übersprungen wird</span><span class="sxs-lookup"><span data-stu-id="067a7-118">The number of entries to return after skipping the 'skip' number of entries</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="067a7-119">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="067a7-119">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="067a7-120">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="067a7-120">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="067a7-121">Antwort-Modell abrufen Abfrage für einen Auftrag Gerät</span><span class="sxs-lookup"><span data-stu-id="067a7-121">Response model of Get Query for a Device Job</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceJobAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync (string deviceId, string jobId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDeviceJobAsync(string deviceId, string jobId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest updateRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IDeviceJobOperations.UpdateDeviceJobAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceJobAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iDeviceJobOperations.UpdateDeviceJobAsync (deviceId, jobId, updateRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="updateRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateDeviceJobRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="067a7-122">ID des Geräts</span><span class="sxs-lookup"><span data-stu-id="067a7-122">id of device</span></span>
            </param>
        <param name="jobId">
            <span data-ttu-id="067a7-123">ID des Auftrags zu aktualisieren</span><span class="sxs-lookup"><span data-stu-id="067a7-123">id of job to update</span></span>
            </param>
        <param name="updateRequest">
            <span data-ttu-id="067a7-124">Anfordern von Daten, die auszuführende Aktion enthält</span><span class="sxs-lookup"><span data-stu-id="067a7-124">Request data, contains the action to be taken</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="067a7-125">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="067a7-125">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="067a7-126">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="067a7-126">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="067a7-127">Aktualisieren eines Auftrags Gerät</span><span class="sxs-lookup"><span data-stu-id="067a7-127">Update a device job</span></span>
            </summary>
        <returns>
            <span data-ttu-id="067a7-128">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="067a7-128">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>