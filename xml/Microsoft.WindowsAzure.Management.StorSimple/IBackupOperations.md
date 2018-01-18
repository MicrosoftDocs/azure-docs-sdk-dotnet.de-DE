<Type Name="IBackupOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations">
  <TypeSignature Language="C#" Value="public interface IBackupOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBackupOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBackupOperations" />
  <TypeSignature Language="F#" Value="type IBackupOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d0cc6-101">Alle Vorgänge im Zusammenhang mit der Sicherung</span><span class="sxs-lookup"><span data-stu-id="d0cc6-101">All Operations related to Backup</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginCreatingBackupAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreatingBackupAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginCreatingBackupAsync (deviceId, policyId, backupRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-102">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-102">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="d0cc6-103">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-103">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="d0cc6-104">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-104">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-105">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-105">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-106">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-106">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0cc6-107">Starten Sie einen Sicherungsvorgang für die PolicyId und BackupRequest angegeben.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-107">Begin a backup operation for the policyId and backupRequest specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d0cc6-108">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-108">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginDeletingAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeletingAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginDeletingAsync (deviceId, backupSetId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-109">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-109">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="d0cc6-110">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-110">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-111">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-111">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-112">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-112">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0cc6-113">Löschen eines Sicherungssatzes, dargestellt durch die bereitgestellten BackSetId zu beginnen.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-113">Begin deleting a backup set represented by the backSetId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d0cc6-114">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-114">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoringAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.BeginRestoringAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginRestoringAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iBackupOperations.BeginRestoringAsync (deviceId, backupDetailsForRestore, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-115">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-115">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="d0cc6-116">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-116">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-117">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-118">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-118">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0cc6-119">Starten Sie einen Sicherungssatz wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-119">Begin restoring a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d0cc6-120">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-120">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.CreateAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.CreateAsync (deviceId, policyId, backupRequest, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-121">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-121">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="d0cc6-122">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-122">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="d0cc6-123">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-123">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-124">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-124">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-125">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-125">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d0cc6-126">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-126">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.DeleteAsync(System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.DeleteAsync (deviceId, backupSetId, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-127">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-127">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="d0cc6-128">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-128">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-129">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-129">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-130">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-130">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d0cc6-131">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-131">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync (string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync(string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.GetAsync(System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;" Usage="iBackupOperations.GetAsync (deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-132">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-132">The device id for which the call will be made.</span></span>
            </param>
        <param name="filterType">
            <span data-ttu-id="d0cc6-133">Wenn IsAllSelected = "true", und geben Sie hier Datenträger oder BackupPolicy</span><span class="sxs-lookup"><span data-stu-id="d0cc6-133">If isAllSelected = true, then specify Volume or BackupPolicy here</span></span>
            </param>
        <param name="isAllSelected">
            <span data-ttu-id="d0cc6-134">Volume BackupPolicy oder sogar beides abrufen</span><span class="sxs-lookup"><span data-stu-id="d0cc6-134">To retrieve Volume or BackupPolicy or both</span></span>
            </param>
        <param name="filterValue">
            <span data-ttu-id="d0cc6-135">Wenn IsAllSelected = "true", und klicken Sie dann hier VolumeId oder BackupPolicy angeben</span><span class="sxs-lookup"><span data-stu-id="d0cc6-135">If isAllSelected = true then specify VolumeId or BackupPolicy here</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="d0cc6-136">StartTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="d0cc6-136">StartTime for filtering BackupSets</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="d0cc6-137">EndTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="d0cc6-137">EndTime for filtering BackupSets</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="d0cc6-138">Anzahl von Elementen übersprungen wird, im Rahmen der Paginierung</span><span class="sxs-lookup"><span data-stu-id="d0cc6-138">Number of elements to be skipped as part of pagination</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="d0cc6-139">Anzahl der Elemente in der aktuellen Seite abgerufen.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-139">Number of elements to retrieve in the current page</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-140">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-140">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-141">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-141">Cancellation token.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="d0cc6-142">Das Antwort-Modell für die Liste der Sicherungssätze.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-142">The response model for the list of BackupSets.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync (string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync(string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.RestoreAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestoreAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iBackupOperations.RestoreAsync (deviceId, backupDetailsForRestore, customRequestHeaders, cancellationToken)" />
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
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            <span data-ttu-id="d0cc6-143">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-143">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="d0cc6-144">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-144">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="d0cc6-145">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-145">The Custom Request Headers which client must use.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="d0cc6-146">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-146">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="d0cc6-147">Stellen Sie einen Sicherungssatz wieder her.</span><span class="sxs-lookup"><span data-stu-id="d0cc6-147">Restore a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="d0cc6-148">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="d0cc6-148">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>