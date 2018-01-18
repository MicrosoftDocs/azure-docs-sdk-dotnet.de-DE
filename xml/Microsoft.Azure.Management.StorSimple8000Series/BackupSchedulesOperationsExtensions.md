<Type Name="BackupSchedulesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupSchedulesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupSchedulesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupSchedulesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3f01a-101">Erweiterungsmethoden für BackupSchedulesOperations.</span><span class="sxs-lookup"><span data-stu-id="3f01a-101">Extension methods for BackupSchedulesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, parameters As BackupSchedule, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-103">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-104">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-104">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-105">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-105">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f01a-106">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-106">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-107">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-108">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-109">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-109">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-111">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-111">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-112">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-112">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-113">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-113">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f01a-114">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-114">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-118">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-118">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDelete (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-120">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-120">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-121">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-121">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-122">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-122">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-124">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-124">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-125">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-125">Deletes the backup schedule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.BeginDeleteAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-126">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-127">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-127">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-128">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-128">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-129">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-129">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-130">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-130">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-131">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-131">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-133">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-133">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, parameters As BackupSchedule, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdate (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-134">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-135">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-135">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-136">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-136">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-137">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-137">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f01a-138">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-138">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-139">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-140">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-140">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-141">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-141">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, backupPolicyName, backupScheduleName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-142">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-143">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-143">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-144">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-144">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-145">Der Name des Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-145">The backup schedule name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3f01a-146">Der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-146">The backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-148">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-148">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-150">Erstellt oder aktualisiert den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-150">Creates or updates the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Delete (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-152">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-152">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-153">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-153">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-154">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-154">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-155">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-156">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-156">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-157">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-157">Deletes the backup schedule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.DeleteAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-159">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-159">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-160">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-160">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-161">Der Name der Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-161">The name the backup schedule.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-162">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-163">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-163">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-165">Löscht den Sicherungszeitplan.</span><span class="sxs-lookup"><span data-stu-id="3f01a-165">Deletes the backup schedule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule Get (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule Get(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, backupScheduleName As String, resourceGroupName As String, managerName As String) As BackupSchedule" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.Get (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-166">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-167">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-167">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-168">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-168">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-169">Der Name der Sicherungszeitplan abgerufen werden sollen</span><span class="sxs-lookup"><span data-stu-id="3f01a-169">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-170">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-170">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-171">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-171">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-172">Ruft die Eigenschaften des angegebenen Sicherungszeitplan Namens ab.</span><span class="sxs-lookup"><span data-stu-id="3f01a-172">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string backupScheduleName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.GetAsync (operations, deviceName, backupPolicyName, backupScheduleName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupScheduleName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-173">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-174">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-174">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-175">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-175">The backup policy name.</span></span>
            </param>
        <param name="backupScheduleName">
            <span data-ttu-id="3f01a-176">Der Name der Sicherungszeitplan abgerufen werden sollen</span><span class="sxs-lookup"><span data-stu-id="3f01a-176">The name of the backup schedule to be fetched</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-177">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-178">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-180">Ruft die Eigenschaften des angegebenen Sicherungszeitplan Namens ab.</span><span class="sxs-lookup"><span data-stu-id="3f01a-180">Gets the properties of the specified backup schedule name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicy">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; ListByBackupPolicy (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt; ListByBackupPolicy(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicy(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByBackupPolicy (operations As IBackupSchedulesOperations, deviceName As String, backupPolicyName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of BackupSchedule)" />
      <MemberSignature Language="F#" Value="static member ListByBackupPolicy : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicy (operations, deviceName, backupPolicyName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-181">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-182">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-182">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-183">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-183">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-184">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-184">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-185">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-185">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-186">Ruft alle Sicherungszeitpläne in einer Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-186">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByBackupPolicyAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; ListByBackupPolicyAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt; ListByBackupPolicyAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicyAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByBackupPolicyAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions.ListByBackupPolicyAsync (operations, deviceName, backupPolicyName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupSchedulesOperationsExtensions/&lt;ListByBackupPolicyAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupSchedulesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3f01a-187">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3f01a-187">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3f01a-188">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3f01a-188">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="3f01a-189">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-189">The backup policy name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3f01a-190">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3f01a-190">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3f01a-191">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3f01a-191">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3f01a-192">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3f01a-192">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3f01a-193">Ruft alle Sicherungszeitpläne in einer Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="3f01a-193">Gets all the backup schedules in a backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>