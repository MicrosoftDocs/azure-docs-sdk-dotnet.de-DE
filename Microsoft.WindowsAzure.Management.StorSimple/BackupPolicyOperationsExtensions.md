<Type Name="BackupPolicyOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupPolicyOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupPolicyOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupPolicyOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupPolicyOperationsExtensions = class" />
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
            <span data-ttu-id="7470c-101">Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten</span><span class="sxs-lookup"><span data-stu-id="7470c-101">This is an RESTFul API to manage you StorSimple Objects</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginCreatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicy (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-102">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-102">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-103">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-103">Required.</span></span> <span data-ttu-id="7470c-104">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-104">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="7470c-105">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-105">Required.</span></span> <span data-ttu-id="7470c-106">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-106">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-107">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-107">Required.</span></span> <span data-ttu-id="7470c-108">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-108">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-109">Die BeginCreatingBackupPolicy-Vorgang erstellt eine neue Sicherungsrichtlinie für diesen bestimmten Datenträger mit der angegebenen Zeitpläne.</span><span class="sxs-lookup"><span data-stu-id="7470c-109">The BeginCreatingBackupPolicy operation creates a new backup policy for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-110">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-110">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginCreatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginCreatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginCreatingBackupPolicyAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-111">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-111">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-112">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-112">Required.</span></span> <span data-ttu-id="7470c-113">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-113">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="7470c-114">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-114">Required.</span></span> <span data-ttu-id="7470c-115">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-115">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-116">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-116">Required.</span></span> <span data-ttu-id="7470c-117">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-117">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-118">Die BeginCreatingBackupPolicy-Vorgang erstellt eine neue Sicherungsrichtlinie für diesen bestimmten Datenträger mit der angegebenen Zeitpläne.</span><span class="sxs-lookup"><span data-stu-id="7470c-118">The BeginCreatingBackupPolicy operation creates a new backup policy for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-119">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-119">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleting">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginDeleting(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeleting : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeleting (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-120">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-120">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-121">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-121">Required.</span></span> <span data-ttu-id="7470c-122">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-122">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-123">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-123">Required.</span></span> <span data-ttu-id="7470c-124">Die ID der Sicherungsrichtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="7470c-124">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-125">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-125">Required.</span></span> <span data-ttu-id="7470c-126">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-126">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-127">Beginnen Sie durch das Löschen einer Sicherungsrichtlinie, die durch die bereitgestellten PolicyId dargestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-127">Begin deleting a backup policy represented by the policyId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-128">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-128">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeletingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginDeletingAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginDeletingAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginDeletingAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-129">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-129">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-130">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-130">Required.</span></span> <span data-ttu-id="7470c-131">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-131">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-132">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-132">Required.</span></span> <span data-ttu-id="7470c-133">Die ID der Sicherungsrichtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="7470c-133">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-134">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-134">Required.</span></span> <span data-ttu-id="7470c-135">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-135">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-136">Beginnen Sie durch das Löschen einer Sicherungsrichtlinie, die durch die bereitgestellten PolicyId dargestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-136">Begin deleting a backup policy represented by the policyId provided.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-137">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-137">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicy">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdatingBackupPolicy(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicy : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicy (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-138">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-138">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-139">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-139">Required.</span></span> <span data-ttu-id="7470c-140">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-140">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-141">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-141">Required.</span></span> <span data-ttu-id="7470c-142">Die ID der Sicherungsrichtlinie zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7470c-142">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="7470c-143">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-143">Required.</span></span> <span data-ttu-id="7470c-144">Parameter für die Sicherungsrichtlinie Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-144">Parameters supplied to the Update Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-145">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-145">Required.</span></span> <span data-ttu-id="7470c-146">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-146">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-147">Mit dem Vorgang BeginUpdatingBackupPolicy aktualisiert eine Sicherungsrichtlinie, die durch PolicyId für dieses bestimmte Volume mit dem angegebenen Zeitpläne dargestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-147">The BeginUpdatingBackupPolicy operation updates a backup policy represented by policyId for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-148">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-148">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdatingBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdatingBackupPolicyAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdatingBackupPolicyAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.BeginUpdatingBackupPolicyAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-149">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-149">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-150">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-150">Required.</span></span> <span data-ttu-id="7470c-151">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-151">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-152">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-152">Required.</span></span> <span data-ttu-id="7470c-153">Die ID der Sicherungsrichtlinie zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7470c-153">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="7470c-154">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-154">Required.</span></span> <span data-ttu-id="7470c-155">Parameter für die Sicherungsrichtlinie Update zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-155">Parameters supplied to the Update Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-156">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-156">Required.</span></span> <span data-ttu-id="7470c-157">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-157">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7470c-158">Mit dem Vorgang BeginUpdatingBackupPolicy aktualisiert eine Sicherungsrichtlinie, die durch PolicyId für dieses bestimmte Volume mit dem angegebenen Zeitpläne dargestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-158">The BeginUpdatingBackupPolicy operation updates a backup policy represented by policyId for this given volume with the given schedules.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="7470c-159">Dies ist der Aufgabenantwort für alle asynchrone Aufrufe</span><span class="sxs-lookup"><span data-stu-id="7470c-159">This is the Task Response for all Async Calls</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Create(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Create (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-160">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-160">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-161">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-161">Required.</span></span> <span data-ttu-id="7470c-162">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-162">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="7470c-163">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-163">Required.</span></span> <span data-ttu-id="7470c-164">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-164">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-165">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-165">Required.</span></span> <span data-ttu-id="7470c-166">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-166">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-167">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-167">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; CreateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig backupPolicy, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.CreateAsync (operations, deviceId, backupPolicy, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="backupPolicy" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.NewBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-168">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-168">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-169">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-169">Required.</span></span> <span data-ttu-id="7470c-170">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-170">The device id for which the call will be made.</span></span>
            </param>
        <param name="backupPolicy">
            <span data-ttu-id="7470c-171">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-171">Required.</span></span> <span data-ttu-id="7470c-172">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-172">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-173">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-173">Required.</span></span> <span data-ttu-id="7470c-174">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-174">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-175">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-175">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Delete(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Delete (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-176">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-176">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-177">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-177">Required.</span></span> <span data-ttu-id="7470c-178">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-178">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-179">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-179">Required.</span></span> <span data-ttu-id="7470c-180">Die ID der Sicherungsrichtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="7470c-180">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-181">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-181">Required.</span></span> <span data-ttu-id="7470c-182">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-182">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-183">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-183">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; DeleteAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.DeleteAsync (operations, deviceId, policyId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-184">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-184">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-185">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-185">Required.</span></span> <span data-ttu-id="7470c-186">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-186">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-187">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-187">Required.</span></span> <span data-ttu-id="7470c-188">Die ID der Sicherungsrichtlinie zu löschen.</span><span class="sxs-lookup"><span data-stu-id="7470c-188">The backup policy ID to delete.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-189">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-189">Required.</span></span> <span data-ttu-id="7470c-190">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-190">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-191">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-191">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByName">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse GetBackupPolicyDetailsByName(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByName : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByName (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-192">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-192">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-193">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-193">Required.</span></span> <span data-ttu-id="7470c-194">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-194">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7470c-195">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-195">Required.</span></span> <span data-ttu-id="7470c-196">Der Name der Richtlinie zum Abrufen von Details zur Sicherungsrichtlinie durch.</span><span class="sxs-lookup"><span data-stu-id="7470c-196">The name of the policy to fetch backup policy details by.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-197">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-197">Required.</span></span> <span data-ttu-id="7470c-198">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-198">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-199">Das Antwort-Modell für die Liste der Sicherungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="7470c-199">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetBackupPolicyDetailsByNameAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt; GetBackupPolicyDetailsByNameAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyName, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetBackupPolicyDetailsByNameAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.GetBackupPolicyDetailsByNameAsync (operations, deviceId, policyName, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.GetBackupPolicyDetailsResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyName" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-200">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-200">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-201">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-201">Required.</span></span> <span data-ttu-id="7470c-202">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-202">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyName">
            <span data-ttu-id="7470c-203">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-203">Required.</span></span> <span data-ttu-id="7470c-204">Der Name der Richtlinie zum Abrufen von Details zur Sicherungsrichtlinie durch.</span><span class="sxs-lookup"><span data-stu-id="7470c-204">The name of the policy to fetch backup policy details by.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-205">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-205">Required.</span></span> <span data-ttu-id="7470c-206">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-206">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-207">Das Antwort-Modell für die Liste der Sicherungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="7470c-207">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse List(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.List (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-208">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-208">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-209">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-209">Required.</span></span> <span data-ttu-id="7470c-210">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-210">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-211">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-211">Required.</span></span> <span data-ttu-id="7470c-212">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-212">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-213">Das Antwort-Modell für die Liste der Sicherungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="7470c-213">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt; ListAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.ListAsync (operations, deviceId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.BackupPolicyListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-214">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-214">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-215">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-215">Required.</span></span> <span data-ttu-id="7470c-216">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-216">The device id for which the call will be made.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-217">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-217">Required.</span></span> <span data-ttu-id="7470c-218">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-218">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-219">Das Antwort-Modell für die Liste der Sicherungsrichtlinien.</span><span class="sxs-lookup"><span data-stu-id="7470c-219">The response model for the list of backup policies.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo Update(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.Update (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-220">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-220">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-221">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-221">Required.</span></span> <span data-ttu-id="7470c-222">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-222">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-223">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-223">Required.</span></span> <span data-ttu-id="7470c-224">Die ID der Sicherungsrichtlinie zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7470c-224">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="7470c-225">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-225">Required.</span></span> <span data-ttu-id="7470c-226">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-226">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-227">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-227">Required.</span></span> <span data-ttu-id="7470c-228">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-228">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-229">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-229">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync (this Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateAsync(class Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations operations, string deviceId, string policyId, class Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig policyInfo, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync(Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations,System.String,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations * string * string * Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.BackupPolicyOperationsExtensions.UpdateAsync (operations, deviceId, policyId, policyInfo, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations" RefType="this" />
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="policyId" Type="System.String" />
        <Parameter Name="policyInfo" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.UpdateBackupPolicyConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="7470c-230">Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span><span class="sxs-lookup"><span data-stu-id="7470c-230">Reference to the Microsoft.WindowsAzure.Management.StorSimple.IBackupPolicyOperations.</span></span>
            </param>
        <param name="deviceId">
            <span data-ttu-id="7470c-231">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-231">Required.</span></span> <span data-ttu-id="7470c-232">Die Geräte-Id für die der Aufruf erfolgt.</span><span class="sxs-lookup"><span data-stu-id="7470c-232">The device id for which the call will be made.</span></span>
            </param>
        <param name="policyId">
            <span data-ttu-id="7470c-233">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-233">Required.</span></span> <span data-ttu-id="7470c-234">Die ID der Sicherungsrichtlinie zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7470c-234">The backup policy ID to update.</span></span>
            </param>
        <param name="policyInfo">
            <span data-ttu-id="7470c-235">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-235">Required.</span></span> <span data-ttu-id="7470c-236">Parameter für die Sicherungsrichtlinie erstellen zur Verfügung gestellt.</span><span class="sxs-lookup"><span data-stu-id="7470c-236">Parameters supplied to the Create Backup Policy operation.</span></span>
            </param>
        <param name="customRequestHeaders">
            <span data-ttu-id="7470c-237">Erforderlich.</span><span class="sxs-lookup"><span data-stu-id="7470c-237">Required.</span></span> <span data-ttu-id="7470c-238">Die benutzerdefinierte Anforderungsheader Client verwenden muss.</span><span class="sxs-lookup"><span data-stu-id="7470c-238">The Custom Request Headers which client must use.</span></span>
            </param>
        <summary>To be added.</summary>
        <returns>
            <span data-ttu-id="7470c-239">Informationen über die asynchrone Aufgabe</span><span class="sxs-lookup"><span data-stu-id="7470c-239">Info about the async task</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>