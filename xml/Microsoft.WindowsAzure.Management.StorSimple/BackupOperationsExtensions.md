<Type Name="BackupOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupOperationsExtensions = class" />
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
            <span data-ttu-id="5664b-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="5664b-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackup">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackup (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackup(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackup(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackup : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackup (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-103">Required.</span></span> <span data-ttu-id="5664b-104">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-104">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="5664b-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-105">Required.</span></span> <span data-ttu-id="5664b-106">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-106">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="5664b-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-107">Required.</span></span> <span data-ttu-id="5664b-108">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="5664b-108">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-109">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-109">Required.</span></span> <span data-ttu-id="5664b-110">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-110">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-111">Starten Sie einen Sicherungsvorgang für die PolicyId und BackupRequest angegeben.</span><span class="sxs-lookup"><span data-stu-id="5664b-111">Begin a backup operation for the policyId and backupRequest specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-112">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-112">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingBackupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackupAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginCreatingBackupAsync (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-113">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-113">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-114">Required.</span></span> <span data-ttu-id="5664b-115">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-115">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="5664b-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-116">Required.</span></span> <span data-ttu-id="5664b-117">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-117">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="5664b-118">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-118">Required.</span></span> <span data-ttu-id="5664b-119">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="5664b-119">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-120">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-120">Required.</span></span> <span data-ttu-id="5664b-121">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-121">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-122">Starten Sie einen Sicherungsvorgang für die PolicyId und BackupRequest angegeben.</span><span class="sxs-lookup"><span data-stu-id="5664b-122">Begin a backup operation for the policyId and backupRequest specified.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-123">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-123">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeleting (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-124">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-124">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-125">Required.</span></span> <span data-ttu-id="5664b-126">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-126">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="5664b-127">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-127">Required.</span></span> <span data-ttu-id="5664b-128">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5664b-128">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-129">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-129">Required.</span></span> <span data-ttu-id="5664b-130">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-130">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-131">Löschen eines Sicherungssatzes, dargestellt durch die bereitgestellten BackSetId zu beginnen.</span><span class="sxs-lookup"><span data-stu-id="5664b-131">Begin deleting a backup set represented by the backSetId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-132">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-132">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginDeletingAsync (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-133">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-133">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-134">Required.</span></span> <span data-ttu-id="5664b-135">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-135">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="5664b-136">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-136">Required.</span></span> <span data-ttu-id="5664b-137">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5664b-137">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-138">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-138">Required.</span></span> <span data-ttu-id="5664b-139">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-139">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-140">Löschen eines Sicherungssatzes, dargestellt durch die bereitgestellten BackSetId zu beginnen.</span><span class="sxs-lookup"><span data-stu-id="5664b-140">Begin deleting a backup set represented by the backSetId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-141">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-141">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoring">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginRestoring (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginRestoring(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoring(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginRestoring : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoring (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-142">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-142">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-143">Required.</span></span> <span data-ttu-id="5664b-144">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-144">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="5664b-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-145">Required.</span></span> <span data-ttu-id="5664b-146">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5664b-146">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-147">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-147">Required.</span></span> <span data-ttu-id="5664b-148">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-148">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-149">Starten Sie einen Sicherungssatz wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="5664b-149">Begin restoring a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-150">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-150">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoringAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginRestoringAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoringAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginRestoringAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.BeginRestoringAsync (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-151">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-151">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-152">Required.</span></span> <span data-ttu-id="5664b-153">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-153">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="5664b-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-154">Required.</span></span> <span data-ttu-id="5664b-155">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5664b-155">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-156">Required.</span></span> <span data-ttu-id="5664b-157">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-157">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-158">Starten Sie einen Sicherungssatz wiederherstellen.</span><span class="sxs-lookup"><span data-stu-id="5664b-158">Begin restoring a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-159">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="5664b-159">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Create (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-160">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-160">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-161">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-161">Required.</span></span> <span data-ttu-id="5664b-162">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-162">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="5664b-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-163">Required.</span></span> <span data-ttu-id="5664b-164">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-164">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="5664b-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-165">Required.</span></span> <span data-ttu-id="5664b-166">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="5664b-166">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-167">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-167">Required.</span></span> <span data-ttu-id="5664b-168">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-168">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-169">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-169">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest backupRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.CreateAsync (operations, deviceId, policyId, backupRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="backupRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.BackupNowRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-170">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-170">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-171">Required.</span></span> <span data-ttu-id="5664b-172">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-172">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="5664b-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-173">Required.</span></span> <span data-ttu-id="5664b-174">Die Richtlinien-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-174">The policy id for which the call will be made.</span></span>
            </param>
        <param name="backupRequest">
            <span data-ttu-id="5664b-175">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-175">Required.</span></span> <span data-ttu-id="5664b-176">Parameter für die Sicherung beginnen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="5664b-176">Parameters supplied to the Begin Backup operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-177">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-177">Required.</span></span> <span data-ttu-id="5664b-178">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-178">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-179">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-179">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Delete (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-180">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-180">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-181">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-181">Required.</span></span> <span data-ttu-id="5664b-182">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-182">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="5664b-183">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-183">Required.</span></span> <span data-ttu-id="5664b-184">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5664b-184">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-185">Required.</span></span> <span data-ttu-id="5664b-186">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-186">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-187">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-187">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string backupSetId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.DeleteAsync (operations, deviceId, backupSetId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupSetId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-188">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-188">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-189">Required.</span></span> <span data-ttu-id="5664b-190">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-190">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupSetId">
            <span data-ttu-id="5664b-191">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-191">Required.</span></span> <span data-ttu-id="5664b-192">Die Sicherungssatz-ID zu löschen.</span><span class="sxs-lookup"><span data-stu-id="5664b-192">The backup set ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-193">Required.</span></span> <span data-ttu-id="5664b-194">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-194">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-195">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-195">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse Get (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse Get(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Get(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Get (operations, deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-196">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-196">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-197">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-197">Required.</span></span> <span data-ttu-id="5664b-198">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-198">The device id for which the call will be made.</span></span>
            </param>
        <param name="filterType">
            <span data-ttu-id="5664b-199">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-199">Optional.</span></span> <span data-ttu-id="5664b-200">Wenn IsAllSelected = "true", und geben Sie hier Datenträger oder BackupPolicy</span><span class="sxs-lookup"><span data-stu-id="5664b-200">If isAllSelected = true, then specify Volume or BackupPolicy here</span></span>
            </param>
        <param name="isAllSelected">
            <span data-ttu-id="5664b-201">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-201">Required.</span></span> <span data-ttu-id="5664b-202">Volume BackupPolicy oder sogar beides abrufen</span><span class="sxs-lookup"><span data-stu-id="5664b-202">To retrieve Volume or BackupPolicy or both</span></span>
            </param>
        <param name="filterValue">
            <span data-ttu-id="5664b-203">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-203">Optional.</span></span> <span data-ttu-id="5664b-204">Wenn IsAllSelected = "true", und klicken Sie dann hier VolumeId oder BackupPolicy angeben</span><span class="sxs-lookup"><span data-stu-id="5664b-204">If isAllSelected = true then specify VolumeId or BackupPolicy here</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="5664b-205">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-205">Optional.</span></span> <span data-ttu-id="5664b-206">StartTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="5664b-206">StartTime for filtering BackupSets</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="5664b-207">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-207">Optional.</span></span> <span data-ttu-id="5664b-208">EndTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="5664b-208">EndTime for filtering BackupSets</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="5664b-209">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-209">Optional.</span></span> <span data-ttu-id="5664b-210">Anzahl von Elementen übersprungen wird, im Rahmen der Paginierung</span><span class="sxs-lookup"><span data-stu-id="5664b-210">Number of elements to be skipped as part of pagination</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="5664b-211">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-211">Optional.</span></span> <span data-ttu-id="5664b-212">Anzahl der Elemente in der aktuellen Seite abgerufen.</span><span class="sxs-lookup"><span data-stu-id="5664b-212">Number of elements to retrieve in the current page</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-213">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-213">Required.</span></span> <span data-ttu-id="5664b-214">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-214">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-215">Das Antwort-Modell für die Liste der Sicherungssätze.</span><span class="sxs-lookup"><span data-stu-id="5664b-215">The response model for the list of BackupSets.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt; GetAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, string filterType, string isAllSelected, string filterValue, string startTime, string endTime, string skip, string top, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.GetAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,System.String,System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * string * string * string * string * string * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.GetAsync (operations, deviceId, filterType, isAllSelected, filterValue, startTime, endTime, skip, top, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="filterType" Type="System.String" />
        <Parameter Name="isAllSelected" Type="System.String" />
        <Parameter Name="filterValue" Type="System.String" />
        <Parameter Name="startTime" Type="System.String" />
        <Parameter Name="endTime" Type="System.String" />
        <Parameter Name="skip" Type="System.String" />
        <Parameter Name="top" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-216">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-216">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-217">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-217">Required.</span></span> <span data-ttu-id="5664b-218">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-218">The device id for which the call will be made.</span></span>
            </param>
        <param name="filterType">
            <span data-ttu-id="5664b-219">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-219">Optional.</span></span> <span data-ttu-id="5664b-220">Wenn IsAllSelected = "true", und geben Sie hier Datenträger oder BackupPolicy</span><span class="sxs-lookup"><span data-stu-id="5664b-220">If isAllSelected = true, then specify Volume or BackupPolicy here</span></span>
            </param>
        <param name="isAllSelected">
            <span data-ttu-id="5664b-221">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-221">Required.</span></span> <span data-ttu-id="5664b-222">Volume BackupPolicy oder sogar beides abrufen</span><span class="sxs-lookup"><span data-stu-id="5664b-222">To retrieve Volume or BackupPolicy or both</span></span>
            </param>
        <param name="filterValue">
            <span data-ttu-id="5664b-223">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-223">Optional.</span></span> <span data-ttu-id="5664b-224">Wenn IsAllSelected = "true", und klicken Sie dann hier VolumeId oder BackupPolicy angeben</span><span class="sxs-lookup"><span data-stu-id="5664b-224">If isAllSelected = true then specify VolumeId or BackupPolicy here</span></span>
            </param>
        <param name="startTime">
            <span data-ttu-id="5664b-225">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-225">Optional.</span></span> <span data-ttu-id="5664b-226">StartTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="5664b-226">StartTime for filtering BackupSets</span></span>
            </param>
        <param name="endTime">
            <span data-ttu-id="5664b-227">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-227">Optional.</span></span> <span data-ttu-id="5664b-228">EndTime zum Filtern der Sicherungssätze</span><span class="sxs-lookup"><span data-stu-id="5664b-228">EndTime for filtering BackupSets</span></span>
            </param>
        <param name="skip">
            <span data-ttu-id="5664b-229">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-229">Optional.</span></span> <span data-ttu-id="5664b-230">Anzahl von Elementen übersprungen wird, im Rahmen der Paginierung</span><span class="sxs-lookup"><span data-stu-id="5664b-230">Number of elements to be skipped as part of pagination</span></span>
            </param>
        <param name="top">
            <span data-ttu-id="5664b-231">Optional.</span><span class="sxs-lookup"><span data-stu-id="5664b-231">Optional.</span></span> <span data-ttu-id="5664b-232">Anzahl der Elemente in der aktuellen Seite abgerufen.</span><span class="sxs-lookup"><span data-stu-id="5664b-232">Number of elements to retrieve in the current page</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-233">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-233">Required.</span></span> <span data-ttu-id="5664b-234">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-234">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="5664b-235">Das Antwort-Modell für die Liste der Sicherungssätze.</span><span class="sxs-lookup"><span data-stu-id="5664b-235">The response model for the list of BackupSets.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Restore (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Restore(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Restore(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Restore : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.Restore (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-236">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-236">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-237">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-237">Required.</span></span> <span data-ttu-id="5664b-238">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-238">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="5664b-239">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-239">Required.</span></span> <span data-ttu-id="5664b-240">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5664b-240">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-241">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-241">Required.</span></span> <span data-ttu-id="5664b-242">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-242">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-243">Stellen Sie einen Sicherungssatz wieder her.</span><span class="sxs-lookup"><span data-stu-id="5664b-243">Restore a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-244">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-244">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; RestoreAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest backupDetailsForRestore, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.RestoreAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member RestoreAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupOperationsExtensions.RestoreAsync (operations, deviceId, backupDetailsForRestore, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupDetailsForRestore" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.RestoreBackupRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="5664b-245">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span><span class="sxs-lookup"><span data-stu-id="5664b-245">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="5664b-246">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-246">Required.</span></span> <span data-ttu-id="5664b-247">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="5664b-247">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupDetailsForRestore">
            <span data-ttu-id="5664b-248">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-248">Required.</span></span> <span data-ttu-id="5664b-249">Die Details der Sicherung wiederhergestellt werden.</span><span class="sxs-lookup"><span data-stu-id="5664b-249">The details of the backup to be restored.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="5664b-250">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="5664b-250">Required.</span></span> <span data-ttu-id="5664b-251">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="5664b-251">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5664b-252">Stellen Sie einen Sicherungssatz wieder her.</span><span class="sxs-lookup"><span data-stu-id="5664b-252">Restore a backup set.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5664b-253">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="5664b-253">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>