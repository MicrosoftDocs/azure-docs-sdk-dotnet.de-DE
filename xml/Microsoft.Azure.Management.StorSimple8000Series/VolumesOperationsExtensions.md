<Type Name="VolumesOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VolumesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VolumesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VolumesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VolumesOperationsExtensions = class" />
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
            <span data-ttu-id="c17a0-101">Erweiterungsmethoden für VolumesOperations.</span><span class="sxs-lookup"><span data-stu-id="c17a0-101">Extension methods for VolumesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, parameters As Volume, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-103">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-104">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-104">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-105">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-105">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c17a0-106">Volume erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c17a0-106">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-107">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-107">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-108">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-108">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-109">Erstellt oder aktualisiert das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-109">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-110">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-110">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-111">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-111">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-112">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-112">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-113">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-113">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c17a0-114">Volume erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c17a0-114">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-115">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-115">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-116">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-116">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-117">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-117">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-118">Erstellt oder aktualisiert das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-118">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDelete (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-119">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-119">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-120">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-120">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-121">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-121">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-122">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-122">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-123">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-123">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-124">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-124">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-125">Löscht das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-125">Deletes the volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.BeginDeleteAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-126">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-126">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-127">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-127">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-128">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-128">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-129">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-129">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-130">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-130">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-131">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-131">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-132">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-132">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-133">Löscht das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-133">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, parameters As Volume, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdate (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-134">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-134">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-135">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-135">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-136">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-136">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-137">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-137">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c17a0-138">Volume erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c17a0-138">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-139">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-139">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-140">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-140">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-141">Erstellt oder aktualisiert das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-141">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.Volume,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.Volume * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, volumeContainerName, volumeName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-142">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-142">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-143">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-143">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-144">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-144">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-145">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-145">The volume name.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="c17a0-146">Volume erstellt oder aktualisiert werden.</span><span class="sxs-lookup"><span data-stu-id="c17a0-146">Volume to be created or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-147">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-147">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-148">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-148">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-149">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-149">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-150">Erstellt oder aktualisiert das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-150">Creates or updates the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Delete (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-152">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-152">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-153">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-153">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-154">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-154">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-155">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-155">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-156">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-156">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-157">Löscht das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-157">Deletes the volume.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.DeleteAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-159">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-159">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-160">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-160">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-161">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-161">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-162">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-162">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-163">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-163">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-164">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-164">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-165">Löscht das Volume.</span><span class="sxs-lookup"><span data-stu-id="c17a0-165">Deletes the volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.Volume Get (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume Get(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As Volume" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.Volume" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.Get (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.Volume</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-166">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-166">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-167">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-167">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-168">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-168">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-169">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-169">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-170">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-170">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-171">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-171">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-172">Gibt die Eigenschaften mit dem angegebenen Volume-Namen zurück.</span><span class="sxs-lookup"><span data-stu-id="c17a0-172">Returns the properties of the specified volume name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.GetAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-173">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-173">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-174">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-174">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-175">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-175">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-176">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-176">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-177">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-177">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-178">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-178">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-179">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-179">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-180">Gibt die Eigenschaften mit dem angegebenen Volume-Namen zurück.</span><span class="sxs-lookup"><span data-stu-id="c17a0-180">Returns the properties of the specified volume name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IVolumesOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Volume)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-181">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-181">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-182">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-182">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-183">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-183">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-184">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-184">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-185">Ruft alle Volumes in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-185">Retrieves all the volumes in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListByDeviceAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-186">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-186">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-187">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-187">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-188">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-188">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-189">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-189">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-190">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-190">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-191">Ruft alle Volumes in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-191">Retrieves all the volumes in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByVolumeContainer">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByVolumeContainer (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt; ListByVolumeContainer(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainer(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByVolumeContainer (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Volume)" />
      <MemberSignature Language="F#" Value="static member ListByVolumeContainer : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainer (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-192">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-192">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-193">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-193">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-194">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-194">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-195">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-195">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-196">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-196">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-197">Ruft alle Volumes im Volume-Container ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-197">Retrieves all the volumes in a volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByVolumeContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByVolumeContainerAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt; ListByVolumeContainerAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainerAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByVolumeContainerAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListByVolumeContainerAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListByVolumeContainerAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Volume&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-198">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-198">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-199">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-199">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-200">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-200">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-201">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-201">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-202">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-202">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-203">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-203">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-204">Ruft alle Volumes im Volume-Container ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-204">Retrieves all the volumes in a volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IVolumesOperations, deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinition (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-205">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-205">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-206">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-206">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-207">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-207">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-208">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-208">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-209">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-209">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-210">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-210">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-211">Ruft die metrikdefinitionen für das angegebene Volume ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-211">Gets the metric definitions for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-212">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-212">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-213">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-213">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-214">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-214">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-215">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-215">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-216">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-216">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-217">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-217">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-218">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-218">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-219">Ruft die metrikdefinitionen für das angegebene Volume ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-219">Gets the metric definitions for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IVolumesOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, volumeContainerName As String, volumeName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-220">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-220">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c17a0-221">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c17a0-221">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-222">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-222">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-223">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-223">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-224">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-224">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-225">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-225">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-226">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-226">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-227">Ruft die Metriken für das angegebene Volume ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-227">Gets the metrics for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string volumeName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, volumeContainerName, volumeName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumesOperationsExtensions/&lt;ListMetricsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumesOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="volumeName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="c17a0-228">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="c17a0-228">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="c17a0-229">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="c17a0-229">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="c17a0-230">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="c17a0-230">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="c17a0-231">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="c17a0-231">The volume container name.</span></span>
            </param>
        <param name="volumeName">
            <span data-ttu-id="c17a0-232">Der Name des Volumes.</span><span class="sxs-lookup"><span data-stu-id="c17a0-232">The volume name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="c17a0-233">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="c17a0-233">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="c17a0-234">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="c17a0-234">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="c17a0-235">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="c17a0-235">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="c17a0-236">Ruft die Metriken für das angegebene Volume ab.</span><span class="sxs-lookup"><span data-stu-id="c17a0-236">Gets the metrics for the specified volume.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>