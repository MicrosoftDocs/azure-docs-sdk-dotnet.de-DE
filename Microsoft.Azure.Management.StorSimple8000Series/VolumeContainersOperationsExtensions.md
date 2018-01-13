<Type Name="VolumeContainersOperationsExtensions" FullName="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VolumeContainersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VolumeContainersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VolumeContainersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VolumeContainersOperationsExtensions = class" />
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
            <span data-ttu-id="75588-101">Erweiterungsmethoden für VolumeContainersOperations.</span><span class="sxs-lookup"><span data-stu-id="75588-101">Extension methods for VolumeContainersOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer BeginCreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer BeginCreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, parameters As VolumeContainer, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdate (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-102">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-103">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-103">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-104">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-104">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="75588-105">Der volumecontainer hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="75588-105">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-106">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-106">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-107">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-107">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-108">Erstellt oder aktualisiert die Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-108">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginCreateOrUpdateAsync (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-109">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-109">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-110">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-110">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-111">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-111">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="75588-112">Der volumecontainer hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="75588-112">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-113">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-113">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-114">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-114">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-115">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-115">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-116">Erstellt oder aktualisiert die Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-116">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDelete(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDelete (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-117">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-117">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-118">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-118">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-119">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-119">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-120">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-120">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-121">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-121">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-122">Löscht den volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="75588-122">Deletes the volume container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.BeginDeleteAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;BeginDeleteAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-123">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-123">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-124">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-124">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-125">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-125">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-126">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-126">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-127">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-127">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-128">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-128">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-129">Löscht den volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="75588-129">Deletes the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer CreateOrUpdate (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer CreateOrUpdate(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, parameters As VolumeContainer, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdate (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-130">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-130">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-131">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-131">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-132">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-132">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="75588-133">Der volumecontainer hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="75588-133">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-134">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-134">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-135">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-135">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-136">Erstellt oder aktualisiert die Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-136">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer parameters, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.CreateOrUpdateAsync (operations, deviceName, volumeContainerName, parameters, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-137">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-137">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-138">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-138">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-139">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-139">The name of the volume container.</span></span>
            </param>
        <param name="parameters">
            <span data-ttu-id="75588-140">Der volumecontainer hinzugefügt oder aktualisiert werden soll.</span><span class="sxs-lookup"><span data-stu-id="75588-140">The volume container to be added or updated.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-141">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-141">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-142">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-142">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-143">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-143">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-144">Erstellt oder aktualisiert die Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-144">Creates or updates the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Delete(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; unit" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Delete (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-145">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-145">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-146">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-146">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-147">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-147">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-148">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-148">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-149">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-149">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-150">Löscht den volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="75588-150">Deletes the volume container.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.DeleteAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;DeleteAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-151">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-151">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-152">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-152">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-153">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-153">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-154">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-154">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-155">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-155">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-156">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-156">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-157">Löscht den volumecontainer.</span><span class="sxs-lookup"><span data-stu-id="75588-157">Deletes the volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer Get (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer Get(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Get(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As VolumeContainer" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.Get (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-158">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-158">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-159">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-159">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-160">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-160">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-161">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-161">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-162">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-162">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-163">Ruft die Eigenschaften des angegebenen Volume-Container Namens ab.</span><span class="sxs-lookup"><span data-stu-id="75588-163">Gets the properties of the specified volume container name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; GetAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; GetAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.GetAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.GetAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;GetAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-164">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-164">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-165">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-165">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-166">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-166">The name of the volume container.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-167">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-167">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-168">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-168">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-169">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-169">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-170">Ruft die Eigenschaften des angegebenen Volume-Container Namens ab.</span><span class="sxs-lookup"><span data-stu-id="75588-170">Gets the properties of the specified volume container name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDevice">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; ListByDevice (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt; ListByDevice(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDevice(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByDevice (operations As IVolumeContainersOperations, deviceName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of VolumeContainer)" />
      <MemberSignature Language="F#" Value="static member ListByDevice : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDevice (operations, deviceName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-171">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-171">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-172">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-172">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-173">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-173">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-174">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-174">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-175">Ruft alle volumecontainer in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="75588-175">Gets all the volume containers in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByDeviceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; ListByDeviceAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt; ListByDeviceAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDeviceAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByDeviceAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListByDeviceAsync (operations, deviceName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListByDeviceAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainer&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-176">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-176">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-177">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-177">The device name</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-178">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-178">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-179">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-179">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-180">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-180">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-181">Ruft alle volumecontainer in einem Gerät ab.</span><span class="sxs-lookup"><span data-stu-id="75588-181">Gets all the volume containers in a device.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinition">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt; ListMetricDefinition(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinition(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetricDefinition (operations As IVolumeContainersOperations, deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinition : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinition (operations, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-182">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-182">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-183">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-183">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-184">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-184">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-185">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-185">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-186">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-186">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-187">Ruft die metrikdefinitionen für den angegebenen Volume-Container ab.</span><span class="sxs-lookup"><span data-stu-id="75588-187">Gets the metric definitions for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricDefinitionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt; ListMetricDefinitionAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinitionAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricDefinitionAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricDefinitionAsync (operations, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListMetricDefinitionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-188">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-188">The operations group for this extension method.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-189">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-189">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-190">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-190">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-191">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-191">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-192">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-192">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-193">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-193">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-194">Ruft die metrikdefinitionen für den angegebenen Volume-Container ab.</span><span class="sxs-lookup"><span data-stu-id="75588-194">Gets the metric definitions for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetrics">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt; ListMetrics(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetrics(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListMetrics (operations As IVolumeContainersOperations, odataQuery As ODataQuery(Of MetricFilter), deviceName As String, volumeContainerName As String, resourceGroupName As String, managerName As String) As IEnumerable(Of Metrics)" />
      <MemberSignature Language="F#" Value="static member ListMetrics : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetrics (operations, odataQuery, deviceName, volumeContainerName, resourceGroupName, managerName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-195">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-195">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="75588-196">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="75588-196">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-197">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-197">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-198">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-198">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-199">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-199">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-200">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-200">The manager name</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-201">Ruft die Metriken für den angegebenen Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-201">Gets the metrics for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListMetricsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync (this Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt; ListMetricsAsync(class Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations operations, class Microsoft.Rest.Azure.OData.ODataQuery`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; odataQuery, string deviceName, string volumeContainerName, string resourceGroupName, string managerName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricsAsync(Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations,Microsoft.Rest.Azure.OData.ODataQuery{Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter},System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListMetricsAsync : Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations * Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt; * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;" Usage="Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions.ListMetricsAsync (operations, odataQuery, deviceName, volumeContainerName, resourceGroupName, managerName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.StorSimple8000Series.VolumeContainersOperationsExtensions/&lt;ListMetricsAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Metrics&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.StorSimple8000Series.IVolumeContainersOperations" RefType="this" />
        <Parameter Name="odataQuery" Type="Microsoft.Rest.Azure.OData.ODataQuery&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.MetricFilter&gt;" />
        <Parameter Name="deviceName" Type="System.String" />
        <Parameter Name="volumeContainerName" Type="System.String" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="managerName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="75588-202">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="75588-202">The operations group for this extension method.</span></span>
            </param>
        <param name="odataQuery">
            <span data-ttu-id="75588-203">OData-Parameter des Vorgangs angewendet.</span><span class="sxs-lookup"><span data-stu-id="75588-203">OData parameters to apply to the operation.</span></span>
            </param>
        <param name="deviceName">
            <span data-ttu-id="75588-204">Der Name des Laufwerks</span><span class="sxs-lookup"><span data-stu-id="75588-204">The device name</span></span>
            </param>
        <param name="volumeContainerName">
            <span data-ttu-id="75588-205">Der Name des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-205">The volume container name.</span></span>
            </param>
        <param name="resourceGroupName">
            <span data-ttu-id="75588-206">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="75588-206">The resource group name</span></span>
            </param>
        <param name="managerName">
            <span data-ttu-id="75588-207">Den Namen des Managers</span><span class="sxs-lookup"><span data-stu-id="75588-207">The manager name</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="75588-208">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="75588-208">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="75588-209">Ruft die Metriken für den angegebenen Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="75588-209">Gets the metrics for the specified volume container.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>