<Type Name="BackupPoliciesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupPoliciesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupPoliciesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupPoliciesOperationsExtensions = class" />
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
            <span data-ttu-id="dcef0-101">Erweiterungsmethoden für BackupPoliciesOperations.</span><span class="sxs-lookup"><span data-stu-id="dcef0-101">Extension methods for BackupPoliciesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BackupNow">
      <MemberSignature Language="C#" Value="public static void BackupNow (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BackupNow(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BackupNow(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BackupNow (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, backupType As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BackupNow : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BackupNow (operations, deviceName, backupPolicyName, backupType, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-103">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-104">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-104">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="dcef0-105">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dcef0-105">The backup Type.</span></span> <span data-ttu-id="dcef0-106">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="dcef0-106">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-107">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-108">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-109">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-109">Backup the backup policy now.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BackupNowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BackupNowAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BackupNowAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BackupNowAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BackupNowAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BackupNowAsync (operations, deviceName, backupPolicyName, backupType, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;BackupNowAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-111">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-111">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-112">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-112">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="dcef0-113">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dcef0-113">The backup Type.</span></span> <span data-ttu-id="dcef0-114">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="dcef0-114">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-118">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-118">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackupNow">
      <MemberSignature Language="C#" Value="public static void BeginBackupNow (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginBackupNow(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginBackupNow(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginBackupNow (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, backupType As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginBackupNow : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginBackupNow (operations, deviceName, backupPolicyName, backupType, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-120">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-120">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-121">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-121">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="dcef0-122">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dcef0-122">The backup Type.</span></span> <span data-ttu-id="dcef0-123">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="dcef0-123">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-124">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-124">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-125">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-125">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-126">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-126">Backup the backup policy now.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginBackupNowAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginBackupNowAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginBackupNowAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string backupType, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginBackupNowAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginBackupNowAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginBackupNowAsync (operations, deviceName, backupPolicyName, backupType, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;BeginBackupNowAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="backupType" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-127">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-127">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-128">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-128">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-129">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-129">The backup policy name.</span></span>
            </param>
        <param name="backupType">
            <span data-ttu-id="dcef0-130">Die Art der Sicherung.</span><span class="sxs-lookup"><span data-stu-id="dcef0-130">The backup Type.</span></span> <span data-ttu-id="dcef0-131">Dies kann CloudSnapshot oder LocalSnapshot sein.</span><span class="sxs-lookup"><span data-stu-id="dcef0-131">This can be cloudSnapshot or localSnapshot.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-132">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-132">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-133">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-133">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-134">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-134">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-135">Sichern Sie nun die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-135">Backup the backup policy now.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, parameters As BackupPolicy, resourceGroupName As String, managerName As String) As BackupPolicy" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, backupPolicyName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-136">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-136">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-137">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-137">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-138">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="dcef0-138">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcef0-139">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-139">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-140">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-140">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-141">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-141">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-142">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-142">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, backupPolicyName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-143">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-143">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-144">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-144">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-145">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="dcef0-145">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcef0-146">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-146">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-148">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-148">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-150">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-150">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginDelete (operations, deviceName, backupPolicyName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-152">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-152">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-153">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-153">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-154">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-154">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-155">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-155">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-156">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-156">Deletes the backup policy.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.BeginDeleteAsync (operations, deviceName, backupPolicyName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-157">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-157">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-158">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-158">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-159">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-159">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-160">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-160">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-161">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-161">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-162">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-162">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-163">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-163">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, parameters As BackupPolicy, resourceGroupName As String, managerName As String) As BackupPolicy" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.CreateOrUpdate (operations, deviceName, backupPolicyName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-164">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-165">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-165">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-166">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="dcef0-166">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcef0-167">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-167">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-168">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-168">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-169">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-169">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-170">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-170">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, backupPolicyName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-171">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-172">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-172">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-173">Der Name der Sicherungsrichtlinie erstellt/aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="dcef0-173">The name of the backup policy to be created/updated.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="dcef0-174">Die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-174">The backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-175">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-175">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-176">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-176">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-177">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-177">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-178">Erstellt oder aktualisiert die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-178">Creates or updates the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.Delete (operations, deviceName, backupPolicyName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-179">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-179">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-180">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-180">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-181">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-181">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-182">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-182">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-183">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-183">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-184">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-184">Deletes the backup policy.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.DeleteAsync (operations, deviceName, backupPolicyName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-185">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-185">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-186">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-186">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-187">Der Name der Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-187">The name of the backup policy.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-188">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-188">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-189">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-189">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-191">Löscht die Sicherungsrichtlinie.</span><span class="sxs-lookup"><span data-stu-id="dcef0-191">Deletes the backup policy.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy Get (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy Get(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IBackupPoliciesOperations, deviceName As String, backupPolicyName As String, resourceGroupName As String, managerName As String) As BackupPolicy" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.Get (operations, deviceName, backupPolicyName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-192">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-193">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-193">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-194">Der Name der Sicherungsrichtlinie abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="dcef0-194">The name of backup policy to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-195">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-195">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-196">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-196">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-197">Ruft die Eigenschaften des angegebenen Namens ab.</span><span class="sxs-lookup"><span data-stu-id="dcef0-197">Gets the properties of the specified backup policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string backupPolicyName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.GetAsync (operations, deviceName, backupPolicyName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupPolicyName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-198">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-199">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-199">The device name</span></span>
            </param>
        <param name="backupPolicyName">
            <span data-ttu-id="dcef0-200">Der Name der Sicherungsrichtlinie abgerufen werden sollen.</span><span class="sxs-lookup"><span data-stu-id="dcef0-200">The name of backup policy to be fetched.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-201">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-202">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-202">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-204">Ruft die Eigenschaften des angegebenen Namens ab.</span><span class="sxs-lookup"><span data-stu-id="dcef0-204">Gets the properties of the specified backup policy name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IBackupPoliciesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of BackupPolicy)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-205">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-206">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-206">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-207">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-207">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-208">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-208">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-209">Ruft alle Sicherungsrichtlinien in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="dcef0-209">Gets all the backup policies in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupPoliciesOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupPolicy&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupPoliciesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="dcef0-210">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="dcef0-210">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="dcef0-211">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="dcef0-211">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="dcef0-212">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="dcef0-212">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="dcef0-213">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="dcef0-213">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="dcef0-214">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="dcef0-214">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="dcef0-215">Ruft alle Sicherungsrichtlinien in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="dcef0-215">Gets all the backup policies in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>