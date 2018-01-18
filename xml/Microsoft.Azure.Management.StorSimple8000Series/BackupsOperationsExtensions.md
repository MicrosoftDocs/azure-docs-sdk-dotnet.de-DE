<Type Name="BackupsOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class BackupsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit BackupsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module BackupsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type BackupsOperationsExtensions = class" />
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
            <span data-ttu-id="3b685-101">Erweiterungsmethoden für BackupsOperations.</span><span class="sxs-lookup"><span data-stu-id="3b685-101">Extension methods for BackupsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginClone">
      <MemberSignature Language="C#" Value="public static void BeginClone (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginClone(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginClone(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginClone (operations As IBackupsOperations, deviceName As String, backupName As String, backupElementName As String, parameters As CloneRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginClone : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginClone (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-103">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-104">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-104">The backup name.</span></span>
            </param>
        <param name="backupElementName">
            <span data-ttu-id="3b685-105">Der Name des backup-Element.</span><span class="sxs-lookup"><span data-stu-id="3b685-105">The backup element name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3b685-106">Das Klon-Request-Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b685-106">The clone request object.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-107">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-108">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-109">Klont die backup-Element als ein neues Volume an.</span><span class="sxs-lookup"><span data-stu-id="3b685-109">Clones the backup element as a new volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCloneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginCloneAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginCloneAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginCloneAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCloneAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginCloneAsync (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginCloneAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-111">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-111">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-112">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-112">The backup name.</span></span>
            </param>
        <param name="backupElementName">
            <span data-ttu-id="3b685-113">Der Name des backup-Element.</span><span class="sxs-lookup"><span data-stu-id="3b685-113">The backup element name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3b685-114">Das Klon-Request-Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b685-114">The clone request object.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-118">Klont die backup-Element als ein neues Volume an.</span><span class="sxs-lookup"><span data-stu-id="3b685-118">Clones the backup element as a new volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDelete (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-120">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-120">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-121">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-121">The backup name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-122">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-122">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-123">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-123">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-124">Löscht die Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="3b685-124">Deletes the backup.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginDeleteAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-125">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-125">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-126">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-126">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-127">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-127">The backup name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-128">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-128">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-129">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-129">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-130">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-130">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-131">Löscht die Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="3b685-131">Deletes the backup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestore">
      <MemberSignature Language="C#" Value="public static void BeginRestore (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginRestore(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestore(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginRestore (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginRestore : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestore (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-132">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-132">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-133">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-133">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-134">Der Name des Sicherungssatzes</span><span class="sxs-lookup"><span data-stu-id="3b685-134">The backupSet name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-135">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-135">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-136">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-136">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-137">Stellt die Sicherung auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="3b685-137">Restores the backup on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginRestoreAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginRestoreAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestoreAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestoreAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.BeginRestoreAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;BeginRestoreAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-138">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-138">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-139">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-139">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-140">Der Name des Sicherungssatzes</span><span class="sxs-lookup"><span data-stu-id="3b685-140">The backupSet name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-141">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-141">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-142">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-142">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-144">Stellt die Sicherung auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="3b685-144">Restores the backup on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Clone">
      <MemberSignature Language="C#" Value="public static void Clone (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Clone(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Clone(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Clone (operations As IBackupsOperations, deviceName As String, backupName As String, backupElementName As String, parameters As CloneRequest, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Clone : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Clone (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-145">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-146">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-146">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-147">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-147">The backup name.</span></span>
            </param>
        <param name="backupElementName">
            <span data-ttu-id="3b685-148">Der Name des backup-Element.</span><span class="sxs-lookup"><span data-stu-id="3b685-148">The backup element name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3b685-149">Das Klon-Request-Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b685-149">The clone request object.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-150">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-150">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-151">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-151">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-152">Klont die backup-Element als ein neues Volume an.</span><span class="sxs-lookup"><span data-stu-id="3b685-152">Clones the backup element as a new volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloneAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CloneAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CloneAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string backupElementName, class Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.CloneAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CloneAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.CloneAsync (operations, deviceName, backupName, backupElementName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;CloneAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="backupElementName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.CloneRequest" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-153">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-153">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-154">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-154">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-155">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-155">The backup name.</span></span>
            </param>
        <param name="backupElementName">
            <span data-ttu-id="3b685-156">Der Name des backup-Element.</span><span class="sxs-lookup"><span data-stu-id="3b685-156">The backup element name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="3b685-157">Das Klon-Request-Objekt.</span><span class="sxs-lookup"><span data-stu-id="3b685-157">The clone request object.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-158">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-158">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-159">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-159">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-160">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-160">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-161">Klont die backup-Element als ein neues Volume an.</span><span class="sxs-lookup"><span data-stu-id="3b685-161">Clones the backup element as a new volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Delete (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-162">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-162">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-163">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-163">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-164">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-164">The backup name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-165">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-165">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-166">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-166">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-167">Löscht die Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="3b685-167">Deletes the backup.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.DeleteAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-168">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-168">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-169">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-169">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-170">Der Name der Sicherungskopie.</span><span class="sxs-lookup"><span data-stu-id="3b685-170">The backup name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-171">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-171">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-172">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-172">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-173">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-173">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-174">Löscht die Sicherung an.</span><span class="sxs-lookup"><span data-stu-id="3b685-174">Deletes the backup.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IBackupsOperations, deviceName As String, resourceGroupName As String, managerName As String, Optional odataQuery As ODataQuery(Of BackupFilter) = null) As IPage(Of Backup)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName, odataQuery)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-175">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-175">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-176">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-176">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-177">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-178">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-178">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="3b685-179">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="3b685-179">OData parameters to apply to the operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-180">Ruft alle Sicherungen in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="3b685-180">Retrieves all the backups in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string resourceGroupName, string managerName, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; odataQuery, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, odataQuery, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.BackupFilter&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-181">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-182">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-182">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-183">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-184">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-184">The manager name</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="3b685-185">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="3b685-185">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-186">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-186">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-187">Ruft alle Sicherungen in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="3b685-187">Retrieves all the backups in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDeviceNext (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt; ListByDeviceNext(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNext(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDeviceNext (operations As IBackupsOperations, nextPageLink As String) As IPage(Of Backup)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNext : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-188">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3b685-189">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3b685-189">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-190">Ruft alle Sicherungen in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="3b685-190">Retrieves all the backups in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceNextAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt; ListByDeviceNextAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNextAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceNextAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.ListByDeviceNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;ListByDeviceNextAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Backup&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-191">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-191">The operations group for this extension method.</span></span>
            </param>
        <param name="nextPageLink">
            <span data-ttu-id="3b685-192">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="3b685-192">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-194">Ruft alle Sicherungen in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="3b685-194">Retrieves all the backups in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restore">
      <MemberSignature Language="C#" Value="public static void Restore (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Restore(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Restore(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Restore (operations As IBackupsOperations, deviceName As String, backupName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Restore : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.Restore (operations, deviceName, backupName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-195">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-196">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-196">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-197">Der Name des Sicherungssatzes</span><span class="sxs-lookup"><span data-stu-id="3b685-197">The backupSet name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-198">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-198">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-199">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-199">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-200">Stellt die Sicherung auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="3b685-200">Restores the backup on the device.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestoreAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task RestoreAsync (this Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task RestoreAsync(class Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations operations, string deviceName, string backupName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.RestoreAsync(Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestoreAsync : Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions.RestoreAsync (operations, deviceName, backupName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.BackupsOperationsExtensions/&lt;RestoreAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IBackupsOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="backupName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="3b685-201">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="3b685-201">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="3b685-202">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="3b685-202">The device name</span></span>
            </param>
        <param name="backupName">
            <span data-ttu-id="3b685-203">Der Name des Sicherungssatzes</span><span class="sxs-lookup"><span data-stu-id="3b685-203">The backupSet name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="3b685-204">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="3b685-204">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="3b685-205">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="3b685-205">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="3b685-206">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="3b685-206">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="3b685-207">Stellt die Sicherung auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="3b685-207">Restores the backup on the device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>